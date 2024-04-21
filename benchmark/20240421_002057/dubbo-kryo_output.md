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
# Warmup Iteration   1: 1.721 ops/ms
Iteration   1: 7.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.774 ops/ms


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
# Warmup Iteration   1: 6.145 ops/ms
Iteration   1: 14.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.545 ops/ms


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
# Warmup Iteration   1: 6.295 ops/ms
Iteration   1: 13.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.277 ops/ms


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
# Warmup Iteration   1: 4.890 ops/ms
Iteration   1: 7.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.851 ops/ms


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.059 ms/op
Iteration   1: 2.078 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.078 ms/op


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
# Warmup Iteration   1: 2.873 ±(99.9%) 0.054 ms/op
Iteration   1: 1.766 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.766 ms/op


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
# Warmup Iteration   1: 2.989 ±(99.9%) 0.050 ms/op
Iteration   1: 1.905 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.905 ms/op


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.090 ms/op
Iteration   1: 3.664 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.664 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.087 ms/op
Iteration   1: 2.205 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.519 ms/op
                 createUser·p0.50:   2.083 ms/op
                 createUser·p0.90:   2.638 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  18.022 ms/op
                 createUser·p0.9999: 19.238 ms/op
                 createUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14500
  mean =      2.205 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 517 
    [ 1.250,  2.500) = 11992 
    [ 2.500,  3.750) = 1483 
    [ 3.750,  5.000) = 206 
    [ 5.000,  6.250) = 201 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     19.238 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 2.977 ±(99.9%) 0.075 ms/op
Iteration   1: 1.752 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.446 ms/op
                 existUser·p0.50:   1.622 ms/op
                 existUser·p0.90:   2.216 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   3.218 ms/op
                 existUser·p0.999:  14.758 ms/op
                 existUser·p0.9999: 15.421 ms/op
                 existUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18212
  mean =      1.752 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 543 
    [ 1.250,  2.500) = 16884 
    [ 2.500,  3.750) = 654 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      1.622 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.218 ms/op
     p(99.9000) =     14.758 ms/op
     p(99.9900) =     15.421 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 3.089 ±(99.9%) 0.088 ms/op
Iteration   1: 1.940 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   1.864 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.564 ms/op
                 getUser·p0.99:   3.236 ms/op
                 getUser·p0.999:  12.682 ms/op
                 getUser·p0.9999: 14.365 ms/op
                 getUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16486
  mean =      1.940 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 228 
    [ 1.250,  2.500) = 15242 
    [ 2.500,  3.750) = 905 
    [ 3.750,  5.000) = 7 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.236 ms/op
     p(99.9000) =     12.682 ms/op
     p(99.9900) =     14.365 ms/op
     p(99.9990) =     14.418 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.114 ms/op
Iteration   1: 3.034 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.596 ms/op
                 listUser·p0.95:   4.063 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  21.881 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10542
  mean =      3.034 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 927 
    [ 2.500,  5.000) = 9432 
    [ 5.000,  7.500) = 150 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     21.881 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.774          ops/ms
ClientSimple.existUser                       thrpt         14.545          ops/ms
ClientSimple.getUser                         thrpt         13.277          ops/ms
ClientSimple.listUser                        thrpt          7.851          ops/ms
ClientSimple.createUser                       avgt          2.078           ms/op
ClientSimple.existUser                        avgt          1.766           ms/op
ClientSimple.getUser                          avgt          1.905           ms/op
ClientSimple.listUser                         avgt          3.664           ms/op
ClientSimple.createUser                     sample  14500   2.205 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.519           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.083           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.121           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.743           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.022           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.238           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.268           ms/op
ClientSimple.existUser                      sample  18212   1.752 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.446           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.622           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.216           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.218           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.758           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.421           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.516           ms/op
ClientSimple.getUser                        sample  16486   1.940 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.604           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.864           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.236           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.682           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.365           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.418           ms/op
ClientSimple.listUser                       sample  10542   3.034 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.200           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.863           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.596           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.063           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.562           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.881           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.364           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.364           ms/op

Benchmark result is saved to 1713658581563.json
