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
# Warmup Iteration   1: 1.717 ops/ms
Iteration   1: 7.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.562 ops/ms


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
# Warmup Iteration   1: 6.899 ops/ms
Iteration   1: 14.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.304 ops/ms


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
# Warmup Iteration   1: 5.584 ops/ms
Iteration   1: 12.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.718 ops/ms


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
# Warmup Iteration   1: 4.916 ops/ms
Iteration   1: 7.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.962 ops/ms


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.080 ms/op
Iteration   1: 2.191 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.191 ms/op


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
# Warmup Iteration   1: 3.402 ±(99.9%) 0.054 ms/op
Iteration   1: 2.068 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.068 ms/op


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
# Warmup Iteration   1: 3.318 ±(99.9%) 0.060 ms/op
Iteration   1: 2.169 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.169 ms/op


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
# Warmup Iteration   1: 4.434 ±(99.9%) 0.089 ms/op
Iteration   1: 3.638 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.638 ms/op


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
# Warmup Iteration   1: 3.661 ±(99.9%) 0.116 ms/op
Iteration   1: 2.179 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   2.068 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.826 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  16.789 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14629
  mean =      2.179 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12711 
    [ 2.500,  5.000) = 1717 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.068 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     16.789 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.072 ms/op
Iteration   1: 1.886 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   3.065 ms/op
                 existUser·p0.999:  14.729 ms/op
                 existUser·p0.9999: 15.263 ms/op
                 existUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16988
  mean =      1.886 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 236 
    [ 1.250,  2.500) = 16147 
    [ 2.500,  3.750) = 479 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.065 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     15.263 ms/op
     p(99.9990) =     15.286 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.117 ms/op
Iteration   1: 2.159 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.066 ms/op
                 getUser·p0.90:   2.900 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   4.655 ms/op
                 getUser·p0.999:  9.945 ms/op
                 getUser·p0.9999: 10.306 ms/op
                 getUser·p1.00:   10.338 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14877
  mean =      2.159 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 12 
    [ 1.000,  2.000) = 6885 
    [ 2.000,  3.000) = 6866 
    [ 3.000,  4.000) = 942 
    [ 4.000,  5.000) = 51 
    [ 5.000,  6.000) = 57 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 30 
    [ 9.000, 10.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      4.655 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     10.306 ms/op
     p(99.9990) =     10.338 ms/op
     p(99.9999) =     10.338 ms/op
    p(100.0000) =     10.338 ms/op


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
# Warmup Iteration   1: 5.005 ±(99.9%) 0.151 ms/op
Iteration   1: 3.498 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.076 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.823 ms/op
                 listUser·p0.99:   13.697 ms/op
                 listUser·p0.999:  17.428 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9125
  mean =      3.498 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 337 
    [ 2.500,  3.750) = 6185 
    [ 3.750,  5.000) = 2224 
    [ 5.000,  6.250) = 211 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.823 ms/op
     p(99.0000) =     13.697 ms/op
     p(99.9000) =     17.428 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.562          ops/ms
ClientSimple.existUser                       thrpt         14.304          ops/ms
ClientSimple.getUser                         thrpt         12.718          ops/ms
ClientSimple.listUser                        thrpt          7.962          ops/ms
ClientSimple.createUser                       avgt          2.191           ms/op
ClientSimple.existUser                        avgt          2.068           ms/op
ClientSimple.getUser                          avgt          2.169           ms/op
ClientSimple.listUser                         avgt          3.638           ms/op
ClientSimple.createUser                     sample  14629   2.179 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.738           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.068           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.826           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.464           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.789           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.217           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.217           ms/op
ClientSimple.existUser                      sample  16988   1.886 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.643           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.753           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.065           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.729           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.263           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.286           ms/op
ClientSimple.getUser                        sample  14877   2.159 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.735           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.066           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.129           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.655           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.945           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.306           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.338           ms/op
ClientSimple.listUser                       sample   9125   3.498 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.067           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.076           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.823           ms/op
ClientSimple.listUser:listUser·p0.99        sample         13.697           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.428           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.465           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.465           ms/op

Benchmark result is saved to 1722233175010.json
