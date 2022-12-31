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
# Warmup Iteration   1: 1.008 ops/ms
Iteration   1: 2.037 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.037 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.814 ops/ms
Iteration   1: 4.706 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.706 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.543 ops/ms
Iteration   1: 4.273 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.273 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.933 ops/ms
Iteration   1: 1.107 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.107 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 20.748 ±(99.9%) 0.298 ms/op
Iteration   1: 8.216 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.216 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.667 ±(99.9%) 0.094 ms/op
Iteration   1: 5.329 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.329 ms/op


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
# Warmup Iteration   1: 10.808 ±(99.9%) 0.162 ms/op
Iteration   1: 5.853 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.853 ms/op


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
# Warmup Iteration   1: 32.138 ±(99.9%) 0.909 ms/op
Iteration   1: 16.797 ±(99.9%) 0.111 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.797 ms/op


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
# Warmup Iteration   1: 13.134 ±(99.9%) 0.512 ms/op
Iteration   1: 7.693 ±(99.9%) 0.183 ms/op
                 createUser·p0.00:   3.142 ms/op
                 createUser·p0.50:   6.578 ms/op
                 createUser·p0.90:   11.092 ms/op
                 createUser·p0.95:   16.908 ms/op
                 createUser·p0.99:   23.244 ms/op
                 createUser·p0.999:  29.983 ms/op
                 createUser·p0.9999: 30.015 ms/op
                 createUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4160
  mean =      7.693 ±(99.9%) 0.183 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 13 
    [ 5.000,  7.500) = 3372 
    [ 7.500, 10.000) = 264 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.142 ms/op
     p(50.0000) =      6.578 ms/op
     p(90.0000) =     11.092 ms/op
     p(95.0000) =     16.908 ms/op
     p(99.0000) =     23.244 ms/op
     p(99.9000) =     29.983 ms/op
     p(99.9900) =     30.015 ms/op
     p(99.9990) =     30.015 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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
# Warmup Iteration   1: 7.649 ±(99.9%) 0.241 ms/op
Iteration   1: 4.288 ±(99.9%) 0.075 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   4.514 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   8.265 ms/op
                 existUser·p0.99:   12.349 ms/op
                 existUser·p0.999:  14.877 ms/op
                 existUser·p0.9999: 15.483 ms/op
                 existUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7480
  mean =      4.288 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 1462 
    [ 2.500,  3.750) = 757 
    [ 3.750,  5.000) = 3910 
    [ 5.000,  6.250) = 806 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      8.265 ms/op
     p(99.0000) =     12.349 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     15.483 ms/op
     p(99.9990) =     15.483 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 9.390 ±(99.9%) 0.366 ms/op
Iteration   1: 5.077 ±(99.9%) 0.070 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   4.907 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   6.693 ms/op
                 getUser·p0.99:   13.641 ms/op
                 getUser·p0.999:  20.437 ms/op
                 getUser·p0.9999: 21.299 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6323
  mean =      5.077 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 3670 
    [ 5.000,  7.500) = 2380 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =     13.641 ms/op
     p(99.9000) =     20.437 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 28.871 ±(99.9%) 1.066 ms/op
Iteration   1: 17.934 ±(99.9%) 0.338 ms/op
                 listUser·p0.00:   4.260 ms/op
                 listUser·p0.50:   17.236 ms/op
                 listUser·p0.90:   22.217 ms/op
                 listUser·p0.95:   25.716 ms/op
                 listUser·p0.99:   34.328 ms/op
                 listUser·p0.999:  40.147 ms/op
                 listUser·p0.9999: 47.186 ms/op
                 listUser·p1.00:   47.186 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1783
  mean =     17.934 ±(99.9%) 0.338 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5 
    [ 5.000, 10.000) = 35 
    [10.000, 15.000) = 249 
    [15.000, 20.000) = 1163 
    [20.000, 25.000) = 240 
    [25.000, 30.000) = 41 
    [30.000, 35.000) = 35 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      4.260 ms/op
     p(50.0000) =     17.236 ms/op
     p(90.0000) =     22.217 ms/op
     p(95.0000) =     25.716 ms/op
     p(99.0000) =     34.328 ms/op
     p(99.9000) =     40.147 ms/op
     p(99.9900) =     47.186 ms/op
     p(99.9990) =     47.186 ms/op
     p(99.9999) =     47.186 ms/op
    p(100.0000) =     47.186 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.037          ops/ms
Client.existUser                       thrpt         4.706          ops/ms
Client.getUser                         thrpt         4.273          ops/ms
Client.listUser                        thrpt         1.107          ops/ms
Client.createUser                       avgt         8.216           ms/op
Client.existUser                        avgt         5.329           ms/op
Client.getUser                          avgt         5.853           ms/op
Client.listUser                         avgt        16.797           ms/op
Client.createUser                     sample  4160   7.693 ± 0.183   ms/op
Client.createUser:createUser·p0.00    sample         3.142           ms/op
Client.createUser:createUser·p0.50    sample         6.578           ms/op
Client.createUser:createUser·p0.90    sample        11.092           ms/op
Client.createUser:createUser·p0.95    sample        16.908           ms/op
Client.createUser:createUser·p0.99    sample        23.244           ms/op
Client.createUser:createUser·p0.999   sample        29.983           ms/op
Client.createUser:createUser·p0.9999  sample        30.015           ms/op
Client.createUser:createUser·p1.00    sample        30.015           ms/op
Client.existUser                      sample  7480   4.288 ± 0.075   ms/op
Client.existUser:existUser·p0.00      sample         0.837           ms/op
Client.existUser:existUser·p0.50      sample         4.514           ms/op
Client.existUser:existUser·p0.90      sample         5.431           ms/op
Client.existUser:existUser·p0.95      sample         8.265           ms/op
Client.existUser:existUser·p0.99      sample        12.349           ms/op
Client.existUser:existUser·p0.999     sample        14.877           ms/op
Client.existUser:existUser·p0.9999    sample        15.483           ms/op
Client.existUser:existUser·p1.00      sample        15.483           ms/op
Client.getUser                        sample  6323   5.077 ± 0.070   ms/op
Client.getUser:getUser·p0.00          sample         0.782           ms/op
Client.getUser:getUser·p0.50          sample         4.907           ms/op
Client.getUser:getUser·p0.90          sample         5.882           ms/op
Client.getUser:getUser·p0.95          sample         6.693           ms/op
Client.getUser:getUser·p0.99          sample        13.641           ms/op
Client.getUser:getUser·p0.999         sample        20.437           ms/op
Client.getUser:getUser·p0.9999        sample        21.299           ms/op
Client.getUser:getUser·p1.00          sample        21.299           ms/op
Client.listUser                       sample  1783  17.934 ± 0.338   ms/op
Client.listUser:listUser·p0.00        sample         4.260           ms/op
Client.listUser:listUser·p0.50        sample        17.236           ms/op
Client.listUser:listUser·p0.90        sample        22.217           ms/op
Client.listUser:listUser·p0.95        sample        25.716           ms/op
Client.listUser:listUser·p0.99        sample        34.328           ms/op
Client.listUser:listUser·p0.999       sample        40.147           ms/op
Client.listUser:listUser·p0.9999      sample        47.186           ms/op
Client.listUser:listUser·p1.00        sample        47.186           ms/op
