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
# Warmup Iteration   1: 1.752 ops/ms
Iteration   1: 7.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.484 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.820 ops/ms
Iteration   1: 13.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.579 ops/ms


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
# Warmup Iteration   1: 6.186 ops/ms
Iteration   1: 14.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.867 ops/ms


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
# Warmup Iteration   1: 5.065 ops/ms
Iteration   1: 7.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.721 ops/ms


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
# Warmup Iteration   1: 4.303 ±(99.9%) 0.068 ms/op
Iteration   1: 2.471 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.471 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.066 ±(99.9%) 0.086 ms/op
Iteration   1: 2.002 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.002 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ±(99.9%) 0.059 ms/op
Iteration   1: 1.823 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.823 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.367 ±(99.9%) 0.131 ms/op
Iteration   1: 3.788 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.788 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.396 ±(99.9%) 0.085 ms/op
Iteration   1: 2.140 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.034 ms/op
                 createUser·p0.90:   2.474 ms/op
                 createUser·p0.95:   2.699 ms/op
                 createUser·p0.99:   5.346 ms/op
                 createUser·p0.999:  16.910 ms/op
                 createUser·p0.9999: 18.451 ms/op
                 createUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14946
  mean =      2.140 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 13570 
    [ 2.500,  3.750) = 1021 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 102 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      5.346 ms/op
     p(99.9000) =     16.910 ms/op
     p(99.9900) =     18.451 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.074 ms/op
Iteration   1: 1.921 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   1.827 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.510 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  14.270 ms/op
                 existUser·p0.9999: 15.745 ms/op
                 existUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16645
  mean =      1.921 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 632 
    [ 1.250,  2.500) = 15165 
    [ 2.500,  3.750) = 595 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.510 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     15.745 ms/op
     p(99.9990) =     15.811 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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
# Warmup Iteration   1: 3.244 ±(99.9%) 0.126 ms/op
Iteration   1: 1.972 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.694 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.433 ms/op
                 getUser·p0.95:   2.650 ms/op
                 getUser·p0.99:   3.647 ms/op
                 getUser·p0.999:  11.658 ms/op
                 getUser·p0.9999: 12.403 ms/op
                 getUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16216
  mean =      1.972 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 460 
    [ 1.250,  2.500) = 14457 
    [ 2.500,  3.750) = 1140 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.647 ms/op
     p(99.9000) =     11.658 ms/op
     p(99.9900) =     12.403 ms/op
     p(99.9990) =     13.156 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.159 ms/op
Iteration   1: 3.516 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   3.391 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.054 ms/op
                 listUser·p0.999:  8.190 ms/op
                 listUser·p0.9999: 8.389 ms/op
                 listUser·p1.00:   8.389 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9099
  mean =      3.516 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 7 
    [1.500, 2.000) = 36 
    [2.000, 2.500) = 304 
    [2.500, 3.000) = 2786 
    [3.000, 3.500) = 1815 
    [3.500, 4.000) = 1690 
    [4.000, 4.500) = 1436 
    [4.500, 5.000) = 710 
    [5.000, 5.500) = 153 
    [5.500, 6.000) = 62 
    [6.000, 6.500) = 34 
    [6.500, 7.000) = 28 
    [7.000, 7.500) = 20 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =      8.190 ms/op
     p(99.9900) =      8.389 ms/op
     p(99.9990) =      8.389 ms/op
     p(99.9999) =      8.389 ms/op
    p(100.0000) =      8.389 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.484          ops/ms
ClientSimple.existUser                       thrpt         13.579          ops/ms
ClientSimple.getUser                         thrpt         14.867          ops/ms
ClientSimple.listUser                        thrpt          7.721          ops/ms
ClientSimple.createUser                       avgt          2.471           ms/op
ClientSimple.existUser                        avgt          2.002           ms/op
ClientSimple.getUser                          avgt          1.823           ms/op
ClientSimple.listUser                         avgt          3.788           ms/op
ClientSimple.createUser                     sample  14946   2.140 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.784           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.034           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.474           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.346           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.910           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.451           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.678           ms/op
ClientSimple.existUser                      sample  16645   1.921 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.639           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.827           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.510           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.276           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.270           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.745           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.811           ms/op
ClientSimple.getUser                        sample  16216   1.972 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.694           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.647           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.658           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.403           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.156           ms/op
ClientSimple.listUser                       sample   9099   3.516 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.896           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.391           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.054           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.190           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.389           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.389           ms/op

Benchmark result is saved to 1711173989687.json
