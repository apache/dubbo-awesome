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
# Warmup Iteration   1: 0.654 ops/ms
Iteration   1: 5.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.836 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.866 ops/ms
Iteration   1: 11.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.985 ops/ms


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
# Warmup Iteration   1: 6.514 ops/ms
Iteration   1: 13.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.787 ops/ms


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
# Warmup Iteration   1: 6.043 ops/ms
Iteration   1: 8.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.984 ops/ms


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.060 ms/op
Iteration   1: 2.464 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.464 ms/op


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
# Warmup Iteration   1: 3.639 ±(99.9%) 0.063 ms/op
Iteration   1: 1.947 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.947 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.204 ±(99.9%) 0.068 ms/op
Iteration   1: 1.984 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.984 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.424 ±(99.9%) 0.083 ms/op
Iteration   1: 3.301 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.301 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.557 ±(99.9%) 0.083 ms/op
Iteration   1: 2.319 ±(99.9%) 0.070 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   2.011 ms/op
                 createUser·p0.90:   2.486 ms/op
                 createUser·p0.95:   2.724 ms/op
                 createUser·p0.99:   12.648 ms/op
                 createUser·p0.999:  37.749 ms/op
                 createUser·p0.9999: 39.089 ms/op
                 createUser·p1.00:   39.453 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13965
  mean =      2.319 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12632 
    [ 2.500,  5.000) = 1007 
    [ 5.000,  7.500) = 13 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =     12.648 ms/op
     p(99.9000) =     37.749 ms/op
     p(99.9900) =     39.089 ms/op
     p(99.9990) =     39.453 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


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
# Warmup Iteration   1: 3.324 ±(99.9%) 0.071 ms/op
Iteration   1: 1.744 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.451 ms/op
                 existUser·p0.50:   1.655 ms/op
                 existUser·p0.90:   2.093 ms/op
                 existUser·p0.95:   2.273 ms/op
                 existUser·p0.99:   3.055 ms/op
                 existUser·p0.999:  14.303 ms/op
                 existUser·p0.9999: 14.860 ms/op
                 existUser·p1.00:   15.024 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18326
  mean =      1.744 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 447 
    [ 1.250,  2.500) = 17415 
    [ 2.500,  3.750) = 327 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      1.655 ms/op
     p(90.0000) =      2.093 ms/op
     p(95.0000) =      2.273 ms/op
     p(99.0000) =      3.055 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     14.860 ms/op
     p(99.9990) =     15.024 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 2.985 ±(99.9%) 0.077 ms/op
Iteration   1: 1.943 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   1.768 ms/op
                 getUser·p0.90:   2.503 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   3.271 ms/op
                 getUser·p0.999:  20.427 ms/op
                 getUser·p0.9999: 21.508 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16538
  mean =      1.943 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14865 
    [ 2.500,  5.000) = 1572 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      1.768 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.271 ms/op
     p(99.9000) =     20.427 ms/op
     p(99.9900) =     21.508 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.120 ms/op
Iteration   1: 3.425 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.367 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.373 ms/op
                 listUser·p0.999:  17.397 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9357
  mean =      3.425 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 522 
    [ 2.500,  3.750) = 6289 
    [ 3.750,  5.000) = 2176 
    [ 5.000,  6.250) = 252 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     17.397 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.836          ops/ms
ClientSimple.existUser                       thrpt         11.985          ops/ms
ClientSimple.getUser                         thrpt         13.787          ops/ms
ClientSimple.listUser                        thrpt          8.984          ops/ms
ClientSimple.createUser                       avgt          2.464           ms/op
ClientSimple.existUser                        avgt          1.947           ms/op
ClientSimple.getUser                          avgt          1.984           ms/op
ClientSimple.listUser                         avgt          3.301           ms/op
ClientSimple.createUser                     sample  13965   2.319 ± 0.070   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.614           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.011           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.486           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.648           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.749           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.089           ms/op
ClientSimple.createUser:createUser·p1.00    sample         39.453           ms/op
ClientSimple.existUser                      sample  18326   1.744 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.451           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.655           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.093           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.055           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.303           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.860           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.024           ms/op
ClientSimple.getUser                        sample  16538   1.943 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.613           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.768           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.271           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.427           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.508           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.594           ms/op
ClientSimple.listUser                       sample   9357   3.425 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.278           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.367           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.178           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.373           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.397           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.564           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.564           ms/op

Benchmark result is saved to 1713399309451.json
