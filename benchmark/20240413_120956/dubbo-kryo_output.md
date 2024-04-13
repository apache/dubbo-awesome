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
# Warmup Iteration   1: 1.129 ops/ms
Iteration   1: 7.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.321 ops/ms


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
# Warmup Iteration   1: 5.972 ops/ms
Iteration   1: 14.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.550 ops/ms


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
# Warmup Iteration   1: 6.098 ops/ms
Iteration   1: 13.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.722 ops/ms


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
# Warmup Iteration   1: 5.271 ops/ms
Iteration   1: 8.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.872 ops/ms


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.066 ms/op
Iteration   1: 2.134 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.134 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.057 ms/op
Iteration   1: 1.966 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.966 ms/op


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
# Warmup Iteration   1: 3.129 ±(99.9%) 0.051 ms/op
Iteration   1: 1.850 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.850 ms/op


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.091 ms/op
Iteration   1: 3.670 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.670 ms/op


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
# Warmup Iteration   1: 3.504 ±(99.9%) 0.082 ms/op
Iteration   1: 2.117 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   1.946 ms/op
                 createUser·p0.90:   2.511 ms/op
                 createUser·p0.95:   2.748 ms/op
                 createUser·p0.99:   5.047 ms/op
                 createUser·p0.999:  13.530 ms/op
                 createUser·p0.9999: 14.293 ms/op
                 createUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15088
  mean =      2.117 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 13487 
    [ 2.500,  3.750) = 1306 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      5.047 ms/op
     p(99.9000) =     13.530 ms/op
     p(99.9900) =     14.293 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.087 ms/op
Iteration   1: 1.739 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   1.575 ms/op
                 existUser·p0.90:   2.204 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   3.166 ms/op
                 existUser·p0.999:  17.727 ms/op
                 existUser·p0.9999: 18.470 ms/op
                 existUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18382
  mean =      1.739 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1243 
    [ 1.250,  2.500) = 16657 
    [ 2.500,  3.750) = 325 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      1.575 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      3.166 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     18.470 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 3.273 ±(99.9%) 0.082 ms/op
Iteration   1: 1.901 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   1.790 ms/op
                 getUser·p0.90:   2.314 ms/op
                 getUser·p0.95:   2.613 ms/op
                 getUser·p0.99:   3.342 ms/op
                 getUser·p0.999:  11.354 ms/op
                 getUser·p0.9999: 11.836 ms/op
                 getUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17002
  mean =      1.901 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 15805 
    [ 2.500,  3.750) = 1006 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      1.790 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      3.342 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     11.836 ms/op
     p(99.9990) =     11.928 ms/op
     p(99.9999) =     11.928 ms/op
    p(100.0000) =     11.928 ms/op


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
# Warmup Iteration   1: 4.509 ±(99.9%) 0.141 ms/op
Iteration   1: 3.517 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.490 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.626 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  7.486 ms/op
                 listUser·p0.9999: 7.709 ms/op
                 listUser·p1.00:   7.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9264
  mean =      3.517 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 12 
    [1.500, 2.000) = 56 
    [2.000, 2.500) = 313 
    [2.500, 3.000) = 1629 
    [3.000, 3.500) = 2692 
    [3.500, 4.000) = 2728 
    [4.000, 4.500) = 1256 
    [4.500, 5.000) = 357 
    [5.000, 5.500) = 120 
    [5.500, 6.000) = 53 
    [6.000, 6.500) = 10 
    [6.500, 7.000) = 25 
    [7.000, 7.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.626 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      7.486 ms/op
     p(99.9900) =      7.709 ms/op
     p(99.9990) =      7.709 ms/op
     p(99.9999) =      7.709 ms/op
    p(100.0000) =      7.709 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.321          ops/ms
ClientSimple.existUser                       thrpt         14.550          ops/ms
ClientSimple.getUser                         thrpt         13.722          ops/ms
ClientSimple.listUser                        thrpt          8.872          ops/ms
ClientSimple.createUser                       avgt          2.134           ms/op
ClientSimple.existUser                        avgt          1.966           ms/op
ClientSimple.getUser                          avgt          1.850           ms/op
ClientSimple.listUser                         avgt          3.670           ms/op
ClientSimple.createUser                     sample  15088   2.117 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.718           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.946           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.511           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.047           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.530           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.293           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.402           ms/op
ClientSimple.existUser                      sample  18382   1.739 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.640           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.575           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.204           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.166           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.727           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.470           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.579           ms/op
ClientSimple.getUser                        sample  17002   1.901 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.670           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.790           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.314           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.342           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.354           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.836           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.928           ms/op
ClientSimple.listUser                       sample   9264   3.517 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.171           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.490           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.626           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.521           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.486           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.709           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.709           ms/op

Benchmark result is saved to 1713009931685.json
