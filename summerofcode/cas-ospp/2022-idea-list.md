## tls证书中心化管理滚动更新

Dubbo 作为一个 RPC 框架，在处理请求的时候只能无条件（即使采用 token 鉴权机制）认为来自对端的数据是可信的，因此如果 Dubbo 传输的数据被中间人截获，将对 Dubbo 请求的处理造成严重的影响。而基于连接的 TLS 机制可以很好的解决这个问题，但是当前 Dubbo 对于证书的管理较为简单，也无法适配动态证书生效的情况，因此需要一个中心化的组件来管控 Dubbo 的证书，基于可信通道下发认证信息。基于此 Dubbo 可以做到将节点的连接暴露的互联网中进行通信，降低节点间通信成本，和提高应用间可信程度。

参考：mTLS 机制

## 端口协议复用

一个端口支持多种协议可以使部署和运维更为方便，甚至在一些特殊的开发场景也能降低复杂度。例如：一个业务逻辑需要提供给不同语言、不同业务方进行调用。
当前大多数 rpc 框架均不支持该逻辑(包括 Dubbo)
以 Dubbo 举例，使用Triple 协议并开启所有默认服务，会开启如下默认端口
● Triple: 50051
● Metadata : 20880
● Qos: 22222
如果后续增加其他功能可能还会更多，这很不优雅，并且还启动了多个 Netty Server，造成了资源浪费。
如果本地需要测试，在不修改配置的情况下端口会冲突导致启动失败，体验很差。
目标
实现服务端同端口多协议暴露,将各种协议服务使用一种统一的方式使用同一个 Netty Server 进行暴露
● 将Qos 协议和 Triple 协议使用同一个端口暴露
● (Optional)将 Dubbo 的其他协议进行接入
1. 对于协议切换/架构升级的场景，通常需要同时暴露多个协议，单端口多协议能最大程度上带来运维的便捷性。
2. 从后端开发的角度一套业务代码加少许配置就能暴露多个端口也能带来降低开发成本
   目前 Dubbo 支持一个应用对外发布多种 RPC 协议，但这些 RPC 协议都需要独立占用一个服务端端口，另外 Dubbo QoS 也同样占用了一个端口。维护这些端口的监听需要消耗一定的资源，同时暴露多端口对于运维也存在一定复杂度，如 VIP /域名等。因此可以通过在同一个端口支持多种复用协议来降低复杂度，提高易用性。
   Background
   One port supports multiple protocols, which makes deployment and operation and maintenance more convenient and simple, and even reduces complexity in special development scenarios. For example, a business logic needs to be provided to different languages and different business parties for invocation.
   Most current RPC frameworks do not support this logic (including Dubbo).
   Taking Dubbo as an example, using the Triple protocol and enabled all default services will open the following default ports.
   ● Triple: 50051
   ● Metadata : 20880
   ● Qos: 22222
   If other functions are added in the future, there may be more, which is very inelegant, and multiple Netty Servers are also started, resulting in a waste of resources.
   If you need to test locally, the port conflict will cause the startup to fail without modifying the configuration, and the experience is very poor.
   Goal
   Implement multi-protocol exposure on the same port on the server side, and expose various protocol services using the same Netty Server in a unified way.
   ● Expose the QoS protocol and the Triple protocol using the same port
   ● (optional)Implement other protocols of Dubbo in this way.
   Meaning
   ● Start the various protocol services in a unified manner
   ● Support the same port exposed multiple protocols
   Before
   ● Netty

## 优雅下线
   对于部署了 Dubbo 服务的应用，由于应用发布需要重启进程，这个时候很多在途请求会由于进程的关闭而失败。因此 Dubbo 需要一种机制，在应用进程退出前通知所有的消费端不再发起新的请求，同时等待所有在途请求结束后再关闭进程。

## 完善故障排查机制与流程

当前 Dubbo 在使用的时候由于环境等种种原因，可能会出现如地址找不到、请求超时等异常。在大多数地方都有日志进行记录，本项目希望能为 Dubbo 提供一种快速的故障排查机制，包括但不限于在日志中透出排查网页信息、故障排查码，亦或者是自动感知上下文情况自动分析获取解决办法等。

admin api 迁移 qos 去中心化管控

Dubbo 拥有多种治理规则，如基于标签路由等，这些规则都是基于 Dubbo Admin 中心化进行管控。本题目希望将 Dubbo Admin 的 API 迁移到 Dubbo QoS 中，以此来达到不需要部署 Dubbo Admin 的后端程序即可对集群进行管控的目的。

## 对外暴露的 API 信息控制

在 Dubbo 版本迭代过程中，内部相互依赖的接口签名很容易被改动。但是这些仅 Dubbo 内部使用的 API 很多被用户误使用。为了更好地控制 Dubbo 对外暴露的 API 信息，Dubbo 希望将 API 分类为三种类型：暴露给用户开放使用的、内部 Dubbo 使用的、单元测试使用的。基于此在 Dubbo 编译的时候进行强制卡点，避免用户依赖内部使用的 API。

参考：Guava 的 VisibleForTesting 和 kolin 的 OptIn、JDK9 中开始提供的 module 机制

## dubbo-website 界面交互优化


## 性能调优：Profiling & Benchmark
在选型 RPC 框架时，性能是用户关心的一个核心因素，好的 RPC 框架一方面可以减少长尾请求，提供可预测的稳定响应时间，另一方面是单次调用响应时间最少。 这对于提升终端用户的体验以及降低界面加载速度来说是至关重要的。
从框架内部看，对于一个成熟的框架，内部也需要通过微基准测试的方式来保证内部处理是趋向最优的。这样在发布版本或提交 PR 时，能够简单直观的发现框架的性能是否有所下降，也能更快的定位到修改点对最终性能的影响。通过这种方式也能鼓励那些喜欢性能调优的外部人员参与到社区内部，来为开源社区贡献自己的一份力量，从而进一步促进社区的稳定发展和运行。
目前 Dubbo 缺少全局上和框架内部的性能数据。提供完善的性能测试套件和微基准测试套件能够给所有 Dubbo 用户和开发者更加直观的理解 Dubbo 的性能，并写出性能友好的代码。Benchamrk 能够方便用户调研框架以及开发者进行框架开发和性能调优，有利于框架的发展和让用户使用 Dubbo。

目标：
增加 Dubbo Java/ GO 的  benchmark ，包括但不限于 Triple / Dubbo  协议 / 内部框架实现，方式可以是微基准测试或提供 Profiling 的工具/脚本。


## Dubbo Reactive Stream
Reactive Stream 提供了一套标准的异步流处理 API， 在能够让应用写出事件驱动的程序的同时，也通过 backpressure 的方式保证了节点的稳定。Triple 协议在通信协议层面为 Dubbo 框架增加了流式场景的支持，在此基础上能够实现上层包括大文件传输和推送机制的业务需求。但目前的用户 API 较为原始，需要用户实现 StreamObserver 。而 Reactive Stream 作为反应式编程的事实标准，反压策略也能最大程度的保证处理大规模流数据时不会产生 Buffer Overflow 。Dubbo + Reactive Stream Stub的组合模式可以给用户带来最方便的流式使用方式以及全链路异步性能提升。

目标
Dubbo Compiler 的 code generator  支持生成  Reative Stream Stub API ，如 reactor / rxjava ，提供相应使用文档和实例，支持 backpressure

## Triple stub generator
### Describe the proposal
Gradle is a promising build tool for modern jvm language users, we shoulde support it when users using dubbo.
Dubbo has a maven compiler plugin for generating protos, but the [protobuf-gradle-plugin](https://github.com/google/protobuf-gradle-plugin) does not support specifing `MainClass` . So Dubbo's compiler can not work with gradle. Hoping anyone can help to fix it.

Here are some candidate solutions
- Publish multiple maven plugins with determined `MainClass`
- Write a build script template for generating Dubbo proto files
- Write a plugin like [akka](https://plugins.gradle.org/plugin/com.lightbend.akka.grpc.gradle)
- Support `MainClass` in `protobuf-gradle-plugin`



