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
# Warmup Iteration   1: 1.801 ops/ms
Iteration   1: 6.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.933 ops/ms


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
# Warmup Iteration   1: 5.656 ops/ms
Iteration   1: 11.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.973 ops/ms


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
# Warmup Iteration   1: 6.187 ops/ms
Iteration   1: 13.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.753 ops/ms


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
# Warmup Iteration   1: 5.120 ops/ms
Iteration   1: 9.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.064 ops/ms


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.110 ms/op
Iteration   1: 2.253 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.253 ms/op


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
# Warmup Iteration   1: 3.249 ±(99.9%) 0.055 ms/op
Iteration   1: 1.883 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.883 ms/op


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
# Warmup Iteration   1: 3.225 ±(99.9%) 0.067 ms/op
Iteration   1: 1.767 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.767 ms/op


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
# Warmup Iteration   1: 4.131 ±(99.9%) 0.086 ms/op
Iteration   1: 3.824 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.824 ms/op


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
# Warmup Iteration   1: 3.247 ±(99.9%) 0.085 ms/op
Iteration   1: 2.329 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.479 ms/op
                 createUser·p0.50:   2.159 ms/op
                 createUser·p0.90:   2.847 ms/op
                 createUser·p0.95:   3.446 ms/op
                 createUser·p0.99:   6.750 ms/op
                 createUser·p0.999:  14.111 ms/op
                 createUser·p0.9999: 18.658 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13734
  mean =      2.329 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 10760 
    [ 2.500,  3.750) = 2283 
    [ 3.750,  5.000) = 349 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.446 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     14.111 ms/op
     p(99.9900) =     18.658 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.089 ms/op
Iteration   1: 1.941 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   1.882 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   4.466 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 11.376 ms/op
                 existUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16482
  mean =      1.941 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 532 
    [ 1.250,  2.500) = 14952 
    [ 2.500,  3.750) = 817 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      4.466 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     11.376 ms/op
     p(99.9990) =     11.387 ms/op
     p(99.9999) =     11.387 ms/op
    p(100.0000) =     11.387 ms/op


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
# Warmup Iteration   1: 3.220 ±(99.9%) 0.078 ms/op
Iteration   1: 2.026 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.450 ms/op
                 getUser·p0.50:   1.935 ms/op
                 getUser·p0.90:   2.503 ms/op
                 getUser·p0.95:   2.630 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  14.221 ms/op
                 getUser·p0.9999: 14.916 ms/op
                 getUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15779
  mean =      2.026 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 249 
    [ 1.250,  2.500) = 13940 
    [ 2.500,  3.750) = 1377 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     14.916 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.374 ±(99.9%) 0.120 ms/op
Iteration   1: 3.000 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   2.736 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.187 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  12.130 ms/op
                 listUser·p0.9999: 12.285 ms/op
                 listUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10637
  mean =      3.000 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1742 
    [ 2.500,  3.750) = 7435 
    [ 3.750,  5.000) = 1301 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.769 ms/op
     p(50.0000) =      2.736 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.187 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     12.130 ms/op
     p(99.9900) =     12.285 ms/op
     p(99.9990) =     12.288 ms/op
     p(99.9999) =     12.288 ms/op
    p(100.0000) =     12.288 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.933          ops/ms
ClientSimple.existUser                       thrpt         11.973          ops/ms
ClientSimple.getUser                         thrpt         13.753          ops/ms
ClientSimple.listUser                        thrpt          9.064          ops/ms
ClientSimple.createUser                       avgt          2.253           ms/op
ClientSimple.existUser                        avgt          1.883           ms/op
ClientSimple.getUser                          avgt          1.767           ms/op
ClientSimple.listUser                         avgt          3.824           ms/op
ClientSimple.createUser                     sample  13734   2.329 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.479           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.159           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.446           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.750           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.111           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.658           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.842           ms/op
ClientSimple.existUser                      sample  16482   1.941 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.562           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.882           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.466           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.223           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.376           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.387           ms/op
ClientSimple.getUser                        sample  15779   2.026 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.450           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.935           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.325           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.221           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.916           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.926           ms/op
ClientSimple.listUser                       sample  10637   3.000 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.769           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.736           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.924           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.187           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.718           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.130           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.285           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.288           ms/op

Benchmark result is saved to 1716098718305.json
