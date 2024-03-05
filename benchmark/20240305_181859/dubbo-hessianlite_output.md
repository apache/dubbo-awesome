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
# Warmup Iteration   1: 2.761 ops/ms
Iteration   1: 6.365 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.365 ops/ms


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
# Warmup Iteration   1: 5.754 ops/ms
Iteration   1: 12.316 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.316 ops/ms


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
# Warmup Iteration   1: 3.810 ops/ms
Iteration   1: 9.494 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.494 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.194 ops/ms
Iteration   1: 3.735 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.735 ops/ms


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
# Warmup Iteration   1: 5.388 ±(99.9%) 0.076 ms/op
Iteration   1: 2.836 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.836 ms/op


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
# Warmup Iteration   1: 2.875 ±(99.9%) 0.027 ms/op
Iteration   1: 2.216 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.216 ms/op


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.048 ms/op
Iteration   1: 3.087 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.087 ms/op


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
# Warmup Iteration   1: 13.062 ±(99.9%) 0.255 ms/op
Iteration   1: 8.881 ±(99.9%) 0.107 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.881 ms/op


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
# Warmup Iteration   1: 5.752 ±(99.9%) 0.298 ms/op
Iteration   1: 3.123 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   7.139 ms/op
                 createUser·p0.999:  15.348 ms/op
                 createUser·p0.9999: 16.299 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10226
  mean =      3.123 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1879 
    [ 2.500,  3.750) = 7422 
    [ 3.750,  5.000) = 570 
    [ 5.000,  6.250) = 197 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      7.139 ms/op
     p(99.9000) =     15.348 ms/op
     p(99.9900) =     16.299 ms/op
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
# Warmup Iteration   1: 2.840 ±(99.9%) 0.070 ms/op
Iteration   1: 1.740 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   1.583 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  4.546 ms/op
                 existUser·p0.9999: 5.808 ms/op
                 existUser·p1.00:   5.857 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18676
  mean =      1.740 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 77 
    [1.000, 1.500) = 7019 
    [1.500, 2.000) = 7510 
    [2.000, 2.500) = 2935 
    [2.500, 3.000) = 739 
    [3.000, 3.500) = 207 
    [3.500, 4.000) = 130 
    [4.000, 4.500) = 38 
    [4.500, 5.000) = 15 
    [5.000, 5.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      1.583 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =      4.546 ms/op
     p(99.9900) =      5.808 ms/op
     p(99.9990) =      5.857 ms/op
     p(99.9999) =      5.857 ms/op
    p(100.0000) =      5.857 ms/op


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.092 ms/op
Iteration   1: 3.056 ±(99.9%) 0.052 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.900 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  29.116 ms/op
                 getUser·p0.9999: 29.877 ms/op
                 getUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10447
  mean =      3.056 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2120 
    [ 2.500,  5.000) = 8129 
    [ 5.000,  7.500) = 125 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     29.116 ms/op
     p(99.9900) =     29.877 ms/op
     p(99.9990) =     29.884 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 11.152 ±(99.9%) 0.312 ms/op
Iteration   1: 8.143 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   7.733 ms/op
                 listUser·p0.90:   10.682 ms/op
                 listUser·p0.95:   11.626 ms/op
                 listUser·p0.99:   19.296 ms/op
                 listUser·p0.999:  21.886 ms/op
                 listUser·p0.9999: 22.970 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4027
  mean =      8.143 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 131 
    [ 5.000,  7.500) = 1637 
    [ 7.500, 10.000) = 1591 
    [10.000, 12.500) = 545 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.466 ms/op
     p(50.0000) =      7.733 ms/op
     p(90.0000) =     10.682 ms/op
     p(95.0000) =     11.626 ms/op
     p(99.0000) =     19.296 ms/op
     p(99.9000) =     21.886 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.365          ops/ms
Client.existUser                       thrpt         12.316          ops/ms
Client.getUser                         thrpt          9.494          ops/ms
Client.listUser                        thrpt          3.735          ops/ms
Client.createUser                       avgt          2.836           ms/op
Client.existUser                        avgt          2.216           ms/op
Client.getUser                          avgt          3.087           ms/op
Client.listUser                         avgt          8.881           ms/op
Client.createUser                     sample  10226   3.123 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.124           ms/op
Client.createUser:createUser·p0.50    sample          2.994           ms/op
Client.createUser:createUser·p0.90    sample          3.711           ms/op
Client.createUser:createUser·p0.95    sample          4.055           ms/op
Client.createUser:createUser·p0.99    sample          7.139           ms/op
Client.createUser:createUser·p0.999   sample         15.348           ms/op
Client.createUser:createUser·p0.9999  sample         16.299           ms/op
Client.createUser:createUser·p1.00    sample         16.302           ms/op
Client.existUser                      sample  18676   1.740 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.662           ms/op
Client.existUser:existUser·p0.50      sample          1.583           ms/op
Client.existUser:existUser·p0.90      sample          2.306           ms/op
Client.existUser:existUser·p0.95      sample          2.585           ms/op
Client.existUser:existUser·p0.99      sample          3.510           ms/op
Client.existUser:existUser·p0.999     sample          4.546           ms/op
Client.existUser:existUser·p0.9999    sample          5.808           ms/op
Client.existUser:existUser·p1.00      sample          5.857           ms/op
Client.getUser                        sample  10447   3.056 ± 0.052   ms/op
Client.getUser:getUser·p0.00          sample          0.708           ms/op
Client.getUser:getUser·p0.50          sample          2.900           ms/op
Client.getUser:getUser·p0.90          sample          3.641           ms/op
Client.getUser:getUser·p0.95          sample          4.104           ms/op
Client.getUser:getUser·p0.99          sample          7.062           ms/op
Client.getUser:getUser·p0.999         sample         29.116           ms/op
Client.getUser:getUser·p0.9999        sample         29.877           ms/op
Client.getUser:getUser·p1.00          sample         29.884           ms/op
Client.listUser                       sample   4027   8.143 ± 0.121   ms/op
Client.listUser:listUser·p0.00        sample          2.466           ms/op
Client.listUser:listUser·p0.50        sample          7.733           ms/op
Client.listUser:listUser·p0.90        sample         10.682           ms/op
Client.listUser:listUser·p0.95        sample         11.626           ms/op
Client.listUser:listUser·p0.99        sample         19.296           ms/op
Client.listUser:listUser·p0.999       sample         21.886           ms/op
Client.listUser:listUser·p0.9999      sample         22.970           ms/op
Client.listUser:listUser·p1.00        sample         22.970           ms/op
