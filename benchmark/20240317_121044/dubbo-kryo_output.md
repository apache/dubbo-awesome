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
# Warmup Iteration   1: 1.589 ops/ms
Iteration   1: 7.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.580 ops/ms


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
# Warmup Iteration   1: 6.886 ops/ms
Iteration   1: 12.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.182 ops/ms


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
# Warmup Iteration   1: 6.031 ops/ms
Iteration   1: 13.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.311 ops/ms


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
# Warmup Iteration   1: 5.733 ops/ms
Iteration   1: 8.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.778 ops/ms


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
# Warmup Iteration   1: 3.934 ±(99.9%) 0.072 ms/op
Iteration   1: 2.142 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.142 ms/op


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
# Warmup Iteration   1: 3.139 ±(99.9%) 0.079 ms/op
Iteration   1: 1.850 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.850 ms/op


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.075 ms/op
Iteration   1: 1.937 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.937 ms/op


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.082 ms/op
Iteration   1: 3.482 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.482 ms/op


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
# Warmup Iteration   1: 3.526 ±(99.9%) 0.089 ms/op
Iteration   1: 2.009 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   1.761 ms/op
                 createUser·p0.90:   2.494 ms/op
                 createUser·p0.95:   2.687 ms/op
                 createUser·p0.99:   7.406 ms/op
                 createUser·p0.999:  31.522 ms/op
                 createUser·p0.9999: 32.368 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16011
  mean =      2.009 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14456 
    [ 2.500,  5.000) = 1328 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     31.522 ms/op
     p(99.9900) =     32.368 ms/op
     p(99.9990) =     32.408 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 3.054 ±(99.9%) 0.064 ms/op
Iteration   1: 1.750 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   1.671 ms/op
                 existUser·p0.90:   1.878 ms/op
                 existUser·p0.95:   2.023 ms/op
                 existUser·p0.99:   2.511 ms/op
                 existUser·p0.999:  25.690 ms/op
                 existUser·p0.9999: 26.296 ms/op
                 existUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18393
  mean =      1.750 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18202 
    [ 2.500,  5.000) = 115 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      1.671 ms/op
     p(90.0000) =      1.878 ms/op
     p(95.0000) =      2.023 ms/op
     p(99.0000) =      2.511 ms/op
     p(99.9000) =     25.690 ms/op
     p(99.9900) =     26.296 ms/op
     p(99.9990) =     26.378 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 3.322 ±(99.9%) 0.080 ms/op
Iteration   1: 2.070 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.441 ms/op
                 getUser·p0.50:   2.017 ms/op
                 getUser·p0.90:   2.527 ms/op
                 getUser·p0.95:   2.691 ms/op
                 getUser·p0.99:   3.375 ms/op
                 getUser·p0.999:  14.042 ms/op
                 getUser·p0.9999: 15.335 ms/op
                 getUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15456
  mean =      2.070 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 13645 
    [ 2.500,  3.750) = 1617 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.441 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      3.375 ms/op
     p(99.9000) =     14.042 ms/op
     p(99.9900) =     15.335 ms/op
     p(99.9990) =     15.335 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 4.242 ±(99.9%) 0.132 ms/op
Iteration   1: 3.326 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   3.330 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  10.174 ms/op
                 listUser·p0.9999: 10.224 ms/op
                 listUser·p1.00:   10.224 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9731
  mean =      3.326 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 4 
    [ 1.000,  2.000) = 660 
    [ 2.000,  3.000) = 2647 
    [ 3.000,  4.000) = 4825 
    [ 4.000,  5.000) = 1217 
    [ 5.000,  6.000) = 241 
    [ 6.000,  7.000) = 44 
    [ 7.000,  8.000) = 34 
    [ 8.000,  9.000) = 10 
    [ 9.000, 10.000) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     10.174 ms/op
     p(99.9900) =     10.224 ms/op
     p(99.9990) =     10.224 ms/op
     p(99.9999) =     10.224 ms/op
    p(100.0000) =     10.224 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.580          ops/ms
ClientSimple.existUser                       thrpt         12.182          ops/ms
ClientSimple.getUser                         thrpt         13.311          ops/ms
ClientSimple.listUser                        thrpt          8.778          ops/ms
ClientSimple.createUser                       avgt          2.142           ms/op
ClientSimple.existUser                        avgt          1.850           ms/op
ClientSimple.getUser                          avgt          1.937           ms/op
ClientSimple.listUser                         avgt          3.482           ms/op
ClientSimple.createUser                     sample  16011   2.009 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.601           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.761           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.494           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.406           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.522           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.368           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.408           ms/op
ClientSimple.existUser                      sample  18393   1.750 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.426           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.671           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.878           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.023           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.690           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.296           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.378           ms/op
ClientSimple.getUser                        sample  15456   2.070 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.441           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.017           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.375           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.042           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.335           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.335           ms/op
ClientSimple.listUser                       sample   9731   3.326 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.859           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.330           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.768           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.898           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.174           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.224           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.224           ms/op

Benchmark result is saved to 1710677179962.json
