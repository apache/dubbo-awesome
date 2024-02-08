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
# Warmup Iteration   1: 2.159 ops/ms
Iteration   1: 5.880 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.880 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.654 ops/ms
Iteration   1: 12.006 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.006 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.670 ops/ms
Iteration   1: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.288 ops/ms


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
# Warmup Iteration   1: 2.074 ops/ms
Iteration   1: 3.459 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.459 ops/ms


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
# Warmup Iteration   1: 5.251 ±(99.9%) 0.095 ms/op
Iteration   1: 3.001 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.001 ms/op


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
# Warmup Iteration   1: 3.175 ±(99.9%) 0.033 ms/op
Iteration   1: 1.910 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.910 ms/op


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
# Warmup Iteration   1: 5.120 ±(99.9%) 0.072 ms/op
Iteration   1: 3.106 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.532 ±(99.9%) 0.213 ms/op
Iteration   1: 9.058 ±(99.9%) 0.097 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.058 ms/op


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
# Warmup Iteration   1: 4.992 ±(99.9%) 0.117 ms/op
Iteration   1: 3.096 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.066 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  14.920 ms/op
                 createUser·p0.9999: 16.276 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10327
  mean =      3.096 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1691 
    [ 2.500,  3.750) = 7679 
    [ 3.750,  5.000) = 763 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.012 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.066 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     14.920 ms/op
     p(99.9900) =     16.276 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 3.021 ±(99.9%) 0.067 ms/op
Iteration   1: 1.714 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   1.636 ms/op
                 existUser·p0.90:   2.056 ms/op
                 existUser·p0.95:   2.216 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.012 ms/op
                 existUser·p0.9999: 10.422 ms/op
                 existUser·p1.00:   10.437 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18655
  mean =      1.714 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 83 
    [ 1.000,  2.000) = 16196 
    [ 2.000,  3.000) = 2051 
    [ 3.000,  4.000) = 77 
    [ 4.000,  5.000) = 110 
    [ 5.000,  6.000) = 70 
    [ 6.000,  7.000) = 41 
    [ 7.000,  8.000) = 25 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      1.636 ms/op
     p(90.0000) =      2.056 ms/op
     p(95.0000) =      2.216 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.012 ms/op
     p(99.9900) =     10.422 ms/op
     p(99.9990) =     10.437 ms/op
     p(99.9999) =     10.437 ms/op
    p(100.0000) =     10.437 ms/op


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.097 ms/op
Iteration   1: 2.900 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.356 ms/op
                 getUser·p0.50:   2.724 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   4.778 ms/op
                 getUser·p0.999:  7.684 ms/op
                 getUser·p0.9999: 8.916 ms/op
                 getUser·p1.00:   8.962 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10974
  mean =      2.900 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 22 
    [1.500, 2.000) = 189 
    [2.000, 2.500) = 3343 
    [2.500, 3.000) = 3550 
    [3.000, 3.500) = 1954 
    [3.500, 4.000) = 1135 
    [4.000, 4.500) = 590 
    [4.500, 5.000) = 122 
    [5.000, 5.500) = 34 
    [5.500, 6.000) = 10 
    [6.000, 6.500) = 8 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 6 
    [8.000, 8.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      2.724 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      4.778 ms/op
     p(99.9000) =      7.684 ms/op
     p(99.9900) =      8.916 ms/op
     p(99.9990) =      8.962 ms/op
     p(99.9999) =      8.962 ms/op
    p(100.0000) =      8.962 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.794 ±(99.9%) 0.591 ms/op
Iteration   1: 8.471 ±(99.9%) 0.104 ms/op
                 listUser·p0.00:   3.363 ms/op
                 listUser·p0.50:   8.233 ms/op
                 listUser·p0.90:   11.010 ms/op
                 listUser·p0.95:   12.027 ms/op
                 listUser·p0.99:   14.254 ms/op
                 listUser·p0.999:  19.111 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3777
  mean =      8.471 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 55 
    [ 5.000,  7.500) = 1179 
    [ 7.500, 10.000) = 1858 
    [10.000, 12.500) = 551 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.363 ms/op
     p(50.0000) =      8.233 ms/op
     p(90.0000) =     11.010 ms/op
     p(95.0000) =     12.027 ms/op
     p(99.0000) =     14.254 ms/op
     p(99.9000) =     19.111 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.880          ops/ms
Client.existUser                       thrpt         12.006          ops/ms
Client.getUser                         thrpt          8.288          ops/ms
Client.listUser                        thrpt          3.459          ops/ms
Client.createUser                       avgt          3.001           ms/op
Client.existUser                        avgt          1.910           ms/op
Client.getUser                          avgt          3.106           ms/op
Client.listUser                         avgt          9.058           ms/op
Client.createUser                     sample  10327   3.096 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          1.012           ms/op
Client.createUser:createUser·p0.50    sample          2.970           ms/op
Client.createUser:createUser·p0.90    sample          3.707           ms/op
Client.createUser:createUser·p0.95    sample          4.066           ms/op
Client.createUser:createUser·p0.99    sample          6.545           ms/op
Client.createUser:createUser·p0.999   sample         14.920           ms/op
Client.createUser:createUser·p0.9999  sample         16.276           ms/op
Client.createUser:createUser·p1.00    sample         16.302           ms/op
Client.existUser                      sample  18655   1.714 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.554           ms/op
Client.existUser:existUser·p0.50      sample          1.636           ms/op
Client.existUser:existUser·p0.90      sample          2.056           ms/op
Client.existUser:existUser·p0.95      sample          2.216           ms/op
Client.existUser:existUser·p0.99      sample          4.325           ms/op
Client.existUser:existUser·p0.999     sample          7.012           ms/op
Client.existUser:existUser·p0.9999    sample         10.422           ms/op
Client.existUser:existUser·p1.00      sample         10.437           ms/op
Client.getUser                        sample  10974   2.900 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.356           ms/op
Client.getUser:getUser·p0.50          sample          2.724           ms/op
Client.getUser:getUser·p0.90          sample          3.863           ms/op
Client.getUser:getUser·p0.95          sample          4.125           ms/op
Client.getUser:getUser·p0.99          sample          4.778           ms/op
Client.getUser:getUser·p0.999         sample          7.684           ms/op
Client.getUser:getUser·p0.9999        sample          8.916           ms/op
Client.getUser:getUser·p1.00          sample          8.962           ms/op
Client.listUser                       sample   3777   8.471 ± 0.104   ms/op
Client.listUser:listUser·p0.00        sample          3.363           ms/op
Client.listUser:listUser·p0.50        sample          8.233           ms/op
Client.listUser:listUser·p0.90        sample         11.010           ms/op
Client.listUser:listUser·p0.95        sample         12.027           ms/op
Client.listUser:listUser·p0.99        sample         14.254           ms/op
Client.listUser:listUser·p0.999       sample         19.111           ms/op
Client.listUser:listUser·p0.9999      sample         23.200           ms/op
Client.listUser:listUser·p1.00        sample         23.200           ms/op
