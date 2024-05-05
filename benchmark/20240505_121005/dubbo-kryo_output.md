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
# Warmup Iteration   1: 1.444 ops/ms
Iteration   1: 7.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.534 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.594 ops/ms
Iteration   1: 13.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.764 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.434 ops/ms
Iteration   1: 14.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.800 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.421 ops/ms
Iteration   1: 9.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.512 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.033 ±(99.9%) 0.072 ms/op
Iteration   1: 2.068 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.068 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.810 ±(99.9%) 0.044 ms/op
Iteration   1: 1.771 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.771 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.458 ±(99.9%) 0.057 ms/op
Iteration   1: 2.354 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.354 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.490 ±(99.9%) 0.090 ms/op
Iteration   1: 3.243 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.243 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.877 ±(99.9%) 0.095 ms/op
Iteration   1: 1.955 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   1.829 ms/op
                 createUser·p0.90:   2.408 ms/op
                 createUser·p0.95:   2.639 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  15.346 ms/op
                 createUser·p0.9999: 16.685 ms/op
                 createUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16351
  mean =      1.955 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 433 
    [ 1.250,  2.500) = 14740 
    [ 2.500,  3.750) = 940 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.639 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     15.346 ms/op
     p(99.9900) =     16.685 ms/op
     p(99.9990) =     16.695 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.945 ±(99.9%) 0.064 ms/op
Iteration   1: 1.768 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   1.673 ms/op
                 existUser·p0.90:   1.931 ms/op
                 existUser·p0.95:   2.150 ms/op
                 existUser·p0.99:   2.849 ms/op
                 existUser·p0.999:  18.514 ms/op
                 existUser·p0.9999: 18.612 ms/op
                 existUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18068
  mean =      1.768 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 17546 
    [ 2.500,  3.750) = 343 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      1.931 ms/op
     p(95.0000) =      2.150 ms/op
     p(99.0000) =      2.849 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     18.612 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.125 ±(99.9%) 0.075 ms/op
Iteration   1: 2.078 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.480 ms/op
                 getUser·p0.50:   2.005 ms/op
                 getUser·p0.90:   2.712 ms/op
                 getUser·p0.95:   2.933 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  14.350 ms/op
                 getUser·p0.9999: 14.491 ms/op
                 getUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15384
  mean =      2.078 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 226 
    [ 1.250,  2.500) = 12314 
    [ 2.500,  3.750) = 2649 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      3.994 ms/op
     p(99.9000) =     14.350 ms/op
     p(99.9900) =     14.491 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.986 ±(99.9%) 0.119 ms/op
Iteration   1: 3.735 ±(99.9%) 0.177 ms/op
                 listUser·p0.00:   0.765 ms/op
                 listUser·p0.50:   3.322 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   14.844 ms/op
                 listUser·p0.999:  92.386 ms/op
                 listUser·p0.9999: 100.663 ms/op
                 listUser·p1.00:   100.663 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8573
  mean =      3.735 ±(99.9%) 0.177 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 8454 
    [ 10.000,  20.000) = 38 
    [ 20.000,  30.000) = 35 
    [ 30.000,  40.000) = 9 
    [ 40.000,  50.000) = 8 
    [ 50.000,  60.000) = 4 
    [ 60.000,  70.000) = 8 
    [ 70.000,  80.000) = 2 
    [ 80.000,  90.000) = 5 
    [ 90.000, 100.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =     14.844 ms/op
     p(99.9000) =     92.386 ms/op
     p(99.9900) =    100.663 ms/op
     p(99.9990) =    100.663 ms/op
     p(99.9999) =    100.663 ms/op
    p(100.0000) =    100.663 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.534          ops/ms
ClientSimple.existUser                       thrpt          13.764          ops/ms
ClientSimple.getUser                         thrpt          14.800          ops/ms
ClientSimple.listUser                        thrpt           9.512          ops/ms
ClientSimple.createUser                       avgt           2.068           ms/op
ClientSimple.existUser                        avgt           1.771           ms/op
ClientSimple.getUser                          avgt           2.354           ms/op
ClientSimple.listUser                         avgt           3.243           ms/op
ClientSimple.createUser                     sample  16351    1.955 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.847           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.829           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.408           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.639           ms/op
ClientSimple.createUser:createUser·p0.99    sample           5.562           ms/op
ClientSimple.createUser:createUser·p0.999   sample          15.346           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          16.685           ms/op
ClientSimple.createUser:createUser·p1.00    sample          16.695           ms/op
ClientSimple.existUser                      sample  18068    1.768 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.813           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.673           ms/op
ClientSimple.existUser:existUser·p0.90      sample           1.931           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.150           ms/op
ClientSimple.existUser:existUser·p0.99      sample           2.849           ms/op
ClientSimple.existUser:existUser·p0.999     sample          18.514           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          18.612           ms/op
ClientSimple.existUser:existUser·p1.00      sample          18.612           ms/op
ClientSimple.getUser                        sample  15384    2.078 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.480           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.005           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.712           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.933           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.994           ms/op
ClientSimple.getUser:getUser·p0.999         sample          14.350           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          14.491           ms/op
ClientSimple.getUser:getUser·p1.00          sample          14.500           ms/op
ClientSimple.listUser                       sample   8573    3.735 ± 0.177   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.765           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.322           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          14.844           ms/op
ClientSimple.listUser:listUser·p0.999       sample          92.386           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         100.663           ms/op
ClientSimple.listUser:listUser·p1.00        sample         100.663           ms/op

Benchmark result is saved to 1714910745683.json
