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
# Warmup Iteration   1: 1.329 ops/ms
Iteration   1: 6.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.765 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.018 ops/ms
Iteration   1: 10.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.526 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.454 ops/ms
Iteration   1: 12.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.834 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ops/ms
Iteration   1: 8.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.712 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.492 ±(99.9%) 0.084 ms/op
Iteration   1: 2.211 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.211 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.309 ±(99.9%) 0.049 ms/op
Iteration   1: 2.154 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.154 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.504 ±(99.9%) 0.067 ms/op
Iteration   1: 2.223 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.223 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.490 ±(99.9%) 0.092 ms/op
Iteration   1: 3.481 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.481 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.216 ±(99.9%) 0.080 ms/op
Iteration   1: 2.292 ±(99.9%) 0.065 ms/op
                 createUser·p0.00:   0.568 ms/op
                 createUser·p0.50:   2.050 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   3.011 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  45.554 ms/op
                 createUser·p0.9999: 47.503 ms/op
                 createUser·p1.00:   47.841 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13965
  mean =      2.292 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13778 
    [ 5.000, 10.000) = 91 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     45.554 ms/op
     p(99.9900) =     47.503 ms/op
     p(99.9990) =     47.841 ms/op
     p(99.9999) =     47.841 ms/op
    p(100.0000) =     47.841 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.148 ±(99.9%) 0.070 ms/op
Iteration   1: 2.343 ±(99.9%) 0.050 ms/op
                 existUser·p0.00:   0.444 ms/op
                 existUser·p0.50:   2.277 ms/op
                 existUser·p0.90:   2.728 ms/op
                 existUser·p0.95:   2.933 ms/op
                 existUser·p0.99:   4.592 ms/op
                 existUser·p0.999:  35.127 ms/op
                 existUser·p0.9999: 35.669 ms/op
                 existUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13649
  mean =      2.343 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10054 
    [ 2.500,  5.000) = 3468 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      4.592 ms/op
     p(99.9000) =     35.127 ms/op
     p(99.9900) =     35.669 ms/op
     p(99.9990) =     35.717 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.649 ±(99.9%) 0.119 ms/op
Iteration   1: 2.129 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   2.050 ms/op
                 getUser·p0.90:   2.608 ms/op
                 getUser·p0.95:   2.818 ms/op
                 getUser·p0.99:   4.138 ms/op
                 getUser·p0.999:  13.844 ms/op
                 getUser·p0.9999: 14.320 ms/op
                 getUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15091
  mean =      2.129 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 12909 
    [ 2.500,  3.750) = 1962 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.608 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      4.138 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     14.320 ms/op
     p(99.9990) =     14.320 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.825 ±(99.9%) 0.149 ms/op
Iteration   1: 3.423 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.343 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.526 ms/op
                 listUser·p0.999:  24.641 ms/op
                 listUser·p0.9999: 25.821 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9338
  mean =      3.423 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 621 
    [ 2.500,  5.000) = 8314 
    [ 5.000,  7.500) = 336 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      4.343 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.526 ms/op
     p(99.9000) =     24.641 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.765          ops/ms
ClientSimple.existUser                       thrpt         10.526          ops/ms
ClientSimple.getUser                         thrpt         12.834          ops/ms
ClientSimple.listUser                        thrpt          8.712          ops/ms
ClientSimple.createUser                       avgt          2.211           ms/op
ClientSimple.existUser                        avgt          2.154           ms/op
ClientSimple.getUser                          avgt          2.223           ms/op
ClientSimple.listUser                         avgt          3.481           ms/op
ClientSimple.createUser                     sample  13965   2.292 ± 0.065   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.568           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.050           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.011           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.619           ms/op
ClientSimple.createUser:createUser·p0.999   sample         45.554           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         47.503           ms/op
ClientSimple.createUser:createUser·p1.00    sample         47.841           ms/op
ClientSimple.existUser                      sample  13649   2.343 ± 0.050   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.444           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.728           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.933           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.592           ms/op
ClientSimple.existUser:existUser·p0.999     sample         35.127           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         35.669           ms/op
ClientSimple.existUser:existUser·p1.00      sample         35.717           ms/op
ClientSimple.getUser                        sample  15091   2.129 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.705           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.050           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.608           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.138           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.844           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.320           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.320           ms/op
ClientSimple.listUser                       sample   9338   3.423 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.042           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.035           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.343           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.526           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.641           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.821           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.821           ms/op

Benchmark result is saved to 1722686765714.json
