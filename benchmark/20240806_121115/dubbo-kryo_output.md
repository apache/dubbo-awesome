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
# Warmup Iteration   1: 1.990 ops/ms
Iteration   1: 7.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.569 ops/ms


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
# Warmup Iteration   1: 5.815 ops/ms
Iteration   1: 12.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.721 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.681 ops/ms
Iteration   1: 13.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.052 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.302 ops/ms
Iteration   1: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.529 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.782 ±(99.9%) 0.065 ms/op
Iteration   1: 2.053 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.053 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.140 ±(99.9%) 0.051 ms/op
Iteration   1: 1.817 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.817 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.199 ±(99.9%) 0.056 ms/op
Iteration   1: 2.238 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.238 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.081 ms/op
Iteration   1: 3.976 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.976 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.117 ms/op
Iteration   1: 2.186 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.609 ms/op
                 createUser·p0.50:   2.073 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.793 ms/op
                 createUser·p0.99:   6.036 ms/op
                 createUser·p0.999:  17.760 ms/op
                 createUser·p0.9999: 19.804 ms/op
                 createUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14621
  mean =      2.186 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12470 
    [ 2.500,  5.000) = 1935 
    [ 5.000,  7.500) = 117 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      2.073 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      6.036 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     19.804 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 3.247 ±(99.9%) 0.083 ms/op
Iteration   1: 2.014 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   1.923 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   3.762 ms/op
                 existUser·p0.999:  27.013 ms/op
                 existUser·p0.9999: 27.781 ms/op
                 existUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15880
  mean =      2.014 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14726 
    [ 2.500,  5.000) = 1090 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.762 ms/op
     p(99.9000) =     27.013 ms/op
     p(99.9900) =     27.781 ms/op
     p(99.9990) =     27.820 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 3.202 ±(99.9%) 0.074 ms/op
Iteration   1: 2.059 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   1.843 ms/op
                 getUser·p0.90:   2.564 ms/op
                 getUser·p0.95:   2.789 ms/op
                 getUser·p0.99:   5.198 ms/op
                 getUser·p0.999:  18.743 ms/op
                 getUser·p0.9999: 19.259 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15643
  mean =      2.059 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 184 
    [ 1.250,  2.500) = 13550 
    [ 2.500,  3.750) = 1665 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      5.198 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     19.259 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 4.444 ±(99.9%) 0.143 ms/op
Iteration   1: 3.300 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.542 ms/op
                 listUser·p0.50:   3.211 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.691 ms/op
                 listUser·p0.999:  21.342 ms/op
                 listUser·p0.9999: 22.708 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9708
  mean =      3.300 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2377 
    [ 2.500,  5.000) = 7104 
    [ 5.000,  7.500) = 173 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.691 ms/op
     p(99.9000) =     21.342 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.569          ops/ms
ClientSimple.existUser                       thrpt         12.721          ops/ms
ClientSimple.getUser                         thrpt         13.052          ops/ms
ClientSimple.listUser                        thrpt          8.529          ops/ms
ClientSimple.createUser                       avgt          2.053           ms/op
ClientSimple.existUser                        avgt          1.817           ms/op
ClientSimple.getUser                          avgt          2.238           ms/op
ClientSimple.listUser                         avgt          3.976           ms/op
ClientSimple.createUser                     sample  14621   2.186 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.609           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.073           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.036           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.760           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.804           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.349           ms/op
ClientSimple.existUser                      sample  15880   2.014 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.495           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.923           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.762           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.013           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.781           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.820           ms/op
ClientSimple.getUser                        sample  15643   2.059 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.709           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.843           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.198           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.743           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.259           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.333           ms/op
ClientSimple.listUser                       sample   9708   3.300 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.542           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.211           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.691           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.342           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.708           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.708           ms/op

Benchmark result is saved to 1722946024143.json
