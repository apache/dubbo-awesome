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
# Warmup Iteration   1: 2.077 ops/ms
Iteration   1: 7.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.464 ops/ms


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
# Warmup Iteration   1: 7.319 ops/ms
Iteration   1: 12.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.984 ops/ms


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
# Warmup Iteration   1: 6.095 ops/ms
Iteration   1: 14.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.750 ops/ms


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
# Warmup Iteration   1: 4.086 ops/ms
Iteration   1: 8.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.277 ops/ms


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.095 ms/op
Iteration   1: 2.341 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.341 ms/op


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
# Warmup Iteration   1: 3.310 ±(99.9%) 0.057 ms/op
Iteration   1: 2.171 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.171 ms/op


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
# Warmup Iteration   1: 3.059 ±(99.9%) 0.058 ms/op
Iteration   1: 1.790 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.790 ms/op


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
# Warmup Iteration   1: 4.786 ±(99.9%) 0.092 ms/op
Iteration   1: 3.553 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.553 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.075 ms/op
Iteration   1: 2.373 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.863 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   7.474 ms/op
                 createUser·p0.999:  29.098 ms/op
                 createUser·p0.9999: 34.777 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13467
  mean =      2.373 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10351 
    [ 2.500,  5.000) = 2840 
    [ 5.000,  7.500) = 145 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.863 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      7.474 ms/op
     p(99.9000) =     29.098 ms/op
     p(99.9900) =     34.777 ms/op
     p(99.9990) =     34.800 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 2.899 ±(99.9%) 0.064 ms/op
Iteration   1: 1.958 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.402 ms/op
                 existUser·p0.50:   1.917 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   3.305 ms/op
                 existUser·p0.999:  17.367 ms/op
                 existUser·p0.9999: 17.641 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16435
  mean =      1.958 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 841 
    [ 1.250,  2.500) = 14484 
    [ 2.500,  3.750) = 999 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.305 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     17.641 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.084 ms/op
Iteration   1: 1.885 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   1.739 ms/op
                 getUser·p0.90:   2.150 ms/op
                 getUser·p0.95:   2.384 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  24.119 ms/op
                 getUser·p0.9999: 26.159 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16971
  mean =      1.885 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16325 
    [ 2.500,  5.000) = 522 
    [ 5.000,  7.500) = 23 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      1.739 ms/op
     p(90.0000) =      2.150 ms/op
     p(95.0000) =      2.384 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =     24.119 ms/op
     p(99.9900) =     26.159 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 4.461 ±(99.9%) 0.151 ms/op
Iteration   1: 3.338 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.265 ms/op
                 listUser·p0.90:   4.180 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.463 ms/op
                 listUser·p0.999:  26.214 ms/op
                 listUser·p0.9999: 26.739 ms/op
                 listUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9615
  mean =      3.338 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1302 
    [ 2.500,  5.000) = 8180 
    [ 5.000,  7.500) = 100 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      4.180 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.463 ms/op
     p(99.9000) =     26.214 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     26.739 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.464          ops/ms
ClientSimple.existUser                       thrpt         12.984          ops/ms
ClientSimple.getUser                         thrpt         14.750          ops/ms
ClientSimple.listUser                        thrpt          8.277          ops/ms
ClientSimple.createUser                       avgt          2.341           ms/op
ClientSimple.existUser                        avgt          2.171           ms/op
ClientSimple.getUser                          avgt          1.790           ms/op
ClientSimple.listUser                         avgt          3.553           ms/op
ClientSimple.createUser                     sample  13467   2.373 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.605           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.146           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.474           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.098           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.777           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.800           ms/op
ClientSimple.existUser                      sample  16435   1.958 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.402           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.917           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.305           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.367           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.641           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.662           ms/op
ClientSimple.getUser                        sample  16971   1.885 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.601           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.739           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.150           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.384           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.334           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.119           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.159           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.182           ms/op
ClientSimple.listUser                       sample   9615   3.338 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.031           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.265           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.180           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.463           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.214           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.739           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.739           ms/op

Benchmark result is saved to 1721498746802.json
