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
# Warmup Iteration   1: 0.871 ops/ms
Iteration   1: 7.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.162 ops/ms


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
# Warmup Iteration   1: 6.336 ops/ms
Iteration   1: 12.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.114 ops/ms


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
# Warmup Iteration   1: 5.518 ops/ms
Iteration   1: 13.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.536 ops/ms


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
# Warmup Iteration   1: 5.102 ops/ms
Iteration   1: 8.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.234 ops/ms


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.068 ms/op
Iteration   1: 2.311 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.311 ms/op


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.057 ms/op
Iteration   1: 2.018 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.018 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.063 ms/op
Iteration   1: 2.015 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.015 ms/op


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.089 ms/op
Iteration   1: 3.644 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.644 ms/op


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
# Warmup Iteration   1: 3.371 ±(99.9%) 0.080 ms/op
Iteration   1: 2.029 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.391 ms/op
                 createUser·p0.50:   1.929 ms/op
                 createUser·p0.90:   2.408 ms/op
                 createUser·p0.95:   2.626 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  16.237 ms/op
                 createUser·p0.9999: 17.095 ms/op
                 createUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15780
  mean =      2.029 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 753 
    [ 1.250,  2.500) = 13918 
    [ 2.500,  3.750) = 839 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     16.237 ms/op
     p(99.9900) =     17.095 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 2.994 ±(99.9%) 0.071 ms/op
Iteration   1: 1.895 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.442 ms/op
                 existUser·p0.50:   1.870 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.646 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  15.228 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16865
  mean =      1.895 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15657 
    [ 2.500,  5.000) = 1149 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =     15.228 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 3.309 ±(99.9%) 0.088 ms/op
Iteration   1: 2.112 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   2.077 ms/op
                 getUser·p0.90:   2.585 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   3.281 ms/op
                 getUser·p0.999:  10.306 ms/op
                 getUser·p0.9999: 11.289 ms/op
                 getUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15417
  mean =      2.112 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 12971 
    [ 2.500,  3.750) = 2185 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.281 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     11.289 ms/op
     p(99.9990) =     11.289 ms/op
     p(99.9999) =     11.289 ms/op
    p(100.0000) =     11.289 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.233 ±(99.9%) 0.133 ms/op
Iteration   1: 2.964 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   2.798 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   4.777 ms/op
                 listUser·p0.999:  6.122 ms/op
                 listUser·p0.9999: 10.171 ms/op
                 listUser·p1.00:   10.174 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10788
  mean =      2.964 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 30 
    [ 2.000,  3.000) = 7700 
    [ 3.000,  4.000) = 2361 
    [ 4.000,  5.000) = 646 
    [ 5.000,  6.000) = 38 
    [ 6.000,  7.000) = 6 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      4.777 ms/op
     p(99.9000) =      6.122 ms/op
     p(99.9900) =     10.171 ms/op
     p(99.9990) =     10.174 ms/op
     p(99.9999) =     10.174 ms/op
    p(100.0000) =     10.174 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.162          ops/ms
ClientSimple.existUser                       thrpt         12.114          ops/ms
ClientSimple.getUser                         thrpt         13.536          ops/ms
ClientSimple.listUser                        thrpt          8.234          ops/ms
ClientSimple.createUser                       avgt          2.311           ms/op
ClientSimple.existUser                        avgt          2.018           ms/op
ClientSimple.getUser                          avgt          2.015           ms/op
ClientSimple.listUser                         avgt          3.644           ms/op
ClientSimple.createUser                     sample  15780   2.029 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.391           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.929           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.408           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.702           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.237           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.095           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.170           ms/op
ClientSimple.existUser                      sample  16865   1.895 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.442           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.870           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.646           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.785           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.228           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.233           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.233           ms/op
ClientSimple.getUser                        sample  15417   2.112 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.697           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.077           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.281           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.306           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.289           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.289           ms/op
ClientSimple.listUser                       sample  10788   2.964 ± 0.017   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.137           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.798           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.768           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.108           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.777           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.122           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.171           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.174           ms/op

Benchmark result is saved to 1711389936137.json
