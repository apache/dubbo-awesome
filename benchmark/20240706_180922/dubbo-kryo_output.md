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
# Warmup Iteration   1: 1.779 ops/ms
Iteration   1: 6.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.922 ops/ms


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
# Warmup Iteration   1: 6.075 ops/ms
Iteration   1: 11.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.326 ops/ms


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
# Warmup Iteration   1: 5.320 ops/ms
Iteration   1: 11.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.151 ops/ms


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
# Warmup Iteration   1: 4.475 ops/ms
Iteration   1: 9.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.869 ops/ms


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.062 ms/op
Iteration   1: 2.118 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.118 ms/op


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
# Warmup Iteration   1: 3.142 ±(99.9%) 0.045 ms/op
Iteration   1: 1.561 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.561 ms/op


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
# Warmup Iteration   1: 3.518 ±(99.9%) 0.074 ms/op
Iteration   1: 1.959 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.959 ms/op


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
# Warmup Iteration   1: 4.736 ±(99.9%) 0.103 ms/op
Iteration   1: 2.913 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.913 ms/op


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
# Warmup Iteration   1: 3.413 ±(99.9%) 0.090 ms/op
Iteration   1: 2.077 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   1.946 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.781 ms/op
                 createUser·p0.99:   4.885 ms/op
                 createUser·p0.999:  18.907 ms/op
                 createUser·p0.9999: 20.427 ms/op
                 createUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15387
  mean =      2.077 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13730 
    [ 2.500,  5.000) = 1507 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      4.885 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     20.427 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 3.182 ±(99.9%) 0.082 ms/op
Iteration   1: 1.821 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.500 ms/op
                 existUser·p0.50:   1.729 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   4.426 ms/op
                 existUser·p0.999:  13.894 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17578
  mean =      1.821 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2512 
    [ 1.250,  2.500) = 13632 
    [ 2.500,  3.750) = 1233 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      4.426 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     13.992 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.071 ms/op
Iteration   1: 1.899 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   1.819 ms/op
                 getUser·p0.90:   2.494 ms/op
                 getUser·p0.95:   2.638 ms/op
                 getUser·p0.99:   3.113 ms/op
                 getUser·p0.999:  11.059 ms/op
                 getUser·p0.9999: 11.554 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17093
  mean =      1.899 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 761 
    [ 1.250,  2.500) = 14687 
    [ 2.500,  3.750) = 1532 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.113 ms/op
     p(99.9000) =     11.059 ms/op
     p(99.9900) =     11.554 ms/op
     p(99.9990) =     11.682 ms/op
     p(99.9999) =     11.682 ms/op
    p(100.0000) =     11.682 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.150 ms/op
Iteration   1: 3.170 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.069 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 15.513 ms/op
                 listUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10105
  mean =      3.170 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2141 
    [ 2.500,  3.750) = 6113 
    [ 3.750,  5.000) = 1478 
    [ 5.000,  6.250) = 181 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.069 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     15.513 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.922          ops/ms
ClientSimple.existUser                       thrpt         11.326          ops/ms
ClientSimple.getUser                         thrpt         11.151          ops/ms
ClientSimple.listUser                        thrpt          9.869          ops/ms
ClientSimple.createUser                       avgt          2.118           ms/op
ClientSimple.existUser                        avgt          1.561           ms/op
ClientSimple.getUser                          avgt          1.959           ms/op
ClientSimple.listUser                         avgt          2.913           ms/op
ClientSimple.createUser                     sample  15387   2.077 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.483           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.946           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.885           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.907           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.427           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.939           ms/op
ClientSimple.existUser                      sample  17578   1.821 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.500           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.729           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.630           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.426           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.894           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.992           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.992           ms/op
ClientSimple.getUser                        sample  17093   1.899 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.585           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.819           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.113           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.059           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.554           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.682           ms/op
ClientSimple.listUser                       sample  10105   3.170 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.321           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.920           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.940           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.069           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.172           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.513           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.516           ms/op

Benchmark result is saved to 1720289084832.json
