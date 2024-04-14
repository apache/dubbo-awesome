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
# Warmup Iteration   1: 1.086 ops/ms
Iteration   1: 6.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.536 ops/ms


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
# Warmup Iteration   1: 7.080 ops/ms
Iteration   1: 13.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.148 ops/ms


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
# Warmup Iteration   1: 6.127 ops/ms
Iteration   1: 14.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.198 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.482 ops/ms
Iteration   1: 9.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.424 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.779 ±(99.9%) 0.064 ms/op
Iteration   1: 2.226 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.226 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.974 ±(99.9%) 0.051 ms/op
Iteration   1: 1.645 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.645 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.032 ±(99.9%) 0.052 ms/op
Iteration   1: 1.999 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.999 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.665 ±(99.9%) 0.084 ms/op
Iteration   1: 3.193 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.193 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.327 ±(99.9%) 0.072 ms/op
Iteration   1: 2.286 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.416 ms/op
                 createUser·p0.50:   2.052 ms/op
                 createUser·p0.90:   2.875 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   12.273 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 19.216 ms/op
                 createUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13992
  mean =      2.286 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 469 
    [ 1.250,  2.500) = 10875 
    [ 2.500,  3.750) = 2279 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      2.052 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =     12.273 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     19.216 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.837 ±(99.9%) 0.059 ms/op
Iteration   1: 2.004 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   1.946 ms/op
                 existUser·p0.90:   2.363 ms/op
                 existUser·p0.95:   2.518 ms/op
                 existUser·p0.99:   3.285 ms/op
                 existUser·p0.999:  20.840 ms/op
                 existUser·p0.9999: 20.985 ms/op
                 existUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15942
  mean =      2.004 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15092 
    [ 2.500,  5.000) = 741 
    [ 5.000,  7.500) = 13 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.518 ms/op
     p(99.0000) =      3.285 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     20.985 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 3.249 ±(99.9%) 0.071 ms/op
Iteration   1: 1.856 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   1.769 ms/op
                 getUser·p0.90:   2.208 ms/op
                 getUser·p0.95:   2.519 ms/op
                 getUser·p0.99:   3.052 ms/op
                 getUser·p0.999:  10.240 ms/op
                 getUser·p0.9999: 10.502 ms/op
                 getUser·p1.00:   10.502 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17395
  mean =      1.856 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 9 
    [ 1.000,  2.000) = 14567 
    [ 2.000,  3.000) = 2628 
    [ 3.000,  4.000) = 112 
    [ 4.000,  5.000) = 32 
    [ 5.000,  6.000) = 13 
    [ 6.000,  7.000) = 2 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.052 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     10.502 ms/op
     p(99.9990) =     10.502 ms/op
     p(99.9999) =     10.502 ms/op
    p(100.0000) =     10.502 ms/op


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.106 ms/op
Iteration   1: 3.597 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   5.980 ms/op
                 listUser·p0.999:  20.317 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8959
  mean =      3.597 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 871 
    [ 2.500,  5.000) = 7762 
    [ 5.000,  7.500) = 260 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     20.317 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.536          ops/ms
ClientSimple.existUser                       thrpt         13.148          ops/ms
ClientSimple.getUser                         thrpt         14.198          ops/ms
ClientSimple.listUser                        thrpt          9.424          ops/ms
ClientSimple.createUser                       avgt          2.226           ms/op
ClientSimple.existUser                        avgt          1.645           ms/op
ClientSimple.getUser                          avgt          1.999           ms/op
ClientSimple.listUser                         avgt          3.193           ms/op
ClientSimple.createUser                     sample  13992   2.286 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.416           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.052           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.150           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.273           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.990           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.216           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.857           ms/op
ClientSimple.existUser                      sample  15942   2.004 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.618           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.946           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.363           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.518           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.285           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.840           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.985           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.004           ms/op
ClientSimple.getUser                        sample  17395   1.856 ± 0.012   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.765           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.769           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.208           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.052           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.240           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.502           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.502           ms/op
ClientSimple.listUser                       sample   8959   3.597 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.090           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.629           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.980           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.317           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.578           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.578           ms/op

Benchmark result is saved to 1713103688302.json
