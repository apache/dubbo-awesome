
## DefaultExecutorRepository 调整说明 

`ApplicationConfig` 新增 `String executor-management-mode` 参数 为了方便后面描述，记作 `mode`。

1.原先代码都是获取默认的 `SPI` 实例，即 `DefaultExecutorRepository`，现在调整为根据 `mode` 参数值 获取对应 `SPI` 实例。（详见 `ExecutorRepository.getInstance` 方法）

2.新增 `SPI` 类 `IsolationExecutorRepository`，父类为 `DefaultExecutorRepository`，前后 `SPI name` 分别为 `isolation` 和 `default`。

3.`DefaultExecutorRepository#data` 存储结构调整，原有二级key类型从 `Integer` 调整为 `String`。调整原因是 `IsolationExecutorRepository` 需要以 `url.serviceKey` 作为二级key存储，该类型是 `String`，且主要依靠该值做隔离。

4.方法调整说明
- `getExecutorSecondKey` 根据 `side = provider or consumer` 调用 `getConsumerKey` or `getProviderKey` 方法。
- `setThreadNameIfAbsent`   当某个服务暴露多个协议的时候，是不支持 服务+协议 维度线程池隔离的，所以如果 `SPI` 为 `isolation`，则 `threadName` 不会再有协议端口的信息。
- `createExecutor`                  `SPI` 为 `default` 则根据 `protocolConfig` 创建线程池，`SPI` 为 `isolation` 则从 `url.attributes` 获取线程池（见下面"注"）。
- `getConsumerKey`              消费端按照原有逻辑，不参与服务端线程池隔离。
- `getProviderKey`                  `SPI` 为 `default` 则获取 `url.port` 做隔离 ，`SPI` 为 `isolation` 则获取 `url.serviceKey` 做隔离。
- `getExecutorSupport`  主要是在服务端收到请求的时候协助获取线程池的，`SPI` 为 `default` 则返回 `DefaultExecutorSupport`，`SPI` 为 `isolation` 则根据 `url.protocol` 返回 `DubboIsolationExecutorSupport` 还是 `TriIsolationExecutorSupport`。

注：当 `ServiceConfig#export` 的时候，因为 `executor` 属性类型是 `Executor` 类型，不是 `String`，无法直接以参数的方式附着在 `url.parameters` 上，所以会将 `executor` 添加到 `url.attributes` 中（详见 `ServiceConfig#processServiceExecutor` 方法），并在 `IsolationExecutorRepository#createExecutor` 方法中获取。

# 隔离线程池的存储和获取

## 隔离线程池的存储
服务暴露的时候，根据各自服务的 `url.serviceKey` 存储在 `IsolationExecutorRepository#data` 中。

## 隔离线程池的获取
- 当消费者向提供者发起请求，服务端需要根据 **url.serviceKey/三元组** 取出对应的线程池，所以如何获取这份数据是最为关键的。可以发现 三元组 存储在网络数据包里的，如果是 `dubbo` 协议，则存在 `Request#mdata` 属性中，如果是 `triple` 协议，则可以从 `headers` 获取三元组信息。因此添加 `DubboIsolationExecutorSupport` 和 `TriIsolationExecutorSupport` 这两个类来解析并获取网络数据包的三元组信息，从而取出服务各自的线程池。
- `dubbo` 协议获取服务端线程池的逻辑在 `WrappedChannelHandler#getSharedExecutorService` 方法，会在这里使用 `DubboIsolationExecutorSupport#getExecutor`，triple协议则在 `TripleHttp2FrameServerHandler#onHeadersRead` 方法，会在这里使用 `TriIsolationExecutorSupport#getExecutor`。
- `dubbo` 协议不同于 `triple`，`triple` 直接能从头部获取三元组，而 `dubbo` 协议的三元组是放在` Request#mdata` 这部分未解码的消息体里的，而解码工作原先默认是放在 **提供者/服务/隔离线程池** 去做的，但是我们本身的目的又是去获取隔离线程池，这里就发生了矛盾，所以不得不做出一种让步：当识别到 `mode = isolation`，则直接在 `netty io` 线程进行解码。（详见 `DubboCodec#isDecodeDataInIoThread`）