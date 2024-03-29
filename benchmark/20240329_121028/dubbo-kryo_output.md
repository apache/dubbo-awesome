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
# Warmup Iteration   1: 1.861 ops/ms
Iteration   1: 6.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.623 ops/ms


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
# Warmup Iteration   1: 5.506 ops/ms
Iteration   1: 12.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.854 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.488 ops/ms
Iteration   1: 13.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.764 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.568 ops/ms
Iteration   1: 8.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.570 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.290 ±(99.9%) 0.084 ms/op
Iteration   1: 2.388 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.388 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.531 ±(99.9%) 0.057 ms/op
Iteration   1: 1.938 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.938 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.392 ±(99.9%) 0.063 ms/op
Iteration   1: 2.241 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.241 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.736 ±(99.9%) 0.088 ms/op
Iteration   1: 3.375 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.375 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.542 ±(99.9%) 0.090 ms/op
Iteration   1: 2.266 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   2.042 ms/op
                 createUser·p0.90:   2.707 ms/op
                 createUser·p0.95:   2.933 ms/op
                 createUser·p0.99:   10.715 ms/op
                 createUser·p0.999:  27.127 ms/op
                 createUser·p0.9999: 30.519 ms/op
                 createUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14391
  mean =      2.266 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11684 
    [ 2.500,  5.000) = 2440 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     27.127 ms/op
     p(99.9900) =     30.519 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 3.089 ±(99.9%) 0.082 ms/op
Iteration   1: 1.887 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   1.892 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.445 ms/op
                 existUser·p0.99:   3.776 ms/op
                 existUser·p0.999:  12.778 ms/op
                 existUser·p0.9999: 13.145 ms/op
                 existUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17120
  mean =      1.887 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1095 
    [ 1.250,  2.500) = 15338 
    [ 2.500,  3.750) = 501 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.445 ms/op
     p(99.0000) =      3.776 ms/op
     p(99.9000) =     12.778 ms/op
     p(99.9900) =     13.145 ms/op
     p(99.9990) =     13.156 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.095 ms/op
Iteration   1: 2.013 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.351 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.683 ms/op
                 getUser·p0.95:   2.884 ms/op
                 getUser·p0.99:   4.488 ms/op
                 getUser·p0.999:  22.282 ms/op
                 getUser·p0.9999: 22.592 ms/op
                 getUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15903
  mean =      2.013 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13252 
    [ 2.500,  5.000) = 2532 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      4.488 ms/op
     p(99.9000) =     22.282 ms/op
     p(99.9900) =     22.592 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 4.457 ±(99.9%) 0.133 ms/op
Iteration   1: 3.393 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   3.203 ms/op
                 listUser·p0.90:   4.575 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.078 ms/op
                 listUser·p0.999:  17.444 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9414
  mean =      3.393 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1272 
    [ 2.500,  3.750) = 5444 
    [ 3.750,  5.000) = 2237 
    [ 5.000,  6.250) = 393 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      4.575 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     17.444 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.623          ops/ms
ClientSimple.existUser                       thrpt         12.854          ops/ms
ClientSimple.getUser                         thrpt         13.764          ops/ms
ClientSimple.listUser                        thrpt          8.570          ops/ms
ClientSimple.createUser                       avgt          2.388           ms/op
ClientSimple.existUser                        avgt          1.938           ms/op
ClientSimple.getUser                          avgt          2.241           ms/op
ClientSimple.listUser                         avgt          3.375           ms/op
ClientSimple.createUser                     sample  14391   2.266 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.555           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.042           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.715           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.127           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.519           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.605           ms/op
ClientSimple.existUser                      sample  17120   1.887 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.634           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.892           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.776           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.778           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.145           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.156           ms/op
ClientSimple.getUser                        sample  15903   2.013 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.351           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.884           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.488           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.282           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.592           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.708           ms/op
ClientSimple.listUser                       sample   9414   3.393 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.196           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.203           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.575           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.078           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.444           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.547           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.547           ms/op

Benchmark result is saved to 1711713957345.json
