# D4 - Observability
* Authors: Zhiguo Wu, Dewei Gong, Jun Liu

## Objective
在本设计内，我们主要涉及的内容为Dubbo的指标体系，并且需要设计的内容总共涉及三块，指标收集、本地聚合、指标推送。
* 指标收集：我们将Dubbo内部需要监控的指标推送至统一的Collector中进行存储。
* 本地聚合：指标收集获取的均为基础指标，而一些分位数指标则需通过本地聚合计算得出。
* 指标推送：收集和聚合后的指标通过一定的方式推送至第三方服务器，本文档只涉及Prometheus。

* 我们将原来的MetricsConfig配置重构后供可观测性使用，并且只有在柔性服务开启或者Metrics，Config配置存在的情况下才会开启指标收集的功能。

## Background
## Related Proposals
[backpressure](./D9-backpressure.md)
## Proposal
### 指标收集
指标通过common模块下的MetricsCollector存储所有指标数据，供柔性服务、指标推送获取。  
收集指标时，默认只收集基础指标，而一些单机聚合指标则需要开启服务柔性或者本地聚合后另起线程计算。此处若开启服务柔性，则本地聚合默认开启。且柔性服务依赖本地聚合的数据。  
柔性服务开启方式暂定。 

本地聚合开启方式:  
```xml
<dubbo:metrics>
    <dubbo:aggregation enabled="true" />
</dubbo:metrics>
```

### 基础指标
基础指标此处不建议收集太具体的指标，更具体的指标可通过Prometheus的Promql计算获得，或者通过开启本地聚合，另起线程计算。  

**基础指标目前暂定以下：**
总请求数、总成功数、总失败数、正在处理的请求数、线程数、请求响应时间（补充中。。。）

**数据流转**
在common包下定义MetricsCollector来收集Dubbo内部各类指标，若开启本地聚合则另起线程，基于MetricsCollector内已存在指标进行统计计算后再次写入该类中。
若开启了本地聚合，则指标接口（仿照MetadataService写一个MetricsService）从MetricsCollector中获取其需要的数据。    
若开启了指标推送（Prometheus为例），则Prometheus SPI中将common包下Dubbo自定义的指标类（如Counter、Gauge等）转换为Prometheus自己的指标类。最后通过用户配置的推送方式（pull、push）来将指标推送至Prometheus服务器中。  

具体如下图所示。  
![observability](../images/observability.png)  

### 指标聚合
其中指标聚合大部分需要通过滑动窗口计算，此处先介绍采用的滑动窗口算法

**滑动窗口**
此处滑动窗口以Prometheus JavaClient的TimeWindowQuantiles为例  
假设我们初始有6个bucket，每个窗口时间设置为2分钟  
每次写入指标数据时，我们会将数据分别写入6个bucket内。每隔两分钟移动一个bucket并且清除原来bucket内的数据。 
读取指标时，我们读取当前current指向的bucket，以达到滑动窗口的效果。  
具体如下图所示。  
![observability](../images/observability-2.png)


在每个bucket内，我们计算分位数指标时也有3种常用算法可选用
* TDigest（极端分位精确度高，如p1 p99，中间分位精确度低，如p50。推荐使用该方式）
    * https://op8867555.github.io/posts/2018-04-09-tdigest.html
    * https://blog.csdn.net/csdnnews/article/details/116246540
    * 开源实现：https://github.com/tdunning/t-digest
* HdrHistogram（精确度低）
    * https://caorong.github.io/2016/07/31/hdrhistogram/
    * 开源实现：https://github.com/HdrHistogram/HdrHistogram
* CKMS（允许一定错误率，由用户自己设置，Prometheus的TimeWindowQuantiles内部使用了该算法。资料偏少，大致看看即可）
    * https://caorong.github.io/2020/08/03/quartile-%20algorithm/
    * https://www.stevenengelhardt.com/2018/03/29/calculating-percentiles-on-streaming-data-part-7-cormode-korn-muthukrishnan-srivastava/
    * http://dimacs.rutgers.edu/~graham/pubs/papers/bquant-icde.pdf  

**参数设计**  
指标聚合参数：
```xml
<dubbo:metrics>
    <dubbo:aggregation enabled="true" bucket-num="5" time-window-seconds="10"/>
</dubbo:metrics>
```

由于聚合指标的计算消耗较大，故在本地聚合开启时，Dubbo内部会开启另外的线程做指标的聚合计算，获取更精确的分位数指标。

### 本地聚合
本地聚合指将一些简单的指标通过计算获取各分位数指标的过程。  

**具体指标**   
* qps: 基于滑动窗口获取动态qps
* rt: 基于滑动窗口获取动态rt
* 失败请求数: 基于滑动窗口获取最近时间内的失败请求数
* 成功请求数: 基于滑动窗口获取最近时间内的成功请求数
* 处理中请求数: 前后增加Filter简单统计即可
*（补充中。。。）

### 指标接口
指标接口将提供一个类似于MetadataService的MetricsService，该Service不仅提供柔性服务所需的接口级数据，也提供所有指标的查询方式。  
其中方法级指标的查询的接口可按如下方式声明

```java
public class MethodMetrics {
  private Integer qps;
  private Quantile rt;
  private Integer succeed;
  private Integer failed;
  private Integer processing;
}

public class Quantile {
  private Double p99;
  private Double p95;
  private Double max;
  private Double avg;
  private Double min;
  private Double last;
}
```

### 指标推送
指标推送只有用户在设置了<dubbo:metrics />配置且配置protocol参数后才开启，若只开启指标聚合，则默认不推送指标。

1、Promehteus Pull ServiceDiscovery
* 使用dubbo-admin等类似的中间层，启动时根据配置将本机 IP、Port、MetricsURL 推送地址信息至dubbo-admin（或任意中间层）的方式，暴露HTTP ServiceDiscovery供prometheus读取，配置方式如<dubbo:metrics protocol="prometheus" mode="pull" address="${dubbo-admin.address}" port="20888" url="/metrics"/>，其中在pull模式下address为可选参数，若不填则需用户手动在Prometheus配置文件中配置地址
    * 优点：稳定，并且能通过中间层移除已下线的应用，只保留存活应用供Prometheus读取
    * 缺点：不够轻量，如果用户没有使用dubbo-admin则必须引入。如果用户自己实现了dubbo控制台则需提供类似http-sd-starter模块供集成，并且该模块需实现健康检查代码，检测已下线的dubbo应用并移除
    * 
2、Prometheus Push Pushgateway
* 用户直接在Dubbo配置文件中配置Prometheus Pushgateway的地址即可，如<dubbo:metrics protocol="prometheus" mode="push" address="${prometheus.pushgateway-url}" interval="5" />，其中interval代表推送间隔
    * 优点：方便，用户只需要引入依赖，并加上这一行配置即可直接采集指标
    * 缺点：Push方式Prometheus无法自动删除已下线的应用的指标，需要用户手动处理

### 集成测试
由于 Dubbo 原有一套指标体系，在可观测行对接完成之后需要清除旧代码并且修改集成测试相关代码

### 整合 Spring 配置
目前国内大部分用户都是基于 Spring 整合 Dubbo 使用，为了更方便用户配置相关内容，需要完善配置自动补全部分，并且对接 SpringBoot 的 Actuator

### 整体结构设计
1、移除原来与 Metrics 相关的类
2、创建新模块 dubbo-metrics/dubbo-metrics-api、dubbo-metrics/dubbo-metrics-prometheus，MetricsConfig 作为该模块的配置类
3、若不使用micrometer，则在common模块下实现自己的Counter、Gauge等，并在dubbo-metrics/dubbo-metrics-prometheus手动转换成prometheus对应的类型
4、若使用micrometer，则Collector中使用基本类型代表指标，如Long、Double等，并在dubbo-metrics-api中引入micrometer，由micrometer对内部指标进行转换
