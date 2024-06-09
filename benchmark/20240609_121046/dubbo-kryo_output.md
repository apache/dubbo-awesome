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
# Warmup Iteration   1: 0.858 ops/ms
Iteration   1: 5.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.740 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 6.096 ops/ms
Iteration   1: 12.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.508 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.481 ops/ms
Iteration   1: 12.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.264 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.463 ops/ms
Iteration   1: 8.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.390 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.969 ±(99.9%) 0.072 ms/op
Iteration   1: 2.073 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.073 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.050 ms/op
Iteration   1: 2.078 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.078 ms/op


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
# Warmup Iteration   1: 3.406 ±(99.9%) 0.072 ms/op
Iteration   1: 2.202 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.202 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.092 ms/op
Iteration   1: 3.523 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.523 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.100 ms/op
Iteration   1: 2.436 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.432 ms/op
                 createUser·p0.50:   2.163 ms/op
                 createUser·p0.90:   2.925 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 19.104 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13136
  mean =      2.436 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 9907 
    [ 2.500,  3.750) = 2638 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      2.163 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.082 ms/op
Iteration   1: 2.019 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.343 ms/op
                 existUser·p0.50:   1.903 ms/op
                 existUser·p0.90:   2.384 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  17.830 ms/op
                 existUser·p0.9999: 18.598 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15860
  mean =      2.019 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 14583 
    [ 2.500,  3.750) = 850 
    [ 3.750,  5.000) = 143 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =     17.830 ms/op
     p(99.9900) =     18.598 ms/op
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
# Warmup Iteration   1: 3.522 ±(99.9%) 0.083 ms/op
Iteration   1: 2.066 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   1.987 ms/op
                 getUser·p0.90:   2.531 ms/op
                 getUser·p0.95:   2.724 ms/op
                 getUser·p0.99:   3.387 ms/op
                 getUser·p0.999:  12.632 ms/op
                 getUser·p0.9999: 14.526 ms/op
                 getUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15701
  mean =      2.066 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 13815 
    [ 2.500,  3.750) = 1715 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      3.387 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     14.526 ms/op
     p(99.9990) =     16.712 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 5.064 ±(99.9%) 0.151 ms/op
Iteration   1: 3.557 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.178 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   6.844 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9029
  mean =      3.557 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 400 
    [ 2.500,  3.750) = 5829 
    [ 3.750,  5.000) = 2405 
    [ 5.000,  6.250) = 279 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.844 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     18.481 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.740          ops/ms
ClientSimple.existUser                       thrpt         12.508          ops/ms
ClientSimple.getUser                         thrpt         12.264          ops/ms
ClientSimple.listUser                        thrpt          8.390          ops/ms
ClientSimple.createUser                       avgt          2.073           ms/op
ClientSimple.existUser                        avgt          2.078           ms/op
ClientSimple.getUser                          avgt          2.202           ms/op
ClientSimple.listUser                         avgt          3.523           ms/op
ClientSimple.createUser                     sample  13136   2.436 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.432           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.163           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.925           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.269           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.191           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.990           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.104           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.104           ms/op
ClientSimple.existUser                      sample  15860   2.019 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.343           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.903           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.998           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.830           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.598           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.809           ms/op
ClientSimple.getUser                        sample  15701   2.066 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.851           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.987           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.724           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.387           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.632           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.526           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.712           ms/op
ClientSimple.listUser                       sample   9029   3.557 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.014           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.178           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.844           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.153           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.481           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.481           ms/op

Benchmark result is saved to 1717934806601.json
