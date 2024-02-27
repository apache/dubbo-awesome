# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.539 ops/ms
Iteration   1: 6.256 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.256 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.513 ops/ms
Iteration   1: 11.883 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.883 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.563 ops/ms
Iteration   1: 9.566 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.566 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.263 ops/ms
Iteration   1: 4.111 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.111 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.516 ±(99.9%) 0.070 ms/op
Iteration   1: 3.101 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.101 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.207 ±(99.9%) 0.029 ms/op
Iteration   1: 2.048 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.048 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.848 ±(99.9%) 0.076 ms/op
Iteration   1: 2.733 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.733 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.160 ±(99.9%) 0.174 ms/op
Iteration   1: 8.183 ±(99.9%) 0.122 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.183 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.117 ±(99.9%) 0.130 ms/op
Iteration   1: 3.116 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   2.888 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.761 ms/op
                 createUser·p0.999:  14.833 ms/op
                 createUser·p0.9999: 16.416 ms/op
                 createUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10263
  mean =      3.116 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1497 
    [ 2.500,  3.750) = 7381 
    [ 3.750,  5.000) = 1142 
    [ 5.000,  6.250) = 94 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.761 ms/op
     p(99.9000) =     14.833 ms/op
     p(99.9900) =     16.416 ms/op
     p(99.9990) =     16.417 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.000 ±(99.9%) 0.076 ms/op
Iteration   1: 1.844 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.441 ms/op
                 existUser·p0.99:   3.279 ms/op
                 existUser·p0.999:  4.637 ms/op
                 existUser·p0.9999: 6.377 ms/op
                 existUser·p1.00:   6.996 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17339
  mean =      1.844 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 119 
    [1.000, 1.500) = 2264 
    [1.500, 2.000) = 10179 
    [2.000, 2.500) = 4004 
    [2.500, 3.000) = 529 
    [3.000, 3.500) = 123 
    [3.500, 4.000) = 54 
    [4.000, 4.500) = 33 
    [4.500, 5.000) = 32 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      3.279 ms/op
     p(99.9000) =      4.637 ms/op
     p(99.9900) =      6.377 ms/op
     p(99.9990) =      6.996 ms/op
     p(99.9999) =      6.996 ms/op
    p(100.0000) =      6.996 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.463 ±(99.9%) 0.101 ms/op
Iteration   1: 2.898 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.753 ms/op
                 getUser·p0.90:   3.810 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  8.114 ms/op
                 getUser·p0.9999: 9.710 ms/op
                 getUser·p1.00:   9.765 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11158
  mean =      2.898 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 3 
    [ 1.000,  2.000) = 538 
    [ 2.000,  3.000) = 6450 
    [ 3.000,  4.000) = 3542 
    [ 4.000,  5.000) = 509 
    [ 5.000,  6.000) = 61 
    [ 6.000,  7.000) = 18 
    [ 7.000,  8.000) = 23 
    [ 8.000,  9.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      3.810 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =      8.114 ms/op
     p(99.9900) =      9.710 ms/op
     p(99.9990) =      9.765 ms/op
     p(99.9999) =      9.765 ms/op
    p(100.0000) =      9.765 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.126 ±(99.9%) 0.442 ms/op
Iteration   1: 7.780 ±(99.9%) 0.118 ms/op
                 listUser·p0.00:   2.953 ms/op
                 listUser·p0.50:   7.365 ms/op
                 listUser·p0.90:   10.107 ms/op
                 listUser·p0.95:   11.312 ms/op
                 listUser·p0.99:   18.504 ms/op
                 listUser·p0.999:  20.762 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4130
  mean =      7.780 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 152 
    [ 5.000,  7.500) = 2026 
    [ 7.500, 10.000) = 1522 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.953 ms/op
     p(50.0000) =      7.365 ms/op
     p(90.0000) =     10.107 ms/op
     p(95.0000) =     11.312 ms/op
     p(99.0000) =     18.504 ms/op
     p(99.9000) =     20.762 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.256          ops/ms
Client.existUser                       thrpt         11.883          ops/ms
Client.getUser                         thrpt          9.566          ops/ms
Client.listUser                        thrpt          4.111          ops/ms
Client.createUser                       avgt          3.101           ms/op
Client.existUser                        avgt          2.048           ms/op
Client.getUser                          avgt          2.733           ms/op
Client.listUser                         avgt          8.183           ms/op
Client.createUser                     sample  10263   3.116 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.151           ms/op
Client.createUser:createUser·p0.50    sample          2.888           ms/op
Client.createUser:createUser·p0.90    sample          3.973           ms/op
Client.createUser:createUser·p0.95    sample          4.456           ms/op
Client.createUser:createUser·p0.99    sample          6.761           ms/op
Client.createUser:createUser·p0.999   sample         14.833           ms/op
Client.createUser:createUser·p0.9999  sample         16.416           ms/op
Client.createUser:createUser·p1.00    sample         16.417           ms/op
Client.existUser                      sample  17339   1.844 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.524           ms/op
Client.existUser:existUser·p0.50      sample          1.796           ms/op
Client.existUser:existUser·p0.90      sample          2.261           ms/op
Client.existUser:existUser·p0.95      sample          2.441           ms/op
Client.existUser:existUser·p0.99      sample          3.279           ms/op
Client.existUser:existUser·p0.999     sample          4.637           ms/op
Client.existUser:existUser·p0.9999    sample          6.377           ms/op
Client.existUser:existUser·p1.00      sample          6.996           ms/op
Client.getUser                        sample  11158   2.898 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.888           ms/op
Client.getUser:getUser·p0.50          sample          2.753           ms/op
Client.getUser:getUser·p0.90          sample          3.810           ms/op
Client.getUser:getUser·p0.95          sample          4.035           ms/op
Client.getUser:getUser·p0.99          sample          5.079           ms/op
Client.getUser:getUser·p0.999         sample          8.114           ms/op
Client.getUser:getUser·p0.9999        sample          9.710           ms/op
Client.getUser:getUser·p1.00          sample          9.765           ms/op
Client.listUser                       sample   4130   7.780 ± 0.118   ms/op
Client.listUser:listUser·p0.00        sample          2.953           ms/op
Client.listUser:listUser·p0.50        sample          7.365           ms/op
Client.listUser:listUser·p0.90        sample         10.107           ms/op
Client.listUser:listUser·p0.95        sample         11.312           ms/op
Client.listUser:listUser·p0.99        sample         18.504           ms/op
Client.listUser:listUser·p0.999       sample         20.762           ms/op
Client.listUser:listUser·p0.9999      sample         21.889           ms/op
Client.listUser:listUser·p1.00        sample         21.889           ms/op
