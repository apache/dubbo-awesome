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
# Warmup Iteration   1: 1.388 ops/ms
Iteration   1: 6.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.570 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.113 ops/ms
Iteration   1: 12.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.368 ops/ms


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
# Warmup Iteration   1: 6.356 ops/ms
Iteration   1: 13.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.338 ops/ms


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
# Warmup Iteration   1: 5.108 ops/ms
Iteration   1: 8.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.732 ops/ms


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.156 ms/op
Iteration   1: 2.336 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.336 ms/op


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
# Warmup Iteration   1: 3.368 ±(99.9%) 0.056 ms/op
Iteration   1: 2.003 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.003 ms/op


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
# Warmup Iteration   1: 3.240 ±(99.9%) 0.075 ms/op
Iteration   1: 1.931 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.723 ±(99.9%) 0.110 ms/op
Iteration   1: 3.579 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.579 ms/op


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
# Warmup Iteration   1: 3.389 ±(99.9%) 0.087 ms/op
Iteration   1: 2.134 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   1.944 ms/op
                 createUser·p0.90:   2.445 ms/op
                 createUser·p0.95:   2.819 ms/op
                 createUser·p0.99:   6.800 ms/op
                 createUser·p0.999:  24.773 ms/op
                 createUser·p0.9999: 36.177 ms/op
                 createUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14994
  mean =      2.134 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13711 
    [ 2.500,  5.000) = 1056 
    [ 5.000,  7.500) = 92 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.819 ms/op
     p(99.0000) =      6.800 ms/op
     p(99.9000) =     24.773 ms/op
     p(99.9900) =     36.177 ms/op
     p(99.9990) =     37.290 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.070 ms/op
Iteration   1: 1.836 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   1.667 ms/op
                 existUser·p0.90:   2.048 ms/op
                 existUser·p0.95:   2.302 ms/op
                 existUser·p0.99:   3.378 ms/op
                 existUser·p0.999:  32.408 ms/op
                 existUser·p0.9999: 32.613 ms/op
                 existUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17366
  mean =      1.836 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16766 
    [ 2.500,  5.000) = 489 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.048 ms/op
     p(95.0000) =      2.302 ms/op
     p(99.0000) =      3.378 ms/op
     p(99.9000) =     32.408 ms/op
     p(99.9900) =     32.613 ms/op
     p(99.9990) =     32.637 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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
# Warmup Iteration   1: 3.308 ±(99.9%) 0.079 ms/op
Iteration   1: 1.977 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.418 ms/op
                 getUser·p0.50:   1.847 ms/op
                 getUser·p0.90:   2.343 ms/op
                 getUser·p0.95:   2.556 ms/op
                 getUser·p0.99:   3.183 ms/op
                 getUser·p0.999:  16.074 ms/op
                 getUser·p0.9999: 16.564 ms/op
                 getUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16317
  mean =      1.977 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 235 
    [ 1.250,  2.500) = 15084 
    [ 2.500,  3.750) = 906 
    [ 3.750,  5.000) = 6 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.183 ms/op
     p(99.9000) =     16.074 ms/op
     p(99.9900) =     16.564 ms/op
     p(99.9990) =     16.564 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


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
# Warmup Iteration   1: 4.322 ±(99.9%) 0.144 ms/op
Iteration   1: 3.248 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  9.059 ms/op
                 listUser·p0.9999: 12.567 ms/op
                 listUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9841
  mean =      3.248 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 966 
    [ 2.500,  3.750) = 6715 
    [ 3.750,  5.000) = 1860 
    [ 5.000,  6.250) = 115 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =      9.059 ms/op
     p(99.9900) =     12.567 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.570          ops/ms
ClientSimple.existUser                       thrpt         12.368          ops/ms
ClientSimple.getUser                         thrpt         13.338          ops/ms
ClientSimple.listUser                        thrpt          8.732          ops/ms
ClientSimple.createUser                       avgt          2.336           ms/op
ClientSimple.existUser                        avgt          2.003           ms/op
ClientSimple.getUser                          avgt          1.931           ms/op
ClientSimple.listUser                         avgt          3.579           ms/op
ClientSimple.createUser                     sample  14994   2.134 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.899           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.944           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.445           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.819           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.800           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.773           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.177           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.290           ms/op
ClientSimple.existUser                      sample  17366   1.836 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.662           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.667           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.048           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.378           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.408           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.613           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.637           ms/op
ClientSimple.getUser                        sample  16317   1.977 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.418           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.847           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.343           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.183           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.074           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.564           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.564           ms/op
ClientSimple.listUser                       sample   9841   3.248 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.871           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.990           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.112           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.307           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.059           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.567           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.567           ms/op

Benchmark result is saved to 1711346729545.json
