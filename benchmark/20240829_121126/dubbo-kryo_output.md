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
# Warmup Iteration   1: 1.019 ops/ms
Iteration   1: 7.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.088 ops/ms


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
# Warmup Iteration   1: 6.200 ops/ms
Iteration   1: 12.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.949 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.112 ops/ms
Iteration   1: 12.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.171 ops/ms


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
# Warmup Iteration   1: 4.780 ops/ms
Iteration   1: 8.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.794 ops/ms


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.081 ms/op
Iteration   1: 2.438 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.438 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.051 ms/op
Iteration   1: 1.825 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.825 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.084 ms/op
Iteration   1: 2.195 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.195 ms/op


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
# Warmup Iteration   1: 4.498 ±(99.9%) 0.099 ms/op
Iteration   1: 3.198 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.198 ms/op


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
# Warmup Iteration   1: 3.290 ±(99.9%) 0.076 ms/op
Iteration   1: 2.115 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.432 ms/op
                 createUser·p0.50:   1.997 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.757 ms/op
                 createUser·p0.99:   7.920 ms/op
                 createUser·p0.999:  21.168 ms/op
                 createUser·p0.9999: 22.413 ms/op
                 createUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15119
  mean =      2.115 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13543 
    [ 2.500,  5.000) = 1330 
    [ 5.000,  7.500) = 74 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      7.920 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 2.901 ±(99.9%) 0.065 ms/op
Iteration   1: 1.868 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.163 ms/op
                 existUser·p0.95:   2.286 ms/op
                 existUser·p0.99:   3.381 ms/op
                 existUser·p0.999:  22.643 ms/op
                 existUser·p0.9999: 22.774 ms/op
                 existUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17163
  mean =      1.868 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16698 
    [ 2.500,  5.000) = 374 
    [ 5.000,  7.500) = 26 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.163 ms/op
     p(95.0000) =      2.286 ms/op
     p(99.0000) =      3.381 ms/op
     p(99.9000) =     22.643 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 3.568 ±(99.9%) 0.157 ms/op
Iteration   1: 1.786 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   1.731 ms/op
                 getUser·p0.90:   2.163 ms/op
                 getUser·p0.95:   2.376 ms/op
                 getUser·p0.99:   2.998 ms/op
                 getUser·p0.999:  15.434 ms/op
                 getUser·p0.9999: 15.674 ms/op
                 getUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17901
  mean =      1.786 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 392 
    [ 1.250,  2.500) = 16946 
    [ 2.500,  3.750) = 477 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.163 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      2.998 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     15.674 ms/op
     p(99.9990) =     15.778 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.141 ms/op
Iteration   1: 3.272 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.269 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.070 ms/op
                 listUser·p0.999:  7.137 ms/op
                 listUser·p0.9999: 7.602 ms/op
                 listUser·p1.00:   7.602 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9760
  mean =      3.272 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 5 
    [1.500, 2.000) = 86 
    [2.000, 2.500) = 1098 
    [2.500, 3.000) = 2620 
    [3.000, 3.500) = 2501 
    [3.500, 4.000) = 2450 
    [4.000, 4.500) = 660 
    [4.500, 5.000) = 130 
    [5.000, 5.500) = 71 
    [5.500, 6.000) = 38 
    [6.000, 6.500) = 35 
    [6.500, 7.000) = 21 
    [7.000, 7.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =      7.137 ms/op
     p(99.9900) =      7.602 ms/op
     p(99.9990) =      7.602 ms/op
     p(99.9999) =      7.602 ms/op
    p(100.0000) =      7.602 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.088          ops/ms
ClientSimple.existUser                       thrpt         12.949          ops/ms
ClientSimple.getUser                         thrpt         12.171          ops/ms
ClientSimple.listUser                        thrpt          8.794          ops/ms
ClientSimple.createUser                       avgt          2.438           ms/op
ClientSimple.existUser                        avgt          1.825           ms/op
ClientSimple.getUser                          avgt          2.195           ms/op
ClientSimple.listUser                         avgt          3.198           ms/op
ClientSimple.createUser                     sample  15119   2.115 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.432           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.997           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.920           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.168           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.413           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.413           ms/op
ClientSimple.existUser                      sample  17163   1.868 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.665           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.772           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.163           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.381           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.643           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.774           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.774           ms/op
ClientSimple.getUser                        sample  17901   1.786 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.688           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.731           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.163           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.998           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.434           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.674           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.778           ms/op
ClientSimple.listUser                       sample   9760   3.272 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.286           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.269           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.014           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.070           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.137           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.602           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.602           ms/op

Benchmark result is saved to 1724933222864.json
