# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.086 ops/ms
Iteration   1: 7.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.141 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.117 ops/ms
Iteration   1: 12.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.594 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.051 ops/ms
Iteration   1: 13.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.373 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.993 ops/ms
Iteration   1: 8.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.623 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.544 ±(99.9%) 0.072 ms/op
Iteration   1: 2.224 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.224 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.189 ±(99.9%) 0.042 ms/op
Iteration   1: 1.810 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.810 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.241 ±(99.9%) 0.057 ms/op
Iteration   1: 1.979 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.979 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.672 ±(99.9%) 0.099 ms/op
Iteration   1: 3.413 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.413 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.286 ±(99.9%) 0.076 ms/op
Iteration   1: 2.267 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   1.966 ms/op
                 createUser·p0.90:   2.839 ms/op
                 createUser·p0.95:   3.362 ms/op
                 createUser·p0.99:   8.118 ms/op
                 createUser·p0.999:  30.231 ms/op
                 createUser·p0.9999: 31.772 ms/op
                 createUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14104
  mean =      2.267 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10867 
    [ 2.500,  5.000) = 2873 
    [ 5.000,  7.500) = 156 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.362 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     30.231 ms/op
     p(99.9900) =     31.772 ms/op
     p(99.9990) =     31.785 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.968 ±(99.9%) 0.075 ms/op
Iteration   1: 1.970 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   1.950 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   3.240 ms/op
                 existUser·p0.999:  18.199 ms/op
                 existUser·p0.9999: 19.051 ms/op
                 existUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16207
  mean =      1.970 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 885 
    [ 1.250,  2.500) = 14401 
    [ 2.500,  3.750) = 806 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.950 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      3.240 ms/op
     p(99.9000) =     18.199 ms/op
     p(99.9900) =     19.051 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.383 ±(99.9%) 0.082 ms/op
Iteration   1: 2.074 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.572 ms/op
                 getUser·p0.50:   1.995 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   4.349 ms/op
                 getUser·p0.999:  9.880 ms/op
                 getUser·p0.9999: 10.243 ms/op
                 getUser·p1.00:   10.306 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15412
  mean =      2.074 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 17 
    [ 1.000,  2.000) = 7763 
    [ 2.000,  3.000) = 7061 
    [ 3.000,  4.000) = 381 
    [ 4.000,  5.000) = 110 
    [ 5.000,  6.000) = 16 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 24 
    [ 8.000,  9.000) = 8 
    [ 9.000, 10.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      4.349 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     10.243 ms/op
     p(99.9990) =     10.306 ms/op
     p(99.9999) =     10.306 ms/op
    p(100.0000) =     10.306 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.264 ±(99.9%) 0.121 ms/op
Iteration   1: 3.463 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   5.461 ms/op
                 listUser·p0.999:  6.961 ms/op
                 listUser·p0.9999: 11.485 ms/op
                 listUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9238
  mean =      3.463 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1101 
    [ 2.500,  3.750) = 5165 
    [ 3.750,  5.000) = 2694 
    [ 5.000,  6.250) = 229 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.461 ms/op
     p(99.9000) =      6.961 ms/op
     p(99.9900) =     11.485 ms/op
     p(99.9990) =     11.485 ms/op
     p(99.9999) =     11.485 ms/op
    p(100.0000) =     11.485 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.141          ops/ms
ClientSimple.existUser                       thrpt         12.594          ops/ms
ClientSimple.getUser                         thrpt         13.373          ops/ms
ClientSimple.listUser                        thrpt          8.623          ops/ms
ClientSimple.createUser                       avgt          2.224           ms/op
ClientSimple.existUser                        avgt          1.810           ms/op
ClientSimple.getUser                          avgt          1.979           ms/op
ClientSimple.listUser                         avgt          3.413           ms/op
ClientSimple.createUser                     sample  14104   2.267 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.530           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.966           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.362           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.118           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.231           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.772           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.785           ms/op
ClientSimple.existUser                      sample  16207   1.970 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.511           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.950           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.240           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.199           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.051           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.071           ms/op
ClientSimple.getUser                        sample  15412   2.074 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.572           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.995           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.349           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.880           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.243           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.306           ms/op
ClientSimple.listUser                       sample   9238   3.463 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.962           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.461           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.961           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.485           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.485           ms/op

Benchmark result is saved to 1719986807803.json
