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
# Warmup Iteration   1: 1.615 ops/ms
Iteration   1: 6.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.799 ops/ms


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
# Warmup Iteration   1: 7.058 ops/ms
Iteration   1: 12.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.615 ops/ms


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
# Warmup Iteration   1: 6.185 ops/ms
Iteration   1: 14.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.821 ops/ms


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
# Warmup Iteration   1: 5.255 ops/ms
Iteration   1: 8.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.859 ops/ms


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
# Warmup Iteration   1: 3.910 ±(99.9%) 0.066 ms/op
Iteration   1: 2.169 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.169 ms/op


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
# Warmup Iteration   1: 3.459 ±(99.9%) 0.058 ms/op
Iteration   1: 1.833 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.833 ms/op


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
# Warmup Iteration   1: 3.339 ±(99.9%) 0.058 ms/op
Iteration   1: 1.990 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.990 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.079 ms/op
Iteration   1: 3.284 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.284 ms/op


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.162 ms/op
Iteration   1: 2.169 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   2.009 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.920 ms/op
                 createUser·p0.99:   9.706 ms/op
                 createUser·p0.999:  17.055 ms/op
                 createUser·p0.9999: 18.088 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14758
  mean =      2.169 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 756 
    [ 1.250,  2.500) = 11979 
    [ 2.500,  3.750) = 1651 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      9.706 ms/op
     p(99.9000) =     17.055 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 2.873 ±(99.9%) 0.066 ms/op
Iteration   1: 1.727 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   1.585 ms/op
                 existUser·p0.90:   2.013 ms/op
                 existUser·p0.95:   2.241 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  28.541 ms/op
                 existUser·p0.9999: 29.108 ms/op
                 existUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18513
  mean =      1.727 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18012 
    [ 2.500,  5.000) = 424 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      1.585 ms/op
     p(90.0000) =      2.013 ms/op
     p(95.0000) =      2.241 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =     28.541 ms/op
     p(99.9900) =     29.108 ms/op
     p(99.9990) =     29.164 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 3.267 ±(99.9%) 0.086 ms/op
Iteration   1: 2.076 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   1.991 ms/op
                 getUser·p0.90:   2.400 ms/op
                 getUser·p0.95:   2.666 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  12.216 ms/op
                 getUser·p0.9999: 12.434 ms/op
                 getUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15403
  mean =      2.076 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 14249 
    [ 2.500,  3.750) = 781 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     12.216 ms/op
     p(99.9900) =     12.434 ms/op
     p(99.9990) =     12.452 ms/op
     p(99.9999) =     12.452 ms/op
    p(100.0000) =     12.452 ms/op


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.134 ms/op
Iteration   1: 3.424 ±(99.9%) 0.089 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.017 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  44.543 ms/op
                 listUser·p0.9999: 46.531 ms/op
                 listUser·p1.00:   46.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9328
  mean =      3.424 ±(99.9%) 0.089 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9090 
    [ 5.000, 10.000) = 174 
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 26 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.017 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     44.543 ms/op
     p(99.9900) =     46.531 ms/op
     p(99.9990) =     46.531 ms/op
     p(99.9999) =     46.531 ms/op
    p(100.0000) =     46.531 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.799          ops/ms
ClientSimple.existUser                       thrpt         12.615          ops/ms
ClientSimple.getUser                         thrpt         14.821          ops/ms
ClientSimple.listUser                        thrpt          8.859          ops/ms
ClientSimple.createUser                       avgt          2.169           ms/op
ClientSimple.existUser                        avgt          1.833           ms/op
ClientSimple.getUser                          avgt          1.990           ms/op
ClientSimple.listUser                         avgt          3.284           ms/op
ClientSimple.createUser                     sample  14758   2.169 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.531           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.009           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.706           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.055           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.088           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.088           ms/op
ClientSimple.existUser                      sample  18513   1.727 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.568           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.585           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.013           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.645           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.541           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.108           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.164           ms/op
ClientSimple.getUser                        sample  15403   2.076 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.843           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.991           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.653           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.216           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.434           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.452           ms/op
ClientSimple.listUser                       sample   9328   3.424 ± 0.089   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.879           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.017           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.479           ms/op
ClientSimple.listUser:listUser·p0.999       sample         44.543           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         46.531           ms/op
ClientSimple.listUser:listUser·p1.00        sample         46.531           ms/op

Benchmark result is saved to 1712750771691.json
