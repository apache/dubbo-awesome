# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.823 ops/ms
Iteration   1: 7.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.739 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.957 ops/ms
Iteration   1: 13.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.690 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.057 ops/ms
Iteration   1: 13.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.634 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.644 ops/ms
Iteration   1: 8.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.629 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.032 ±(99.9%) 0.080 ms/op
Iteration   1: 2.218 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.218 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.198 ±(99.9%) 0.056 ms/op
Iteration   1: 1.931 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.931 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.438 ±(99.9%) 0.053 ms/op
Iteration   1: 2.049 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.049 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.506 ±(99.9%) 0.097 ms/op
Iteration   1: 3.217 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.217 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.431 ±(99.9%) 0.088 ms/op
Iteration   1: 2.040 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.568 ms/op
                 createUser·p0.50:   1.882 ms/op
                 createUser·p0.90:   2.445 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  26.203 ms/op
                 createUser·p0.9999: 32.437 ms/op
                 createUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15667
  mean =      2.040 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14238 
    [ 2.500,  5.000) = 1272 
    [ 5.000,  7.500) = 48 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =     26.203 ms/op
     p(99.9900) =     32.437 ms/op
     p(99.9990) =     32.604 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.906 ±(99.9%) 0.064 ms/op
Iteration   1: 1.873 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   1.755 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   3.358 ms/op
                 existUser·p0.999:  15.286 ms/op
                 existUser·p0.9999: 15.471 ms/op
                 existUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17103
  mean =      1.873 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 416 
    [ 1.250,  2.500) = 15912 
    [ 2.500,  3.750) = 659 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.755 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      3.358 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     15.471 ms/op
     p(99.9990) =     15.483 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.214 ±(99.9%) 0.090 ms/op
Iteration   1: 2.216 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.277 ms/op
                 getUser·p0.50:   2.179 ms/op
                 getUser·p0.90:   2.662 ms/op
                 getUser·p0.95:   2.904 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  13.854 ms/op
                 getUser·p0.9999: 13.936 ms/op
                 getUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14439
  mean =      2.216 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 212 
    [ 1.250,  2.500) = 11684 
    [ 2.500,  3.750) = 2372 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.277 ms/op
     p(50.0000) =      2.179 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =     13.854 ms/op
     p(99.9900) =     13.936 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.554 ±(99.9%) 0.132 ms/op
Iteration   1: 3.558 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  19.727 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8984
  mean =      3.558 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1535 
    [ 2.500,  5.000) = 7047 
    [ 5.000,  7.500) = 289 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     19.727 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.739          ops/ms
ClientSimple.existUser                       thrpt         13.690          ops/ms
ClientSimple.getUser                         thrpt         13.634          ops/ms
ClientSimple.listUser                        thrpt          8.629          ops/ms
ClientSimple.createUser                       avgt          2.218           ms/op
ClientSimple.existUser                        avgt          1.931           ms/op
ClientSimple.getUser                          avgt          2.049           ms/op
ClientSimple.listUser                         avgt          3.217           ms/op
ClientSimple.createUser                     sample  15667   2.040 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.568           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.882           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.445           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.005           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.203           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.437           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.604           ms/op
ClientSimple.existUser                      sample  17103   1.873 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.564           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.755           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.358           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.286           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.471           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.483           ms/op
ClientSimple.getUser                        sample  14439   2.216 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.277           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.179           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.904           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.628           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.854           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.936           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.943           ms/op
ClientSimple.listUser                       sample   8984   3.558 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.781           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.572           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.832           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.727           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.218           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.218           ms/op

Benchmark result is saved to 1711152868742.json
