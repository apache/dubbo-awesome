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
# Warmup Iteration   1: 0.702 ops/ms
Iteration   1: 4.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  4.713 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.498 ops/ms
Iteration   1: 12.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.370 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.655 ops/ms
Iteration   1: 11.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.041 ops/ms


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
# Warmup Iteration   1: 4.072 ops/ms
Iteration   1: 8.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.935 ops/ms


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
# Warmup Iteration   1: 4.474 ±(99.9%) 0.099 ms/op
Iteration   1: 2.261 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.261 ms/op


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.102 ms/op
Iteration   1: 2.082 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.082 ms/op


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
# Warmup Iteration   1: 3.480 ±(99.9%) 0.063 ms/op
Iteration   1: 2.308 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.308 ms/op


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
# Warmup Iteration   1: 6.735 ±(99.9%) 0.222 ms/op
Iteration   1: 4.138 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.138 ms/op


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
# Warmup Iteration   1: 5.070 ±(99.9%) 0.138 ms/op
Iteration   1: 2.595 ±(99.9%) 0.063 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   2.253 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   4.464 ms/op
                 createUser·p0.99:   10.551 ms/op
                 createUser·p0.999:  35.979 ms/op
                 createUser·p0.9999: 36.887 ms/op
                 createUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12300
  mean =      2.595 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8662 
    [ 2.500,  5.000) = 3116 
    [ 5.000,  7.500) = 314 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.253 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      4.464 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     35.979 ms/op
     p(99.9900) =     36.887 ms/op
     p(99.9990) =     36.962 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


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
# Warmup Iteration   1: 3.141 ±(99.9%) 0.088 ms/op
Iteration   1: 2.093 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   1.929 ms/op
                 existUser·p0.90:   2.540 ms/op
                 existUser·p0.95:   2.814 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  15.200 ms/op
                 existUser·p0.9999: 15.727 ms/op
                 existUser·p1.00:   15.761 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15276
  mean =      2.093 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 194 
    [ 1.250,  2.500) = 13411 
    [ 2.500,  3.750) = 1274 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     15.200 ms/op
     p(99.9900) =     15.727 ms/op
     p(99.9990) =     15.761 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 3.497 ±(99.9%) 0.099 ms/op
Iteration   1: 2.340 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.418 ms/op
                 getUser·p0.50:   2.073 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.708 ms/op
                 getUser·p0.99:   7.826 ms/op
                 getUser·p0.999:  27.991 ms/op
                 getUser·p0.9999: 28.942 ms/op
                 getUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13773
  mean =      2.340 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10153 
    [ 2.500,  5.000) = 3200 
    [ 5.000,  7.500) = 273 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      2.073 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.708 ms/op
     p(99.0000) =      7.826 ms/op
     p(99.9000) =     27.991 ms/op
     p(99.9900) =     28.942 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 5.422 ±(99.9%) 0.175 ms/op
Iteration   1: 4.007 ±(99.9%) 0.065 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.446 ms/op
                 listUser·p0.99:   10.041 ms/op
                 listUser·p0.999:  23.101 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7982
  mean =      4.007 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 653 
    [ 2.500,  5.000) = 6330 
    [ 5.000,  7.500) = 748 
    [ 7.500, 10.000) = 170 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      6.446 ms/op
     p(99.0000) =     10.041 ms/op
     p(99.9000) =     23.101 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          4.713          ops/ms
ClientSimple.existUser                       thrpt         12.370          ops/ms
ClientSimple.getUser                         thrpt         11.041          ops/ms
ClientSimple.listUser                        thrpt          8.935          ops/ms
ClientSimple.createUser                       avgt          2.261           ms/op
ClientSimple.existUser                        avgt          2.082           ms/op
ClientSimple.getUser                          avgt          2.308           ms/op
ClientSimple.listUser                         avgt          4.138           ms/op
ClientSimple.createUser                     sample  12300   2.595 ± 0.063   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.695           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.253           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.990           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.464           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.551           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.979           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.887           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.962           ms/op
ClientSimple.existUser                      sample  15276   2.093 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.765           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.929           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.814           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.939           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.200           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.727           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.761           ms/op
ClientSimple.getUser                        sample  13773   2.340 ± 0.046   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.418           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.073           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.994           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.708           ms/op
ClientSimple.getUser:getUser·p0.99          sample          7.826           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.991           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.942           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.967           ms/op
ClientSimple.listUser                       sample   7982   4.007 ± 0.065   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.940           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.744           ms/op
ClientSimple.listUser:listUser·p0.90        sample          5.374           ms/op
ClientSimple.listUser:listUser·p0.95        sample          6.446           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.041           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.101           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.790           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.790           ms/op

Benchmark result is saved to 1714673101173.json
