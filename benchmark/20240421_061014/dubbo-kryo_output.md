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
# Warmup Iteration   1: 1.607 ops/ms
Iteration   1: 6.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.792 ops/ms


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
# Warmup Iteration   1: 5.793 ops/ms
Iteration   1: 11.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.917 ops/ms


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
# Warmup Iteration   1: 5.440 ops/ms
Iteration   1: 11.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.402 ops/ms


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
# Warmup Iteration   1: 5.173 ops/ms
Iteration   1: 8.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.116 ops/ms


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
# Warmup Iteration   1: 4.162 ±(99.9%) 0.126 ms/op
Iteration   1: 2.488 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.488 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.003 ±(99.9%) 0.053 ms/op
Iteration   1: 1.730 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.730 ms/op


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
# Warmup Iteration   1: 3.464 ±(99.9%) 0.062 ms/op
Iteration   1: 2.105 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.933 ±(99.9%) 0.109 ms/op
Iteration   1: 3.111 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.111 ms/op


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
# Warmup Iteration   1: 3.365 ±(99.9%) 0.083 ms/op
Iteration   1: 2.156 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.589 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.806 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   6.336 ms/op
                 createUser·p0.999:  25.695 ms/op
                 createUser·p0.9999: 26.461 ms/op
                 createUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14851
  mean =      2.156 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12550 
    [ 2.500,  5.000) = 2108 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      6.336 ms/op
     p(99.9000) =     25.695 ms/op
     p(99.9900) =     26.461 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 2.910 ±(99.9%) 0.073 ms/op
Iteration   1: 1.845 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   1.729 ms/op
                 existUser·p0.90:   2.216 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  16.679 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17325
  mean =      1.845 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 430 
    [ 1.250,  2.500) = 16267 
    [ 2.500,  3.750) = 445 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.106 ms/op
Iteration   1: 1.972 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.408 ms/op
                 getUser·p0.50:   1.882 ms/op
                 getUser·p0.90:   2.511 ms/op
                 getUser·p0.95:   2.617 ms/op
                 getUser·p0.99:   2.953 ms/op
                 getUser·p0.999:  13.435 ms/op
                 getUser·p0.9999: 14.852 ms/op
                 getUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16215
  mean =      1.972 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 14398 
    [ 2.500,  3.750) = 1681 
    [ 3.750,  5.000) = 7 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      2.953 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     14.852 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 5.395 ±(99.9%) 0.187 ms/op
Iteration   1: 3.837 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.201 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  21.091 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8342
  mean =      3.837 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 442 
    [ 2.500,  5.000) = 7373 
    [ 5.000,  7.500) = 483 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.201 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     21.091 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.792          ops/ms
ClientSimple.existUser                       thrpt         11.917          ops/ms
ClientSimple.getUser                         thrpt         11.402          ops/ms
ClientSimple.listUser                        thrpt          8.116          ops/ms
ClientSimple.createUser                       avgt          2.488           ms/op
ClientSimple.existUser                        avgt          1.730           ms/op
ClientSimple.getUser                          avgt          2.105           ms/op
ClientSimple.listUser                         avgt          3.111           ms/op
ClientSimple.createUser                     sample  14851   2.156 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.589           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.154           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.336           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.695           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.461           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.477           ms/op
ClientSimple.existUser                      sample  17325   1.845 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.540           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.729           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.216           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.149           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.679           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.974           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.974           ms/op
ClientSimple.getUser                        sample  16215   1.972 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.408           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.882           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.953           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.435           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.852           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.893           ms/op
ClientSimple.listUser                       sample   8342   3.837 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.167           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.760           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.201           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.496           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.091           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.463           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.463           ms/op

Benchmark result is saved to 1713679544646.json
