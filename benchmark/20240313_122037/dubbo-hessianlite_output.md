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
# Warmup Iteration   1: 2.201 ops/ms
Iteration   1: 5.553 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.553 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.254 ops/ms
Iteration   1: 12.452 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.452 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.454 ops/ms
Iteration   1: 8.931 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.931 ops/ms


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
# Warmup Iteration   1: 2.030 ops/ms
Iteration   1: 3.720 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.720 ops/ms


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
# Warmup Iteration   1: 6.950 ±(99.9%) 0.111 ms/op
Iteration   1: 3.341 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.341 ms/op


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
# Warmup Iteration   1: 3.438 ±(99.9%) 0.031 ms/op
Iteration   1: 2.049 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.049 ms/op


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
# Warmup Iteration   1: 4.464 ±(99.9%) 0.056 ms/op
Iteration   1: 3.207 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.207 ms/op


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
# Warmup Iteration   1: 11.363 ±(99.9%) 0.291 ms/op
Iteration   1: 8.744 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.744 ms/op


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
# Warmup Iteration   1: 4.886 ±(99.9%) 0.125 ms/op
Iteration   1: 2.791 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   2.703 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.823 ms/op
                 createUser·p0.999:  7.623 ms/op
                 createUser·p0.9999: 8.957 ms/op
                 createUser·p1.00:   8.978 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11424
  mean =      2.791 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 20 
    [1.500, 2.000) = 348 
    [2.000, 2.500) = 3144 
    [2.500, 3.000) = 5124 
    [3.000, 3.500) = 1828 
    [3.500, 4.000) = 607 
    [4.000, 4.500) = 208 
    [4.500, 5.000) = 41 
    [5.000, 5.500) = 24 
    [5.500, 6.000) = 6 
    [6.000, 6.500) = 10 
    [6.500, 7.000) = 26 
    [7.000, 7.500) = 21 
    [7.500, 8.000) = 14 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      2.703 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.823 ms/op
     p(99.9000) =      7.623 ms/op
     p(99.9900) =      8.957 ms/op
     p(99.9990) =      8.978 ms/op
     p(99.9999) =      8.978 ms/op
    p(100.0000) =      8.978 ms/op


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
# Warmup Iteration   1: 2.942 ±(99.9%) 0.060 ms/op
Iteration   1: 1.930 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   1.849 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   3.186 ms/op
                 existUser·p0.999:  19.890 ms/op
                 existUser·p0.9999: 20.300 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16557
  mean =      1.930 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15794 
    [ 2.500,  5.000) = 714 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      3.186 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     20.300 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 5.086 ±(99.9%) 0.163 ms/op
Iteration   1: 3.186 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  7.066 ms/op
                 getUser·p0.9999: 8.812 ms/op
                 getUser·p1.00:   8.815 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10024
  mean =      3.186 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 5 
    [1.500, 2.000) = 68 
    [2.000, 2.500) = 1716 
    [2.500, 3.000) = 2399 
    [3.000, 3.500) = 2668 
    [3.500, 4.000) = 2119 
    [4.000, 4.500) = 738 
    [4.500, 5.000) = 192 
    [5.000, 5.500) = 78 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 17 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 7 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.095 ms/op
     p(99.9000) =      7.066 ms/op
     p(99.9900) =      8.812 ms/op
     p(99.9990) =      8.815 ms/op
     p(99.9999) =      8.815 ms/op
    p(100.0000) =      8.815 ms/op


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
# Warmup Iteration   1: 11.420 ±(99.9%) 0.419 ms/op
Iteration   1: 7.254 ±(99.9%) 0.100 ms/op
                 listUser·p0.00:   1.909 ms/op
                 listUser·p0.50:   6.947 ms/op
                 listUser·p0.90:   9.388 ms/op
                 listUser·p0.95:   10.699 ms/op
                 listUser·p0.99:   15.663 ms/op
                 listUser·p0.999:  18.985 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4453
  mean =      7.254 ±(99.9%) 0.100 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 320 
    [ 5.000,  7.500) = 2522 
    [ 7.500, 10.000) = 1299 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.909 ms/op
     p(50.0000) =      6.947 ms/op
     p(90.0000) =      9.388 ms/op
     p(95.0000) =     10.699 ms/op
     p(99.0000) =     15.663 ms/op
     p(99.9000) =     18.985 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.553          ops/ms
Client.existUser                       thrpt         12.452          ops/ms
Client.getUser                         thrpt          8.931          ops/ms
Client.listUser                        thrpt          3.720          ops/ms
Client.createUser                       avgt          3.341           ms/op
Client.existUser                        avgt          2.049           ms/op
Client.getUser                          avgt          3.207           ms/op
Client.listUser                         avgt          8.744           ms/op
Client.createUser                     sample  11424   2.791 ± 0.019   ms/op
Client.createUser:createUser·p0.00    sample          1.102           ms/op
Client.createUser:createUser·p0.50    sample          2.703           ms/op
Client.createUser:createUser·p0.90    sample          3.428           ms/op
Client.createUser:createUser·p0.95    sample          3.797           ms/op
Client.createUser:createUser·p0.99    sample          4.823           ms/op
Client.createUser:createUser·p0.999   sample          7.623           ms/op
Client.createUser:createUser·p0.9999  sample          8.957           ms/op
Client.createUser:createUser·p1.00    sample          8.978           ms/op
Client.existUser                      sample  16557   1.930 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.660           ms/op
Client.existUser:existUser·p0.50      sample          1.849           ms/op
Client.existUser:existUser·p0.90      sample          2.331           ms/op
Client.existUser:existUser·p0.95      sample          2.490           ms/op
Client.existUser:existUser·p0.99      sample          3.186           ms/op
Client.existUser:existUser·p0.999     sample         19.890           ms/op
Client.existUser:existUser·p0.9999    sample         20.300           ms/op
Client.existUser:existUser·p1.00      sample         20.644           ms/op
Client.getUser                        sample  10024   3.186 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.950           ms/op
Client.getUser:getUser·p0.50          sample          3.146           ms/op
Client.getUser:getUser·p0.90          sample          4.022           ms/op
Client.getUser:getUser·p0.95          sample          4.268           ms/op
Client.getUser:getUser·p0.99          sample          5.095           ms/op
Client.getUser:getUser·p0.999         sample          7.066           ms/op
Client.getUser:getUser·p0.9999        sample          8.812           ms/op
Client.getUser:getUser·p1.00          sample          8.815           ms/op
Client.listUser                       sample   4453   7.254 ± 0.100   ms/op
Client.listUser:listUser·p0.00        sample          1.909           ms/op
Client.listUser:listUser·p0.50        sample          6.947           ms/op
Client.listUser:listUser·p0.90        sample          9.388           ms/op
Client.listUser:listUser·p0.95        sample         10.699           ms/op
Client.listUser:listUser·p0.99        sample         15.663           ms/op
Client.listUser:listUser·p0.999       sample         18.985           ms/op
Client.listUser:listUser·p0.9999      sample         20.775           ms/op
Client.listUser:listUser·p1.00        sample         20.775           ms/op
