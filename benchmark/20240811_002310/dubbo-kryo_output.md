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
# Warmup Iteration   1: 1.827 ops/ms
Iteration   1: 7.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.047 ops/ms


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
# Warmup Iteration   1: 7.167 ops/ms
Iteration   1: 12.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.797 ops/ms


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
# Warmup Iteration   1: 6.534 ops/ms
Iteration   1: 13.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.594 ops/ms


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
# Warmup Iteration   1: 5.685 ops/ms
Iteration   1: 9.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.476 ops/ms


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
# Warmup Iteration   1: 3.529 ±(99.9%) 0.059 ms/op
Iteration   1: 2.225 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.225 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.316 ±(99.9%) 0.051 ms/op
Iteration   1: 1.871 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.871 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.452 ±(99.9%) 0.066 ms/op
Iteration   1: 1.895 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.895 ms/op


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
# Warmup Iteration   1: 4.371 ±(99.9%) 0.096 ms/op
Iteration   1: 3.119 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.119 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.416 ±(99.9%) 0.097 ms/op
Iteration   1: 2.050 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   1.890 ms/op
                 createUser·p0.90:   2.261 ms/op
                 createUser·p0.95:   2.609 ms/op
                 createUser·p0.99:   5.919 ms/op
                 createUser·p0.999:  27.373 ms/op
                 createUser·p0.9999: 28.017 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15649
  mean =      2.050 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14768 
    [ 2.500,  5.000) = 655 
    [ 5.000,  7.500) = 97 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      5.919 ms/op
     p(99.9000) =     27.373 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 3.046 ±(99.9%) 0.070 ms/op
Iteration   1: 1.969 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.580 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.732 ms/op
                 existUser·p0.99:   3.869 ms/op
                 existUser·p0.999:  18.055 ms/op
                 existUser·p0.9999: 18.444 ms/op
                 existUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16251
  mean =      1.969 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 14403 
    [ 2.500,  3.750) = 1527 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.869 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     18.444 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.233 ms/op
Iteration   1: 2.224 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.239 ms/op
                 getUser·p0.50:   2.101 ms/op
                 getUser·p0.90:   2.761 ms/op
                 getUser·p0.95:   3.305 ms/op
                 getUser·p0.99:   6.978 ms/op
                 getUser·p0.999:  12.707 ms/op
                 getUser·p0.9999: 14.584 ms/op
                 getUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14423
  mean =      2.224 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 264 
    [ 1.250,  2.500) = 11363 
    [ 2.500,  3.750) = 2348 
    [ 3.750,  5.000) = 245 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.239 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.305 ms/op
     p(99.0000) =      6.978 ms/op
     p(99.9000) =     12.707 ms/op
     p(99.9900) =     14.584 ms/op
     p(99.9990) =     14.598 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.146 ms/op
Iteration   1: 2.985 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.570 ms/op
                 listUser·p0.50:   2.826 ms/op
                 listUser·p0.90:   3.682 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   4.740 ms/op
                 listUser·p0.999:  8.047 ms/op
                 listUser·p0.9999: 9.517 ms/op
                 listUser·p1.00:   9.585 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10732
  mean =      2.985 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 72 
    [ 2.000,  3.000) = 7850 
    [ 3.000,  4.000) = 2060 
    [ 4.000,  5.000) = 659 
    [ 5.000,  6.000) = 21 
    [ 6.000,  7.000) = 25 
    [ 7.000,  8.000) = 31 
    [ 8.000,  9.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      4.740 ms/op
     p(99.9000) =      8.047 ms/op
     p(99.9900) =      9.517 ms/op
     p(99.9990) =      9.585 ms/op
     p(99.9999) =      9.585 ms/op
    p(100.0000) =      9.585 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.047          ops/ms
ClientSimple.existUser                       thrpt         12.797          ops/ms
ClientSimple.getUser                         thrpt         13.594          ops/ms
ClientSimple.listUser                        thrpt          9.476          ops/ms
ClientSimple.createUser                       avgt          2.225           ms/op
ClientSimple.existUser                        avgt          1.871           ms/op
ClientSimple.getUser                          avgt          1.895           ms/op
ClientSimple.listUser                         avgt          3.119           ms/op
ClientSimple.createUser                     sample  15649   2.050 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.657           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.890           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.261           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.609           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.919           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.373           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.017           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.017           ms/op
ClientSimple.existUser                      sample  16251   1.969 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.580           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.780           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.732           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.869           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.055           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.444           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.711           ms/op
ClientSimple.getUser                        sample  14423   2.224 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.239           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.101           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.305           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.978           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.707           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.584           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.598           ms/op
ClientSimple.listUser                       sample  10732   2.985 ± 0.019   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.570           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.826           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.682           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.740           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.047           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.517           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.585           ms/op

Benchmark result is saved to 1723335514824.json
