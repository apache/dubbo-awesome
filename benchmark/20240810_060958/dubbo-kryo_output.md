# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.863 ops/ms
Iteration   1: 8.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.070 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.182 ops/ms
Iteration   1: 12.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.143 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.266 ops/ms
Iteration   1: 11.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.333 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.304 ops/ms
Iteration   1: 9.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.443 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.738 ±(99.9%) 0.053 ms/op
Iteration   1: 1.932 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.932 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.122 ±(99.9%) 0.050 ms/op
Iteration   1: 1.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.543 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.298 ±(99.9%) 0.063 ms/op
Iteration   1: 2.054 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.054 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.350 ±(99.9%) 0.092 ms/op
Iteration   1: 3.105 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.105 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.190 ±(99.9%) 0.073 ms/op
Iteration   1: 2.274 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.590 ms/op
                 createUser·p0.50:   2.130 ms/op
                 createUser·p0.90:   2.761 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  22.542 ms/op
                 createUser·p0.9999: 26.488 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14059
  mean =      2.274 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11321 
    [ 2.500,  5.000) = 2466 
    [ 5.000,  7.500) = 176 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     22.542 ms/op
     p(99.9900) =     26.488 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.787 ±(99.9%) 0.064 ms/op
Iteration   1: 1.906 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.490 ms/op
                 existUser·p0.50:   1.774 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   4.231 ms/op
                 existUser·p0.999:  31.374 ms/op
                 existUser·p0.9999: 32.363 ms/op
                 existUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16773
  mean =      1.906 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15959 
    [ 2.500,  5.000) = 691 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      4.231 ms/op
     p(99.9000) =     31.374 ms/op
     p(99.9900) =     32.363 ms/op
     p(99.9990) =     32.408 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.963 ±(99.9%) 0.068 ms/op
Iteration   1: 1.915 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.526 ms/op
                 getUser·p0.50:   1.819 ms/op
                 getUser·p0.90:   2.245 ms/op
                 getUser·p0.95:   2.458 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  13.091 ms/op
                 getUser·p0.9999: 13.400 ms/op
                 getUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16794
  mean =      1.915 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 222 
    [ 1.250,  2.500) = 15848 
    [ 2.500,  3.750) = 525 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     13.400 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.218 ±(99.9%) 0.135 ms/op
Iteration   1: 3.263 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.851 ms/op
                 listUser·p0.50:   3.305 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.128 ms/op
                 listUser·p0.999:  7.743 ms/op
                 listUser·p0.9999: 7.782 ms/op
                 listUser·p1.00:   7.782 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9800
  mean =      3.263 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 161 
    [2.000, 2.500) = 1802 
    [2.500, 3.000) = 1815 
    [3.000, 3.500) = 2045 
    [3.500, 4.000) = 2360 
    [4.000, 4.500) = 1251 
    [4.500, 5.000) = 242 
    [5.000, 5.500) = 32 
    [5.500, 6.000) = 29 
    [6.000, 6.500) = 13 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =      7.743 ms/op
     p(99.9900) =      7.782 ms/op
     p(99.9990) =      7.782 ms/op
     p(99.9999) =      7.782 ms/op
    p(100.0000) =      7.782 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.070          ops/ms
ClientSimple.existUser                       thrpt         12.143          ops/ms
ClientSimple.getUser                         thrpt         11.333          ops/ms
ClientSimple.listUser                        thrpt          9.443          ops/ms
ClientSimple.createUser                       avgt          1.932           ms/op
ClientSimple.existUser                        avgt          1.543           ms/op
ClientSimple.getUser                          avgt          2.054           ms/op
ClientSimple.listUser                         avgt          3.105           ms/op
ClientSimple.createUser                     sample  14059   2.274 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.590           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.130           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.142           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.644           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.542           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.488           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.608           ms/op
ClientSimple.existUser                      sample  16773   1.906 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.490           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.774           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.231           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.374           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.363           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.408           ms/op
ClientSimple.getUser                        sample  16794   1.915 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.526           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.819           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.245           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.309           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.091           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.400           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.500           ms/op
ClientSimple.listUser                       sample   9800   3.263 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.851           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.305           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.128           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.743           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.782           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.782           ms/op

Benchmark result is saved to 1723269919537.json
