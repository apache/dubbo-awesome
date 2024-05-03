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
# Warmup Iteration   1: 2.021 ops/ms
Iteration   1: 7.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.382 ops/ms


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
# Warmup Iteration   1: 6.258 ops/ms
Iteration   1: 12.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.918 ops/ms


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
# Warmup Iteration   1: 6.375 ops/ms
Iteration   1: 13.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.357 ops/ms


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
# Warmup Iteration   1: 5.838 ops/ms
Iteration   1: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.225 ops/ms


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
# Warmup Iteration   1: 4.751 ±(99.9%) 0.084 ms/op
Iteration   1: 2.321 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.321 ms/op


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
# Warmup Iteration   1: 3.256 ±(99.9%) 0.055 ms/op
Iteration   1: 1.848 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.848 ms/op


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
# Warmup Iteration   1: 2.986 ±(99.9%) 0.050 ms/op
Iteration   1: 1.773 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.773 ms/op


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.120 ms/op
Iteration   1: 3.544 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.544 ms/op


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
# Warmup Iteration   1: 3.417 ±(99.9%) 0.076 ms/op
Iteration   1: 2.169 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   2.060 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.720 ms/op
                 createUser·p0.99:   7.851 ms/op
                 createUser·p0.999:  17.891 ms/op
                 createUser·p0.9999: 18.219 ms/op
                 createUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15067
  mean =      2.169 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 225 
    [ 1.250,  2.500) = 13192 
    [ 2.500,  3.750) = 1359 
    [ 3.750,  5.000) = 111 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      7.851 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 3.082 ±(99.9%) 0.083 ms/op
Iteration   1: 1.838 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.461 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.228 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  14.700 ms/op
                 existUser·p0.9999: 15.340 ms/op
                 existUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17396
  mean =      1.838 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 543 
    [ 1.250,  2.500) = 16228 
    [ 2.500,  3.750) = 491 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      3.478 ms/op
     p(99.9000) =     14.700 ms/op
     p(99.9900) =     15.340 ms/op
     p(99.9990) =     15.352 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.086 ms/op
Iteration   1: 2.183 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   0.565 ms/op
                 getUser·p0.50:   2.015 ms/op
                 getUser·p0.90:   2.499 ms/op
                 getUser·p0.95:   2.740 ms/op
                 getUser·p0.99:   3.930 ms/op
                 getUser·p0.999:  34.485 ms/op
                 getUser·p0.9999: 35.885 ms/op
                 getUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14804
  mean =      2.183 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13341 
    [ 2.500,  5.000) = 1344 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.930 ms/op
     p(99.9000) =     34.485 ms/op
     p(99.9900) =     35.885 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.143 ms/op
Iteration   1: 3.676 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.980 ms/op
                 listUser·p0.999:  7.451 ms/op
                 listUser·p0.9999: 7.692 ms/op
                 listUser·p1.00:   7.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8703
  mean =      3.676 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 20 
    [1.500, 2.000) = 63 
    [2.000, 2.500) = 139 
    [2.500, 3.000) = 806 
    [3.000, 3.500) = 2120 
    [3.500, 4.000) = 3354 
    [4.000, 4.500) = 1715 
    [4.500, 5.000) = 274 
    [5.000, 5.500) = 65 
    [5.500, 6.000) = 65 
    [6.000, 6.500) = 71 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =      7.451 ms/op
     p(99.9900) =      7.692 ms/op
     p(99.9990) =      7.692 ms/op
     p(99.9999) =      7.692 ms/op
    p(100.0000) =      7.692 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.382          ops/ms
ClientSimple.existUser                       thrpt         12.918          ops/ms
ClientSimple.getUser                         thrpt         13.357          ops/ms
ClientSimple.listUser                        thrpt          8.225          ops/ms
ClientSimple.createUser                       avgt          2.321           ms/op
ClientSimple.existUser                        avgt          1.848           ms/op
ClientSimple.getUser                          avgt          1.773           ms/op
ClientSimple.listUser                         avgt          3.544           ms/op
ClientSimple.createUser                     sample  15067   2.169 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.745           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.060           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.851           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.891           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.219           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.252           ms/op
ClientSimple.existUser                      sample  17396   1.838 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.461           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.761           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.228           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.478           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.700           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.340           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.352           ms/op
ClientSimple.getUser                        sample  14804   2.183 ± 0.044   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.565           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.015           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.930           ms/op
ClientSimple.getUser:getUser·p0.999         sample         34.485           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         35.885           ms/op
ClientSimple.getUser:getUser·p1.00          sample         35.979           ms/op
ClientSimple.listUser                       sample   8703   3.676 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.241           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.674           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.980           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.451           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.692           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.692           ms/op

Benchmark result is saved to 1714737956840.json
