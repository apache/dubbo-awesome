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
# Warmup Iteration   1: 1.703 ops/ms
Iteration   1: 6.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.560 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.070 ops/ms
Iteration   1: 11.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.741 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.100 ops/ms
Iteration   1: 14.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.770 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.021 ops/ms
Iteration   1: 9.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.133 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.065 ms/op
Iteration   1: 2.264 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.264 ms/op


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
# Warmup Iteration   1: 3.026 ±(99.9%) 0.044 ms/op
Iteration   1: 1.718 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.718 ms/op


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.095 ms/op
Iteration   1: 2.144 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.144 ms/op


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.098 ms/op
Iteration   1: 3.484 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.484 ms/op


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.131 ms/op
Iteration   1: 2.220 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   2.028 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   3.104 ms/op
                 createUser·p0.99:   8.552 ms/op
                 createUser·p0.999:  15.768 ms/op
                 createUser·p0.9999: 16.550 ms/op
                 createUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14401
  mean =      2.220 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 12580 
    [ 2.500,  3.750) = 1285 
    [ 3.750,  5.000) = 121 
    [ 5.000,  6.250) = 101 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      3.104 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     15.768 ms/op
     p(99.9900) =     16.550 ms/op
     p(99.9990) =     16.564 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


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
# Warmup Iteration   1: 2.949 ±(99.9%) 0.081 ms/op
Iteration   1: 1.848 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   1.751 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  15.668 ms/op
                 existUser·p0.9999: 16.460 ms/op
                 existUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17631
  mean =      1.848 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1165 
    [ 1.250,  2.500) = 15009 
    [ 2.500,  3.750) = 1321 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.437 ms/op
     p(99.9000) =     15.668 ms/op
     p(99.9900) =     16.460 ms/op
     p(99.9990) =     16.548 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


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
# Warmup Iteration   1: 3.372 ±(99.9%) 0.094 ms/op
Iteration   1: 1.928 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   1.862 ms/op
                 getUser·p0.90:   2.269 ms/op
                 getUser·p0.95:   2.482 ms/op
                 getUser·p0.99:   3.355 ms/op
                 getUser·p0.999:  10.568 ms/op
                 getUser·p0.9999: 11.125 ms/op
                 getUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16595
  mean =      1.928 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 15729 
    [ 2.500,  3.750) = 661 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      3.355 ms/op
     p(99.9000) =     10.568 ms/op
     p(99.9900) =     11.125 ms/op
     p(99.9990) =     11.125 ms/op
     p(99.9999) =     11.125 ms/op
    p(100.0000) =     11.125 ms/op


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
# Warmup Iteration   1: 5.139 ±(99.9%) 0.172 ms/op
Iteration   1: 3.383 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   3.154 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   5.857 ms/op
                 listUser·p0.999:  6.738 ms/op
                 listUser·p0.9999: 8.536 ms/op
                 listUser·p1.00:   8.536 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9472
  mean =      3.383 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 6 
    [1.000, 1.500) = 46 
    [1.500, 2.000) = 105 
    [2.000, 2.500) = 287 
    [2.500, 3.000) = 3361 
    [3.000, 3.500) = 1981 
    [3.500, 4.000) = 1780 
    [4.000, 4.500) = 1319 
    [4.500, 5.000) = 362 
    [5.000, 5.500) = 104 
    [5.500, 6.000) = 69 
    [6.000, 6.500) = 36 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =      6.738 ms/op
     p(99.9900) =      8.536 ms/op
     p(99.9990) =      8.536 ms/op
     p(99.9999) =      8.536 ms/op
    p(100.0000) =      8.536 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.560          ops/ms
ClientSimple.existUser                       thrpt         11.741          ops/ms
ClientSimple.getUser                         thrpt         14.770          ops/ms
ClientSimple.listUser                        thrpt          9.133          ops/ms
ClientSimple.createUser                       avgt          2.264           ms/op
ClientSimple.existUser                        avgt          1.718           ms/op
ClientSimple.getUser                          avgt          2.144           ms/op
ClientSimple.listUser                         avgt          3.484           ms/op
ClientSimple.createUser                     sample  14401   2.220 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.736           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.028           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.104           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.552           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.768           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.550           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.564           ms/op
ClientSimple.existUser                      sample  17631   1.848 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.426           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.751           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.437           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.668           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.460           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.548           ms/op
ClientSimple.getUser                        sample  16595   1.928 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.580           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.862           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.269           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.355           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.568           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.125           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.125           ms/op
ClientSimple.listUser                       sample   9472   3.383 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.843           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.154           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.645           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.857           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.738           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.536           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.536           ms/op

Benchmark result is saved to 1719122762854.json
