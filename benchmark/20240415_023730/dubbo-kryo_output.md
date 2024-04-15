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
# Warmup Iteration   1: 1.934 ops/ms
Iteration   1: 8.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.013 ops/ms


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
# Warmup Iteration   1: 6.209 ops/ms
Iteration   1: 13.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.317 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.939 ops/ms
Iteration   1: 13.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.936 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.665 ops/ms
Iteration   1: 9.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.304 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.788 ±(99.9%) 0.068 ms/op
Iteration   1: 2.058 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.058 ms/op


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
# Warmup Iteration   1: 3.621 ±(99.9%) 0.050 ms/op
Iteration   1: 1.782 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.782 ms/op


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
# Warmup Iteration   1: 3.099 ±(99.9%) 0.068 ms/op
Iteration   1: 1.878 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.878 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.089 ms/op
Iteration   1: 3.038 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.038 ms/op


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
# Warmup Iteration   1: 3.322 ±(99.9%) 0.072 ms/op
Iteration   1: 2.055 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   2.462 ms/op
                 createUser·p0.95:   2.762 ms/op
                 createUser·p0.99:   6.184 ms/op
                 createUser·p0.999:  21.299 ms/op
                 createUser·p0.9999: 21.412 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15552
  mean =      2.055 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14230 
    [ 2.500,  5.000) = 1113 
    [ 5.000,  7.500) = 80 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.762 ms/op
     p(99.0000) =      6.184 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     21.412 ms/op
     p(99.9990) =     21.430 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.963 ±(99.9%) 0.061 ms/op
Iteration   1: 1.912 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   3.813 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 12.517 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16714
  mean =      1.912 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 15052 
    [ 2.500,  3.750) = 1297 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     12.517 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.546 ±(99.9%) 0.094 ms/op
Iteration   1: 1.940 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   1.804 ms/op
                 getUser·p0.90:   2.404 ms/op
                 getUser·p0.95:   2.671 ms/op
                 getUser·p0.99:   3.684 ms/op
                 getUser·p0.999:  16.737 ms/op
                 getUser·p0.9999: 16.810 ms/op
                 getUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16484
  mean =      1.940 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 189 
    [ 1.250,  2.500) = 15016 
    [ 2.500,  3.750) = 1120 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.684 ms/op
     p(99.9000) =     16.737 ms/op
     p(99.9900) =     16.810 ms/op
     p(99.9990) =     16.810 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 5.134 ±(99.9%) 0.165 ms/op
Iteration   1: 3.913 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.254 ms/op
                 listUser·p0.999:  22.834 ms/op
                 listUser·p0.9999: 22.872 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8163
  mean =      3.913 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 232 
    [ 2.500,  5.000) = 7517 
    [ 5.000,  7.500) = 355 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.254 ms/op
     p(99.9000) =     22.834 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.013          ops/ms
ClientSimple.existUser                       thrpt         13.317          ops/ms
ClientSimple.getUser                         thrpt         13.936          ops/ms
ClientSimple.listUser                        thrpt          9.304          ops/ms
ClientSimple.createUser                       avgt          2.058           ms/op
ClientSimple.existUser                        avgt          1.782           ms/op
ClientSimple.getUser                          avgt          1.878           ms/op
ClientSimple.listUser                         avgt          3.038           ms/op
ClientSimple.createUser                     sample  15552   2.055 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.719           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.762           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.184           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.299           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.412           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.430           ms/op
ClientSimple.existUser                      sample  16714   1.912 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.565           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.780           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.813           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.255           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.517           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.517           ms/op
ClientSimple.getUser                        sample  16484   1.940 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.624           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.804           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.684           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.737           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.810           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.810           ms/op
ClientSimple.listUser                       sample   8163   3.913 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.200           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.834           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.014           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.254           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.834           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.872           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.872           ms/op

Benchmark result is saved to 1713148330777.json
