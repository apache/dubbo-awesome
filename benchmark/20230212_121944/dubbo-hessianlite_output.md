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
# Warmup Iteration   1: 1.073 ops/ms
Iteration   1: 2.599 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.599 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.332 ops/ms
Iteration   1: 7.003 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.003 ops/ms


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
# Warmup Iteration   1: 2.182 ops/ms
Iteration   1: 4.721 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.721 ops/ms


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
# Warmup Iteration   1: 0.813 ops/ms
Iteration   1: 1.430 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.430 ops/ms


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
# Warmup Iteration   1: 19.940 ±(99.9%) 0.300 ms/op
Iteration   1: 9.925 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.925 ms/op


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
# Warmup Iteration   1: 8.001 ±(99.9%) 0.117 ms/op
Iteration   1: 5.054 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.054 ms/op


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
# Warmup Iteration   1: 9.254 ±(99.9%) 0.178 ms/op
Iteration   1: 5.755 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.755 ms/op


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
# Warmup Iteration   1: 27.521 ±(99.9%) 0.543 ms/op
Iteration   1: 15.040 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.040 ms/op


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
# Warmup Iteration   1: 12.862 ±(99.9%) 0.472 ms/op
Iteration   1: 8.557 ±(99.9%) 0.118 ms/op
                 createUser·p0.00:   2.286 ms/op
                 createUser·p0.50:   8.372 ms/op
                 createUser·p0.90:   9.028 ms/op
                 createUser·p0.95:   9.535 ms/op
                 createUser·p0.99:   20.316 ms/op
                 createUser·p0.999:  25.992 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3782
  mean =      8.557 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 45 
    [ 5.000,  7.500) = 190 
    [ 7.500, 10.000) = 3371 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.286 ms/op
     p(50.0000) =      8.372 ms/op
     p(90.0000) =      9.028 ms/op
     p(95.0000) =      9.535 ms/op
     p(99.0000) =     20.316 ms/op
     p(99.9000) =     25.992 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 6.681 ±(99.9%) 0.213 ms/op
Iteration   1: 3.997 ±(99.9%) 0.060 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.944 ms/op
                 existUser·p0.90:   4.781 ms/op
                 existUser·p0.95:   7.265 ms/op
                 existUser·p0.99:   10.453 ms/op
                 existUser·p0.999:  15.598 ms/op
                 existUser·p0.9999: 15.630 ms/op
                 existUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8003
  mean =      3.997 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1372 
    [ 2.500,  3.750) = 962 
    [ 3.750,  5.000) = 4965 
    [ 5.000,  6.250) = 155 
    [ 6.250,  7.500) = 219 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 128 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.781 ms/op
     p(95.0000) =      7.265 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     15.598 ms/op
     p(99.9900) =     15.630 ms/op
     p(99.9990) =     15.630 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 12.593 ±(99.9%) 0.415 ms/op
Iteration   1: 5.681 ±(99.9%) 0.116 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   7.414 ms/op
                 getUser·p0.95:   7.913 ms/op
                 getUser·p0.99:   21.809 ms/op
                 getUser·p0.999:  30.367 ms/op
                 getUser·p0.9999: 31.392 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5644
  mean =      5.681 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 2164 
    [ 5.000,  7.500) = 2923 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      7.414 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     21.809 ms/op
     p(99.9000) =     30.367 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     31.392 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 32.543 ±(99.9%) 0.882 ms/op
Iteration   1: 18.065 ±(99.9%) 0.306 ms/op
                 listUser·p0.00:   6.283 ms/op
                 listUser·p0.50:   17.596 ms/op
                 listUser·p0.90:   21.561 ms/op
                 listUser·p0.95:   24.797 ms/op
                 listUser·p0.99:   31.926 ms/op
                 listUser·p0.999:  35.489 ms/op
                 listUser·p0.9999: 36.569 ms/op
                 listUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1784
  mean =     18.065 ±(99.9%) 0.306 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 519 
    [17.500, 20.000) = 524 
    [20.000, 22.500) = 284 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      6.283 ms/op
     p(50.0000) =     17.596 ms/op
     p(90.0000) =     21.561 ms/op
     p(95.0000) =     24.797 ms/op
     p(99.0000) =     31.926 ms/op
     p(99.9000) =     35.489 ms/op
     p(99.9900) =     36.569 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.599          ops/ms
Client.existUser                       thrpt         7.003          ops/ms
Client.getUser                         thrpt         4.721          ops/ms
Client.listUser                        thrpt         1.430          ops/ms
Client.createUser                       avgt         9.925           ms/op
Client.existUser                        avgt         5.054           ms/op
Client.getUser                          avgt         5.755           ms/op
Client.listUser                         avgt        15.040           ms/op
Client.createUser                     sample  3782   8.557 ± 0.118   ms/op
Client.createUser:createUser·p0.00    sample         2.286           ms/op
Client.createUser:createUser·p0.50    sample         8.372           ms/op
Client.createUser:createUser·p0.90    sample         9.028           ms/op
Client.createUser:createUser·p0.95    sample         9.535           ms/op
Client.createUser:createUser·p0.99    sample        20.316           ms/op
Client.createUser:createUser·p0.999   sample        25.992           ms/op
Client.createUser:createUser·p0.9999  sample        26.116           ms/op
Client.createUser:createUser·p1.00    sample        26.116           ms/op
Client.existUser                      sample  8003   3.997 ± 0.060   ms/op
Client.existUser:existUser·p0.00      sample         1.098           ms/op
Client.existUser:existUser·p0.50      sample         3.944           ms/op
Client.existUser:existUser·p0.90      sample         4.781           ms/op
Client.existUser:existUser·p0.95      sample         7.265           ms/op
Client.existUser:existUser·p0.99      sample        10.453           ms/op
Client.existUser:existUser·p0.999     sample        15.598           ms/op
Client.existUser:existUser·p0.9999    sample        15.630           ms/op
Client.existUser:existUser·p1.00      sample        15.630           ms/op
Client.getUser                        sample  5644   5.681 ± 0.116   ms/op
Client.getUser:getUser·p0.00          sample         0.848           ms/op
Client.getUser:getUser·p0.50          sample         5.202           ms/op
Client.getUser:getUser·p0.90          sample         7.414           ms/op
Client.getUser:getUser·p0.95          sample         7.913           ms/op
Client.getUser:getUser·p0.99          sample        21.809           ms/op
Client.getUser:getUser·p0.999         sample        30.367           ms/op
Client.getUser:getUser·p0.9999        sample        31.392           ms/op
Client.getUser:getUser·p1.00          sample        31.392           ms/op
Client.listUser                       sample  1784  18.065 ± 0.306   ms/op
Client.listUser:listUser·p0.00        sample         6.283           ms/op
Client.listUser:listUser·p0.50        sample        17.596           ms/op
Client.listUser:listUser·p0.90        sample        21.561           ms/op
Client.listUser:listUser·p0.95        sample        24.797           ms/op
Client.listUser:listUser·p0.99        sample        31.926           ms/op
Client.listUser:listUser·p0.999       sample        35.489           ms/op
Client.listUser:listUser·p0.9999      sample        36.569           ms/op
Client.listUser:listUser·p1.00        sample        36.569           ms/op
