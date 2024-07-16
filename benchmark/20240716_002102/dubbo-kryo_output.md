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
# Warmup Iteration   1: 1.737 ops/ms
Iteration   1: 7.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.110 ops/ms


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
# Warmup Iteration   1: 6.052 ops/ms
Iteration   1: 12.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.093 ops/ms


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
# Warmup Iteration   1: 6.080 ops/ms
Iteration   1: 14.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.324 ops/ms


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
# Warmup Iteration   1: 5.235 ops/ms
Iteration   1: 8.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.438 ops/ms


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.093 ms/op
Iteration   1: 2.060 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.060 ms/op


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
# Warmup Iteration   1: 3.003 ±(99.9%) 0.052 ms/op
Iteration   1: 1.925 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.925 ms/op


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
# Warmup Iteration   1: 3.483 ±(99.9%) 0.069 ms/op
Iteration   1: 1.899 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.899 ms/op


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
# Warmup Iteration   1: 4.997 ±(99.9%) 0.116 ms/op
Iteration   1: 3.551 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.551 ms/op


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
# Warmup Iteration   1: 3.690 ±(99.9%) 0.122 ms/op
Iteration   1: 2.207 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   1.894 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   14.107 ms/op
                 createUser·p0.999:  28.290 ms/op
                 createUser·p0.9999: 33.655 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14659
  mean =      2.207 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12899 
    [ 2.500,  5.000) = 1471 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =     14.107 ms/op
     p(99.9000) =     28.290 ms/op
     p(99.9900) =     33.655 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 2.928 ±(99.9%) 0.069 ms/op
Iteration   1: 1.964 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.443 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.548 ms/op
                 existUser·p0.95:   2.843 ms/op
                 existUser·p0.99:   5.747 ms/op
                 existUser·p0.999:  12.481 ms/op
                 existUser·p0.9999: 14.803 ms/op
                 existUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16224
  mean =      1.964 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 622 
    [ 1.250,  2.500) = 13825 
    [ 2.500,  3.750) = 1563 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      5.747 ms/op
     p(99.9000) =     12.481 ms/op
     p(99.9900) =     14.803 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 3.585 ±(99.9%) 0.114 ms/op
Iteration   1: 1.939 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   1.866 ms/op
                 getUser·p0.90:   2.208 ms/op
                 getUser·p0.95:   2.445 ms/op
                 getUser·p0.99:   3.364 ms/op
                 getUser·p0.999:  9.788 ms/op
                 getUser·p0.9999: 10.431 ms/op
                 getUser·p1.00:   10.453 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16575
  mean =      1.939 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 12627 
    [ 2.000,  3.000) = 3682 
    [ 3.000,  4.000) = 169 
    [ 4.000,  5.000) = 30 
    [ 5.000,  6.000) = 4 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 23 
    [ 8.000,  9.000) = 9 
    [ 9.000, 10.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.445 ms/op
     p(99.0000) =      3.364 ms/op
     p(99.9000) =      9.788 ms/op
     p(99.9900) =     10.431 ms/op
     p(99.9990) =     10.453 ms/op
     p(99.9999) =     10.453 ms/op
    p(100.0000) =     10.453 ms/op


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
# Warmup Iteration   1: 4.967 ±(99.9%) 0.198 ms/op
Iteration   1: 3.791 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  21.398 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8431
  mean =      3.791 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 330 
    [ 2.500,  5.000) = 7801 
    [ 5.000,  7.500) = 249 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.110          ops/ms
ClientSimple.existUser                       thrpt         12.093          ops/ms
ClientSimple.getUser                         thrpt         14.324          ops/ms
ClientSimple.listUser                        thrpt          8.438          ops/ms
ClientSimple.createUser                       avgt          2.060           ms/op
ClientSimple.existUser                        avgt          1.925           ms/op
ClientSimple.getUser                          avgt          1.899           ms/op
ClientSimple.listUser                         avgt          3.551           ms/op
ClientSimple.createUser                     sample  14659   2.207 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.530           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.894           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample         14.107           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.290           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.655           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.686           ms/op
ClientSimple.existUser                      sample  16224   1.964 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.443           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.772           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.843           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.747           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.481           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.803           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.844           ms/op
ClientSimple.getUser                        sample  16575   1.939 ± 0.013   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.112           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.866           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.208           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.364           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.788           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.431           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.453           ms/op
ClientSimple.listUser                       sample   8431   3.791 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.204           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.756           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.816           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.398           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.660           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.660           ms/op

Benchmark result is saved to 1721089004640.json
