# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.079 ops/ms
Iteration   1: 2.585 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.585 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.583 ops/ms
Iteration   1: 6.251 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.251 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.527 ops/ms
Iteration   1: 4.442 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.442 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.861 ops/ms
Iteration   1: 1.251 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.251 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 17.536 ±(99.9%) 0.233 ms/op
Iteration   1: 8.365 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.365 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.079 ±(99.9%) 0.074 ms/op
Iteration   1: 4.127 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.127 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.526 ±(99.9%) 0.162 ms/op
Iteration   1: 5.712 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.712 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 33.463 ±(99.9%) 0.759 ms/op
Iteration   1: 18.287 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.088 ±(99.9%) 0.413 ms/op
Iteration   1: 6.880 ±(99.9%) 0.143 ms/op
                 createUser·p0.00:   2.630 ms/op
                 createUser·p0.50:   5.767 ms/op
                 createUser·p0.90:   10.142 ms/op
                 createUser·p0.95:   14.516 ms/op
                 createUser·p0.99:   15.417 ms/op
                 createUser·p0.999:  26.280 ms/op
                 createUser·p0.9999: 30.245 ms/op
                 createUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4651
  mean =      6.880 ±(99.9%) 0.143 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 140 
    [ 5.000,  7.500) = 3707 
    [ 7.500, 10.000) = 328 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.630 ms/op
     p(50.0000) =      5.767 ms/op
     p(90.0000) =     10.142 ms/op
     p(95.0000) =     14.516 ms/op
     p(99.0000) =     15.417 ms/op
     p(99.9000) =     26.280 ms/op
     p(99.9900) =     30.245 ms/op
     p(99.9990) =     30.245 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.836 ±(99.9%) 0.176 ms/op
Iteration   1: 4.124 ±(99.9%) 0.097 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.719 ms/op
                 existUser·p0.99:   12.520 ms/op
                 existUser·p0.999:  37.886 ms/op
                 existUser·p0.9999: 38.076 ms/op
                 existUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7897
  mean =      4.124 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 127 
    [ 2.500,  5.000) = 7024 
    [ 5.000,  7.500) = 511 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.719 ms/op
     p(99.0000) =     12.520 ms/op
     p(99.9000) =     37.886 ms/op
     p(99.9900) =     38.076 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.841 ±(99.9%) 0.345 ms/op
Iteration   1: 4.822 ±(99.9%) 0.074 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   17.470 ms/op
                 getUser·p0.999:  21.667 ms/op
                 getUser·p0.9999: 22.020 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6761
  mean =      4.822 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 5312 
    [ 5.000,  7.500) = 1219 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.201 ms/op
     p(99.0000) =     17.470 ms/op
     p(99.9000) =     21.667 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 26.639 ±(99.9%) 0.785 ms/op
Iteration   1: 19.976 ±(99.9%) 0.280 ms/op
                 listUser·p0.00:   8.520 ms/op
                 listUser·p0.50:   20.677 ms/op
                 listUser·p0.90:   22.938 ms/op
                 listUser·p0.95:   24.576 ms/op
                 listUser·p0.99:   28.541 ms/op
                 listUser·p0.999:  39.880 ms/op
                 listUser·p0.9999: 40.960 ms/op
                 listUser·p1.00:   40.960 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1633
  mean =     19.976 ±(99.9%) 0.280 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 3 
    [10.000, 15.000) = 161 
    [15.000, 20.000) = 397 
    [20.000, 25.000) = 1000 
    [25.000, 30.000) = 58 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      8.520 ms/op
     p(50.0000) =     20.677 ms/op
     p(90.0000) =     22.938 ms/op
     p(95.0000) =     24.576 ms/op
     p(99.0000) =     28.541 ms/op
     p(99.9000) =     39.880 ms/op
     p(99.9900) =     40.960 ms/op
     p(99.9990) =     40.960 ms/op
     p(99.9999) =     40.960 ms/op
    p(100.0000) =     40.960 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.585          ops/ms
Client.existUser                       thrpt         6.251          ops/ms
Client.getUser                         thrpt         4.442          ops/ms
Client.listUser                        thrpt         1.251          ops/ms
Client.createUser                       avgt         8.365           ms/op
Client.existUser                        avgt         4.127           ms/op
Client.getUser                          avgt         5.712           ms/op
Client.listUser                         avgt        18.287           ms/op
Client.createUser                     sample  4651   6.880 ± 0.143   ms/op
Client.createUser:createUser·p0.00    sample         2.630           ms/op
Client.createUser:createUser·p0.50    sample         5.767           ms/op
Client.createUser:createUser·p0.90    sample        10.142           ms/op
Client.createUser:createUser·p0.95    sample        14.516           ms/op
Client.createUser:createUser·p0.99    sample        15.417           ms/op
Client.createUser:createUser·p0.999   sample        26.280           ms/op
Client.createUser:createUser·p0.9999  sample        30.245           ms/op
Client.createUser:createUser·p1.00    sample        30.245           ms/op
Client.existUser                      sample  7897   4.124 ± 0.097   ms/op
Client.existUser:existUser·p0.00      sample         1.116           ms/op
Client.existUser:existUser·p0.50      sample         3.973           ms/op
Client.existUser:existUser·p0.90      sample         4.940           ms/op
Client.existUser:existUser·p0.95      sample         5.719           ms/op
Client.existUser:existUser·p0.99      sample        12.520           ms/op
Client.existUser:existUser·p0.999     sample        37.886           ms/op
Client.existUser:existUser·p0.9999    sample        38.076           ms/op
Client.existUser:existUser·p1.00      sample        38.076           ms/op
Client.getUser                        sample  6761   4.822 ± 0.074   ms/op
Client.getUser:getUser·p0.00          sample         1.569           ms/op
Client.getUser:getUser·p0.50          sample         4.522           ms/op
Client.getUser:getUser·p0.90          sample         5.464           ms/op
Client.getUser:getUser·p0.95          sample         6.201           ms/op
Client.getUser:getUser·p0.99          sample        17.470           ms/op
Client.getUser:getUser·p0.999         sample        21.667           ms/op
Client.getUser:getUser·p0.9999        sample        22.020           ms/op
Client.getUser:getUser·p1.00          sample        22.020           ms/op
Client.listUser                       sample  1633  19.976 ± 0.280   ms/op
Client.listUser:listUser·p0.00        sample         8.520           ms/op
Client.listUser:listUser·p0.50        sample        20.677           ms/op
Client.listUser:listUser·p0.90        sample        22.938           ms/op
Client.listUser:listUser·p0.95        sample        24.576           ms/op
Client.listUser:listUser·p0.99        sample        28.541           ms/op
Client.listUser:listUser·p0.999       sample        39.880           ms/op
Client.listUser:listUser·p0.9999      sample        40.960           ms/op
Client.listUser:listUser·p1.00        sample        40.960           ms/op
