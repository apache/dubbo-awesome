## 目录

*   [背景](#背景)

*   [目标](#目标)

*   [XDS 路由协议解析](#xds-路由协议解析)

    *   [XDS 服务发现流程](#xds-服务发现流程)

        *   [LDS ](#lds-)

        *   [RDS](#rds)

        *   [CDS](#cds)

        *   [EDS](#eds)

        *   [总结](#总结)

    *   [VirtualService 对 RDS 的影响](#virtualservice-对-rds-的影响)

    *   [DestinationRule 对 CDS的影响](#destinationrule-对-cds的影响)

    *   [Pod 打标对EDS的影响](#pod-打标对eds的影响)

    *   [XDS 路由总结](#xds-路由总结)

*   [Dubbo 路由适配](#dubbo-路由适配)

# Dubbo 对接 XDS 路由

## 背景

Dubbo 框架使用 proxyless 的方式接入控制中心，对接 XDS 协议。将 XDS 的路由功能与 Dubbo 的路由功能适配。

## 目标

完成基本路由功能，其他服务治理功能如负载均衡、权重、超时等后续添加

*   解析 VirtualService 规则，uri、head 的规则匹配

*   解析 DestinationRule 规则适配 subsets

## XDS 路由协议解析

先部署一个 Pod 注入 sidecar，借助 `istioctl` 工具进行 xds 协议分析。

```bash
kubectl get pod
NAME                              READY   STATUS    RESTARTS   AGE
productpage-v1-65b75f6885-cb7d5   2/2     Running   0          9h
```

将 demo `dubbo-samples-xds` 部署在集群中，以下将对此 demo 进行分析。

### XDS 服务发现流程

#### LDS&#x20;

获取LDS数据，获取 `dubbo-samples-xds-provide`监听端口为 50051

```bash
istioctl proxy-config listener productpage-v1-65b75f6885-cb7d5

ADDRESS        PORT  MATCH                                   DESTINATION
......
10.102.128.210 15443 ALL                                     Cluster: outbound|15443||istio-ingressgateway.istio-system.svc.cluster.local
10.102.128.210 31400 ALL                                     Cluster: outbound|31400||istio-ingressgateway.istio-system.svc.cluster.local
0.0.0.0        50051 Trans: raw_buffer; App: http/1.1,h2c    Route: 50051
0.0.0.0        50051 ALL                                     PassthroughCluster
```

查看具体数据，获取 routeConfigName 名称为 `50051`

```bash
istioctl proxy-config listener productpage-v1-65b75f6885-cb7d5 --port=50051 -o json 
```

```json
.....
"typedConfig": {
  "@type": "type.googleapis.com/envoy.extensions.filters.network.http_connection_manager.v3.HttpConnectionManager",
  "statPrefix": "outbound_0.0.0.0_50051",
  "rds": {
    "configSource": {
      "ads": {},
      "initialFetchTimeout": "0s",
      "resourceApiVersion": "V3"
    },
    "routeConfigName": "50051"
  }
...
```

#### RDS

通过路由名称 `50051`  查询 RDS ，获取到  cluster `outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local`&#x20;

```bash
istioctl proxy-config route productpage-v1-65b75f6885-cb7d5 --name=50051 -o json
```

```json
[
    {
        "name": "50051",
        "virtualHosts": [
            ...,
            {
                "name": "dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local:50051",
                "domains": [
                    "dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local",
                    "dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local:50051",
                    "dubbo-samples-xds-provider.dubbo-demo",
                    "dubbo-samples-xds-provider.dubbo-demo:50051",
                    "dubbo-samples-xds-provider.dubbo-demo.svc",
                    "dubbo-samples-xds-provider.dubbo-demo.svc:50051",
                    "10.104.227.50",
                    "10.104.227.50:50051"
                ],
                "routes": [
                    {
                        "name": "default",
                        "match": {
                            "prefix": "/"
                        },
                        "route": {
                            "cluster": "outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local",
                            "timeout": "0s",
                            "retryPolicy": {
                                "retryOn": "connect-failure,refused-stream,unavailable,cancelled,retriable-status-codes",
                                "numRetries": 2,
                                "retryHostPredicate": [
                                    {
                                        "name": "envoy.retry_host_predicates.previous_hosts"
                                    }
                                ],
                                "hostSelectionRetryMaxAttempts": "5",
                                "retriableStatusCodes": [
                                    503
                                ]
                            },
                            "maxStreamDuration": {
                                "maxStreamDuration": "0s",
                                "grpcTimeoutHeaderMax": "0s"
                            }
                        },
                        "decorator": {
                            "operation": "dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local:50051/*"
                        }
                    }
                ],
                "includeRequestAttemptCount": true
            }
        ],
        "validateClusters": false
    }
]
```

#### CDS

通过 `outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local`  查询 cluster，获取 EDS。

```json
istioctl proxy-config cluster productpage-v1-65b75f6885-cb7d5 --fqdn=dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local -o json
```

```json
        .....
        "name": "outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local",
        "type": "EDS",
        "edsClusterConfig": {
            "edsConfig": {
                "ads": {},
                "initialFetchTimeout": "0s",
                "resourceApiVersion": "V3"
            },
            "serviceName": "outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local"
        },
        "connectTimeout": "10s",
        "circuitBreakers": {
            "thresholds": [
                {
                    "maxConnections": 4294967295,
                    "maxPendingRequests": 4294967295,
                    "maxRequests": 4294967295,
                    "maxRetries": 4294967295,
                    "trackRemaining": true
                }
            ]
        },
        ....
```

#### EDS

通过 `outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local`获取 endpoint&#x20;

```bash
istioctl proxy-config endpoint productpage-v1-65b75f6885-cb7d5 --cluster="outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local"

ENDPOINT              STATUS      OUTLIER CHECK     CLUSTER
10.244.1.58:50051     HEALTHY     OK                outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local
10.244.2.55:50051     HEALTHY     OK                outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local
10.244.2.56:50051     HEALTHY     OK                outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local
```

#### 总结

整个服务发现的流程由 LDS —> RDS —> CDS —> EDS。

### VirtualService 对 RDS 的影响

提交 VirtualService 规则

```yaml
apiVersion: networking.istio.io/v1alpha3
kind: VirtualService
metadata:
  name: dubbo-samples-xds-provider
  namespace: dubbo-demo
spec:
  hosts:
    - dubbo-samples-xds-provider
  http:
    - match:
        - uri:
            prefix: /user/v1
      route:
        - destination:
            host: dubbo-samples-xds-provider
            subset: v1
    - match:
        - uri:
            prefix: /user/v2
      route:
        - destination:
            host: dubbo-samples-xds-provider
            subset: v2
```

再次查看`50051` RDS 信息，已经新增两条路由信息，分别路由到 cluster `outbound|50051|v1|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local` 和 cluster `outbound|50051|v2|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local`

```yaml
istioctl proxy-config route productpage-v1-65b75f6885-cb7d5 --name=50051 -o json
```

```json
[{
  "name": "50051",
    ....,
    {
      "name": "dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local:50051",
      "domains": [
        "dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local",
        "dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local:50051",
        "dubbo-samples-xds-provider.dubbo-demo",
        "dubbo-samples-xds-provider.dubbo-demo:50051",
        "dubbo-samples-xds-provider.dubbo-demo.svc",
        "dubbo-samples-xds-provider.dubbo-demo.svc:50051",
        "10.104.227.50",
        "10.104.227.50:50051"
      ],
      "routes": [{
          "match": {
            "prefix": "/user/v1",
            "caseSensitive": true
          },
          "route": {
            "cluster": "outbound|50051|v1|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local",
            "timeout": "0s",
            .......
     ,
        {
          "match": {
            "prefix": "/user/v2",
            "caseSensitive": true
          },
          "route": {
            "cluster": "outbound|50051|v2|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local",
            "timeout": "0s",
            ......
  ],
  "validateClusters": false
}]
```

### DestinationRule 对 CDS的影响

提交DestinationRule  规则

```yaml
apiVersion: networking.istio.io/v1alpha3
kind: DestinationRule
metadata:
  name: dubbo-samples-xds-provider
  namespace: dubbo-demo
spec:
  host: dubbo-samples-xds-provider
  subsets:
    - name: v1
      labels:
        version: v1
    - name: v2
      labels:
        version: v2

```

查询 cluster `dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local` ，相比之前多了 EDS `outbound|50051|v1|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local`&#x20;

和 `outbound|50051|v1|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local` 。

```yaml
istioctl proxy-config cluster productpage-v1-65b75f6885-cb7d5 --fqdn=dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local
```

```json
...

        ],
        "name": "outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local",
        "type": "EDS",
        "edsClusterConfig": {
            "edsConfig": {
                "ads": {},
                "initialFetchTimeout": "0s",
                "resourceApiVersion": "V3"
            },
            "serviceName": "outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local"
        },
        

...
        "name": "outbound|50051|v2|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local",
        "type": "EDS",
        "edsClusterConfig": {
            "edsConfig": {
                "ads": {},
                "initialFetchTimeout": "0s",
                "resourceApiVersion": "V3"
            },
            "serviceName": "outbound|50051|v2|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local"
        },
...

        "name": "outbound|50051|v1|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local",
        "type": "EDS",
        "edsClusterConfig": {
            "edsConfig": {
                "ads": {},
                "initialFetchTimeout": "0s",
                "resourceApiVersion": "V3"
            },
            "serviceName": "outbound|50051|v1|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local"
        },
  ....       

```

### Pod 打标对EDS的影响

分别部署`dubbo-samples-xds-provider` v1、v2 版本各一个。

```bash
kubectl get pod -n dubbo-demo --show-labels=true

NAME                                             READY   STATUS    RESTARTS      AGE     LABELS
dubbo-samples-xds-provider-565d5c8844-5m66w      1/1     Running   0             71m     app=dubbo-samples-xds-provider,pod-template-hash=565d5c8844
dubbo-samples-xds-provider-565d5c8844-crq8s      1/1     Running   0             71m     app=dubbo-samples-xds-provider,pod-template-hash=565d5c8844
dubbo-samples-xds-provider-565d5c8844-v6zvr      1/1     Running   0             71m     app=dubbo-samples-xds-provider,pod-template-hash=565d5c8844
dubbo-samples-xds-provider-v1-7f68b67f55-z9d85   1/1     Running   0             5m39s   app=dubbo-samples-xds-provider,pod-template-hash=7f68b67f55,version=v1
dubbo-samples-xds-provider-v2-54b49d86c4-pxs5z   1/1     Running   0             14s     app=dubbo-samples-xds-provider,pod-template-hash=54b49d86c4,version=v2

```

再次查看 ESD 出现了 v1、v2 版本的数据名称和 cluster 对应上。而且`outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local` 包含 v1、v2 版本的 endpoint。

```bash
istioctl proxy-config endpoint productpage-v1-65b75f6885-cb7d5 | grep dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local


10.244.1.58:50051                HEALTHY     OK                outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local
10.244.1.61:50051                HEALTHY     OK                outbound|50051|v1|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local
10.244.1.61:50051                HEALTHY     OK                outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local
10.244.1.62:50051                HEALTHY     OK                outbound|50051|v2|dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local
10.244.1.62:50051                HEALTHY     OK                outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local
10.244.2.55:50051                HEALTHY     OK                outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local
10.244.2.56:50051                HEALTHY     OK                outbound|50051||dubbo-samples-xds-provider.dubbo-demo.svc.cluster.local
```

### XDS 路由总结

1.  VirtualService 修改 RDS 数据；

2.  DestinationRule 修改 CDS 数据；

3.  Pod 标签与EDS 适配 ；

## Dubbo 路由适配

1.  将 XDS 协议与 Dubbo 路由体系结合起来，新创建 XDSRouter 完成此功能；

2.  XDSRouter 监听 RDS 获取路由规则，完成 uri、head 匹配功能；

3.  XDSRouter 监听 EDS 获取 endpoint 数据，完成对实例 subsets 的适配；

4.  Dubbo 内部对 XDS 资源建立一套通知机制；
