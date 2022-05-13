# 背景

相关issue：https://github.com/apache/dubbo/issues/9662

相关的PR：https://github.com/apache/dubbo/pull/9873

问题简述：MetadataService是Dubbo3.0的一个内部服务，主要提供看对服务元数据信息的操作能力。MetadataService的服务调用与正常的业务服务调用无异。目前所有正常的业务服务所代表的url都会携带ServiceModel，并且在发起服务调用时，会将url中的ServiceModel作为调用RpcInvocation携带的ServiceModel。但是MetadataService所代表的url却没有携带，具体可见MetadataUtils.java内的逻辑。

当用户配置了metadata-service-protocol: tri，也就意味着发起MetadataService服务调用采样了triple协议，而triple协议在调用时依赖了ServiceModel的相关信息。当发起MetadataService服务调用时，从invocation和url中没能拿到ServiceModel，从而报NPE。

# 需要讨论的内容

如果需要修复这个问题，大致有三个方案：

1. 在现有的逻辑内向MetadataService注入ServiceModel，让MetadataService的服务发现与正常的业务服务引用保持相同的逻辑，代价是引入的ReferenceConfigBase比较重，其中很多内容都不太需要用到。
2. 抽象出一套内置服务的逻辑，不走ref config，用于内部的轻量级服务，改动量需要评估，可能会较大。
3. 单独在triple解决这个依赖问题，但是这治标不治本，后续协议依然会踩坑。

----



会议纪要：

1. ServiceModel和referenceConfig 解耦，来支持MetadataService的ServiceModel注入需求，避免引入重量级的ReferenceConfig
2. Triple 协议的stub存储全局的信息，待优化。
