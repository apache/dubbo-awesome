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
# Warmup Iteration   1: 1.685 ops/ms
Iteration   1: 6.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.556 ops/ms


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
# Warmup Iteration   1: 5.983 ops/ms
Iteration   1: 15.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.700 ops/ms


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
# Warmup Iteration   1: 6.180 ops/ms
Iteration   1: 12.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.234 ops/ms


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
# Warmup Iteration   1: 5.020 ops/ms
Iteration   1: 8.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.573 ops/ms


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.062 ms/op
Iteration   1: 2.264 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.264 ms/op


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
# Warmup Iteration   1: 3.447 ±(99.9%) 0.060 ms/op
Iteration   1: 1.773 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.773 ms/op


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
# Warmup Iteration   1: 3.713 ±(99.9%) 0.071 ms/op
Iteration   1: 1.906 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.906 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.081 ms/op
Iteration   1: 3.211 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.211 ms/op


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
# Warmup Iteration   1: 3.490 ±(99.9%) 0.095 ms/op
Iteration   1: 2.421 ±(99.9%) 0.092 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   2.060 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   3.014 ms/op
                 createUser·p0.99:   12.550 ms/op
                 createUser·p0.999:  60.733 ms/op
                 createUser·p0.9999: 84.067 ms/op
                 createUser·p1.00:   87.425 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13201
  mean =      2.421 ±(99.9%) 0.092 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12901 
    [ 5.000, 10.000) = 112 
    [10.000, 15.000) = 126 
    [15.000, 20.000) = 14 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 6 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 5 
    [45.000, 50.000) = 7 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 4 
    [65.000, 70.000) = 2 
    [70.000, 75.000) = 4 
    [75.000, 80.000) = 2 
    [80.000, 85.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      3.014 ms/op
     p(99.0000) =     12.550 ms/op
     p(99.9000) =     60.733 ms/op
     p(99.9900) =     84.067 ms/op
     p(99.9990) =     87.425 ms/op
     p(99.9999) =     87.425 ms/op
    p(100.0000) =     87.425 ms/op


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
# Warmup Iteration   1: 3.065 ±(99.9%) 0.088 ms/op
Iteration   1: 1.928 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  17.736 ms/op
                 existUser·p0.9999: 18.910 ms/op
                 existUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16577
  mean =      1.928 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 821 
    [ 1.250,  2.500) = 13697 
    [ 2.500,  3.750) = 1883 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =     17.736 ms/op
     p(99.9900) =     18.910 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 3.364 ±(99.9%) 0.088 ms/op
Iteration   1: 2.133 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   1.954 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   5.212 ms/op
                 getUser·p0.999:  34.385 ms/op
                 getUser·p0.9999: 35.224 ms/op
                 getUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15080
  mean =      2.133 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13062 
    [ 2.500,  5.000) = 1838 
    [ 5.000,  7.500) = 116 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      5.212 ms/op
     p(99.9000) =     34.385 ms/op
     p(99.9900) =     35.224 ms/op
     p(99.9990) =     35.324 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.135 ms/op
Iteration   1: 3.392 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  8.305 ms/op
                 listUser·p0.9999: 8.585 ms/op
                 listUser·p1.00:   8.585 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9415
  mean =      3.392 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 0 
    [1.500, 2.000) = 18 
    [2.000, 2.500) = 144 
    [2.500, 3.000) = 4123 
    [3.000, 3.500) = 1776 
    [3.500, 4.000) = 1316 
    [4.000, 4.500) = 1236 
    [4.500, 5.000) = 527 
    [5.000, 5.500) = 157 
    [5.500, 6.000) = 64 
    [6.000, 6.500) = 15 
    [6.500, 7.000) = 21 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =      8.305 ms/op
     p(99.9900) =      8.585 ms/op
     p(99.9990) =      8.585 ms/op
     p(99.9999) =      8.585 ms/op
    p(100.0000) =      8.585 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.556          ops/ms
ClientSimple.existUser                       thrpt         15.700          ops/ms
ClientSimple.getUser                         thrpt         12.234          ops/ms
ClientSimple.listUser                        thrpt          8.573          ops/ms
ClientSimple.createUser                       avgt          2.264           ms/op
ClientSimple.existUser                        avgt          1.773           ms/op
ClientSimple.getUser                          avgt          1.906           ms/op
ClientSimple.listUser                         avgt          3.211           ms/op
ClientSimple.createUser                     sample  13201   2.421 ± 0.092   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.689           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.060           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.014           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.550           ms/op
ClientSimple.createUser:createUser·p0.999   sample         60.733           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         84.067           ms/op
ClientSimple.createUser:createUser·p1.00    sample         87.425           ms/op
ClientSimple.existUser                      sample  16577   1.928 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.682           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.786           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.751           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.736           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.910           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.104           ms/op
ClientSimple.getUser                        sample  15080   2.133 ± 0.044   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.788           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.954           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.212           ms/op
ClientSimple.getUser:getUser·p0.999         sample         34.385           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         35.224           ms/op
ClientSimple.getUser:getUser·p1.00          sample         35.324           ms/op
ClientSimple.listUser                       sample   9415   3.392 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.653           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.833           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.305           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.585           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.585           ms/op

Benchmark result is saved to 1713485715173.json
