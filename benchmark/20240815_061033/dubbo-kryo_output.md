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
# Warmup Iteration   1: 1.776 ops/ms
Iteration   1: 6.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.592 ops/ms


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
# Warmup Iteration   1: 6.525 ops/ms
Iteration   1: 11.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.734 ops/ms


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
# Warmup Iteration   1: 5.113 ops/ms
Iteration   1: 12.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.012 ops/ms


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
# Warmup Iteration   1: 5.734 ops/ms
Iteration   1: 8.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.610 ops/ms


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.071 ms/op
Iteration   1: 1.971 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.971 ms/op


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
# Warmup Iteration   1: 3.441 ±(99.9%) 0.056 ms/op
Iteration   1: 2.038 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.038 ms/op


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
# Warmup Iteration   1: 3.461 ±(99.9%) 0.068 ms/op
Iteration   1: 1.883 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.883 ms/op


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.086 ms/op
Iteration   1: 3.317 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.317 ms/op


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.103 ms/op
Iteration   1: 2.044 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.464 ms/op
                 createUser·p0.50:   1.761 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.971 ms/op
                 createUser·p0.99:   6.203 ms/op
                 createUser·p0.999:  22.708 ms/op
                 createUser·p0.9999: 28.507 ms/op
                 createUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15593
  mean =      2.044 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13300 
    [ 2.500,  5.000) = 2075 
    [ 5.000,  7.500) = 111 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.971 ms/op
     p(99.0000) =      6.203 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     28.507 ms/op
     p(99.9990) =     28.672 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 3.511 ±(99.9%) 0.184 ms/op
Iteration   1: 1.748 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   1.651 ms/op
                 existUser·p0.90:   2.122 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 12.697 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18273
  mean =      1.748 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 788 
    [ 1.250,  2.500) = 16895 
    [ 2.500,  3.750) = 424 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      1.651 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      3.412 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     12.697 ms/op
     p(99.9990) =     12.927 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


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
# Warmup Iteration   1: 3.405 ±(99.9%) 0.093 ms/op
Iteration   1: 2.176 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   2.085 ms/op
                 getUser·p0.90:   2.679 ms/op
                 getUser·p0.95:   2.871 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  11.260 ms/op
                 getUser·p0.9999: 11.544 ms/op
                 getUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14721
  mean =      2.176 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 11672 
    [ 2.500,  3.750) = 2756 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =     11.260 ms/op
     p(99.9900) =     11.544 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


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
# Warmup Iteration   1: 5.039 ±(99.9%) 0.155 ms/op
Iteration   1: 3.150 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  6.765 ms/op
                 listUser·p0.9999: 10.448 ms/op
                 listUser·p1.00:   10.502 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10153
  mean =      3.150 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 148 
    [ 2.000,  3.000) = 5402 
    [ 3.000,  4.000) = 3462 
    [ 4.000,  5.000) = 913 
    [ 5.000,  6.000) = 166 
    [ 6.000,  7.000) = 59 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      6.765 ms/op
     p(99.9900) =     10.448 ms/op
     p(99.9990) =     10.502 ms/op
     p(99.9999) =     10.502 ms/op
    p(100.0000) =     10.502 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.592          ops/ms
ClientSimple.existUser                       thrpt         11.734          ops/ms
ClientSimple.getUser                         thrpt         12.012          ops/ms
ClientSimple.listUser                        thrpt          8.610          ops/ms
ClientSimple.createUser                       avgt          1.971           ms/op
ClientSimple.existUser                        avgt          2.038           ms/op
ClientSimple.getUser                          avgt          1.883           ms/op
ClientSimple.listUser                         avgt          3.317           ms/op
ClientSimple.createUser                     sample  15593   2.044 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.464           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.761           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.971           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.203           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.708           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.507           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.672           ms/op
ClientSimple.existUser                      sample  18273   1.748 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.737           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.651           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.122           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.412           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.534           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.697           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.927           ms/op
ClientSimple.getUser                        sample  14721   2.176 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.715           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.085           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.871           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.936           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.260           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.544           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.567           ms/op
ClientSimple.listUser                       sample  10153   3.150 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.907           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.937           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.055           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.620           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.765           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.448           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.502           ms/op

Benchmark result is saved to 1723701965037.json
