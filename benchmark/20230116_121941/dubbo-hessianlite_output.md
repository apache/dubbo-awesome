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
# Warmup Iteration   1: 1.099 ops/ms
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
# Warmup Iteration   1: 2.555 ops/ms
Iteration   1: 6.332 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.332 ops/ms


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
# Warmup Iteration   1: 1.564 ops/ms
Iteration   1: 4.085 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.085 ops/ms


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
# Warmup Iteration   1: 0.822 ops/ms
Iteration   1: 1.353 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.353 ops/ms


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
# Warmup Iteration   1: 17.387 ±(99.9%) 0.383 ms/op
Iteration   1: 8.322 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.322 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.414 ±(99.9%) 0.080 ms/op
Iteration   1: 4.611 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.611 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.984 ±(99.9%) 0.153 ms/op
Iteration   1: 5.118 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.118 ms/op


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
# Warmup Iteration   1: 28.662 ±(99.9%) 0.510 ms/op
Iteration   1: 16.030 ±(99.9%) 0.118 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.030 ms/op


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
# Warmup Iteration   1: 12.051 ±(99.9%) 0.464 ms/op
Iteration   1: 7.043 ±(99.9%) 0.172 ms/op
                 createUser·p0.00:   2.376 ms/op
                 createUser·p0.50:   6.300 ms/op
                 createUser·p0.90:   8.192 ms/op
                 createUser·p0.95:   12.255 ms/op
                 createUser·p0.99:   17.105 ms/op
                 createUser·p0.999:  42.074 ms/op
                 createUser·p0.9999: 42.140 ms/op
                 createUser·p1.00:   42.140 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4552
  mean =      7.043 ±(99.9%) 0.172 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 72 
    [ 5.000, 10.000) = 4189 
    [10.000, 15.000) = 195 
    [15.000, 20.000) = 64 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      2.376 ms/op
     p(50.0000) =      6.300 ms/op
     p(90.0000) =      8.192 ms/op
     p(95.0000) =     12.255 ms/op
     p(99.0000) =     17.105 ms/op
     p(99.9000) =     42.074 ms/op
     p(99.9900) =     42.140 ms/op
     p(99.9990) =     42.140 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


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
# Warmup Iteration   1: 6.820 ±(99.9%) 0.211 ms/op
Iteration   1: 4.043 ±(99.9%) 0.075 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   3.824 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   7.012 ms/op
                 existUser·p0.99:   12.386 ms/op
                 existUser·p0.999:  19.890 ms/op
                 existUser·p0.9999: 20.316 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7986
  mean =      4.043 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 410 
    [ 2.500,  5.000) = 6826 
    [ 5.000,  7.500) = 398 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      3.824 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      7.012 ms/op
     p(99.0000) =     12.386 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     20.316 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 11.324 ±(99.9%) 0.365 ms/op
Iteration   1: 4.451 ±(99.9%) 0.047 ms/op
                 getUser·p0.00:   1.841 ms/op
                 getUser·p0.50:   4.145 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   9.978 ms/op
                 getUser·p0.999:  13.828 ms/op
                 getUser·p0.9999: 13.861 ms/op
                 getUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7261
  mean =      4.451 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 8 
    [ 2.500,  3.750) = 1999 
    [ 3.750,  5.000) = 3411 
    [ 5.000,  6.250) = 1538 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.841 ms/op
     p(50.0000) =      4.145 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 24.264 ±(99.9%) 0.735 ms/op
Iteration   1: 17.687 ±(99.9%) 0.278 ms/op
                 listUser·p0.00:   8.651 ms/op
                 listUser·p0.50:   18.448 ms/op
                 listUser·p0.90:   21.365 ms/op
                 listUser·p0.95:   21.814 ms/op
                 listUser·p0.99:   29.557 ms/op
                 listUser·p0.999:  38.874 ms/op
                 listUser·p0.9999: 39.584 ms/op
                 listUser·p1.00:   39.584 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1832
  mean =     17.687 ±(99.9%) 0.278 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 453 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 625 
    [20.000, 22.500) = 406 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      8.651 ms/op
     p(50.0000) =     18.448 ms/op
     p(90.0000) =     21.365 ms/op
     p(95.0000) =     21.814 ms/op
     p(99.0000) =     29.557 ms/op
     p(99.9000) =     38.874 ms/op
     p(99.9900) =     39.584 ms/op
     p(99.9990) =     39.584 ms/op
     p(99.9999) =     39.584 ms/op
    p(100.0000) =     39.584 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.410          ops/ms
Client.existUser                       thrpt         6.332          ops/ms
Client.getUser                         thrpt         4.085          ops/ms
Client.listUser                        thrpt         1.353          ops/ms
Client.createUser                       avgt         8.322           ms/op
Client.existUser                        avgt         4.611           ms/op
Client.getUser                          avgt         5.118           ms/op
Client.listUser                         avgt        16.030           ms/op
Client.createUser                     sample  4552   7.043 ± 0.172   ms/op
Client.createUser:createUser·p0.00    sample         2.376           ms/op
Client.createUser:createUser·p0.50    sample         6.300           ms/op
Client.createUser:createUser·p0.90    sample         8.192           ms/op
Client.createUser:createUser·p0.95    sample        12.255           ms/op
Client.createUser:createUser·p0.99    sample        17.105           ms/op
Client.createUser:createUser·p0.999   sample        42.074           ms/op
Client.createUser:createUser·p0.9999  sample        42.140           ms/op
Client.createUser:createUser·p1.00    sample        42.140           ms/op
Client.existUser                      sample  7986   4.043 ± 0.075   ms/op
Client.existUser:existUser·p0.00      sample         0.630           ms/op
Client.existUser:existUser·p0.50      sample         3.824           ms/op
Client.existUser:existUser·p0.90      sample         4.923           ms/op
Client.existUser:existUser·p0.95      sample         7.012           ms/op
Client.existUser:existUser·p0.99      sample        12.386           ms/op
Client.existUser:existUser·p0.999     sample        19.890           ms/op
Client.existUser:existUser·p0.9999    sample        20.316           ms/op
Client.existUser:existUser·p1.00      sample        20.316           ms/op
Client.getUser                        sample  7261   4.451 ± 0.047   ms/op
Client.getUser:getUser·p0.00          sample         1.841           ms/op
Client.getUser:getUser·p0.50          sample         4.145           ms/op
Client.getUser:getUser·p0.90          sample         5.538           ms/op
Client.getUser:getUser·p0.95          sample         5.874           ms/op
Client.getUser:getUser·p0.99          sample         9.978           ms/op
Client.getUser:getUser·p0.999         sample        13.828           ms/op
Client.getUser:getUser·p0.9999        sample        13.861           ms/op
Client.getUser:getUser·p1.00          sample        13.861           ms/op
Client.listUser                       sample  1832  17.687 ± 0.278   ms/op
Client.listUser:listUser·p0.00        sample         8.651           ms/op
Client.listUser:listUser·p0.50        sample        18.448           ms/op
Client.listUser:listUser·p0.90        sample        21.365           ms/op
Client.listUser:listUser·p0.95        sample        21.814           ms/op
Client.listUser:listUser·p0.99        sample        29.557           ms/op
Client.listUser:listUser·p0.999       sample        38.874           ms/op
Client.listUser:listUser·p0.9999      sample        39.584           ms/op
Client.listUser:listUser·p1.00        sample        39.584           ms/op
