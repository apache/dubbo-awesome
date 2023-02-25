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
# Warmup Iteration   1: 1.159 ops/ms
Iteration   1: 2.309 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.309 ops/ms


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
# Warmup Iteration   1: 3.171 ops/ms
Iteration   1: 7.396 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.396 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.424 ops/ms
Iteration   1: 4.681 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.681 ops/ms


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
# Warmup Iteration   1: 0.867 ops/ms
Iteration   1: 1.490 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.490 ops/ms


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
# Warmup Iteration   1: 15.403 ±(99.9%) 0.134 ms/op
Iteration   1: 7.152 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.152 ms/op


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
# Warmup Iteration   1: 6.366 ±(99.9%) 0.091 ms/op
Iteration   1: 3.418 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.418 ms/op


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
# Warmup Iteration   1: 7.682 ±(99.9%) 0.133 ms/op
Iteration   1: 5.097 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.097 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 30.024 ±(99.9%) 0.860 ms/op
Iteration   1: 16.977 ±(99.9%) 0.049 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.977 ms/op


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
# Warmup Iteration   1: 10.624 ±(99.9%) 0.440 ms/op
Iteration   1: 5.581 ±(99.9%) 0.078 ms/op
                 createUser·p0.00:   2.066 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.160 ms/op
                 createUser·p0.95:   8.847 ms/op
                 createUser·p0.99:   15.126 ms/op
                 createUser·p0.999:  16.630 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5719
  mean =      5.581 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 6 
    [ 2.500,  3.750) = 168 
    [ 3.750,  5.000) = 1559 
    [ 5.000,  6.250) = 3491 
    [ 6.250,  7.500) = 188 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.066 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     15.126 ms/op
     p(99.9000) =     16.630 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 5.996 ±(99.9%) 0.162 ms/op
Iteration   1: 3.629 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   8.978 ms/op
                 existUser·p0.999:  17.045 ms/op
                 existUser·p0.9999: 17.957 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8823
  mean =      3.629 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 740 
    [ 2.500,  3.750) = 4570 
    [ 3.750,  5.000) = 3101 
    [ 5.000,  6.250) = 185 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     17.045 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 11.191 ±(99.9%) 0.299 ms/op
Iteration   1: 5.027 ±(99.9%) 0.086 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   4.678 ms/op
                 getUser·p0.90:   5.890 ms/op
                 getUser·p0.95:   6.963 ms/op
                 getUser·p0.99:   20.065 ms/op
                 getUser·p0.999:  24.623 ms/op
                 getUser·p0.9999: 25.297 ms/op
                 getUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6366
  mean =      5.027 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 4541 
    [ 5.000,  7.500) = 1518 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.963 ms/op
     p(99.0000) =     20.065 ms/op
     p(99.9000) =     24.623 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 26.958 ±(99.9%) 0.887 ms/op
Iteration   1: 18.550 ±(99.9%) 0.262 ms/op
                 listUser·p0.00:   5.988 ms/op
                 listUser·p0.50:   18.842 ms/op
                 listUser·p0.90:   21.594 ms/op
                 listUser·p0.95:   22.610 ms/op
                 listUser·p0.99:   28.836 ms/op
                 listUser·p0.999:  30.291 ms/op
                 listUser·p0.9999: 30.507 ms/op
                 listUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1730
  mean =     18.550 ±(99.9%) 0.262 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 786 
    [20.000, 22.500) = 451 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.988 ms/op
     p(50.0000) =     18.842 ms/op
     p(90.0000) =     21.594 ms/op
     p(95.0000) =     22.610 ms/op
     p(99.0000) =     28.836 ms/op
     p(99.9000) =     30.291 ms/op
     p(99.9900) =     30.507 ms/op
     p(99.9990) =     30.507 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.309          ops/ms
Client.existUser                       thrpt         7.396          ops/ms
Client.getUser                         thrpt         4.681          ops/ms
Client.listUser                        thrpt         1.490          ops/ms
Client.createUser                       avgt         7.152           ms/op
Client.existUser                        avgt         3.418           ms/op
Client.getUser                          avgt         5.097           ms/op
Client.listUser                         avgt        16.977           ms/op
Client.createUser                     sample  5719   5.581 ± 0.078   ms/op
Client.createUser:createUser·p0.00    sample         2.066           ms/op
Client.createUser:createUser·p0.50    sample         5.202           ms/op
Client.createUser:createUser·p0.90    sample         6.160           ms/op
Client.createUser:createUser·p0.95    sample         8.847           ms/op
Client.createUser:createUser·p0.99    sample        15.126           ms/op
Client.createUser:createUser·p0.999   sample        16.630           ms/op
Client.createUser:createUser·p0.9999  sample        17.990           ms/op
Client.createUser:createUser·p1.00    sample        17.990           ms/op
Client.existUser                      sample  8823   3.629 ± 0.044   ms/op
Client.existUser:existUser·p0.00      sample         0.509           ms/op
Client.existUser:existUser·p0.50      sample         3.617           ms/op
Client.existUser:existUser·p0.90      sample         4.116           ms/op
Client.existUser:existUser·p0.95      sample         4.407           ms/op
Client.existUser:existUser·p0.99      sample         8.978           ms/op
Client.existUser:existUser·p0.999     sample        17.045           ms/op
Client.existUser:existUser·p0.9999    sample        17.957           ms/op
Client.existUser:existUser·p1.00      sample        17.957           ms/op
Client.getUser                        sample  6366   5.027 ± 0.086   ms/op
Client.getUser:getUser·p0.00          sample         1.409           ms/op
Client.getUser:getUser·p0.50          sample         4.678           ms/op
Client.getUser:getUser·p0.90          sample         5.890           ms/op
Client.getUser:getUser·p0.95          sample         6.963           ms/op
Client.getUser:getUser·p0.99          sample        20.065           ms/op
Client.getUser:getUser·p0.999         sample        24.623           ms/op
Client.getUser:getUser·p0.9999        sample        25.297           ms/op
Client.getUser:getUser·p1.00          sample        25.297           ms/op
Client.listUser                       sample  1730  18.550 ± 0.262   ms/op
Client.listUser:listUser·p0.00        sample         5.988           ms/op
Client.listUser:listUser·p0.50        sample        18.842           ms/op
Client.listUser:listUser·p0.90        sample        21.594           ms/op
Client.listUser:listUser·p0.95        sample        22.610           ms/op
Client.listUser:listUser·p0.99        sample        28.836           ms/op
Client.listUser:listUser·p0.999       sample        30.291           ms/op
Client.listUser:listUser·p0.9999      sample        30.507           ms/op
Client.listUser:listUser·p1.00        sample        30.507           ms/op
