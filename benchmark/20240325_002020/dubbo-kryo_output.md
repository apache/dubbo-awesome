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
# Warmup Iteration   1: 1.816 ops/ms
Iteration   1: 6.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.293 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.654 ops/ms
Iteration   1: 12.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.662 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.730 ops/ms
Iteration   1: 12.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.893 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.998 ops/ms
Iteration   1: 9.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.172 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ±(99.9%) 0.065 ms/op
Iteration   1: 2.045 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.045 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.210 ±(99.9%) 0.049 ms/op
Iteration   1: 1.763 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.763 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.375 ±(99.9%) 0.053 ms/op
Iteration   1: 2.097 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.097 ms/op


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
# Warmup Iteration   1: 5.338 ±(99.9%) 0.131 ms/op
Iteration   1: 3.190 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.190 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.047 ±(99.9%) 0.141 ms/op
Iteration   1: 2.368 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   2.232 ms/op
                 createUser·p0.90:   2.888 ms/op
                 createUser·p0.95:   3.274 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  16.408 ms/op
                 createUser·p0.9999: 18.554 ms/op
                 createUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13531
  mean =      2.368 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 9979 
    [ 2.500,  3.750) = 3112 
    [ 3.750,  5.000) = 253 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.274 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     16.408 ms/op
     p(99.9900) =     18.554 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.198 ±(99.9%) 0.089 ms/op
Iteration   1: 1.750 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   1.587 ms/op
                 existUser·p0.90:   2.236 ms/op
                 existUser·p0.95:   2.494 ms/op
                 existUser·p0.99:   3.228 ms/op
                 existUser·p0.999:  18.121 ms/op
                 existUser·p0.9999: 18.230 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18298
  mean =      1.750 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 496 
    [ 1.250,  2.500) = 16907 
    [ 2.500,  3.750) = 746 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      1.587 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      3.228 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     18.230 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.269 ±(99.9%) 0.085 ms/op
Iteration   1: 2.072 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   1.929 ms/op
                 getUser·p0.90:   2.515 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   5.136 ms/op
                 getUser·p0.999:  20.677 ms/op
                 getUser·p0.9999: 23.739 ms/op
                 getUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15439
  mean =      2.072 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13817 
    [ 2.500,  5.000) = 1453 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     23.739 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 4.315 ±(99.9%) 0.117 ms/op
Iteration   1: 3.321 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.755 ms/op
                 listUser·p0.50:   3.244 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.361 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9645
  mean =      3.321 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 948 
    [ 2.500,  5.000) = 8429 
    [ 5.000,  7.500) = 224 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.361 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.293          ops/ms
ClientSimple.existUser                       thrpt         12.662          ops/ms
ClientSimple.getUser                         thrpt         12.893          ops/ms
ClientSimple.listUser                        thrpt          9.172          ops/ms
ClientSimple.createUser                       avgt          2.045           ms/op
ClientSimple.existUser                        avgt          1.763           ms/op
ClientSimple.getUser                          avgt          2.097           ms/op
ClientSimple.listUser                         avgt          3.190           ms/op
ClientSimple.createUser                     sample  13531   2.368 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.021           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.232           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.274           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.128           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.408           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.554           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.612           ms/op
ClientSimple.existUser                      sample  18298   1.750 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.589           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.587           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.228           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.121           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.230           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.285           ms/op
ClientSimple.getUser                        sample  15439   2.072 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.706           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.929           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.136           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.677           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.739           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.757           ms/op
ClientSimple.listUser                       sample   9645   3.321 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.755           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.244           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.361           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.350           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.675           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.675           ms/op

Benchmark result is saved to 1711325738524.json
