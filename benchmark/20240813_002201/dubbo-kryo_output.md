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
# Warmup Iteration   1: 1.630 ops/ms
Iteration   1: 6.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.863 ops/ms


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
# Warmup Iteration   1: 6.077 ops/ms
Iteration   1: 12.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.742 ops/ms


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
# Warmup Iteration   1: 5.619 ops/ms
Iteration   1: 13.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.494 ops/ms


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
# Warmup Iteration   1: 3.605 ops/ms
Iteration   1: 8.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.443 ops/ms


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.076 ms/op
Iteration   1: 2.187 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.187 ms/op


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
# Warmup Iteration   1: 3.115 ±(99.9%) 0.058 ms/op
Iteration   1: 1.723 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.723 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.059 ms/op
Iteration   1: 2.204 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.204 ms/op


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
# Warmup Iteration   1: 4.623 ±(99.9%) 0.086 ms/op
Iteration   1: 3.066 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.066 ms/op


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
# Warmup Iteration   1: 3.387 ±(99.9%) 0.076 ms/op
Iteration   1: 2.085 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.473 ms/op
                 createUser·p0.50:   1.835 ms/op
                 createUser·p0.90:   2.646 ms/op
                 createUser·p0.95:   2.978 ms/op
                 createUser·p0.99:   9.060 ms/op
                 createUser·p0.999:  23.691 ms/op
                 createUser·p0.9999: 23.980 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15330
  mean =      2.085 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13487 
    [ 2.500,  5.000) = 1544 
    [ 5.000,  7.500) = 123 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     23.691 ms/op
     p(99.9900) =     23.980 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 3.085 ±(99.9%) 0.073 ms/op
Iteration   1: 2.183 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   2.150 ms/op
                 existUser·p0.90:   2.576 ms/op
                 existUser·p0.95:   2.769 ms/op
                 existUser·p0.99:   3.529 ms/op
                 existUser·p0.999:  12.015 ms/op
                 existUser·p0.9999: 12.698 ms/op
                 existUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14643
  mean =      2.183 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 12443 
    [ 2.500,  3.750) = 1993 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      3.529 ms/op
     p(99.9000) =     12.015 ms/op
     p(99.9900) =     12.698 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


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
# Warmup Iteration   1: 3.214 ±(99.9%) 0.070 ms/op
Iteration   1: 1.854 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.522 ms/op
                 getUser·p0.50:   1.714 ms/op
                 getUser·p0.90:   2.261 ms/op
                 getUser·p0.95:   2.404 ms/op
                 getUser·p0.99:   3.011 ms/op
                 getUser·p0.999:  21.444 ms/op
                 getUser·p0.9999: 21.678 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17595
  mean =      1.854 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17093 
    [ 2.500,  5.000) = 395 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.404 ms/op
     p(99.0000) =      3.011 ms/op
     p(99.9000) =     21.444 ms/op
     p(99.9900) =     21.678 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.136 ms/op
Iteration   1: 3.102 ±(99.9%) 0.066 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   2.839 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  35.238 ms/op
                 listUser·p0.9999: 35.910 ms/op
                 listUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10304
  mean =      3.102 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2339 
    [ 2.500,  5.000) = 7781 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     35.238 ms/op
     p(99.9900) =     35.910 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.863          ops/ms
ClientSimple.existUser                       thrpt         12.742          ops/ms
ClientSimple.getUser                         thrpt         13.494          ops/ms
ClientSimple.listUser                        thrpt          8.443          ops/ms
ClientSimple.createUser                       avgt          2.187           ms/op
ClientSimple.existUser                        avgt          1.723           ms/op
ClientSimple.getUser                          avgt          2.204           ms/op
ClientSimple.listUser                         avgt          3.066           ms/op
ClientSimple.createUser                     sample  15330   2.085 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.473           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.835           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.060           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.691           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.980           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.084           ms/op
ClientSimple.existUser                      sample  14643   2.183 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.663           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.769           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.529           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.015           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.698           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.698           ms/op
ClientSimple.getUser                        sample  17595   1.854 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.522           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.714           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.261           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.011           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.444           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.678           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.151           ms/op
ClientSimple.listUser                       sample  10304   3.102 ± 0.066   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.015           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.839           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.817           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.108           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.078           ms/op
ClientSimple.listUser:listUser·p0.999       sample         35.238           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         35.910           ms/op
ClientSimple.listUser:listUser·p1.00        sample         35.914           ms/op

Benchmark result is saved to 1723508261827.json
