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
# Warmup Iteration   1: 2.135 ops/ms
Iteration   1: 7.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.623 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.984 ops/ms
Iteration   1: 13.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.312 ops/ms


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
# Warmup Iteration   1: 5.312 ops/ms
Iteration   1: 13.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.525 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.975 ops/ms
Iteration   1: 7.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.774 ops/ms


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
# Warmup Iteration   1: 4.289 ±(99.9%) 0.075 ms/op
Iteration   1: 2.419 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.419 ms/op


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
# Warmup Iteration   1: 3.471 ±(99.9%) 0.089 ms/op
Iteration   1: 2.039 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.039 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.052 ms/op
Iteration   1: 2.151 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.151 ms/op


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.083 ms/op
Iteration   1: 3.164 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.164 ms/op


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.094 ms/op
Iteration   1: 2.116 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   2.531 ms/op
                 createUser·p0.95:   2.974 ms/op
                 createUser·p0.99:   10.863 ms/op
                 createUser·p0.999:  14.627 ms/op
                 createUser·p0.9999: 18.448 ms/op
                 createUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15133
  mean =      2.116 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 679 
    [ 1.250,  2.500) = 12827 
    [ 2.500,  3.750) = 1300 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.974 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     14.627 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.074 ms/op
Iteration   1: 1.893 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   1.774 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   3.289 ms/op
                 existUser·p0.999:  15.140 ms/op
                 existUser·p0.9999: 16.869 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16899
  mean =      1.893 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 416 
    [ 1.250,  2.500) = 15359 
    [ 2.500,  3.750) = 1006 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.289 ms/op
     p(99.9000) =     15.140 ms/op
     p(99.9900) =     16.869 ms/op
     p(99.9990) =     17.072 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 3.143 ±(99.9%) 0.080 ms/op
Iteration   1: 2.142 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.308 ms/op
                 getUser·p0.50:   1.890 ms/op
                 getUser·p0.90:   2.908 ms/op
                 getUser·p0.95:   3.274 ms/op
                 getUser·p0.99:   5.552 ms/op
                 getUser·p0.999:  26.104 ms/op
                 getUser·p0.9999: 26.590 ms/op
                 getUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15074
  mean =      2.142 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11851 
    [ 2.500,  5.000) = 3070 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.274 ms/op
     p(99.0000) =      5.552 ms/op
     p(99.9000) =     26.104 ms/op
     p(99.9900) =     26.590 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 4.893 ±(99.9%) 0.159 ms/op
Iteration   1: 3.698 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.717 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.626 ms/op
                 listUser·p0.999:  14.406 ms/op
                 listUser·p0.9999: 14.565 ms/op
                 listUser·p1.00:   14.565 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8719
  mean =      3.698 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 780 
    [ 2.500,  3.750) = 4455 
    [ 3.750,  5.000) = 2867 
    [ 5.000,  6.250) = 461 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      6.626 ms/op
     p(99.9000) =     14.406 ms/op
     p(99.9900) =     14.565 ms/op
     p(99.9990) =     14.565 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.623          ops/ms
ClientSimple.existUser                       thrpt         13.312          ops/ms
ClientSimple.getUser                         thrpt         13.525          ops/ms
ClientSimple.listUser                        thrpt          7.774          ops/ms
ClientSimple.createUser                       avgt          2.419           ms/op
ClientSimple.existUser                        avgt          2.039           ms/op
ClientSimple.getUser                          avgt          2.151           ms/op
ClientSimple.listUser                         avgt          3.164           ms/op
ClientSimple.createUser                     sample  15133   2.116 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.524           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.531           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.974           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.863           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.627           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.448           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.448           ms/op
ClientSimple.existUser                      sample  16899   1.893 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.781           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.774           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.289           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.140           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.869           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.072           ms/op
ClientSimple.getUser                        sample  15074   2.142 ± 0.038   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.308           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.890           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.908           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.274           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.552           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.104           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.590           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.673           ms/op
ClientSimple.listUser                       sample   8719   3.698 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.717           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.617           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.626           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.406           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.565           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.565           ms/op

Benchmark result is saved to 1724695863615.json
