# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_createUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_createUser_jmhTest.createUser_Throughput(ClientPb_createUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:02:07
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_existUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_existUser_jmhTest.existUser_Throughput(ClientPb_existUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:01:56
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_getUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_getUser_jmhTest.getUser_Throughput(ClientPb_getUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:01:44
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_listUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_listUser_jmhTest.listUser_Throughput(ClientPb_listUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:01:32
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_createUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_createUser_jmhTest.createUser_AverageTime(ClientPb_createUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:01:21
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_existUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_existUser_jmhTest.existUser_AverageTime(ClientPb_existUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_getUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_getUser_jmhTest.getUser_AverageTime(ClientPb_getUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_listUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_listUser_jmhTest.listUser_AverageTime(ClientPb_listUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:00:46
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_createUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_createUser_jmhTest.createUser_SampleTime(ClientPb_createUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_existUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_existUser_jmhTest.existUser_SampleTime(ClientPb_existUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_getUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_getUser_jmhTest.getUser_SampleTime(ClientPb_getUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:00:11
# Fork: 1 of 1
# Warmup Iteration   1: <failure>

java.lang.IllegalStateException: Not found class org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple, cause: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:690)
	at org.apache.dubbo.rpc.stub.StubSuppliers.getServiceDescriptor(StubSuppliers.java:61)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:347)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.ReferenceConfigBase.get(ReferenceConfigBase.java:395)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroyReference(SimpleReferenceCache.java:294)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:248)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.destroy(SimpleReferenceCache.java:271)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:555)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:517)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:183)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:156)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:157)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:143)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:178)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:171)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:145)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:429)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:386)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:949)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:594)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.ClientPb.<init>(ClientPb.java:32)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B1.<init>(ClientPb_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B2.<init>(ClientPb_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType_B3.<init>(ClientPb_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_jmhType.<init>(ClientPb_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.ClientPb_listUser_jmhTest._jmh_tryInit_f_clientpb0_G(ClientPb_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.ClientPb_listUser_jmhTest.listUser_SampleTime(ClientPb_listUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
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
Caused by: java.lang.ClassNotFoundException: org.apache.dubbo.benchmark.bean.DubboUserServiceDubbo$IUserServiceTriple
	at java.net.URLClassLoader.findClass(URLClassLoader.java:387)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418)
	at sun.misc.Launcher$AppClassLoader.loadClass(Launcher.java:352)
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351)
	at java.lang.Class.forName0(Native Method)
	at java.lang.Class.forName(Class.java:348)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:791)
	at org.apache.dubbo.common.utils.ReflectUtils.name2class(ReflectUtils.java:711)
	at org.apache.dubbo.common.utils.ReflectUtils.forName(ReflectUtils.java:688)
	... 43 more


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




# Run complete. Total time: 00:02:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark  Mode  Cnt  Score   Error  Units

Benchmark result is saved to 1710439494055.json
