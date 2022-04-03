# 报名须知
* 请务必详细阅读指引：https://community.apache.org/gsoc.html#prospective-asf-mentors-read-this
* 请务必在感兴趣的 Project 的 Issue 下方留言。
* Google 官方报名地址：https://summerofcode.withgoogle.com/


## 题目一：可观测性
* Related proposal https://github.com/apache/dubbo-awesome/blob/master/proposals/D4-observability.md
* Project links of different languages:
  * Java https://github.com/apache/dubbo/issues/9886
  * Golang 
## 题目二：Proxyless Mesh  
* Related proposal https://github.com/apache/dubbo-awesome/blob/master/proposals/D3.2-proxyless-mesh.md
* Project links of different languages:
  * Java https://github.com/apache/dubbo/issues/9884
  * Golang 
## 题目三：Proxy Mesh - Thin SDK
* Related proposal https://github.com/apache/dubbo-awesome/blob/master/proposals/D3.1-thinsdk-sidecar-mesh.md
* Project links of different languages:
  * Java https://github.com/apache/dubbo/issues/9885
  * Golang 
## 题目四：admin api 迁移 qos 去中心化管控

## 题目五：服务治理场景化用例设计
* Related project link(https://github.com/apache/dubbo/issues/9887)    

**任务描述**  
Dubbo 拥有丰富的治理规则，如服务发现、负载均衡、路由策略（标签路由、条件路由）等，但是这些治理规则的使用具有一定的难度，用户也很难直观的了解到其对应的使用场景。因此 Dubbo 期望有这样的一些场景化的用例能够体现 Dubbo 的治理能力，帮助用户将治理规则迁移到真实业务场景中使用。

这是一项相对比较有挑战性的任务，难度并不在编码本身，而在于对整个 Dubbo 及微服务体系要有比较总体的把握。如能顺利完成，对于参与者整体的视野提升将具有非常大的帮助。参与者可以导师一起协作完成。

**参考：**  
Istio 中 bookinfo 应用

## 题目六：rust 多语言实现
* Related issue: 
* 总体目标：为 Dubbo3 提供 rust 多语言实现

## 题目七：python3 多语言实现

* Related issue: 
* 总体目标：为 Dubbo3 提供 python3 多语言实现

## 题目八：Dubbo、Triple协议的抓包解析工具

* Related issue: 
* 总体目标：为了方便Dubbo的用户排查问题，为Dubbo社区提供解析Dubbo、Triple协议的工具。目前比较流行的抓包工具有wireshark等，但是Wireshark的开源许可证是GPL2，与Apache 2.0不兼容，因此我们需要实现解析Dubbo自身协议的工具。

