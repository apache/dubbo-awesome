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
# Warmup Iteration   1: 1.536 ops/ms
Iteration   1: 6.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.574 ops/ms


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
# Warmup Iteration   1: 5.290 ops/ms
Iteration   1: 11.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.670 ops/ms


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
# Warmup Iteration   1: 4.806 ops/ms
Iteration   1: 12.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.460 ops/ms


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
# Warmup Iteration   1: 4.742 ops/ms
Iteration   1: 8.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.929 ops/ms


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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.088 ms/op
Iteration   1: 2.413 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.413 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.058 ms/op
Iteration   1: 1.949 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.949 ms/op


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
# Warmup Iteration   1: 3.450 ±(99.9%) 0.059 ms/op
Iteration   1: 2.009 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.009 ms/op


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
# Warmup Iteration   1: 4.490 ±(99.9%) 0.087 ms/op
Iteration   1: 3.889 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.889 ms/op


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
# Warmup Iteration   1: 3.459 ±(99.9%) 0.088 ms/op
Iteration   1: 2.176 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   1.946 ms/op
                 createUser·p0.90:   2.417 ms/op
                 createUser·p0.95:   2.695 ms/op
                 createUser·p0.99:   9.208 ms/op
                 createUser·p0.999:  32.309 ms/op
                 createUser·p0.9999: 33.244 ms/op
                 createUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14690
  mean =      2.176 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13561 
    [ 2.500,  5.000) = 938 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      9.208 ms/op
     p(99.9000) =     32.309 ms/op
     p(99.9900) =     33.244 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 2.985 ±(99.9%) 0.075 ms/op
Iteration   1: 1.858 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.559 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.007 ms/op
                 existUser·p0.95:   2.170 ms/op
                 existUser·p0.99:   4.267 ms/op
                 existUser·p0.999:  15.061 ms/op
                 existUser·p0.9999: 15.558 ms/op
                 existUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17205
  mean =      1.858 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 16738 
    [ 2.500,  3.750) = 219 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.007 ms/op
     p(95.0000) =      2.170 ms/op
     p(99.0000) =      4.267 ms/op
     p(99.9000) =     15.061 ms/op
     p(99.9900) =     15.558 ms/op
     p(99.9990) =     15.581 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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
# Warmup Iteration   1: 3.359 ±(99.9%) 0.097 ms/op
Iteration   1: 2.007 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   1.931 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.707 ms/op
                 getUser·p0.99:   3.454 ms/op
                 getUser·p0.999:  11.375 ms/op
                 getUser·p0.9999: 11.715 ms/op
                 getUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15923
  mean =      2.007 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 533 
    [ 1.250,  2.500) = 13724 
    [ 2.500,  3.750) = 1530 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.454 ms/op
     p(99.9000) =     11.375 ms/op
     p(99.9900) =     11.715 ms/op
     p(99.9990) =     11.715 ms/op
     p(99.9999) =     11.715 ms/op
    p(100.0000) =     11.715 ms/op


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
# Warmup Iteration   1: 4.729 ±(99.9%) 0.150 ms/op
Iteration   1: 3.610 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   3.473 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.713 ms/op
                 listUser·p0.99:   9.780 ms/op
                 listUser·p0.999:  26.575 ms/op
                 listUser·p0.9999: 27.001 ms/op
                 listUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8852
  mean =      3.610 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 977 
    [ 2.500,  5.000) = 7546 
    [ 5.000,  7.500) = 209 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.713 ms/op
     p(99.0000) =      9.780 ms/op
     p(99.9000) =     26.575 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.574          ops/ms
ClientSimple.existUser                       thrpt         11.670          ops/ms
ClientSimple.getUser                         thrpt         12.460          ops/ms
ClientSimple.listUser                        thrpt          8.929          ops/ms
ClientSimple.createUser                       avgt          2.413           ms/op
ClientSimple.existUser                        avgt          1.949           ms/op
ClientSimple.getUser                          avgt          2.009           ms/op
ClientSimple.listUser                         avgt          3.889           ms/op
ClientSimple.createUser                     sample  14690   2.176 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.621           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.946           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.417           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.208           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.309           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.244           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.260           ms/op
ClientSimple.existUser                      sample  17205   1.858 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.559           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.763           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.007           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.170           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.267           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.061           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.558           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.581           ms/op
ClientSimple.getUser                        sample  15923   2.007 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.758           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.931           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.454           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.375           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.715           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.715           ms/op
ClientSimple.listUser                       sample   8852   3.610 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.800           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.473           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.713           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.780           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.575           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.001           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.001           ms/op

Benchmark result is saved to 1722405905101.json
