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
# Warmup Iteration   1: 1.547 ops/ms
Iteration   1: 7.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.675 ops/ms


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
# Warmup Iteration   1: 6.040 ops/ms
Iteration   1: 13.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.256 ops/ms


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
# Warmup Iteration   1: 4.620 ops/ms
Iteration   1: 10.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.427 ops/ms


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
# Warmup Iteration   1: 4.325 ops/ms
Iteration   1: 7.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.426 ops/ms


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.088 ms/op
Iteration   1: 2.212 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.212 ms/op


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
# Warmup Iteration   1: 2.958 ±(99.9%) 0.053 ms/op
Iteration   1: 1.807 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.807 ms/op


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
# Warmup Iteration   1: 3.371 ±(99.9%) 0.065 ms/op
Iteration   1: 1.974 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.974 ms/op


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
# Warmup Iteration   1: 4.334 ±(99.9%) 0.080 ms/op
Iteration   1: 3.353 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.353 ms/op


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
# Warmup Iteration   1: 3.436 ±(99.9%) 0.089 ms/op
Iteration   1: 1.969 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.487 ms/op
                 createUser·p0.50:   1.757 ms/op
                 createUser·p0.90:   2.347 ms/op
                 createUser·p0.95:   2.650 ms/op
                 createUser·p0.99:   9.783 ms/op
                 createUser·p0.999:  17.695 ms/op
                 createUser·p0.9999: 18.651 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16077
  mean =      1.969 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 454 
    [ 1.250,  2.500) = 14533 
    [ 2.500,  3.750) = 705 
    [ 3.750,  5.000) = 133 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      9.783 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     18.651 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 3.092 ±(99.9%) 0.079 ms/op
Iteration   1: 1.931 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   1.798 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.577 ms/op
                 existUser·p0.99:   3.385 ms/op
                 existUser·p0.999:  21.234 ms/op
                 existUser·p0.9999: 21.594 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16557
  mean =      1.931 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15447 
    [ 2.500,  5.000) = 1044 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.577 ms/op
     p(99.0000) =      3.385 ms/op
     p(99.9000) =     21.234 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.123 ms/op
Iteration   1: 2.108 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   2.032 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   2.855 ms/op
                 getUser·p0.99:   4.716 ms/op
                 getUser·p0.999:  12.269 ms/op
                 getUser·p0.9999: 12.705 ms/op
                 getUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15167
  mean =      2.108 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 277 
    [ 1.250,  2.500) = 12732 
    [ 2.500,  3.750) = 1877 
    [ 3.750,  5.000) = 183 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      4.716 ms/op
     p(99.9000) =     12.269 ms/op
     p(99.9900) =     12.705 ms/op
     p(99.9990) =     12.730 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


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
# Warmup Iteration   1: 4.433 ±(99.9%) 0.119 ms/op
Iteration   1: 3.777 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.504 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.440 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8483
  mean =      3.777 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 680 
    [ 2.500,  3.750) = 3447 
    [ 3.750,  5.000) = 3974 
    [ 5.000,  6.250) = 199 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.440 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.675          ops/ms
ClientSimple.existUser                       thrpt         13.256          ops/ms
ClientSimple.getUser                         thrpt         10.427          ops/ms
ClientSimple.listUser                        thrpt          7.426          ops/ms
ClientSimple.createUser                       avgt          2.212           ms/op
ClientSimple.existUser                        avgt          1.807           ms/op
ClientSimple.getUser                          avgt          1.974           ms/op
ClientSimple.listUser                         avgt          3.353           ms/op
ClientSimple.createUser                     sample  16077   1.969 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.487           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.757           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.347           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.650           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.783           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.695           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.651           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.711           ms/op
ClientSimple.existUser                      sample  16557   1.931 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.608           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.798           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.577           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.385           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.234           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.594           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.594           ms/op
ClientSimple.getUser                        sample  15167   2.108 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.660           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.032           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.716           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.269           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.705           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.730           ms/op
ClientSimple.listUser                       sample   8483   3.777 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.504           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.768           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.440           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.564           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.071           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.071           ms/op

Benchmark result is saved to 1711865086617.json
