# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.215 ops/ms
Iteration   1: 6.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.134 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.259 ops/ms
Iteration   1: 13.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.164 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.962 ops/ms
Iteration   1: 11.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.860 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.941 ops/ms
Iteration   1: 8.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.755 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.710 ±(99.9%) 0.060 ms/op
Iteration   1: 2.108 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.108 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.079 ±(99.9%) 0.057 ms/op
Iteration   1: 2.224 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.224 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.293 ±(99.9%) 0.057 ms/op
Iteration   1: 2.225 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.225 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.818 ±(99.9%) 0.106 ms/op
Iteration   1: 3.522 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.522 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.520 ±(99.9%) 0.104 ms/op
Iteration   1: 2.039 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   1.835 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.990 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  15.135 ms/op
                 createUser·p0.9999: 21.611 ms/op
                 createUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15777
  mean =      2.039 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14031 
    [ 2.500,  5.000) = 1543 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     15.135 ms/op
     p(99.9900) =     21.611 ms/op
     p(99.9990) =     26.837 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.074 ±(99.9%) 0.064 ms/op
Iteration   1: 2.345 ±(99.9%) 0.152 ms/op
                 existUser·p0.00:   0.421 ms/op
                 existUser·p0.50:   1.939 ms/op
                 existUser·p0.90:   2.384 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   9.410 ms/op
                 existUser·p0.999:  105.644 ms/op
                 existUser·p0.9999: 139.015 ms/op
                 existUser·p1.00:   141.033 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13666
  mean =      2.345 ±(99.9%) 0.152 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 13547 
    [ 12.500,  25.000) = 64 
    [ 25.000,  37.500) = 5 
    [ 37.500,  50.000) = 10 
    [ 50.000,  62.500) = 6 
    [ 62.500,  75.000) = 4 
    [ 75.000,  87.500) = 6 
    [ 87.500, 100.000) = 9 
    [100.000, 112.500) = 6 
    [112.500, 125.000) = 2 
    [125.000, 137.500) = 6 
    [137.500, 150.000) = 1 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      9.410 ms/op
     p(99.9000) =    105.644 ms/op
     p(99.9900) =    139.015 ms/op
     p(99.9990) =    141.033 ms/op
     p(99.9999) =    141.033 ms/op
    p(100.0000) =    141.033 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.161 ±(99.9%) 0.071 ms/op
Iteration   1: 2.359 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   2.347 ms/op
                 getUser·p0.90:   2.777 ms/op
                 getUser·p0.95:   2.978 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  18.609 ms/op
                 getUser·p0.9999: 18.928 ms/op
                 getUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13555
  mean =      2.359 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 9376 
    [ 2.500,  3.750) = 3926 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.347 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =     18.609 ms/op
     p(99.9900) =     18.928 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.294 ±(99.9%) 0.116 ms/op
Iteration   1: 3.821 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.971 ms/op
                 listUser·p0.99:   6.259 ms/op
                 listUser·p0.999:  18.434 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8423
  mean =      3.821 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 688 
    [ 2.500,  3.750) = 2918 
    [ 3.750,  5.000) = 4414 
    [ 5.000,  6.250) = 317 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.971 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     18.434 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.134          ops/ms
ClientSimple.existUser                       thrpt          13.164          ops/ms
ClientSimple.getUser                         thrpt          11.860          ops/ms
ClientSimple.listUser                        thrpt           8.755          ops/ms
ClientSimple.createUser                       avgt           2.108           ms/op
ClientSimple.existUser                        avgt           2.224           ms/op
ClientSimple.getUser                          avgt           2.225           ms/op
ClientSimple.listUser                         avgt           3.522           ms/op
ClientSimple.createUser                     sample  15777    2.039 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.614           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.835           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.990           ms/op
ClientSimple.createUser:createUser·p0.99    sample           7.619           ms/op
ClientSimple.createUser:createUser·p0.999   sample          15.135           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          21.611           ms/op
ClientSimple.createUser:createUser·p1.00    sample          26.837           ms/op
ClientSimple.existUser                      sample  13666    2.345 ± 0.152   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.421           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.939           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.384           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample           9.410           ms/op
ClientSimple.existUser:existUser·p0.999     sample         105.644           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         139.015           ms/op
ClientSimple.existUser:existUser·p1.00      sample         141.033           ms/op
ClientSimple.getUser                        sample  13555    2.359 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.693           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.347           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.777           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.978           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.538           ms/op
ClientSimple.getUser:getUser·p0.999         sample          18.609           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          18.928           ms/op
ClientSimple.getUser:getUser·p1.00          sample          18.940           ms/op
ClientSimple.listUser                       sample   8423    3.821 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.178           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.604           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.971           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.259           ms/op
ClientSimple.listUser:listUser·p0.999       sample          18.434           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          19.530           ms/op
ClientSimple.listUser:listUser·p1.00        sample          19.530           ms/op

Benchmark result is saved to 1724890648145.json
