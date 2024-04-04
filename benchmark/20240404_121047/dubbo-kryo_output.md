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
# Warmup Iteration   1: 0.876 ops/ms
Iteration   1: 6.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.104 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.516 ops/ms
Iteration   1: 12.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.275 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.330 ops/ms
Iteration   1: 13.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.581 ops/ms


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
# Warmup Iteration   1: 3.985 ops/ms
Iteration   1: 8.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.274 ops/ms


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
# Warmup Iteration   1: 4.145 ±(99.9%) 0.079 ms/op
Iteration   1: 2.271 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.271 ms/op


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
# Warmup Iteration   1: 2.905 ±(99.9%) 0.047 ms/op
Iteration   1: 1.755 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.755 ms/op


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
# Warmup Iteration   1: 3.159 ±(99.9%) 0.051 ms/op
Iteration   1: 2.032 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.032 ms/op


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
# Warmup Iteration   1: 4.959 ±(99.9%) 0.095 ms/op
Iteration   1: 3.318 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.318 ms/op


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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.117 ms/op
Iteration   1: 2.187 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.011 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.901 ms/op
                 createUser·p0.99:   5.256 ms/op
                 createUser·p0.999:  16.843 ms/op
                 createUser·p0.9999: 17.758 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14612
  mean =      2.187 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 12575 
    [ 2.500,  3.750) = 1682 
    [ 3.750,  5.000) = 155 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.901 ms/op
     p(99.0000) =      5.256 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     17.758 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 2.942 ±(99.9%) 0.069 ms/op
Iteration   1: 1.951 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.449 ms/op
                 existUser·p0.99:   7.489 ms/op
                 existUser·p0.999:  27.619 ms/op
                 existUser·p0.9999: 28.359 ms/op
                 existUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16380
  mean =      1.951 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15656 
    [ 2.500,  5.000) = 528 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.449 ms/op
     p(99.0000) =      7.489 ms/op
     p(99.9000) =     27.619 ms/op
     p(99.9900) =     28.359 ms/op
     p(99.9990) =     28.443 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 3.186 ±(99.9%) 0.097 ms/op
Iteration   1: 1.938 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   1.812 ms/op
                 getUser·p0.90:   2.298 ms/op
                 getUser·p0.95:   2.511 ms/op
                 getUser·p0.99:   3.396 ms/op
                 getUser·p0.999:  25.379 ms/op
                 getUser·p0.9999: 26.547 ms/op
                 getUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16495
  mean =      1.938 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15641 
    [ 2.500,  5.000) = 789 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      3.396 ms/op
     p(99.9000) =     25.379 ms/op
     p(99.9900) =     26.547 ms/op
     p(99.9990) =     26.739 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.118 ms/op
Iteration   1: 3.216 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   8.291 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 13.402 ms/op
                 listUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9986
  mean =      3.216 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1451 
    [ 2.500,  3.750) = 6642 
    [ 3.750,  5.000) = 1571 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      8.291 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     13.402 ms/op
     p(99.9999) =     13.402 ms/op
    p(100.0000) =     13.402 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.104          ops/ms
ClientSimple.existUser                       thrpt         12.275          ops/ms
ClientSimple.getUser                         thrpt         13.581          ops/ms
ClientSimple.listUser                        thrpt          8.274          ops/ms
ClientSimple.createUser                       avgt          2.271           ms/op
ClientSimple.existUser                        avgt          1.755           ms/op
ClientSimple.getUser                          avgt          2.032           ms/op
ClientSimple.listUser                         avgt          3.318           ms/op
ClientSimple.createUser                     sample  14612   2.187 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.920           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.011           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.901           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.256           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.843           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.758           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.924           ms/op
ClientSimple.existUser                      sample  16380   1.951 ± 0.040   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.499           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.99      sample          7.489           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.619           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.359           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.443           ms/op
ClientSimple.getUser                        sample  16495   1.938 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.839           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.812           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.298           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.396           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.379           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.547           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.739           ms/op
ClientSimple.listUser                       sample   9986   3.216 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.914           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.945           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.035           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.291           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.255           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.402           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.402           ms/op

Benchmark result is saved to 1712232387235.json
