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
# Warmup Iteration   1: 1.241 ops/ms
Iteration   1: 6.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.029 ops/ms


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
# Warmup Iteration   1: 5.489 ops/ms
Iteration   1: 13.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.416 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.306 ops/ms
Iteration   1: 11.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.184 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.998 ops/ms
Iteration   1: 8.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.719 ops/ms


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
# Warmup Iteration   1: 4.119 ±(99.9%) 0.065 ms/op
Iteration   1: 2.336 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.336 ms/op


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
# Warmup Iteration   1: 3.218 ±(99.9%) 0.055 ms/op
Iteration   1: 1.974 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.974 ms/op


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
# Warmup Iteration   1: 3.540 ±(99.9%) 0.065 ms/op
Iteration   1: 2.044 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.044 ms/op


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
# Warmup Iteration   1: 4.833 ±(99.9%) 0.119 ms/op
Iteration   1: 3.840 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.840 ms/op


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
# Warmup Iteration   1: 3.672 ±(99.9%) 0.092 ms/op
Iteration   1: 2.292 ±(99.9%) 0.060 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   2.075 ms/op
                 createUser·p0.90:   2.675 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  40.632 ms/op
                 createUser·p0.9999: 42.409 ms/op
                 createUser·p1.00:   42.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13945
  mean =      2.292 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13758 
    [ 5.000, 10.000) = 91 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 29 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.675 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     40.632 ms/op
     p(99.9900) =     42.409 ms/op
     p(99.9990) =     42.926 ms/op
     p(99.9999) =     42.926 ms/op
    p(100.0000) =     42.926 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.080 ms/op
Iteration   1: 1.816 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   1.755 ms/op
                 existUser·p0.90:   2.191 ms/op
                 existUser·p0.95:   2.404 ms/op
                 existUser·p0.99:   3.133 ms/op
                 existUser·p0.999:  13.916 ms/op
                 existUser·p0.9999: 14.176 ms/op
                 existUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17604
  mean =      1.816 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1162 
    [ 1.250,  2.500) = 15764 
    [ 2.500,  3.750) = 579 
    [ 3.750,  5.000) = 19 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      1.755 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.404 ms/op
     p(99.0000) =      3.133 ms/op
     p(99.9000) =     13.916 ms/op
     p(99.9900) =     14.176 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.083 ms/op
Iteration   1: 1.992 ±(99.9%) 0.054 ms/op
                 getUser·p0.00:   0.212 ms/op
                 getUser·p0.50:   1.767 ms/op
                 getUser·p0.90:   2.355 ms/op
                 getUser·p0.95:   2.630 ms/op
                 getUser·p0.99:   4.597 ms/op
                 getUser·p0.999:  41.913 ms/op
                 getUser·p0.9999: 54.392 ms/op
                 getUser·p1.00:   54.591 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16084
  mean =      1.992 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15944 
    [ 5.000, 10.000) = 36 
    [10.000, 15.000) = 26 
    [15.000, 20.000) = 20 
    [20.000, 25.000) = 38 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 5 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.212 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      4.597 ms/op
     p(99.9000) =     41.913 ms/op
     p(99.9900) =     54.392 ms/op
     p(99.9990) =     54.591 ms/op
     p(99.9999) =     54.591 ms/op
    p(100.0000) =     54.591 ms/op


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.130 ms/op
Iteration   1: 3.770 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.026 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  14.801 ms/op
                 listUser·p0.9999: 16.122 ms/op
                 listUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8489
  mean =      3.770 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 868 
    [ 2.500,  3.750) = 3527 
    [ 3.750,  5.000) = 3660 
    [ 5.000,  6.250) = 198 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.026 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     14.801 ms/op
     p(99.9900) =     16.122 ms/op
     p(99.9990) =     16.122 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.029          ops/ms
ClientSimple.existUser                       thrpt         13.416          ops/ms
ClientSimple.getUser                         thrpt         11.184          ops/ms
ClientSimple.listUser                        thrpt          8.719          ops/ms
ClientSimple.createUser                       avgt          2.336           ms/op
ClientSimple.existUser                        avgt          1.974           ms/op
ClientSimple.getUser                          avgt          2.044           ms/op
ClientSimple.listUser                         avgt          3.840           ms/op
ClientSimple.createUser                     sample  13945   2.292 ± 0.060   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.686           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.075           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.675           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.464           ms/op
ClientSimple.createUser:createUser·p0.999   sample         40.632           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         42.409           ms/op
ClientSimple.createUser:createUser·p1.00    sample         42.926           ms/op
ClientSimple.existUser                      sample  17604   1.816 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.494           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.755           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.191           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.133           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.916           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.176           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.189           ms/op
ClientSimple.getUser                        sample  16084   1.992 ± 0.054   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.212           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.767           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.355           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.597           ms/op
ClientSimple.getUser:getUser·p0.999         sample         41.913           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         54.392           ms/op
ClientSimple.getUser:getUser·p1.00          sample         54.591           ms/op
ClientSimple.listUser                       sample   8489   3.770 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.227           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.711           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.571           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.026           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.667           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.801           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.122           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.122           ms/op

Benchmark result is saved to 1713312922815.json
