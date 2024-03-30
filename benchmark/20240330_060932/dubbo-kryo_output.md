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
# Warmup Iteration   1: 1.812 ops/ms
Iteration   1: 7.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.344 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.030 ops/ms
Iteration   1: 13.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.636 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.992 ops/ms
Iteration   1: 11.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.704 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.915 ops/ms
Iteration   1: 9.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.411 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.518 ±(99.9%) 0.073 ms/op
Iteration   1: 1.997 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.997 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.040 ±(99.9%) 0.047 ms/op
Iteration   1: 1.777 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.777 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.623 ±(99.9%) 0.072 ms/op
Iteration   1: 1.913 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.913 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.548 ±(99.9%) 0.077 ms/op
Iteration   1: 3.464 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.464 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.440 ±(99.9%) 0.080 ms/op
Iteration   1: 2.227 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   2.126 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.953 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  13.337 ms/op
                 createUser·p0.9999: 27.027 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14344
  mean =      2.227 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12035 
    [ 2.500,  5.000) = 2135 
    [ 5.000,  7.500) = 79 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     27.027 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.891 ±(99.9%) 0.058 ms/op
Iteration   1: 1.752 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   1.655 ms/op
                 existUser·p0.90:   2.046 ms/op
                 existUser·p0.95:   2.200 ms/op
                 existUser·p0.99:   3.160 ms/op
                 existUser·p0.999:  17.596 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18243
  mean =      1.752 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 265 
    [ 1.250,  2.500) = 17646 
    [ 2.500,  3.750) = 168 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      1.655 ms/op
     p(90.0000) =      2.046 ms/op
     p(95.0000) =      2.200 ms/op
     p(99.0000) =      3.160 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.359 ±(99.9%) 0.081 ms/op
Iteration   1: 2.030 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   1.935 ms/op
                 getUser·p0.90:   2.441 ms/op
                 getUser·p0.95:   2.585 ms/op
                 getUser·p0.99:   2.982 ms/op
                 getUser·p0.999:  14.483 ms/op
                 getUser·p0.9999: 15.464 ms/op
                 getUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15717
  mean =      2.030 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 14254 
    [ 2.500,  3.750) = 1256 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      2.982 ms/op
     p(99.9000) =     14.483 ms/op
     p(99.9900) =     15.464 ms/op
     p(99.9990) =     15.614 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.469 ±(99.9%) 0.132 ms/op
Iteration   1: 3.375 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.387 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.813 ms/op
                 listUser·p0.999:  7.679 ms/op
                 listUser·p0.9999: 8.323 ms/op
                 listUser·p1.00:   8.323 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9544
  mean =      3.375 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 16 
    [1.500, 2.000) = 92 
    [2.000, 2.500) = 1098 
    [2.500, 3.000) = 2042 
    [3.000, 3.500) = 1983 
    [3.500, 4.000) = 2494 
    [4.000, 4.500) = 1355 
    [4.500, 5.000) = 263 
    [5.000, 5.500) = 78 
    [5.500, 6.000) = 62 
    [6.000, 6.500) = 29 
    [6.500, 7.000) = 19 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 6 
    [8.000, 8.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.813 ms/op
     p(99.9000) =      7.679 ms/op
     p(99.9900) =      8.323 ms/op
     p(99.9990) =      8.323 ms/op
     p(99.9999) =      8.323 ms/op
    p(100.0000) =      8.323 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.344          ops/ms
ClientSimple.existUser                       thrpt         13.636          ops/ms
ClientSimple.getUser                         thrpt         11.704          ops/ms
ClientSimple.listUser                        thrpt          9.411          ops/ms
ClientSimple.createUser                       avgt          1.997           ms/op
ClientSimple.existUser                        avgt          1.777           ms/op
ClientSimple.getUser                          avgt          1.913           ms/op
ClientSimple.listUser                         avgt          3.464           ms/op
ClientSimple.createUser                     sample  14344   2.227 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.866           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.126           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.439           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.337           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.027           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.197           ms/op
ClientSimple.existUser                      sample  18243   1.752 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.664           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.655           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.046           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.200           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.160           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.596           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.727           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.727           ms/op
ClientSimple.getUser                        sample  15717   2.030 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.599           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.935           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.441           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.982           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.483           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.464           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.614           ms/op
ClientSimple.listUser                       sample   9544   3.375 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.118           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.387           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.813           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.679           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.323           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.323           ms/op

Benchmark result is saved to 1711778693746.json
