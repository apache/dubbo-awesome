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
# Warmup Iteration   1: 1.343 ops/ms
Iteration   1: 6.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.904 ops/ms


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
# Warmup Iteration   1: 6.060 ops/ms
Iteration   1: 12.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.335 ops/ms


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
# Warmup Iteration   1: 5.342 ops/ms
Iteration   1: 13.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.507 ops/ms


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
# Warmup Iteration   1: 4.601 ops/ms
Iteration   1: 7.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.755 ops/ms


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.075 ms/op
Iteration   1: 2.109 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.109 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.067 ms/op
Iteration   1: 1.983 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.983 ms/op


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.066 ms/op
Iteration   1: 2.053 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.958 ±(99.9%) 0.112 ms/op
Iteration   1: 3.597 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.597 ms/op


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.096 ms/op
Iteration   1: 2.149 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   1.987 ms/op
                 createUser·p0.90:   2.687 ms/op
                 createUser·p0.95:   2.871 ms/op
                 createUser·p0.99:   5.478 ms/op
                 createUser·p0.999:  15.909 ms/op
                 createUser·p0.9999: 16.910 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14966
  mean =      2.149 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 404 
    [ 1.250,  2.500) = 12047 
    [ 2.500,  3.750) = 2184 
    [ 3.750,  5.000) = 156 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      5.478 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     16.910 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.304 ±(99.9%) 0.075 ms/op
Iteration   1: 2.351 ±(99.9%) 0.054 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.191 ms/op
                 existUser·p0.90:   2.818 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   5.539 ms/op
                 existUser·p0.999:  39.005 ms/op
                 existUser·p0.9999: 39.771 ms/op
                 existUser·p1.00:   39.846 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13826
  mean =      2.351 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10486 
    [ 2.500,  5.000) = 3149 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      5.539 ms/op
     p(99.9000) =     39.005 ms/op
     p(99.9900) =     39.771 ms/op
     p(99.9990) =     39.846 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.079 ms/op
Iteration   1: 2.274 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   2.216 ms/op
                 getUser·p0.90:   2.929 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  11.304 ms/op
                 getUser·p0.9999: 12.330 ms/op
                 getUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14059
  mean =      2.274 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 164 
    [ 1.250,  2.500) = 9886 
    [ 2.500,  3.750) = 3825 
    [ 3.750,  5.000) = 147 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.994 ms/op
     p(99.9000) =     11.304 ms/op
     p(99.9900) =     12.330 ms/op
     p(99.9990) =     12.370 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.134 ms/op
Iteration   1: 3.413 ±(99.9%) 0.065 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   3.289 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  31.130 ms/op
                 listUser·p0.9999: 31.523 ms/op
                 listUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9369
  mean =      3.413 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1294 
    [ 2.500,  5.000) = 7873 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     31.130 ms/op
     p(99.9900) =     31.523 ms/op
     p(99.9990) =     31.523 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.904          ops/ms
ClientSimple.existUser                       thrpt         12.335          ops/ms
ClientSimple.getUser                         thrpt         13.507          ops/ms
ClientSimple.listUser                        thrpt          7.755          ops/ms
ClientSimple.createUser                       avgt          2.109           ms/op
ClientSimple.existUser                        avgt          1.983           ms/op
ClientSimple.getUser                          avgt          2.053           ms/op
ClientSimple.listUser                         avgt          3.597           ms/op
ClientSimple.createUser                     sample  14966   2.149 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.633           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.987           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.478           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.909           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.910           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.236           ms/op
ClientSimple.existUser                      sample  13826   2.351 ± 0.054   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.575           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.191           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.818           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.068           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.539           ms/op
ClientSimple.existUser:existUser·p0.999     sample         39.005           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         39.771           ms/op
ClientSimple.existUser:existUser·p1.00      sample         39.846           ms/op
ClientSimple.getUser                        sample  14059   2.274 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.771           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.216           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.092           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.994           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.304           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.330           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.370           ms/op
ClientSimple.listUser                       sample   9369   3.413 ± 0.065   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.984           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.289           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.112           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.946           ms/op
ClientSimple.listUser:listUser·p0.999       sample         31.130           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.523           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.523           ms/op

Benchmark result is saved to 1723961125768.json
