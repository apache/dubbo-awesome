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
# Warmup Iteration   1: 1.839 ops/ms
Iteration   1: 7.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.559 ops/ms


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
# Warmup Iteration   1: 5.975 ops/ms
Iteration   1: 10.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.815 ops/ms


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
# Warmup Iteration   1: 5.037 ops/ms
Iteration   1: 12.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.839 ops/ms


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
# Warmup Iteration   1: 5.004 ops/ms
Iteration   1: 8.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.922 ops/ms


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
# Warmup Iteration   1: 3.627 ±(99.9%) 0.066 ms/op
Iteration   1: 1.981 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.981 ms/op


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
# Warmup Iteration   1: 2.961 ±(99.9%) 0.048 ms/op
Iteration   1: 1.877 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.877 ms/op


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
# Warmup Iteration   1: 3.171 ±(99.9%) 0.064 ms/op
Iteration   1: 2.236 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.236 ms/op


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
# Warmup Iteration   1: 5.263 ±(99.9%) 0.114 ms/op
Iteration   1: 3.162 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.162 ms/op


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
# Warmup Iteration   1: 3.355 ±(99.9%) 0.080 ms/op
Iteration   1: 2.034 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   1.872 ms/op
                 createUser·p0.90:   2.408 ms/op
                 createUser·p0.95:   2.695 ms/op
                 createUser·p0.99:   5.305 ms/op
                 createUser·p0.999:  18.383 ms/op
                 createUser·p0.9999: 19.272 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15706
  mean =      2.034 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 163 
    [ 1.250,  2.500) = 14253 
    [ 2.500,  3.750) = 889 
    [ 3.750,  5.000) = 227 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      5.305 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     19.272 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 2.917 ±(99.9%) 0.068 ms/op
Iteration   1: 1.735 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   1.561 ms/op
                 existUser·p0.90:   2.025 ms/op
                 existUser·p0.95:   2.228 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  37.356 ms/op
                 existUser·p0.9999: 37.890 ms/op
                 existUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18479
  mean =      1.735 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18058 
    [ 2.500,  5.000) = 341 
    [ 5.000,  7.500) = 16 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      1.561 ms/op
     p(90.0000) =      2.025 ms/op
     p(95.0000) =      2.228 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =     37.356 ms/op
     p(99.9900) =     37.890 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 3.442 ±(99.9%) 0.089 ms/op
Iteration   1: 2.095 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   1.970 ms/op
                 getUser·p0.90:   2.544 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   3.779 ms/op
                 getUser·p0.999:  23.550 ms/op
                 getUser·p0.9999: 24.780 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15309
  mean =      2.095 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13513 
    [ 2.500,  5.000) = 1696 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      3.779 ms/op
     p(99.9000) =     23.550 ms/op
     p(99.9900) =     24.780 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.118 ms/op
Iteration   1: 3.048 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.379 ms/op
                 listUser·p0.50:   2.839 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.133 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  11.764 ms/op
                 listUser·p0.9999: 12.560 ms/op
                 listUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10496
  mean =      3.048 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 564 
    [ 2.500,  3.750) = 8632 
    [ 3.750,  5.000) = 1094 
    [ 5.000,  6.250) = 172 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     12.560 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.559          ops/ms
ClientSimple.existUser                       thrpt         10.815          ops/ms
ClientSimple.getUser                         thrpt         12.839          ops/ms
ClientSimple.listUser                        thrpt          8.922          ops/ms
ClientSimple.createUser                       avgt          1.981           ms/op
ClientSimple.existUser                        avgt          1.877           ms/op
ClientSimple.getUser                          avgt          2.236           ms/op
ClientSimple.listUser                         avgt          3.162           ms/op
ClientSimple.createUser                     sample  15706   2.034 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.790           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.872           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.408           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.305           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.383           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.272           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.366           ms/op
ClientSimple.existUser                      sample  18479   1.735 ± 0.041   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.630           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.561           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.025           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.228           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.010           ms/op
ClientSimple.existUser:existUser·p0.999     sample         37.356           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         37.890           ms/op
ClientSimple.existUser:existUser·p1.00      sample         37.945           ms/op
ClientSimple.getUser                        sample  15309   2.095 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.524           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.970           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.544           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.779           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.550           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.780           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.936           ms/op
ClientSimple.listUser                       sample  10496   3.048 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.379           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.839           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.858           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.133           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.603           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.764           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.560           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.567           ms/op

Benchmark result is saved to 1723896358651.json
