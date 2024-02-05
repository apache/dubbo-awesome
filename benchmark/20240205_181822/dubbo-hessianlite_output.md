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
# Warmup Iteration   1: 2.156 ops/ms
Iteration   1: 6.180 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.180 ops/ms


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
# Warmup Iteration   1: 5.335 ops/ms
Iteration   1: 12.915 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.915 ops/ms


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
# Warmup Iteration   1: 4.203 ops/ms
Iteration   1: 8.104 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.104 ops/ms


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
# Warmup Iteration   1: 2.121 ops/ms
Iteration   1: 3.503 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.503 ops/ms


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
# Warmup Iteration   1: 5.325 ±(99.9%) 0.053 ms/op
Iteration   1: 3.252 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.252 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.025 ms/op
Iteration   1: 1.867 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.867 ms/op


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
# Warmup Iteration   1: 5.406 ±(99.9%) 0.066 ms/op
Iteration   1: 3.285 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.285 ms/op


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
# Warmup Iteration   1: 11.480 ±(99.9%) 0.240 ms/op
Iteration   1: 8.156 ±(99.9%) 0.074 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.156 ms/op


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
# Warmup Iteration   1: 5.142 ±(99.9%) 0.114 ms/op
Iteration   1: 2.932 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   2.806 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   4.185 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  13.913 ms/op
                 createUser·p0.9999: 15.630 ms/op
                 createUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10905
  mean =      2.932 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 2921 
    [ 2.500,  3.750) = 7149 
    [ 3.750,  5.000) = 586 
    [ 5.000,  6.250) = 109 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      4.185 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     13.913 ms/op
     p(99.9900) =     15.630 ms/op
     p(99.9990) =     15.630 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.077 ms/op
Iteration   1: 1.913 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.200 ms/op
                 existUser·p0.95:   2.408 ms/op
                 existUser·p0.99:   3.554 ms/op
                 existUser·p0.999:  17.767 ms/op
                 existUser·p0.9999: 17.826 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16787
  mean =      1.913 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 16115 
    [ 2.500,  3.750) = 402 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      3.554 ms/op
     p(99.9000) =     17.767 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.253 ±(99.9%) 0.093 ms/op
Iteration   1: 3.014 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   2.830 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.248 ms/op
                 getUser·p0.999:  7.155 ms/op
                 getUser·p0.9999: 8.737 ms/op
                 getUser·p1.00:   8.749 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10567
  mean =      3.014 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 5 
    [1.000, 1.500) = 25 
    [1.500, 2.000) = 73 
    [2.000, 2.500) = 2258 
    [2.500, 3.000) = 3647 
    [3.000, 3.500) = 2397 
    [3.500, 4.000) = 1484 
    [4.000, 4.500) = 394 
    [4.500, 5.000) = 151 
    [5.000, 5.500) = 62 
    [5.500, 6.000) = 14 
    [6.000, 6.500) = 3 
    [6.500, 7.000) = 26 
    [7.000, 7.500) = 25 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.248 ms/op
     p(99.9000) =      7.155 ms/op
     p(99.9900) =      8.737 ms/op
     p(99.9990) =      8.749 ms/op
     p(99.9999) =      8.749 ms/op
    p(100.0000) =      8.749 ms/op


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
# Warmup Iteration   1: 11.298 ±(99.9%) 0.400 ms/op
Iteration   1: 7.463 ±(99.9%) 0.105 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   7.176 ms/op
                 listUser·p0.90:   9.732 ms/op
                 listUser·p0.95:   10.699 ms/op
                 listUser·p0.99:   14.669 ms/op
                 listUser·p0.999:  22.997 ms/op
                 listUser·p0.9999: 24.740 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4293
  mean =      7.463 ±(99.9%) 0.105 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 258 
    [ 5.000,  7.500) = 2223 
    [ 7.500, 10.000) = 1458 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.294 ms/op
     p(50.0000) =      7.176 ms/op
     p(90.0000) =      9.732 ms/op
     p(95.0000) =     10.699 ms/op
     p(99.0000) =     14.669 ms/op
     p(99.9000) =     22.997 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.180          ops/ms
Client.existUser                       thrpt         12.915          ops/ms
Client.getUser                         thrpt          8.104          ops/ms
Client.listUser                        thrpt          3.503          ops/ms
Client.createUser                       avgt          3.252           ms/op
Client.existUser                        avgt          1.867           ms/op
Client.getUser                          avgt          3.285           ms/op
Client.listUser                         avgt          8.156           ms/op
Client.createUser                     sample  10905   2.932 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.010           ms/op
Client.createUser:createUser·p0.50    sample          2.806           ms/op
Client.createUser:createUser·p0.90    sample          3.564           ms/op
Client.createUser:createUser·p0.95    sample          4.185           ms/op
Client.createUser:createUser·p0.99    sample          6.439           ms/op
Client.createUser:createUser·p0.999   sample         13.913           ms/op
Client.createUser:createUser·p0.9999  sample         15.630           ms/op
Client.createUser:createUser·p1.00    sample         15.630           ms/op
Client.existUser                      sample  16787   1.913 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.622           ms/op
Client.existUser:existUser·p0.50      sample          1.839           ms/op
Client.existUser:existUser·p0.90      sample          2.200           ms/op
Client.existUser:existUser·p0.95      sample          2.408           ms/op
Client.existUser:existUser·p0.99      sample          3.554           ms/op
Client.existUser:existUser·p0.999     sample         17.767           ms/op
Client.existUser:existUser·p0.9999    sample         17.826           ms/op
Client.existUser:existUser·p1.00      sample         17.826           ms/op
Client.getUser                        sample  10567   3.014 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.716           ms/op
Client.getUser:getUser·p0.50          sample          2.830           ms/op
Client.getUser:getUser·p0.90          sample          3.838           ms/op
Client.getUser:getUser·p0.95          sample          4.100           ms/op
Client.getUser:getUser·p0.99          sample          5.248           ms/op
Client.getUser:getUser·p0.999         sample          7.155           ms/op
Client.getUser:getUser·p0.9999        sample          8.737           ms/op
Client.getUser:getUser·p1.00          sample          8.749           ms/op
Client.listUser                       sample   4293   7.463 ± 0.105   ms/op
Client.listUser:listUser·p0.00        sample          2.294           ms/op
Client.listUser:listUser·p0.50        sample          7.176           ms/op
Client.listUser:listUser·p0.90        sample          9.732           ms/op
Client.listUser:listUser·p0.95        sample         10.699           ms/op
Client.listUser:listUser·p0.99        sample         14.669           ms/op
Client.listUser:listUser·p0.999       sample         22.997           ms/op
Client.listUser:listUser·p0.9999      sample         24.740           ms/op
Client.listUser:listUser·p1.00        sample         24.740           ms/op
