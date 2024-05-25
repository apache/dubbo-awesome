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
# Warmup Iteration   1: 1.803 ops/ms
Iteration   1: 7.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.174 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.540 ops/ms
Iteration   1: 14.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.036 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.359 ops/ms
Iteration   1: 14.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.077 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.544 ops/ms
Iteration   1: 8.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.386 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ±(99.9%) 0.064 ms/op
Iteration   1: 2.265 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.265 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.573 ±(99.9%) 0.057 ms/op
Iteration   1: 1.987 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.987 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.562 ±(99.9%) 0.087 ms/op
Iteration   1: 1.876 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.876 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.409 ±(99.9%) 0.087 ms/op
Iteration   1: 3.735 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.735 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.396 ±(99.9%) 0.097 ms/op
Iteration   1: 2.419 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   2.095 ms/op
                 createUser·p0.90:   2.793 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   10.846 ms/op
                 createUser·p0.999:  20.665 ms/op
                 createUser·p0.9999: 21.451 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13360
  mean =      2.419 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10414 
    [ 2.500,  5.000) = 2436 
    [ 5.000,  7.500) = 265 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.095 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     20.665 ms/op
     p(99.9900) =     21.451 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.876 ±(99.9%) 0.075 ms/op
Iteration   1: 1.888 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.516 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  13.269 ms/op
                 existUser·p0.9999: 13.407 ms/op
                 existUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17125
  mean =      1.888 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 628 
    [ 1.250,  2.500) = 15246 
    [ 2.500,  3.750) = 1097 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      3.527 ms/op
     p(99.9000) =     13.269 ms/op
     p(99.9900) =     13.407 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ±(99.9%) 0.084 ms/op
Iteration   1: 1.977 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.442 ms/op
                 getUser·p0.95:   2.589 ms/op
                 getUser·p0.99:   3.691 ms/op
                 getUser·p0.999:  13.446 ms/op
                 getUser·p0.9999: 13.986 ms/op
                 getUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16336
  mean =      1.977 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 14976 
    [ 2.500,  3.750) = 1074 
    [ 3.750,  5.000) = 96 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.442 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.691 ms/op
     p(99.9000) =     13.446 ms/op
     p(99.9900) =     13.986 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.835 ±(99.9%) 0.153 ms/op
Iteration   1: 3.683 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.127 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  9.966 ms/op
                 listUser·p0.9999: 10.535 ms/op
                 listUser·p1.00:   10.535 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8702
  mean =      3.683 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 32 
    [ 2.000,  3.000) = 2093 
    [ 3.000,  4.000) = 3919 
    [ 4.000,  5.000) = 2080 
    [ 5.000,  6.000) = 457 
    [ 6.000,  7.000) = 46 
    [ 7.000,  8.000) = 40 
    [ 8.000,  9.000) = 2 
    [ 9.000, 10.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.127 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =      9.966 ms/op
     p(99.9900) =     10.535 ms/op
     p(99.9990) =     10.535 ms/op
     p(99.9999) =     10.535 ms/op
    p(100.0000) =     10.535 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.174          ops/ms
ClientSimple.existUser                       thrpt         14.036          ops/ms
ClientSimple.getUser                         thrpt         14.077          ops/ms
ClientSimple.listUser                        thrpt          8.386          ops/ms
ClientSimple.createUser                       avgt          2.265           ms/op
ClientSimple.existUser                        avgt          1.987           ms/op
ClientSimple.getUser                          avgt          1.876           ms/op
ClientSimple.listUser                         avgt          3.735           ms/op
ClientSimple.createUser                     sample  13360   2.419 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.647           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.095           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.793           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.846           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.665           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.451           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.594           ms/op
ClientSimple.existUser                      sample  17125   1.888 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.516           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.786           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.527           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.269           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.407           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.500           ms/op
ClientSimple.getUser                        sample  16336   1.977 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.564           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.442           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.691           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.446           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.986           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.402           ms/op
ClientSimple.listUser                       sample   8702   3.683 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.331           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.629           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.127           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.545           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.966           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.535           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.535           ms/op

Benchmark result is saved to 1716596108085.json
