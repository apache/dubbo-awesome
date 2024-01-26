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
# Warmup Iteration   1: 2.364 ops/ms
Iteration   1: 5.685 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.685 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.005 ops/ms
Iteration   1: 14.405 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.405 ops/ms


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
# Warmup Iteration   1: 4.281 ops/ms
Iteration   1: 9.121 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.121 ops/ms


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
# Warmup Iteration   1: 1.976 ops/ms
Iteration   1: 3.464 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.464 ops/ms


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
# Warmup Iteration   1: 5.674 ±(99.9%) 0.059 ms/op
Iteration   1: 3.267 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.267 ms/op


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
# Warmup Iteration   1: 3.163 ±(99.9%) 0.041 ms/op
Iteration   1: 1.930 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.930 ms/op


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
# Warmup Iteration   1: 5.262 ±(99.9%) 0.072 ms/op
Iteration   1: 3.273 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.273 ms/op


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
# Warmup Iteration   1: 14.230 ±(99.9%) 0.341 ms/op
Iteration   1: 9.025 ±(99.9%) 0.100 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.025 ms/op


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
# Warmup Iteration   1: 4.435 ±(99.9%) 0.108 ms/op
Iteration   1: 3.334 ±(99.9%) 0.065 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   15.422 ms/op
                 createUser·p0.999:  19.595 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9593
  mean =      3.334 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1483 
    [ 2.500,  5.000) = 7608 
    [ 5.000,  7.500) = 235 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =     15.422 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 2.926 ±(99.9%) 0.062 ms/op
Iteration   1: 1.837 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.566 ms/op
                 existUser·p0.50:   1.688 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   3.378 ms/op
                 existUser·p0.999:  14.460 ms/op
                 existUser·p0.9999: 15.103 ms/op
                 existUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17411
  mean =      1.837 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 783 
    [ 1.250,  2.500) = 15193 
    [ 2.500,  3.750) = 1299 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      1.688 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.378 ms/op
     p(99.9000) =     14.460 ms/op
     p(99.9900) =     15.103 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 4.442 ±(99.9%) 0.104 ms/op
Iteration   1: 3.140 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.596 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.383 ms/op
                 getUser·p0.999:  7.281 ms/op
                 getUser·p0.9999: 8.811 ms/op
                 getUser·p1.00:   8.815 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10191
  mean =      3.140 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 6 
    [1.000, 1.500) = 57 
    [1.500, 2.000) = 255 
    [2.000, 2.500) = 1642 
    [2.500, 3.000) = 2316 
    [3.000, 3.500) = 3117 
    [3.500, 4.000) = 1941 
    [4.000, 4.500) = 508 
    [4.500, 5.000) = 167 
    [5.000, 5.500) = 95 
    [5.500, 6.000) = 23 
    [6.000, 6.500) = 26 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 23 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.383 ms/op
     p(99.9000) =      7.281 ms/op
     p(99.9900) =      8.811 ms/op
     p(99.9990) =      8.815 ms/op
     p(99.9999) =      8.815 ms/op
    p(100.0000) =      8.815 ms/op


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
# Warmup Iteration   1: 11.814 ±(99.9%) 0.381 ms/op
Iteration   1: 9.839 ±(99.9%) 0.168 ms/op
                 listUser·p0.00:   3.445 ms/op
                 listUser·p0.50:   9.290 ms/op
                 listUser·p0.90:   13.101 ms/op
                 listUser·p0.95:   14.693 ms/op
                 listUser·p0.99:   23.255 ms/op
                 listUser·p0.999:  26.673 ms/op
                 listUser·p0.9999: 28.082 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3263
  mean =      9.839 ±(99.9%) 0.168 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 26 
    [ 5.000,  7.500) = 487 
    [ 7.500, 10.000) = 1509 
    [10.000, 12.500) = 820 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      3.445 ms/op
     p(50.0000) =      9.290 ms/op
     p(90.0000) =     13.101 ms/op
     p(95.0000) =     14.693 ms/op
     p(99.0000) =     23.255 ms/op
     p(99.9000) =     26.673 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.685          ops/ms
Client.existUser                       thrpt         14.405          ops/ms
Client.getUser                         thrpt          9.121          ops/ms
Client.listUser                        thrpt          3.464          ops/ms
Client.createUser                       avgt          3.267           ms/op
Client.existUser                        avgt          1.930           ms/op
Client.getUser                          avgt          3.273           ms/op
Client.listUser                         avgt          9.025           ms/op
Client.createUser                     sample   9593   3.334 ± 0.065   ms/op
Client.createUser:createUser·p0.00    sample          0.954           ms/op
Client.createUser:createUser·p0.50    sample          2.920           ms/op
Client.createUser:createUser·p0.90    sample          4.088           ms/op
Client.createUser:createUser·p0.95    sample          5.161           ms/op
Client.createUser:createUser·p0.99    sample         15.422           ms/op
Client.createUser:createUser·p0.999   sample         19.595           ms/op
Client.createUser:createUser·p0.9999  sample         21.594           ms/op
Client.createUser:createUser·p1.00    sample         21.594           ms/op
Client.existUser                      sample  17411   1.837 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.566           ms/op
Client.existUser:existUser·p0.50      sample          1.688           ms/op
Client.existUser:existUser·p0.90      sample          2.437           ms/op
Client.existUser:existUser·p0.95      sample          2.675           ms/op
Client.existUser:existUser·p0.99      sample          3.378           ms/op
Client.existUser:existUser·p0.999     sample         14.460           ms/op
Client.existUser:existUser·p0.9999    sample         15.103           ms/op
Client.existUser:existUser·p1.00      sample         15.188           ms/op
Client.getUser                        sample  10191   3.140 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.596           ms/op
Client.getUser:getUser·p0.50          sample          3.109           ms/op
Client.getUser:getUser·p0.90          sample          3.936           ms/op
Client.getUser:getUser·p0.95          sample          4.284           ms/op
Client.getUser:getUser·p0.99          sample          5.383           ms/op
Client.getUser:getUser·p0.999         sample          7.281           ms/op
Client.getUser:getUser·p0.9999        sample          8.811           ms/op
Client.getUser:getUser·p1.00          sample          8.815           ms/op
Client.listUser                       sample   3263   9.839 ± 0.168   ms/op
Client.listUser:listUser·p0.00        sample          3.445           ms/op
Client.listUser:listUser·p0.50        sample          9.290           ms/op
Client.listUser:listUser·p0.90        sample         13.101           ms/op
Client.listUser:listUser·p0.95        sample         14.693           ms/op
Client.listUser:listUser·p0.99        sample         23.255           ms/op
Client.listUser:listUser·p0.999       sample         26.673           ms/op
Client.listUser:listUser·p0.9999      sample         28.082           ms/op
Client.listUser:listUser·p1.00        sample         28.082           ms/op
