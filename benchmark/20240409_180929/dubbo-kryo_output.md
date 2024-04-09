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
# Warmup Iteration   1: 1.565 ops/ms
Iteration   1: 6.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.842 ops/ms


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
# Warmup Iteration   1: 6.579 ops/ms
Iteration   1: 12.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.432 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.643 ops/ms
Iteration   1: 13.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.139 ops/ms


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
Iteration   1: 8.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.465 ops/ms


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.072 ms/op
Iteration   1: 2.024 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.024 ms/op


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
# Warmup Iteration   1: 3.326 ±(99.9%) 0.064 ms/op
Iteration   1: 1.875 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.875 ms/op


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
# Warmup Iteration   1: 3.397 ±(99.9%) 0.062 ms/op
Iteration   1: 2.034 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.034 ms/op


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
# Warmup Iteration   1: 4.531 ±(99.9%) 0.103 ms/op
Iteration   1: 3.459 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.459 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.095 ms/op
Iteration   1: 1.973 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   1.769 ms/op
                 createUser·p0.90:   2.245 ms/op
                 createUser·p0.95:   2.642 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  30.992 ms/op
                 createUser·p0.9999: 31.209 ms/op
                 createUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16200
  mean =      1.973 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15153 
    [ 2.500,  5.000) = 848 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     30.992 ms/op
     p(99.9900) =     31.209 ms/op
     p(99.9990) =     31.392 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 2.891 ±(99.9%) 0.064 ms/op
Iteration   1: 1.865 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   4.103 ms/op
                 existUser·p0.999:  12.452 ms/op
                 existUser·p0.9999: 13.203 ms/op
                 existUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17194
  mean =      1.865 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 381 
    [ 1.250,  2.500) = 16049 
    [ 2.500,  3.750) = 579 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      4.103 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     13.203 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


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
# Warmup Iteration   1: 3.373 ±(99.9%) 0.098 ms/op
Iteration   1: 2.099 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.668 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.666 ms/op
                 getUser·p0.95:   2.818 ms/op
                 getUser·p0.99:   3.520 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 12.132 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15213
  mean =      2.099 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 12526 
    [ 2.500,  3.750) = 2545 
    [ 3.750,  5.000) = 23 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      3.520 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     12.132 ms/op
     p(99.9990) =     12.141 ms/op
     p(99.9999) =     12.141 ms/op
    p(100.0000) =     12.141 ms/op


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.115 ms/op
Iteration   1: 3.639 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.495 ms/op
                 listUser·p0.999:  21.234 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8807
  mean =      3.639 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 856 
    [ 2.500,  5.000) = 7490 
    [ 5.000,  7.500) = 375 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.495 ms/op
     p(99.9000) =     21.234 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.842          ops/ms
ClientSimple.existUser                       thrpt         12.432          ops/ms
ClientSimple.getUser                         thrpt         13.139          ops/ms
ClientSimple.listUser                        thrpt          8.465          ops/ms
ClientSimple.createUser                       avgt          2.024           ms/op
ClientSimple.existUser                        avgt          1.875           ms/op
ClientSimple.getUser                          avgt          2.034           ms/op
ClientSimple.listUser                         avgt          3.459           ms/op
ClientSimple.createUser                     sample  16200   1.973 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.671           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.769           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.245           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.488           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.992           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.209           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.392           ms/op
ClientSimple.existUser                      sample  17194   1.865 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.671           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.772           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.103           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.452           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.203           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.615           ms/op
ClientSimple.getUser                        sample  15213   2.099 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.668           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.520           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.042           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.132           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.141           ms/op
ClientSimple.listUser                       sample   8807   3.639 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.852           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.633           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.014           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.495           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.234           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.463           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.463           ms/op

Benchmark result is saved to 1712685900406.json
