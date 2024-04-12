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
# Warmup Iteration   1: 2.193 ops/ms
Iteration   1: 7.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.807 ops/ms


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
# Warmup Iteration   1: 6.597 ops/ms
Iteration   1: 15.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.077 ops/ms


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
# Warmup Iteration   1: 6.184 ops/ms
Iteration   1: 14.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.805 ops/ms


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
# Warmup Iteration   1: 4.608 ops/ms
Iteration   1: 7.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.850 ops/ms


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.070 ms/op
Iteration   1: 2.129 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.129 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.055 ms/op
Iteration   1: 1.751 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.751 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.051 ms/op
Iteration   1: 2.053 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.053 ms/op


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.114 ms/op
Iteration   1: 2.967 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.967 ms/op


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
# Warmup Iteration   1: 3.506 ±(99.9%) 0.089 ms/op
Iteration   1: 2.524 ±(99.9%) 0.059 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.343 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   4.112 ms/op
                 createUser·p0.999:  39.256 ms/op
                 createUser·p0.9999: 39.942 ms/op
                 createUser·p1.00:   39.977 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12676
  mean =      2.524 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7653 
    [ 2.500,  5.000) = 4947 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.343 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.305 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =     39.256 ms/op
     p(99.9900) =     39.942 ms/op
     p(99.9990) =     39.977 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


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
# Warmup Iteration   1: 2.909 ±(99.9%) 0.063 ms/op
Iteration   1: 1.832 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   1.751 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.355 ms/op
                 existUser·p0.99:   2.818 ms/op
                 existUser·p0.999:  12.632 ms/op
                 existUser·p0.9999: 13.976 ms/op
                 existUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17436
  mean =      1.832 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 16877 
    [ 2.500,  3.750) = 351 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      2.818 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 3.280 ±(99.9%) 0.115 ms/op
Iteration   1: 1.903 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.449 ms/op
                 getUser·p0.50:   1.702 ms/op
                 getUser·p0.90:   2.544 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   3.581 ms/op
                 getUser·p0.999:  13.094 ms/op
                 getUser·p0.9999: 13.244 ms/op
                 getUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16788
  mean =      1.903 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 342 
    [ 1.250,  2.500) = 14527 
    [ 2.500,  3.750) = 1787 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.449 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.581 ms/op
     p(99.9000) =     13.094 ms/op
     p(99.9900) =     13.244 ms/op
     p(99.9990) =     13.255 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


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
# Warmup Iteration   1: 4.593 ±(99.9%) 0.202 ms/op
Iteration   1: 3.909 ±(99.9%) 0.221 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   3.342 ms/op
                 listUser·p0.90:   4.722 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  116.109 ms/op
                 listUser·p0.9999: 124.125 ms/op
                 listUser·p1.00:   124.125 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8185
  mean =      3.909 ±(99.9%) 0.221 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 8099 
    [ 12.500,  25.000) = 34 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 3 
    [ 50.000,  62.500) = 16 
    [ 62.500,  75.000) = 18 
    [ 75.000,  87.500) = 3 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 3 
    [112.500, 125.000) = 9 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.722 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =     13.156 ms/op
     p(99.9000) =    116.109 ms/op
     p(99.9900) =    124.125 ms/op
     p(99.9990) =    124.125 ms/op
     p(99.9999) =    124.125 ms/op
    p(100.0000) =    124.125 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.807          ops/ms
ClientSimple.existUser                       thrpt          15.077          ops/ms
ClientSimple.getUser                         thrpt          14.805          ops/ms
ClientSimple.listUser                        thrpt           7.850          ops/ms
ClientSimple.createUser                       avgt           2.129           ms/op
ClientSimple.existUser                        avgt           1.751           ms/op
ClientSimple.getUser                          avgt           2.053           ms/op
ClientSimple.listUser                         avgt           2.967           ms/op
ClientSimple.createUser                     sample  12676    2.524 ± 0.059   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.708           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.343           ms/op
ClientSimple.createUser:createUser·p0.90    sample           3.101           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.305           ms/op
ClientSimple.createUser:createUser·p0.99    sample           4.112           ms/op
ClientSimple.createUser:createUser·p0.999   sample          39.256           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          39.942           ms/op
ClientSimple.createUser:createUser·p1.00    sample          39.977           ms/op
ClientSimple.existUser                      sample  17436    1.832 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.604           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.751           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.355           ms/op
ClientSimple.existUser:existUser·p0.99      sample           2.818           ms/op
ClientSimple.existUser:existUser·p0.999     sample          12.632           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          13.976           ms/op
ClientSimple.existUser:existUser·p1.00      sample          14.025           ms/op
ClientSimple.getUser                        sample  16788    1.903 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.449           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.702           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.544           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.581           ms/op
ClientSimple.getUser:getUser·p0.999         sample          13.094           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          13.244           ms/op
ClientSimple.getUser:getUser·p1.00          sample          13.255           ms/op
ClientSimple.listUser                       sample   8185    3.909 ± 0.221   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.941           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.342           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.722           ms/op
ClientSimple.listUser:listUser·p0.95        sample           5.382           ms/op
ClientSimple.listUser:listUser·p0.99        sample          13.156           ms/op
ClientSimple.listUser:listUser·p0.999       sample         116.109           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         124.125           ms/op
ClientSimple.listUser:listUser·p1.00        sample         124.125           ms/op

Benchmark result is saved to 1712880893631.json
