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
# Warmup Iteration   1: 1.659 ops/ms
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
# Warmup Iteration   1: 5.255 ops/ms
Iteration   1: 11.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.976 ops/ms


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
# Warmup Iteration   1: 5.346 ops/ms
Iteration   1: 12.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.055 ops/ms


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
# Warmup Iteration   1: 4.891 ops/ms
Iteration   1: 8.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.364 ops/ms


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
# Warmup Iteration   1: 4.204 ±(99.9%) 0.075 ms/op
Iteration   1: 2.302 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.302 ms/op


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
# Warmup Iteration   1: 2.854 ±(99.9%) 0.044 ms/op
Iteration   1: 1.802 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.802 ms/op


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
# Warmup Iteration   1: 3.417 ±(99.9%) 0.064 ms/op
Iteration   1: 2.187 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.187 ms/op


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.087 ms/op
Iteration   1: 3.253 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.253 ms/op


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.078 ms/op
Iteration   1: 2.489 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   2.253 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.367 ms/op
                 createUser·p0.99:   10.481 ms/op
                 createUser·p0.999:  14.967 ms/op
                 createUser·p0.9999: 17.128 ms/op
                 createUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12831
  mean =      2.489 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 8214 
    [ 2.500,  3.750) = 4122 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.253 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.367 ms/op
     p(99.0000) =     10.481 ms/op
     p(99.9000) =     14.967 ms/op
     p(99.9900) =     17.128 ms/op
     p(99.9990) =     17.138 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 2.768 ±(99.9%) 0.058 ms/op
Iteration   1: 1.715 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   1.589 ms/op
                 existUser·p0.90:   2.048 ms/op
                 existUser·p0.95:   2.214 ms/op
                 existUser·p0.99:   3.088 ms/op
                 existUser·p0.999:  18.481 ms/op
                 existUser·p0.9999: 18.693 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18850
  mean =      1.715 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 337 
    [ 1.250,  2.500) = 18203 
    [ 2.500,  3.750) = 184 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.589 ms/op
     p(90.0000) =      2.048 ms/op
     p(95.0000) =      2.214 ms/op
     p(99.0000) =      3.088 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     18.693 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 3.227 ±(99.9%) 0.078 ms/op
Iteration   1: 1.952 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.446 ms/op
                 getUser·p0.50:   1.884 ms/op
                 getUser·p0.90:   2.437 ms/op
                 getUser·p0.95:   2.621 ms/op
                 getUser·p0.99:   3.599 ms/op
                 getUser·p0.999:  11.633 ms/op
                 getUser·p0.9999: 12.017 ms/op
                 getUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16370
  mean =      1.952 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 326 
    [ 1.250,  2.500) = 14782 
    [ 2.500,  3.750) = 1122 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 5 
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
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.599 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     12.017 ms/op
     p(99.9990) =     12.059 ms/op
     p(99.9999) =     12.059 ms/op
    p(100.0000) =     12.059 ms/op


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.156 ms/op
Iteration   1: 3.119 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   2.834 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.988 ms/op
                 listUser·p0.999:  7.967 ms/op
                 listUser·p0.9999: 9.640 ms/op
                 listUser·p1.00:   9.650 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10247
  mean =      3.119 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 3 
    [ 1.500,  2.000) = 33 
    [ 2.000,  2.500) = 870 
    [ 2.500,  3.000) = 5105 
    [ 3.000,  3.500) = 1665 
    [ 3.500,  4.000) = 1650 
    [ 4.000,  4.500) = 529 
    [ 4.500,  5.000) = 163 
    [ 5.000,  5.500) = 37 
    [ 5.500,  6.000) = 94 
    [ 6.000,  6.500) = 77 
    [ 6.500,  7.000) = 4 
    [ 7.000,  7.500) = 0 
    [ 7.500,  8.000) = 10 
    [ 8.000,  8.500) = 4 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =      7.967 ms/op
     p(99.9900) =      9.640 ms/op
     p(99.9990) =      9.650 ms/op
     p(99.9999) =      9.650 ms/op
    p(100.0000) =      9.650 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.644          ops/ms
ClientSimple.existUser                       thrpt         11.976          ops/ms
ClientSimple.getUser                         thrpt         12.055          ops/ms
ClientSimple.listUser                        thrpt          8.364          ops/ms
ClientSimple.createUser                       avgt          2.302           ms/op
ClientSimple.existUser                        avgt          1.802           ms/op
ClientSimple.getUser                          avgt          2.187           ms/op
ClientSimple.listUser                         avgt          3.253           ms/op
ClientSimple.createUser                     sample  12831   2.489 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.731           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.253           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.088           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.367           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.481           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.967           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.128           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.138           ms/op
ClientSimple.existUser                      sample  18850   1.715 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.616           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.589           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.048           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.214           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.088           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.481           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.693           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.809           ms/op
ClientSimple.getUser                        sample  16370   1.952 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.446           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.884           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.437           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.599           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.633           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.017           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.059           ms/op
ClientSimple.listUser                       sample  10247   3.119 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.419           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.834           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.961           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.988           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.967           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.640           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.650           ms/op

Benchmark result is saved to 1710548038412.json
