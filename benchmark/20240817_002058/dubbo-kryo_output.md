# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.760 ops/ms
Iteration   1: 7.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.674 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.325 ops/ms
Iteration   1: 14.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.536 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.174 ops/ms
Iteration   1: 12.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.261 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.191 ops/ms
Iteration   1: 8.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.277 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.013 ±(99.9%) 0.070 ms/op
Iteration   1: 2.274 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.274 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.126 ±(99.9%) 0.049 ms/op
Iteration   1: 1.986 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.986 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.415 ±(99.9%) 0.055 ms/op
Iteration   1: 1.827 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.827 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.288 ±(99.9%) 0.094 ms/op
Iteration   1: 3.158 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.158 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.373 ±(99.9%) 0.084 ms/op
Iteration   1: 2.134 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   2.925 ms/op
                 createUser·p0.99:   8.031 ms/op
                 createUser·p0.999:  14.139 ms/op
                 createUser·p0.9999: 14.650 ms/op
                 createUser·p1.00:   15.024 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14963
  mean =      2.134 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 198 
    [ 1.250,  2.500) = 11859 
    [ 2.500,  3.750) = 2622 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      8.031 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     14.650 ms/op
     p(99.9990) =     15.024 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.056 ±(99.9%) 0.097 ms/op
Iteration   1: 1.936 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.454 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.560 ms/op
                 existUser·p0.95:   2.703 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  11.499 ms/op
                 existUser·p0.9999: 11.895 ms/op
                 existUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16831
  mean =      1.936 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 472 
    [ 1.250,  2.500) = 14372 
    [ 2.500,  3.750) = 1798 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =     11.499 ms/op
     p(99.9900) =     11.895 ms/op
     p(99.9990) =     11.895 ms/op
     p(99.9999) =     11.895 ms/op
    p(100.0000) =     11.895 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.437 ±(99.9%) 0.088 ms/op
Iteration   1: 2.123 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   0.421 ms/op
                 getUser·p0.50:   1.995 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.761 ms/op
                 getUser·p0.99:   4.021 ms/op
                 getUser·p0.999:  35.320 ms/op
                 getUser·p0.9999: 35.881 ms/op
                 getUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15062
  mean =      2.123 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13047 
    [ 2.500,  5.000) = 1906 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      4.021 ms/op
     p(99.9000) =     35.320 ms/op
     p(99.9900) =     35.881 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.284 ±(99.9%) 0.146 ms/op
Iteration   1: 3.301 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.367 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.864 ms/op
                 listUser·p0.999:  7.432 ms/op
                 listUser·p0.9999: 10.453 ms/op
                 listUser·p1.00:   10.453 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9780
  mean =      3.301 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 231 
    [ 2.000,  3.000) = 2827 
    [ 3.000,  4.000) = 5667 
    [ 4.000,  5.000) = 753 
    [ 5.000,  6.000) = 224 
    [ 6.000,  7.000) = 43 
    [ 7.000,  8.000) = 32 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.864 ms/op
     p(99.9000) =      7.432 ms/op
     p(99.9900) =     10.453 ms/op
     p(99.9990) =     10.453 ms/op
     p(99.9999) =     10.453 ms/op
    p(100.0000) =     10.453 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.674          ops/ms
ClientSimple.existUser                       thrpt         14.536          ops/ms
ClientSimple.getUser                         thrpt         12.261          ops/ms
ClientSimple.listUser                        thrpt          8.277          ops/ms
ClientSimple.createUser                       avgt          2.274           ms/op
ClientSimple.existUser                        avgt          1.986           ms/op
ClientSimple.getUser                          avgt          1.827           ms/op
ClientSimple.listUser                         avgt          3.158           ms/op
ClientSimple.createUser                     sample  14963   2.134 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.764           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.925           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.031           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.139           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.650           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.024           ms/op
ClientSimple.existUser                      sample  16831   1.936 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.454           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.800           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.006           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.499           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.895           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.895           ms/op
ClientSimple.getUser                        sample  15062   2.123 ± 0.045   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.421           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.995           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.021           ms/op
ClientSimple.getUser:getUser·p0.999         sample         35.320           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         35.881           ms/op
ClientSimple.getUser:getUser·p1.00          sample         35.914           ms/op
ClientSimple.listUser                       sample   9780   3.301 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.085           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.367           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.864           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.432           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.453           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.453           ms/op

Benchmark result is saved to 1723853780161.json
