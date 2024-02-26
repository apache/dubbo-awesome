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
# Warmup Iteration   1: 2.384 ops/ms
Iteration   1: 6.473 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.473 ops/ms


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
# Warmup Iteration   1: 6.163 ops/ms
Iteration   1: 15.347 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  15.347 ops/ms


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
# Warmup Iteration   1: 3.644 ops/ms
Iteration   1: 8.555 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.555 ops/ms


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
# Warmup Iteration   1: 2.237 ops/ms
Iteration   1: 3.604 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.604 ops/ms


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
# Warmup Iteration   1: 6.319 ±(99.9%) 0.091 ms/op
Iteration   1: 3.052 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.052 ms/op


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
# Warmup Iteration   1: 3.103 ±(99.9%) 0.033 ms/op
Iteration   1: 1.768 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.768 ms/op


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.047 ms/op
Iteration   1: 2.922 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.922 ms/op


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
# Warmup Iteration   1: 13.374 ±(99.9%) 0.281 ms/op
Iteration   1: 8.111 ±(99.9%) 0.116 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.111 ms/op


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
# Warmup Iteration   1: 4.703 ±(99.9%) 0.103 ms/op
Iteration   1: 3.220 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   7.887 ms/op
                 createUser·p0.999:  16.286 ms/op
                 createUser·p0.9999: 17.891 ms/op
                 createUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9927
  mean =      3.220 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1723 
    [ 2.500,  3.750) = 6020 
    [ 3.750,  5.000) = 1987 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      7.887 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.078 ms/op
Iteration   1: 1.951 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   1.909 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   3.134 ms/op
                 existUser·p0.999:  5.450 ms/op
                 existUser·p0.9999: 6.879 ms/op
                 existUser·p1.00:   7.315 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16424
  mean =      1.951 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 54 
    [1.000, 1.500) = 1576 
    [1.500, 2.000) = 7946 
    [2.000, 2.500) = 5584 
    [2.500, 3.000) = 1072 
    [3.000, 3.500) = 93 
    [3.500, 4.000) = 16 
    [4.000, 4.500) = 48 
    [4.500, 5.000) = 10 
    [5.000, 5.500) = 10 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 9 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.134 ms/op
     p(99.9000) =      5.450 ms/op
     p(99.9900) =      6.879 ms/op
     p(99.9990) =      7.315 ms/op
     p(99.9999) =      7.315 ms/op
    p(100.0000) =      7.315 ms/op


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
# Warmup Iteration   1: 4.107 ±(99.9%) 0.090 ms/op
Iteration   1: 3.121 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  8.518 ms/op
                 getUser·p0.9999: 9.011 ms/op
                 getUser·p1.00:   9.011 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10238
  mean =      3.121 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 12 
    [ 1.500,  2.000) = 101 
    [ 2.000,  2.500) = 2085 
    [ 2.500,  3.000) = 2603 
    [ 3.000,  3.500) = 2925 
    [ 3.500,  4.000) = 1503 
    [ 4.000,  4.500) = 564 
    [ 4.500,  5.000) = 243 
    [ 5.000,  5.500) = 37 
    [ 5.500,  6.000) = 78 
    [ 6.000,  6.500) = 46 
    [ 6.500,  7.000) = 6 
    [ 7.000,  7.500) = 2 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 23 
    [ 8.500,  9.000) = 8 
    [ 9.000,  9.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =      8.518 ms/op
     p(99.9900) =      9.011 ms/op
     p(99.9990) =      9.011 ms/op
     p(99.9999) =      9.011 ms/op
    p(100.0000) =      9.011 ms/op


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
# Warmup Iteration   1: 11.205 ±(99.9%) 0.357 ms/op
Iteration   1: 7.605 ±(99.9%) 0.125 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   7.291 ms/op
                 listUser·p0.90:   9.911 ms/op
                 listUser·p0.95:   10.879 ms/op
                 listUser·p0.99:   17.569 ms/op
                 listUser·p0.999:  27.220 ms/op
                 listUser·p0.9999: 31.031 ms/op
                 listUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4260
  mean =      7.605 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 295 
    [ 5.000,  7.500) = 2040 
    [ 7.500, 10.000) = 1525 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.343 ms/op
     p(50.0000) =      7.291 ms/op
     p(90.0000) =      9.911 ms/op
     p(95.0000) =     10.879 ms/op
     p(99.0000) =     17.569 ms/op
     p(99.9000) =     27.220 ms/op
     p(99.9900) =     31.031 ms/op
     p(99.9990) =     31.031 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.473          ops/ms
Client.existUser                       thrpt         15.347          ops/ms
Client.getUser                         thrpt          8.555          ops/ms
Client.listUser                        thrpt          3.604          ops/ms
Client.createUser                       avgt          3.052           ms/op
Client.existUser                        avgt          1.768           ms/op
Client.getUser                          avgt          2.922           ms/op
Client.listUser                         avgt          8.111           ms/op
Client.createUser                     sample   9927   3.220 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          1.337           ms/op
Client.createUser:createUser·p0.50    sample          2.982           ms/op
Client.createUser:createUser·p0.90    sample          4.190           ms/op
Client.createUser:createUser·p0.95    sample          4.448           ms/op
Client.createUser:createUser·p0.99    sample          7.887           ms/op
Client.createUser:createUser·p0.999   sample         16.286           ms/op
Client.createUser:createUser·p0.9999  sample         17.891           ms/op
Client.createUser:createUser·p1.00    sample         17.891           ms/op
Client.existUser                      sample  16424   1.951 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.581           ms/op
Client.existUser:existUser·p0.50      sample          1.909           ms/op
Client.existUser:existUser·p0.90      sample          2.433           ms/op
Client.existUser:existUser·p0.95      sample          2.638           ms/op
Client.existUser:existUser·p0.99      sample          3.134           ms/op
Client.existUser:existUser·p0.999     sample          5.450           ms/op
Client.existUser:existUser·p0.9999    sample          6.879           ms/op
Client.existUser:existUser·p1.00      sample          7.315           ms/op
Client.getUser                        sample  10238   3.121 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          1.147           ms/op
Client.getUser:getUser·p0.50          sample          3.043           ms/op
Client.getUser:getUser·p0.90          sample          3.994           ms/op
Client.getUser:getUser·p0.95          sample          4.432           ms/op
Client.getUser:getUser·p0.99          sample          5.849           ms/op
Client.getUser:getUser·p0.999         sample          8.518           ms/op
Client.getUser:getUser·p0.9999        sample          9.011           ms/op
Client.getUser:getUser·p1.00          sample          9.011           ms/op
Client.listUser                       sample   4260   7.605 ± 0.125   ms/op
Client.listUser:listUser·p0.00        sample          2.343           ms/op
Client.listUser:listUser·p0.50        sample          7.291           ms/op
Client.listUser:listUser·p0.90        sample          9.911           ms/op
Client.listUser:listUser·p0.95        sample         10.879           ms/op
Client.listUser:listUser·p0.99        sample         17.569           ms/op
Client.listUser:listUser·p0.999       sample         27.220           ms/op
Client.listUser:listUser·p0.9999      sample         31.031           ms/op
Client.listUser:listUser·p1.00        sample         31.031           ms/op
