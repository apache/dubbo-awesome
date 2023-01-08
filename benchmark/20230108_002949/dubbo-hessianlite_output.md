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
# Warmup Iteration   1: 1.037 ops/ms
Iteration   1: 2.520 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.520 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 2.649 ops/ms
Iteration   1: 7.402 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.402 ops/ms


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
# Warmup Iteration   1: 2.458 ops/ms
Iteration   1: 3.925 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.925 ops/ms


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
# Warmup Iteration   1: 0.953 ops/ms
Iteration   1: 1.259 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.259 ops/ms


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
# Warmup Iteration   1: 18.138 ±(99.9%) 0.283 ms/op
Iteration   1: 6.172 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.172 ms/op


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
# Warmup Iteration   1: 5.660 ±(99.9%) 0.056 ms/op
Iteration   1: 4.017 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.017 ms/op


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
# Warmup Iteration   1: 7.314 ±(99.9%) 0.105 ms/op
Iteration   1: 4.860 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.860 ms/op


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
# Warmup Iteration   1: 31.688 ±(99.9%) 0.455 ms/op
Iteration   1: 20.009 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  20.009 ms/op


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
# Warmup Iteration   1: 9.744 ±(99.9%) 0.264 ms/op
Iteration   1: 6.174 ±(99.9%) 0.101 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   6.349 ms/op
                 createUser·p0.90:   7.458 ms/op
                 createUser·p0.95:   10.568 ms/op
                 createUser·p0.99:   13.817 ms/op
                 createUser·p0.999:  18.071 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5167
  mean =      6.174 ±(99.9%) 0.101 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181 
    [ 2.500,  5.000) = 957 
    [ 5.000,  7.500) = 3518 
    [ 7.500, 10.000) = 242 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      6.349 ms/op
     p(90.0000) =      7.458 ms/op
     p(95.0000) =     10.568 ms/op
     p(99.0000) =     13.817 ms/op
     p(99.9000) =     18.071 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 5.978 ±(99.9%) 0.170 ms/op
Iteration   1: 3.575 ±(99.9%) 0.067 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   7.015 ms/op
                 existUser·p0.99:   11.545 ms/op
                 existUser·p0.999:  17.628 ms/op
                 existUser·p0.9999: 17.891 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9033
  mean =      3.575 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 2381 
    [ 2.500,  3.750) = 3734 
    [ 3.750,  5.000) = 2102 
    [ 5.000,  6.250) = 231 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      7.015 ms/op
     p(99.0000) =     11.545 ms/op
     p(99.9000) =     17.628 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 9.188 ±(99.9%) 0.253 ms/op
Iteration   1: 4.249 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   5.018 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   9.907 ms/op
                 getUser·p0.999:  15.507 ms/op
                 getUser·p0.9999: 15.696 ms/op
                 getUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7533
  mean =      4.249 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 65 
    [ 2.500,  3.750) = 2079 
    [ 3.750,  5.000) = 4585 
    [ 5.000,  6.250) = 586 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.018 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      9.907 ms/op
     p(99.9000) =     15.507 ms/op
     p(99.9900) =     15.696 ms/op
     p(99.9990) =     15.696 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 30.088 ±(99.9%) 0.856 ms/op
Iteration   1: 18.176 ±(99.9%) 0.389 ms/op
                 listUser·p0.00:   5.177 ms/op
                 listUser·p0.50:   18.022 ms/op
                 listUser·p0.90:   23.757 ms/op
                 listUser·p0.95:   25.068 ms/op
                 listUser·p0.99:   34.940 ms/op
                 listUser·p0.999:  39.178 ms/op
                 listUser·p0.9999: 41.026 ms/op
                 listUser·p1.00:   41.026 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1761
  mean =     18.176 ±(99.9%) 0.389 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 53 
    [10.000, 15.000) = 635 
    [15.000, 20.000) = 329 
    [20.000, 25.000) = 642 
    [25.000, 30.000) = 76 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      5.177 ms/op
     p(50.0000) =     18.022 ms/op
     p(90.0000) =     23.757 ms/op
     p(95.0000) =     25.068 ms/op
     p(99.0000) =     34.940 ms/op
     p(99.9000) =     39.178 ms/op
     p(99.9900) =     41.026 ms/op
     p(99.9990) =     41.026 ms/op
     p(99.9999) =     41.026 ms/op
    p(100.0000) =     41.026 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.520          ops/ms
Client.existUser                       thrpt         7.402          ops/ms
Client.getUser                         thrpt         3.925          ops/ms
Client.listUser                        thrpt         1.259          ops/ms
Client.createUser                       avgt         6.172           ms/op
Client.existUser                        avgt         4.017           ms/op
Client.getUser                          avgt         4.860           ms/op
Client.listUser                         avgt        20.009           ms/op
Client.createUser                     sample  5167   6.174 ± 0.101   ms/op
Client.createUser:createUser·p0.00    sample         1.651           ms/op
Client.createUser:createUser·p0.50    sample         6.349           ms/op
Client.createUser:createUser·p0.90    sample         7.458           ms/op
Client.createUser:createUser·p0.95    sample        10.568           ms/op
Client.createUser:createUser·p0.99    sample        13.817           ms/op
Client.createUser:createUser·p0.999   sample        18.071           ms/op
Client.createUser:createUser·p0.9999  sample        24.838           ms/op
Client.createUser:createUser·p1.00    sample        24.838           ms/op
Client.existUser                      sample  9033   3.575 ± 0.067   ms/op
Client.existUser:existUser·p0.00      sample         0.664           ms/op
Client.existUser:existUser·p0.50      sample         3.154           ms/op
Client.existUser:existUser·p0.90      sample         4.432           ms/op
Client.existUser:existUser·p0.95      sample         7.015           ms/op
Client.existUser:existUser·p0.99      sample        11.545           ms/op
Client.existUser:existUser·p0.999     sample        17.628           ms/op
Client.existUser:existUser·p0.9999    sample        17.891           ms/op
Client.existUser:existUser·p1.00      sample        17.891           ms/op
Client.getUser                        sample  7533   4.249 ± 0.044   ms/op
Client.getUser:getUser·p0.00          sample         0.899           ms/op
Client.getUser:getUser·p0.50          sample         4.026           ms/op
Client.getUser:getUser·p0.90          sample         5.018           ms/op
Client.getUser:getUser·p0.95          sample         5.497           ms/op
Client.getUser:getUser·p0.99          sample         9.907           ms/op
Client.getUser:getUser·p0.999         sample        15.507           ms/op
Client.getUser:getUser·p0.9999        sample        15.696           ms/op
Client.getUser:getUser·p1.00          sample        15.696           ms/op
Client.listUser                       sample  1761  18.176 ± 0.389   ms/op
Client.listUser:listUser·p0.00        sample         5.177           ms/op
Client.listUser:listUser·p0.50        sample        18.022           ms/op
Client.listUser:listUser·p0.90        sample        23.757           ms/op
Client.listUser:listUser·p0.95        sample        25.068           ms/op
Client.listUser:listUser·p0.99        sample        34.940           ms/op
Client.listUser:listUser·p0.999       sample        39.178           ms/op
Client.listUser:listUser·p0.9999      sample        41.026           ms/op
Client.listUser:listUser·p1.00        sample        41.026           ms/op
