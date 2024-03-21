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
# Warmup Iteration   1: 1.649 ops/ms
Iteration   1: 6.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.084 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.178 ops/ms
Iteration   1: 10.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.125 ops/ms


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
# Warmup Iteration   1: 5.353 ops/ms
Iteration   1: 11.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.107 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.347 ops/ms
Iteration   1: 7.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.786 ops/ms


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.080 ms/op
Iteration   1: 2.114 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.114 ms/op


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
# Warmup Iteration   1: 3.300 ±(99.9%) 0.051 ms/op
Iteration   1: 2.062 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.062 ms/op


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.056 ms/op
Iteration   1: 2.109 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.109 ms/op


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
# Warmup Iteration   1: 4.589 ±(99.9%) 0.095 ms/op
Iteration   1: 3.682 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.682 ms/op


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
# Warmup Iteration   1: 3.587 ±(99.9%) 0.095 ms/op
Iteration   1: 2.486 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   2.392 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.482 ms/op
                 createUser·p0.99:   7.483 ms/op
                 createUser·p0.999:  18.416 ms/op
                 createUser·p0.9999: 19.544 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12865
  mean =      2.486 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 7418 
    [ 2.500,  3.750) = 4892 
    [ 3.750,  5.000) = 144 
    [ 5.000,  6.250) = 126 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      2.392 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      7.483 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     19.544 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 3.017 ±(99.9%) 0.075 ms/op
Iteration   1: 1.821 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   1.722 ms/op
                 existUser·p0.90:   2.064 ms/op
                 existUser·p0.95:   2.294 ms/op
                 existUser·p0.99:   3.395 ms/op
                 existUser·p0.999:  13.952 ms/op
                 existUser·p0.9999: 15.706 ms/op
                 existUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17605
  mean =      1.821 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 16999 
    [ 2.500,  3.750) = 352 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.064 ms/op
     p(95.0000) =      2.294 ms/op
     p(99.0000) =      3.395 ms/op
     p(99.9000) =     13.952 ms/op
     p(99.9900) =     15.706 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.074 ms/op
Iteration   1: 1.951 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.471 ms/op
                 getUser·p0.50:   1.845 ms/op
                 getUser·p0.90:   2.507 ms/op
                 getUser·p0.95:   2.638 ms/op
                 getUser·p0.99:   3.530 ms/op
                 getUser·p0.999:  16.541 ms/op
                 getUser·p0.9999: 16.822 ms/op
                 getUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16444
  mean =      1.951 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 228 
    [ 1.250,  2.500) = 14530 
    [ 2.500,  3.750) = 1531 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.530 ms/op
     p(99.9000) =     16.541 ms/op
     p(99.9900) =     16.822 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.123 ms/op
Iteration   1: 3.518 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.404 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   5.619 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9103
  mean =      3.518 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 431 
    [ 2.500,  3.750) = 5733 
    [ 3.750,  5.000) = 2731 
    [ 5.000,  6.250) = 159 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.619 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.084          ops/ms
ClientSimple.existUser                       thrpt         10.125          ops/ms
ClientSimple.getUser                         thrpt         11.107          ops/ms
ClientSimple.listUser                        thrpt          7.786          ops/ms
ClientSimple.createUser                       avgt          2.114           ms/op
ClientSimple.existUser                        avgt          2.062           ms/op
ClientSimple.getUser                          avgt          2.109           ms/op
ClientSimple.listUser                         avgt          3.682           ms/op
ClientSimple.createUser                     sample  12865   2.486 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.646           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.392           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.150           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.482           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.483           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.416           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.544           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.562           ms/op
ClientSimple.existUser                      sample  17605   1.821 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.596           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.722           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.064           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.395           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.952           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.706           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.892           ms/op
ClientSimple.getUser                        sample  16444   1.951 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.471           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.845           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.530           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.541           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.822           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.843           ms/op
ClientSimple.listUser                       sample   9103   3.518 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.180           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.404           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.619           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.039           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.334           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.334           ms/op

Benchmark result is saved to 1711022757226.json
