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
# Warmup Iteration   1: 1.936 ops/ms
Iteration   1: 7.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.018 ops/ms


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
# Warmup Iteration   1: 5.541 ops/ms
Iteration   1: 11.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.298 ops/ms


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
# Warmup Iteration   1: 5.749 ops/ms
Iteration   1: 13.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.365 ops/ms


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
# Warmup Iteration   1: 5.353 ops/ms
Iteration   1: 8.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.373 ops/ms


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.079 ms/op
Iteration   1: 2.080 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.080 ms/op


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
# Warmup Iteration   1: 3.394 ±(99.9%) 0.053 ms/op
Iteration   1: 1.887 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.887 ms/op


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
# Warmup Iteration   1: 3.543 ±(99.9%) 0.066 ms/op
Iteration   1: 1.928 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.928 ms/op


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
# Warmup Iteration   1: 4.693 ±(99.9%) 0.098 ms/op
Iteration   1: 3.783 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.783 ms/op


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.111 ms/op
Iteration   1: 2.221 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.388 ms/op
                 createUser·p0.50:   2.054 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.859 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  19.025 ms/op
                 createUser·p0.9999: 21.449 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14397
  mean =      2.221 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12385 
    [ 2.500,  5.000) = 1808 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     19.025 ms/op
     p(99.9900) =     21.449 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.071 ms/op
Iteration   1: 2.291 ±(99.9%) 0.064 ms/op
                 existUser·p0.00:   0.218 ms/op
                 existUser·p0.50:   2.077 ms/op
                 existUser·p0.90:   2.810 ms/op
                 existUser·p0.95:   3.219 ms/op
                 existUser·p0.99:   9.391 ms/op
                 existUser·p0.999:  13.418 ms/op
                 existUser·p0.9999: 125.529 ms/op
                 existUser·p1.00:   128.975 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14172
  mean =      2.291 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 14110 
    [ 12.500,  25.000) = 58 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 3 
    [125.000, 137.500) = 1 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.218 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      9.391 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =    125.529 ms/op
     p(99.9990) =    128.975 ms/op
     p(99.9999) =    128.975 ms/op
    p(100.0000) =    128.975 ms/op


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
# Warmup Iteration   1: 3.355 ±(99.9%) 0.089 ms/op
Iteration   1: 2.329 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.477 ms/op
                 getUser·p0.50:   2.232 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.799 ms/op
                 getUser·p0.999:  22.249 ms/op
                 getUser·p0.9999: 23.411 ms/op
                 getUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13859
  mean =      2.329 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9936 
    [ 2.500,  5.000) = 3852 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.799 ms/op
     p(99.9000) =     22.249 ms/op
     p(99.9900) =     23.411 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.114 ms/op
Iteration   1: 3.204 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   4.119 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.412 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 18.710 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10124
  mean =      3.204 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 1189 
    [ 2.500,  3.750) = 6972 
    [ 3.750,  5.000) = 1667 
    [ 5.000,  6.250) = 163 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      4.119 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.412 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     18.710 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.018          ops/ms
ClientSimple.existUser                       thrpt          11.298          ops/ms
ClientSimple.getUser                         thrpt          13.365          ops/ms
ClientSimple.listUser                        thrpt           8.373          ops/ms
ClientSimple.createUser                       avgt           2.080           ms/op
ClientSimple.existUser                        avgt           1.887           ms/op
ClientSimple.getUser                          avgt           1.928           ms/op
ClientSimple.listUser                         avgt           3.783           ms/op
ClientSimple.createUser                     sample  14397    2.221 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.388           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.054           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.859           ms/op
ClientSimple.createUser:createUser·p0.99    sample           5.882           ms/op
ClientSimple.createUser:createUser·p0.999   sample          19.025           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          21.449           ms/op
ClientSimple.createUser:createUser·p1.00    sample          21.463           ms/op
ClientSimple.existUser                      sample  14172    2.291 ± 0.064   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.218           ms/op
ClientSimple.existUser:existUser·p0.50      sample           2.077           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.810           ms/op
ClientSimple.existUser:existUser·p0.95      sample           3.219           ms/op
ClientSimple.existUser:existUser·p0.99      sample           9.391           ms/op
ClientSimple.existUser:existUser·p0.999     sample          13.418           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         125.529           ms/op
ClientSimple.existUser:existUser·p1.00      sample         128.975           ms/op
ClientSimple.getUser                        sample  13859    2.329 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.477           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.232           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.974           ms/op
ClientSimple.getUser:getUser·p0.95          sample           3.232           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.799           ms/op
ClientSimple.getUser:getUser·p0.999         sample          22.249           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          23.411           ms/op
ClientSimple.getUser:getUser·p1.00          sample          23.462           ms/op
ClientSimple.listUser                       sample  10124    3.204 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.818           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.904           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.119           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.506           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.412           ms/op
ClientSimple.listUser:listUser·p0.999       sample          18.579           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          18.710           ms/op
ClientSimple.listUser:listUser·p1.00        sample          18.711           ms/op

Benchmark result is saved to 1712276113656.json
