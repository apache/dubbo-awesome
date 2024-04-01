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
# Warmup Iteration   1: 0.900 ops/ms
Iteration   1: 6.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.029 ops/ms


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
# Warmup Iteration   1: 6.013 ops/ms
Iteration   1: 11.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.779 ops/ms


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
# Warmup Iteration   1: 5.616 ops/ms
Iteration   1: 12.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.628 ops/ms


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
# Warmup Iteration   1: 4.511 ops/ms
Iteration   1: 8.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.470 ops/ms


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.079 ms/op
Iteration   1: 2.122 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.122 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.047 ms/op
Iteration   1: 1.877 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.877 ms/op


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
# Warmup Iteration   1: 3.441 ±(99.9%) 0.076 ms/op
Iteration   1: 2.285 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.285 ms/op


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.100 ms/op
Iteration   1: 2.914 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.914 ms/op


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
# Warmup Iteration   1: 3.606 ±(99.9%) 0.095 ms/op
Iteration   1: 2.129 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   1.939 ms/op
                 createUser·p0.90:   2.666 ms/op
                 createUser·p0.95:   2.871 ms/op
                 createUser·p0.99:   6.060 ms/op
                 createUser·p0.999:  20.414 ms/op
                 createUser·p0.9999: 23.297 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15027
  mean =      2.129 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12587 
    [ 2.500,  5.000) = 2245 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      6.060 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     23.297 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 2.936 ±(99.9%) 0.067 ms/op
Iteration   1: 2.067 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   1.987 ms/op
                 existUser·p0.90:   2.613 ms/op
                 existUser·p0.95:   2.761 ms/op
                 existUser·p0.99:   3.139 ms/op
                 existUser·p0.999:  15.033 ms/op
                 existUser·p0.9999: 15.213 ms/op
                 existUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15465
  mean =      2.067 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 286 
    [ 1.250,  2.500) = 12078 
    [ 2.500,  3.750) = 3014 
    [ 3.750,  5.000) = 5 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      3.139 ms/op
     p(99.9000) =     15.033 ms/op
     p(99.9900) =     15.213 ms/op
     p(99.9990) =     15.303 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 3.194 ±(99.9%) 0.107 ms/op
Iteration   1: 1.981 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.456 ms/op
                 getUser·p0.50:   1.898 ms/op
                 getUser·p0.90:   2.396 ms/op
                 getUser·p0.95:   2.597 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 11.113 ms/op
                 getUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16240
  mean =      1.981 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 235 
    [ 1.250,  2.500) = 14921 
    [ 2.500,  3.750) = 927 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     11.113 ms/op
     p(99.9990) =     11.174 ms/op
     p(99.9999) =     11.174 ms/op
    p(100.0000) =     11.174 ms/op


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.112 ms/op
Iteration   1: 3.204 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.371 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 14.598 ms/op
                 listUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10036
  mean =      3.204 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 833 
    [ 2.500,  3.750) = 7308 
    [ 3.750,  5.000) = 1762 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.371 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     14.598 ms/op
     p(99.9990) =     14.598 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.029          ops/ms
ClientSimple.existUser                       thrpt         11.779          ops/ms
ClientSimple.getUser                         thrpt         12.628          ops/ms
ClientSimple.listUser                        thrpt          8.470          ops/ms
ClientSimple.createUser                       avgt          2.122           ms/op
ClientSimple.existUser                        avgt          1.877           ms/op
ClientSimple.getUser                          avgt          2.285           ms/op
ClientSimple.listUser                         avgt          2.914           ms/op
ClientSimple.createUser                     sample  15027   2.129 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.528           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.939           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.666           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.060           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.414           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.297           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.396           ms/op
ClientSimple.existUser                      sample  15465   2.067 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.698           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.987           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.613           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.761           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.139           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.033           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.213           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.303           ms/op
ClientSimple.getUser                        sample  16240   1.981 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.456           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.898           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.396           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.699           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.026           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.113           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.174           ms/op
ClientSimple.listUser                       sample  10036   3.204 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.118           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.982           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.998           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.371           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.467           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.598           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.598           ms/op

Benchmark result is saved to 1711930608183.json
