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
# Warmup Iteration   1: 1.714 ops/ms
Iteration   1: 7.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.233 ops/ms


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
# Warmup Iteration   1: 5.978 ops/ms
Iteration   1: 13.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.012 ops/ms


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
# Warmup Iteration   1: 5.423 ops/ms
Iteration   1: 12.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.284 ops/ms


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
# Warmup Iteration   1: 4.312 ops/ms
Iteration   1: 9.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.330 ops/ms


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.075 ms/op
Iteration   1: 2.202 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.202 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.055 ms/op
Iteration   1: 1.755 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.755 ms/op


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
# Warmup Iteration   1: 3.513 ±(99.9%) 0.057 ms/op
Iteration   1: 2.218 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.218 ms/op


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.089 ms/op
Iteration   1: 3.677 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.677 ms/op


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
# Warmup Iteration   1: 3.376 ±(99.9%) 0.107 ms/op
Iteration   1: 2.531 ±(99.9%) 0.092 ms/op
                 createUser·p0.00:   0.328 ms/op
                 createUser·p0.50:   2.191 ms/op
                 createUser·p0.90:   2.912 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   9.044 ms/op
                 createUser·p0.999:  46.751 ms/op
                 createUser·p0.9999: 47.645 ms/op
                 createUser·p1.00:   47.645 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12640
  mean =      2.531 ±(99.9%) 0.092 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12335 
    [ 5.000, 10.000) = 212 
    [10.000, 15.000) = 29 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.328 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     46.751 ms/op
     p(99.9900) =     47.645 ms/op
     p(99.9990) =     47.645 ms/op
     p(99.9999) =     47.645 ms/op
    p(100.0000) =     47.645 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.071 ms/op
Iteration   1: 1.691 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   1.563 ms/op
                 existUser·p0.90:   2.130 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.027 ms/op
                 existUser·p0.999:  11.960 ms/op
                 existUser·p0.9999: 12.133 ms/op
                 existUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18903
  mean =      1.691 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 464 
    [ 1.250,  2.500) = 17441 
    [ 2.500,  3.750) = 884 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      1.563 ms/op
     p(90.0000) =      2.130 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.027 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     12.133 ms/op
     p(99.9990) =     12.206 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


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
# Warmup Iteration   1: 3.234 ±(99.9%) 0.095 ms/op
Iteration   1: 2.274 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   2.212 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   2.941 ms/op
                 getUser·p0.99:   3.962 ms/op
                 getUser·p0.999:  12.074 ms/op
                 getUser·p0.9999: 12.229 ms/op
                 getUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14073
  mean =      2.274 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 10618 
    [ 2.500,  3.750) = 3223 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.212 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      3.962 ms/op
     p(99.9000) =     12.074 ms/op
     p(99.9900) =     12.229 ms/op
     p(99.9990) =     12.255 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


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
# Warmup Iteration   1: 4.546 ±(99.9%) 0.129 ms/op
Iteration   1: 3.513 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.490 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.972 ms/op
                 listUser·p0.999:  24.084 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9112
  mean =      3.513 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 637 
    [ 2.500,  5.000) = 8333 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     24.084 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.233          ops/ms
ClientSimple.existUser                       thrpt         13.012          ops/ms
ClientSimple.getUser                         thrpt         12.284          ops/ms
ClientSimple.listUser                        thrpt          9.330          ops/ms
ClientSimple.createUser                       avgt          2.202           ms/op
ClientSimple.existUser                        avgt          1.755           ms/op
ClientSimple.getUser                          avgt          2.218           ms/op
ClientSimple.listUser                         avgt          3.677           ms/op
ClientSimple.createUser                     sample  12640   2.531 ± 0.092   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.328           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.191           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.248           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.044           ms/op
ClientSimple.createUser:createUser·p0.999   sample         46.751           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         47.645           ms/op
ClientSimple.createUser:createUser·p1.00    sample         47.645           ms/op
ClientSimple.existUser                      sample  18903   1.691 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.521           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.563           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.027           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.960           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.133           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.206           ms/op
ClientSimple.getUser                        sample  14073   2.274 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.571           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.212           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.962           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.074           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.229           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.255           ms/op
ClientSimple.listUser                       sample   9112   3.513 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.284           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.490           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.137           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.972           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.084           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.166           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.166           ms/op

Benchmark result is saved to 1711821888941.json
