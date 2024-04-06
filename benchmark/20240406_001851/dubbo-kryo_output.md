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
# Warmup Iteration   1: 1.598 ops/ms
Iteration   1: 7.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.146 ops/ms


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
# Warmup Iteration   1: 6.237 ops/ms
Iteration   1: 12.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.489 ops/ms


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
# Warmup Iteration   1: 5.567 ops/ms
Iteration   1: 13.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.801 ops/ms


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
# Warmup Iteration   1: 5.220 ops/ms
Iteration   1: 8.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.470 ops/ms


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
# Warmup Iteration   1: 4.197 ±(99.9%) 0.075 ms/op
Iteration   1: 2.333 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.333 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.043 ms/op
Iteration   1: 1.679 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.679 ms/op


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
# Warmup Iteration   1: 3.109 ±(99.9%) 0.055 ms/op
Iteration   1: 2.188 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.188 ms/op


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
# Warmup Iteration   1: 4.708 ±(99.9%) 0.092 ms/op
Iteration   1: 3.403 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.403 ms/op


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.269 ms/op
Iteration   1: 2.336 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   2.130 ms/op
                 createUser·p0.90:   2.834 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   9.224 ms/op
                 createUser·p0.999:  13.140 ms/op
                 createUser·p0.9999: 14.828 ms/op
                 createUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13685
  mean =      2.336 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 11021 
    [ 2.500,  3.750) = 1954 
    [ 3.750,  5.000) = 171 
    [ 5.000,  6.250) = 157 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.834 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     14.828 ms/op
     p(99.9990) =     14.828 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.083 ms/op
Iteration   1: 2.032 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   1.921 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   4.924 ms/op
                 existUser·p0.999:  14.893 ms/op
                 existUser·p0.9999: 14.991 ms/op
                 existUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15820
  mean =      2.032 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 14548 
    [ 2.500,  3.750) = 932 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      4.924 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     14.991 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.081 ms/op
Iteration   1: 1.890 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   1.821 ms/op
                 getUser·p0.90:   2.310 ms/op
                 getUser·p0.95:   2.519 ms/op
                 getUser·p0.99:   3.207 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 12.485 ms/op
                 getUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17032
  mean =      1.890 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 244 
    [ 1.250,  2.500) = 15893 
    [ 2.500,  3.750) = 816 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.207 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     12.485 ms/op
     p(99.9990) =     12.681 ms/op
     p(99.9999) =     12.681 ms/op
    p(100.0000) =     12.681 ms/op


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.146 ms/op
Iteration   1: 3.383 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.133 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  6.334 ms/op
                 listUser·p0.9999: 6.873 ms/op
                 listUser·p1.00:   6.873 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9516
  mean =      3.383 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 11 
    [1.500, 2.000) = 55 
    [2.000, 2.500) = 527 
    [2.500, 3.000) = 3590 
    [3.000, 3.500) = 1414 
    [3.500, 4.000) = 1630 
    [4.000, 4.500) = 1567 
    [4.500, 5.000) = 447 
    [5.000, 5.500) = 186 
    [5.500, 6.000) = 69 
    [6.000, 6.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      6.334 ms/op
     p(99.9900) =      6.873 ms/op
     p(99.9990) =      6.873 ms/op
     p(99.9999) =      6.873 ms/op
    p(100.0000) =      6.873 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.146          ops/ms
ClientSimple.existUser                       thrpt         12.489          ops/ms
ClientSimple.getUser                         thrpt         13.801          ops/ms
ClientSimple.listUser                        thrpt          8.470          ops/ms
ClientSimple.createUser                       avgt          2.333           ms/op
ClientSimple.existUser                        avgt          1.679           ms/op
ClientSimple.getUser                          avgt          2.188           ms/op
ClientSimple.listUser                         avgt          3.403           ms/op
ClientSimple.createUser                     sample  13685   2.336 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.757           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.130           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.506           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.224           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.140           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.828           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.828           ms/op
ClientSimple.existUser                      sample  15820   2.032 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.756           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.921           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.924           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.893           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.991           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.991           ms/op
ClientSimple.getUser                        sample  17032   1.890 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.588           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.821           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.310           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.207           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.059           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.485           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.681           ms/op
ClientSimple.listUser                       sample   9516   3.383 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.077           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.133           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.489           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.334           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.873           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.873           ms/op

Benchmark result is saved to 1712362457850.json
