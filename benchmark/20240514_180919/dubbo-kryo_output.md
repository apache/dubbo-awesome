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
# Warmup Iteration   1: 1.531 ops/ms
Iteration   1: 6.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.791 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.740 ops/ms
Iteration   1: 12.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.634 ops/ms


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
# Warmup Iteration   1: 5.974 ops/ms
Iteration   1: 11.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.585 ops/ms


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
# Warmup Iteration   1: 3.551 ops/ms
Iteration   1: 7.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.931 ops/ms


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.061 ms/op
Iteration   1: 2.194 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.194 ms/op


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
# Warmup Iteration   1: 2.886 ±(99.9%) 0.042 ms/op
Iteration   1: 1.854 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.854 ms/op


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
# Warmup Iteration   1: 3.566 ±(99.9%) 0.074 ms/op
Iteration   1: 2.241 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.241 ms/op


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
# Warmup Iteration   1: 4.765 ±(99.9%) 0.111 ms/op
Iteration   1: 2.924 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.924 ms/op


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
# Warmup Iteration   1: 3.376 ±(99.9%) 0.101 ms/op
Iteration   1: 2.066 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.447 ms/op
                 createUser·p0.50:   1.878 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.920 ms/op
                 createUser·p0.99:   9.541 ms/op
                 createUser·p0.999:  16.991 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15465
  mean =      2.066 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 691 
    [ 1.250,  2.500) = 12959 
    [ 2.500,  3.750) = 1523 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      9.541 ms/op
     p(99.9000) =     16.991 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.080 ±(99.9%) 0.075 ms/op
Iteration   1: 1.818 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.195 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   3.366 ms/op
                 existUser·p0.999:  11.567 ms/op
                 existUser·p0.9999: 11.665 ms/op
                 existUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17618
  mean =      1.818 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1040 
    [ 1.250,  2.500) = 15923 
    [ 2.500,  3.750) = 512 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      3.366 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     11.665 ms/op
     p(99.9999) =     11.665 ms/op
    p(100.0000) =     11.665 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.086 ms/op
Iteration   1: 1.956 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   1.827 ms/op
                 getUser·p0.90:   2.540 ms/op
                 getUser·p0.95:   2.900 ms/op
                 getUser·p0.99:   3.500 ms/op
                 getUser·p0.999:  12.326 ms/op
                 getUser·p0.9999: 13.819 ms/op
                 getUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16341
  mean =      1.956 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 272 
    [ 1.250,  2.500) = 14300 
    [ 2.500,  3.750) = 1650 
    [ 3.750,  5.000) = 23 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      3.500 ms/op
     p(99.9000) =     12.326 ms/op
     p(99.9900) =     13.819 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.128 ms/op
Iteration   1: 3.612 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.780 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.794 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.618 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8847
  mean =      3.612 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 941 
    [ 2.500,  3.750) = 4471 
    [ 3.750,  5.000) = 2713 
    [ 5.000,  6.250) = 556 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.794 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     14.618 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.791          ops/ms
ClientSimple.existUser                       thrpt         12.634          ops/ms
ClientSimple.getUser                         thrpt         11.585          ops/ms
ClientSimple.listUser                        thrpt          7.931          ops/ms
ClientSimple.createUser                       avgt          2.194           ms/op
ClientSimple.existUser                        avgt          1.854           ms/op
ClientSimple.getUser                          avgt          2.241           ms/op
ClientSimple.listUser                         avgt          2.924           ms/op
ClientSimple.createUser                     sample  15465   2.066 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.447           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.878           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.541           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.991           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.236           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.236           ms/op
ClientSimple.existUser                      sample  17618   1.818 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.665           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.772           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.366           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.567           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.665           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.665           ms/op
ClientSimple.getUser                        sample  16341   1.956 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.546           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.827           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.500           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.326           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.819           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.861           ms/op
ClientSimple.listUser                       sample   8847   3.612 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.780           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.486           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.794           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.218           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.726           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.618           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.071           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.071           ms/op

Benchmark result is saved to 1715709898520.json
