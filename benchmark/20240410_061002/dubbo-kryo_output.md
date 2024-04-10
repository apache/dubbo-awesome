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
# Warmup Iteration   1: 1.801 ops/ms
Iteration   1: 6.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.470 ops/ms


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
# Warmup Iteration   1: 6.554 ops/ms
Iteration   1: 12.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.654 ops/ms


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
# Warmup Iteration   1: 6.168 ops/ms
Iteration   1: 11.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.657 ops/ms


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
# Warmup Iteration   1: 5.911 ops/ms
Iteration   1: 9.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.258 ops/ms


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
# Warmup Iteration   1: 3.608 ±(99.9%) 0.060 ms/op
Iteration   1: 2.078 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.078 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.050 ms/op
Iteration   1: 1.959 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.959 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.066 ms/op
Iteration   1: 1.901 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.901 ms/op


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
# Warmup Iteration   1: 6.514 ±(99.9%) 0.164 ms/op
Iteration   1: 3.233 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.233 ms/op


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.103 ms/op
Iteration   1: 2.066 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   1.880 ms/op
                 createUser·p0.90:   2.462 ms/op
                 createUser·p0.95:   2.720 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  12.983 ms/op
                 createUser·p0.9999: 13.155 ms/op
                 createUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15536
  mean =      2.066 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 14085 
    [ 2.500,  3.750) = 1060 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     12.983 ms/op
     p(99.9900) =     13.155 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


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
# Warmup Iteration   1: 3.173 ±(99.9%) 0.089 ms/op
Iteration   1: 2.063 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   1.985 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.732 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  14.680 ms/op
                 existUser·p0.9999: 14.769 ms/op
                 existUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15571
  mean =      2.063 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 14225 
    [ 2.500,  3.750) = 930 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     14.769 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.120 ms/op
Iteration   1: 2.299 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   2.179 ms/op
                 getUser·p0.90:   2.884 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   4.757 ms/op
                 getUser·p0.999:  20.742 ms/op
                 getUser·p0.9999: 21.357 ms/op
                 getUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13916
  mean =      2.299 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10524 
    [ 2.500,  5.000) = 3324 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.179 ms/op
     p(90.0000) =      2.884 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      4.757 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     21.357 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 5.690 ±(99.9%) 0.145 ms/op
Iteration   1: 4.060 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   13.074 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7877
  mean =      4.060 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 428 
    [ 2.500,  3.750) = 2916 
    [ 3.750,  5.000) = 3673 
    [ 5.000,  6.250) = 581 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =     13.074 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.470          ops/ms
ClientSimple.existUser                       thrpt         12.654          ops/ms
ClientSimple.getUser                         thrpt         11.657          ops/ms
ClientSimple.listUser                        thrpt          9.258          ops/ms
ClientSimple.createUser                       avgt          2.078           ms/op
ClientSimple.existUser                        avgt          1.959           ms/op
ClientSimple.getUser                          avgt          1.901           ms/op
ClientSimple.listUser                         avgt          3.233           ms/op
ClientSimple.createUser                     sample  15536   2.066 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.758           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.880           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.710           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.983           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.155           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.173           ms/op
ClientSimple.existUser                      sample  15571   2.063 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.524           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.985           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.732           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.325           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.680           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.769           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.778           ms/op
ClientSimple.getUser                        sample  13916   2.299 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.857           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.179           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.884           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.109           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.757           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.742           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.357           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.627           ms/op
ClientSimple.listUser                       sample   7877   4.060 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.114           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.883           ms/op
ClientSimple.listUser:listUser·p0.90        sample          5.112           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.636           ms/op
ClientSimple.listUser:listUser·p0.99        sample         13.074           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.760           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.579           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.579           ms/op

Benchmark result is saved to 1712729148384.json
