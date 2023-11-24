# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.546 ops/ms
Iteration   1: 5.918 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.918 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.276 ops/ms
Iteration   1: 12.754 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.754 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.340 ops/ms
Iteration   1: 8.602 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.602 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.758 ops/ms
Iteration   1: 3.463 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.463 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.656 ±(99.9%) 0.071 ms/op
Iteration   1: 2.948 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.948 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.881 ±(99.9%) 0.043 ms/op
Iteration   1: 1.767 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.767 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.499 ±(99.9%) 0.053 ms/op
Iteration   1: 2.806 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.806 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.126 ±(99.9%) 0.240 ms/op
Iteration   1: 7.829 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.829 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.625 ±(99.9%) 0.094 ms/op
Iteration   1: 2.916 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   2.814 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.944 ms/op
                 createUser·p0.999:  7.569 ms/op
                 createUser·p0.9999: 9.221 ms/op
                 createUser·p1.00:   9.224 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10953
  mean =      2.916 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 130 
    [ 2.000,  3.000) = 7342 
    [ 3.000,  4.000) = 3143 
    [ 4.000,  5.000) = 235 
    [ 5.000,  6.000) = 39 
    [ 6.000,  7.000) = 25 
    [ 7.000,  8.000) = 35 
    [ 8.000,  9.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.944 ms/op
     p(99.9000) =      7.569 ms/op
     p(99.9900) =      9.221 ms/op
     p(99.9990) =      9.224 ms/op
     p(99.9999) =      9.224 ms/op
    p(100.0000) =      9.224 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.909 ±(99.9%) 0.057 ms/op
Iteration   1: 2.055 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.498 ms/op
                 existUser·p0.50:   1.831 ms/op
                 existUser·p0.90:   2.568 ms/op
                 existUser·p0.95:   2.933 ms/op
                 existUser·p0.99:   7.103 ms/op
                 existUser·p0.999:  16.178 ms/op
                 existUser·p0.9999: 17.338 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15546
  mean =      2.055 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 220 
    [ 1.250,  2.500) = 13511 
    [ 2.500,  3.750) = 1346 
    [ 3.750,  5.000) = 231 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      7.103 ms/op
     p(99.9000) =     16.178 ms/op
     p(99.9900) =     17.338 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.461 ±(99.9%) 0.088 ms/op
Iteration   1: 2.782 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   2.765 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   5.689 ms/op
                 getUser·p0.999:  16.194 ms/op
                 getUser·p0.9999: 17.486 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11514
  mean =      2.782 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 4479 
    [ 2.500,  3.750) = 6536 
    [ 3.750,  5.000) = 332 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.765 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.689 ms/op
     p(99.9000) =     16.194 ms/op
     p(99.9900) =     17.486 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.976 ±(99.9%) 0.407 ms/op
Iteration   1: 8.507 ±(99.9%) 0.110 ms/op
                 listUser·p0.00:   3.006 ms/op
                 listUser·p0.50:   8.225 ms/op
                 listUser·p0.90:   11.010 ms/op
                 listUser·p0.95:   12.124 ms/op
                 listUser·p0.99:   15.571 ms/op
                 listUser·p0.999:  20.944 ms/op
                 listUser·p0.9999: 26.935 ms/op
                 listUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3764
  mean =      8.507 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 51 
    [ 5.000,  7.500) = 1163 
    [ 7.500, 10.000) = 1854 
    [10.000, 12.500) = 551 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      3.006 ms/op
     p(50.0000) =      8.225 ms/op
     p(90.0000) =     11.010 ms/op
     p(95.0000) =     12.124 ms/op
     p(99.0000) =     15.571 ms/op
     p(99.9000) =     20.944 ms/op
     p(99.9900) =     26.935 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.918          ops/ms
Client.existUser                       thrpt         12.754          ops/ms
Client.getUser                         thrpt          8.602          ops/ms
Client.listUser                        thrpt          3.463          ops/ms
Client.createUser                       avgt          2.948           ms/op
Client.existUser                        avgt          1.767           ms/op
Client.getUser                          avgt          2.806           ms/op
Client.listUser                         avgt          7.829           ms/op
Client.createUser                     sample  10953   2.916 ± 0.018   ms/op
Client.createUser:createUser·p0.00    sample          0.850           ms/op
Client.createUser:createUser·p0.50    sample          2.814           ms/op
Client.createUser:createUser·p0.90    sample          3.482           ms/op
Client.createUser:createUser·p0.95    sample          3.785           ms/op
Client.createUser:createUser·p0.99    sample          4.944           ms/op
Client.createUser:createUser·p0.999   sample          7.569           ms/op
Client.createUser:createUser·p0.9999  sample          9.221           ms/op
Client.createUser:createUser·p1.00    sample          9.224           ms/op
Client.existUser                      sample  15546   2.055 ± 0.032   ms/op
Client.existUser:existUser·p0.00      sample          0.498           ms/op
Client.existUser:existUser·p0.50      sample          1.831           ms/op
Client.existUser:existUser·p0.90      sample          2.568           ms/op
Client.existUser:existUser·p0.95      sample          2.933           ms/op
Client.existUser:existUser·p0.99      sample          7.103           ms/op
Client.existUser:existUser·p0.999     sample         16.178           ms/op
Client.existUser:existUser·p0.9999    sample         17.338           ms/op
Client.existUser:existUser·p1.00      sample         17.465           ms/op
Client.getUser                        sample  11514   2.782 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          0.804           ms/op
Client.getUser:getUser·p0.50          sample          2.765           ms/op
Client.getUser:getUser·p0.90          sample          3.441           ms/op
Client.getUser:getUser·p0.95          sample          3.699           ms/op
Client.getUser:getUser·p0.99          sample          5.689           ms/op
Client.getUser:getUser·p0.999         sample         16.194           ms/op
Client.getUser:getUser·p0.9999        sample         17.486           ms/op
Client.getUser:getUser·p1.00          sample         17.531           ms/op
Client.listUser                       sample   3764   8.507 ± 0.110   ms/op
Client.listUser:listUser·p0.00        sample          3.006           ms/op
Client.listUser:listUser·p0.50        sample          8.225           ms/op
Client.listUser:listUser·p0.90        sample         11.010           ms/op
Client.listUser:listUser·p0.95        sample         12.124           ms/op
Client.listUser:listUser·p0.99        sample         15.571           ms/op
Client.listUser:listUser·p0.999       sample         20.944           ms/op
Client.listUser:listUser·p0.9999      sample         26.935           ms/op
Client.listUser:listUser·p1.00        sample         26.935           ms/op
