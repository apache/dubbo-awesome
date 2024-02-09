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
# Warmup Iteration   1: 2.261 ops/ms
Iteration   1: 6.008 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.008 ops/ms


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
# Warmup Iteration   1: 5.771 ops/ms
Iteration   1: 12.444 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.444 ops/ms


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
# Warmup Iteration   1: 3.755 ops/ms
Iteration   1: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.380 ops/ms


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
# Warmup Iteration   1: 2.149 ops/ms
Iteration   1: 3.999 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.999 ops/ms


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
# Warmup Iteration   1: 5.649 ±(99.9%) 0.128 ms/op
Iteration   1: 3.043 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.043 ms/op


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
# Warmup Iteration   1: 3.043 ±(99.9%) 0.025 ms/op
Iteration   1: 1.750 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.750 ms/op


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
# Warmup Iteration   1: 4.762 ±(99.9%) 0.065 ms/op
Iteration   1: 3.333 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.333 ms/op


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
# Warmup Iteration   1: 11.863 ±(99.9%) 0.256 ms/op
Iteration   1: 9.558 ±(99.9%) 0.111 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.558 ms/op


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
# Warmup Iteration   1: 5.074 ±(99.9%) 0.095 ms/op
Iteration   1: 3.049 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   2.822 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   7.430 ms/op
                 createUser·p0.999:  14.165 ms/op
                 createUser·p0.9999: 15.593 ms/op
                 createUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10712
  mean =      3.049 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 2938 
    [ 2.500,  3.750) = 6224 
    [ 3.750,  5.000) = 1227 
    [ 5.000,  6.250) = 135 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     14.165 ms/op
     p(99.9900) =     15.593 ms/op
     p(99.9990) =     15.598 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 3.497 ±(99.9%) 0.096 ms/op
Iteration   1: 1.867 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   1.655 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.908 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  24.113 ms/op
                 existUser·p0.9999: 24.178 ms/op
                 existUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17119
  mean =      1.867 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15486 
    [ 2.500,  5.000) = 1588 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      1.655 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =     24.113 ms/op
     p(99.9900) =     24.178 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.754 ±(99.9%) 0.126 ms/op
Iteration   1: 3.060 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   5.797 ms/op
                 getUser·p0.999:  25.887 ms/op
                 getUser·p0.9999: 27.522 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10434
  mean =      3.060 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2594 
    [ 2.500,  5.000) = 7637 
    [ 5.000,  7.500) = 138 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.797 ms/op
     p(99.9000) =     25.887 ms/op
     p(99.9900) =     27.522 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 12.025 ±(99.9%) 0.433 ms/op
Iteration   1: 7.254 ±(99.9%) 0.090 ms/op
                 listUser·p0.00:   3.133 ms/op
                 listUser·p0.50:   7.045 ms/op
                 listUser·p0.90:   9.126 ms/op
                 listUser·p0.95:   9.952 ms/op
                 listUser·p0.99:   12.338 ms/op
                 listUser·p0.999:  20.989 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4411
  mean =      7.254 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 207 
    [ 5.000,  7.500) = 2567 
    [ 7.500, 10.000) = 1424 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.133 ms/op
     p(50.0000) =      7.045 ms/op
     p(90.0000) =      9.126 ms/op
     p(95.0000) =      9.952 ms/op
     p(99.0000) =     12.338 ms/op
     p(99.9000) =     20.989 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.008          ops/ms
Client.existUser                       thrpt         12.444          ops/ms
Client.getUser                         thrpt          8.380          ops/ms
Client.listUser                        thrpt          3.999          ops/ms
Client.createUser                       avgt          3.043           ms/op
Client.existUser                        avgt          1.750           ms/op
Client.getUser                          avgt          3.333           ms/op
Client.listUser                         avgt          9.558           ms/op
Client.createUser                     sample  10712   3.049 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          1.130           ms/op
Client.createUser:createUser·p0.50    sample          2.822           ms/op
Client.createUser:createUser·p0.90    sample          3.957           ms/op
Client.createUser:createUser·p0.95    sample          4.293           ms/op
Client.createUser:createUser·p0.99    sample          7.430           ms/op
Client.createUser:createUser·p0.999   sample         14.165           ms/op
Client.createUser:createUser·p0.9999  sample         15.593           ms/op
Client.createUser:createUser·p1.00    sample         15.598           ms/op
Client.existUser                      sample  17119   1.867 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.667           ms/op
Client.existUser:existUser·p0.50      sample          1.655           ms/op
Client.existUser:existUser·p0.90      sample          2.458           ms/op
Client.existUser:existUser·p0.95      sample          2.908           ms/op
Client.existUser:existUser·p0.99      sample          3.666           ms/op
Client.existUser:existUser·p0.999     sample         24.113           ms/op
Client.existUser:existUser·p0.9999    sample         24.178           ms/op
Client.existUser:existUser·p1.00      sample         24.248           ms/op
Client.getUser                        sample  10434   3.060 ± 0.049   ms/op
Client.getUser:getUser·p0.00          sample          0.825           ms/op
Client.getUser:getUser·p0.50          sample          2.925           ms/op
Client.getUser:getUser·p0.90          sample          3.785           ms/op
Client.getUser:getUser·p0.95          sample          4.141           ms/op
Client.getUser:getUser·p0.99          sample          5.797           ms/op
Client.getUser:getUser·p0.999         sample         25.887           ms/op
Client.getUser:getUser·p0.9999        sample         27.522           ms/op
Client.getUser:getUser·p1.00          sample         27.525           ms/op
Client.listUser                       sample   4411   7.254 ± 0.090   ms/op
Client.listUser:listUser·p0.00        sample          3.133           ms/op
Client.listUser:listUser·p0.50        sample          7.045           ms/op
Client.listUser:listUser·p0.90        sample          9.126           ms/op
Client.listUser:listUser·p0.95        sample          9.952           ms/op
Client.listUser:listUser·p0.99        sample         12.338           ms/op
Client.listUser:listUser·p0.999       sample         20.989           ms/op
Client.listUser:listUser·p0.9999      sample         22.774           ms/op
Client.listUser:listUser·p1.00        sample         22.774           ms/op
