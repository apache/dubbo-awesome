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
# Warmup Iteration   1: 0.877 ops/ms
Iteration   1: 6.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.532 ops/ms


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
# Warmup Iteration   1: 5.513 ops/ms
Iteration   1: 12.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.737 ops/ms


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
# Warmup Iteration   1: 5.006 ops/ms
Iteration   1: 12.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.637 ops/ms


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
# Warmup Iteration   1: 4.491 ops/ms
Iteration   1: 8.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.209 ops/ms


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.074 ms/op
Iteration   1: 2.637 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.637 ms/op


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
# Warmup Iteration   1: 3.334 ±(99.9%) 0.053 ms/op
Iteration   1: 1.824 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.824 ms/op


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
# Warmup Iteration   1: 3.323 ±(99.9%) 0.064 ms/op
Iteration   1: 1.858 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.858 ms/op


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.074 ms/op
Iteration   1: 3.331 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.331 ms/op


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
# Warmup Iteration   1: 3.702 ±(99.9%) 0.104 ms/op
Iteration   1: 2.363 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.212 ms/op
                 createUser·p0.90:   2.763 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   7.014 ms/op
                 createUser·p0.999:  22.053 ms/op
                 createUser·p0.9999: 22.717 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13664
  mean =      2.363 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10134 
    [ 2.500,  5.000) = 3258 
    [ 5.000,  7.500) = 143 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.212 ms/op
     p(90.0000) =      2.763 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      7.014 ms/op
     p(99.9000) =     22.053 ms/op
     p(99.9900) =     22.717 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.103 ms/op
Iteration   1: 2.082 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   1.964 ms/op
                 existUser·p0.90:   2.662 ms/op
                 existUser·p0.95:   2.925 ms/op
                 existUser·p0.99:   5.091 ms/op
                 existUser·p0.999:  31.249 ms/op
                 existUser·p0.9999: 31.924 ms/op
                 existUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15355
  mean =      2.082 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12672 
    [ 2.500,  5.000) = 2524 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      5.091 ms/op
     p(99.9000) =     31.249 ms/op
     p(99.9900) =     31.924 ms/op
     p(99.9990) =     32.047 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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
# Warmup Iteration   1: 3.405 ±(99.9%) 0.114 ms/op
Iteration   1: 2.106 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.003 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   3.297 ms/op
                 getUser·p0.999:  15.614 ms/op
                 getUser·p0.9999: 16.179 ms/op
                 getUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15242
  mean =      2.106 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 12895 
    [ 2.500,  3.750) = 2235 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.003 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      3.297 ms/op
     p(99.9000) =     15.614 ms/op
     p(99.9900) =     16.179 ms/op
     p(99.9990) =     16.187 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 4.567 ±(99.9%) 0.143 ms/op
Iteration   1: 3.839 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  26.793 ms/op
                 listUser·p0.9999: 27.460 ms/op
                 listUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8330
  mean =      3.839 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 447 
    [ 2.500,  5.000) = 7434 
    [ 5.000,  7.500) = 378 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     26.793 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.532          ops/ms
ClientSimple.existUser                       thrpt         12.737          ops/ms
ClientSimple.getUser                         thrpt         12.637          ops/ms
ClientSimple.listUser                        thrpt          8.209          ops/ms
ClientSimple.createUser                       avgt          2.637           ms/op
ClientSimple.existUser                        avgt          1.824           ms/op
ClientSimple.getUser                          avgt          1.858           ms/op
ClientSimple.listUser                         avgt          3.331           ms/op
ClientSimple.createUser                     sample  13664   2.363 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.904           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.212           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.763           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.105           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.014           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.053           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.717           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.741           ms/op
ClientSimple.existUser                      sample  15355   2.082 ± 0.040   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.623           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.964           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.925           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.091           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.249           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.924           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.047           ms/op
ClientSimple.getUser                        sample  15242   2.106 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.842           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.003           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.297           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.614           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.179           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.187           ms/op
ClientSimple.listUser                       sample   8330   3.839 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.766           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.752           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.079           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.389           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.793           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.460           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.460           ms/op

Benchmark result is saved to 1716293195012.json
