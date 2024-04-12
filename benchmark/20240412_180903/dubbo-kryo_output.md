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
# Warmup Iteration   1: 1.265 ops/ms
Iteration   1: 6.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.233 ops/ms


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
# Warmup Iteration   1: 5.331 ops/ms
Iteration   1: 11.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.255 ops/ms


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
# Warmup Iteration   1: 5.272 ops/ms
Iteration   1: 13.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.126 ops/ms


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
# Warmup Iteration   1: 4.678 ops/ms
Iteration   1: 7.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.918 ops/ms


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.093 ms/op
Iteration   1: 2.150 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.150 ms/op


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
# Warmup Iteration   1: 3.455 ±(99.9%) 0.057 ms/op
Iteration   1: 2.016 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.016 ms/op


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
# Warmup Iteration   1: 3.262 ±(99.9%) 0.062 ms/op
Iteration   1: 2.217 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.217 ms/op


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
# Warmup Iteration   1: 4.488 ±(99.9%) 0.087 ms/op
Iteration   1: 3.223 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.223 ms/op


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
# Warmup Iteration   1: 3.688 ±(99.9%) 0.098 ms/op
Iteration   1: 2.118 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   1.911 ms/op
                 createUser·p0.90:   2.551 ms/op
                 createUser·p0.95:   2.871 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 27.066 ms/op
                 createUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15092
  mean =      2.118 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13426 
    [ 2.500,  5.000) = 1423 
    [ 5.000,  7.500) = 138 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.551 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 3.224 ±(99.9%) 0.088 ms/op
Iteration   1: 1.764 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.402 ms/op
                 existUser·p0.50:   1.659 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   3.059 ms/op
                 existUser·p0.999:  10.581 ms/op
                 existUser·p0.9999: 11.574 ms/op
                 existUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18212
  mean =      1.764 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 627 
    [ 1.250,  2.500) = 16889 
    [ 2.500,  3.750) = 582 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      1.659 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      3.059 ms/op
     p(99.9000) =     10.581 ms/op
     p(99.9900) =     11.574 ms/op
     p(99.9990) =     11.682 ms/op
     p(99.9999) =     11.682 ms/op
    p(100.0000) =     11.682 ms/op


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
# Warmup Iteration   1: 3.598 ±(99.9%) 0.128 ms/op
Iteration   1: 2.171 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.611 ms/op
                 getUser·p0.50:   2.062 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.765 ms/op
                 getUser·p0.99:   6.033 ms/op
                 getUser·p0.999:  24.690 ms/op
                 getUser·p0.9999: 25.414 ms/op
                 getUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14759
  mean =      2.171 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12386 
    [ 2.500,  5.000) = 2192 
    [ 5.000,  7.500) = 117 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      6.033 ms/op
     p(99.9000) =     24.690 ms/op
     p(99.9900) =     25.414 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 4.404 ±(99.9%) 0.125 ms/op
Iteration   1: 3.124 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.054 ms/op
                 listUser·p0.999:  6.007 ms/op
                 listUser·p0.9999: 6.810 ms/op
                 listUser·p1.00:   6.824 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10227
  mean =      3.124 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 10 
    [1.500, 2.000) = 53 
    [2.000, 2.500) = 532 
    [2.500, 3.000) = 5667 
    [3.000, 3.500) = 1489 
    [3.500, 4.000) = 1317 
    [4.000, 4.500) = 856 
    [4.500, 5.000) = 182 
    [5.000, 5.500) = 75 
    [5.500, 6.000) = 36 
    [6.000, 6.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.054 ms/op
     p(99.9000) =      6.007 ms/op
     p(99.9900) =      6.810 ms/op
     p(99.9990) =      6.824 ms/op
     p(99.9999) =      6.824 ms/op
    p(100.0000) =      6.824 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.233          ops/ms
ClientSimple.existUser                       thrpt         11.255          ops/ms
ClientSimple.getUser                         thrpt         13.126          ops/ms
ClientSimple.listUser                        thrpt          7.918          ops/ms
ClientSimple.createUser                       avgt          2.150           ms/op
ClientSimple.existUser                        avgt          2.016           ms/op
ClientSimple.getUser                          avgt          2.217           ms/op
ClientSimple.listUser                         avgt          3.223           ms/op
ClientSimple.createUser                     sample  15092   2.118 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.033           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.911           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.551           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.890           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.236           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.066           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.066           ms/op
ClientSimple.existUser                      sample  18212   1.764 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.402           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.659           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.059           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.581           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.574           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.682           ms/op
ClientSimple.getUser                        sample  14759   2.171 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.611           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.062           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.765           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.033           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.690           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.414           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.461           ms/op
ClientSimple.listUser                       sample  10227   3.124 ± 0.020   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.186           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.896           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.055           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.054           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.007           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.810           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.824           ms/op

Benchmark result is saved to 1712945077635.json
