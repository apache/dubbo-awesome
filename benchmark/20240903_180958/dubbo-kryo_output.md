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
# Warmup Iteration   1: 2.027 ops/ms
Iteration   1: 7.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.656 ops/ms


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
# Warmup Iteration   1: 5.630 ops/ms
Iteration   1: 11.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.179 ops/ms


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
# Warmup Iteration   1: 5.760 ops/ms
Iteration   1: 12.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.560 ops/ms


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
# Warmup Iteration   1: 4.126 ops/ms
Iteration   1: 8.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.226 ops/ms


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
# Warmup Iteration   1: 4.604 ±(99.9%) 0.099 ms/op
Iteration   1: 2.076 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.076 ms/op


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
# Warmup Iteration   1: 3.663 ±(99.9%) 0.060 ms/op
Iteration   1: 1.975 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.975 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.059 ms/op
Iteration   1: 1.899 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.899 ms/op


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.092 ms/op
Iteration   1: 3.428 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.428 ms/op


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.101 ms/op
Iteration   1: 2.633 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   0.544 ms/op
                 createUser·p0.50:   2.310 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   11.239 ms/op
                 createUser·p0.999:  30.736 ms/op
                 createUser·p0.9999: 30.835 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12120
  mean =      2.633 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7379 
    [ 2.500,  5.000) = 4233 
    [ 5.000,  7.500) = 232 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      2.310 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =     11.239 ms/op
     p(99.9000) =     30.736 ms/op
     p(99.9900) =     30.835 ms/op
     p(99.9990) =     30.835 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 3.090 ±(99.9%) 0.081 ms/op
Iteration   1: 1.901 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   3.687 ms/op
                 existUser·p0.999:  13.028 ms/op
                 existUser·p0.9999: 13.360 ms/op
                 existUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16827
  mean =      1.901 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 359 
    [ 1.250,  2.500) = 15040 
    [ 2.500,  3.750) = 1263 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      3.687 ms/op
     p(99.9000) =     13.028 ms/op
     p(99.9900) =     13.360 ms/op
     p(99.9990) =     13.517 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


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
# Warmup Iteration   1: 3.549 ±(99.9%) 0.089 ms/op
Iteration   1: 2.026 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   1.839 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   2.982 ms/op
                 getUser·p0.99:   3.721 ms/op
                 getUser·p0.999:  14.923 ms/op
                 getUser·p0.9999: 15.139 ms/op
                 getUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15790
  mean =      2.026 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 13435 
    [ 2.500,  3.750) = 2097 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      3.721 ms/op
     p(99.9000) =     14.923 ms/op
     p(99.9900) =     15.139 ms/op
     p(99.9990) =     15.139 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 4.709 ±(99.9%) 0.164 ms/op
Iteration   1: 3.470 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.638 ms/op
                 listUser·p0.99:   7.183 ms/op
                 listUser·p0.999:  8.028 ms/op
                 listUser·p0.9999: 8.634 ms/op
                 listUser·p1.00:   8.634 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9216
  mean =      3.470 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 60 
    [1.500, 2.000) = 156 
    [2.000, 2.500) = 909 
    [2.500, 3.000) = 1749 
    [3.000, 3.500) = 1547 
    [3.500, 4.000) = 2863 
    [4.000, 4.500) = 1294 
    [4.500, 5.000) = 346 
    [5.000, 5.500) = 79 
    [5.500, 6.000) = 70 
    [6.000, 6.500) = 17 
    [6.500, 7.000) = 22 
    [7.000, 7.500) = 15 
    [7.500, 8.000) = 70 
    [8.000, 8.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.638 ms/op
     p(99.0000) =      7.183 ms/op
     p(99.9000) =      8.028 ms/op
     p(99.9900) =      8.634 ms/op
     p(99.9990) =      8.634 ms/op
     p(99.9999) =      8.634 ms/op
    p(100.0000) =      8.634 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.656          ops/ms
ClientSimple.existUser                       thrpt         11.179          ops/ms
ClientSimple.getUser                         thrpt         12.560          ops/ms
ClientSimple.listUser                        thrpt          8.226          ops/ms
ClientSimple.createUser                       avgt          2.076           ms/op
ClientSimple.existUser                        avgt          1.975           ms/op
ClientSimple.getUser                          avgt          1.899           ms/op
ClientSimple.listUser                         avgt          3.428           ms/op
ClientSimple.createUser                     sample  12120   2.633 ± 0.061   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.544           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.310           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.031           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.002           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.239           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.736           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.835           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.835           ms/op
ClientSimple.existUser                      sample  16827   1.901 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.555           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.687           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.028           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.360           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.517           ms/op
ClientSimple.getUser                        sample  15790   2.026 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.825           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.839           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.982           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.721           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.923           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.139           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.139           ms/op
ClientSimple.listUser                       sample   9216   3.470 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.800           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.535           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.638           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.183           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.028           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.634           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.634           ms/op

Benchmark result is saved to 1725386742197.json
