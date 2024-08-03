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
# Warmup Iteration   1: 1.627 ops/ms
Iteration   1: 7.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.148 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.793 ops/ms
Iteration   1: 14.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.225 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.691 ops/ms
Iteration   1: 11.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.870 ops/ms


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
# Warmup Iteration   1: 5.334 ops/ms
Iteration   1: 7.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.673 ops/ms


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
# Warmup Iteration   1: 3.587 ±(99.9%) 0.063 ms/op
Iteration   1: 2.136 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.136 ms/op


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
# Warmup Iteration   1: 3.065 ±(99.9%) 0.058 ms/op
Iteration   1: 1.932 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.180 ±(99.9%) 0.057 ms/op
Iteration   1: 2.003 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.003 ms/op


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
# Warmup Iteration   1: 4.325 ±(99.9%) 0.089 ms/op
Iteration   1: 3.383 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.383 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.099 ms/op
Iteration   1: 2.210 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.424 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.560 ms/op
                 createUser·p0.95:   2.777 ms/op
                 createUser·p0.99:   5.542 ms/op
                 createUser·p0.999:  17.793 ms/op
                 createUser·p0.9999: 18.938 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14460
  mean =      2.210 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 459 
    [ 1.250,  2.500) = 12001 
    [ 2.500,  3.750) = 1745 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      5.542 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     18.938 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.103 ms/op
Iteration   1: 1.999 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   1.907 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   3.850 ms/op
                 existUser·p0.999:  11.616 ms/op
                 existUser·p0.9999: 11.879 ms/op
                 existUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15993
  mean =      1.999 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 15110 
    [ 2.500,  3.750) = 667 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =     11.616 ms/op
     p(99.9900) =     11.879 ms/op
     p(99.9990) =     12.026 ms/op
     p(99.9999) =     12.026 ms/op
    p(100.0000) =     12.026 ms/op


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
# Warmup Iteration   1: 3.429 ±(99.9%) 0.088 ms/op
Iteration   1: 2.230 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   2.126 ms/op
                 getUser·p0.90:   2.683 ms/op
                 getUser·p0.95:   2.859 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  12.823 ms/op
                 getUser·p0.9999: 14.292 ms/op
                 getUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14348
  mean =      2.230 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 10904 
    [ 2.500,  3.750) = 3227 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =     12.823 ms/op
     p(99.9900) =     14.292 ms/op
     p(99.9990) =     14.598 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 4.697 ±(99.9%) 0.182 ms/op
Iteration   1: 3.544 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.388 ms/op
                 listUser·p0.999:  8.582 ms/op
                 listUser·p0.9999: 11.026 ms/op
                 listUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9018
  mean =      3.544 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 729 
    [ 2.500,  3.750) = 4726 
    [ 3.750,  5.000) = 3297 
    [ 5.000,  6.250) = 162 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.388 ms/op
     p(99.9000) =      8.582 ms/op
     p(99.9900) =     11.026 ms/op
     p(99.9990) =     11.026 ms/op
     p(99.9999) =     11.026 ms/op
    p(100.0000) =     11.026 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.148          ops/ms
ClientSimple.existUser                       thrpt         14.225          ops/ms
ClientSimple.getUser                         thrpt         11.870          ops/ms
ClientSimple.listUser                        thrpt          7.673          ops/ms
ClientSimple.createUser                       avgt          2.136           ms/op
ClientSimple.existUser                        avgt          1.932           ms/op
ClientSimple.getUser                          avgt          2.003           ms/op
ClientSimple.listUser                         avgt          3.383           ms/op
ClientSimple.createUser                     sample  14460   2.210 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.424           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.560           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.777           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.542           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.793           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.938           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.464           ms/op
ClientSimple.existUser                      sample  15993   1.999 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.969           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.907           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.850           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.616           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.879           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.026           ms/op
ClientSimple.getUser                        sample  14348   2.230 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.804           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.126           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.129           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.823           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.292           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.598           ms/op
ClientSimple.listUser                       sample   9018   3.544 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.951           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.580           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.388           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.582           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.026           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.026           ms/op

Benchmark result is saved to 1722644175872.json
