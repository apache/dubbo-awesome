# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.454 ops/ms
Iteration   1: 6.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.346 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.695 ops/ms
Iteration   1: 13.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.748 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.867 ops/ms
Iteration   1: 12.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.299 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.982 ops/ms
Iteration   1: 8.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.413 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.275 ±(99.9%) 0.078 ms/op
Iteration   1: 2.284 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.284 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ±(99.9%) 0.050 ms/op
Iteration   1: 1.786 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.786 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.217 ±(99.9%) 0.061 ms/op
Iteration   1: 2.276 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.276 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.336 ±(99.9%) 0.102 ms/op
Iteration   1: 3.455 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.455 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.601 ±(99.9%) 0.099 ms/op
Iteration   1: 2.157 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.502 ms/op
                 createUser·p0.50:   1.812 ms/op
                 createUser·p0.90:   2.703 ms/op
                 createUser·p0.95:   3.363 ms/op
                 createUser·p0.99:   10.663 ms/op
                 createUser·p0.999:  21.463 ms/op
                 createUser·p0.9999: 21.730 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14818
  mean =      2.157 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12806 
    [ 2.500,  5.000) = 1664 
    [ 5.000,  7.500) = 128 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      3.363 ms/op
     p(99.0000) =     10.663 ms/op
     p(99.9000) =     21.463 ms/op
     p(99.9900) =     21.730 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.087 ±(99.9%) 0.068 ms/op
Iteration   1: 1.858 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.473 ms/op
                 existUser·p0.50:   1.815 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  18.219 ms/op
                 existUser·p0.9999: 18.860 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17202
  mean =      1.858 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 977 
    [ 1.250,  2.500) = 15346 
    [ 2.500,  3.750) = 762 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.375 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     18.860 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.330 ±(99.9%) 0.087 ms/op
Iteration   1: <failure>

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_sample_jmhStub(ClientSimple_getUser_jmhTest.java:336)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:269)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 27 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more

org.apache.dubbo.rpc.RpcException: Failed to invoke the method getUser in the service org.apache.dubbo.benchmark.service.UserService. Tried 3 times of the providers [localhost:8080] (1/1) from the registry localhost:8080 on the consumer 10.1.0.151 using the dubbo version 3.2.11. Last error is: Invoke remote method timeout. method: getUser, provider: dubbo://localhost:8080/org.apache.dubbo.benchmark.service.UserService?application=dubbo-kyro-client&background=false&check=false&client=netty4&executor-management-mode=isolation&file-cache=true&interface=org.apache.dubbo.benchmark.service.UserService&optimizer=org.apache.dubbo.benchmark.serialize.SerializationOptimizerImpl&pid=3337&prefer.serialization=kryo&reference.filter=-default&register.ip=10.1.0.151&revision=1.0-SNAPSHOT&serialization=kryo&side=consumer&sticky=false&unloadClusterRelated=false, cause: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:126)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invoke(AbstractClusterInvoker.java:366)
	at org.apache.dubbo.rpc.cluster.support.wrapper.AbstractCluster$ClusterFilterInvoker.invoke(AbstractCluster.java:101)
	at org.apache.dubbo.rpc.cluster.support.wrapper.MockClusterInvoker.invoke(MockClusterInvoker.java:106)
	at org.apache.dubbo.rpc.cluster.support.wrapper.ScopeClusterInvoker.invoke(ScopeClusterInvoker.java:156)
	at org.apache.dubbo.rpc.proxy.InvocationUtil.invoke(InvocationUtil.java:64)
	at org.apache.dubbo.rpc.proxy.InvokerInvocationHandler.invoke(InvokerInvocationHandler.java:81)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at sun.reflect.GeneratedMethodAccessor33.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.apache.dubbo.config.spring.util.LazyTargetInvocationHandler.invoke(LazyTargetInvocationHandler.java:54)
	at org.apache.dubbo.benchmark.service.UserServiceDubboProxy0.getUser(UserServiceDubboProxy0.java)
	at org.apache.dubbo.benchmark.rpc.AbstractClient.getUser(AbstractClient.java:29)
	at org.apache.dubbo.benchmark.ClientSimple.getUser(ClientSimple.java:59)
	at org.apache.dubbo.benchmark.generated.ClientSimple_getUser_jmhTest.getUser_SampleTime(ClientSimple_getUser_jmhTest.java:260)
	at sun.reflect.GeneratedMethodAccessor1.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.util.concurrent.TimeoutException: Timeout after 1000ms waiting for result.
	at org.apache.dubbo.rpc.AsyncRpcResult.get(AsyncRpcResult.java:222)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.waitForResultIfSync(AbstractInvoker.java:292)
	at org.apache.dubbo.rpc.protocol.AbstractInvoker.invoke(AbstractInvoker.java:194)
	at org.apache.dubbo.rpc.listener.ListenerInvokerWrapper.invoke(ListenerInvokerWrapper.java:71)
	at org.apache.dubbo.rpc.protocol.ReferenceCountInvokerWrapper.invoke(ReferenceCountInvokerWrapper.java:106)
	at org.apache.dubbo.rpc.cluster.support.AbstractClusterInvoker.invokeWithContext(AbstractClusterInvoker.java:412)
	at org.apache.dubbo.rpc.cluster.support.FailoverClusterInvoker.doInvoke(FailoverClusterInvoker.java:82)
	... 26 more


<JMH had finished, but forked VM did not exit, are there stray running threads? Waiting 24 seconds more...>

Non-finished threads:

Thread[DestroyJavaVM,5,main]
  at java.lang.Object.wait(Native Method)
  at java.lang.Thread.join(Thread.java:1257)
  at java.lang.Thread.join(Thread.java:1331)
  at java.lang.ApplicationShutdownHooks.runHooks(ApplicationShutdownHooks.java:107)
  at java.lang.ApplicationShutdownHooks$1.run(ApplicationShutdownHooks.java:46)
  at java.lang.Shutdown.runHooks(Shutdown.java:130)
  at java.lang.Shutdown.shutdown(Shutdown.java:190)


<JMH had finished, but forked VM did not exit, are there stray running threads? Waiting 19 seconds more...>

Non-finished threads:

Thread[DestroyJavaVM,5,main]
  at java.lang.Object.wait(Native Method)
  at java.lang.Thread.join(Thread.java:1257)
  at java.lang.Thread.join(Thread.java:1331)
  at java.lang.ApplicationShutdownHooks.runHooks(ApplicationShutdownHooks.java:107)
  at java.lang.ApplicationShutdownHooks$1.run(ApplicationShutdownHooks.java:46)
  at java.lang.Shutdown.runHooks(Shutdown.java:130)
  at java.lang.Shutdown.shutdown(Shutdown.java:190)




# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.904 ±(99.9%) 0.157 ms/op
Iteration   1: 3.311 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.269 ms/op
                 listUser·p0.999:  28.944 ms/op
                 listUser·p0.9999: 32.768 ms/op
                 listUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9671
  mean =      3.311 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1556 
    [ 2.500,  5.000) = 7841 
    [ 5.000,  7.500) = 228 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.269 ms/op
     p(99.9000) =     28.944 ms/op
     p(99.9900) =     32.768 ms/op
     p(99.9990) =     32.768 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


# Run complete. Total time: 00:01:34

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.346          ops/ms
ClientSimple.existUser                       thrpt         13.748          ops/ms
ClientSimple.getUser                         thrpt         12.299          ops/ms
ClientSimple.listUser                        thrpt          8.413          ops/ms
ClientSimple.createUser                       avgt          2.284           ms/op
ClientSimple.existUser                        avgt          1.786           ms/op
ClientSimple.getUser                          avgt          2.276           ms/op
ClientSimple.listUser                         avgt          3.455           ms/op
ClientSimple.createUser                     sample  14818   2.157 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.502           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.812           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.363           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.663           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.463           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.730           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.856           ms/op
ClientSimple.existUser                      sample  17202   1.858 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.473           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.815           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.375           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.219           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.860           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.907           ms/op
ClientSimple.listUser                       sample   9671   3.311 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.284           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.052           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.269           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.944           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.768           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.768           ms/op

Benchmark result is saved to 1716487524694.json
