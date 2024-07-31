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
# Warmup Iteration   1: 2.175 ops/ms
Iteration   1: 6.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.698 ops/ms


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
# Warmup Iteration   1: 6.685 ops/ms
Iteration   1: 14.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.425 ops/ms


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
# Warmup Iteration   1: 5.751 ops/ms
Iteration   1: 11.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.433 ops/ms


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
# Warmup Iteration   1: 4.918 ops/ms
Iteration   1: 8.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.859 ops/ms


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.066 ms/op
Iteration   1: 2.053 ±(99.9%) 0.025 ms/op


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
# Warmup Iteration   1: 2.773 ±(99.9%) 0.048 ms/op
Iteration   1: 1.926 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.926 ms/op


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
# Warmup Iteration   1: 3.228 ±(99.9%) 0.052 ms/op
Iteration   1: 1.825 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.825 ms/op


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
# Warmup Iteration   1: 4.323 ±(99.9%) 0.076 ms/op
Iteration   1: 3.386 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.386 ms/op


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
# Warmup Iteration   1: 3.638 ±(99.9%) 0.089 ms/op
Iteration   1: 2.106 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   1.976 ms/op
                 createUser·p0.90:   2.650 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 17.317 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15161
  mean =      2.106 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 755 
    [ 1.250,  2.500) = 11829 
    [ 2.500,  3.750) = 2314 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      1.976 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     17.317 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.034 ±(99.9%) 0.073 ms/op
Iteration   1: 1.694 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.442 ms/op
                 existUser·p0.50:   1.622 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   2.822 ms/op
                 existUser·p0.999:  12.654 ms/op
                 existUser·p0.9999: 13.158 ms/op
                 existUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18825
  mean =      1.694 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1939 
    [ 1.250,  2.500) = 16092 
    [ 2.500,  3.750) = 728 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      1.622 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      2.822 ms/op
     p(99.9000) =     12.654 ms/op
     p(99.9900) =     13.158 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.121 ±(99.9%) 0.077 ms/op
Iteration   1: 2.253 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   2.154 ms/op
                 getUser·p0.90:   2.736 ms/op
                 getUser·p0.95:   2.904 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  34.341 ms/op
                 getUser·p0.9999: 34.865 ms/op
                 getUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14191
  mean =      2.253 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10786 
    [ 2.500,  5.000) = 3356 
    [ 5.000,  7.500) = 16 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.154 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =     34.341 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 4.431 ±(99.9%) 0.138 ms/op
Iteration   1: 3.171 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.235 ms/op
                 listUser·p0.999:  6.110 ms/op
                 listUser·p0.9999: 7.415 ms/op
                 listUser·p1.00:   7.422 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10151
  mean =      3.171 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 19 
    [1.500, 2.000) = 107 
    [2.000, 2.500) = 936 
    [2.500, 3.000) = 3918 
    [3.000, 3.500) = 1895 
    [3.500, 4.000) = 2286 
    [4.000, 4.500) = 755 
    [4.500, 5.000) = 114 
    [5.000, 5.500) = 75 
    [5.500, 6.000) = 33 
    [6.000, 6.500) = 6 
    [6.500, 7.000) = 6 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =      6.110 ms/op
     p(99.9900) =      7.415 ms/op
     p(99.9990) =      7.422 ms/op
     p(99.9999) =      7.422 ms/op
    p(100.0000) =      7.422 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.698          ops/ms
ClientSimple.existUser                       thrpt         14.425          ops/ms
ClientSimple.getUser                         thrpt         11.433          ops/ms
ClientSimple.listUser                        thrpt          8.859          ops/ms
ClientSimple.createUser                       avgt          2.053           ms/op
ClientSimple.existUser                        avgt          1.926           ms/op
ClientSimple.getUser                          avgt          1.825           ms/op
ClientSimple.listUser                         avgt          3.386           ms/op
ClientSimple.createUser                     sample  15161   2.106 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.764           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.976           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.650           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.858           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.203           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.317           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.334           ms/op
ClientSimple.existUser                      sample  18825   1.694 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.442           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.622           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.822           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.654           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.158           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.173           ms/op
ClientSimple.getUser                        sample  14191   2.253 ± 0.042   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.510           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.154           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.904           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.707           ms/op
ClientSimple.getUser:getUser·p0.999         sample         34.341           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         34.865           ms/op
ClientSimple.getUser:getUser·p1.00          sample         34.865           ms/op
ClientSimple.listUser                       sample  10151   3.171 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.098           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.023           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.990           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.235           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.110           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.415           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.422           ms/op

Benchmark result is saved to 1722384842905.json
