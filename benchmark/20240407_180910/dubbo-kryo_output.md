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
# Warmup Iteration   1: 1.071 ops/ms
Iteration   1: 6.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.783 ops/ms


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
# Warmup Iteration   1: 6.767 ops/ms
Iteration   1: 11.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.866 ops/ms


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
# Warmup Iteration   1: 6.446 ops/ms
Iteration   1: 13.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.448 ops/ms


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
# Warmup Iteration   1: 5.199 ops/ms
Iteration   1: 8.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.820 ops/ms


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.086 ms/op
Iteration   1: 2.209 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.209 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.060 ms/op
Iteration   1: 1.678 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.678 ms/op


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
# Warmup Iteration   1: 3.067 ±(99.9%) 0.055 ms/op
Iteration   1: 2.121 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.121 ms/op


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
# Warmup Iteration   1: 5.103 ±(99.9%) 0.102 ms/op
Iteration   1: 3.384 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.384 ms/op


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
# Warmup Iteration   1: 3.459 ±(99.9%) 0.084 ms/op
Iteration   1: 2.226 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.720 ms/op
                 createUser·p0.50:   1.974 ms/op
                 createUser·p0.90:   2.564 ms/op
                 createUser·p0.95:   2.875 ms/op
                 createUser·p0.99:   8.233 ms/op
                 createUser·p0.999:  27.427 ms/op
                 createUser·p0.9999: 34.760 ms/op
                 createUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14353
  mean =      2.226 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12613 
    [ 2.500,  5.000) = 1453 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      8.233 ms/op
     p(99.9000) =     27.427 ms/op
     p(99.9900) =     34.760 ms/op
     p(99.9990) =     38.470 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


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
# Warmup Iteration   1: 2.965 ±(99.9%) 0.067 ms/op
Iteration   1: 1.936 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   3.285 ms/op
                 existUser·p0.999:  19.300 ms/op
                 existUser·p0.9999: 19.433 ms/op
                 existUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16526
  mean =      1.936 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 325 
    [ 1.250,  2.500) = 15032 
    [ 2.500,  3.750) = 1070 
    [ 3.750,  5.000) = 6 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.285 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     19.433 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.078 ms/op
Iteration   1: 2.057 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.295 ms/op
                 getUser·p0.50:   2.034 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   2.912 ms/op
                 getUser·p0.99:   3.601 ms/op
                 getUser·p0.999:  14.107 ms/op
                 getUser·p0.9999: 14.476 ms/op
                 getUser·p1.00:   14.549 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15588
  mean =      2.057 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 847 
    [ 1.250,  2.500) = 11207 
    [ 2.500,  3.750) = 3414 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.295 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      3.601 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     14.476 ms/op
     p(99.9990) =     14.549 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 5.508 ±(99.9%) 0.183 ms/op
Iteration   1: 3.452 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.975 ms/op
                 listUser·p0.999:  12.324 ms/op
                 listUser·p0.9999: 12.517 ms/op
                 listUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9268
  mean =      3.452 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 981 
    [ 2.500,  3.750) = 5805 
    [ 3.750,  5.000) = 2153 
    [ 5.000,  6.250) = 244 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.975 ms/op
     p(99.9000) =     12.324 ms/op
     p(99.9900) =     12.517 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.783          ops/ms
ClientSimple.existUser                       thrpt         11.866          ops/ms
ClientSimple.getUser                         thrpt         13.448          ops/ms
ClientSimple.listUser                        thrpt          8.820          ops/ms
ClientSimple.createUser                       avgt          2.209           ms/op
ClientSimple.existUser                        avgt          1.678           ms/op
ClientSimple.getUser                          avgt          2.121           ms/op
ClientSimple.listUser                         avgt          3.384           ms/op
ClientSimple.createUser                     sample  14353   2.226 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.720           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.974           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.564           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.233           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.427           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.760           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.470           ms/op
ClientSimple.existUser                      sample  16526   1.936 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.426           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.804           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.285           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.300           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.433           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.497           ms/op
ClientSimple.getUser                        sample  15588   2.057 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.295           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.034           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.601           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.107           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.476           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.549           ms/op
ClientSimple.listUser                       sample   9268   3.452 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.848           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.486           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.975           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.324           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.517           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.517           ms/op

Benchmark result is saved to 1712513097989.json
