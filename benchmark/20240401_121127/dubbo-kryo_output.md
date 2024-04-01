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
# Warmup Iteration   1: 1.534 ops/ms
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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.194 ops/ms
Iteration   1: 11.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.606 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.428 ops/ms
Iteration   1: 11.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.587 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.308 ops/ms
Iteration   1: 9.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.078 ops/ms


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
# Warmup Iteration   1: 4.467 ±(99.9%) 0.078 ms/op
Iteration   1: 2.159 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.159 ms/op


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
# Warmup Iteration   1: 3.262 ±(99.9%) 0.050 ms/op
Iteration   1: 1.900 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.900 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.064 ms/op
Iteration   1: 1.886 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.886 ms/op


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
# Warmup Iteration   1: 4.801 ±(99.9%) 0.102 ms/op
Iteration   1: 3.227 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.227 ms/op


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.106 ms/op
Iteration   1: 2.355 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   2.253 ms/op
                 createUser·p0.90:   2.879 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   5.967 ms/op
                 createUser·p0.999:  18.028 ms/op
                 createUser·p0.9999: 20.963 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13609
  mean =      2.355 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9014 
    [ 2.500,  5.000) = 4440 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.253 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      5.967 ms/op
     p(99.9000) =     18.028 ms/op
     p(99.9900) =     20.963 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 3.010 ±(99.9%) 0.066 ms/op
Iteration   1: 1.782 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   1.577 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  21.856 ms/op
                 existUser·p0.9999: 21.922 ms/op
                 existUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17952
  mean =      1.782 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17096 
    [ 2.500,  5.000) = 670 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      1.577 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     21.856 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     21.922 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 3.373 ±(99.9%) 0.081 ms/op
Iteration   1: 2.357 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.372 ms/op
                 getUser·p0.90:   2.839 ms/op
                 getUser·p0.95:   3.023 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  11.336 ms/op
                 getUser·p0.9999: 11.522 ms/op
                 getUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13697
  mean =      2.357 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 8136 
    [ 2.500,  3.750) = 5307 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.372 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =     11.336 ms/op
     p(99.9900) =     11.522 ms/op
     p(99.9990) =     11.534 ms/op
     p(99.9999) =     11.534 ms/op
    p(100.0000) =     11.534 ms/op


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
# Warmup Iteration   1: 4.468 ±(99.9%) 0.146 ms/op
Iteration   1: 3.873 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  8.843 ms/op
                 listUser·p0.9999: 9.159 ms/op
                 listUser·p1.00:   9.159 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8253
  mean =      3.873 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 95 
    [ 2.000,  3.000) = 521 
    [ 3.000,  4.000) = 4710 
    [ 4.000,  5.000) = 2462 
    [ 5.000,  6.000) = 329 
    [ 6.000,  7.000) = 64 
    [ 7.000,  8.000) = 9 
    [ 8.000,  9.000) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =      8.843 ms/op
     p(99.9900) =      9.159 ms/op
     p(99.9990) =      9.159 ms/op
     p(99.9999) =      9.159 ms/op
    p(100.0000) =      9.159 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.570          ops/ms
ClientSimple.existUser                       thrpt         11.606          ops/ms
ClientSimple.getUser                         thrpt         11.587          ops/ms
ClientSimple.listUser                        thrpt          9.078          ops/ms
ClientSimple.createUser                       avgt          2.159           ms/op
ClientSimple.existUser                        avgt          1.900           ms/op
ClientSimple.getUser                          avgt          1.886           ms/op
ClientSimple.listUser                         avgt          3.227           ms/op
ClientSimple.createUser                     sample  13609   2.355 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.699           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.253           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.150           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.967           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.028           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.963           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.365           ms/op
ClientSimple.existUser                      sample  17952   1.782 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.638           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.577           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.267           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.856           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.922           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.922           ms/op
ClientSimple.getUser                        sample  13697   2.357 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.613           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.372           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.023           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.707           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.336           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.522           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.534           ms/op
ClientSimple.listUser                       sample   8253   3.873 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.994           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.822           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.087           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.824           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.843           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.159           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.159           ms/op

Benchmark result is saved to 1711973218619.json
