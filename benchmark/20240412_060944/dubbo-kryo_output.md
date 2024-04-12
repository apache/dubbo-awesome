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
# Warmup Iteration   1: 1.678 ops/ms
Iteration   1: 7.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.296 ops/ms


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
# Warmup Iteration   1: 7.019 ops/ms
Iteration   1: 12.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.067 ops/ms


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
# Warmup Iteration   1: 6.569 ops/ms
Iteration   1: 13.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.666 ops/ms


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
# Warmup Iteration   1: 5.361 ops/ms
Iteration   1: 8.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.098 ops/ms


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.061 ms/op
Iteration   1: 2.014 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.014 ms/op


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
# Warmup Iteration   1: 3.237 ±(99.9%) 0.048 ms/op
Iteration   1: 1.890 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.890 ms/op


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
# Warmup Iteration   1: 3.419 ±(99.9%) 0.063 ms/op
Iteration   1: 1.966 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.966 ms/op


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
# Warmup Iteration   1: 5.340 ±(99.9%) 0.111 ms/op
Iteration   1: 3.458 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.458 ms/op


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
# Warmup Iteration   1: 3.348 ±(99.9%) 0.084 ms/op
Iteration   1: 2.093 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.515 ms/op
                 createUser·p0.50:   1.858 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.314 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 19.966 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15433
  mean =      2.093 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12539 
    [ 2.500,  5.000) = 2812 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.314 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     19.966 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 3.199 ±(99.9%) 0.084 ms/op
Iteration   1: 1.855 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.302 ms/op
                 existUser·p0.50:   1.737 ms/op
                 existUser·p0.90:   2.224 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   3.782 ms/op
                 existUser·p0.999:  19.562 ms/op
                 existUser·p0.9999: 19.963 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17572
  mean =      1.855 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16884 
    [ 2.500,  5.000) = 596 
    [ 5.000,  7.500) = 58 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.302 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      3.782 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     19.963 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 3.302 ±(99.9%) 0.083 ms/op
Iteration   1: 2.289 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   2.171 ms/op
                 getUser·p0.90:   2.855 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   5.537 ms/op
                 getUser·p0.999:  12.386 ms/op
                 getUser·p0.9999: 12.606 ms/op
                 getUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14001
  mean =      2.289 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 10487 
    [ 2.500,  3.750) = 3199 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.855 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      5.537 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     12.606 ms/op
     p(99.9990) =     12.632 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


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
# Warmup Iteration   1: 4.514 ±(99.9%) 0.139 ms/op
Iteration   1: 3.108 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.011 ms/op
                 listUser·p0.999:  11.862 ms/op
                 listUser·p0.9999: 12.026 ms/op
                 listUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10327
  mean =      3.108 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 442 
    [ 2.500,  3.750) = 8708 
    [ 3.750,  5.000) = 961 
    [ 5.000,  6.250) = 118 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.011 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     12.026 ms/op
     p(99.9990) =     12.026 ms/op
     p(99.9999) =     12.026 ms/op
    p(100.0000) =     12.026 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.296          ops/ms
ClientSimple.existUser                       thrpt         12.067          ops/ms
ClientSimple.getUser                         thrpt         13.666          ops/ms
ClientSimple.listUser                        thrpt          8.098          ops/ms
ClientSimple.createUser                       avgt          2.014           ms/op
ClientSimple.existUser                        avgt          1.890           ms/op
ClientSimple.getUser                          avgt          1.966           ms/op
ClientSimple.listUser                         avgt          3.458           ms/op
ClientSimple.createUser                     sample  15433   2.093 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.515           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.858           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.080           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.314           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.145           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.300           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.966           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.251           ms/op
ClientSimple.existUser                      sample  17572   1.855 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.302           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.737           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.782           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.562           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.963           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.087           ms/op
ClientSimple.getUser                        sample  14001   2.289 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.553           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.171           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.113           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.537           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.386           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.606           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.632           ms/op
ClientSimple.listUser                       sample  10327   3.108 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.848           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.888           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.826           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.011           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.862           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.026           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.026           ms/op

Benchmark result is saved to 1712901926171.json
