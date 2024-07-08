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
# Warmup Iteration   1: 1.598 ops/ms
Iteration   1: 7.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.383 ops/ms


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
# Warmup Iteration   1: 6.153 ops/ms
Iteration   1: 11.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.862 ops/ms


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
# Warmup Iteration   1: 5.737 ops/ms
Iteration   1: 13.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.425 ops/ms


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
# Warmup Iteration   1: 5.967 ops/ms
Iteration   1: 8.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.994 ops/ms


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
# Warmup Iteration   1: 3.588 ±(99.9%) 0.064 ms/op
Iteration   1: 1.906 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.906 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.056 ms/op
Iteration   1: 1.723 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.723 ms/op


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
# Warmup Iteration   1: 3.408 ±(99.9%) 0.061 ms/op
Iteration   1: 1.993 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.993 ms/op


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.091 ms/op
Iteration   1: 3.481 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.481 ms/op


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.113 ms/op
Iteration   1: 2.226 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.502 ms/op
                 createUser·p0.50:   1.980 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   6.930 ms/op
                 createUser·p0.999:  34.144 ms/op
                 createUser·p0.9999: 35.294 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14560
  mean =      2.226 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12793 
    [ 2.500,  5.000) = 1560 
    [ 5.000,  7.500) = 71 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     34.144 ms/op
     p(99.9900) =     35.294 ms/op
     p(99.9990) =     35.324 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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
# Warmup Iteration   1: 3.142 ±(99.9%) 0.076 ms/op
Iteration   1: 1.730 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   1.655 ms/op
                 existUser·p0.90:   2.064 ms/op
                 existUser·p0.95:   2.208 ms/op
                 existUser·p0.99:   2.668 ms/op
                 existUser·p0.999:  12.248 ms/op
                 existUser·p0.9999: 12.408 ms/op
                 existUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18469
  mean =      1.730 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 368 
    [ 1.250,  2.500) = 17809 
    [ 2.500,  3.750) = 216 
    [ 3.750,  5.000) = 4 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      1.655 ms/op
     p(90.0000) =      2.064 ms/op
     p(95.0000) =      2.208 ms/op
     p(99.0000) =      2.668 ms/op
     p(99.9000) =     12.248 ms/op
     p(99.9900) =     12.408 ms/op
     p(99.9990) =     12.435 ms/op
     p(99.9999) =     12.435 ms/op
    p(100.0000) =     12.435 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.082 ms/op
Iteration   1: 1.915 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   1.790 ms/op
                 getUser·p0.90:   2.376 ms/op
                 getUser·p0.95:   2.617 ms/op
                 getUser·p0.99:   3.070 ms/op
                 getUser·p0.999:  14.762 ms/op
                 getUser·p0.9999: 15.453 ms/op
                 getUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16748
  mean =      1.915 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 15437 
    [ 2.500,  3.750) = 1119 
    [ 3.750,  5.000) = 16 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      1.790 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      3.070 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     15.453 ms/op
     p(99.9990) =     15.630 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.120 ms/op
Iteration   1: 3.099 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   2.830 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.266 ms/op
                 listUser·p0.99:   6.021 ms/op
                 listUser·p0.999:  15.264 ms/op
                 listUser·p0.9999: 15.925 ms/op
                 listUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10343
  mean =      3.099 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 2187 
    [ 2.500,  3.750) = 6723 
    [ 3.750,  5.000) = 1156 
    [ 5.000,  6.250) = 175 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.266 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     15.264 ms/op
     p(99.9900) =     15.925 ms/op
     p(99.9990) =     15.925 ms/op
     p(99.9999) =     15.925 ms/op
    p(100.0000) =     15.925 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.383          ops/ms
ClientSimple.existUser                       thrpt         11.862          ops/ms
ClientSimple.getUser                         thrpt         13.425          ops/ms
ClientSimple.listUser                        thrpt          8.994          ops/ms
ClientSimple.createUser                       avgt          1.906           ms/op
ClientSimple.existUser                        avgt          1.723           ms/op
ClientSimple.getUser                          avgt          1.993           ms/op
ClientSimple.listUser                         avgt          3.481           ms/op
ClientSimple.createUser                     sample  14560   2.226 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.502           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.980           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.930           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.144           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.294           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.324           ms/op
ClientSimple.existUser                      sample  18469   1.730 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.534           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.655           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.064           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.208           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.668           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.248           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.408           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.435           ms/op
ClientSimple.getUser                        sample  16748   1.915 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.777           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.790           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.070           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.762           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.453           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.630           ms/op
ClientSimple.listUser                       sample  10343   3.099 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.898           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.830           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.879           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.266           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.021           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.264           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.925           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.925           ms/op

Benchmark result is saved to 1720418766689.json
