# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.137 ops/ms
Iteration   1: 2.410 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.410 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.697 ops/ms
Iteration   1: 6.099 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.099 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.700 ops/ms
Iteration   1: 5.087 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.087 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.815 ops/ms
Iteration   1: 1.375 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.375 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 18.284 ±(99.9%) 0.281 ms/op
Iteration   1: 7.608 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.608 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.647 ±(99.9%) 0.081 ms/op
Iteration   1: 4.003 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.003 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.625 ±(99.9%) 0.168 ms/op
Iteration   1: 4.720 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.720 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 29.977 ±(99.9%) 0.409 ms/op
Iteration   1: 21.015 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  21.015 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.170 ±(99.9%) 0.352 ms/op
Iteration   1: 7.192 ±(99.9%) 0.166 ms/op
                 createUser·p0.00:   3.273 ms/op
                 createUser·p0.50:   6.136 ms/op
                 createUser·p0.90:   7.823 ms/op
                 createUser·p0.95:   15.155 ms/op
                 createUser·p0.99:   25.887 ms/op
                 createUser·p0.999:  26.116 ms/op
                 createUser·p0.9999: 26.870 ms/op
                 createUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4436
  mean =      7.192 ±(99.9%) 0.166 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4 
    [ 5.000,  7.500) = 3822 
    [ 7.500, 10.000) = 258 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      3.273 ms/op
     p(50.0000) =      6.136 ms/op
     p(90.0000) =      7.823 ms/op
     p(95.0000) =     15.155 ms/op
     p(99.0000) =     25.887 ms/op
     p(99.9000) =     26.116 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.989 ±(99.9%) 0.239 ms/op
Iteration   1: 4.791 ±(99.9%) 0.228 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   4.108 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   6.980 ms/op
                 existUser·p0.99:   31.627 ms/op
                 existUser·p0.999:  82.706 ms/op
                 existUser·p0.9999: 96.862 ms/op
                 existUser·p1.00:   96.862 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6681
  mean =      4.791 ±(99.9%) 0.228 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 6471 
    [ 10.000,  20.000) = 133 
    [ 20.000,  30.000) = 4 
    [ 30.000,  40.000) = 36 
    [ 40.000,  50.000) = 6 
    [ 50.000,  60.000) = 5 
    [ 60.000,  70.000) = 5 
    [ 70.000,  80.000) = 5 
    [ 80.000,  90.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =     31.627 ms/op
     p(99.9000) =     82.706 ms/op
     p(99.9900) =     96.862 ms/op
     p(99.9990) =     96.862 ms/op
     p(99.9999) =     96.862 ms/op
    p(100.0000) =     96.862 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 12.312 ±(99.9%) 0.476 ms/op
Iteration   1: 4.656 ±(99.9%) 0.047 ms/op
                 getUser·p0.00:   1.853 ms/op
                 getUser·p0.50:   4.497 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.841 ms/op
                 getUser·p0.99:   9.610 ms/op
                 getUser·p0.999:  16.908 ms/op
                 getUser·p0.9999: 17.039 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7018
  mean =      4.656 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 8 
    [ 2.500,  3.750) = 472 
    [ 3.750,  5.000) = 5282 
    [ 5.000,  6.250) = 1005 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      9.610 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.511 ±(99.9%) 0.684 ms/op
Iteration   1: 18.751 ±(99.9%) 0.335 ms/op
                 listUser·p0.00:   6.341 ms/op
                 listUser·p0.50:   17.400 ms/op
                 listUser·p0.90:   22.109 ms/op
                 listUser·p0.95:   28.017 ms/op
                 listUser·p0.99:   35.258 ms/op
                 listUser·p0.999:  41.963 ms/op
                 listUser·p0.9999: 42.598 ms/op
                 listUser·p1.00:   42.598 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1692
  mean =     18.751 ±(99.9%) 0.335 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 14 
    [10.000, 15.000) = 105 
    [15.000, 20.000) = 1092 
    [20.000, 25.000) = 386 
    [25.000, 30.000) = 40 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      6.341 ms/op
     p(50.0000) =     17.400 ms/op
     p(90.0000) =     22.109 ms/op
     p(95.0000) =     28.017 ms/op
     p(99.0000) =     35.258 ms/op
     p(99.9000) =     41.963 ms/op
     p(99.9900) =     42.598 ms/op
     p(99.9990) =     42.598 ms/op
     p(99.9999) =     42.598 ms/op
    p(100.0000) =     42.598 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.410          ops/ms
Client.existUser                       thrpt         6.099          ops/ms
Client.getUser                         thrpt         5.087          ops/ms
Client.listUser                        thrpt         1.375          ops/ms
Client.createUser                       avgt         7.608           ms/op
Client.existUser                        avgt         4.003           ms/op
Client.getUser                          avgt         4.720           ms/op
Client.listUser                         avgt        21.015           ms/op
Client.createUser                     sample  4436   7.192 ± 0.166   ms/op
Client.createUser:createUser·p0.00    sample         3.273           ms/op
Client.createUser:createUser·p0.50    sample         6.136           ms/op
Client.createUser:createUser·p0.90    sample         7.823           ms/op
Client.createUser:createUser·p0.95    sample        15.155           ms/op
Client.createUser:createUser·p0.99    sample        25.887           ms/op
Client.createUser:createUser·p0.999   sample        26.116           ms/op
Client.createUser:createUser·p0.9999  sample        26.870           ms/op
Client.createUser:createUser·p1.00    sample        26.870           ms/op
Client.existUser                      sample  6681   4.791 ± 0.228   ms/op
Client.existUser:existUser·p0.00      sample         1.540           ms/op
Client.existUser:existUser·p0.50      sample         4.108           ms/op
Client.existUser:existUser·p0.90      sample         4.874           ms/op
Client.existUser:existUser·p0.95      sample         6.980           ms/op
Client.existUser:existUser·p0.99      sample        31.627           ms/op
Client.existUser:existUser·p0.999     sample        82.706           ms/op
Client.existUser:existUser·p0.9999    sample        96.862           ms/op
Client.existUser:existUser·p1.00      sample        96.862           ms/op
Client.getUser                        sample  7018   4.656 ± 0.047   ms/op
Client.getUser:getUser·p0.00          sample         1.853           ms/op
Client.getUser:getUser·p0.50          sample         4.497           ms/op
Client.getUser:getUser·p0.90          sample         5.333           ms/op
Client.getUser:getUser·p0.95          sample         5.841           ms/op
Client.getUser:getUser·p0.99          sample         9.610           ms/op
Client.getUser:getUser·p0.999         sample        16.908           ms/op
Client.getUser:getUser·p0.9999        sample        17.039           ms/op
Client.getUser:getUser·p1.00          sample        17.039           ms/op
Client.listUser                       sample  1692  18.751 ± 0.335   ms/op
Client.listUser:listUser·p0.00        sample         6.341           ms/op
Client.listUser:listUser·p0.50        sample        17.400           ms/op
Client.listUser:listUser·p0.90        sample        22.109           ms/op
Client.listUser:listUser·p0.95        sample        28.017           ms/op
Client.listUser:listUser·p0.99        sample        35.258           ms/op
Client.listUser:listUser·p0.999       sample        41.963           ms/op
Client.listUser:listUser·p0.9999      sample        42.598           ms/op
Client.listUser:listUser·p1.00        sample        42.598           ms/op
