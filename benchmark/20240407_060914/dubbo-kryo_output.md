# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.115 ops/ms
Iteration   1: 6.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.508 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.947 ops/ms
Iteration   1: 12.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.967 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.225 ops/ms
Iteration   1: 13.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.442 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.739 ops/ms
Iteration   1: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.166 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.065 ms/op
Iteration   1: 2.049 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.049 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.418 ±(99.9%) 0.047 ms/op
Iteration   1: 1.702 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.702 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ±(99.9%) 0.071 ms/op
Iteration   1: 2.316 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.316 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.469 ±(99.9%) 0.101 ms/op
Iteration   1: 3.816 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.816 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.402 ±(99.9%) 0.076 ms/op
Iteration   1: 2.160 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.673 ms/op
                 createUser·p0.50:   2.042 ms/op
                 createUser·p0.90:   2.687 ms/op
                 createUser·p0.95:   2.978 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  19.910 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14798
  mean =      2.160 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12440 
    [ 2.500,  5.000) = 2153 
    [ 5.000,  7.500) = 76 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     19.910 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.034 ±(99.9%) 0.082 ms/op
Iteration   1: 2.127 ±(99.9%) 0.042 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   1.974 ms/op
                 existUser·p0.90:   2.572 ms/op
                 existUser·p0.95:   2.695 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  32.801 ms/op
                 existUser·p0.9999: 34.469 ms/op
                 existUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15204
  mean =      2.127 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13107 
    [ 2.500,  5.000) = 2032 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.498 ms/op
     p(99.9000) =     32.801 ms/op
     p(99.9900) =     34.469 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.273 ±(99.9%) 0.087 ms/op
Iteration   1: 1.912 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.548 ms/op
                 getUser·p0.50:   1.825 ms/op
                 getUser·p0.90:   2.265 ms/op
                 getUser·p0.95:   2.458 ms/op
                 getUser·p0.99:   3.252 ms/op
                 getUser·p0.999:  13.418 ms/op
                 getUser·p0.9999: 13.778 ms/op
                 getUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16747
  mean =      1.912 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 15989 
    [ 2.500,  3.750) = 572 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.252 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     13.778 ms/op
     p(99.9990) =     13.877 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.590 ±(99.9%) 0.153 ms/op
Iteration   1: 3.307 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   3.260 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  14.651 ms/op
                 listUser·p0.9999: 16.417 ms/op
                 listUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9686
  mean =      3.307 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1192 
    [ 2.500,  3.750) = 6419 
    [ 3.750,  5.000) = 1787 
    [ 5.000,  6.250) = 161 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     14.651 ms/op
     p(99.9900) =     16.417 ms/op
     p(99.9990) =     16.417 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.508          ops/ms
ClientSimple.existUser                       thrpt         12.967          ops/ms
ClientSimple.getUser                         thrpt         13.442          ops/ms
ClientSimple.listUser                        thrpt          8.166          ops/ms
ClientSimple.createUser                       avgt          2.049           ms/op
ClientSimple.existUser                        avgt          1.702           ms/op
ClientSimple.getUser                          avgt          2.316           ms/op
ClientSimple.listUser                         avgt          3.816           ms/op
ClientSimple.createUser                     sample  14798   2.160 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.673           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.042           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.094           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.910           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.546           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.546           ms/op
ClientSimple.existUser                      sample  15204   2.127 ± 0.042   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.708           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.974           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.498           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.801           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         34.469           ms/op
ClientSimple.existUser:existUser·p1.00      sample         34.537           ms/op
ClientSimple.getUser                        sample  16747   1.912 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.548           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.825           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.265           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.252           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.418           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.778           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.877           ms/op
ClientSimple.listUser                       sample   9686   3.307 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.022           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.260           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.043           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.529           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.651           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.417           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.417           ms/op

Benchmark result is saved to 1712469888880.json
