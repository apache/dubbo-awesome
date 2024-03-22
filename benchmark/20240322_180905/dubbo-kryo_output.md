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
# Warmup Iteration   1: 1.580 ops/ms
Iteration   1: 7.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.406 ops/ms


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
# Warmup Iteration   1: 5.940 ops/ms
Iteration   1: 10.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.131 ops/ms


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
# Warmup Iteration   1: 6.000 ops/ms
Iteration   1: 12.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.529 ops/ms


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
# Warmup Iteration   1: 4.267 ops/ms
Iteration   1: 8.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.576 ops/ms


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.075 ms/op
Iteration   1: 2.277 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.277 ms/op


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
# Warmup Iteration   1: 3.272 ±(99.9%) 0.051 ms/op
Iteration   1: 1.775 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.775 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.057 ms/op
Iteration   1: 1.921 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.921 ms/op


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
# Warmup Iteration   1: 4.721 ±(99.9%) 0.091 ms/op
Iteration   1: 3.564 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.564 ms/op


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
# Warmup Iteration   1: 3.654 ±(99.9%) 0.094 ms/op
Iteration   1: 1.919 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   1.745 ms/op
                 createUser·p0.90:   2.408 ms/op
                 createUser·p0.95:   2.556 ms/op
                 createUser·p0.99:   3.381 ms/op
                 createUser·p0.999:  22.305 ms/op
                 createUser·p0.9999: 24.631 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16658
  mean =      1.919 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15566 
    [ 2.500,  5.000) = 962 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.381 ms/op
     p(99.9000) =     22.305 ms/op
     p(99.9900) =     24.631 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 3.087 ±(99.9%) 0.074 ms/op
Iteration   1: 2.025 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.504 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.621 ms/op
                 existUser·p0.95:   2.757 ms/op
                 existUser·p0.99:   2.998 ms/op
                 existUser·p0.999:  16.682 ms/op
                 existUser·p0.9999: 17.469 ms/op
                 existUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15803
  mean =      2.025 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 409 
    [ 1.250,  2.500) = 13060 
    [ 2.500,  3.750) = 2285 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      2.998 ms/op
     p(99.9000) =     16.682 ms/op
     p(99.9900) =     17.469 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.261 ±(99.9%) 0.098 ms/op
Iteration   1: 2.133 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   2.009 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   2.867 ms/op
                 getUser·p0.99:   5.564 ms/op
                 getUser·p0.999:  17.760 ms/op
                 getUser·p0.9999: 18.514 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14978
  mean =      2.133 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 324 
    [ 1.250,  2.500) = 12511 
    [ 2.500,  3.750) = 1844 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      5.564 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 4.287 ±(99.9%) 0.141 ms/op
Iteration   1: 3.481 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.375 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.087 ms/op
                 listUser·p0.999:  26.536 ms/op
                 listUser·p0.9999: 27.460 ms/op
                 listUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9199
  mean =      3.481 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 675 
    [ 2.500,  5.000) = 8409 
    [ 5.000,  7.500) = 82 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.087 ms/op
     p(99.9000) =     26.536 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.406          ops/ms
ClientSimple.existUser                       thrpt         10.131          ops/ms
ClientSimple.getUser                         thrpt         12.529          ops/ms
ClientSimple.listUser                        thrpt          8.576          ops/ms
ClientSimple.createUser                       avgt          2.277           ms/op
ClientSimple.existUser                        avgt          1.775           ms/op
ClientSimple.getUser                          avgt          1.921           ms/op
ClientSimple.listUser                         avgt          3.564           ms/op
ClientSimple.createUser                     sample  16658   1.919 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.640           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.745           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.408           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.381           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.305           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.631           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.740           ms/op
ClientSimple.existUser                      sample  15803   2.025 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.504           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.757           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.998           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.682           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.469           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.564           ms/op
ClientSimple.getUser                        sample  14978   2.133 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.686           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.009           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.867           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.564           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.760           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.514           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.514           ms/op
ClientSimple.listUser                       sample   9199   3.481 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.313           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.375           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.087           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.536           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.460           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.460           ms/op

Benchmark result is saved to 1711130695281.json
