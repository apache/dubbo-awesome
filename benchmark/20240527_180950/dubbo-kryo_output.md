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
# Warmup Iteration   1: 1.815 ops/ms
Iteration   1: 6.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.854 ops/ms


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
# Warmup Iteration   1: 5.478 ops/ms
Iteration   1: 11.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.103 ops/ms


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
# Warmup Iteration   1: 4.998 ops/ms
Iteration   1: 13.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.004 ops/ms


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
# Warmup Iteration   1: 4.823 ops/ms
Iteration   1: 8.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.513 ops/ms


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.080 ms/op
Iteration   1: 2.045 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.045 ms/op


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
# Warmup Iteration   1: 3.547 ±(99.9%) 0.074 ms/op
Iteration   1: 1.970 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.970 ms/op


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
# Warmup Iteration   1: 3.438 ±(99.9%) 0.062 ms/op
Iteration   1: 2.108 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.108 ms/op


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
# Warmup Iteration   1: 4.178 ±(99.9%) 0.076 ms/op
Iteration   1: 3.299 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.299 ms/op


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
# Warmup Iteration   1: 3.546 ±(99.9%) 0.083 ms/op
Iteration   1: 2.167 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   1.976 ms/op
                 createUser·p0.90:   2.535 ms/op
                 createUser·p0.95:   2.814 ms/op
                 createUser·p0.99:   7.986 ms/op
                 createUser·p0.999:  14.565 ms/op
                 createUser·p0.9999: 14.985 ms/op
                 createUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14759
  mean =      2.167 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 12904 
    [ 2.500,  3.750) = 1317 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      1.976 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      7.986 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     14.985 ms/op
     p(99.9990) =     15.352 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 2.960 ±(99.9%) 0.075 ms/op
Iteration   1: 2.019 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   1.882 ms/op
                 existUser·p0.90:   2.810 ms/op
                 existUser·p0.95:   3.005 ms/op
                 existUser·p0.99:   4.249 ms/op
                 existUser·p0.999:  14.221 ms/op
                 existUser·p0.9999: 14.425 ms/op
                 existUser·p1.00:   14.434 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15828
  mean =      2.019 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 304 
    [ 1.250,  2.500) = 12477 
    [ 2.500,  3.750) = 2857 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.005 ms/op
     p(99.0000) =      4.249 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     14.425 ms/op
     p(99.9990) =     14.434 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 3.250 ±(99.9%) 0.100 ms/op
Iteration   1: 1.865 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   1.825 ms/op
                 getUser·p0.90:   2.290 ms/op
                 getUser·p0.95:   2.466 ms/op
                 getUser·p0.99:   3.431 ms/op
                 getUser·p0.999:  17.990 ms/op
                 getUser·p0.9999: 19.118 ms/op
                 getUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17137
  mean =      1.865 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 718 
    [ 1.250,  2.500) = 15672 
    [ 2.500,  3.750) = 613 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.431 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     19.118 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.114 ms/op
Iteration   1: 3.410 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.396 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.762 ms/op
                 listUser·p0.99:   5.604 ms/op
                 listUser·p0.999:  7.487 ms/op
                 listUser·p0.9999: 7.758 ms/op
                 listUser·p1.00:   7.758 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9394
  mean =      3.410 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 11 
    [1.500, 2.000) = 68 
    [2.000, 2.500) = 926 
    [2.500, 3.000) = 2434 
    [3.000, 3.500) = 1717 
    [3.500, 4.000) = 2209 
    [4.000, 4.500) = 1242 
    [4.500, 5.000) = 485 
    [5.000, 5.500) = 193 
    [5.500, 6.000) = 60 
    [6.000, 6.500) = 13 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.762 ms/op
     p(99.0000) =      5.604 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =      7.758 ms/op
     p(99.9990) =      7.758 ms/op
     p(99.9999) =      7.758 ms/op
    p(100.0000) =      7.758 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.854          ops/ms
ClientSimple.existUser                       thrpt         11.103          ops/ms
ClientSimple.getUser                         thrpt         13.004          ops/ms
ClientSimple.listUser                        thrpt          8.513          ops/ms
ClientSimple.createUser                       avgt          2.045           ms/op
ClientSimple.existUser                        avgt          1.970           ms/op
ClientSimple.getUser                          avgt          2.108           ms/op
ClientSimple.listUser                         avgt          3.299           ms/op
ClientSimple.createUser                     sample  14759   2.167 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.581           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.976           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.535           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.986           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.565           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.985           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.352           ms/op
ClientSimple.existUser                      sample  15828   2.019 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.857           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.882           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.810           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.005           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.249           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.221           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.425           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.434           ms/op
ClientSimple.getUser                        sample  17137   1.865 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.857           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.825           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.290           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.431           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.990           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.118           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.399           ms/op
ClientSimple.listUser                       sample   9394   3.410 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.315           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.396           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.762           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.604           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.487           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.758           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.758           ms/op

Benchmark result is saved to 1716833118828.json
