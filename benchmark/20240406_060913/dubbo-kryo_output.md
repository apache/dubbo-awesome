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
# Warmup Iteration   1: 1.505 ops/ms
Iteration   1: 6.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.428 ops/ms


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
# Warmup Iteration   1: 6.366 ops/ms
Iteration   1: 13.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.313 ops/ms


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
# Warmup Iteration   1: 5.253 ops/ms
Iteration   1: 12.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.470 ops/ms


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
# Warmup Iteration   1: 5.120 ops/ms
Iteration   1: 8.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.977 ops/ms


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.079 ms/op
Iteration   1: 2.485 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.485 ms/op


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
# Warmup Iteration   1: 3.070 ±(99.9%) 0.048 ms/op
Iteration   1: 2.021 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.021 ms/op


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
# Warmup Iteration   1: 3.465 ±(99.9%) 0.070 ms/op
Iteration   1: 1.783 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.783 ms/op


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
# Warmup Iteration   1: 4.475 ±(99.9%) 0.105 ms/op
Iteration   1: 3.034 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.034 ms/op


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
# Warmup Iteration   1: 3.416 ±(99.9%) 0.089 ms/op
Iteration   1: 2.106 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   1.931 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.806 ms/op
                 createUser·p0.99:   7.222 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 19.134 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15179
  mean =      2.106 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 467 
    [ 1.250,  2.500) = 12890 
    [ 2.500,  3.750) = 1621 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      7.222 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     19.134 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 3.307 ±(99.9%) 0.164 ms/op
Iteration   1: 2.108 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.378 ms/op
                 existUser·p0.50:   2.050 ms/op
                 existUser·p0.90:   2.462 ms/op
                 existUser·p0.95:   2.666 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  15.270 ms/op
                 existUser·p0.9999: 15.735 ms/op
                 existUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15168
  mean =      2.108 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 231 
    [ 1.250,  2.500) = 13660 
    [ 2.500,  3.750) = 1103 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     15.735 ms/op
     p(99.9990) =     15.778 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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
# Warmup Iteration   1: 3.228 ±(99.9%) 0.082 ms/op
Iteration   1: 2.244 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   2.167 ms/op
                 getUser·p0.90:   2.740 ms/op
                 getUser·p0.95:   2.916 ms/op
                 getUser·p0.99:   3.934 ms/op
                 getUser·p0.999:  18.096 ms/op
                 getUser·p0.9999: 18.556 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14252
  mean =      2.244 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 10889 
    [ 2.500,  3.750) = 3100 
    [ 3.750,  5.000) = 143 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      3.934 ms/op
     p(99.9000) =     18.096 ms/op
     p(99.9900) =     18.556 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 4.912 ±(99.9%) 0.352 ms/op
Iteration   1: 3.237 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.154 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.877 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9869
  mean =      3.237 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2284 
    [ 2.500,  5.000) = 7375 
    [ 5.000,  7.500) = 122 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.877 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.428          ops/ms
ClientSimple.existUser                       thrpt         13.313          ops/ms
ClientSimple.getUser                         thrpt         12.470          ops/ms
ClientSimple.listUser                        thrpt          8.977          ops/ms
ClientSimple.createUser                       avgt          2.485           ms/op
ClientSimple.existUser                        avgt          2.021           ms/op
ClientSimple.getUser                          avgt          1.783           ms/op
ClientSimple.listUser                         avgt          3.034           ms/op
ClientSimple.createUser                     sample  15179   2.106 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.548           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.931           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.222           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.514           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.134           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.202           ms/op
ClientSimple.existUser                      sample  15168   2.108 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.378           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.050           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.666           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.137           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.270           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.735           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.778           ms/op
ClientSimple.getUser                        sample  14252   2.244 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.679           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.167           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.916           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.934           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.096           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.556           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.612           ms/op
ClientSimple.listUser                       sample   9869   3.237 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.126           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.154           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.092           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.877           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.794           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.185           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.185           ms/op

Benchmark result is saved to 1712383495338.json
