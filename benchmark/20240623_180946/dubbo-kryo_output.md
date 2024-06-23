# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.864 ops/ms
Iteration   1: 7.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.354 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.815 ops/ms
Iteration   1: 12.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.639 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.635 ops/ms
Iteration   1: 13.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.244 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.390 ops/ms
Iteration   1: 8.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.699 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ±(99.9%) 0.078 ms/op
Iteration   1: 2.064 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.064 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.131 ±(99.9%) 0.068 ms/op
Iteration   1: 1.893 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.893 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.301 ±(99.9%) 0.068 ms/op
Iteration   1: 1.970 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.970 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.379 ±(99.9%) 0.086 ms/op
Iteration   1: 3.374 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.374 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.311 ±(99.9%) 0.090 ms/op
Iteration   1: 2.137 ±(99.9%) 0.080 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   1.872 ms/op
                 createUser·p0.90:   2.376 ms/op
                 createUser·p0.95:   2.622 ms/op
                 createUser·p0.99:   5.528 ms/op
                 createUser·p0.999:  66.060 ms/op
                 createUser·p0.9999: 67.175 ms/op
                 createUser·p1.00:   67.240 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14957
  mean =      2.137 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14787 
    [ 5.000, 10.000) = 61 
    [10.000, 15.000) = 5 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 33 
    [25.000, 30.000) = 6 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 5 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.622 ms/op
     p(99.0000) =      5.528 ms/op
     p(99.9000) =     66.060 ms/op
     p(99.9900) =     67.175 ms/op
     p(99.9990) =     67.240 ms/op
     p(99.9999) =     67.240 ms/op
    p(100.0000) =     67.240 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.971 ±(99.9%) 0.081 ms/op
Iteration   1: 1.759 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   1.642 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   3.015 ms/op
                 existUser·p0.999:  12.272 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18262
  mean =      1.759 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 215 
    [ 1.250,  2.500) = 17186 
    [ 2.500,  3.750) = 764 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      1.642 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      3.015 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     13.943 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.034 ±(99.9%) 0.082 ms/op
Iteration   1: 1.827 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   1.706 ms/op
                 getUser·p0.90:   2.044 ms/op
                 getUser·p0.95:   2.257 ms/op
                 getUser·p0.99:   3.146 ms/op
                 getUser·p0.999:  25.362 ms/op
                 getUser·p0.9999: 25.559 ms/op
                 getUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17496
  mean =      1.827 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17159 
    [ 2.500,  5.000) = 214 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.044 ms/op
     p(95.0000) =      2.257 ms/op
     p(99.0000) =      3.146 ms/op
     p(99.9000) =     25.362 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.471 ±(99.9%) 0.119 ms/op
Iteration   1: 3.542 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  7.429 ms/op
                 listUser·p0.9999: 8.700 ms/op
                 listUser·p1.00:   8.700 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9037
  mean =      3.542 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 21 
    [1.500, 2.000) = 72 
    [2.000, 2.500) = 511 
    [2.500, 3.000) = 1825 
    [3.000, 3.500) = 1482 
    [3.500, 4.000) = 3153 
    [4.000, 4.500) = 1278 
    [4.500, 5.000) = 430 
    [5.000, 5.500) = 153 
    [5.500, 6.000) = 42 
    [6.000, 6.500) = 16 
    [6.500, 7.000) = 18 
    [7.000, 7.500) = 31 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      7.429 ms/op
     p(99.9900) =      8.700 ms/op
     p(99.9990) =      8.700 ms/op
     p(99.9999) =      8.700 ms/op
    p(100.0000) =      8.700 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.354          ops/ms
ClientSimple.existUser                       thrpt         12.639          ops/ms
ClientSimple.getUser                         thrpt         13.244          ops/ms
ClientSimple.listUser                        thrpt          8.699          ops/ms
ClientSimple.createUser                       avgt          2.064           ms/op
ClientSimple.existUser                        avgt          1.893           ms/op
ClientSimple.getUser                          avgt          1.970           ms/op
ClientSimple.listUser                         avgt          3.374           ms/op
ClientSimple.createUser                     sample  14957   2.137 ± 0.080   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.630           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.872           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.376           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.622           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.528           ms/op
ClientSimple.createUser:createUser·p0.999   sample         66.060           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         67.175           ms/op
ClientSimple.createUser:createUser·p1.00    sample         67.240           ms/op
ClientSimple.existUser                      sample  18262   1.759 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.778           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.642           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.015           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.272           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.943           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.025           ms/op
ClientSimple.getUser                        sample  17496   1.827 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.652           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.706           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.044           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.257           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.146           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.362           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.559           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.559           ms/op
ClientSimple.listUser                       sample   9037   3.542 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.061           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.625           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.734           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.429           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.700           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.700           ms/op

Benchmark result is saved to 1719165906724.json
