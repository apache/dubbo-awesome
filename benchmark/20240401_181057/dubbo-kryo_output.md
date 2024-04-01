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
# Warmup Iteration   1: 1.151 ops/ms
Iteration   1: 5.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.316 ops/ms


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
# Warmup Iteration   1: 5.938 ops/ms
Iteration   1: 13.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.335 ops/ms


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
# Warmup Iteration   1: 4.170 ops/ms
Iteration   1: 11.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.835 ops/ms


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
# Warmup Iteration   1: 5.352 ops/ms
Iteration   1: 8.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.617 ops/ms


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.068 ms/op
Iteration   1: 2.346 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.346 ms/op


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
# Warmup Iteration   1: 3.344 ±(99.9%) 0.066 ms/op
Iteration   1: 1.955 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.955 ms/op


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
# Warmup Iteration   1: 3.334 ±(99.9%) 0.050 ms/op
Iteration   1: 2.371 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.371 ms/op


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
# Warmup Iteration   1: 4.289 ±(99.9%) 0.088 ms/op
Iteration   1: 3.384 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.384 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.086 ms/op
Iteration   1: 2.034 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   1.835 ms/op
                 createUser·p0.90:   2.327 ms/op
                 createUser·p0.95:   2.630 ms/op
                 createUser·p0.99:   9.185 ms/op
                 createUser·p0.999:  32.702 ms/op
                 createUser·p0.9999: 35.359 ms/op
                 createUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15718
  mean =      2.034 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14733 
    [ 2.500,  5.000) = 726 
    [ 5.000,  7.500) = 80 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      9.185 ms/op
     p(99.9000) =     32.702 ms/op
     p(99.9900) =     35.359 ms/op
     p(99.9990) =     37.814 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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
# Warmup Iteration   1: 3.115 ±(99.9%) 0.078 ms/op
Iteration   1: 1.957 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.438 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   4.882 ms/op
                 existUser·p0.999:  30.855 ms/op
                 existUser·p0.9999: 31.338 ms/op
                 existUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16388
  mean =      1.957 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14856 
    [ 2.500,  5.000) = 1391 
    [ 5.000,  7.500) = 77 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =     30.855 ms/op
     p(99.9900) =     31.338 ms/op
     p(99.9990) =     31.359 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 3.487 ±(99.9%) 0.099 ms/op
Iteration   1: 2.034 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   1.894 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.830 ms/op
                 getUser·p0.99:   3.378 ms/op
                 getUser·p0.999:  13.402 ms/op
                 getUser·p0.9999: 13.507 ms/op
                 getUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15960
  mean =      2.034 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 13974 
    [ 2.500,  3.750) = 1747 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      3.378 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     13.507 ms/op
     p(99.9990) =     13.517 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


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
# Warmup Iteration   1: 4.585 ±(99.9%) 0.141 ms/op
Iteration   1: 3.687 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   5.433 ms/op
                 listUser·p0.999:  7.173 ms/op
                 listUser·p0.9999: 8.364 ms/op
                 listUser·p1.00:   8.364 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8669
  mean =      3.687 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 9 
    [1.500, 2.000) = 66 
    [2.000, 2.500) = 353 
    [2.500, 3.000) = 1206 
    [3.000, 3.500) = 1691 
    [3.500, 4.000) = 2494 
    [4.000, 4.500) = 1675 
    [4.500, 5.000) = 869 
    [5.000, 5.500) = 224 
    [5.500, 6.000) = 55 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      5.433 ms/op
     p(99.9000) =      7.173 ms/op
     p(99.9900) =      8.364 ms/op
     p(99.9990) =      8.364 ms/op
     p(99.9999) =      8.364 ms/op
    p(100.0000) =      8.364 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.316          ops/ms
ClientSimple.existUser                       thrpt         13.335          ops/ms
ClientSimple.getUser                         thrpt         11.835          ops/ms
ClientSimple.listUser                        thrpt          8.617          ops/ms
ClientSimple.createUser                       avgt          2.346           ms/op
ClientSimple.existUser                        avgt          1.955           ms/op
ClientSimple.getUser                          avgt          2.371           ms/op
ClientSimple.listUser                         avgt          3.384           ms/op
ClientSimple.createUser                     sample  15718   2.034 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.551           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.835           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.327           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.185           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.702           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.359           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.814           ms/op
ClientSimple.existUser                      sample  16388   1.957 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.438           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.761           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.882           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.855           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.338           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.359           ms/op
ClientSimple.getUser                        sample  15960   2.034 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.506           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.894           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.378           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.402           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.507           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.517           ms/op
ClientSimple.listUser                       sample   8669   3.687 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.284           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.752           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.882           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.433           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.173           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.364           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.364           ms/op

Benchmark result is saved to 1711994692009.json
