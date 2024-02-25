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
# Warmup Iteration   1: 2.235 ops/ms
Iteration   1: 6.004 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.004 ops/ms


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
# Warmup Iteration   1: 6.079 ops/ms
Iteration   1: 12.785 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.785 ops/ms


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
# Warmup Iteration   1: 3.853 ops/ms
Iteration   1: 8.843 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.843 ops/ms


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
# Warmup Iteration   1: 1.837 ops/ms
Iteration   1: 3.855 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.855 ops/ms


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
# Warmup Iteration   1: 5.235 ±(99.9%) 0.070 ms/op
Iteration   1: 3.277 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.277 ms/op


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
# Warmup Iteration   1: 3.085 ±(99.9%) 0.028 ms/op
Iteration   1: 1.723 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.723 ms/op


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
# Warmup Iteration   1: 5.177 ±(99.9%) 0.079 ms/op
Iteration   1: 3.386 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.386 ms/op


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
# Warmup Iteration   1: 13.477 ±(99.9%) 0.210 ms/op
Iteration   1: 8.889 ±(99.9%) 0.157 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.889 ms/op


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
# Warmup Iteration   1: 5.015 ±(99.9%) 0.114 ms/op
Iteration   1: 2.840 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   2.695 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  9.740 ms/op
                 createUser·p0.9999: 10.975 ms/op
                 createUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11254
  mean =      2.840 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 74 
    [ 2.000,  3.000) = 8364 
    [ 3.000,  4.000) = 2477 
    [ 4.000,  5.000) = 184 
    [ 5.000,  6.000) = 56 
    [ 6.000,  7.000) = 26 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 39 
    [ 9.000, 10.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      2.695 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.740 ms/op
     p(99.9900) =     10.975 ms/op
     p(99.9990) =     10.977 ms/op
     p(99.9999) =     10.977 ms/op
    p(100.0000) =     10.977 ms/op


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
# Warmup Iteration   1: 2.976 ±(99.9%) 0.067 ms/op
Iteration   1: 1.944 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   1.858 ms/op
                 existUser·p0.90:   2.249 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  34.996 ms/op
                 existUser·p0.9999: 35.436 ms/op
                 existUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16437
  mean =      1.944 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15818 
    [ 2.500,  5.000) = 523 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.249 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =     34.996 ms/op
     p(99.9900) =     35.436 ms/op
     p(99.9990) =     35.521 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.094 ms/op
Iteration   1: 3.058 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.188 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  6.239 ms/op
                 getUser·p0.9999: 6.933 ms/op
                 getUser·p1.00:   6.939 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10448
  mean =      3.058 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 14 
    [1.000, 1.500) = 61 
    [1.500, 2.000) = 401 
    [2.000, 2.500) = 1506 
    [2.500, 3.000) = 3217 
    [3.000, 3.500) = 2818 
    [3.500, 4.000) = 1571 
    [4.000, 4.500) = 549 
    [4.500, 5.000) = 179 
    [5.000, 5.500) = 53 
    [5.500, 6.000) = 32 
    [6.000, 6.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.188 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =      6.239 ms/op
     p(99.9900) =      6.933 ms/op
     p(99.9990) =      6.939 ms/op
     p(99.9999) =      6.939 ms/op
    p(100.0000) =      6.939 ms/op


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
# Warmup Iteration   1: 12.510 ±(99.9%) 0.462 ms/op
Iteration   1: 8.078 ±(99.9%) 0.104 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   7.766 ms/op
                 listUser·p0.90:   10.453 ms/op
                 listUser·p0.95:   11.581 ms/op
                 listUser·p0.99:   15.545 ms/op
                 listUser·p0.999:  21.208 ms/op
                 listUser·p0.9999: 27.099 ms/op
                 listUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3962
  mean =      8.078 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 59 
    [ 5.000,  7.500) = 1624 
    [ 7.500, 10.000) = 1775 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      7.766 ms/op
     p(90.0000) =     10.453 ms/op
     p(95.0000) =     11.581 ms/op
     p(99.0000) =     15.545 ms/op
     p(99.9000) =     21.208 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.004          ops/ms
Client.existUser                       thrpt         12.785          ops/ms
Client.getUser                         thrpt          8.843          ops/ms
Client.listUser                        thrpt          3.855          ops/ms
Client.createUser                       avgt          3.277           ms/op
Client.existUser                        avgt          1.723           ms/op
Client.getUser                          avgt          3.386           ms/op
Client.listUser                         avgt          8.889           ms/op
Client.createUser                     sample  11254   2.840 ± 0.021   ms/op
Client.createUser:createUser·p0.00    sample          1.300           ms/op
Client.createUser:createUser·p0.50    sample          2.695           ms/op
Client.createUser:createUser·p0.90    sample          3.285           ms/op
Client.createUser:createUser·p0.95    sample          3.535           ms/op
Client.createUser:createUser·p0.99    sample          5.530           ms/op
Client.createUser:createUser·p0.999   sample          9.740           ms/op
Client.createUser:createUser·p0.9999  sample         10.975           ms/op
Client.createUser:createUser·p1.00    sample         10.977           ms/op
Client.existUser                      sample  16437   1.944 ± 0.040   ms/op
Client.existUser:existUser·p0.00      sample          0.555           ms/op
Client.existUser:existUser·p0.50      sample          1.858           ms/op
Client.existUser:existUser·p0.90      sample          2.249           ms/op
Client.existUser:existUser·p0.95      sample          2.417           ms/op
Client.existUser:existUser·p0.99      sample          3.547           ms/op
Client.existUser:existUser·p0.999     sample         34.996           ms/op
Client.existUser:existUser·p0.9999    sample         35.436           ms/op
Client.existUser:existUser·p1.00      sample         35.521           ms/op
Client.getUser                        sample  10448   3.058 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.809           ms/op
Client.getUser:getUser·p0.50          sample          3.006           ms/op
Client.getUser:getUser·p0.90          sample          3.924           ms/op
Client.getUser:getUser·p0.95          sample          4.188           ms/op
Client.getUser:getUser·p0.99          sample          5.243           ms/op
Client.getUser:getUser·p0.999         sample          6.239           ms/op
Client.getUser:getUser·p0.9999        sample          6.933           ms/op
Client.getUser:getUser·p1.00          sample          6.939           ms/op
Client.listUser                       sample   3962   8.078 ± 0.104   ms/op
Client.listUser:listUser·p0.00        sample          2.085           ms/op
Client.listUser:listUser·p0.50        sample          7.766           ms/op
Client.listUser:listUser·p0.90        sample         10.453           ms/op
Client.listUser:listUser·p0.95        sample         11.581           ms/op
Client.listUser:listUser·p0.99        sample         15.545           ms/op
Client.listUser:listUser·p0.999       sample         21.208           ms/op
Client.listUser:listUser·p0.9999      sample         27.099           ms/op
Client.listUser:listUser·p1.00        sample         27.099           ms/op
