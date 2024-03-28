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
# Warmup Iteration   1: 2.099 ops/ms
Iteration   1: 7.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.156 ops/ms


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
# Warmup Iteration   1: 6.025 ops/ms
Iteration   1: 12.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.065 ops/ms


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
# Warmup Iteration   1: 4.895 ops/ms
Iteration   1: 11.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.993 ops/ms


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
# Warmup Iteration   1: 4.730 ops/ms
Iteration   1: 9.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.336 ops/ms


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.077 ms/op
Iteration   1: 2.153 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.153 ms/op


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
# Warmup Iteration   1: 3.352 ±(99.9%) 0.064 ms/op
Iteration   1: 2.106 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.106 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.055 ms/op
Iteration   1: 1.859 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.859 ms/op


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
# Warmup Iteration   1: 4.262 ±(99.9%) 0.085 ms/op
Iteration   1: 3.178 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.178 ms/op


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
# Warmup Iteration   1: 3.381 ±(99.9%) 0.087 ms/op
Iteration   1: 2.167 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.508 ms/op
                 createUser·p0.50:   1.958 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.797 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  31.137 ms/op
                 createUser·p0.9999: 35.914 ms/op
                 createUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14760
  mean =      2.167 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12382 
    [ 2.500,  5.000) = 2175 
    [ 5.000,  7.500) = 74 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.797 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     31.137 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 2.973 ±(99.9%) 0.083 ms/op
Iteration   1: 2.116 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   2.052 ms/op
                 existUser·p0.90:   2.765 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  12.468 ms/op
                 existUser·p0.9999: 12.616 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15108
  mean =      2.116 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 747 
    [ 1.250,  2.500) = 10724 
    [ 2.500,  3.750) = 3513 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      2.052 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      3.506 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     12.616 ms/op
     p(99.9990) =     12.616 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


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
# Warmup Iteration   1: 3.364 ±(99.9%) 0.085 ms/op
Iteration   1: 2.033 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.522 ms/op
                 getUser·p0.50:   1.952 ms/op
                 getUser·p0.90:   2.650 ms/op
                 getUser·p0.95:   2.839 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  15.570 ms/op
                 getUser·p0.9999: 17.704 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15707
  mean =      2.033 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 497 
    [ 1.250,  2.500) = 12760 
    [ 2.500,  3.750) = 2281 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =     15.570 ms/op
     p(99.9900) =     17.704 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 4.772 ±(99.9%) 0.189 ms/op
Iteration   1: 3.224 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.397 ms/op
                 listUser·p0.999:  8.348 ms/op
                 listUser·p0.9999: 8.536 ms/op
                 listUser·p1.00:   8.536 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9908
  mean =      3.224 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 18 
    [1.500, 2.000) = 85 
    [2.000, 2.500) = 802 
    [2.500, 3.000) = 3759 
    [3.000, 3.500) = 2153 
    [3.500, 4.000) = 1824 
    [4.000, 4.500) = 807 
    [4.500, 5.000) = 228 
    [5.000, 5.500) = 57 
    [5.500, 6.000) = 39 
    [6.000, 6.500) = 49 
    [6.500, 7.000) = 52 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.397 ms/op
     p(99.9000) =      8.348 ms/op
     p(99.9900) =      8.536 ms/op
     p(99.9990) =      8.536 ms/op
     p(99.9999) =      8.536 ms/op
    p(100.0000) =      8.536 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.156          ops/ms
ClientSimple.existUser                       thrpt         12.065          ops/ms
ClientSimple.getUser                         thrpt         11.993          ops/ms
ClientSimple.listUser                        thrpt          9.336          ops/ms
ClientSimple.createUser                       avgt          2.153           ms/op
ClientSimple.existUser                        avgt          2.106           ms/op
ClientSimple.getUser                          avgt          1.859           ms/op
ClientSimple.listUser                         avgt          3.178           ms/op
ClientSimple.createUser                     sample  14760   2.167 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.508           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.958           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.797           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.095           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.137           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.914           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.914           ms/op
ClientSimple.existUser                      sample  15108   2.116 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.543           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.052           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.765           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.978           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.506           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.468           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.616           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.616           ms/op
ClientSimple.getUser                        sample  15707   2.033 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.522           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.952           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.211           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.570           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.704           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.760           ms/op
ClientSimple.listUser                       sample   9908   3.224 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.853           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.052           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.088           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.397           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.348           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.536           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.536           ms/op

Benchmark result is saved to 1711649089845.json
