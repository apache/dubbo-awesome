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
# Warmup Iteration   1: 1.316 ops/ms
Iteration   1: 6.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.448 ops/ms


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
# Warmup Iteration   1: 5.722 ops/ms
Iteration   1: 11.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.321 ops/ms


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
# Warmup Iteration   1: 5.495 ops/ms
Iteration   1: 12.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.025 ops/ms


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
# Warmup Iteration   1: 4.457 ops/ms
Iteration   1: 8.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.262 ops/ms


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.058 ms/op
Iteration   1: 2.136 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.136 ms/op


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
# Warmup Iteration   1: 3.341 ±(99.9%) 0.066 ms/op
Iteration   1: 2.105 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.105 ms/op


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
# Warmup Iteration   1: 3.324 ±(99.9%) 0.052 ms/op
Iteration   1: 2.066 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.066 ms/op


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.093 ms/op
Iteration   1: 3.556 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.556 ms/op


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.084 ms/op
Iteration   1: 2.165 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   1.970 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  27.762 ms/op
                 createUser·p0.9999: 28.118 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14767
  mean =      2.165 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12595 
    [ 2.500,  5.000) = 2007 
    [ 5.000,  7.500) = 83 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     27.762 ms/op
     p(99.9900) =     28.118 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 3.297 ±(99.9%) 0.078 ms/op
Iteration   1: 1.803 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   1.741 ms/op
                 existUser·p0.90:   2.220 ms/op
                 existUser·p0.95:   2.392 ms/op
                 existUser·p0.99:   3.933 ms/op
                 existUser·p0.999:  11.113 ms/op
                 existUser·p0.9999: 11.800 ms/op
                 existUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17729
  mean =      1.803 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 785 
    [ 1.250,  2.500) = 16299 
    [ 2.500,  3.750) = 458 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.220 ms/op
     p(95.0000) =      2.392 ms/op
     p(99.0000) =      3.933 ms/op
     p(99.9000) =     11.113 ms/op
     p(99.9900) =     11.800 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


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
# Warmup Iteration   1: 3.459 ±(99.9%) 0.082 ms/op
Iteration   1: 2.204 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   2.081 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   2.929 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  20.896 ms/op
                 getUser·p0.9999: 22.053 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14657
  mean =      2.204 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11141 
    [ 2.500,  5.000) = 3409 
    [ 5.000,  7.500) = 28 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =     20.896 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 5.431 ±(99.9%) 0.150 ms/op
Iteration   1: 3.707 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.535 ms/op
                 listUser·p0.999:  6.966 ms/op
                 listUser·p0.9999: 9.568 ms/op
                 listUser·p1.00:   9.568 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8632
  mean =      3.707 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 2 
    [ 1.500,  2.000) = 84 
    [ 2.000,  2.500) = 449 
    [ 2.500,  3.000) = 1710 
    [ 3.000,  3.500) = 1157 
    [ 3.500,  4.000) = 1815 
    [ 4.000,  4.500) = 2134 
    [ 4.500,  5.000) = 956 
    [ 5.000,  5.500) = 158 
    [ 5.500,  6.000) = 32 
    [ 6.000,  6.500) = 45 
    [ 6.500,  7.000) = 83 
    [ 7.000,  7.500) = 1 
    [ 7.500,  8.000) = 3 
    [ 8.000,  8.500) = 2 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.535 ms/op
     p(99.9000) =      6.966 ms/op
     p(99.9900) =      9.568 ms/op
     p(99.9990) =      9.568 ms/op
     p(99.9999) =      9.568 ms/op
    p(100.0000) =      9.568 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.448          ops/ms
ClientSimple.existUser                       thrpt         11.321          ops/ms
ClientSimple.getUser                         thrpt         12.025          ops/ms
ClientSimple.listUser                        thrpt          8.262          ops/ms
ClientSimple.createUser                       avgt          2.136           ms/op
ClientSimple.existUser                        avgt          2.105           ms/op
ClientSimple.getUser                          avgt          2.066           ms/op
ClientSimple.listUser                         avgt          3.556           ms/op
ClientSimple.createUser                     sample  14767   2.165 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.597           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.970           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.187           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.726           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.762           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.118           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.180           ms/op
ClientSimple.existUser                      sample  17729   1.803 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.585           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.741           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.933           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.113           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.800           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.813           ms/op
ClientSimple.getUser                        sample  14657   2.204 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.774           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.081           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.760           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.896           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.053           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.053           ms/op
ClientSimple.listUser                       sample   8632   3.707 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.360           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.768           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.535           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.966           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.568           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.568           ms/op

Benchmark result is saved to 1713722731499.json
