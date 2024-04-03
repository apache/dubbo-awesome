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
# Warmup Iteration   1: 1.653 ops/ms
Iteration   1: 7.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.437 ops/ms


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
# Warmup Iteration   1: 5.741 ops/ms
Iteration   1: 12.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.929 ops/ms


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
# Warmup Iteration   1: 4.986 ops/ms
Iteration   1: 12.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.984 ops/ms


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
# Warmup Iteration   1: 5.408 ops/ms
Iteration   1: 8.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.350 ops/ms


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.073 ms/op
Iteration   1: 2.081 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.081 ms/op


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
# Warmup Iteration   1: 3.334 ±(99.9%) 0.054 ms/op
Iteration   1: 2.070 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.070 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.054 ms/op
Iteration   1: 1.969 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.969 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.101 ms/op
Iteration   1: 3.651 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.651 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.092 ms/op
Iteration   1: 2.212 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.435 ms/op
                 createUser·p0.50:   1.985 ms/op
                 createUser·p0.90:   2.462 ms/op
                 createUser·p0.95:   2.736 ms/op
                 createUser·p0.99:   8.270 ms/op
                 createUser·p0.999:  28.395 ms/op
                 createUser·p0.9999: 29.346 ms/op
                 createUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14448
  mean =      2.212 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13193 
    [ 2.500,  5.000) = 1032 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      8.270 ms/op
     p(99.9000) =     28.395 ms/op
     p(99.9900) =     29.346 ms/op
     p(99.9990) =     29.360 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 2.890 ±(99.9%) 0.063 ms/op
Iteration   1: 1.984 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.244 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  20.608 ms/op
                 existUser·p0.9999: 21.476 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16103
  mean =      1.984 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14464 
    [ 2.500,  5.000) = 1542 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.244 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =     20.608 ms/op
     p(99.9900) =     21.476 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.087 ms/op
Iteration   1: 2.098 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   1.892 ms/op
                 getUser·p0.90:   2.441 ms/op
                 getUser·p0.95:   2.712 ms/op
                 getUser·p0.99:   11.987 ms/op
                 getUser·p0.999:  25.068 ms/op
                 getUser·p0.9999: 27.198 ms/op
                 getUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15266
  mean =      2.098 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14037 
    [ 2.500,  5.000) = 1052 
    [ 5.000,  7.500) = 16 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =     11.987 ms/op
     p(99.9000) =     25.068 ms/op
     p(99.9900) =     27.198 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 5.337 ±(99.9%) 0.264 ms/op
Iteration   1: 3.472 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   0.720 ms/op
                 listUser·p0.50:   3.281 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   10.303 ms/op
                 listUser·p0.999:  21.692 ms/op
                 listUser·p0.9999: 24.576 ms/op
                 listUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9207
  mean =      3.472 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2048 
    [ 2.500,  5.000) = 6740 
    [ 5.000,  7.500) = 256 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =     10.303 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.437          ops/ms
ClientSimple.existUser                       thrpt         12.929          ops/ms
ClientSimple.getUser                         thrpt         12.984          ops/ms
ClientSimple.listUser                        thrpt          8.350          ops/ms
ClientSimple.createUser                       avgt          2.081           ms/op
ClientSimple.existUser                        avgt          2.070           ms/op
ClientSimple.getUser                          avgt          1.969           ms/op
ClientSimple.listUser                         avgt          3.651           ms/op
ClientSimple.createUser                     sample  14448   2.212 ± 0.053   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.435           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.985           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.736           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.270           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.395           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.346           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.360           ms/op
ClientSimple.existUser                      sample  16103   1.984 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.244           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.835           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.613           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.608           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.476           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.496           ms/op
ClientSimple.getUser                        sample  15266   2.098 ± 0.044   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.673           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.892           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.441           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.99          sample         11.987           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.068           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.198           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.803           ms/op
ClientSimple.listUser                       sample   9207   3.472 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.720           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.281           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.303           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.692           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.576           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.576           ms/op

Benchmark result is saved to 1712103303618.json
