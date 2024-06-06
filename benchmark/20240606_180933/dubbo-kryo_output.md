# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.234 ops/ms
Iteration   1: 6.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.023 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.317 ops/ms
Iteration   1: 12.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.046 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.509 ops/ms
Iteration   1: 10.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.111 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.730 ops/ms
Iteration   1: 8.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.334 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.254 ±(99.9%) 0.078 ms/op
Iteration   1: 2.310 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.310 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.254 ±(99.9%) 0.056 ms/op
Iteration   1: 1.564 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.564 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.393 ±(99.9%) 0.068 ms/op
Iteration   1: 2.226 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.226 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.736 ±(99.9%) 0.106 ms/op
Iteration   1: 3.202 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.202 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.662 ±(99.9%) 0.100 ms/op
Iteration   1: 2.261 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   2.167 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  19.823 ms/op
                 createUser·p0.9999: 22.819 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14061
  mean =      2.261 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10684 
    [ 2.500,  5.000) = 3187 
    [ 5.000,  7.500) = 111 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     19.823 ms/op
     p(99.9900) =     22.819 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.070 ±(99.9%) 0.073 ms/op
Iteration   1: 2.229 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.486 ms/op
                 existUser·p0.50:   2.050 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.289 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  25.821 ms/op
                 existUser·p0.9999: 26.696 ms/op
                 existUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14366
  mean =      2.229 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11308 
    [ 2.500,  5.000) = 2853 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.289 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     25.821 ms/op
     p(99.9900) =     26.696 ms/op
     p(99.9990) =     26.739 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.497 ±(99.9%) 0.104 ms/op
Iteration   1: 2.050 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   1.913 ms/op
                 getUser·p0.90:   2.494 ms/op
                 getUser·p0.95:   2.679 ms/op
                 getUser·p0.99:   3.954 ms/op
                 getUser·p0.999:  20.251 ms/op
                 getUser·p0.9999: 20.396 ms/op
                 getUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15536
  mean =      2.050 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14012 
    [ 2.500,  5.000) = 1432 
    [ 5.000,  7.500) = 28 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      3.954 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     20.396 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.243 ±(99.9%) 0.143 ms/op
Iteration   1: 3.778 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.325 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8445
  mean =      3.778 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 343 
    [ 2.500,  3.750) = 4138 
    [ 3.750,  5.000) = 3700 
    [ 5.000,  6.250) = 167 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.325 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.023          ops/ms
ClientSimple.existUser                       thrpt         12.046          ops/ms
ClientSimple.getUser                         thrpt         10.111          ops/ms
ClientSimple.listUser                        thrpt          8.334          ops/ms
ClientSimple.createUser                       avgt          2.310           ms/op
ClientSimple.existUser                        avgt          1.564           ms/op
ClientSimple.getUser                          avgt          2.226           ms/op
ClientSimple.listUser                         avgt          3.202           ms/op
ClientSimple.createUser                     sample  14061   2.261 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.898           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.167           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.199           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.833           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.823           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.819           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.872           ms/op
ClientSimple.existUser                      sample  14366   2.229 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.486           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.050           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.974           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.289           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.874           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.821           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.696           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.739           ms/op
ClientSimple.getUser                        sample  15536   2.050 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.660           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.913           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.954           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.251           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.396           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.414           ms/op
ClientSimple.listUser                       sample   8445   3.778 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.071           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.711           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.325           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.941           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.334           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.334           ms/op

Benchmark result is saved to 1717697119492.json
