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
# Warmup Iteration   1: 1.558 ops/ms
Iteration   1: 5.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.320 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.938 ops/ms
Iteration   1: 13.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.611 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.458 ops/ms
Iteration   1: 11.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.931 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.869 ops/ms
Iteration   1: 7.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.974 ops/ms


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.078 ms/op
Iteration   1: 2.123 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.123 ms/op


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
# Warmup Iteration   1: 3.428 ±(99.9%) 0.063 ms/op
Iteration   1: 1.762 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.762 ms/op


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
# Warmup Iteration   1: 3.562 ±(99.9%) 0.073 ms/op
Iteration   1: 2.073 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.073 ms/op


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
# Warmup Iteration   1: 4.239 ±(99.9%) 0.097 ms/op
Iteration   1: 3.619 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.619 ms/op


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
# Warmup Iteration   1: 4.145 ±(99.9%) 0.117 ms/op
Iteration   1: 2.328 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.520 ms/op
                 createUser·p0.50:   2.159 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   9.751 ms/op
                 createUser·p0.999:  15.446 ms/op
                 createUser·p0.9999: 16.460 ms/op
                 createUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13781
  mean =      2.328 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 472 
    [ 1.250,  2.500) = 9862 
    [ 2.500,  3.750) = 2924 
    [ 3.750,  5.000) = 160 
    [ 5.000,  6.250) = 111 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      9.751 ms/op
     p(99.9000) =     15.446 ms/op
     p(99.9900) =     16.460 ms/op
     p(99.9990) =     16.466 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


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
# Warmup Iteration   1: 3.275 ±(99.9%) 0.075 ms/op
Iteration   1: 2.080 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   1.956 ms/op
                 existUser·p0.90:   2.540 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  19.857 ms/op
                 existUser·p0.9999: 20.397 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15360
  mean =      2.080 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13584 
    [ 2.500,  5.000) = 1639 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     20.397 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 3.374 ±(99.9%) 0.100 ms/op
Iteration   1: 2.067 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   1.937 ms/op
                 getUser·p0.90:   2.761 ms/op
                 getUser·p0.95:   3.015 ms/op
                 getUser·p0.99:   3.872 ms/op
                 getUser·p0.999:  14.541 ms/op
                 getUser·p0.9999: 14.764 ms/op
                 getUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15471
  mean =      2.067 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 488 
    [ 1.250,  2.500) = 12043 
    [ 2.500,  3.750) = 2776 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.872 ms/op
     p(99.9000) =     14.541 ms/op
     p(99.9900) =     14.764 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.922 ±(99.9%) 0.172 ms/op
Iteration   1: 3.707 ±(99.9%) 0.056 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.520 ms/op
                 listUser·p0.95:   5.365 ms/op
                 listUser·p0.99:   8.279 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8682
  mean =      3.707 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 421 
    [ 2.500,  3.750) = 4654 
    [ 3.750,  5.000) = 3065 
    [ 5.000,  6.250) = 297 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.520 ms/op
     p(95.0000) =      5.365 ms/op
     p(99.0000) =      8.279 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.595 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.320          ops/ms
ClientSimple.existUser                       thrpt         13.611          ops/ms
ClientSimple.getUser                         thrpt         11.931          ops/ms
ClientSimple.listUser                        thrpt          7.974          ops/ms
ClientSimple.createUser                       avgt          2.123           ms/op
ClientSimple.existUser                        avgt          1.762           ms/op
ClientSimple.getUser                          avgt          2.073           ms/op
ClientSimple.listUser                         avgt          3.619           ms/op
ClientSimple.createUser                     sample  13781   2.328 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.520           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.159           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.199           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.751           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.446           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.460           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.466           ms/op
ClientSimple.existUser                      sample  15360   2.080 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.537           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.956           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.822           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.375           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.857           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.397           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.414           ms/op
ClientSimple.getUser                        sample  15471   2.067 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.530           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.937           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.015           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.872           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.541           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.764           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.926           ms/op
ClientSimple.listUser                       sample   8682   3.707 ± 0.056   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.221           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.600           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.520           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.365           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.279           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.940           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.595           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.595           ms/op

Benchmark result is saved to 1713053918854.json
