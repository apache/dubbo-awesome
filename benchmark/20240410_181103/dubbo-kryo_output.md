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
# Warmup Iteration   1: 1.589 ops/ms
Iteration   1: 6.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.015 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.390 ops/ms
Iteration   1: 11.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.829 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.146 ops/ms
Iteration   1: 10.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.567 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.723 ops/ms
Iteration   1: 7.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.695 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.732 ±(99.9%) 0.100 ms/op
Iteration   1: 2.311 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.311 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.171 ±(99.9%) 0.077 ms/op
Iteration   1: 2.133 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.133 ms/op


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
# Warmup Iteration   1: 3.392 ±(99.9%) 0.062 ms/op
Iteration   1: 1.875 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.875 ms/op


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
# Warmup Iteration   1: 4.843 ±(99.9%) 0.101 ms/op
Iteration   1: 3.170 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.170 ms/op


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
# Warmup Iteration   1: 3.532 ±(99.9%) 0.085 ms/op
Iteration   1: 2.317 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.595 ms/op
                 createUser·p0.50:   2.103 ms/op
                 createUser·p0.90:   2.793 ms/op
                 createUser·p0.95:   3.739 ms/op
                 createUser·p0.99:   7.040 ms/op
                 createUser·p0.999:  13.307 ms/op
                 createUser·p0.9999: 13.658 ms/op
                 createUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13804
  mean =      2.317 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 10945 
    [ 2.500,  3.750) = 2088 
    [ 3.750,  5.000) = 344 
    [ 5.000,  6.250) = 170 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      2.103 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      3.739 ms/op
     p(99.0000) =      7.040 ms/op
     p(99.9000) =     13.307 ms/op
     p(99.9900) =     13.658 ms/op
     p(99.9990) =     13.795 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.075 ms/op
Iteration   1: 2.130 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   2.001 ms/op
                 existUser·p0.90:   2.552 ms/op
                 existUser·p0.95:   2.736 ms/op
                 existUser·p0.99:   4.736 ms/op
                 existUser·p0.999:  28.279 ms/op
                 existUser·p0.9999: 28.588 ms/op
                 existUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15164
  mean =      2.130 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13308 
    [ 2.500,  5.000) = 1758 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      4.736 ms/op
     p(99.9000) =     28.279 ms/op
     p(99.9900) =     28.588 ms/op
     p(99.9990) =     28.639 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 3.550 ±(99.9%) 0.093 ms/op
Iteration   1: 2.130 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   2.046 ms/op
                 getUser·p0.90:   2.703 ms/op
                 getUser·p0.95:   2.970 ms/op
                 getUser·p0.99:   4.554 ms/op
                 getUser·p0.999:  21.398 ms/op
                 getUser·p0.9999: 21.987 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15004
  mean =      2.130 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12271 
    [ 2.500,  5.000) = 2606 
    [ 5.000,  7.500) = 84 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      4.554 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 5.166 ±(99.9%) 0.215 ms/op
Iteration   1: 3.606 ±(99.9%) 0.056 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.461 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  19.697 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8886
  mean =      3.606 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 672 
    [ 2.500,  5.000) = 7831 
    [ 5.000,  7.500) = 264 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     19.697 ms/op
     p(99.9900) =     20.120 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.015          ops/ms
ClientSimple.existUser                       thrpt         11.829          ops/ms
ClientSimple.getUser                         thrpt         10.567          ops/ms
ClientSimple.listUser                        thrpt          7.695          ops/ms
ClientSimple.createUser                       avgt          2.311           ms/op
ClientSimple.existUser                        avgt          2.133           ms/op
ClientSimple.getUser                          avgt          1.875           ms/op
ClientSimple.listUser                         avgt          3.170           ms/op
ClientSimple.createUser                     sample  13804   2.317 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.595           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.103           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.739           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.040           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.307           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.658           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.795           ms/op
ClientSimple.existUser                      sample  15164   2.130 ± 0.040   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.543           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.001           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.552           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.736           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.736           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.279           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.588           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.639           ms/op
ClientSimple.getUser                        sample  15004   2.130 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.545           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.046           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.970           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.554           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.398           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.987           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.217           ms/op
ClientSimple.listUser                       sample   8886   3.606 ± 0.056   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.278           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.461           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.799           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.697           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.120           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.120           ms/op

Benchmark result is saved to 1712772339720.json
