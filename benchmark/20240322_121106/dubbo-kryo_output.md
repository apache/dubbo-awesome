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
# Warmup Iteration   1: 0.943 ops/ms
Iteration   1: 6.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.383 ops/ms


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
# Warmup Iteration   1: 4.972 ops/ms
Iteration   1: 11.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.466 ops/ms


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
# Warmup Iteration   1: 7.719 ops/ms
Iteration   1: 15.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.446 ops/ms


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
# Warmup Iteration   1: 5.756 ops/ms
Iteration   1: 9.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.133 ops/ms


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
# Warmup Iteration   1: 3.416 ±(99.9%) 0.057 ms/op
Iteration   1: 2.435 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.435 ms/op


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
# Warmup Iteration   1: 3.451 ±(99.9%) 0.075 ms/op
Iteration   1: 1.982 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.982 ms/op


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
# Warmup Iteration   1: 3.459 ±(99.9%) 0.066 ms/op
Iteration   1: 2.032 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.032 ms/op


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.090 ms/op
Iteration   1: 3.637 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.637 ms/op


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
# Warmup Iteration   1: 3.410 ±(99.9%) 0.089 ms/op
Iteration   1: 1.985 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   1.786 ms/op
                 createUser·p0.90:   2.445 ms/op
                 createUser·p0.95:   2.933 ms/op
                 createUser·p0.99:   6.290 ms/op
                 createUser·p0.999:  16.417 ms/op
                 createUser·p0.9999: 16.652 ms/op
                 createUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16122
  mean =      1.985 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 346 
    [ 1.250,  2.500) = 14289 
    [ 2.500,  3.750) = 1258 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      6.290 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     16.652 ms/op
     p(99.9990) =     16.663 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 2.848 ±(99.9%) 0.064 ms/op
Iteration   1: 1.962 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.438 ms/op
                 existUser·p0.50:   1.886 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.486 ms/op
                 existUser·p0.99:   3.314 ms/op
                 existUser·p0.999:  26.653 ms/op
                 existUser·p0.9999: 27.451 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16307
  mean =      1.962 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15577 
    [ 2.500,  5.000) = 635 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.486 ms/op
     p(99.0000) =      3.314 ms/op
     p(99.9000) =     26.653 ms/op
     p(99.9900) =     27.451 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.080 ms/op
Iteration   1: 2.123 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.075 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.822 ms/op
                 getUser·p0.99:   3.677 ms/op
                 getUser·p0.999:  12.812 ms/op
                 getUser·p0.9999: 12.951 ms/op
                 getUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15060
  mean =      2.123 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 12956 
    [ 2.500,  3.750) = 1796 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.677 ms/op
     p(99.9000) =     12.812 ms/op
     p(99.9900) =     12.951 ms/op
     p(99.9990) =     12.960 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


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
# Warmup Iteration   1: 4.952 ±(99.9%) 0.159 ms/op
Iteration   1: 3.186 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   2.839 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.450 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 17.793 ms/op
                 listUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10051
  mean =      3.186 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 1068 
    [ 2.500,  3.750) = 7156 
    [ 3.750,  5.000) = 1504 
    [ 5.000,  6.250) = 154 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.450 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.383          ops/ms
ClientSimple.existUser                       thrpt         11.466          ops/ms
ClientSimple.getUser                         thrpt         15.446          ops/ms
ClientSimple.listUser                        thrpt          9.133          ops/ms
ClientSimple.createUser                       avgt          2.435           ms/op
ClientSimple.existUser                        avgt          1.982           ms/op
ClientSimple.getUser                          avgt          2.032           ms/op
ClientSimple.listUser                         avgt          3.637           ms/op
ClientSimple.createUser                     sample  16122   1.985 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.548           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.786           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.445           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.290           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.417           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.652           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.663           ms/op
ClientSimple.existUser                      sample  16307   1.962 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.438           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.886           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.314           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.653           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.451           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.492           ms/op
ClientSimple.getUser                        sample  15060   2.123 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.736           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.075           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.677           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.812           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.951           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.960           ms/op
ClientSimple.listUser                       sample  10051   3.186 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.766           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.839           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.043           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.450           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.662           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.793           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.793           ms/op

Benchmark result is saved to 1711109188837.json
