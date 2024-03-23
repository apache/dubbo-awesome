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
# Warmup Iteration   1: 1.492 ops/ms
Iteration   1: 6.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.086 ops/ms


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
# Warmup Iteration   1: 6.206 ops/ms
Iteration   1: 11.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.553 ops/ms


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
# Warmup Iteration   1: 5.644 ops/ms
Iteration   1: 12.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.397 ops/ms


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
# Warmup Iteration   1: 4.905 ops/ms
Iteration   1: 8.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.440 ops/ms


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.064 ms/op
Iteration   1: 2.071 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.071 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.062 ms/op
Iteration   1: 2.089 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.089 ms/op


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
# Warmup Iteration   1: 3.213 ±(99.9%) 0.056 ms/op
Iteration   1: 1.966 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.966 ms/op


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
# Warmup Iteration   1: 4.463 ±(99.9%) 0.113 ms/op
Iteration   1: 3.507 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.507 ms/op


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
# Warmup Iteration   1: 3.763 ±(99.9%) 0.138 ms/op
Iteration   1: 2.243 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.535 ms/op
                 createUser·p0.50:   2.052 ms/op
                 createUser·p0.90:   2.676 ms/op
                 createUser·p0.95:   2.892 ms/op
                 createUser·p0.99:   6.628 ms/op
                 createUser·p0.999:  17.662 ms/op
                 createUser·p0.9999: 22.015 ms/op
                 createUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14287
  mean =      2.243 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11883 
    [ 2.500,  5.000) = 2098 
    [ 5.000,  7.500) = 203 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.052 ms/op
     p(90.0000) =      2.676 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      6.628 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     22.015 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 2.956 ±(99.9%) 0.067 ms/op
Iteration   1: 1.901 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   1.833 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   2.826 ms/op
                 existUser·p0.999:  27.531 ms/op
                 existUser·p0.9999: 28.157 ms/op
                 existUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16823
  mean =      1.901 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16150 
    [ 2.500,  5.000) = 635 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      2.826 ms/op
     p(99.9000) =     27.531 ms/op
     p(99.9900) =     28.157 ms/op
     p(99.9990) =     28.246 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 3.549 ±(99.9%) 0.112 ms/op
Iteration   1: 1.953 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   1.864 ms/op
                 getUser·p0.90:   2.232 ms/op
                 getUser·p0.95:   2.445 ms/op
                 getUser·p0.99:   3.216 ms/op
                 getUser·p0.999:  10.945 ms/op
                 getUser·p0.9999: 11.877 ms/op
                 getUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16361
  mean =      1.953 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 15635 
    [ 2.500,  3.750) = 606 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.445 ms/op
     p(99.0000) =      3.216 ms/op
     p(99.9000) =     10.945 ms/op
     p(99.9900) =     11.877 ms/op
     p(99.9990) =     11.960 ms/op
     p(99.9999) =     11.960 ms/op
    p(100.0000) =     11.960 ms/op


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.111 ms/op
Iteration   1: 3.801 ±(99.9%) 0.064 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  28.497 ms/op
                 listUser·p0.9999: 31.490 ms/op
                 listUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8478
  mean =      3.801 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 805 
    [ 2.500,  5.000) = 7149 
    [ 5.000,  7.500) = 458 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     28.497 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     31.490 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.086          ops/ms
ClientSimple.existUser                       thrpt         11.553          ops/ms
ClientSimple.getUser                         thrpt         12.397          ops/ms
ClientSimple.listUser                        thrpt          8.440          ops/ms
ClientSimple.createUser                       avgt          2.071           ms/op
ClientSimple.existUser                        avgt          2.089           ms/op
ClientSimple.getUser                          avgt          1.966           ms/op
ClientSimple.listUser                         avgt          3.507           ms/op
ClientSimple.createUser                     sample  14287   2.243 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.535           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.052           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.676           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.892           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.628           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.662           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.015           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.086           ms/op
ClientSimple.existUser                      sample  16823   1.901 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.482           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.833           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.310           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.826           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.531           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.157           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.246           ms/op
ClientSimple.getUser                        sample  16361   1.953 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.940           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.864           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.232           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.216           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.945           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.877           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.960           ms/op
ClientSimple.listUser                       sample   8478   3.801 ± 0.064   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.988           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.789           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.841           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.087           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.636           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.497           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.490           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.490           ms/op

Benchmark result is saved to 1711217094867.json
