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
# Warmup Iteration   1: 1.860 ops/ms
Iteration   1: 7.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.196 ops/ms


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
# Warmup Iteration   1: 5.793 ops/ms
Iteration   1: 12.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.569 ops/ms


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
# Warmup Iteration   1: 6.698 ops/ms
Iteration   1: 14.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.083 ops/ms


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
# Warmup Iteration   1: 5.106 ops/ms
Iteration   1: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.120 ops/ms


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.078 ms/op
Iteration   1: 2.205 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.205 ms/op


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
# Warmup Iteration   1: 3.461 ±(99.9%) 0.060 ms/op
Iteration   1: 1.866 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.866 ms/op


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.057 ms/op
Iteration   1: 1.931 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.931 ms/op


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.094 ms/op
Iteration   1: 3.438 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.438 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.110 ms/op
Iteration   1: 2.286 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   2.220 ms/op
                 createUser·p0.90:   2.900 ms/op
                 createUser·p0.95:   3.130 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  17.270 ms/op
                 createUser·p0.9999: 19.235 ms/op
                 createUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13997
  mean =      2.286 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 306 
    [ 1.250,  2.500) = 9251 
    [ 2.500,  3.750) = 4203 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 99 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.130 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     17.270 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 2.953 ±(99.9%) 0.073 ms/op
Iteration   1: 1.855 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.306 ms/op
                 existUser·p0.50:   1.665 ms/op
                 existUser·p0.90:   2.699 ms/op
                 existUser·p0.95:   2.937 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  22.959 ms/op
                 existUser·p0.9999: 23.193 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17335
  mean =      1.855 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14892 
    [ 2.500,  5.000) = 2339 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.306 ms/op
     p(50.0000) =      1.665 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =     22.959 ms/op
     p(99.9900) =     23.193 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.084 ms/op
Iteration   1: 1.782 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.615 ms/op
                 getUser·p0.50:   1.690 ms/op
                 getUser·p0.90:   2.089 ms/op
                 getUser·p0.95:   2.306 ms/op
                 getUser·p0.99:   3.253 ms/op
                 getUser·p0.999:  11.108 ms/op
                 getUser·p0.9999: 11.190 ms/op
                 getUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17988
  mean =      1.782 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 17311 
    [ 2.500,  3.750) = 368 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      1.690 ms/op
     p(90.0000) =      2.089 ms/op
     p(95.0000) =      2.306 ms/op
     p(99.0000) =      3.253 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     11.190 ms/op
     p(99.9990) =     11.190 ms/op
     p(99.9999) =     11.190 ms/op
    p(100.0000) =     11.190 ms/op


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.136 ms/op
Iteration   1: 3.672 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.510 ms/op
                 listUser·p0.999:  9.688 ms/op
                 listUser·p0.9999: 12.878 ms/op
                 listUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8713
  mean =      3.672 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 380 
    [ 2.500,  3.750) = 4500 
    [ 3.750,  5.000) = 3407 
    [ 5.000,  6.250) = 319 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.510 ms/op
     p(99.9000) =      9.688 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.196          ops/ms
ClientSimple.existUser                       thrpt         12.569          ops/ms
ClientSimple.getUser                         thrpt         14.083          ops/ms
ClientSimple.listUser                        thrpt          8.120          ops/ms
ClientSimple.createUser                       avgt          2.205           ms/op
ClientSimple.existUser                        avgt          1.866           ms/op
ClientSimple.getUser                          avgt          1.931           ms/op
ClientSimple.listUser                         avgt          3.438           ms/op
ClientSimple.createUser                     sample  13997   2.286 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.630           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.220           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.130           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.284           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.270           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.235           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.300           ms/op
ClientSimple.existUser                      sample  17335   1.855 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.306           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.665           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.699           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.937           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.682           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.959           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.193           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.265           ms/op
ClientSimple.getUser                        sample  17988   1.782 ± 0.013   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.615           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.690           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.089           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.306           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.253           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.108           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.190           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.190           ms/op
ClientSimple.listUser                       sample   8713   3.672 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.262           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.641           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.510           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.688           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.878           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.878           ms/op

Benchmark result is saved to 1717351550477.json
