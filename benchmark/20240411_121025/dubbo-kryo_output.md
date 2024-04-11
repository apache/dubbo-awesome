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
# Warmup Iteration   1: 1.605 ops/ms
Iteration   1: 6.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.632 ops/ms


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
# Warmup Iteration   1: 6.702 ops/ms
Iteration   1: 12.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.227 ops/ms


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
# Warmup Iteration   1: 4.861 ops/ms
Iteration   1: 12.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.151 ops/ms


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
# Warmup Iteration   1: 4.926 ops/ms
Iteration   1: 8.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.138 ops/ms


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.069 ms/op
Iteration   1: 2.099 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.099 ms/op


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
# Warmup Iteration   1: 3.134 ±(99.9%) 0.050 ms/op
Iteration   1: 1.618 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.618 ms/op


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
# Warmup Iteration   1: 3.408 ±(99.9%) 0.064 ms/op
Iteration   1: 2.328 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.328 ms/op


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
# Warmup Iteration   1: 4.170 ±(99.9%) 0.111 ms/op
Iteration   1: 3.535 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.535 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.100 ms/op
Iteration   1: 2.201 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.532 ms/op
                 createUser·p0.50:   2.015 ms/op
                 createUser·p0.90:   2.560 ms/op
                 createUser·p0.95:   2.867 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  22.479 ms/op
                 createUser·p0.9999: 22.715 ms/op
                 createUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14512
  mean =      2.201 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12774 
    [ 2.500,  5.000) = 1572 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     22.479 ms/op
     p(99.9900) =     22.715 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 3.090 ±(99.9%) 0.077 ms/op
Iteration   1: 1.886 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   1.759 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.188 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 12.439 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16955
  mean =      1.886 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 163 
    [ 1.250,  2.500) = 15837 
    [ 2.500,  3.750) = 817 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.188 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     12.439 ms/op
     p(99.9990) =     12.485 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


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
# Warmup Iteration   1: 3.090 ±(99.9%) 0.069 ms/op
Iteration   1: 1.860 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   1.696 ms/op
                 getUser·p0.90:   2.451 ms/op
                 getUser·p0.95:   2.650 ms/op
                 getUser·p0.99:   3.107 ms/op
                 getUser·p0.999:  14.926 ms/op
                 getUser·p0.9999: 15.466 ms/op
                 getUser·p1.00:   15.466 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17235
  mean =      1.860 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 15586 
    [ 2.500,  3.750) = 1374 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.451 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.107 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     15.466 ms/op
     p(99.9990) =     15.466 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 5.124 ±(99.9%) 0.251 ms/op
Iteration   1: 3.407 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.314 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.564 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  12.380 ms/op
                 listUser·p0.9999: 14.254 ms/op
                 listUser·p1.00:   14.254 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9397
  mean =      3.407 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 873 
    [ 2.500,  3.750) = 5711 
    [ 3.750,  5.000) = 2506 
    [ 5.000,  6.250) = 159 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.564 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     12.380 ms/op
     p(99.9900) =     14.254 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.632          ops/ms
ClientSimple.existUser                       thrpt         12.227          ops/ms
ClientSimple.getUser                         thrpt         12.151          ops/ms
ClientSimple.listUser                        thrpt          8.138          ops/ms
ClientSimple.createUser                       avgt          2.099           ms/op
ClientSimple.existUser                        avgt          1.618           ms/op
ClientSimple.getUser                          avgt          2.328           ms/op
ClientSimple.listUser                         avgt          3.535           ms/op
ClientSimple.createUser                     sample  14512   2.201 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.532           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.015           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.560           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.365           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.479           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.715           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.774           ms/op
ClientSimple.existUser                      sample  16955   1.886 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.607           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.759           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.188           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.321           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.439           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.485           ms/op
ClientSimple.getUser                        sample  17235   1.860 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.683           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.696           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.451           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.107           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.926           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.466           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.466           ms/op
ClientSimple.listUser                       sample   9397   3.407 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.856           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.314           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.564           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.004           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.380           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.254           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.254           ms/op

Benchmark result is saved to 1712837170506.json
