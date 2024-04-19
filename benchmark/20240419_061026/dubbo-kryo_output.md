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
# Warmup Iteration   1: 1.884 ops/ms
Iteration   1: 6.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.625 ops/ms


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
# Warmup Iteration   1: 5.523 ops/ms
Iteration   1: 13.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.383 ops/ms


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
# Warmup Iteration   1: 5.175 ops/ms
Iteration   1: 11.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.594 ops/ms


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
# Warmup Iteration   1: 4.500 ops/ms
Iteration   1: 9.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.769 ops/ms


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.071 ms/op
Iteration   1: 2.221 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.221 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.048 ms/op
Iteration   1: 1.799 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.799 ms/op


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
# Warmup Iteration   1: 3.307 ±(99.9%) 0.052 ms/op
Iteration   1: 1.893 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.893 ms/op


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.075 ms/op
Iteration   1: 3.059 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.059 ms/op


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.102 ms/op
Iteration   1: 2.004 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.358 ms/op
                 createUser·p0.50:   1.837 ms/op
                 createUser·p0.90:   2.417 ms/op
                 createUser·p0.95:   2.605 ms/op
                 createUser·p0.99:   5.107 ms/op
                 createUser·p0.999:  16.564 ms/op
                 createUser·p0.9999: 17.666 ms/op
                 createUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15950
  mean =      2.004 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 14611 
    [ 2.500,  3.750) = 1002 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.358 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      5.107 ms/op
     p(99.9000) =     16.564 ms/op
     p(99.9900) =     17.666 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 2.737 ±(99.9%) 0.060 ms/op
Iteration   1: 1.870 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.378 ms/op
                 existUser·p0.50:   1.722 ms/op
                 existUser·p0.90:   2.159 ms/op
                 existUser·p0.95:   2.327 ms/op
                 existUser·p0.99:   4.642 ms/op
                 existUser·p0.999:  26.116 ms/op
                 existUser·p0.9999: 26.491 ms/op
                 existUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17106
  mean =      1.870 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16554 
    [ 2.500,  5.000) = 402 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.327 ms/op
     p(99.0000) =      4.642 ms/op
     p(99.9000) =     26.116 ms/op
     p(99.9900) =     26.491 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 3.460 ±(99.9%) 0.088 ms/op
Iteration   1: 1.890 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.470 ms/op
                 getUser·p0.50:   1.743 ms/op
                 getUser·p0.90:   2.540 ms/op
                 getUser·p0.95:   2.716 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  10.661 ms/op
                 getUser·p0.9999: 11.321 ms/op
                 getUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17055
  mean =      1.890 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 398 
    [ 1.250,  2.500) = 14707 
    [ 2.500,  3.750) = 1799 
    [ 3.750,  5.000) = 107 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      1.743 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =     10.661 ms/op
     p(99.9900) =     11.321 ms/op
     p(99.9990) =     11.321 ms/op
     p(99.9999) =     11.321 ms/op
    p(100.0000) =     11.321 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.139 ms/op
Iteration   1: 3.485 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.169 ms/op
                 listUser·p0.999:  7.132 ms/op
                 listUser·p0.9999: 7.487 ms/op
                 listUser·p1.00:   7.487 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9197
  mean =      3.485 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 44 
    [1.500, 2.000) = 186 
    [2.000, 2.500) = 559 
    [2.500, 3.000) = 1651 
    [3.000, 3.500) = 1830 
    [3.500, 4.000) = 3032 
    [4.000, 4.500) = 1470 
    [4.500, 5.000) = 233 
    [5.000, 5.500) = 67 
    [5.500, 6.000) = 23 
    [6.000, 6.500) = 33 
    [6.500, 7.000) = 28 
    [7.000, 7.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =      7.132 ms/op
     p(99.9900) =      7.487 ms/op
     p(99.9990) =      7.487 ms/op
     p(99.9999) =      7.487 ms/op
    p(100.0000) =      7.487 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.625          ops/ms
ClientSimple.existUser                       thrpt         13.383          ops/ms
ClientSimple.getUser                         thrpt         11.594          ops/ms
ClientSimple.listUser                        thrpt          9.769          ops/ms
ClientSimple.createUser                       avgt          2.221           ms/op
ClientSimple.existUser                        avgt          1.799           ms/op
ClientSimple.getUser                          avgt          1.893           ms/op
ClientSimple.listUser                         avgt          3.059           ms/op
ClientSimple.createUser                     sample  15950   2.004 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.358           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.837           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.417           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.107           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.564           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.666           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.153           ms/op
ClientSimple.existUser                      sample  17106   1.870 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.378           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.722           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.159           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.642           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.116           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.491           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.608           ms/op
ClientSimple.getUser                        sample  17055   1.890 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.470           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.743           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.658           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.661           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.321           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.321           ms/op
ClientSimple.listUser                       sample   9197   3.485 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.978           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.169           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.132           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.487           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.487           ms/op

Benchmark result is saved to 1713506768909.json
