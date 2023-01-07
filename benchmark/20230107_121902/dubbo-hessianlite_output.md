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
# Warmup Iteration   1: 1.023 ops/ms
Iteration   1: 2.222 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.222 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.858 ops/ms
Iteration   1: 5.711 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.711 ops/ms


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
# Warmup Iteration   1: 2.169 ops/ms
Iteration   1: 3.967 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.967 ops/ms


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
# Warmup Iteration   1: 0.855 ops/ms
Iteration   1: 1.372 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.372 ops/ms


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
# Warmup Iteration   1: 16.183 ±(99.9%) 0.226 ms/op
Iteration   1: 8.893 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.893 ms/op


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
# Warmup Iteration   1: 8.910 ±(99.9%) 0.110 ms/op
Iteration   1: 4.527 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.527 ms/op


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
# Warmup Iteration   1: 14.232 ±(99.9%) 0.141 ms/op
Iteration   1: 5.752 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.752 ms/op


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
# Warmup Iteration   1: 30.749 ±(99.9%) 0.878 ms/op
Iteration   1: 18.379 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.379 ms/op


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
# Warmup Iteration   1: 12.905 ±(99.9%) 0.405 ms/op
Iteration   1: 7.761 ±(99.9%) 0.130 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   7.873 ms/op
                 createUser·p0.90:   8.962 ms/op
                 createUser·p0.95:   10.764 ms/op
                 createUser·p0.99:   15.296 ms/op
                 createUser·p0.999:  26.462 ms/op
                 createUser·p0.9999: 26.640 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4145
  mean =      7.761 ±(99.9%) 0.130 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 488 
    [ 5.000,  7.500) = 921 
    [ 7.500, 10.000) = 2441 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      7.873 ms/op
     p(90.0000) =      8.962 ms/op
     p(95.0000) =     10.764 ms/op
     p(99.0000) =     15.296 ms/op
     p(99.9000) =     26.462 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 6.603 ±(99.9%) 0.253 ms/op
Iteration   1: 3.990 ±(99.9%) 0.068 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   6.743 ms/op
                 existUser·p0.99:   12.075 ms/op
                 existUser·p0.999:  16.433 ms/op
                 existUser·p0.9999: 16.482 ms/op
                 existUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8016
  mean =      3.990 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 1602 
    [ 2.500,  3.750) = 2334 
    [ 3.750,  5.000) = 3303 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 124 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      6.743 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     16.433 ms/op
     p(99.9900) =     16.482 ms/op
     p(99.9990) =     16.482 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 9.032 ±(99.9%) 0.313 ms/op
Iteration   1: 5.011 ±(99.9%) 0.063 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   5.743 ms/op
                 getUser·p0.95:   6.472 ms/op
                 getUser·p0.99:   12.959 ms/op
                 getUser·p0.999:  18.730 ms/op
                 getUser·p0.9999: 19.661 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6393
  mean =      5.011 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 55 
    [ 2.500,  3.750) = 500 
    [ 3.750,  5.000) = 3490 
    [ 5.000,  6.250) = 1968 
    [ 6.250,  7.500) = 193 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.472 ms/op
     p(99.0000) =     12.959 ms/op
     p(99.9000) =     18.730 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 28.766 ±(99.9%) 0.888 ms/op
Iteration   1: 20.410 ±(99.9%) 0.354 ms/op
                 listUser·p0.00:   12.141 ms/op
                 listUser·p0.50:   21.234 ms/op
                 listUser·p0.90:   24.150 ms/op
                 listUser·p0.95:   25.362 ms/op
                 listUser·p0.99:   40.070 ms/op
                 listUser·p0.999:  41.922 ms/op
                 listUser·p0.9999: 42.074 ms/op
                 listUser·p1.00:   42.074 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1581
  mean =     20.410 ±(99.9%) 0.354 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 493 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 507 
    [22.500, 25.000) = 330 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 
    [37.500, 40.000) = 9 
    [40.000, 42.500) = 15 
    [42.500, 45.000) = 0 
    [45.000, 47.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =     12.141 ms/op
     p(50.0000) =     21.234 ms/op
     p(90.0000) =     24.150 ms/op
     p(95.0000) =     25.362 ms/op
     p(99.0000) =     40.070 ms/op
     p(99.9000) =     41.922 ms/op
     p(99.9900) =     42.074 ms/op
     p(99.9990) =     42.074 ms/op
     p(99.9999) =     42.074 ms/op
    p(100.0000) =     42.074 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.222          ops/ms
Client.existUser                       thrpt         5.711          ops/ms
Client.getUser                         thrpt         3.967          ops/ms
Client.listUser                        thrpt         1.372          ops/ms
Client.createUser                       avgt         8.893           ms/op
Client.existUser                        avgt         4.527           ms/op
Client.getUser                          avgt         5.752           ms/op
Client.listUser                         avgt        18.379           ms/op
Client.createUser                     sample  4145   7.761 ± 0.130   ms/op
Client.createUser:createUser·p0.00    sample         1.458           ms/op
Client.createUser:createUser·p0.50    sample         7.873           ms/op
Client.createUser:createUser·p0.90    sample         8.962           ms/op
Client.createUser:createUser·p0.95    sample        10.764           ms/op
Client.createUser:createUser·p0.99    sample        15.296           ms/op
Client.createUser:createUser·p0.999   sample        26.462           ms/op
Client.createUser:createUser·p0.9999  sample        26.640           ms/op
Client.createUser:createUser·p1.00    sample        26.640           ms/op
Client.existUser                      sample  8016   3.990 ± 0.068   ms/op
Client.existUser:existUser·p0.00      sample         1.006           ms/op
Client.existUser:existUser·p0.50      sample         3.797           ms/op
Client.existUser:existUser·p0.90      sample         4.964           ms/op
Client.existUser:existUser·p0.95      sample         6.743           ms/op
Client.existUser:existUser·p0.99      sample        12.075           ms/op
Client.existUser:existUser·p0.999     sample        16.433           ms/op
Client.existUser:existUser·p0.9999    sample        16.482           ms/op
Client.existUser:existUser·p1.00      sample        16.482           ms/op
Client.getUser                        sample  6393   5.011 ± 0.063   ms/op
Client.getUser:getUser·p0.00          sample         1.327           ms/op
Client.getUser:getUser·p0.50          sample         4.899           ms/op
Client.getUser:getUser·p0.90          sample         5.743           ms/op
Client.getUser:getUser·p0.95          sample         6.472           ms/op
Client.getUser:getUser·p0.99          sample        12.959           ms/op
Client.getUser:getUser·p0.999         sample        18.730           ms/op
Client.getUser:getUser·p0.9999        sample        19.661           ms/op
Client.getUser:getUser·p1.00          sample        19.661           ms/op
Client.listUser                       sample  1581  20.410 ± 0.354   ms/op
Client.listUser:listUser·p0.00        sample        12.141           ms/op
Client.listUser:listUser·p0.50        sample        21.234           ms/op
Client.listUser:listUser·p0.90        sample        24.150           ms/op
Client.listUser:listUser·p0.95        sample        25.362           ms/op
Client.listUser:listUser·p0.99        sample        40.070           ms/op
Client.listUser:listUser·p0.999       sample        41.922           ms/op
Client.listUser:listUser·p0.9999      sample        42.074           ms/op
Client.listUser:listUser·p1.00        sample        42.074           ms/op
