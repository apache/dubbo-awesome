# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.551 ops/ms
Iteration   1: 7.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.223 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.448 ops/ms
Iteration   1: 13.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.472 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.587 ops/ms
Iteration   1: 12.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.626 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.995 ops/ms
Iteration   1: 8.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.990 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.274 ±(99.9%) 0.089 ms/op
Iteration   1: 2.129 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.129 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.183 ±(99.9%) 0.041 ms/op
Iteration   1: 1.581 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.581 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.345 ±(99.9%) 0.060 ms/op
Iteration   1: 2.173 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.173 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.598 ±(99.9%) 0.110 ms/op
Iteration   1: 3.231 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.231 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.624 ±(99.9%) 0.088 ms/op
Iteration   1: 1.927 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.376 ms/op
                 createUser·p0.50:   1.749 ms/op
                 createUser·p0.90:   2.167 ms/op
                 createUser·p0.95:   2.404 ms/op
                 createUser·p0.99:   9.615 ms/op
                 createUser·p0.999:  22.030 ms/op
                 createUser·p0.9999: 22.500 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16682
  mean =      1.927 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15939 
    [ 2.500,  5.000) = 456 
    [ 5.000,  7.500) = 91 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.404 ms/op
     p(99.0000) =      9.615 ms/op
     p(99.9000) =     22.030 ms/op
     p(99.9900) =     22.500 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.773 ±(99.9%) 0.065 ms/op
Iteration   1: 1.886 ±(99.9%) 0.118 ms/op
                 existUser·p0.00:   0.282 ms/op
                 existUser·p0.50:   1.442 ms/op
                 existUser·p0.90:   2.091 ms/op
                 existUser·p0.95:   2.351 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  88.888 ms/op
                 existUser·p0.9999: 127.393 ms/op
                 existUser·p1.00:   128.319 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17067
  mean =      1.886 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 16945 
    [ 12.500,  25.000) = 41 
    [ 25.000,  37.500) = 32 
    [ 37.500,  50.000) = 7 
    [ 50.000,  62.500) = 8 
    [ 62.500,  75.000) = 10 
    [ 75.000,  87.500) = 7 
    [ 87.500, 100.000) = 2 
    [100.000, 112.500) = 4 
    [112.500, 125.000) = 7 
    [125.000, 137.500) = 4 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      1.442 ms/op
     p(90.0000) =      2.091 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     88.888 ms/op
     p(99.9900) =    127.393 ms/op
     p(99.9990) =    128.319 ms/op
     p(99.9999) =    128.319 ms/op
    p(100.0000) =    128.319 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.261 ±(99.9%) 0.076 ms/op
Iteration   1: 1.950 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   1.785 ms/op
                 getUser·p0.90:   2.433 ms/op
                 getUser·p0.95:   2.679 ms/op
                 getUser·p0.99:   5.696 ms/op
                 getUser·p0.999:  13.492 ms/op
                 getUser·p0.9999: 15.531 ms/op
                 getUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16516
  mean =      1.950 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 216 
    [ 1.250,  2.500) = 14963 
    [ 2.500,  3.750) = 1058 
    [ 3.750,  5.000) = 107 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      1.785 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      5.696 ms/op
     p(99.9000) =     13.492 ms/op
     p(99.9900) =     15.531 ms/op
     p(99.9990) =     16.417 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.341 ±(99.9%) 0.113 ms/op
Iteration   1: 2.571 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   2.462 ms/op
                 listUser·p0.90:   3.346 ms/op
                 listUser·p0.95:   3.862 ms/op
                 listUser·p0.99:   4.833 ms/op
                 listUser·p0.999:  6.317 ms/op
                 listUser·p0.9999: 8.045 ms/op
                 listUser·p1.00:   8.086 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 12444
  mean =      2.571 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 67 
    [1.500, 2.000) = 1613 
    [2.000, 2.500) = 5138 
    [2.500, 3.000) = 3499 
    [3.000, 3.500) = 1110 
    [3.500, 4.000) = 571 
    [4.000, 4.500) = 248 
    [4.500, 5.000) = 99 
    [5.000, 5.500) = 15 
    [5.500, 6.000) = 27 
    [6.000, 6.500) = 49 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.862 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      6.317 ms/op
     p(99.9900) =      8.045 ms/op
     p(99.9990) =      8.086 ms/op
     p(99.9999) =      8.086 ms/op
    p(100.0000) =      8.086 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.223          ops/ms
ClientSimple.existUser                       thrpt          13.472          ops/ms
ClientSimple.getUser                         thrpt          12.626          ops/ms
ClientSimple.listUser                        thrpt           8.990          ops/ms
ClientSimple.createUser                       avgt           2.129           ms/op
ClientSimple.existUser                        avgt           1.581           ms/op
ClientSimple.getUser                          avgt           2.173           ms/op
ClientSimple.listUser                         avgt           3.231           ms/op
ClientSimple.createUser                     sample  16682    1.927 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.376           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.749           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.167           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.404           ms/op
ClientSimple.createUser:createUser·p0.99    sample           9.615           ms/op
ClientSimple.createUser:createUser·p0.999   sample          22.030           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          22.500           ms/op
ClientSimple.createUser:createUser·p1.00    sample          22.675           ms/op
ClientSimple.existUser                      sample  17067    1.886 ± 0.118   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.282           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.442           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.091           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.351           ms/op
ClientSimple.existUser:existUser·p0.99      sample           5.841           ms/op
ClientSimple.existUser:existUser·p0.999     sample          88.888           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         127.393           ms/op
ClientSimple.existUser:existUser·p1.00      sample         128.319           ms/op
ClientSimple.getUser                        sample  16516    1.950 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.734           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.785           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.433           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.679           ms/op
ClientSimple.getUser:getUser·p0.99          sample           5.696           ms/op
ClientSimple.getUser:getUser·p0.999         sample          13.492           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          15.531           ms/op
ClientSimple.getUser:getUser·p1.00          sample          16.417           ms/op
ClientSimple.listUser                       sample  12444    2.571 ± 0.019   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.014           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.462           ms/op
ClientSimple.listUser:listUser·p0.90        sample           3.346           ms/op
ClientSimple.listUser:listUser·p0.95        sample           3.862           ms/op
ClientSimple.listUser:listUser·p0.99        sample           4.833           ms/op
ClientSimple.listUser:listUser·p0.999       sample           6.317           ms/op
ClientSimple.listUser:listUser·p0.9999      sample           8.045           ms/op
ClientSimple.listUser:listUser·p1.00        sample           8.086           ms/op

Benchmark result is saved to 1726013855993.json
