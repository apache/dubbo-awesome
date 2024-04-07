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
# Warmup Iteration   1: 1.601 ops/ms
Iteration   1: 5.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.614 ops/ms


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
# Warmup Iteration   1: 5.692 ops/ms
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
# Warmup Iteration   1: 5.860 ops/ms
Iteration   1: 13.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.000 ops/ms


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
# Warmup Iteration   1: 4.352 ops/ms
Iteration   1: 8.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.597 ops/ms


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.075 ms/op
Iteration   1: 2.313 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.313 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.057 ms/op
Iteration   1: 1.761 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.761 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.055 ms/op
Iteration   1: 2.148 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.148 ms/op


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
# Warmup Iteration   1: 4.216 ±(99.9%) 0.075 ms/op
Iteration   1: 3.638 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.638 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.105 ms/op
Iteration   1: 2.287 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   2.017 ms/op
                 createUser·p0.90:   2.671 ms/op
                 createUser·p0.95:   3.313 ms/op
                 createUser·p0.99:   8.978 ms/op
                 createUser·p0.999:  35.517 ms/op
                 createUser·p0.9999: 35.822 ms/op
                 createUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14060
  mean =      2.287 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12002 
    [ 2.500,  5.000) = 1672 
    [ 5.000,  7.500) = 180 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      3.313 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     35.517 ms/op
     p(99.9900) =     35.822 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 3.151 ±(99.9%) 0.085 ms/op
Iteration   1: 1.933 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.432 ms/op
                 existUser·p0.50:   1.884 ms/op
                 existUser·p0.90:   2.372 ms/op
                 existUser·p0.95:   2.511 ms/op
                 existUser·p0.99:   3.369 ms/op
                 existUser·p0.999:  16.537 ms/op
                 existUser·p0.9999: 17.335 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16560
  mean =      1.933 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1068 
    [ 1.250,  2.500) = 14635 
    [ 2.500,  3.750) = 708 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      3.369 ms/op
     p(99.9000) =     16.537 ms/op
     p(99.9900) =     17.335 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.083 ms/op
Iteration   1: 2.149 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.230 ms/op
                 getUser·p0.50:   1.993 ms/op
                 getUser·p0.90:   2.826 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   4.150 ms/op
                 getUser·p0.999:  13.798 ms/op
                 getUser·p0.9999: 14.051 ms/op
                 getUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14858
  mean =      2.149 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 11412 
    [ 2.500,  3.750) = 3115 
    [ 3.750,  5.000) = 120 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.230 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      4.150 ms/op
     p(99.9000) =     13.798 ms/op
     p(99.9900) =     14.051 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 5.004 ±(99.9%) 0.159 ms/op
Iteration   1: 3.524 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.154 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  18.317 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9080
  mean =      3.524 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 290 
    [ 2.500,  3.750) = 5923 
    [ 3.750,  5.000) = 2379 
    [ 5.000,  6.250) = 338 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.614          ops/ms
ClientSimple.existUser                       thrpt         12.432          ops/ms
ClientSimple.getUser                         thrpt         13.000          ops/ms
ClientSimple.listUser                        thrpt          8.597          ops/ms
ClientSimple.createUser                       avgt          2.313           ms/op
ClientSimple.existUser                        avgt          1.761           ms/op
ClientSimple.getUser                          avgt          2.148           ms/op
ClientSimple.listUser                         avgt          3.638           ms/op
ClientSimple.createUser                     sample  14060   2.287 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.736           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.017           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.313           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.978           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.517           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.822           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.848           ms/op
ClientSimple.existUser                      sample  16560   1.933 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.432           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.884           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.369           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.537           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.335           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.400           ms/op
ClientSimple.getUser                        sample  14858   2.149 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.230           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.993           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.072           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.150           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.798           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.051           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.123           ms/op
ClientSimple.listUser                       sample   9080   3.524 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.384           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.154           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.079           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.414           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.317           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.366           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.366           ms/op

Benchmark result is saved to 1712491531842.json
