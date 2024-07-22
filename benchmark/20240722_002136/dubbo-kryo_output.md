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
# Warmup Iteration   1: 1.891 ops/ms
Iteration   1: 6.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.765 ops/ms


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
# Warmup Iteration   1: 6.646 ops/ms
Iteration   1: 13.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.289 ops/ms


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
# Warmup Iteration   1: 5.119 ops/ms
Iteration   1: 11.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.720 ops/ms


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
# Warmup Iteration   1: 4.189 ops/ms
Iteration   1: 8.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.997 ops/ms


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.070 ms/op
Iteration   1: 2.202 ±(99.9%) 0.011 ms/op


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
# Warmup Iteration   1: 3.030 ±(99.9%) 0.046 ms/op
Iteration   1: 2.008 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.008 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.053 ms/op
Iteration   1: 1.891 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.891 ms/op


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.099 ms/op
Iteration   1: 3.107 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.107 ms/op


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
# Warmup Iteration   1: 3.554 ±(99.9%) 0.127 ms/op
Iteration   1: 2.294 ±(99.9%) 0.083 ms/op
                 createUser·p0.00:   0.453 ms/op
                 createUser·p0.50:   1.950 ms/op
                 createUser·p0.90:   2.699 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   9.077 ms/op
                 createUser·p0.999:  49.883 ms/op
                 createUser·p0.9999: 51.879 ms/op
                 createUser·p1.00:   51.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13919
  mean =      2.294 ±(99.9%) 0.083 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13691 
    [ 5.000, 10.000) = 127 
    [10.000, 15.000) = 38 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 8 
    [45.000, 50.000) = 19 
    [50.000, 55.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      1.950 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     49.883 ms/op
     p(99.9900) =     51.879 ms/op
     p(99.9990) =     51.905 ms/op
     p(99.9999) =     51.905 ms/op
    p(100.0000) =     51.905 ms/op


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
# Warmup Iteration   1: 3.044 ±(99.9%) 0.072 ms/op
Iteration   1: 1.831 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   1.692 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.465 ms/op
                 existUser·p0.99:   4.156 ms/op
                 existUser·p0.999:  15.794 ms/op
                 existUser·p0.9999: 15.946 ms/op
                 existUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17441
  mean =      1.831 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 544 
    [ 1.250,  2.500) = 16129 
    [ 2.500,  3.750) = 550 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      1.692 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.465 ms/op
     p(99.0000) =      4.156 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     15.946 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.280 ms/op
Iteration   1: 2.142 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   2.075 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.879 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  16.140 ms/op
                 getUser·p0.9999: 16.751 ms/op
                 getUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14914
  mean =      2.142 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 292 
    [ 1.250,  2.500) = 12162 
    [ 2.500,  3.750) = 2254 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =     16.140 ms/op
     p(99.9900) =     16.751 ms/op
     p(99.9990) =     17.138 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.676 ±(99.9%) 0.148 ms/op
Iteration   1: 3.367 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.461 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.046 ms/op
                 listUser·p0.999:  6.001 ms/op
                 listUser·p0.9999: 6.832 ms/op
                 listUser·p1.00:   6.832 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9494
  mean =      3.367 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 14 
    [1.500, 2.000) = 116 
    [2.000, 2.500) = 917 
    [2.500, 3.000) = 1961 
    [3.000, 3.500) = 1943 
    [3.500, 4.000) = 3236 
    [4.000, 4.500) = 959 
    [4.500, 5.000) = 236 
    [5.000, 5.500) = 68 
    [5.500, 6.000) = 35 
    [6.000, 6.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =      6.001 ms/op
     p(99.9900) =      6.832 ms/op
     p(99.9990) =      6.832 ms/op
     p(99.9999) =      6.832 ms/op
    p(100.0000) =      6.832 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.765          ops/ms
ClientSimple.existUser                       thrpt         13.289          ops/ms
ClientSimple.getUser                         thrpt         11.720          ops/ms
ClientSimple.listUser                        thrpt          8.997          ops/ms
ClientSimple.createUser                       avgt          2.202           ms/op
ClientSimple.existUser                        avgt          2.008           ms/op
ClientSimple.getUser                          avgt          1.891           ms/op
ClientSimple.listUser                         avgt          3.107           ms/op
ClientSimple.createUser                     sample  13919   2.294 ± 0.083   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.453           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.950           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.064           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.077           ms/op
ClientSimple.createUser:createUser·p0.999   sample         49.883           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         51.879           ms/op
ClientSimple.createUser:createUser·p1.00    sample         51.905           ms/op
ClientSimple.existUser                      sample  17441   1.831 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.650           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.692           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.465           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.156           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.794           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.946           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.958           ms/op
ClientSimple.getUser                        sample  14914   2.142 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.540           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.075           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.879           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.350           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.140           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.751           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.138           ms/op
ClientSimple.listUser                       sample   9494   3.367 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.206           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.461           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.046           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.001           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.832           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.832           ms/op

Benchmark result is saved to 1721607444564.json
