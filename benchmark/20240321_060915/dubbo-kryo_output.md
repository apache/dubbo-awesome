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
# Warmup Iteration   1: 1.585 ops/ms
Iteration   1: 7.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.056 ops/ms


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
# Warmup Iteration   1: 6.247 ops/ms
Iteration   1: 14.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.063 ops/ms


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
# Warmup Iteration   1: 5.754 ops/ms
Iteration   1: 12.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.083 ops/ms


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
# Warmup Iteration   1: 4.762 ops/ms
Iteration   1: 8.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.917 ops/ms


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.091 ms/op
Iteration   1: 2.099 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.099 ms/op


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
# Warmup Iteration   1: 3.620 ±(99.9%) 0.052 ms/op
Iteration   1: 1.989 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.989 ms/op


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
# Warmup Iteration   1: 3.462 ±(99.9%) 0.062 ms/op
Iteration   1: 2.045 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.045 ms/op


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
# Warmup Iteration   1: 4.540 ±(99.9%) 0.093 ms/op
Iteration   1: 3.733 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.733 ms/op


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
# Warmup Iteration   1: 3.371 ±(99.9%) 0.079 ms/op
Iteration   1: 2.120 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   2.497 ms/op
                 createUser·p0.95:   2.879 ms/op
                 createUser·p0.99:   11.468 ms/op
                 createUser·p0.999:  19.759 ms/op
                 createUser·p0.9999: 20.349 ms/op
                 createUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15104
  mean =      2.120 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13598 
    [ 2.500,  5.000) = 1260 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.497 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =     11.468 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 2.949 ±(99.9%) 0.068 ms/op
Iteration   1: 1.876 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.425 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.421 ms/op
                 existUser·p0.99:   3.191 ms/op
                 existUser·p0.999:  16.941 ms/op
                 existUser·p0.9999: 17.039 ms/op
                 existUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17264
  mean =      1.876 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 614 
    [ 1.250,  2.500) = 16067 
    [ 2.500,  3.750) = 454 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.421 ms/op
     p(99.0000) =      3.191 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.269 ±(99.9%) 0.080 ms/op
Iteration   1: 1.912 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   1.823 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.720 ms/op
                 getUser·p0.99:   4.023 ms/op
                 getUser·p0.999:  10.736 ms/op
                 getUser·p0.9999: 11.350 ms/op
                 getUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16742
  mean =      1.912 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 652 
    [ 1.250,  2.500) = 14512 
    [ 2.500,  3.750) = 1386 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      4.023 ms/op
     p(99.9000) =     10.736 ms/op
     p(99.9900) =     11.350 ms/op
     p(99.9990) =     12.222 ms/op
     p(99.9999) =     12.222 ms/op
    p(100.0000) =     12.222 ms/op


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
# Warmup Iteration   1: 4.565 ±(99.9%) 0.150 ms/op
Iteration   1: 3.155 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   2.822 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  20.566 ms/op
                 listUser·p0.9999: 21.757 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10126
  mean =      3.155 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 689 
    [ 2.500,  5.000) = 9271 
    [ 5.000,  7.500) = 107 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     20.566 ms/op
     p(99.9900) =     21.757 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.056          ops/ms
ClientSimple.existUser                       thrpt         14.063          ops/ms
ClientSimple.getUser                         thrpt         12.083          ops/ms
ClientSimple.listUser                        thrpt          8.917          ops/ms
ClientSimple.createUser                       avgt          2.099           ms/op
ClientSimple.existUser                        avgt          1.989           ms/op
ClientSimple.getUser                          avgt          2.045           ms/op
ClientSimple.listUser                         avgt          3.733           ms/op
ClientSimple.createUser                     sample  15104   2.120 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.599           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.497           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.468           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.759           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.349           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.349           ms/op
ClientSimple.existUser                      sample  17264   1.876 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.425           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.191           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.941           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.039           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.039           ms/op
ClientSimple.getUser                        sample  16742   1.912 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.777           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.823           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.023           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.736           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.350           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.222           ms/op
ClientSimple.listUser                       sample  10126   3.155 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.417           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.822           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.051           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.530           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.566           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.757           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.758           ms/op

Benchmark result is saved to 1711001100724.json
