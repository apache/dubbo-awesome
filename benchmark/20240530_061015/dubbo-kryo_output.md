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
# Warmup Iteration   1: 1.891 ops/ms
Iteration   1: 7.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.123 ops/ms


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
# Warmup Iteration   1: 6.986 ops/ms
Iteration   1: 14.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.068 ops/ms


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
# Warmup Iteration   1: 6.525 ops/ms
Iteration   1: 13.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.548 ops/ms


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
# Warmup Iteration   1: 5.542 ops/ms
Iteration   1: 9.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.422 ops/ms


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.083 ms/op
Iteration   1: 2.212 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.212 ms/op


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
# Warmup Iteration   1: 3.045 ±(99.9%) 0.056 ms/op
Iteration   1: 1.884 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.884 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.065 ms/op
Iteration   1: 2.162 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.162 ms/op


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.096 ms/op
Iteration   1: 3.817 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.817 ms/op


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
# Warmup Iteration   1: 3.362 ±(99.9%) 0.090 ms/op
Iteration   1: 2.344 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   2.216 ms/op
                 createUser·p0.90:   2.888 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  16.776 ms/op
                 createUser·p0.9999: 17.498 ms/op
                 createUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13700
  mean =      2.344 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 222 
    [ 1.250,  2.500) = 9737 
    [ 2.500,  3.750) = 3337 
    [ 3.750,  5.000) = 137 
    [ 5.000,  6.250) = 145 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     16.776 ms/op
     p(99.9900) =     17.498 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 2.860 ±(99.9%) 0.070 ms/op
Iteration   1: 1.791 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   2.134 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   2.896 ms/op
                 existUser·p0.999:  33.325 ms/op
                 existUser·p0.9999: 33.962 ms/op
                 existUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17845
  mean =      1.791 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17075 
    [ 2.500,  5.000) = 703 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.134 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      2.896 ms/op
     p(99.9000) =     33.325 ms/op
     p(99.9900) =     33.962 ms/op
     p(99.9990) =     34.013 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 3.282 ±(99.9%) 0.133 ms/op
Iteration   1: 2.271 ±(99.9%) 0.140 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   1.896 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.900 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  106.430 ms/op
                 getUser·p0.9999: 107.610 ms/op
                 getUser·p1.00:   107.610 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14166
  mean =      2.271 ±(99.9%) 0.140 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 14102 
    [ 12.500,  25.000) = 32 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 32 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =    106.430 ms/op
     p(99.9900) =    107.610 ms/op
     p(99.9990) =    107.610 ms/op
     p(99.9999) =    107.610 ms/op
    p(100.0000) =    107.610 ms/op


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
# Warmup Iteration   1: 4.517 ±(99.9%) 0.130 ms/op
Iteration   1: 3.026 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   2.781 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   5.745 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 17.753 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10570
  mean =      3.026 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1641 
    [ 2.500,  3.750) = 7632 
    [ 3.750,  5.000) = 1138 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.745 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     17.753 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.123          ops/ms
ClientSimple.existUser                       thrpt          14.068          ops/ms
ClientSimple.getUser                         thrpt          13.548          ops/ms
ClientSimple.listUser                        thrpt           9.422          ops/ms
ClientSimple.createUser                       avgt           2.212           ms/op
ClientSimple.existUser                        avgt           1.884           ms/op
ClientSimple.getUser                          avgt           2.162           ms/op
ClientSimple.listUser                         avgt           3.817           ms/op
ClientSimple.createUser                     sample  13700    2.344 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.631           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.216           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.888           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.203           ms/op
ClientSimple.createUser:createUser·p0.99    sample           6.111           ms/op
ClientSimple.createUser:createUser·p0.999   sample          16.776           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          17.498           ms/op
ClientSimple.createUser:createUser·p1.00    sample          17.498           ms/op
ClientSimple.existUser                      sample  17845    1.791 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.482           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.681           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.134           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.429           ms/op
ClientSimple.existUser:existUser·p0.99      sample           2.896           ms/op
ClientSimple.existUser:existUser·p0.999     sample          33.325           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          33.962           ms/op
ClientSimple.existUser:existUser·p1.00      sample          34.013           ms/op
ClientSimple.getUser                        sample  14166    2.271 ± 0.140   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.622           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.896           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.900           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.866           ms/op
ClientSimple.getUser:getUser·p0.999         sample         106.430           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         107.610           ms/op
ClientSimple.getUser:getUser·p1.00          sample         107.610           ms/op
ClientSimple.listUser                       sample  10570    3.026 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.249           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.781           ms/op
ClientSimple.listUser:listUser·p0.90        sample           3.842           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.149           ms/op
ClientSimple.listUser:listUser·p0.99        sample           5.745           ms/op
ClientSimple.listUser:listUser·p0.999       sample          15.516           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          17.753           ms/op
ClientSimple.listUser:listUser·p1.00        sample          17.760           ms/op

Benchmark result is saved to 1717049158759.json
