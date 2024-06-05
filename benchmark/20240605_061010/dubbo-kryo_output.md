# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.555 ops/ms
Iteration   1: 8.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.286 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.009 ops/ms
Iteration   1: 13.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.528 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.400 ops/ms
Iteration   1: 13.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.945 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.144 ops/ms
Iteration   1: 9.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.023 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.057 ms/op
Iteration   1: 2.170 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.170 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.709 ±(99.9%) 0.048 ms/op
Iteration   1: 1.779 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.779 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.767 ±(99.9%) 0.072 ms/op
Iteration   1: 2.077 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.077 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.969 ±(99.9%) 0.078 ms/op
Iteration   1: 2.960 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.960 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.298 ±(99.9%) 0.086 ms/op
Iteration   1: 2.119 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   1.886 ms/op
                 createUser·p0.90:   2.736 ms/op
                 createUser·p0.95:   2.986 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  16.499 ms/op
                 createUser·p0.9999: 17.760 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15094
  mean =      2.119 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 12309 
    [ 2.500,  3.750) = 2328 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.071 ±(99.9%) 0.073 ms/op
Iteration   1: 1.809 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   1.696 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.408 ms/op
                 existUser·p0.99:   3.776 ms/op
                 existUser·p0.999:  19.759 ms/op
                 existUser·p0.9999: 19.825 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17672
  mean =      1.809 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1566 
    [ 1.250,  2.500) = 15441 
    [ 2.500,  3.750) = 487 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      3.776 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.286 ±(99.9%) 0.083 ms/op
Iteration   1: 2.149 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.630 ms/op
                 getUser·p0.50:   2.058 ms/op
                 getUser·p0.90:   2.634 ms/op
                 getUser·p0.95:   2.892 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  9.878 ms/op
                 getUser·p0.9999: 12.050 ms/op
                 getUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15026
  mean =      2.149 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 12739 
    [ 2.500,  3.750) = 1949 
    [ 3.750,  5.000) = 99 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      9.878 ms/op
     p(99.9900) =     12.050 ms/op
     p(99.9990) =     12.124 ms/op
     p(99.9999) =     12.124 ms/op
    p(100.0000) =     12.124 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.206 ±(99.9%) 0.109 ms/op
Iteration   1: 3.284 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.708 ms/op
                 listUser·p0.50:   3.273 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.988 ms/op
                 listUser·p0.999:  15.113 ms/op
                 listUser·p0.9999: 15.385 ms/op
                 listUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9801
  mean =      3.284 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 1413 
    [ 2.500,  3.750) = 6054 
    [ 3.750,  5.000) = 2136 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     15.113 ms/op
     p(99.9900) =     15.385 ms/op
     p(99.9990) =     15.385 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.286          ops/ms
ClientSimple.existUser                       thrpt         13.528          ops/ms
ClientSimple.getUser                         thrpt         13.945          ops/ms
ClientSimple.listUser                        thrpt          9.023          ops/ms
ClientSimple.createUser                       avgt          2.170           ms/op
ClientSimple.existUser                        avgt          1.779           ms/op
ClientSimple.getUser                          avgt          2.077           ms/op
ClientSimple.listUser                         avgt          2.960           ms/op
ClientSimple.createUser                     sample  15094   2.119 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.873           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.886           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.736           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.986           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.587           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.499           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.760           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.760           ms/op
ClientSimple.existUser                      sample  17672   1.809 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.534           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.696           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.776           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.759           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.825           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.825           ms/op
ClientSimple.getUser                        sample  15026   2.149 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.630           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.058           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.071           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.878           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.050           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.124           ms/op
ClientSimple.listUser                       sample   9801   3.284 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.708           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.273           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.988           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.113           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.385           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.385           ms/op

Benchmark result is saved to 1717567541357.json
