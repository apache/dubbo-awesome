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
# Warmup Iteration   1: 1.767 ops/ms
Iteration   1: 6.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.927 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.532 ops/ms
Iteration   1: 12.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.635 ops/ms


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
# Warmup Iteration   1: 6.258 ops/ms
Iteration   1: 12.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.755 ops/ms


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
# Warmup Iteration   1: 4.760 ops/ms
Iteration   1: 9.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.583 ops/ms


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.092 ms/op
Iteration   1: 1.957 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.957 ms/op


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
# Warmup Iteration   1: 3.661 ±(99.9%) 0.066 ms/op
Iteration   1: 1.993 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.993 ms/op


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
# Warmup Iteration   1: 3.272 ±(99.9%) 0.059 ms/op
Iteration   1: 1.862 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.862 ms/op


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
# Warmup Iteration   1: 5.482 ±(99.9%) 0.122 ms/op
Iteration   1: 3.609 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.609 ms/op


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
# Warmup Iteration   1: 3.577 ±(99.9%) 0.084 ms/op
Iteration   1: 1.996 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   1.796 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.707 ms/op
                 createUser·p0.99:   3.416 ms/op
                 createUser·p0.999:  24.575 ms/op
                 createUser·p0.9999: 25.375 ms/op
                 createUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16018
  mean =      1.996 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14442 
    [ 2.500,  5.000) = 1493 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.416 ms/op
     p(99.9000) =     24.575 ms/op
     p(99.9900) =     25.375 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 2.961 ±(99.9%) 0.063 ms/op
Iteration   1: 1.792 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   1.692 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  13.894 ms/op
                 existUser·p0.9999: 13.979 ms/op
                 existUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17874
  mean =      1.792 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2119 
    [ 1.250,  2.500) = 14803 
    [ 2.500,  3.750) = 724 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.692 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     13.979 ms/op
     p(99.9990) =     13.992 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.311 ±(99.9%) 0.097 ms/op
Iteration   1: 2.274 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.432 ms/op
                 getUser·p0.50:   2.331 ms/op
                 getUser·p0.90:   2.773 ms/op
                 getUser·p0.95:   2.997 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  11.469 ms/op
                 getUser·p0.9999: 12.611 ms/op
                 getUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14323
  mean =      2.274 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 431 
    [ 1.250,  2.500) = 8778 
    [ 2.500,  3.750) = 4927 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      2.331 ms/op
     p(90.0000) =      2.773 ms/op
     p(95.0000) =      2.997 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =     11.469 ms/op
     p(99.9900) =     12.611 ms/op
     p(99.9990) =     12.632 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.128 ms/op
Iteration   1: 3.518 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   8.621 ms/op
                 listUser·p0.999:  14.203 ms/op
                 listUser·p0.9999: 14.909 ms/op
                 listUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9090
  mean =      3.518 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1351 
    [ 2.500,  3.750) = 4650 
    [ 3.750,  5.000) = 2883 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      8.621 ms/op
     p(99.9000) =     14.203 ms/op
     p(99.9900) =     14.909 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.927          ops/ms
ClientSimple.existUser                       thrpt         12.635          ops/ms
ClientSimple.getUser                         thrpt         12.755          ops/ms
ClientSimple.listUser                        thrpt          9.583          ops/ms
ClientSimple.createUser                       avgt          1.957           ms/op
ClientSimple.existUser                        avgt          1.993           ms/op
ClientSimple.getUser                          avgt          1.862           ms/op
ClientSimple.listUser                         avgt          3.609           ms/op
ClientSimple.createUser                     sample  16018   1.996 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.598           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.796           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.416           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.575           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.375           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.395           ms/op
ClientSimple.existUser                      sample  17874   1.792 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.644           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.692           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.522           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.894           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.979           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.992           ms/op
ClientSimple.getUser                        sample  14323   2.274 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.432           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.331           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.773           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.997           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.043           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.469           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.611           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.632           ms/op
ClientSimple.listUser                       sample   9090   3.518 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.100           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.576           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.563           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.621           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.203           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.909           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.909           ms/op

Benchmark result is saved to 1713182784582.json
