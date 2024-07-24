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
# Warmup Iteration   1: 1.488 ops/ms
Iteration   1: 6.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.314 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.710 ops/ms
Iteration   1: 12.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.709 ops/ms


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
# Warmup Iteration   1: 5.014 ops/ms
Iteration   1: 10.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.571 ops/ms


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
# Warmup Iteration   1: 5.029 ops/ms
Iteration   1: 8.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.725 ops/ms


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.076 ms/op
Iteration   1: 2.087 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.087 ms/op


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
# Warmup Iteration   1: 3.023 ±(99.9%) 0.050 ms/op
Iteration   1: 1.857 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.857 ms/op


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
# Warmup Iteration   1: 3.476 ±(99.9%) 0.070 ms/op
Iteration   1: 2.239 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.239 ms/op


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.087 ms/op
Iteration   1: 3.388 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.388 ms/op


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
# Warmup Iteration   1: 3.587 ±(99.9%) 0.090 ms/op
Iteration   1: 2.091 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.564 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.526 ms/op
                 createUser·p0.95:   2.691 ms/op
                 createUser·p0.99:   4.807 ms/op
                 createUser·p0.999:  23.560 ms/op
                 createUser·p0.9999: 26.360 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15463
  mean =      2.091 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13733 
    [ 2.500,  5.000) = 1582 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.526 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      4.807 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     26.360 ms/op
     p(99.9990) =     26.378 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 3.374 ±(99.9%) 0.159 ms/op
Iteration   1: 1.767 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   1.585 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.839 ms/op
                 existUser·p0.999:  13.255 ms/op
                 existUser·p0.9999: 13.697 ms/op
                 existUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18626
  mean =      1.767 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1055 
    [ 1.250,  2.500) = 16571 
    [ 2.500,  3.750) = 808 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      1.585 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.839 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     13.697 ms/op
     p(99.9990) =     13.697 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


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
# Warmup Iteration   1: 3.248 ±(99.9%) 0.073 ms/op
Iteration   1: 2.195 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   2.118 ms/op
                 getUser·p0.90:   2.818 ms/op
                 getUser·p0.95:   2.974 ms/op
                 getUser·p0.99:   3.498 ms/op
                 getUser·p0.999:  13.664 ms/op
                 getUser·p0.9999: 13.782 ms/op
                 getUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14602
  mean =      2.195 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 10617 
    [ 2.500,  3.750) = 3708 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 7 
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
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      2.974 ms/op
     p(99.0000) =      3.498 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     13.782 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 5.001 ±(99.9%) 0.214 ms/op
Iteration   1: 3.710 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   5.880 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 13.697 ms/op
                 listUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8623
  mean =      3.710 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 149 
    [ 2.500,  3.750) = 4246 
    [ 3.750,  5.000) = 3967 
    [ 5.000,  6.250) = 198 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      5.880 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     13.697 ms/op
     p(99.9990) =     13.697 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.314          ops/ms
ClientSimple.existUser                       thrpt         12.709          ops/ms
ClientSimple.getUser                         thrpt         10.571          ops/ms
ClientSimple.listUser                        thrpt          8.725          ops/ms
ClientSimple.createUser                       avgt          2.087           ms/op
ClientSimple.existUser                        avgt          1.857           ms/op
ClientSimple.getUser                          avgt          2.239           ms/op
ClientSimple.listUser                         avgt          3.388           ms/op
ClientSimple.createUser                     sample  15463   2.091 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.564           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.526           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.807           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.560           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.360           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.378           ms/op
ClientSimple.existUser                      sample  18626   1.767 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.569           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.585           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.839           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.255           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.697           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.697           ms/op
ClientSimple.getUser                        sample  14602   2.195 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.601           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.974           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.498           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.664           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.782           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.812           ms/op
ClientSimple.listUser                       sample   8623   3.710 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.061           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.723           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.880           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.582           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.697           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.697           ms/op

Benchmark result is saved to 1721780240804.json
