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
# Warmup Iteration   1: 1.082 ops/ms
Iteration   1: 6.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.582 ops/ms


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
# Warmup Iteration   1: 6.103 ops/ms
Iteration   1: 12.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.704 ops/ms


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
# Warmup Iteration   1: 6.057 ops/ms
Iteration   1: 13.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.805 ops/ms


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
# Warmup Iteration   1: 5.316 ops/ms
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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.541 ±(99.9%) 0.059 ms/op
Iteration   1: 1.936 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.936 ms/op


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
# Warmup Iteration   1: 2.797 ±(99.9%) 0.043 ms/op
Iteration   1: 1.907 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.907 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.075 ms/op
Iteration   1: 2.145 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.145 ms/op


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.096 ms/op
Iteration   1: 3.508 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.508 ms/op


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.189 ms/op
Iteration   1: 2.223 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   2.093 ms/op
                 createUser·p0.90:   2.707 ms/op
                 createUser·p0.95:   2.990 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  14.041 ms/op
                 createUser·p0.9999: 14.518 ms/op
                 createUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14375
  mean =      2.223 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 11233 
    [ 2.500,  3.750) = 2743 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.093 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     14.518 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.130 ±(99.9%) 0.075 ms/op
Iteration   1: 1.811 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.360 ms/op
                 existUser·p0.50:   1.716 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   3.002 ms/op
                 existUser·p0.999:  19.038 ms/op
                 existUser·p0.9999: 20.132 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17920
  mean =      1.811 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16856 
    [ 2.500,  5.000) = 995 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      3.002 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     20.132 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 3.430 ±(99.9%) 0.089 ms/op
Iteration   1: 2.003 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   1.798 ms/op
                 getUser·p0.90:   2.335 ms/op
                 getUser·p0.95:   2.687 ms/op
                 getUser·p0.99:   5.401 ms/op
                 getUser·p0.999:  18.940 ms/op
                 getUser·p0.9999: 19.255 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15967
  mean =      2.003 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 426 
    [ 1.250,  2.500) = 14421 
    [ 2.500,  3.750) = 819 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      5.401 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.255 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.128 ms/op
Iteration   1: 3.272 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   3.076 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.216 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 14.074 ms/op
                 listUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9784
  mean =      3.272 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 475 
    [ 2.500,  3.750) = 7682 
    [ 3.750,  5.000) = 1521 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.216 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     14.074 ms/op
     p(99.9990) =     14.074 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.582          ops/ms
ClientSimple.existUser                       thrpt         12.704          ops/ms
ClientSimple.getUser                         thrpt         13.805          ops/ms
ClientSimple.listUser                        thrpt          9.304          ops/ms
ClientSimple.createUser                       avgt          1.936           ms/op
ClientSimple.existUser                        avgt          1.907           ms/op
ClientSimple.getUser                          avgt          2.145           ms/op
ClientSimple.listUser                         avgt          3.508           ms/op
ClientSimple.createUser                     sample  14375   2.223 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.638           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.093           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.990           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.276           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.041           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.518           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.533           ms/op
ClientSimple.existUser                      sample  17920   1.811 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.360           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.716           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.002           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.038           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.132           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.677           ms/op
ClientSimple.getUser                        sample  15967   2.003 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.787           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.798           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.335           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.401           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.940           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.255           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.333           ms/op
ClientSimple.listUser                       sample   9784   3.272 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.251           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.076           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.026           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.216           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.910           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.074           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.074           ms/op

Benchmark result is saved to 1711519523443.json
