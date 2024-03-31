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
# Warmup Iteration   1: 1.695 ops/ms
Iteration   1: 7.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.197 ops/ms


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
# Warmup Iteration   1: 6.559 ops/ms
Iteration   1: 13.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.280 ops/ms


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
# Warmup Iteration   1: 6.935 ops/ms
Iteration   1: 12.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.005 ops/ms


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
# Warmup Iteration   1: 5.165 ops/ms
Iteration   1: 8.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.825 ops/ms


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.081 ms/op
Iteration   1: 2.448 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.448 ms/op


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
# Warmup Iteration   1: 3.432 ±(99.9%) 0.065 ms/op
Iteration   1: 1.957 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.957 ms/op


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
# Warmup Iteration   1: 3.149 ±(99.9%) 0.063 ms/op
Iteration   1: 1.826 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.826 ms/op


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.070 ms/op
Iteration   1: 3.155 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.155 ms/op


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
# Warmup Iteration   1: 3.355 ±(99.9%) 0.094 ms/op
Iteration   1: 2.152 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   1.993 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   3.011 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  13.631 ms/op
                 createUser·p0.9999: 13.713 ms/op
                 createUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14857
  mean =      2.152 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 12488 
    [ 2.500,  3.750) = 1886 
    [ 3.750,  5.000) = 234 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 2.918 ±(99.9%) 0.069 ms/op
Iteration   1: 1.988 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.368 ms/op
                 existUser·p0.50:   1.917 ms/op
                 existUser·p0.90:   2.372 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   4.901 ms/op
                 existUser·p0.999:  15.628 ms/op
                 existUser·p0.9999: 16.178 ms/op
                 existUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16130
  mean =      1.988 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 430 
    [ 1.250,  2.500) = 14966 
    [ 2.500,  3.750) = 523 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      4.901 ms/op
     p(99.9000) =     15.628 ms/op
     p(99.9900) =     16.178 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 3.350 ±(99.9%) 0.073 ms/op
Iteration   1: 2.080 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   1.917 ms/op
                 getUser·p0.90:   2.548 ms/op
                 getUser·p0.95:   2.691 ms/op
                 getUser·p0.99:   3.379 ms/op
                 getUser·p0.999:  19.020 ms/op
                 getUser·p0.9999: 20.210 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15563
  mean =      2.080 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13683 
    [ 2.500,  5.000) = 1814 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      3.379 ms/op
     p(99.9000) =     19.020 ms/op
     p(99.9900) =     20.210 ms/op
     p(99.9990) =     20.283 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.124 ms/op
Iteration   1: 3.478 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.449 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   5.389 ms/op
                 listUser·p0.999:  7.437 ms/op
                 listUser·p0.9999: 7.668 ms/op
                 listUser·p1.00:   7.668 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9204
  mean =      3.478 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 12 
    [1.500, 2.000) = 67 
    [2.000, 2.500) = 181 
    [2.500, 3.000) = 3266 
    [3.000, 3.500) = 1206 
    [3.500, 4.000) = 2088 
    [4.000, 4.500) = 1680 
    [4.500, 5.000) = 489 
    [5.000, 5.500) = 140 
    [5.500, 6.000) = 35 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.389 ms/op
     p(99.9000) =      7.437 ms/op
     p(99.9900) =      7.668 ms/op
     p(99.9990) =      7.668 ms/op
     p(99.9999) =      7.668 ms/op
    p(100.0000) =      7.668 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.197          ops/ms
ClientSimple.existUser                       thrpt         13.280          ops/ms
ClientSimple.getUser                         thrpt         12.005          ops/ms
ClientSimple.listUser                        thrpt          8.825          ops/ms
ClientSimple.createUser                       avgt          2.448           ms/op
ClientSimple.existUser                        avgt          1.957           ms/op
ClientSimple.getUser                          avgt          1.826           ms/op
ClientSimple.listUser                         avgt          3.155           ms/op
ClientSimple.createUser                     sample  14857   2.152 ± 0.022   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.768           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.993           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.011           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.169           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.631           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.713           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.713           ms/op
ClientSimple.existUser                      sample  16130   1.988 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.368           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.917           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.901           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.628           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.178           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.318           ms/op
ClientSimple.getUser                        sample  15563   2.080 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.741           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.917           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.379           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.020           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.210           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.283           ms/op
ClientSimple.listUser                       sample   9204   3.478 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.139           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.449           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.389           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.437           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.668           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.668           ms/op

Benchmark result is saved to 1711844215203.json
