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
# Warmup Iteration   1: 0.995 ops/ms
Iteration   1: 6.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.379 ops/ms


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
# Warmup Iteration   1: 6.602 ops/ms
Iteration   1: 13.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.469 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.795 ops/ms
Iteration   1: 13.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.874 ops/ms


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
# Warmup Iteration   1: 5.144 ops/ms
Iteration   1: 8.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.727 ops/ms


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.098 ms/op
Iteration   1: 2.220 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.220 ms/op


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
# Warmup Iteration   1: 3.001 ±(99.9%) 0.049 ms/op
Iteration   1: 1.897 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.897 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.053 ms/op
Iteration   1: 1.962 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.962 ms/op


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.080 ms/op
Iteration   1: 3.391 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.391 ms/op


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
# Warmup Iteration   1: 3.262 ±(99.9%) 0.079 ms/op
Iteration   1: 2.065 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   1.843 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.781 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  37.420 ms/op
                 createUser·p0.9999: 37.971 ms/op
                 createUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16014
  mean =      2.065 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14035 
    [ 2.500,  5.000) = 1806 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     37.420 ms/op
     p(99.9900) =     37.971 ms/op
     p(99.9990) =     38.011 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


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
# Warmup Iteration   1: 3.219 ±(99.9%) 0.076 ms/op
Iteration   1: 1.979 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   1.909 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   3.006 ms/op
                 existUser·p0.999:  11.955 ms/op
                 existUser·p0.9999: 17.403 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16312
  mean =      1.979 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 15470 
    [ 2.500,  3.750) = 562 
    [ 3.750,  5.000) = 11 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      3.006 ms/op
     p(99.9000) =     11.955 ms/op
     p(99.9900) =     17.403 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 3.550 ±(99.9%) 0.083 ms/op
Iteration   1: 2.257 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   2.122 ms/op
                 getUser·p0.90:   2.884 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   4.728 ms/op
                 getUser·p0.999:  16.843 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14287
  mean =      2.257 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 10523 
    [ 2.500,  3.750) = 3335 
    [ 3.750,  5.000) = 178 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.884 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      4.728 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.138 ms/op
Iteration   1: 3.463 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   3.510 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.529 ms/op
                 listUser·p0.99:   6.304 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9242
  mean =      3.463 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1324 
    [ 2.500,  3.750) = 4767 
    [ 3.750,  5.000) = 2882 
    [ 5.000,  6.250) = 164 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.529 ms/op
     p(99.0000) =      6.304 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.379          ops/ms
ClientSimple.existUser                       thrpt         13.469          ops/ms
ClientSimple.getUser                         thrpt         13.874          ops/ms
ClientSimple.listUser                        thrpt          8.727          ops/ms
ClientSimple.createUser                       avgt          2.220           ms/op
ClientSimple.existUser                        avgt          1.897           ms/op
ClientSimple.getUser                          avgt          1.962           ms/op
ClientSimple.listUser                         avgt          3.391           ms/op
ClientSimple.createUser                     sample  16014   2.065 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.799           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.843           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.685           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.420           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.971           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.011           ms/op
ClientSimple.existUser                      sample  16312   1.979 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.550           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.909           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.006           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.955           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.403           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.465           ms/op
ClientSimple.getUser                        sample  14287   2.257 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.678           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.884           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.088           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.728           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.843           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.974           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.974           ms/op
ClientSimple.listUser                       sample   9242   3.463 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.372           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.510           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.529           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.304           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.286           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.924           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.924           ms/op

Benchmark result is saved to 1713128208157.json
