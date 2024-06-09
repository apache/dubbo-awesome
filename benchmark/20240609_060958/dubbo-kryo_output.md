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
# Warmup Iteration   1: 1.531 ops/ms
Iteration   1: 6.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.900 ops/ms


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
# Warmup Iteration   1: 5.344 ops/ms
Iteration   1: 12.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.956 ops/ms


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
# Warmup Iteration   1: 5.508 ops/ms
Iteration   1: 12.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.389 ops/ms


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
# Warmup Iteration   1: 4.837 ops/ms
Iteration   1: 9.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.056 ops/ms


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
# Warmup Iteration   1: 4.253 ±(99.9%) 0.096 ms/op
Iteration   1: 2.054 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.054 ms/op


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
# Warmup Iteration   1: 3.040 ±(99.9%) 0.061 ms/op
Iteration   1: 1.755 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.755 ms/op


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
# Warmup Iteration   1: 3.519 ±(99.9%) 0.057 ms/op
Iteration   1: 2.325 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.325 ms/op


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.093 ms/op
Iteration   1: 3.252 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.252 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.079 ms/op
Iteration   1: 2.242 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.388 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.391 ms/op
                 createUser·p0.99:   11.633 ms/op
                 createUser·p0.999:  15.221 ms/op
                 createUser·p0.9999: 15.710 ms/op
                 createUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14324
  mean =      2.242 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 369 
    [ 1.250,  2.500) = 10849 
    [ 2.500,  3.750) = 2654 
    [ 3.750,  5.000) = 150 
    [ 5.000,  6.250) = 99 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.391 ms/op
     p(99.0000) =     11.633 ms/op
     p(99.9000) =     15.221 ms/op
     p(99.9900) =     15.710 ms/op
     p(99.9990) =     15.909 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


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
# Warmup Iteration   1: 3.047 ±(99.9%) 0.074 ms/op
Iteration   1: 1.901 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.453 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.593 ms/op
                 existUser·p0.99:   3.830 ms/op
                 existUser·p0.999:  18.579 ms/op
                 existUser·p0.9999: 18.763 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17004
  mean =      1.901 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2056 
    [ 1.250,  2.500) = 13803 
    [ 2.500,  3.750) = 964 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     18.763 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.095 ms/op
Iteration   1: 1.758 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.459 ms/op
                 getUser·p0.50:   1.642 ms/op
                 getUser·p0.90:   2.195 ms/op
                 getUser·p0.95:   2.413 ms/op
                 getUser·p0.99:   3.100 ms/op
                 getUser·p0.999:  12.531 ms/op
                 getUser·p0.9999: 12.842 ms/op
                 getUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18174
  mean =      1.758 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 288 
    [ 1.250,  2.500) = 17204 
    [ 2.500,  3.750) = 567 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      1.642 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.413 ms/op
     p(99.0000) =      3.100 ms/op
     p(99.9000) =     12.531 ms/op
     p(99.9900) =     12.842 ms/op
     p(99.9990) =     12.976 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


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
# Warmup Iteration   1: 4.989 ±(99.9%) 0.155 ms/op
Iteration   1: 3.753 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.835 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 15.221 ms/op
                 listUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8514
  mean =      3.753 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 339 
    [ 2.500,  3.750) = 3875 
    [ 3.750,  5.000) = 3930 
    [ 5.000,  6.250) = 272 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.835 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     14.975 ms/op
     p(99.9900) =     15.221 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.900          ops/ms
ClientSimple.existUser                       thrpt         12.956          ops/ms
ClientSimple.getUser                         thrpt         12.389          ops/ms
ClientSimple.listUser                        thrpt          9.056          ops/ms
ClientSimple.createUser                       avgt          2.054           ms/op
ClientSimple.existUser                        avgt          1.755           ms/op
ClientSimple.getUser                          avgt          2.325           ms/op
ClientSimple.listUser                         avgt          3.252           ms/op
ClientSimple.createUser                     sample  14324   2.242 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.388           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.391           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.633           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.221           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.710           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.909           ms/op
ClientSimple.existUser                      sample  17004   1.901 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.453           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.835           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.830           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.579           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.763           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.809           ms/op
ClientSimple.getUser                        sample  18174   1.758 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.459           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.642           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.195           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.100           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.531           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.842           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.976           ms/op
ClientSimple.listUser                       sample   8514   3.753 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.264           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.760           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.835           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.636           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.975           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.221           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.221           ms/op

Benchmark result is saved to 1717913133880.json
