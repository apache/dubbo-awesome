# Dubbo Mesh (draft)
* Authors: Zhongming Hua, Jun Liu

## Objective
## Background
## Related Proposals
## Proposal
### 场景
1. 场景一（适用不具备Dubbo SDK定制能力，并且完全没有接入Mesh的用户群体）：Sidecar仅托管服务发现能力以及进出口流量，该群体有三种分支场景：
   ○ 希望增加Sidecar组件，来完成Mesh改造。Sidecar仍然发现原有的注册中心（非kubernetes）内的服务，需要定制控制面来适配第三方注册中心。
   ○ 希望增加Sidecar组件，来完成Mesh改造。服务注册想要切换到控制面官方支持的注册中心，比如istio支持Kubernetes等，此时可以选择采用Dubbo内的 Kubernetes Registry方案。Sidecar发现Kubernetes内的服务。
   ○ 不希望增加Sidecar，来完成Mesh改造。
2. 场景二（适用已经具备对 Dubbo SDK、数据面、控制面的定制能力，并且完全没有接入Mesh的用户群体）：已经基于目前Dubbo版本，做了不同于社区方案的kubernetes 服务注册，比如服务注册模型在kubernetes中的存储模型和存储方式将不一定按照dubbo内的方案来执行。
   ○ 希望增加Sidecar组件，对接istio、Envoy等，来完成Mesh改造。
   ○ 希望不增加Sidecar组件，来完成Mesh改造。

### Mesh模式
   ● 完全Proxy Mesh模式
   ● 主次模式：Proxy Mesh回切到Proxyless Mesh模式（两种并存，主Proxy Mesh，次Proxyless Mesh）
   ● 完全Proxyless Mesh模式
#### Proxy Mesh（ThinSDK）模式
   描述：Proxy Mesh有两种一种是Sidecar、另一种是集中式Proxy。（是否要考虑集中式Proxy的情况）注：下文提到的Proxy Mesh暂时都指代Sidecar模式。

方案：Proxy Mesh采用Dubbo内部的直连模式来完成Dubbo SDK与Sidecar之间的通信。

待做事项：
1. 缩小Dubbo SDK包（新增一个Dubbo ThinSDK Library，名字叫dubbo-thin.jar ？？）：dubbo-thin.jar应该更加专注于RPC本身。
   ○ 服务发现
   ○ 路由（Router、Loadbalance）
   ○ 服务注册（Optional）
   ○ 减少部分可观测性（Optional）
   ■ Metrics数据上报，如果去掉Dubbo的Metrics上报，能会丢失应用于Sidecar之间的rt损耗等。
   ■ Tracing：可以去掉。
   ■ Logging：不能去掉。
2. 减少不必要的类加载
3. 梳理需要适配的内容：
   ○ Cluster内比如merge功能
4. 增强与Sidecar之间的交互（dubbo 、triple）
   ○ 健康状态感知（心跳保活）
   ○ 部分配置露出并且透传，比如timeout、retry等。（主要为请求链路上的配置）
   ○ 广播模式配置透传
5. 是否要加强Dubbo SDK侧对mesh的配置露出（待讨论）：新增MeshConfig，将Dubbo内部的一些模型进行封装，比如sidecar之间的连接数（consumer的connections），改为与sidecar之间的连接数等，让mesh配置更加突出。

#### 主次模式
无需缩小包
方案一：采用新增容错策略、并新增恢复能力（恢复到Proxy Mesh模式）
方案二：通过心跳保活探测来触发切换能力，并通过重连来触发恢复Proxy Mesh模式的能力。
#### Proxyless Mesh模式
