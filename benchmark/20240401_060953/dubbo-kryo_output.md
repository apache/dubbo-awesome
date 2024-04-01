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
# Warmup Iteration   1: 1.012 ops/ms
Iteration   1: 5.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.859 ops/ms


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
# Warmup Iteration   1: 6.485 ops/ms
Iteration   1: 11.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.533 ops/ms


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
# Warmup Iteration   1: 6.320 ops/ms
Iteration   1: 13.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.294 ops/ms


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
# Warmup Iteration   1: 4.846 ops/ms
Iteration   1: 8.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.748 ops/ms


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.075 ms/op
Iteration   1: 2.157 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.157 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.050 ms/op
Iteration   1: 2.026 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.026 ms/op


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
# Warmup Iteration   1: 3.244 ±(99.9%) 0.049 ms/op
Iteration   1: 2.074 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.074 ms/op


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.093 ms/op
Iteration   1: 3.719 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.719 ms/op


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.087 ms/op
Iteration   1: 2.316 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.761 ms/op
                 createUser·p0.95:   3.002 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  31.333 ms/op
                 createUser·p0.9999: 33.075 ms/op
                 createUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13796
  mean =      2.316 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11133 
    [ 2.500,  5.000) = 2396 
    [ 5.000,  7.500) = 98 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     31.333 ms/op
     p(99.9900) =     33.075 ms/op
     p(99.9990) =     33.423 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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
# Warmup Iteration   1: 2.962 ±(99.9%) 0.060 ms/op
Iteration   1: 1.929 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   1.849 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.470 ms/op
                 existUser·p0.99:   3.359 ms/op
                 existUser·p0.999:  11.141 ms/op
                 existUser·p0.9999: 11.354 ms/op
                 existUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16666
  mean =      1.929 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 15774 
    [ 2.500,  3.750) = 645 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      3.359 ms/op
     p(99.9000) =     11.141 ms/op
     p(99.9900) =     11.354 ms/op
     p(99.9990) =     11.354 ms/op
     p(99.9999) =     11.354 ms/op
    p(100.0000) =     11.354 ms/op


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
# Warmup Iteration   1: 3.326 ±(99.9%) 0.091 ms/op
Iteration   1: 1.903 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   1.759 ms/op
                 getUser·p0.90:   2.449 ms/op
                 getUser·p0.95:   2.728 ms/op
                 getUser·p0.99:   3.101 ms/op
                 getUser·p0.999:  12.812 ms/op
                 getUser·p0.9999: 12.990 ms/op
                 getUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16804
  mean =      1.903 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 15219 
    [ 2.500,  3.750) = 1421 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      3.101 ms/op
     p(99.9000) =     12.812 ms/op
     p(99.9900) =     12.990 ms/op
     p(99.9990) =     13.091 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.116 ms/op
Iteration   1: 3.525 ±(99.9%) 0.078 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.199 ms/op
                 listUser·p0.90:   4.313 ms/op
                 listUser·p0.95:   4.512 ms/op
                 listUser·p0.99:   7.518 ms/op
                 listUser·p0.999:  37.159 ms/op
                 listUser·p0.9999: 42.074 ms/op
                 listUser·p1.00:   42.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9064
  mean =      3.525 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8802 
    [ 5.000, 10.000) = 192 
    [10.000, 15.000) = 5 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      4.313 ms/op
     p(95.0000) =      4.512 ms/op
     p(99.0000) =      7.518 ms/op
     p(99.9000) =     37.159 ms/op
     p(99.9900) =     42.074 ms/op
     p(99.9990) =     42.074 ms/op
     p(99.9999) =     42.074 ms/op
    p(100.0000) =     42.074 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.859          ops/ms
ClientSimple.existUser                       thrpt         11.533          ops/ms
ClientSimple.getUser                         thrpt         13.294          ops/ms
ClientSimple.listUser                        thrpt          8.748          ops/ms
ClientSimple.createUser                       avgt          2.157           ms/op
ClientSimple.existUser                        avgt          2.026           ms/op
ClientSimple.getUser                          avgt          2.074           ms/op
ClientSimple.listUser                         avgt          3.719           ms/op
ClientSimple.createUser                     sample  13796   2.316 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.570           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.002           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.454           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.333           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.075           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.423           ms/op
ClientSimple.existUser                      sample  16666   1.929 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.808           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.849           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.310           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.359           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.141           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.354           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.354           ms/op
ClientSimple.getUser                        sample  16804   1.903 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.699           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.759           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.449           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.812           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.990           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.091           ms/op
ClientSimple.listUser                       sample   9064   3.525 ± 0.078   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.311           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.199           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.313           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.512           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.518           ms/op
ClientSimple.listUser:listUser·p0.999       sample         37.159           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         42.074           ms/op
ClientSimple.listUser:listUser·p1.00        sample         42.074           ms/op

Benchmark result is saved to 1711951524643.json
