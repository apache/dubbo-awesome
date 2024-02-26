# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.431 ops/ms
Iteration   1: 5.881 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.881 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.556 ops/ms
Iteration   1: 12.352 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.352 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.681 ops/ms
Iteration   1: 8.491 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.491 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.053 ops/ms
Iteration   1: 3.467 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.467 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.196 ±(99.9%) 0.069 ms/op
Iteration   1: 3.165 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.165 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.072 ±(99.9%) 0.029 ms/op
Iteration   1: 1.721 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.721 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ±(99.9%) 0.049 ms/op
Iteration   1: 2.900 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.900 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.358 ±(99.9%) 0.171 ms/op
Iteration   1: 8.735 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.735 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.860 ±(99.9%) 0.250 ms/op
Iteration   1: 3.247 ±(99.9%) 0.063 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   2.875 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.698 ms/op
                 createUser·p0.99:   10.977 ms/op
                 createUser·p0.999:  26.477 ms/op
                 createUser·p0.9999: 26.542 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9849
  mean =      3.247 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2228 
    [ 2.500,  5.000) = 7223 
    [ 5.000,  7.500) = 220 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.698 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     26.477 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.732 ±(99.9%) 0.054 ms/op
Iteration   1: 1.774 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.487 ms/op
                 existUser·p0.50:   1.669 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.466 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 13.156 ms/op
                 existUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18032
  mean =      1.774 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 991 
    [ 1.250,  2.500) = 16233 
    [ 2.500,  3.750) = 653 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     13.156 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.391 ±(99.9%) 0.110 ms/op
Iteration   1: 3.023 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  6.765 ms/op
                 getUser·p0.9999: 7.858 ms/op
                 getUser·p1.00:   7.889 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10575
  mean =      3.023 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 12 
    [1.000, 1.500) = 128 
    [1.500, 2.000) = 442 
    [2.000, 2.500) = 1605 
    [2.500, 3.000) = 2669 
    [3.000, 3.500) = 3768 
    [3.500, 4.000) = 1367 
    [4.000, 4.500) = 361 
    [4.500, 5.000) = 101 
    [5.000, 5.500) = 67 
    [5.500, 6.000) = 7 
    [6.000, 6.500) = 18 
    [6.500, 7.000) = 23 
    [7.000, 7.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =      6.765 ms/op
     p(99.9900) =      7.858 ms/op
     p(99.9990) =      7.889 ms/op
     p(99.9999) =      7.889 ms/op
    p(100.0000) =      7.889 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.318 ±(99.9%) 0.416 ms/op
Iteration   1: 9.294 ±(99.9%) 0.175 ms/op
                 listUser·p0.00:   3.203 ms/op
                 listUser·p0.50:   8.831 ms/op
                 listUser·p0.90:   12.550 ms/op
                 listUser·p0.95:   13.509 ms/op
                 listUser·p0.99:   21.529 ms/op
                 listUser·p0.999:  34.390 ms/op
                 listUser·p0.9999: 36.045 ms/op
                 listUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3449
  mean =      9.294 ±(99.9%) 0.175 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 69 
    [ 5.000,  7.500) = 846 
    [ 7.500, 10.000) = 1433 
    [10.000, 12.500) = 745 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      3.203 ms/op
     p(50.0000) =      8.831 ms/op
     p(90.0000) =     12.550 ms/op
     p(95.0000) =     13.509 ms/op
     p(99.0000) =     21.529 ms/op
     p(99.9000) =     34.390 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.881          ops/ms
Client.existUser                       thrpt         12.352          ops/ms
Client.getUser                         thrpt          8.491          ops/ms
Client.listUser                        thrpt          3.467          ops/ms
Client.createUser                       avgt          3.165           ms/op
Client.existUser                        avgt          1.721           ms/op
Client.getUser                          avgt          2.900           ms/op
Client.listUser                         avgt          8.735           ms/op
Client.createUser                     sample   9849   3.247 ± 0.063   ms/op
Client.createUser:createUser·p0.00    sample          0.849           ms/op
Client.createUser:createUser·p0.50    sample          2.875           ms/op
Client.createUser:createUser·p0.90    sample          4.211           ms/op
Client.createUser:createUser·p0.95    sample          4.698           ms/op
Client.createUser:createUser·p0.99    sample         10.977           ms/op
Client.createUser:createUser·p0.999   sample         26.477           ms/op
Client.createUser:createUser·p0.9999  sample         26.542           ms/op
Client.createUser:createUser·p1.00    sample         26.542           ms/op
Client.existUser                      sample  18032   1.774 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.487           ms/op
Client.existUser:existUser·p0.50      sample          1.669           ms/op
Client.existUser:existUser·p0.90      sample          2.232           ms/op
Client.existUser:existUser·p0.95      sample          2.466           ms/op
Client.existUser:existUser·p0.99      sample          3.510           ms/op
Client.existUser:existUser·p0.999     sample         12.845           ms/op
Client.existUser:existUser·p0.9999    sample         13.156           ms/op
Client.existUser:existUser·p1.00      sample         13.156           ms/op
Client.getUser                        sample  10575   3.023 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.606           ms/op
Client.getUser:getUser·p0.50          sample          3.056           ms/op
Client.getUser:getUser·p0.90          sample          3.748           ms/op
Client.getUser:getUser·p0.95          sample          4.051           ms/op
Client.getUser:getUser·p0.99          sample          5.038           ms/op
Client.getUser:getUser·p0.999         sample          6.765           ms/op
Client.getUser:getUser·p0.9999        sample          7.858           ms/op
Client.getUser:getUser·p1.00          sample          7.889           ms/op
Client.listUser                       sample   3449   9.294 ± 0.175   ms/op
Client.listUser:listUser·p0.00        sample          3.203           ms/op
Client.listUser:listUser·p0.50        sample          8.831           ms/op
Client.listUser:listUser·p0.90        sample         12.550           ms/op
Client.listUser:listUser·p0.95        sample         13.509           ms/op
Client.listUser:listUser·p0.99        sample         21.529           ms/op
Client.listUser:listUser·p0.999       sample         34.390           ms/op
Client.listUser:listUser·p0.9999      sample         36.045           ms/op
Client.listUser:listUser·p1.00        sample         36.045           ms/op
