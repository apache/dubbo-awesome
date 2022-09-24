# 背景&需求
## 背景
当服务端暴露多个服务的时候，服务端根据address(ip:port)只会启动一次，且以端口为维度会创建对应的线程池（DefaultExecutorRepository）。
当前情况下，这些服务会共享该端口对应的线程池，如果某个服务出现问题从而占满线程池，会影响其他正常服务无法处理请求。

## 需求
增加服务间隔离的线程池管理方式，各自服务享用自己的线程池，互不干扰。
在原有 DefaultExecutorRepository 基础上，新增 IsolationExecutorRepository 线程池管理方式，根据 SPI 进行选择 **【以端口维度、服务间共享的线程池管理方式】** 还是 **【以服务为维度、服务间隔离的线程池管理方式】**

# 新增配置参数
- ApplicationConfig 新增 `String executor-management-mode` 参数（后面统一描述成mode），配置值为 default 和 isolation ，默认为 default。该参数即对应前面的两种线程池管理方式。
- ServiceConfig 新增 `Executor executor` 参数，用以服务间线程池隔离。可以 api、xml、annotation 的方式进行配置。

注1：当 mode = isolation 的时候，executor 配置才会生效，如果没有手动指定 executor，将使用 ProtocolConfig 的 thread pool 相关参数构建默认的 executor。

注2：api、xml、annotation 的配置示例/测试用例分别对应 apacha/dubbo 工程类： ApiIsolationTest、XmlIsolationTest、AnnotationIsolationTest

# 类调整说明-DefaultExecutorRepository

1.原先代码都是获取默认的SPI实例，即 DefaultExecutorRepository，现在调整为根据 mode 参数值 获取对应SPI实例。（详见 ExecutorRepository.getInstance 方法）

2.新增SPI类 IsolationExecutorRepository，父类为 DefaultExecutorRepository，前后 SPI name 分别为 isolation 和 default。

3.DefaultExecutorRepository#data 存储结构调整，原有二级key类型从 Integer 调整为 String。调整原因是 IsolationExecutorRepository 需要以 url.serviceKey 作为二级key存储，该类型是 String，且主要依靠该值做隔离。

4.方法调整说明
- `getExecutorSecondKey` 根据 side = provider or consumer 调用 getConsumerKey or getProviderKey 方法。
- `setThreadNameIfAbsent`   当某个服务暴露多个协议的时候，是不支持 服务+协议 维度线程池隔离的，所以如果 SPI为isolation，则 threadName 不会再有协议端口的信息。
- `createExecutor`                  SPI为default 则根据 protocolConfig 创建线程池，SPI为isolation 则从 url.attributes 获取线程池（见下面"注"）。
- `getConsumerKey`              消费端按照原有逻辑，不参与服务端线程池隔离。
- `getProviderKey`                  SPI为default 则获取 url.port 做隔离 ，SPI为isolation 则获取 url.serviceKey 做隔离。

注：当 ServiceConfig#export 的时候，因为 executor 属性类型是 Executor 类型，不是 String，无法直接以参数的方式附着在 url.parameters 上，所以会将 executor 添加到 url.attributes 中，并在 IsolationExecutorRepository#createExecutor 方法中获取。

# 隔离线程池的存储和获取

## 隔离线程池的存储
服务暴露的时候，根据各自服务的 url.serviceKey 存储在 IsolationExecutorRepository#data 中。

## 隔离线程池的获取
- 当消费者向提供者发起请求，服务端需要根据 **url.serviceKey/三元组** 取出对应的线程池，所以如何获取这份数据是最为关键的。可以发现 三元组 存储在网络数据包里的，如果是 dubbo 协议，则存在 Request#mdata 属性中，如果是 tri 协议，则可以从 headers 获取三元组信息。因此添加 DubboExecutorSupport 和 TriExecutorSupport 这两个类来解析并获取网络数据包的三元组信息，从而取出服务各自的线程池。
- dubbo 协议不同于 tri，tri 直接能从头部获取三元组，而 dubbo 协议的三元组是放在 Request#mdata 这部分未解码的消息体里的，而解码工作原先默认是放在 **提供者/服务/隔离线程池** 去做的，但是我们本身的目的又是去获取隔离线程池，这里就发生了矛盾，所以不得不做出一种让步：当识别到 mode = isolation，则直接在 netty io 线程进行解码。（详见 DubboCodec#isDecodeDataInIoThread）