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
# Warmup Iteration   1: 2.258 ops/ms
Iteration   1: 5.466 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.466 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.279 ops/ms
Iteration   1: 10.960 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.960 ops/ms


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
# Warmup Iteration   1: 3.657 ops/ms
Iteration   1: 7.450 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.450 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.724 ops/ms
Iteration   1: 3.820 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.820 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.492 ±(99.9%) 0.078 ms/op
Iteration   1: 3.483 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.483 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.275 ±(99.9%) 0.037 ms/op
Iteration   1: 1.830 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.830 ms/op


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.049 ms/op
Iteration   1: 3.066 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.066 ms/op


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
# Warmup Iteration   1: 12.242 ±(99.9%) 0.312 ms/op
Iteration   1: 8.426 ±(99.9%) 0.076 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.426 ms/op


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
# Warmup Iteration   1: 5.086 ±(99.9%) 0.114 ms/op
Iteration   1: 3.203 ±(99.9%) 0.060 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   8.969 ms/op
                 createUser·p0.999:  32.449 ms/op
                 createUser·p0.9999: 33.258 ms/op
                 createUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10056
  mean =      3.203 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1298 
    [ 2.500,  5.000) = 8502 
    [ 5.000,  7.500) = 130 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      8.969 ms/op
     p(99.9000) =     32.449 ms/op
     p(99.9900) =     33.258 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.110 ms/op
Iteration   1: 2.223 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   2.171 ms/op
                 existUser·p0.90:   2.695 ms/op
                 existUser·p0.95:   2.920 ms/op
                 existUser·p0.99:   3.933 ms/op
                 existUser·p0.999:  16.388 ms/op
                 existUser·p0.9999: 16.580 ms/op
                 existUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14378
  mean =      2.223 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 217 
    [ 1.250,  2.500) = 10954 
    [ 2.500,  3.750) = 3040 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      3.933 ms/op
     p(99.9000) =     16.388 ms/op
     p(99.9900) =     16.580 ms/op
     p(99.9990) =     16.630 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 4.490 ±(99.9%) 0.110 ms/op
Iteration   1: 2.802 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   2.671 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.712 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.736 ms/op
                 getUser·p0.9999: 7.411 ms/op
                 getUser·p1.00:   7.430 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11574
  mean =      2.802 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 34 
    [1.500, 2.000) = 220 
    [2.000, 2.500) = 3395 
    [2.500, 3.000) = 4685 
    [3.000, 3.500) = 2073 
    [3.500, 4.000) = 888 
    [4.000, 4.500) = 166 
    [4.500, 5.000) = 19 
    [5.000, 5.500) = 10 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 42 
    [6.500, 7.000) = 35 
    [7.000, 7.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.712 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      6.736 ms/op
     p(99.9900) =      7.411 ms/op
     p(99.9990) =      7.430 ms/op
     p(99.9999) =      7.430 ms/op
    p(100.0000) =      7.430 ms/op


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
# Warmup Iteration   1: 12.032 ±(99.9%) 0.410 ms/op
Iteration   1: 7.631 ±(99.9%) 0.097 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   7.389 ms/op
                 listUser·p0.90:   9.863 ms/op
                 listUser·p0.95:   11.026 ms/op
                 listUser·p0.99:   14.329 ms/op
                 listUser·p0.999:  19.294 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4196
  mean =      7.631 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 162 
    [ 5.000,  7.500) = 2084 
    [ 7.500, 10.000) = 1554 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      7.389 ms/op
     p(90.0000) =      9.863 ms/op
     p(95.0000) =     11.026 ms/op
     p(99.0000) =     14.329 ms/op
     p(99.9000) =     19.294 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.466          ops/ms
Client.existUser                       thrpt         10.960          ops/ms
Client.getUser                         thrpt          7.450          ops/ms
Client.listUser                        thrpt          3.820          ops/ms
Client.createUser                       avgt          3.483           ms/op
Client.existUser                        avgt          1.830           ms/op
Client.getUser                          avgt          3.066           ms/op
Client.listUser                         avgt          8.426           ms/op
Client.createUser                     sample  10056   3.203 ± 0.060   ms/op
Client.createUser:createUser·p0.00    sample          1.264           ms/op
Client.createUser:createUser·p0.50    sample          2.978           ms/op
Client.createUser:createUser·p0.90    sample          3.785           ms/op
Client.createUser:createUser·p0.95    sample          4.375           ms/op
Client.createUser:createUser·p0.99    sample          8.969           ms/op
Client.createUser:createUser·p0.999   sample         32.449           ms/op
Client.createUser:createUser·p0.9999  sample         33.258           ms/op
Client.createUser:createUser·p1.00    sample         33.260           ms/op
Client.existUser                      sample  14378   2.223 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.800           ms/op
Client.existUser:existUser·p0.50      sample          2.171           ms/op
Client.existUser:existUser·p0.90      sample          2.695           ms/op
Client.existUser:existUser·p0.95      sample          2.920           ms/op
Client.existUser:existUser·p0.99      sample          3.933           ms/op
Client.existUser:existUser·p0.999     sample         16.388           ms/op
Client.existUser:existUser·p0.9999    sample         16.580           ms/op
Client.existUser:existUser·p1.00      sample         16.630           ms/op
Client.getUser                        sample  11574   2.802 ± 0.018   ms/op
Client.getUser:getUser·p0.00          sample          1.053           ms/op
Client.getUser:getUser·p0.50          sample          2.671           ms/op
Client.getUser:getUser·p0.90          sample          3.506           ms/op
Client.getUser:getUser·p0.95          sample          3.712           ms/op
Client.getUser:getUser·p0.99          sample          4.407           ms/op
Client.getUser:getUser·p0.999         sample          6.736           ms/op
Client.getUser:getUser·p0.9999        sample          7.411           ms/op
Client.getUser:getUser·p1.00          sample          7.430           ms/op
Client.listUser                       sample   4196   7.631 ± 0.097   ms/op
Client.listUser:listUser·p0.00        sample          2.171           ms/op
Client.listUser:listUser·p0.50        sample          7.389           ms/op
Client.listUser:listUser·p0.90        sample          9.863           ms/op
Client.listUser:listUser·p0.95        sample         11.026           ms/op
Client.listUser:listUser·p0.99        sample         14.329           ms/op
Client.listUser:listUser·p0.999       sample         19.294           ms/op
Client.listUser:listUser·p0.9999      sample         20.709           ms/op
Client.listUser:listUser·p1.00        sample         20.709           ms/op
