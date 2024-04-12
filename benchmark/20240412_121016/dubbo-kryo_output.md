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
# Warmup Iteration   1: 1.488 ops/ms
Iteration   1: 6.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.121 ops/ms


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
# Warmup Iteration   1: 6.162 ops/ms
Iteration   1: 12.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.033 ops/ms


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
# Warmup Iteration   1: 5.596 ops/ms
Iteration   1: 12.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.357 ops/ms


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
# Warmup Iteration   1: 4.237 ops/ms
Iteration   1: 8.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.485 ops/ms


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.072 ms/op
Iteration   1: 2.058 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.058 ms/op


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
# Warmup Iteration   1: 3.382 ±(99.9%) 0.080 ms/op
Iteration   1: 1.998 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.998 ms/op


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
# Warmup Iteration   1: 3.361 ±(99.9%) 0.074 ms/op
Iteration   1: 2.084 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.084 ms/op


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
# Warmup Iteration   1: 5.135 ±(99.9%) 0.095 ms/op
Iteration   1: 3.511 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.511 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.081 ms/op
Iteration   1: 2.219 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.632 ms/op
                 createUser·p0.50:   2.007 ms/op
                 createUser·p0.90:   2.773 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   6.816 ms/op
                 createUser·p0.999:  27.263 ms/op
                 createUser·p0.9999: 28.465 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14407
  mean =      2.219 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11845 
    [ 2.500,  5.000) = 2352 
    [ 5.000,  7.500) = 79 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.773 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     27.263 ms/op
     p(99.9900) =     28.465 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.111 ms/op
Iteration   1: 1.944 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.504 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.568 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  14.726 ms/op
                 existUser·p0.9999: 15.486 ms/op
                 existUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16582
  mean =      1.944 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 471 
    [ 1.250,  2.500) = 14134 
    [ 2.500,  3.750) = 1810 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =     14.726 ms/op
     p(99.9900) =     15.486 ms/op
     p(99.9990) =     15.712 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 3.229 ±(99.9%) 0.073 ms/op
Iteration   1: 2.265 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.289 ms/op
                 getUser·p0.50:   2.138 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   5.396 ms/op
                 getUser·p0.999:  23.876 ms/op
                 getUser·p0.9999: 25.010 ms/op
                 getUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14375
  mean =      2.265 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11514 
    [ 2.500,  5.000) = 2671 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.289 ms/op
     p(50.0000) =      2.138 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      5.396 ms/op
     p(99.9000) =     23.876 ms/op
     p(99.9900) =     25.010 ms/op
     p(99.9990) =     25.068 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 4.378 ±(99.9%) 0.150 ms/op
Iteration   1: 3.394 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.219 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  8.759 ms/op
                 listUser·p0.9999: 13.238 ms/op
                 listUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9420
  mean =      3.394 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 266 
    [ 2.500,  3.750) = 6673 
    [ 3.750,  5.000) = 2122 
    [ 5.000,  6.250) = 194 
    [ 6.250,  7.500) = 122 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =      8.759 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     13.238 ms/op
     p(99.9999) =     13.238 ms/op
    p(100.0000) =     13.238 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.121          ops/ms
ClientSimple.existUser                       thrpt         12.033          ops/ms
ClientSimple.getUser                         thrpt         12.357          ops/ms
ClientSimple.listUser                        thrpt          8.485          ops/ms
ClientSimple.createUser                       avgt          2.058           ms/op
ClientSimple.existUser                        avgt          1.998           ms/op
ClientSimple.getUser                          avgt          2.084           ms/op
ClientSimple.listUser                         avgt          3.511           ms/op
ClientSimple.createUser                     sample  14407   2.219 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.632           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.007           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.816           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.263           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.465           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.508           ms/op
ClientSimple.existUser                      sample  16582   1.944 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.504           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.802           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.781           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.726           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.486           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.712           ms/op
ClientSimple.getUser                        sample  14375   2.265 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.289           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.138           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.396           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.876           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.010           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.068           ms/op
ClientSimple.listUser                       sample   9420   3.394 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.307           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.219           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.865           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.759           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.238           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.238           ms/op

Benchmark result is saved to 1712923563592.json
