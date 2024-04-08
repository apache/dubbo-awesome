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
# Warmup Iteration   1: 1.591 ops/ms
Iteration   1: 6.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.644 ops/ms


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
# Warmup Iteration   1: 6.502 ops/ms
Iteration   1: 11.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.529 ops/ms


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
# Warmup Iteration   1: 4.347 ops/ms
Iteration   1: 12.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.576 ops/ms


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
# Warmup Iteration   1: 4.680 ops/ms
Iteration   1: 8.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.068 ops/ms


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.072 ms/op
Iteration   1: 2.006 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.006 ms/op


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
# Warmup Iteration   1: 3.226 ±(99.9%) 0.054 ms/op
Iteration   1: 1.939 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.939 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.073 ms/op
Iteration   1: 2.205 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.205 ms/op


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
# Warmup Iteration   1: 4.864 ±(99.9%) 0.098 ms/op
Iteration   1: 3.913 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.913 ms/op


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
# Warmup Iteration   1: 3.366 ±(99.9%) 0.095 ms/op
Iteration   1: 2.009 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.495 ms/op
                 createUser·p0.50:   1.806 ms/op
                 createUser·p0.90:   2.617 ms/op
                 createUser·p0.95:   2.871 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  15.532 ms/op
                 createUser·p0.9999: 15.892 ms/op
                 createUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16007
  mean =      2.009 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 948 
    [ 1.250,  2.500) = 12768 
    [ 2.500,  3.750) = 2025 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     15.892 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 2.773 ±(99.9%) 0.056 ms/op
Iteration   1: 1.993 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.390 ms/op
                 existUser·p0.95:   2.535 ms/op
                 existUser·p0.99:   2.978 ms/op
                 existUser·p0.999:  19.721 ms/op
                 existUser·p0.9999: 20.513 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16083
  mean =      1.993 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15159 
    [ 2.500,  5.000) = 848 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.390 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      2.978 ms/op
     p(99.9000) =     19.721 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 3.294 ±(99.9%) 0.083 ms/op
Iteration   1: 2.266 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   2.126 ms/op
                 getUser·p0.90:   2.929 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.299 ms/op
                 getUser·p0.999:  15.448 ms/op
                 getUser·p0.9999: 15.626 ms/op
                 getUser·p1.00:   15.647 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14125
  mean =      2.266 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 9695 
    [ 2.500,  3.750) = 4112 
    [ 3.750,  5.000) = 111 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      4.299 ms/op
     p(99.9000) =     15.448 ms/op
     p(99.9900) =     15.626 ms/op
     p(99.9990) =     15.647 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.135 ms/op
Iteration   1: 3.436 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   3.375 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  14.729 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9331
  mean =      3.436 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1077 
    [ 2.500,  3.750) = 5438 
    [ 3.750,  5.000) = 2441 
    [ 5.000,  6.250) = 154 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.856 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.644          ops/ms
ClientSimple.existUser                       thrpt         11.529          ops/ms
ClientSimple.getUser                         thrpt         12.576          ops/ms
ClientSimple.listUser                        thrpt          8.068          ops/ms
ClientSimple.createUser                       avgt          2.006           ms/op
ClientSimple.existUser                        avgt          1.939           ms/op
ClientSimple.getUser                          avgt          2.205           ms/op
ClientSimple.listUser                         avgt          3.913           ms/op
ClientSimple.createUser                     sample  16007   2.009 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.495           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.806           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.617           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.792           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.532           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.892           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.892           ms/op
ClientSimple.existUser                      sample  16083   1.993 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.603           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.390           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.978           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.721           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.513           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.513           ms/op
ClientSimple.getUser                        sample  14125   2.266 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.645           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.126           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.158           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.299           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.448           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.626           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.647           ms/op
ClientSimple.listUser                       sample   9331   3.436 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.979           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.375           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.856           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.729           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.071           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.071           ms/op

Benchmark result is saved to 1712535328585.json
