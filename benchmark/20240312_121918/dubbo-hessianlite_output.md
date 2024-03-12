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
# Warmup Iteration   1: 2.409 ops/ms
Iteration   1: 6.331 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.331 ops/ms


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
# Warmup Iteration   1: 5.231 ops/ms
Iteration   1: 12.159 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.159 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.689 ops/ms
Iteration   1: 8.471 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.471 ops/ms


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
# Warmup Iteration   1: 2.265 ops/ms
Iteration   1: 3.671 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.671 ops/ms


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
# Warmup Iteration   1: 5.311 ±(99.9%) 0.070 ms/op
Iteration   1: 3.106 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.106 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.031 ms/op
Iteration   1: 1.973 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.973 ms/op


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
# Warmup Iteration   1: 5.307 ±(99.9%) 0.058 ms/op
Iteration   1: 3.208 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.208 ms/op


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
# Warmup Iteration   1: 12.573 ±(99.9%) 0.184 ms/op
Iteration   1: 8.928 ±(99.9%) 0.102 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.928 ms/op


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
# Warmup Iteration   1: 4.936 ±(99.9%) 0.111 ms/op
Iteration   1: 3.278 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   4.033 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  10.863 ms/op
                 createUser·p0.9999: 11.059 ms/op
                 createUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9884
  mean =      3.278 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 201 
    [ 2.000,  3.000) = 3660 
    [ 3.000,  4.000) = 4985 
    [ 4.000,  5.000) = 696 
    [ 5.000,  6.000) = 126 
    [ 6.000,  7.000) = 62 
    [ 7.000,  8.000) = 37 
    [ 8.000,  9.000) = 18 
    [ 9.000, 10.000) = 36 
    [10.000, 11.000) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      4.033 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     10.863 ms/op
     p(99.9900) =     11.059 ms/op
     p(99.9990) =     11.059 ms/op
     p(99.9999) =     11.059 ms/op
    p(100.0000) =     11.059 ms/op


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
# Warmup Iteration   1: 3.423 ±(99.9%) 0.087 ms/op
Iteration   1: 2.081 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.512 ms/op
                 existUser·p0.50:   1.858 ms/op
                 existUser·p0.90:   2.867 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   5.393 ms/op
                 existUser·p0.999:  24.269 ms/op
                 existUser·p0.9999: 24.785 ms/op
                 existUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15364
  mean =      2.081 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12863 
    [ 2.500,  5.000) = 2309 
    [ 5.000,  7.500) = 136 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.512 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.330 ms/op
     p(99.0000) =      5.393 ms/op
     p(99.9000) =     24.269 ms/op
     p(99.9900) =     24.785 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.101 ms/op
Iteration   1: 2.745 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   2.630 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  6.980 ms/op
                 getUser·p0.9999: 7.678 ms/op
                 getUser·p1.00:   7.807 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11676
  mean =      2.745 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 14 
    [1.000, 1.500) = 423 
    [1.500, 2.000) = 1214 
    [2.000, 2.500) = 3099 
    [2.500, 3.000) = 3136 
    [3.000, 3.500) = 2019 
    [3.500, 4.000) = 1209 
    [4.000, 4.500) = 340 
    [4.500, 5.000) = 77 
    [5.000, 5.500) = 55 
    [5.500, 6.000) = 58 
    [6.000, 6.500) = 10 
    [6.500, 7.000) = 14 
    [7.000, 7.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =      6.980 ms/op
     p(99.9900) =      7.678 ms/op
     p(99.9990) =      7.807 ms/op
     p(99.9999) =      7.807 ms/op
    p(100.0000) =      7.807 ms/op


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
# Warmup Iteration   1: 11.938 ±(99.9%) 0.363 ms/op
Iteration   1: 7.872 ±(99.9%) 0.111 ms/op
                 listUser·p0.00:   1.706 ms/op
                 listUser·p0.50:   7.594 ms/op
                 listUser·p0.90:   10.060 ms/op
                 listUser·p0.95:   11.125 ms/op
                 listUser·p0.99:   15.650 ms/op
                 listUser·p0.999:  23.471 ms/op
                 listUser·p0.9999: 36.372 ms/op
                 listUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4107
  mean =      7.872 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 146 
    [ 5.000,  7.500) = 1776 
    [ 7.500, 10.000) = 1756 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      7.594 ms/op
     p(90.0000) =     10.060 ms/op
     p(95.0000) =     11.125 ms/op
     p(99.0000) =     15.650 ms/op
     p(99.9000) =     23.471 ms/op
     p(99.9900) =     36.372 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.331          ops/ms
Client.existUser                       thrpt         12.159          ops/ms
Client.getUser                         thrpt          8.471          ops/ms
Client.listUser                        thrpt          3.671          ops/ms
Client.createUser                       avgt          3.106           ms/op
Client.existUser                        avgt          1.973           ms/op
Client.getUser                          avgt          3.208           ms/op
Client.listUser                         avgt          8.928           ms/op
Client.createUser                     sample   9884   3.278 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.200           ms/op
Client.createUser:createUser·p0.50    sample          3.142           ms/op
Client.createUser:createUser·p0.90    sample          4.033           ms/op
Client.createUser:createUser·p0.95    sample          4.456           ms/op
Client.createUser:createUser·p0.99    sample          9.306           ms/op
Client.createUser:createUser·p0.999   sample         10.863           ms/op
Client.createUser:createUser·p0.9999  sample         11.059           ms/op
Client.createUser:createUser·p1.00    sample         11.059           ms/op
Client.existUser                      sample  15364   2.081 ± 0.034   ms/op
Client.existUser:existUser·p0.00      sample          0.512           ms/op
Client.existUser:existUser·p0.50      sample          1.858           ms/op
Client.existUser:existUser·p0.90      sample          2.867           ms/op
Client.existUser:existUser·p0.95      sample          3.330           ms/op
Client.existUser:existUser·p0.99      sample          5.393           ms/op
Client.existUser:existUser·p0.999     sample         24.269           ms/op
Client.existUser:existUser·p0.9999    sample         24.785           ms/op
Client.existUser:existUser·p1.00      sample         24.838           ms/op
Client.getUser                        sample  11676   2.745 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.579           ms/op
Client.getUser:getUser·p0.50          sample          2.630           ms/op
Client.getUser:getUser·p0.90          sample          3.727           ms/op
Client.getUser:getUser·p0.95          sample          3.985           ms/op
Client.getUser:getUser·p0.99          sample          5.267           ms/op
Client.getUser:getUser·p0.999         sample          6.980           ms/op
Client.getUser:getUser·p0.9999        sample          7.678           ms/op
Client.getUser:getUser·p1.00          sample          7.807           ms/op
Client.listUser                       sample   4107   7.872 ± 0.111   ms/op
Client.listUser:listUser·p0.00        sample          1.706           ms/op
Client.listUser:listUser·p0.50        sample          7.594           ms/op
Client.listUser:listUser·p0.90        sample         10.060           ms/op
Client.listUser:listUser·p0.95        sample         11.125           ms/op
Client.listUser:listUser·p0.99        sample         15.650           ms/op
Client.listUser:listUser·p0.999       sample         23.471           ms/op
Client.listUser:listUser·p0.9999      sample         36.372           ms/op
Client.listUser:listUser·p1.00        sample         36.372           ms/op
