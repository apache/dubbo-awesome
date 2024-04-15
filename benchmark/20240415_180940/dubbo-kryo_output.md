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
# Warmup Iteration   1: 1.997 ops/ms
Iteration   1: 8.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.414 ops/ms


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
# Warmup Iteration   1: 6.514 ops/ms
Iteration   1: 13.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.782 ops/ms


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
# Warmup Iteration   1: 6.021 ops/ms
Iteration   1: 13.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.626 ops/ms


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
# Warmup Iteration   1: 5.356 ops/ms
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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.401 ±(99.9%) 0.055 ms/op
Iteration   1: 1.970 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.970 ms/op


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
# Warmup Iteration   1: 3.396 ±(99.9%) 0.090 ms/op
Iteration   1: 1.929 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.929 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.052 ms/op
Iteration   1: 2.133 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.701 ±(99.9%) 0.097 ms/op
Iteration   1: 3.225 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.225 ms/op


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
# Warmup Iteration   1: 3.361 ±(99.9%) 0.077 ms/op
Iteration   1: 2.183 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   1.964 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   2.867 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  24.379 ms/op
                 createUser·p0.9999: 24.887 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15102
  mean =      2.183 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13323 
    [ 2.500,  5.000) = 1461 
    [ 5.000,  7.500) = 144 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     24.379 ms/op
     p(99.9900) =     24.887 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 2.951 ±(99.9%) 0.073 ms/op
Iteration   1: 1.943 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.415 ms/op
                 existUser·p0.50:   1.845 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   2.873 ms/op
                 existUser·p0.999:  11.407 ms/op
                 existUser·p0.9999: 12.480 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16461
  mean =      1.943 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 15132 
    [ 2.500,  3.750) = 1126 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      2.873 ms/op
     p(99.9000) =     11.407 ms/op
     p(99.9900) =     12.480 ms/op
     p(99.9990) =     12.501 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


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
# Warmup Iteration   1: 3.555 ±(99.9%) 0.089 ms/op
Iteration   1: 2.018 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   1.911 ms/op
                 getUser·p0.90:   2.372 ms/op
                 getUser·p0.95:   2.716 ms/op
                 getUser·p0.99:   3.283 ms/op
                 getUser·p0.999:  14.144 ms/op
                 getUser·p0.9999: 14.426 ms/op
                 getUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15848
  mean =      2.018 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 14582 
    [ 2.500,  3.750) = 1063 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      3.283 ms/op
     p(99.9000) =     14.144 ms/op
     p(99.9900) =     14.426 ms/op
     p(99.9990) =     14.598 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.114 ms/op
Iteration   1: 3.006 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.651 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.017 ms/op
                 listUser·p0.999:  7.463 ms/op
                 listUser·p0.9999: 7.933 ms/op
                 listUser·p1.00:   7.946 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10651
  mean =      3.006 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 206 
    [2.000, 2.500) = 1894 
    [2.500, 3.000) = 4572 
    [3.000, 3.500) = 1877 
    [3.500, 4.000) = 1076 
    [4.000, 4.500) = 682 
    [4.500, 5.000) = 212 
    [5.000, 5.500) = 48 
    [5.500, 6.000) = 30 
    [6.000, 6.500) = 21 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.017 ms/op
     p(99.9000) =      7.463 ms/op
     p(99.9900) =      7.933 ms/op
     p(99.9990) =      7.946 ms/op
     p(99.9999) =      7.946 ms/op
    p(100.0000) =      7.946 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.414          ops/ms
ClientSimple.existUser                       thrpt         13.782          ops/ms
ClientSimple.getUser                         thrpt         13.626          ops/ms
ClientSimple.listUser                        thrpt          8.859          ops/ms
ClientSimple.createUser                       avgt          1.970           ms/op
ClientSimple.existUser                        avgt          1.929           ms/op
ClientSimple.getUser                          avgt          2.133           ms/op
ClientSimple.listUser                         avgt          3.225           ms/op
ClientSimple.createUser                     sample  15102   2.183 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.639           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.964           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.864           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.379           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.887           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.904           ms/op
ClientSimple.existUser                      sample  16461   1.943 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.415           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.845           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.873           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.407           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.480           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.501           ms/op
ClientSimple.getUser                        sample  15848   2.018 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.589           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.911           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.372           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.283           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.144           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.426           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.598           ms/op
ClientSimple.listUser                       sample  10651   3.006 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.651           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.863           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.969           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.017           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.463           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.933           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.946           ms/op

Benchmark result is saved to 1713204313490.json
