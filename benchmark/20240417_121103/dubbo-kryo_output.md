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
# Warmup Iteration   1: 2.253 ops/ms
Iteration   1: 6.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.565 ops/ms


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
# Warmup Iteration   1: 5.057 ops/ms
Iteration   1: 11.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.565 ops/ms


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
# Warmup Iteration   1: 5.741 ops/ms
Iteration   1: 12.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.841 ops/ms


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
# Warmup Iteration   1: 5.046 ops/ms
Iteration   1: 8.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.321 ops/ms


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.066 ms/op
Iteration   1: 2.150 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.150 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.050 ms/op
Iteration   1: 1.711 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.711 ms/op


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
# Warmup Iteration   1: 3.401 ±(99.9%) 0.068 ms/op
Iteration   1: 1.899 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.899 ms/op


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
# Warmup Iteration   1: 4.443 ±(99.9%) 0.085 ms/op
Iteration   1: 3.343 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.343 ms/op


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
# Warmup Iteration   1: 3.581 ±(99.9%) 0.115 ms/op
Iteration   1: 1.930 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.478 ms/op
                 createUser·p0.50:   1.753 ms/op
                 createUser·p0.90:   2.269 ms/op
                 createUser·p0.95:   2.466 ms/op
                 createUser·p0.99:   6.934 ms/op
                 createUser·p0.999:  14.860 ms/op
                 createUser·p0.9999: 15.303 ms/op
                 createUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16525
  mean =      1.930 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 643 
    [ 1.250,  2.500) = 15137 
    [ 2.500,  3.750) = 395 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      6.934 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     15.303 ms/op
     p(99.9990) =     15.303 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 2.894 ±(99.9%) 0.064 ms/op
Iteration   1: 1.839 ±(99.9%) 0.062 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   2.036 ms/op
                 existUser·p0.95:   2.220 ms/op
                 existUser·p0.99:   4.247 ms/op
                 existUser·p0.999:  54.501 ms/op
                 existUser·p0.9999: 57.410 ms/op
                 existUser·p1.00:   57.410 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17387
  mean =      1.839 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 17252 
    [ 5.000, 10.000) = 39 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 16 
    [20.000, 25.000) = 16 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.036 ms/op
     p(95.0000) =      2.220 ms/op
     p(99.0000) =      4.247 ms/op
     p(99.9000) =     54.501 ms/op
     p(99.9900) =     57.410 ms/op
     p(99.9990) =     57.410 ms/op
     p(99.9999) =     57.410 ms/op
    p(100.0000) =     57.410 ms/op


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
# Warmup Iteration   1: 3.290 ±(99.9%) 0.074 ms/op
Iteration   1: 2.160 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.093 ms/op
                 getUser·p0.90:   2.540 ms/op
                 getUser·p0.95:   2.748 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  12.386 ms/op
                 getUser·p0.9999: 13.066 ms/op
                 getUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14791
  mean =      2.160 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 12906 
    [ 2.500,  3.750) = 1488 
    [ 3.750,  5.000) = 132 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.093 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     13.066 ms/op
     p(99.9990) =     13.435 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.119 ms/op
Iteration   1: 3.340 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   3.400 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.095 ms/op
                 listUser·p0.999:  11.489 ms/op
                 listUser·p0.9999: 11.928 ms/op
                 listUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9584
  mean =      3.340 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1457 
    [ 2.500,  3.750) = 5212 
    [ 3.750,  5.000) = 2797 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.095 ms/op
     p(99.9000) =     11.489 ms/op
     p(99.9900) =     11.928 ms/op
     p(99.9990) =     11.928 ms/op
     p(99.9999) =     11.928 ms/op
    p(100.0000) =     11.928 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.565          ops/ms
ClientSimple.existUser                       thrpt         11.565          ops/ms
ClientSimple.getUser                         thrpt         12.841          ops/ms
ClientSimple.listUser                        thrpt          8.321          ops/ms
ClientSimple.createUser                       avgt          2.150           ms/op
ClientSimple.existUser                        avgt          1.711           ms/op
ClientSimple.getUser                          avgt          1.899           ms/op
ClientSimple.listUser                         avgt          3.343           ms/op
ClientSimple.createUser                     sample  16525   1.930 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.478           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.753           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.269           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.466           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.934           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.860           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.303           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.303           ms/op
ClientSimple.existUser                      sample  17387   1.839 ± 0.062   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.635           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.638           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.036           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.247           ms/op
ClientSimple.existUser:existUser·p0.999     sample         54.501           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         57.410           ms/op
ClientSimple.existUser:existUser·p1.00      sample         57.410           ms/op
ClientSimple.getUser                        sample  14791   2.160 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.748           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.093           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.530           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.386           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.066           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.435           ms/op
ClientSimple.listUser                       sample   9584   3.340 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.372           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.400           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.145           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.095           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.489           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.928           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.928           ms/op

Benchmark result is saved to 1713355585436.json
