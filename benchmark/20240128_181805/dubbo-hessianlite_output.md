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
# Warmup Iteration   1: 2.629 ops/ms
Iteration   1: 7.216 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.216 ops/ms


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
# Warmup Iteration   1: 6.021 ops/ms
Iteration   1: 12.340 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.340 ops/ms


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
# Warmup Iteration   1: 4.510 ops/ms
Iteration   1: 9.415 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.415 ops/ms


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
# Warmup Iteration   1: 2.243 ops/ms
Iteration   1: 3.749 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.749 ops/ms


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
# Warmup Iteration   1: 5.345 ±(99.9%) 0.063 ms/op
Iteration   1: 3.246 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.246 ms/op


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.032 ms/op
Iteration   1: 1.916 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.916 ms/op


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
# Warmup Iteration   1: 4.602 ±(99.9%) 0.057 ms/op
Iteration   1: 3.013 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.013 ms/op


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
# Warmup Iteration   1: 13.855 ±(99.9%) 0.268 ms/op
Iteration   1: 8.534 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.534 ms/op


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
# Warmup Iteration   1: 4.862 ±(99.9%) 0.117 ms/op
Iteration   1: 3.133 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  25.395 ms/op
                 createUser·p0.9999: 25.813 ms/op
                 createUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10301
  mean =      3.133 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 831 
    [ 2.500,  5.000) = 9274 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     25.395 ms/op
     p(99.9900) =     25.813 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.077 ms/op
Iteration   1: 1.786 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.312 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.486 ms/op
                 existUser·p0.99:   3.410 ms/op
                 existUser·p0.999:  4.400 ms/op
                 existUser·p0.9999: 7.855 ms/op
                 existUser·p1.00:   7.881 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17946
  mean =      1.786 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 5 
    [0.500, 1.000) = 336 
    [1.000, 1.500) = 5474 
    [1.500, 2.000) = 6473 
    [2.000, 2.500) = 4792 
    [2.500, 3.000) = 588 
    [3.000, 3.500) = 131 
    [3.500, 4.000) = 124 
    [4.000, 4.500) = 8 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 6 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.312 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.486 ms/op
     p(99.0000) =      3.410 ms/op
     p(99.9000) =      4.400 ms/op
     p(99.9900) =      7.855 ms/op
     p(99.9990) =      7.881 ms/op
     p(99.9999) =      7.881 ms/op
    p(100.0000) =      7.881 ms/op


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
# Warmup Iteration   1: 4.700 ±(99.9%) 0.118 ms/op
Iteration   1: 3.042 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.550 ms/op
                 getUser·p0.50:   2.904 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  17.365 ms/op
                 getUser·p0.9999: 17.562 ms/op
                 getUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10536
  mean =      3.042 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 3044 
    [ 2.500,  3.750) = 5897 
    [ 3.750,  5.000) = 1350 
    [ 5.000,  6.250) = 121 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     17.365 ms/op
     p(99.9900) =     17.562 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 11.205 ±(99.9%) 0.339 ms/op
Iteration   1: 7.744 ±(99.9%) 0.123 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   7.389 ms/op
                 listUser·p0.90:   10.142 ms/op
                 listUser·p0.95:   11.305 ms/op
                 listUser·p0.99:   18.275 ms/op
                 listUser·p0.999:  26.266 ms/op
                 listUser·p0.9999: 29.196 ms/op
                 listUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4137
  mean =      7.744 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 242 
    [ 5.000,  7.500) = 1932 
    [ 7.500, 10.000) = 1511 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.507 ms/op
     p(50.0000) =      7.389 ms/op
     p(90.0000) =     10.142 ms/op
     p(95.0000) =     11.305 ms/op
     p(99.0000) =     18.275 ms/op
     p(99.9000) =     26.266 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          7.216          ops/ms
Client.existUser                       thrpt         12.340          ops/ms
Client.getUser                         thrpt          9.415          ops/ms
Client.listUser                        thrpt          3.749          ops/ms
Client.createUser                       avgt          3.246           ms/op
Client.existUser                        avgt          1.916           ms/op
Client.getUser                          avgt          3.013           ms/op
Client.listUser                         avgt          8.534           ms/op
Client.createUser                     sample  10301   3.133 ± 0.048   ms/op
Client.createUser:createUser·p0.00    sample          1.237           ms/op
Client.createUser:createUser·p0.50    sample          2.945           ms/op
Client.createUser:createUser·p0.90    sample          3.629           ms/op
Client.createUser:createUser·p0.95    sample          3.920           ms/op
Client.createUser:createUser·p0.99    sample          6.881           ms/op
Client.createUser:createUser·p0.999   sample         25.395           ms/op
Client.createUser:createUser·p0.9999  sample         25.813           ms/op
Client.createUser:createUser·p1.00    sample         25.821           ms/op
Client.existUser                      sample  17946   1.786 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.312           ms/op
Client.existUser:existUser·p0.50      sample          1.788           ms/op
Client.existUser:existUser·p0.90      sample          2.294           ms/op
Client.existUser:existUser·p0.95      sample          2.486           ms/op
Client.existUser:existUser·p0.99      sample          3.410           ms/op
Client.existUser:existUser·p0.999     sample          4.400           ms/op
Client.existUser:existUser·p0.9999    sample          7.855           ms/op
Client.existUser:existUser·p1.00      sample          7.881           ms/op
Client.getUser                        sample  10536   3.042 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          0.550           ms/op
Client.getUser:getUser·p0.50          sample          2.904           ms/op
Client.getUser:getUser·p0.90          sample          3.920           ms/op
Client.getUser:getUser·p0.95          sample          4.383           ms/op
Client.getUser:getUser·p0.99          sample          5.767           ms/op
Client.getUser:getUser·p0.999         sample         17.365           ms/op
Client.getUser:getUser·p0.9999        sample         17.562           ms/op
Client.getUser:getUser·p1.00          sample         17.564           ms/op
Client.listUser                       sample   4137   7.744 ± 0.123   ms/op
Client.listUser:listUser·p0.00        sample          2.507           ms/op
Client.listUser:listUser·p0.50        sample          7.389           ms/op
Client.listUser:listUser·p0.90        sample         10.142           ms/op
Client.listUser:listUser·p0.95        sample         11.305           ms/op
Client.listUser:listUser·p0.99        sample         18.275           ms/op
Client.listUser:listUser·p0.999       sample         26.266           ms/op
Client.listUser:listUser·p0.9999      sample         29.196           ms/op
Client.listUser:listUser·p1.00        sample         29.196           ms/op
