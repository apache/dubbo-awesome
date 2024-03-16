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
# Warmup Iteration   1: 1.895 ops/ms
Iteration   1: 7.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.079 ops/ms


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
# Warmup Iteration   1: 5.589 ops/ms
Iteration   1: 14.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.857 ops/ms


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
# Warmup Iteration   1: 5.803 ops/ms
Iteration   1: 12.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.509 ops/ms


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
# Warmup Iteration   1: 5.166 ops/ms
Iteration   1: 8.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.863 ops/ms


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.065 ms/op
Iteration   1: 2.282 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.282 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.046 ms/op
Iteration   1: 1.929 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.929 ms/op


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
# Warmup Iteration   1: 3.565 ±(99.9%) 0.067 ms/op
Iteration   1: 1.823 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.823 ms/op


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.078 ms/op
Iteration   1: 3.326 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.326 ms/op


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
# Warmup Iteration   1: 3.291 ±(99.9%) 0.085 ms/op
Iteration   1: 2.311 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   2.195 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   5.584 ms/op
                 createUser·p0.999:  12.730 ms/op
                 createUser·p0.9999: 12.908 ms/op
                 createUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13807
  mean =      2.311 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 195 
    [ 1.250,  2.500) = 9738 
    [ 2.500,  3.750) = 3336 
    [ 3.750,  5.000) = 360 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      5.584 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     12.908 ms/op
     p(99.9990) =     12.927 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


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
# Warmup Iteration   1: 3.076 ±(99.9%) 0.068 ms/op
Iteration   1: 1.838 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.382 ms/op
                 existUser·p0.50:   1.618 ms/op
                 existUser·p0.90:   2.642 ms/op
                 existUser·p0.95:   2.843 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  29.179 ms/op
                 existUser·p0.9999: 29.806 ms/op
                 existUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17384
  mean =      1.838 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15242 
    [ 2.500,  5.000) = 2064 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      1.618 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      3.363 ms/op
     p(99.9000) =     29.179 ms/op
     p(99.9900) =     29.806 ms/op
     p(99.9990) =     30.048 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.086 ms/op
Iteration   1: 2.124 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.351 ms/op
                 getUser·p0.50:   2.062 ms/op
                 getUser·p0.90:   2.789 ms/op
                 getUser·p0.95:   3.027 ms/op
                 getUser·p0.99:   3.596 ms/op
                 getUser·p0.999:  5.316 ms/op
                 getUser·p0.9999: 7.331 ms/op
                 getUser·p1.00:   9.306 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15053
  mean =      2.124 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 61 
    [ 1.000,  2.000) = 6927 
    [ 2.000,  3.000) = 7256 
    [ 3.000,  4.000) = 723 
    [ 4.000,  5.000) = 55 
    [ 5.000,  6.000) = 30 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      5.316 ms/op
     p(99.9900) =      7.331 ms/op
     p(99.9990) =      9.306 ms/op
     p(99.9999) =      9.306 ms/op
    p(100.0000) =      9.306 ms/op


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
# Warmup Iteration   1: 4.552 ±(99.9%) 0.134 ms/op
Iteration   1: 3.339 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.013 ms/op
                 listUser·p0.50:   3.228 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.834 ms/op
                 listUser·p0.999:  8.301 ms/op
                 listUser·p0.9999: 9.191 ms/op
                 listUser·p1.00:   9.191 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9580
  mean =      3.339 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 15 
    [ 1.500,  2.000) = 62 
    [ 2.000,  2.500) = 1124 
    [ 2.500,  3.000) = 2801 
    [ 3.000,  3.500) = 1513 
    [ 3.500,  4.000) = 2134 
    [ 4.000,  4.500) = 1464 
    [ 4.500,  5.000) = 294 
    [ 5.000,  5.500) = 27 
    [ 5.500,  6.000) = 68 
    [ 6.000,  6.500) = 8 
    [ 6.500,  7.000) = 3 
    [ 7.000,  7.500) = 36 
    [ 7.500,  8.000) = 5 
    [ 8.000,  8.500) = 21 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.834 ms/op
     p(99.9000) =      8.301 ms/op
     p(99.9900) =      9.191 ms/op
     p(99.9990) =      9.191 ms/op
     p(99.9999) =      9.191 ms/op
    p(100.0000) =      9.191 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.079          ops/ms
ClientSimple.existUser                       thrpt         14.857          ops/ms
ClientSimple.getUser                         thrpt         12.509          ops/ms
ClientSimple.listUser                        thrpt          8.863          ops/ms
ClientSimple.createUser                       avgt          2.282           ms/op
ClientSimple.existUser                        avgt          1.929           ms/op
ClientSimple.getUser                          avgt          1.823           ms/op
ClientSimple.listUser                         avgt          3.326           ms/op
ClientSimple.createUser                     sample  13807   2.311 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.651           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.195           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.970           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.523           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.584           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.730           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         12.908           ms/op
ClientSimple.createUser:createUser·p1.00    sample         12.927           ms/op
ClientSimple.existUser                      sample  17384   1.838 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.382           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.618           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.843           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.363           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.179           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.806           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.048           ms/op
ClientSimple.getUser                        sample  15053   2.124 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.351           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.062           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.027           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.596           ms/op
ClientSimple.getUser:getUser·p0.999         sample          5.316           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          7.331           ms/op
ClientSimple.getUser:getUser·p1.00          sample          9.306           ms/op
ClientSimple.listUser                       sample   9580   3.339 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.013           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.228           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.834           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.301           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.191           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.191           ms/op

Benchmark result is saved to 1710569097435.json
