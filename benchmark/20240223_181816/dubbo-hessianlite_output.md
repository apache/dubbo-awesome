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
# Warmup Iteration   1: 2.608 ops/ms
Iteration   1: 6.553 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.553 ops/ms


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
# Warmup Iteration   1: 6.489 ops/ms
Iteration   1: 13.065 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.065 ops/ms


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
# Warmup Iteration   1: 4.749 ops/ms
Iteration   1: 9.822 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.822 ops/ms


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
# Warmup Iteration   1: 2.307 ops/ms
Iteration   1: 3.563 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.563 ops/ms


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
# Warmup Iteration   1: 5.724 ±(99.9%) 0.079 ms/op
Iteration   1: 3.041 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.041 ms/op


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
# Warmup Iteration   1: 2.908 ±(99.9%) 0.032 ms/op
Iteration   1: 2.067 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.067 ms/op


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
# Warmup Iteration   1: 5.094 ±(99.9%) 0.064 ms/op
Iteration   1: 2.952 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.952 ms/op


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
# Warmup Iteration   1: 12.547 ±(99.9%) 0.296 ms/op
Iteration   1: 8.401 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.401 ms/op


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
# Warmup Iteration   1: 5.538 ±(99.9%) 0.136 ms/op
Iteration   1: 3.073 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   2.818 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.249 ms/op
                 createUser·p0.99:   9.470 ms/op
                 createUser·p0.999:  13.337 ms/op
                 createUser·p0.9999: 15.968 ms/op
                 createUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10525
  mean =      3.073 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2578 
    [ 2.500,  3.750) = 6702 
    [ 3.750,  5.000) = 840 
    [ 5.000,  6.250) = 162 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.249 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     15.968 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.080 ms/op
Iteration   1: 2.017 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.205 ms/op
                 existUser·p0.50:   2.011 ms/op
                 existUser·p0.90:   2.454 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   3.181 ms/op
                 existUser·p0.999:  4.622 ms/op
                 existUser·p0.9999: 6.384 ms/op
                 existUser·p1.00:   6.849 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15843
  mean =      2.017 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 8 
    [0.500, 1.000) = 84 
    [1.000, 1.500) = 1272 
    [1.500, 2.000) = 6346 
    [2.000, 2.500) = 6858 
    [2.500, 3.000) = 1032 
    [3.000, 3.500) = 157 
    [3.500, 4.000) = 42 
    [4.000, 4.500) = 28 
    [4.500, 5.000) = 5 
    [5.000, 5.500) = 5 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.205 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.181 ms/op
     p(99.9000) =      4.622 ms/op
     p(99.9900) =      6.384 ms/op
     p(99.9990) =      6.849 ms/op
     p(99.9999) =      6.849 ms/op
    p(100.0000) =      6.849 ms/op


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
# Warmup Iteration   1: 4.517 ±(99.9%) 0.097 ms/op
Iteration   1: 2.941 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   2.884 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.135 ms/op
                 getUser·p0.99:   5.795 ms/op
                 getUser·p0.999:  6.734 ms/op
                 getUser·p0.9999: 7.787 ms/op
                 getUser·p1.00:   7.864 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10851
  mean =      2.941 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 23 
    [1.500, 2.000) = 491 
    [2.000, 2.500) = 2687 
    [2.500, 3.000) = 2986 
    [3.000, 3.500) = 2897 
    [3.500, 4.000) = 1097 
    [4.000, 4.500) = 336 
    [4.500, 5.000) = 141 
    [5.000, 5.500) = 69 
    [5.500, 6.000) = 33 
    [6.000, 6.500) = 35 
    [6.500, 7.000) = 55 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.135 ms/op
     p(99.0000) =      5.795 ms/op
     p(99.9000) =      6.734 ms/op
     p(99.9900) =      7.787 ms/op
     p(99.9990) =      7.864 ms/op
     p(99.9999) =      7.864 ms/op
    p(100.0000) =      7.864 ms/op


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
# Warmup Iteration   1: 11.617 ±(99.9%) 0.404 ms/op
Iteration   1: 8.020 ±(99.9%) 0.111 ms/op
                 listUser·p0.00:   2.748 ms/op
                 listUser·p0.50:   7.741 ms/op
                 listUser·p0.90:   10.486 ms/op
                 listUser·p0.95:   11.869 ms/op
                 listUser·p0.99:   15.073 ms/op
                 listUser·p0.999:  19.594 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4035
  mean =      8.020 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 127 
    [ 5.000,  7.500) = 1668 
    [ 7.500, 10.000) = 1728 
    [10.000, 12.500) = 378 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.748 ms/op
     p(50.0000) =      7.741 ms/op
     p(90.0000) =     10.486 ms/op
     p(95.0000) =     11.869 ms/op
     p(99.0000) =     15.073 ms/op
     p(99.9000) =     19.594 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.553          ops/ms
Client.existUser                       thrpt         13.065          ops/ms
Client.getUser                         thrpt          9.822          ops/ms
Client.listUser                        thrpt          3.563          ops/ms
Client.createUser                       avgt          3.041           ms/op
Client.existUser                        avgt          2.067           ms/op
Client.getUser                          avgt          2.952           ms/op
Client.listUser                         avgt          8.401           ms/op
Client.createUser                     sample  10525   3.073 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.182           ms/op
Client.createUser:createUser·p0.50    sample          2.818           ms/op
Client.createUser:createUser·p0.90    sample          3.863           ms/op
Client.createUser:createUser·p0.95    sample          4.249           ms/op
Client.createUser:createUser·p0.99    sample          9.470           ms/op
Client.createUser:createUser·p0.999   sample         13.337           ms/op
Client.createUser:createUser·p0.9999  sample         15.968           ms/op
Client.createUser:createUser·p1.00    sample         16.056           ms/op
Client.existUser                      sample  15843   2.017 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.205           ms/op
Client.existUser:existUser·p0.50      sample          2.011           ms/op
Client.existUser:existUser·p0.90      sample          2.454           ms/op
Client.existUser:existUser·p0.95      sample          2.630           ms/op
Client.existUser:existUser·p0.99      sample          3.181           ms/op
Client.existUser:existUser·p0.999     sample          4.622           ms/op
Client.existUser:existUser·p0.9999    sample          6.384           ms/op
Client.existUser:existUser·p1.00      sample          6.849           ms/op
Client.getUser                        sample  10851   2.941 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          1.135           ms/op
Client.getUser:getUser·p0.50          sample          2.884           ms/op
Client.getUser:getUser·p0.90          sample          3.731           ms/op
Client.getUser:getUser·p0.95          sample          4.135           ms/op
Client.getUser:getUser·p0.99          sample          5.795           ms/op
Client.getUser:getUser·p0.999         sample          6.734           ms/op
Client.getUser:getUser·p0.9999        sample          7.787           ms/op
Client.getUser:getUser·p1.00          sample          7.864           ms/op
Client.listUser                       sample   4035   8.020 ± 0.111   ms/op
Client.listUser:listUser·p0.00        sample          2.748           ms/op
Client.listUser:listUser·p0.50        sample          7.741           ms/op
Client.listUser:listUser·p0.90        sample         10.486           ms/op
Client.listUser:listUser·p0.95        sample         11.869           ms/op
Client.listUser:listUser·p0.99        sample         15.073           ms/op
Client.listUser:listUser·p0.999       sample         19.594           ms/op
Client.listUser:listUser·p0.9999      sample         21.463           ms/op
Client.listUser:listUser·p1.00        sample         21.463           ms/op
