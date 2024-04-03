# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.900 ops/ms
Iteration   1: 7.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.252 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.623 ops/ms
Iteration   1: 13.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.421 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.489 ops/ms
Iteration   1: 13.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.635 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.339 ops/ms
Iteration   1: 8.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.419 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.408 ±(99.9%) 0.080 ms/op
Iteration   1: 2.068 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.068 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.143 ±(99.9%) 0.050 ms/op
Iteration   1: 1.867 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.018 ±(99.9%) 0.050 ms/op
Iteration   1: 1.879 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.879 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.278 ±(99.9%) 0.080 ms/op
Iteration   1: 3.186 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.186 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ±(99.9%) 0.097 ms/op
Iteration   1: 2.036 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   1.884 ms/op
                 createUser·p0.90:   2.466 ms/op
                 createUser·p0.95:   2.720 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  14.161 ms/op
                 createUser·p0.9999: 16.602 ms/op
                 createUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15703
  mean =      2.036 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 14211 
    [ 2.500,  3.750) = 1090 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     14.161 ms/op
     p(99.9900) =     16.602 ms/op
     p(99.9990) =     16.695 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.148 ±(99.9%) 0.079 ms/op
Iteration   1: 2.008 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.409 ms/op
                 existUser·p0.50:   1.935 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   3.504 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 13.382 ms/op
                 existUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16062
  mean =      2.008 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 307 
    [ 1.250,  2.500) = 14352 
    [ 2.500,  3.750) = 1266 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.409 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.504 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     13.382 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.304 ±(99.9%) 0.087 ms/op
Iteration   1: 2.051 ±(99.9%) 0.059 ms/op
                 getUser·p0.00:   0.246 ms/op
                 getUser·p0.50:   1.806 ms/op
                 getUser·p0.90:   2.474 ms/op
                 getUser·p0.95:   2.691 ms/op
                 getUser·p0.99:   5.742 ms/op
                 getUser·p0.999:  51.773 ms/op
                 getUser·p0.9999: 55.510 ms/op
                 getUser·p1.00:   57.082 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15578
  mean =      2.051 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15366 
    [ 5.000, 10.000) = 123 
    [10.000, 15.000) = 46 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.246 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      5.742 ms/op
     p(99.9000) =     51.773 ms/op
     p(99.9900) =     55.510 ms/op
     p(99.9990) =     57.082 ms/op
     p(99.9999) =     57.082 ms/op
    p(100.0000) =     57.082 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ±(99.9%) 0.134 ms/op
Iteration   1: 3.675 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   5.382 ms/op
                 listUser·p0.999:  6.468 ms/op
                 listUser·p0.9999: 6.840 ms/op
                 listUser·p1.00:   6.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8699
  mean =      3.675 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 57 
    [2.000, 2.500) = 378 
    [2.500, 3.000) = 631 
    [3.000, 3.500) = 2058 
    [3.500, 4.000) = 3098 
    [4.000, 4.500) = 1823 
    [4.500, 5.000) = 469 
    [5.000, 5.500) = 106 
    [5.500, 6.000) = 33 
    [6.000, 6.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =      6.468 ms/op
     p(99.9900) =      6.840 ms/op
     p(99.9990) =      6.840 ms/op
     p(99.9999) =      6.840 ms/op
    p(100.0000) =      6.840 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.252          ops/ms
ClientSimple.existUser                       thrpt         13.421          ops/ms
ClientSimple.getUser                         thrpt         13.635          ops/ms
ClientSimple.listUser                        thrpt          8.419          ops/ms
ClientSimple.createUser                       avgt          2.068           ms/op
ClientSimple.existUser                        avgt          1.867           ms/op
ClientSimple.getUser                          avgt          1.879           ms/op
ClientSimple.listUser                         avgt          3.186           ms/op
ClientSimple.createUser                     sample  15703   2.036 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.860           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.884           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.466           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.300           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.161           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.602           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.695           ms/op
ClientSimple.existUser                      sample  16062   2.008 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.409           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.935           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.504           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.796           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.382           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.057           ms/op
ClientSimple.getUser                        sample  15578   2.051 ± 0.059   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.246           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.806           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.474           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.742           ms/op
ClientSimple.getUser:getUser·p0.999         sample         51.773           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         55.510           ms/op
ClientSimple.getUser:getUser·p1.00          sample         57.082           ms/op
ClientSimple.listUser                       sample   8699   3.675 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.128           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.666           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.382           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.468           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.840           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.840           ms/op

Benchmark result is saved to 1712167486683.json
