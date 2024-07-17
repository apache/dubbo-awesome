# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.769 ops/ms
Iteration   1: 6.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.450 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.441 ops/ms
Iteration   1: 13.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.696 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.734 ops/ms
Iteration   1: 12.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.914 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.130 ops/ms
Iteration   1: 7.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.939 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.422 ±(99.9%) 0.066 ms/op
Iteration   1: 2.074 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.074 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.426 ±(99.9%) 0.065 ms/op
Iteration   1: 1.970 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.970 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.392 ±(99.9%) 0.052 ms/op
Iteration   1: 2.006 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.006 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ±(99.9%) 0.095 ms/op
Iteration   1: 3.299 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.299 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.299 ±(99.9%) 0.079 ms/op
Iteration   1: 2.037 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   1.827 ms/op
                 createUser·p0.90:   2.261 ms/op
                 createUser·p0.95:   2.462 ms/op
                 createUser·p0.99:   8.668 ms/op
                 createUser·p0.999:  16.155 ms/op
                 createUser·p0.9999: 19.792 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15695
  mean =      2.037 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 14966 
    [ 2.500,  3.750) = 412 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      8.668 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.300 ±(99.9%) 0.082 ms/op
Iteration   1: 1.742 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.373 ms/op
                 existUser·p0.50:   1.667 ms/op
                 existUser·p0.90:   2.042 ms/op
                 existUser·p0.95:   2.163 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  14.107 ms/op
                 existUser·p0.9999: 15.607 ms/op
                 existUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18367
  mean =      1.742 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1202 
    [ 1.250,  2.500) = 16769 
    [ 2.500,  3.750) = 257 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.042 ms/op
     p(95.0000) =      2.163 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     15.607 ms/op
     p(99.9990) =     16.073 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.272 ±(99.9%) 0.097 ms/op
Iteration   1: 1.902 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.389 ms/op
                 getUser·p0.50:   1.698 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.560 ms/op
                 getUser·p0.99:   4.303 ms/op
                 getUser·p0.999:  27.615 ms/op
                 getUser·p0.9999: 28.410 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17241
  mean =      1.902 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16161 
    [ 2.500,  5.000) = 973 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.389 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      4.303 ms/op
     p(99.9000) =     27.615 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.428 ±(99.9%) 0.134 ms/op
Iteration   1: 3.505 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.043 ms/op
                 listUser·p0.999:  7.528 ms/op
                 listUser·p0.9999: 9.667 ms/op
                 listUser·p1.00:   9.667 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9138
  mean =      3.505 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 18 
    [ 1.500,  2.000) = 64 
    [ 2.000,  2.500) = 625 
    [ 2.500,  3.000) = 1092 
    [ 3.000,  3.500) = 2592 
    [ 3.500,  4.000) = 3121 
    [ 4.000,  4.500) = 1231 
    [ 4.500,  5.000) = 202 
    [ 5.000,  5.500) = 51 
    [ 5.500,  6.000) = 47 
    [ 6.000,  6.500) = 44 
    [ 6.500,  7.000) = 16 
    [ 7.000,  7.500) = 21 
    [ 7.500,  8.000) = 11 
    [ 8.000,  8.500) = 1 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.043 ms/op
     p(99.9000) =      7.528 ms/op
     p(99.9900) =      9.667 ms/op
     p(99.9990) =      9.667 ms/op
     p(99.9999) =      9.667 ms/op
    p(100.0000) =      9.667 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.450          ops/ms
ClientSimple.existUser                       thrpt         13.696          ops/ms
ClientSimple.getUser                         thrpt         12.914          ops/ms
ClientSimple.listUser                        thrpt          7.939          ops/ms
ClientSimple.createUser                       avgt          2.074           ms/op
ClientSimple.existUser                        avgt          1.970           ms/op
ClientSimple.getUser                          avgt          2.006           ms/op
ClientSimple.listUser                         avgt          3.299           ms/op
ClientSimple.createUser                     sample  15695   2.037 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.987           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.827           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.261           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.668           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.155           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.792           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.792           ms/op
ClientSimple.existUser                      sample  18367   1.742 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.373           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.667           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.042           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.163           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.543           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.107           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.607           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.073           ms/op
ClientSimple.getUser                        sample  17241   1.902 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.389           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.698           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.303           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.615           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.410           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.410           ms/op
ClientSimple.listUser                       sample   9138   3.505 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.169           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.523           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.043           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.528           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.667           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.667           ms/op

Benchmark result is saved to 1721196369773.json
