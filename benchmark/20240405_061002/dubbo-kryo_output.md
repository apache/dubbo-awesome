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
# Warmup Iteration   1: 1.652 ops/ms
Iteration   1: 7.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.350 ops/ms


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
# Warmup Iteration   1: 6.244 ops/ms
Iteration   1: 12.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.960 ops/ms


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
# Warmup Iteration   1: 5.486 ops/ms
Iteration   1: 11.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.601 ops/ms


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
# Warmup Iteration   1: 5.305 ops/ms
Iteration   1: 9.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.293 ops/ms


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.099 ms/op
Iteration   1: 2.254 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.254 ms/op


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
# Warmup Iteration   1: 3.455 ±(99.9%) 0.070 ms/op
Iteration   1: 1.856 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.856 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.057 ms/op
Iteration   1: 2.090 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.090 ms/op


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
# Warmup Iteration   1: 4.318 ±(99.9%) 0.089 ms/op
Iteration   1: 3.407 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.407 ms/op


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.116 ms/op
Iteration   1: 2.216 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.122 ms/op
                 createUser·p0.90:   2.609 ms/op
                 createUser·p0.95:   2.826 ms/op
                 createUser·p0.99:   5.344 ms/op
                 createUser·p0.999:  14.757 ms/op
                 createUser·p0.9999: 19.355 ms/op
                 createUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14426
  mean =      2.216 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 12212 
    [ 2.500,  3.750) = 1896 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      5.344 ms/op
     p(99.9000) =     14.757 ms/op
     p(99.9900) =     19.355 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 2.992 ±(99.9%) 0.119 ms/op
Iteration   1: 1.890 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   1.827 ms/op
                 existUser·p0.90:   2.204 ms/op
                 existUser·p0.95:   2.421 ms/op
                 existUser·p0.99:   3.325 ms/op
                 existUser·p0.999:  13.959 ms/op
                 existUser·p0.9999: 14.487 ms/op
                 existUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16922
  mean =      1.890 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 400 
    [ 1.250,  2.500) = 15815 
    [ 2.500,  3.750) = 572 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.421 ms/op
     p(99.0000) =      3.325 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     14.487 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.434 ±(99.9%) 0.099 ms/op
Iteration   1: 2.143 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.046 ms/op
                 getUser·p0.90:   2.666 ms/op
                 getUser·p0.95:   2.822 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  12.567 ms/op
                 getUser·p0.9999: 13.198 ms/op
                 getUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14955
  mean =      2.143 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 12585 
    [ 2.500,  3.750) = 2179 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     13.198 ms/op
     p(99.9990) =     13.304 ms/op
     p(99.9999) =     13.304 ms/op
    p(100.0000) =     13.304 ms/op


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
# Warmup Iteration   1: 4.801 ±(99.9%) 0.141 ms/op
Iteration   1: 3.873 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   14.676 ms/op
                 listUser·p0.999:  18.374 ms/op
                 listUser·p0.9999: 18.514 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8260
  mean =      3.873 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 416 
    [ 2.500,  3.750) = 3581 
    [ 3.750,  5.000) = 3824 
    [ 5.000,  6.250) = 312 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =     14.676 ms/op
     p(99.9000) =     18.374 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.350          ops/ms
ClientSimple.existUser                       thrpt         12.960          ops/ms
ClientSimple.getUser                         thrpt         11.601          ops/ms
ClientSimple.listUser                        thrpt          9.293          ops/ms
ClientSimple.createUser                       avgt          2.254           ms/op
ClientSimple.existUser                        avgt          1.856           ms/op
ClientSimple.getUser                          avgt          2.090           ms/op
ClientSimple.listUser                         avgt          3.407           ms/op
ClientSimple.createUser                     sample  14426   2.216 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.702           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.122           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.609           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.826           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.344           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.757           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.355           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.399           ms/op
ClientSimple.existUser                      sample  16922   1.890 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.563           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.827           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.204           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.325           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.959           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.487           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.680           ms/op
ClientSimple.getUser                        sample  14955   2.143 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.912           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.046           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.690           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.567           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.198           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.304           ms/op
ClientSimple.listUser                       sample   8260   3.873 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.014           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.764           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.046           ms/op
ClientSimple.listUser:listUser·p0.99        sample         14.676           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.374           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.514           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.514           ms/op

Benchmark result is saved to 1712297121971.json
