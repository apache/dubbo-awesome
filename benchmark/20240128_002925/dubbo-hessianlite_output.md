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
# Warmup Iteration   1: 2.614 ops/ms
Iteration   1: 6.048 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.048 ops/ms


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
# Warmup Iteration   1: 6.326 ops/ms
Iteration   1: 12.565 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.565 ops/ms


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
# Warmup Iteration   1: 3.956 ops/ms
Iteration   1: 8.425 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.425 ops/ms


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
# Warmup Iteration   1: 2.211 ops/ms
Iteration   1: 3.860 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.860 ops/ms


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
# Warmup Iteration   1: 5.583 ±(99.9%) 0.083 ms/op
Iteration   1: 2.994 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.994 ms/op


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
# Warmup Iteration   1: 2.999 ±(99.9%) 0.031 ms/op
Iteration   1: 1.818 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.818 ms/op


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.046 ms/op
Iteration   1: 2.829 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.829 ms/op


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
# Warmup Iteration   1: 12.178 ±(99.9%) 0.207 ms/op
Iteration   1: 8.522 ±(99.9%) 0.102 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.522 ms/op


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
# Warmup Iteration   1: 4.861 ±(99.9%) 0.098 ms/op
Iteration   1: 2.898 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   2.707 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.740 ms/op
                 createUser·p0.999:  15.696 ms/op
                 createUser·p0.9999: 16.784 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11023
  mean =      2.898 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 3070 
    [ 2.500,  3.750) = 7021 
    [ 3.750,  5.000) = 767 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      2.707 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.740 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     16.784 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.079 ±(99.9%) 0.085 ms/op
Iteration   1: 1.726 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.458 ms/op
                 existUser·p0.50:   1.587 ms/op
                 existUser·p0.90:   2.159 ms/op
                 existUser·p0.95:   2.376 ms/op
                 existUser·p0.99:   3.188 ms/op
                 existUser·p0.999:  23.855 ms/op
                 existUser·p0.9999: 24.117 ms/op
                 existUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18529
  mean =      1.726 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17885 
    [ 2.500,  5.000) = 567 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      1.587 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      3.188 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 4.516 ±(99.9%) 0.141 ms/op
Iteration   1: 3.257 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.498 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   4.049 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.339 ms/op
                 getUser·p0.999:  7.531 ms/op
                 getUser·p0.9999: 7.700 ms/op
                 getUser·p1.00:   7.700 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9813
  mean =      3.257 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 13 
    [1.000, 1.500) = 37 
    [1.500, 2.000) = 189 
    [2.000, 2.500) = 978 
    [2.500, 3.000) = 2396 
    [3.000, 3.500) = 3048 
    [3.500, 4.000) = 2041 
    [4.000, 4.500) = 734 
    [4.500, 5.000) = 131 
    [5.000, 5.500) = 83 
    [5.500, 6.000) = 52 
    [6.000, 6.500) = 30 
    [6.500, 7.000) = 37 
    [7.000, 7.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      4.049 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.339 ms/op
     p(99.9000) =      7.531 ms/op
     p(99.9900) =      7.700 ms/op
     p(99.9990) =      7.700 ms/op
     p(99.9999) =      7.700 ms/op
    p(100.0000) =      7.700 ms/op


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
# Warmup Iteration   1: 13.155 ±(99.9%) 0.459 ms/op
Iteration   1: 8.320 ±(99.9%) 0.118 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   7.987 ms/op
                 listUser·p0.90:   11.321 ms/op
                 listUser·p0.95:   12.354 ms/op
                 listUser·p0.99:   15.472 ms/op
                 listUser·p0.999:  17.905 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3865
  mean =      8.320 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 158 
    [ 5.000,  7.500) = 1409 
    [ 7.500, 10.000) = 1565 
    [10.000, 12.500) = 560 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      7.987 ms/op
     p(90.0000) =     11.321 ms/op
     p(95.0000) =     12.354 ms/op
     p(99.0000) =     15.472 ms/op
     p(99.9000) =     17.905 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.048          ops/ms
Client.existUser                       thrpt         12.565          ops/ms
Client.getUser                         thrpt          8.425          ops/ms
Client.listUser                        thrpt          3.860          ops/ms
Client.createUser                       avgt          2.994           ms/op
Client.existUser                        avgt          1.818           ms/op
Client.getUser                          avgt          2.829           ms/op
Client.listUser                         avgt          8.522           ms/op
Client.createUser                     sample  11023   2.898 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.186           ms/op
Client.createUser:createUser·p0.50    sample          2.707           ms/op
Client.createUser:createUser·p0.90    sample          3.633           ms/op
Client.createUser:createUser·p0.95    sample          4.194           ms/op
Client.createUser:createUser·p0.99    sample          5.740           ms/op
Client.createUser:createUser·p0.999   sample         15.696           ms/op
Client.createUser:createUser·p0.9999  sample         16.784           ms/op
Client.createUser:createUser·p1.00    sample         16.843           ms/op
Client.existUser                      sample  18529   1.726 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.458           ms/op
Client.existUser:existUser·p0.50      sample          1.587           ms/op
Client.existUser:existUser·p0.90      sample          2.159           ms/op
Client.existUser:existUser·p0.95      sample          2.376           ms/op
Client.existUser:existUser·p0.99      sample          3.188           ms/op
Client.existUser:existUser·p0.999     sample         23.855           ms/op
Client.existUser:existUser·p0.9999    sample         24.117           ms/op
Client.existUser:existUser·p1.00      sample         24.117           ms/op
Client.getUser                        sample   9813   3.257 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.498           ms/op
Client.getUser:getUser·p0.50          sample          3.224           ms/op
Client.getUser:getUser·p0.90          sample          4.049           ms/op
Client.getUser:getUser·p0.95          sample          4.342           ms/op
Client.getUser:getUser·p0.99          sample          6.339           ms/op
Client.getUser:getUser·p0.999         sample          7.531           ms/op
Client.getUser:getUser·p0.9999        sample          7.700           ms/op
Client.getUser:getUser·p1.00          sample          7.700           ms/op
Client.listUser                       sample   3865   8.320 ± 0.118   ms/op
Client.listUser:listUser·p0.00        sample          1.669           ms/op
Client.listUser:listUser·p0.50        sample          7.987           ms/op
Client.listUser:listUser·p0.90        sample         11.321           ms/op
Client.listUser:listUser·p0.95        sample         12.354           ms/op
Client.listUser:listUser·p0.99        sample         15.472           ms/op
Client.listUser:listUser·p0.999       sample         17.905           ms/op
Client.listUser:listUser·p0.9999      sample         21.004           ms/op
Client.listUser:listUser·p1.00        sample         21.004           ms/op
