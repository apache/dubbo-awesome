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
# Warmup Iteration   1: 1.232 ops/ms
Iteration   1: 2.853 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.853 ops/ms


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
# Warmup Iteration   1: 2.930 ops/ms
Iteration   1: 6.372 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.372 ops/ms


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
# Warmup Iteration   1: 1.658 ops/ms
Iteration   1: 4.737 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.737 ops/ms


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
# Warmup Iteration   1: 0.835 ops/ms
Iteration   1: 1.605 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.605 ops/ms


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
# Warmup Iteration   1: 15.860 ±(99.9%) 0.290 ms/op
Iteration   1: 6.472 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.472 ms/op


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
# Warmup Iteration   1: 7.808 ±(99.9%) 0.076 ms/op
Iteration   1: 3.862 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.862 ms/op


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
# Warmup Iteration   1: 9.198 ±(99.9%) 0.157 ms/op
Iteration   1: 4.595 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.595 ms/op


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
# Warmup Iteration   1: 31.399 ±(99.9%) 0.595 ms/op
Iteration   1: 17.483 ±(99.9%) 0.113 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.483 ms/op


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
# Warmup Iteration   1: 13.095 ±(99.9%) 0.527 ms/op
Iteration   1: 6.118 ±(99.9%) 0.093 ms/op
                 createUser·p0.00:   2.142 ms/op
                 createUser·p0.50:   5.972 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   8.831 ms/op
                 createUser·p0.99:   15.892 ms/op
                 createUser·p0.999:  20.201 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5249
  mean =      6.118 ±(99.9%) 0.093 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 455 
    [ 5.000,  7.500) = 4449 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.142 ms/op
     p(50.0000) =      5.972 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     15.892 ms/op
     p(99.9000) =     20.201 ms/op
     p(99.9900) =     20.251 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 6.468 ±(99.9%) 0.174 ms/op
Iteration   1: 3.576 ±(99.9%) 0.066 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   3.931 ms/op
                 existUser·p0.95:   4.259 ms/op
                 existUser·p0.99:   10.600 ms/op
                 existUser·p0.999:  28.510 ms/op
                 existUser·p0.9999: 28.901 ms/op
                 existUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8942
  mean =      3.576 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1406 
    [ 2.500,  5.000) = 7248 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      3.931 ms/op
     p(95.0000) =      4.259 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     28.510 ms/op
     p(99.9900) =     28.901 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 11.208 ±(99.9%) 0.402 ms/op
Iteration   1: 4.341 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   1.667 ms/op
                 getUser·p0.50:   4.174 ms/op
                 getUser·p0.90:   5.063 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   6.164 ms/op
                 getUser·p0.999:  14.565 ms/op
                 getUser·p0.9999: 14.713 ms/op
                 getUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7519
  mean =      4.341 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 10 
    [ 2.500,  3.750) = 876 
    [ 3.750,  5.000) = 5752 
    [ 5.000,  6.250) = 809 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.164 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     14.713 ms/op
     p(99.9990) =     14.713 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 25.952 ±(99.9%) 0.730 ms/op
Iteration   1: 17.496 ±(99.9%) 0.284 ms/op
                 listUser·p0.00:   8.389 ms/op
                 listUser·p0.50:   16.941 ms/op
                 listUser·p0.90:   20.883 ms/op
                 listUser·p0.95:   24.510 ms/op
                 listUser·p0.99:   33.693 ms/op
                 listUser·p0.999:  39.013 ms/op
                 listUser·p0.9999: 39.846 ms/op
                 listUser·p1.00:   39.846 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1846
  mean =     17.496 ±(99.9%) 0.284 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 820 
    [17.500, 20.000) = 586 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      8.389 ms/op
     p(50.0000) =     16.941 ms/op
     p(90.0000) =     20.883 ms/op
     p(95.0000) =     24.510 ms/op
     p(99.0000) =     33.693 ms/op
     p(99.9000) =     39.013 ms/op
     p(99.9900) =     39.846 ms/op
     p(99.9990) =     39.846 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.853          ops/ms
Client.existUser                       thrpt         6.372          ops/ms
Client.getUser                         thrpt         4.737          ops/ms
Client.listUser                        thrpt         1.605          ops/ms
Client.createUser                       avgt         6.472           ms/op
Client.existUser                        avgt         3.862           ms/op
Client.getUser                          avgt         4.595           ms/op
Client.listUser                         avgt        17.483           ms/op
Client.createUser                     sample  5249   6.118 ± 0.093   ms/op
Client.createUser:createUser·p0.00    sample         2.142           ms/op
Client.createUser:createUser·p0.50    sample         5.972           ms/op
Client.createUser:createUser·p0.90    sample         6.537           ms/op
Client.createUser:createUser·p0.95    sample         8.831           ms/op
Client.createUser:createUser·p0.99    sample        15.892           ms/op
Client.createUser:createUser·p0.999   sample        20.201           ms/op
Client.createUser:createUser·p0.9999  sample        20.251           ms/op
Client.createUser:createUser·p1.00    sample        20.251           ms/op
Client.existUser                      sample  8942   3.576 ± 0.066   ms/op
Client.existUser:existUser·p0.00      sample         0.742           ms/op
Client.existUser:existUser·p0.50      sample         3.613           ms/op
Client.existUser:existUser·p0.90      sample         3.931           ms/op
Client.existUser:existUser·p0.95      sample         4.259           ms/op
Client.existUser:existUser·p0.99      sample        10.600           ms/op
Client.existUser:existUser·p0.999     sample        28.510           ms/op
Client.existUser:existUser·p0.9999    sample        28.901           ms/op
Client.existUser:existUser·p1.00      sample        28.901           ms/op
Client.getUser                        sample  7519   4.341 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample         1.667           ms/op
Client.getUser:getUser·p0.50          sample         4.174           ms/op
Client.getUser:getUser·p0.90          sample         5.063           ms/op
Client.getUser:getUser·p0.95          sample         5.325           ms/op
Client.getUser:getUser·p0.99          sample         6.164           ms/op
Client.getUser:getUser·p0.999         sample        14.565           ms/op
Client.getUser:getUser·p0.9999        sample        14.713           ms/op
Client.getUser:getUser·p1.00          sample        14.713           ms/op
Client.listUser                       sample  1846  17.496 ± 0.284   ms/op
Client.listUser:listUser·p0.00        sample         8.389           ms/op
Client.listUser:listUser·p0.50        sample        16.941           ms/op
Client.listUser:listUser·p0.90        sample        20.883           ms/op
Client.listUser:listUser·p0.95        sample        24.510           ms/op
Client.listUser:listUser·p0.99        sample        33.693           ms/op
Client.listUser:listUser·p0.999       sample        39.013           ms/op
Client.listUser:listUser·p0.9999      sample        39.846           ms/op
Client.listUser:listUser·p1.00        sample        39.846           ms/op
