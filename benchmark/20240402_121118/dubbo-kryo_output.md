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
# Warmup Iteration   1: 1.709 ops/ms
Iteration   1: 7.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.138 ops/ms


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
# Warmup Iteration   1: 6.885 ops/ms
Iteration   1: 12.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.556 ops/ms


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
# Warmup Iteration   1: 5.337 ops/ms
Iteration   1: 10.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.873 ops/ms


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
# Warmup Iteration   1: 4.282 ops/ms
Iteration   1: 8.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.707 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.432 ±(99.9%) 0.104 ms/op
Iteration   1: 2.236 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.236 ms/op


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
# Warmup Iteration   1: 3.242 ±(99.9%) 0.063 ms/op
Iteration   1: 2.216 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.216 ms/op


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
# Warmup Iteration   1: 3.447 ±(99.9%) 0.069 ms/op
Iteration   1: 2.090 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.090 ms/op


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
# Warmup Iteration   1: 4.632 ±(99.9%) 0.095 ms/op
Iteration   1: 3.538 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.538 ms/op


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.094 ms/op
Iteration   1: 2.115 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   1.835 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.839 ms/op
                 createUser·p0.99:   8.485 ms/op
                 createUser·p0.999:  17.007 ms/op
                 createUser·p0.9999: 18.341 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15110
  mean =      2.115 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 13428 
    [ 2.500,  3.750) = 1196 
    [ 3.750,  5.000) = 155 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      8.485 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     18.341 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 2.991 ±(99.9%) 0.062 ms/op
Iteration   1: 1.951 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   1.815 ms/op
                 existUser·p0.90:   2.634 ms/op
                 existUser·p0.95:   2.941 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  15.870 ms/op
                 existUser·p0.9999: 16.223 ms/op
                 existUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16399
  mean =      1.951 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1109 
    [ 1.250,  2.500) = 12983 
    [ 2.500,  3.750) = 2112 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =     15.870 ms/op
     p(99.9900) =     16.223 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 3.046 ±(99.9%) 0.072 ms/op
Iteration   1: 2.390 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.448 ms/op
                 getUser·p0.50:   2.322 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.717 ms/op
                 getUser·p0.999:  19.464 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13410
  mean =      2.390 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 8409 
    [ 2.500,  3.750) = 4604 
    [ 3.750,  5.000) = 146 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      2.322 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.717 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.134 ms/op
Iteration   1: 3.458 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.510 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  7.936 ms/op
                 listUser·p0.9999: 8.069 ms/op
                 listUser·p1.00:   8.069 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9269
  mean =      3.458 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 9 
    [1.500, 2.000) = 61 
    [2.000, 2.500) = 402 
    [2.500, 3.000) = 1933 
    [3.000, 3.500) = 2163 
    [3.500, 4.000) = 3279 
    [4.000, 4.500) = 1102 
    [4.500, 5.000) = 124 
    [5.000, 5.500) = 40 
    [5.500, 6.000) = 53 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 32 
    [7.000, 7.500) = 24 
    [7.500, 8.000) = 36 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =      7.936 ms/op
     p(99.9900) =      8.069 ms/op
     p(99.9990) =      8.069 ms/op
     p(99.9999) =      8.069 ms/op
    p(100.0000) =      8.069 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.138          ops/ms
ClientSimple.existUser                       thrpt         12.556          ops/ms
ClientSimple.getUser                         thrpt         10.873          ops/ms
ClientSimple.listUser                        thrpt          8.707          ops/ms
ClientSimple.createUser                       avgt          2.236           ms/op
ClientSimple.existUser                        avgt          2.216           ms/op
ClientSimple.getUser                          avgt          2.090           ms/op
ClientSimple.listUser                         avgt          3.538           ms/op
ClientSimple.createUser                     sample  15110   2.115 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.929           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.835           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.485           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.007           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.341           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.743           ms/op
ClientSimple.existUser                      sample  16399   1.951 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.535           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.815           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.634           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.941           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.043           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.870           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.223           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.286           ms/op
ClientSimple.getUser                        sample  13410   2.390 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.448           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.322           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.219           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.717           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.464           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.562           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.562           ms/op
ClientSimple.listUser                       sample   9269   3.458 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.057           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.510           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.133           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.562           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.936           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.069           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.069           ms/op

Benchmark result is saved to 1712059612034.json
