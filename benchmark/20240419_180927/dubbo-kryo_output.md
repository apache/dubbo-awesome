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
# Warmup Iteration   1: 1.531 ops/ms
Iteration   1: 7.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.164 ops/ms


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
# Warmup Iteration   1: 5.889 ops/ms
Iteration   1: 12.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.537 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.456 ops/ms
Iteration   1: 13.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.191 ops/ms


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
# Warmup Iteration   1: 4.469 ops/ms
Iteration   1: 8.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.055 ops/ms


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.068 ms/op
Iteration   1: 2.112 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.112 ms/op


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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.054 ms/op
Iteration   1: 2.034 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.034 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.056 ms/op
Iteration   1: 2.102 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.102 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.246 ±(99.9%) 0.097 ms/op
Iteration   1: 3.329 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.329 ms/op


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
# Warmup Iteration   1: 3.521 ±(99.9%) 0.094 ms/op
Iteration   1: 2.171 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   1.997 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.801 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  18.973 ms/op
                 createUser·p0.9999: 23.734 ms/op
                 createUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14720
  mean =      2.171 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13149 
    [ 2.500,  5.000) = 1366 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.801 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     23.734 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.081 ms/op
Iteration   1: 1.852 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   1.679 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.603 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  26.018 ms/op
                 existUser·p0.9999: 26.232 ms/op
                 existUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17250
  mean =      1.852 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16148 
    [ 2.500,  5.000) = 1017 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.603 ms/op
     p(99.0000) =      3.363 ms/op
     p(99.9000) =     26.018 ms/op
     p(99.9900) =     26.232 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.085 ms/op
Iteration   1: 2.264 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   2.200 ms/op
                 getUser·p0.90:   2.859 ms/op
                 getUser·p0.95:   3.019 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  15.557 ms/op
                 getUser·p0.9999: 16.506 ms/op
                 getUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14115
  mean =      2.264 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 382 
    [ 1.250,  2.500) = 9640 
    [ 2.500,  3.750) = 3880 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.200 ms/op
     p(90.0000) =      2.859 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =     15.557 ms/op
     p(99.9900) =     16.506 ms/op
     p(99.9990) =     16.695 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.170 ms/op
Iteration   1: 3.988 ±(99.9%) 0.076 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.036 ms/op
                 listUser·p0.999:  34.668 ms/op
                 listUser·p0.9999: 35.324 ms/op
                 listUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8014
  mean =      3.988 ±(99.9%) 0.076 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 315 
    [ 2.500,  5.000) = 7310 
    [ 5.000,  7.500) = 356 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.036 ms/op
     p(99.9000) =     34.668 ms/op
     p(99.9900) =     35.324 ms/op
     p(99.9990) =     35.324 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.164          ops/ms
ClientSimple.existUser                       thrpt         12.537          ops/ms
ClientSimple.getUser                         thrpt         13.191          ops/ms
ClientSimple.listUser                        thrpt          8.055          ops/ms
ClientSimple.createUser                       avgt          2.112           ms/op
ClientSimple.existUser                        avgt          2.034           ms/op
ClientSimple.getUser                          avgt          2.102           ms/op
ClientSimple.listUser                         avgt          3.329           ms/op
ClientSimple.createUser                     sample  14720   2.171 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.739           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.997           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.801           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.103           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.973           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.734           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.230           ms/op
ClientSimple.existUser                      sample  17250   1.852 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.614           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.679           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.603           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.363           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.018           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.232           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.280           ms/op
ClientSimple.getUser                        sample  14115   2.264 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.638           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.200           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.019           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.301           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.557           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.506           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.695           ms/op
ClientSimple.listUser                       sample   8014   3.988 ± 0.076   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.147           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.916           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.768           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.036           ms/op
ClientSimple.listUser:listUser·p0.999       sample         34.668           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         35.324           ms/op
ClientSimple.listUser:listUser·p1.00        sample         35.324           ms/op

Benchmark result is saved to 1713549874218.json
