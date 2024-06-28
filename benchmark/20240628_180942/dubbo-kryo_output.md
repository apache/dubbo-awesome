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
# Warmup Iteration   1: 1.448 ops/ms
Iteration   1: 5.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.765 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.912 ops/ms
Iteration   1: 12.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.505 ops/ms


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
# Warmup Iteration   1: 5.124 ops/ms
Iteration   1: 12.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.643 ops/ms


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
# Warmup Iteration   1: 5.100 ops/ms
Iteration   1: 9.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.084 ops/ms


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
# Warmup Iteration   1: 3.510 ±(99.9%) 0.071 ms/op
Iteration   1: 2.117 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.117 ms/op


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
# Warmup Iteration   1: 3.198 ±(99.9%) 0.044 ms/op
Iteration   1: 2.039 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.039 ms/op


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
# Warmup Iteration   1: 3.384 ±(99.9%) 0.058 ms/op
Iteration   1: 1.919 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.919 ms/op


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
# Warmup Iteration   1: 4.521 ±(99.9%) 0.115 ms/op
Iteration   1: 3.734 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.734 ms/op


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
# Warmup Iteration   1: 3.506 ±(99.9%) 0.086 ms/op
Iteration   1: 2.405 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   2.269 ms/op
                 createUser·p0.90:   2.839 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   9.575 ms/op
                 createUser·p0.999:  13.560 ms/op
                 createUser·p0.9999: 15.103 ms/op
                 createUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13360
  mean =      2.405 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 9039 
    [ 2.500,  3.750) = 3791 
    [ 3.750,  5.000) = 145 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      9.575 ms/op
     p(99.9000) =     13.560 ms/op
     p(99.9900) =     15.103 ms/op
     p(99.9990) =     15.450 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 2.997 ±(99.9%) 0.071 ms/op
Iteration   1: 1.829 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.544 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   3.078 ms/op
                 existUser·p0.999:  10.082 ms/op
                 existUser·p0.9999: 11.690 ms/op
                 existUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17631
  mean =      1.829 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 190 
    [ 1.250,  2.500) = 16864 
    [ 2.500,  3.750) = 474 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      3.078 ms/op
     p(99.9000) =     10.082 ms/op
     p(99.9900) =     11.690 ms/op
     p(99.9990) =     11.715 ms/op
     p(99.9999) =     11.715 ms/op
    p(100.0000) =     11.715 ms/op


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
# Warmup Iteration   1: 3.291 ±(99.9%) 0.082 ms/op
Iteration   1: 2.252 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   2.130 ms/op
                 getUser·p0.90:   2.654 ms/op
                 getUser·p0.95:   2.855 ms/op
                 getUser·p0.99:   5.100 ms/op
                 getUser·p0.999:  18.768 ms/op
                 getUser·p0.9999: 18.893 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14239
  mean =      2.252 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 11559 
    [ 2.500,  3.750) = 2357 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      5.100 ms/op
     p(99.9000) =     18.768 ms/op
     p(99.9900) =     18.893 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.132 ms/op
Iteration   1: 3.247 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   3.154 ms/op
                 listUser·p0.90:   4.085 ms/op
                 listUser·p0.95:   4.388 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  10.873 ms/op
                 listUser·p0.9999: 11.862 ms/op
                 listUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9847
  mean =      3.247 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1669 
    [ 2.500,  3.750) = 5928 
    [ 3.750,  5.000) = 1993 
    [ 5.000,  6.250) = 143 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      4.085 ms/op
     p(95.0000) =      4.388 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     10.873 ms/op
     p(99.9900) =     11.862 ms/op
     p(99.9990) =     11.862 ms/op
     p(99.9999) =     11.862 ms/op
    p(100.0000) =     11.862 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.765          ops/ms
ClientSimple.existUser                       thrpt         12.505          ops/ms
ClientSimple.getUser                         thrpt         12.643          ops/ms
ClientSimple.listUser                        thrpt          9.084          ops/ms
ClientSimple.createUser                       avgt          2.117           ms/op
ClientSimple.existUser                        avgt          2.039           ms/op
ClientSimple.getUser                          avgt          1.919           ms/op
ClientSimple.listUser                         avgt          3.734           ms/op
ClientSimple.createUser                     sample  13360   2.405 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.612           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.269           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.064           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.575           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.560           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.103           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.450           ms/op
ClientSimple.existUser                      sample  17631   1.829 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.544           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.735           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.078           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.082           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.690           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.715           ms/op
ClientSimple.getUser                        sample  14239   2.252 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.609           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.130           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.654           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.100           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.768           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.893           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.907           ms/op
ClientSimple.listUser                       sample   9847   3.247 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.438           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.154           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.085           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.388           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.414           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.873           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.862           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.862           ms/op

Benchmark result is saved to 1719597922689.json
