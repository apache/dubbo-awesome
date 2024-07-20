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
# Warmup Iteration   1: 1.958 ops/ms
Iteration   1: 8.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.078 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.210 ops/ms
Iteration   1: 14.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.773 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.820 ops/ms
Iteration   1: 11.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.843 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.263 ops/ms
Iteration   1: 9.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.166 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.857 ±(99.9%) 0.063 ms/op
Iteration   1: 2.202 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.202 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.270 ±(99.9%) 0.050 ms/op
Iteration   1: 1.900 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.900 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.588 ±(99.9%) 0.070 ms/op
Iteration   1: 2.062 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.062 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.072 ±(99.9%) 0.081 ms/op
Iteration   1: 3.244 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.244 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.542 ±(99.9%) 0.115 ms/op
Iteration   1: 2.145 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   1.950 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   2.875 ms/op
                 createUser·p0.99:   9.077 ms/op
                 createUser·p0.999:  17.662 ms/op
                 createUser·p0.9999: 18.384 ms/op
                 createUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14896
  mean =      2.145 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 12912 
    [ 2.500,  3.750) = 1455 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      1.950 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     18.384 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 2.744 ±(99.9%) 0.058 ms/op
Iteration   1: 2.025 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.459 ms/op
                 existUser·p0.50:   1.970 ms/op
                 existUser·p0.90:   2.486 ms/op
                 existUser·p0.95:   2.748 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  17.931 ms/op
                 existUser·p0.9999: 18.528 ms/op
                 existUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15797
  mean =      2.025 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 459 
    [ 1.250,  2.500) = 13853 
    [ 2.500,  3.750) = 1383 
    [ 3.750,  5.000) = 16 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.490 ms/op
     p(99.9000) =     17.931 ms/op
     p(99.9900) =     18.528 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.118 ms/op
Iteration   1: 1.932 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.465 ms/op
                 getUser·p0.50:   1.864 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.650 ms/op
                 getUser·p0.99:   3.078 ms/op
                 getUser·p0.999:  17.436 ms/op
                 getUser·p0.9999: 18.226 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16961
  mean =      1.932 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 559 
    [ 1.250,  2.500) = 15077 
    [ 2.500,  3.750) = 1241 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.078 ms/op
     p(99.9000) =     17.436 ms/op
     p(99.9900) =     18.226 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.765 ±(99.9%) 0.145 ms/op
Iteration   1: 3.282 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.511 ms/op
                 listUser·p0.99:   6.591 ms/op
                 listUser·p0.999:  30.261 ms/op
                 listUser·p0.9999: 30.835 ms/op
                 listUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9747
  mean =      3.282 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1141 
    [ 2.500,  5.000) = 8343 
    [ 5.000,  7.500) = 198 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.511 ms/op
     p(99.0000) =      6.591 ms/op
     p(99.9000) =     30.261 ms/op
     p(99.9900) =     30.835 ms/op
     p(99.9990) =     30.835 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.078          ops/ms
ClientSimple.existUser                       thrpt         14.773          ops/ms
ClientSimple.getUser                         thrpt         11.843          ops/ms
ClientSimple.listUser                        thrpt          9.166          ops/ms
ClientSimple.createUser                       avgt          2.202           ms/op
ClientSimple.existUser                        avgt          1.900           ms/op
ClientSimple.getUser                          avgt          2.062           ms/op
ClientSimple.listUser                         avgt          3.244           ms/op
ClientSimple.createUser                     sample  14896   2.145 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.527           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.950           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.077           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.662           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.384           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.448           ms/op
ClientSimple.existUser                      sample  15797   2.025 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.459           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.970           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.748           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.490           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.931           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.528           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.547           ms/op
ClientSimple.getUser                        sample  16961   1.932 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.465           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.864           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.078           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.436           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.226           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.317           ms/op
ClientSimple.listUser                       sample   9747   3.282 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.920           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.511           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.591           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.261           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         30.835           ms/op
ClientSimple.listUser:listUser·p1.00        sample         30.835           ms/op

Benchmark result is saved to 1721477158377.json
