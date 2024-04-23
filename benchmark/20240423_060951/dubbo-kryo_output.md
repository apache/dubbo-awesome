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
# Warmup Iteration   1: 1.412 ops/ms
Iteration   1: 7.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.311 ops/ms


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
# Warmup Iteration   1: 6.370 ops/ms
Iteration   1: 15.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.544 ops/ms


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
# Warmup Iteration   1: 5.231 ops/ms
Iteration   1: 15.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.151 ops/ms


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
# Warmup Iteration   1: 5.132 ops/ms
Iteration   1: 8.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.760 ops/ms


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.070 ms/op
Iteration   1: 2.007 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.007 ms/op


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
# Warmup Iteration   1: 3.522 ±(99.9%) 0.055 ms/op
Iteration   1: 1.791 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.791 ms/op


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
# Warmup Iteration   1: 3.123 ±(99.9%) 0.083 ms/op
Iteration   1: 1.995 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.995 ms/op


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.085 ms/op
Iteration   1: 3.145 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.145 ms/op


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
# Warmup Iteration   1: 3.177 ±(99.9%) 0.074 ms/op
Iteration   1: 2.148 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   1.931 ms/op
                 createUser·p0.90:   2.671 ms/op
                 createUser·p0.95:   2.909 ms/op
                 createUser·p0.99:   5.394 ms/op
                 createUser·p0.999:  18.219 ms/op
                 createUser·p0.9999: 18.301 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14874
  mean =      2.148 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 12338 
    [ 2.500,  3.750) = 2055 
    [ 3.750,  5.000) = 181 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.909 ms/op
     p(99.0000) =      5.394 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     18.301 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 2.767 ±(99.9%) 0.062 ms/op
Iteration   1: 2.003 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.466 ms/op
                 existUser·p0.50:   1.972 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.613 ms/op
                 existUser·p0.99:   3.342 ms/op
                 existUser·p0.999:  5.137 ms/op
                 existUser·p0.9999: 7.146 ms/op
                 existUser·p1.00:   7.234 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15957
  mean =      2.003 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 26 
    [1.000, 1.500) = 1513 
    [1.500, 2.000) = 6933 
    [2.000, 2.500) = 6246 
    [2.500, 3.000) = 930 
    [3.000, 3.500) = 170 
    [3.500, 4.000) = 52 
    [4.000, 4.500) = 27 
    [4.500, 5.000) = 40 
    [5.000, 5.500) = 9 
    [5.500, 6.000) = 7 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      3.342 ms/op
     p(99.9000) =      5.137 ms/op
     p(99.9900) =      7.146 ms/op
     p(99.9990) =      7.234 ms/op
     p(99.9999) =      7.234 ms/op
    p(100.0000) =      7.234 ms/op


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
# Warmup Iteration   1: 3.039 ±(99.9%) 0.081 ms/op
Iteration   1: 1.928 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.463 ms/op
                 getUser·p0.50:   1.769 ms/op
                 getUser·p0.90:   2.458 ms/op
                 getUser·p0.95:   2.671 ms/op
                 getUser·p0.99:   3.401 ms/op
                 getUser·p0.999:  21.476 ms/op
                 getUser·p0.9999: 21.847 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16589
  mean =      1.928 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15176 
    [ 2.500,  5.000) = 1344 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.401 ms/op
     p(99.9000) =     21.476 ms/op
     p(99.9900) =     21.847 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.119 ms/op
Iteration   1: 3.383 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.351 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  8.618 ms/op
                 listUser·p0.9999: 10.109 ms/op
                 listUser·p1.00:   10.109 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9458
  mean =      3.383 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 61 
    [ 2.000,  3.000) = 2862 
    [ 3.000,  4.000) = 5186 
    [ 4.000,  5.000) = 1095 
    [ 5.000,  6.000) = 119 
    [ 6.000,  7.000) = 69 
    [ 7.000,  8.000) = 34 
    [ 8.000,  9.000) = 29 
    [ 9.000, 10.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     10.109 ms/op
     p(99.9990) =     10.109 ms/op
     p(99.9999) =     10.109 ms/op
    p(100.0000) =     10.109 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.311          ops/ms
ClientSimple.existUser                       thrpt         15.544          ops/ms
ClientSimple.getUser                         thrpt         15.151          ops/ms
ClientSimple.listUser                        thrpt          8.760          ops/ms
ClientSimple.createUser                       avgt          2.007           ms/op
ClientSimple.existUser                        avgt          1.791           ms/op
ClientSimple.getUser                          avgt          1.995           ms/op
ClientSimple.listUser                         avgt          3.145           ms/op
ClientSimple.createUser                     sample  14874   2.148 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.843           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.931           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.909           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.394           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.219           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.301           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.317           ms/op
ClientSimple.existUser                      sample  15957   2.003 ± 0.011   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.466           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.972           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.613           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.342           ms/op
ClientSimple.existUser:existUser·p0.999     sample          5.137           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          7.146           ms/op
ClientSimple.existUser:existUser·p1.00      sample          7.234           ms/op
ClientSimple.getUser                        sample  16589   1.928 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.463           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.769           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.401           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.476           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.847           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.020           ms/op
ClientSimple.listUser                       sample   9458   3.383 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.120           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.351           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.145           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.627           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.618           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.109           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.109           ms/op

Benchmark result is saved to 1713852329778.json
