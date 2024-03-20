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
# Warmup Iteration   1: 1.573 ops/ms
Iteration   1: 6.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.153 ops/ms


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
# Warmup Iteration   1: 5.914 ops/ms
Iteration   1: 13.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.796 ops/ms


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
# Warmup Iteration   1: 5.451 ops/ms
Iteration   1: 12.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.396 ops/ms


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
# Warmup Iteration   1: 5.618 ops/ms
Iteration   1: 8.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.795 ops/ms


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.085 ms/op
Iteration   1: 2.105 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.105 ms/op


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
# Warmup Iteration   1: 3.394 ±(99.9%) 0.079 ms/op
Iteration   1: 1.904 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.904 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.064 ms/op
Iteration   1: 1.928 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.928 ms/op


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.127 ms/op
Iteration   1: 3.503 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.503 ms/op


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
# Warmup Iteration   1: 3.541 ±(99.9%) 0.086 ms/op
Iteration   1: 2.233 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.348 ms/op
                 createUser·p0.50:   2.038 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   8.943 ms/op
                 createUser·p0.999:  23.331 ms/op
                 createUser·p0.9999: 27.449 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14413
  mean =      2.233 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12372 
    [ 2.500,  5.000) = 1723 
    [ 5.000,  7.500) = 125 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.348 ms/op
     p(50.0000) =      2.038 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      8.943 ms/op
     p(99.9000) =     23.331 ms/op
     p(99.9900) =     27.449 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 3.291 ±(99.9%) 0.076 ms/op
Iteration   1: 2.092 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   2.019 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   3.954 ms/op
                 existUser·p0.999:  15.647 ms/op
                 existUser·p0.9999: 16.533 ms/op
                 existUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15363
  mean =      2.092 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 316 
    [ 1.250,  2.500) = 12711 
    [ 2.500,  3.750) = 2169 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.954 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     16.533 ms/op
     p(99.9990) =     16.630 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 3.226 ±(99.9%) 0.080 ms/op
Iteration   1: 2.174 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.060 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   2.917 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  11.289 ms/op
                 getUser·p0.9999: 11.471 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14734
  mean =      2.174 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 12523 
    [ 2.500,  3.750) = 1742 
    [ 3.750,  5.000) = 141 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.917 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     11.471 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


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
# Warmup Iteration   1: 4.951 ±(99.9%) 0.186 ms/op
Iteration   1: 3.745 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.014 ms/op
                 listUser·p0.999:  21.266 ms/op
                 listUser·p0.9999: 22.544 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8525
  mean =      3.745 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 352 
    [ 2.500,  5.000) = 7822 
    [ 5.000,  7.500) = 259 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      8.014 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.153          ops/ms
ClientSimple.existUser                       thrpt         13.796          ops/ms
ClientSimple.getUser                         thrpt         12.396          ops/ms
ClientSimple.listUser                        thrpt          8.795          ops/ms
ClientSimple.createUser                       avgt          2.105           ms/op
ClientSimple.existUser                        avgt          1.904           ms/op
ClientSimple.getUser                          avgt          1.928           ms/op
ClientSimple.listUser                         avgt          3.503           ms/op
ClientSimple.createUser                     sample  14413   2.233 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.348           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.038           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.943           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.331           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.449           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.492           ms/op
ClientSimple.existUser                      sample  15363   2.092 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.655           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.019           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.954           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.647           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.533           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.630           ms/op
ClientSimple.getUser                        sample  14734   2.174 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.613           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.060           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.917           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.497           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.289           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.471           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.518           ms/op
ClientSimple.listUser                       sample   8525   3.745 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.785           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.604           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.014           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.266           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.544           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.544           ms/op

Benchmark result is saved to 1710914716674.json
