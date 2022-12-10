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
Iteration   1: 2.974 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.974 ops/ms


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
# Warmup Iteration   1: 2.605 ops/ms
Iteration   1: 5.080 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.080 ops/ms


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
# Warmup Iteration   1: 2.538 ops/ms
Iteration   1: 3.673 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.673 ops/ms


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
# Warmup Iteration   1: 0.880 ops/ms
Iteration   1: 1.511 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.511 ops/ms


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
# Warmup Iteration   1: 18.626 ±(99.9%) 0.205 ms/op
Iteration   1: 9.156 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.156 ms/op


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
# Warmup Iteration   1: 8.115 ±(99.9%) 0.239 ms/op
Iteration   1: 4.027 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.027 ms/op


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
# Warmup Iteration   1: 11.087 ±(99.9%) 0.149 ms/op
Iteration   1: 4.791 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.791 ms/op


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
# Warmup Iteration   1: 30.116 ±(99.9%) 0.435 ms/op
Iteration   1: 15.845 ±(99.9%) 0.049 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.845 ms/op


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
# Warmup Iteration   1: 12.789 ±(99.9%) 0.436 ms/op
Iteration   1: 6.261 ±(99.9%) 0.067 ms/op
                 createUser·p0.00:   3.060 ms/op
                 createUser·p0.50:   6.341 ms/op
                 createUser·p0.90:   6.824 ms/op
                 createUser·p0.95:   7.021 ms/op
                 createUser·p0.99:   12.744 ms/op
                 createUser·p0.999:  16.974 ms/op
                 createUser·p0.9999: 17.203 ms/op
                 createUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5107
  mean =      6.261 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 376 
    [ 3.750,  5.000) = 201 
    [ 5.000,  6.250) = 1331 
    [ 6.250,  7.500) = 3022 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.060 ms/op
     p(50.0000) =      6.341 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =     12.744 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 8.019 ±(99.9%) 0.335 ms/op
Iteration   1: 4.260 ±(99.9%) 0.068 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   4.557 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   14.090 ms/op
                 existUser·p0.999:  18.940 ms/op
                 existUser·p0.9999: 19.562 ms/op
                 existUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7586
  mean =      4.260 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 187 
    [ 2.500,  3.750) = 1446 
    [ 3.750,  5.000) = 5483 
    [ 5.000,  6.250) = 136 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.557 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =     14.090 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 11.229 ±(99.9%) 0.318 ms/op
Iteration   1: 4.720 ±(99.9%) 0.081 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   5.995 ms/op
                 getUser·p0.99:   13.726 ms/op
                 getUser·p0.999:  28.753 ms/op
                 getUser·p0.9999: 29.000 ms/op
                 getUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6762
  mean =      4.720 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 5591 
    [ 5.000,  7.500) = 988 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      5.995 ms/op
     p(99.0000) =     13.726 ms/op
     p(99.9000) =     28.753 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     29.000 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 23.455 ±(99.9%) 0.690 ms/op
Iteration   1: 13.092 ±(99.9%) 0.222 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   12.206 ms/op
                 listUser·p0.90:   15.765 ms/op
                 listUser·p0.95:   19.176 ms/op
                 listUser·p0.99:   27.801 ms/op
                 listUser·p0.999:  32.509 ms/op
                 listUser·p0.9999: 33.260 ms/op
                 listUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2457
  mean =     13.092 ±(99.9%) 0.222 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 2 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 1367 
    [12.500, 15.000) = 732 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =     12.206 ms/op
     p(90.0000) =     15.765 ms/op
     p(95.0000) =     19.176 ms/op
     p(99.0000) =     27.801 ms/op
     p(99.9000) =     32.509 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.974          ops/ms
Client.existUser                       thrpt         5.080          ops/ms
Client.getUser                         thrpt         3.673          ops/ms
Client.listUser                        thrpt         1.511          ops/ms
Client.createUser                       avgt         9.156           ms/op
Client.existUser                        avgt         4.027           ms/op
Client.getUser                          avgt         4.791           ms/op
Client.listUser                         avgt        15.845           ms/op
Client.createUser                     sample  5107   6.261 ± 0.067   ms/op
Client.createUser:createUser·p0.00    sample         3.060           ms/op
Client.createUser:createUser·p0.50    sample         6.341           ms/op
Client.createUser:createUser·p0.90    sample         6.824           ms/op
Client.createUser:createUser·p0.95    sample         7.021           ms/op
Client.createUser:createUser·p0.99    sample        12.744           ms/op
Client.createUser:createUser·p0.999   sample        16.974           ms/op
Client.createUser:createUser·p0.9999  sample        17.203           ms/op
Client.createUser:createUser·p1.00    sample        17.203           ms/op
Client.existUser                      sample  7586   4.260 ± 0.068   ms/op
Client.existUser:existUser·p0.00      sample         1.049           ms/op
Client.existUser:existUser·p0.50      sample         3.957           ms/op
Client.existUser:existUser·p0.90      sample         4.557           ms/op
Client.existUser:existUser·p0.95      sample         5.775           ms/op
Client.existUser:existUser·p0.99      sample        14.090           ms/op
Client.existUser:existUser·p0.999     sample        18.940           ms/op
Client.existUser:existUser·p0.9999    sample        19.562           ms/op
Client.existUser:existUser·p1.00      sample        19.562           ms/op
Client.getUser                        sample  6762   4.720 ± 0.081   ms/op
Client.getUser:getUser·p0.00          sample         1.272           ms/op
Client.getUser:getUser·p0.50          sample         4.440           ms/op
Client.getUser:getUser·p0.90          sample         5.472           ms/op
Client.getUser:getUser·p0.95          sample         5.995           ms/op
Client.getUser:getUser·p0.99          sample        13.726           ms/op
Client.getUser:getUser·p0.999         sample        28.753           ms/op
Client.getUser:getUser·p0.9999        sample        29.000           ms/op
Client.getUser:getUser·p1.00          sample        29.000           ms/op
Client.listUser                       sample  2457  13.092 ± 0.222   ms/op
Client.listUser:listUser·p0.00        sample         1.843           ms/op
Client.listUser:listUser·p0.50        sample        12.206           ms/op
Client.listUser:listUser·p0.90        sample        15.765           ms/op
Client.listUser:listUser·p0.95        sample        19.176           ms/op
Client.listUser:listUser·p0.99        sample        27.801           ms/op
Client.listUser:listUser·p0.999       sample        32.509           ms/op
Client.listUser:listUser·p0.9999      sample        33.260           ms/op
Client.listUser:listUser·p1.00        sample        33.260           ms/op
