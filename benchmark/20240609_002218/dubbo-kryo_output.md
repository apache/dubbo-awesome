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
# Warmup Iteration   1: 2.014 ops/ms
Iteration   1: 5.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.959 ops/ms


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
# Warmup Iteration   1: 5.681 ops/ms
Iteration   1: 12.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.718 ops/ms


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
# Warmup Iteration   1: 5.449 ops/ms
Iteration   1: 13.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.285 ops/ms


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
# Warmup Iteration   1: 5.333 ops/ms
Iteration   1: 7.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.274 ops/ms


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.084 ms/op
Iteration   1: 2.185 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.185 ms/op


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
# Warmup Iteration   1: 3.606 ±(99.9%) 0.048 ms/op
Iteration   1: 1.917 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.917 ms/op


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.134 ms/op
Iteration   1: 1.949 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.949 ms/op


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
# Warmup Iteration   1: 4.736 ±(99.9%) 0.109 ms/op
Iteration   1: 3.812 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.812 ms/op


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
# Warmup Iteration   1: 3.508 ±(99.9%) 0.085 ms/op
Iteration   1: 2.148 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   2.019 ms/op
                 createUser·p0.90:   2.531 ms/op
                 createUser·p0.95:   2.757 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  18.198 ms/op
                 createUser·p0.9999: 20.414 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14881
  mean =      2.148 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13214 
    [ 2.500,  5.000) = 1433 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     18.198 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 3.088 ±(99.9%) 0.068 ms/op
Iteration   1: 1.835 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   1.714 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.515 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  16.564 ms/op
                 existUser·p0.9999: 16.941 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17411
  mean =      1.835 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1250 
    [ 1.250,  2.500) = 15238 
    [ 2.500,  3.750) = 803 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =     16.564 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 3.187 ±(99.9%) 0.072 ms/op
Iteration   1: 1.905 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   1.733 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   3.019 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  13.631 ms/op
                 getUser·p0.9999: 13.850 ms/op
                 getUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16804
  mean =      1.905 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 422 
    [ 1.250,  2.500) = 14401 
    [ 2.500,  3.750) = 1691 
    [ 3.750,  5.000) = 184 
    [ 5.000,  6.250) = 73 
    [ 6.250,  7.500) = 1 
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
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     13.850 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 5.215 ±(99.9%) 0.172 ms/op
Iteration   1: 3.789 ±(99.9%) 0.112 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  57.803 ms/op
                 listUser·p0.9999: 57.999 ms/op
                 listUser·p1.00:   57.999 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8596
  mean =      3.789 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8205 
    [ 5.000, 10.000) = 314 
    [10.000, 15.000) = 37 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     57.803 ms/op
     p(99.9900) =     57.999 ms/op
     p(99.9990) =     57.999 ms/op
     p(99.9999) =     57.999 ms/op
    p(100.0000) =     57.999 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.959          ops/ms
ClientSimple.existUser                       thrpt         12.718          ops/ms
ClientSimple.getUser                         thrpt         13.285          ops/ms
ClientSimple.listUser                        thrpt          7.274          ops/ms
ClientSimple.createUser                       avgt          2.185           ms/op
ClientSimple.existUser                        avgt          1.917           ms/op
ClientSimple.getUser                          avgt          1.949           ms/op
ClientSimple.listUser                         avgt          3.812           ms/op
ClientSimple.createUser                     sample  14881   2.148 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.553           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.019           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.531           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.111           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.198           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.414           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.414           ms/op
ClientSimple.existUser                      sample  17411   1.835 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.440           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.714           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.486           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.564           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.941           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.941           ms/op
ClientSimple.getUser                        sample  16804   1.905 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.696           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.733           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.019           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.953           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.631           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.850           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.861           ms/op
ClientSimple.listUser                       sample   8596   3.789 ± 0.112   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.389           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.604           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.563           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.932           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.364           ms/op
ClientSimple.listUser:listUser·p0.999       sample         57.803           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         57.999           ms/op
ClientSimple.listUser:listUser·p1.00        sample         57.999           ms/op

Benchmark result is saved to 1717892288416.json
