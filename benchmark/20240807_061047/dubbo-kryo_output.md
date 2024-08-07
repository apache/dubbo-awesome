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
# Warmup Iteration   1: 1.686 ops/ms
Iteration   1: 6.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.072 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.897 ops/ms
Iteration   1: 12.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.563 ops/ms


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
# Warmup Iteration   1: 4.849 ops/ms
Iteration   1: 10.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.993 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.331 ops/ms
Iteration   1: 7.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.652 ops/ms


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
# Warmup Iteration   1: 3.665 ±(99.9%) 0.068 ms/op
Iteration   1: 2.032 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.032 ms/op


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
# Warmup Iteration   1: 3.291 ±(99.9%) 0.050 ms/op
Iteration   1: 2.113 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.113 ms/op


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
# Warmup Iteration   1: 3.069 ±(99.9%) 0.051 ms/op
Iteration   1: 2.244 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.244 ms/op


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.088 ms/op
Iteration   1: 3.438 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.438 ms/op


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
# Warmup Iteration   1: 3.487 ±(99.9%) 0.090 ms/op
Iteration   1: 2.137 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   1.978 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   2.907 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 19.742 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15085
  mean =      2.137 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 13150 
    [ 2.500,  3.750) = 1505 
    [ 3.750,  5.000) = 144 
    [ 5.000,  6.250) = 110 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.907 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     19.742 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 2.846 ±(99.9%) 0.070 ms/op
Iteration   1: 1.716 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.458 ms/op
                 existUser·p0.50:   1.585 ms/op
                 existUser·p0.90:   2.048 ms/op
                 existUser·p0.95:   2.253 ms/op
                 existUser·p0.99:   3.383 ms/op
                 existUser·p0.999:  27.450 ms/op
                 existUser·p0.9999: 28.024 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18651
  mean =      1.716 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18150 
    [ 2.500,  5.000) = 391 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      1.585 ms/op
     p(90.0000) =      2.048 ms/op
     p(95.0000) =      2.253 ms/op
     p(99.0000) =      3.383 ms/op
     p(99.9000) =     27.450 ms/op
     p(99.9900) =     28.024 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 3.502 ±(99.9%) 0.083 ms/op
Iteration   1: 1.886 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   1.659 ms/op
                 getUser·p0.90:   2.757 ms/op
                 getUser·p0.95:   2.945 ms/op
                 getUser·p0.99:   3.416 ms/op
                 getUser·p0.999:  12.615 ms/op
                 getUser·p0.9999: 12.829 ms/op
                 getUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17213
  mean =      1.886 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 811 
    [ 1.250,  2.500) = 13727 
    [ 2.500,  3.750) = 2529 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      1.659 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      3.416 ms/op
     p(99.9000) =     12.615 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     12.829 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


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
# Warmup Iteration   1: 4.271 ±(99.9%) 0.123 ms/op
Iteration   1: 3.344 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   3.322 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.402 ms/op
                 listUser·p0.999:  8.471 ms/op
                 listUser·p0.9999: 8.815 ms/op
                 listUser·p1.00:   8.815 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9560
  mean =      3.344 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 16 
    [1.500, 2.000) = 73 
    [2.000, 2.500) = 969 
    [2.500, 3.000) = 2313 
    [3.000, 3.500) = 2418 
    [3.500, 4.000) = 2212 
    [4.000, 4.500) = 970 
    [4.500, 5.000) = 388 
    [5.000, 5.500) = 121 
    [5.500, 6.000) = 20 
    [6.000, 6.500) = 19 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 4 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.402 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =      8.815 ms/op
     p(99.9990) =      8.815 ms/op
     p(99.9999) =      8.815 ms/op
    p(100.0000) =      8.815 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.072          ops/ms
ClientSimple.existUser                       thrpt         12.563          ops/ms
ClientSimple.getUser                         thrpt         10.993          ops/ms
ClientSimple.listUser                        thrpt          7.652          ops/ms
ClientSimple.createUser                       avgt          2.032           ms/op
ClientSimple.existUser                        avgt          2.113           ms/op
ClientSimple.getUser                          avgt          2.244           ms/op
ClientSimple.listUser                         avgt          3.438           ms/op
ClientSimple.createUser                     sample  15085   2.137 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.582           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.978           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.907           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.849           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.990           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.742           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.759           ms/op
ClientSimple.existUser                      sample  18651   1.716 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.458           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.585           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.048           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.253           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.383           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.450           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.024           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.279           ms/op
ClientSimple.getUser                        sample  17213   1.886 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.706           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.659           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.945           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.416           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.615           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.829           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.829           ms/op
ClientSimple.listUser                       sample   9560   3.344 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.001           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.322           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.402           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.471           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.815           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.815           ms/op

Benchmark result is saved to 1723010763456.json
