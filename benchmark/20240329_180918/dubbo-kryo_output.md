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
# Warmup Iteration   1: 1.660 ops/ms
Iteration   1: 7.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.057 ops/ms


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
# Warmup Iteration   1: 6.402 ops/ms
Iteration   1: 13.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.417 ops/ms


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
# Warmup Iteration   1: 5.840 ops/ms
Iteration   1: 14.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.688 ops/ms


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
# Warmup Iteration   1: 4.736 ops/ms
Iteration   1: 8.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.767 ops/ms


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.065 ms/op
Iteration   1: 2.214 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.214 ms/op


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
# Warmup Iteration   1: 3.418 ±(99.9%) 0.057 ms/op
Iteration   1: 1.863 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.863 ms/op


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
# Warmup Iteration   1: 2.925 ±(99.9%) 0.044 ms/op
Iteration   1: 1.696 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.696 ms/op


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
# Warmup Iteration   1: 4.525 ±(99.9%) 0.125 ms/op
Iteration   1: 3.316 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.316 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.091 ms/op
Iteration   1: 2.319 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.432 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.883 ms/op
                 createUser·p0.99:   8.942 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 19.742 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13823
  mean =      2.319 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 10905 
    [ 2.500,  3.750) = 2471 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.883 ms/op
     p(99.0000) =      8.942 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     19.742 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 2.914 ±(99.9%) 0.072 ms/op
Iteration   1: 1.783 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   1.708 ms/op
                 existUser·p0.90:   1.995 ms/op
                 existUser·p0.95:   2.194 ms/op
                 existUser·p0.99:   2.714 ms/op
                 existUser·p0.999:  16.549 ms/op
                 existUser·p0.9999: 17.427 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17947
  mean =      1.783 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 17475 
    [ 2.500,  3.750) = 255 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      1.995 ms/op
     p(95.0000) =      2.194 ms/op
     p(99.0000) =      2.714 ms/op
     p(99.9000) =     16.549 ms/op
     p(99.9900) =     17.427 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 3.463 ±(99.9%) 0.095 ms/op
Iteration   1: 1.914 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   1.741 ms/op
                 getUser·p0.90:   2.224 ms/op
                 getUser·p0.95:   2.589 ms/op
                 getUser·p0.99:   4.513 ms/op
                 getUser·p0.999:  20.972 ms/op
                 getUser·p0.9999: 21.070 ms/op
                 getUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16705
  mean =      1.914 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15727 
    [ 2.500,  5.000) = 839 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      4.513 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     21.070 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 4.296 ±(99.9%) 0.109 ms/op
Iteration   1: 3.253 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   5.884 ms/op
                 listUser·p0.999:  11.375 ms/op
                 listUser·p0.9999: 11.567 ms/op
                 listUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9868
  mean =      3.253 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 1819 
    [ 2.500,  3.750) = 5266 
    [ 3.750,  5.000) = 2510 
    [ 5.000,  6.250) = 189 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.884 ms/op
     p(99.9000) =     11.375 ms/op
     p(99.9900) =     11.567 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.057          ops/ms
ClientSimple.existUser                       thrpt         13.417          ops/ms
ClientSimple.getUser                         thrpt         14.688          ops/ms
ClientSimple.listUser                        thrpt          8.767          ops/ms
ClientSimple.createUser                       avgt          2.214           ms/op
ClientSimple.existUser                        avgt          1.863           ms/op
ClientSimple.getUser                          avgt          1.696           ms/op
ClientSimple.listUser                         avgt          3.316           ms/op
ClientSimple.createUser                     sample  13823   2.319 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.432           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.883           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.942           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.957           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.742           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.792           ms/op
ClientSimple.existUser                      sample  17947   1.783 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.494           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.708           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.995           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.194           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.714           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.549           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.427           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.531           ms/op
ClientSimple.getUser                        sample  16705   1.914 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.602           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.741           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.224           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.513           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.972           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.070           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.070           ms/op
ClientSimple.listUser                       sample   9868   3.253 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.853           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.052           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.884           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.375           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.567           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.567           ms/op

Benchmark result is saved to 1711735487388.json
