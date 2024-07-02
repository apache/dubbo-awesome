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
# Warmup Iteration   1: 1.858 ops/ms
Iteration   1: 8.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.377 ops/ms


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
# Warmup Iteration   1: 5.330 ops/ms
Iteration   1: 11.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.783 ops/ms


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
# Warmup Iteration   1: 5.380 ops/ms
Iteration   1: 12.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.085 ops/ms


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
# Warmup Iteration   1: 5.003 ops/ms
Iteration   1: 8.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.776 ops/ms


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.064 ms/op
Iteration   1: 2.014 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.014 ms/op


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
# Warmup Iteration   1: 2.835 ±(99.9%) 0.048 ms/op
Iteration   1: 1.773 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.773 ms/op


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
# Warmup Iteration   1: 3.191 ±(99.9%) 0.048 ms/op
Iteration   1: 1.942 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.942 ms/op


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
# Warmup Iteration   1: 4.490 ±(99.9%) 0.079 ms/op
Iteration   1: 3.581 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.581 ms/op


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.212 ms/op
Iteration   1: 2.036 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   1.812 ms/op
                 createUser·p0.90:   2.408 ms/op
                 createUser·p0.95:   2.672 ms/op
                 createUser·p0.99:   9.193 ms/op
                 createUser·p0.999:  16.122 ms/op
                 createUser·p0.9999: 17.496 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15692
  mean =      2.036 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 14502 
    [ 2.500,  3.750) = 781 
    [ 3.750,  5.000) = 156 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.672 ms/op
     p(99.0000) =      9.193 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     17.496 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.405 ±(99.9%) 0.132 ms/op
Iteration   1: 1.924 ±(99.9%) 0.068 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   1.692 ms/op
                 existUser·p0.90:   2.118 ms/op
                 existUser·p0.95:   2.331 ms/op
                 existUser·p0.99:   5.471 ms/op
                 existUser·p0.999:  47.720 ms/op
                 existUser·p0.9999: 70.170 ms/op
                 existUser·p1.00:   70.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16618
  mean =      1.924 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16425 
    [ 5.000, 10.000) = 73 
    [10.000, 15.000) = 35 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 10 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 1 
    [65.000, 70.000) = 8 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      1.692 ms/op
     p(90.0000) =      2.118 ms/op
     p(95.0000) =      2.331 ms/op
     p(99.0000) =      5.471 ms/op
     p(99.9000) =     47.720 ms/op
     p(99.9900) =     70.170 ms/op
     p(99.9990) =     70.517 ms/op
     p(99.9999) =     70.517 ms/op
    p(100.0000) =     70.517 ms/op


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
# Warmup Iteration   1: 3.256 ±(99.9%) 0.085 ms/op
Iteration   1: 2.078 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.556 ms/op
                 getUser·p0.50:   2.017 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.748 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  12.414 ms/op
                 getUser·p0.9999: 12.780 ms/op
                 getUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15440
  mean =      2.078 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 165 
    [ 1.250,  2.500) = 13200 
    [ 2.500,  3.750) = 1944 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =     12.414 ms/op
     p(99.9900) =     12.780 ms/op
     p(99.9990) =     12.780 ms/op
     p(99.9999) =     12.780 ms/op
    p(100.0000) =     12.780 ms/op


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
# Warmup Iteration   1: 4.786 ±(99.9%) 0.151 ms/op
Iteration   1: 3.385 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.692 ms/op
                 listUser·p0.50:   3.232 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.662 ms/op
                 listUser·p0.99:   7.031 ms/op
                 listUser·p0.999:  14.492 ms/op
                 listUser·p0.9999: 15.827 ms/op
                 listUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9457
  mean =      3.385 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 489 
    [ 2.500,  3.750) = 6645 
    [ 3.750,  5.000) = 2054 
    [ 5.000,  6.250) = 153 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.662 ms/op
     p(99.0000) =      7.031 ms/op
     p(99.9000) =     14.492 ms/op
     p(99.9900) =     15.827 ms/op
     p(99.9990) =     15.827 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.377          ops/ms
ClientSimple.existUser                       thrpt         11.783          ops/ms
ClientSimple.getUser                         thrpt         12.085          ops/ms
ClientSimple.listUser                        thrpt          8.776          ops/ms
ClientSimple.createUser                       avgt          2.014           ms/op
ClientSimple.existUser                        avgt          1.773           ms/op
ClientSimple.getUser                          avgt          1.942           ms/op
ClientSimple.listUser                         avgt          3.581           ms/op
ClientSimple.createUser                     sample  15692   2.036 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.682           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.812           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.408           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.672           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.193           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.122           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.496           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.186           ms/op
ClientSimple.existUser                      sample  16618   1.924 ± 0.068   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.536           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.692           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.471           ms/op
ClientSimple.existUser:existUser·p0.999     sample         47.720           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         70.170           ms/op
ClientSimple.existUser:existUser·p1.00      sample         70.517           ms/op
ClientSimple.getUser                        sample  15440   2.078 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.556           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.017           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.650           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.414           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.780           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.780           ms/op
ClientSimple.listUser                       sample   9457   3.385 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.692           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.232           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.662           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.031           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.492           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.827           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.827           ms/op

Benchmark result is saved to 1719879370165.json
