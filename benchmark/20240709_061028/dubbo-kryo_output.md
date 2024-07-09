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
# Warmup Iteration   1: 1.706 ops/ms
Iteration   1: 6.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.830 ops/ms


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
# Warmup Iteration   1: 5.187 ops/ms
Iteration   1: 11.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.628 ops/ms


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
# Warmup Iteration   1: 6.038 ops/ms
Iteration   1: 12.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.314 ops/ms


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
# Warmup Iteration   1: 5.841 ops/ms
Iteration   1: 8.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.758 ops/ms


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
# Warmup Iteration   1: 4.785 ±(99.9%) 0.094 ms/op
Iteration   1: 2.177 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.177 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.050 ms/op
Iteration   1: 1.869 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.869 ms/op


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
# Warmup Iteration   1: 3.368 ±(99.9%) 0.052 ms/op
Iteration   1: 2.105 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.105 ms/op


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
# Warmup Iteration   1: 4.676 ±(99.9%) 0.081 ms/op
Iteration   1: 3.422 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.422 ms/op


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
# Warmup Iteration   1: 3.429 ±(99.9%) 0.082 ms/op
Iteration   1: 2.193 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   2.052 ms/op
                 createUser·p0.90:   2.613 ms/op
                 createUser·p0.95:   2.843 ms/op
                 createUser·p0.99:   6.402 ms/op
                 createUser·p0.999:  19.181 ms/op
                 createUser·p0.9999: 22.153 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14647
  mean =      2.193 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12568 
    [ 2.500,  5.000) = 1871 
    [ 5.000,  7.500) = 112 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      2.052 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      6.402 ms/op
     p(99.9000) =     19.181 ms/op
     p(99.9900) =     22.153 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 3.015 ±(99.9%) 0.091 ms/op
Iteration   1: 2.091 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.508 ms/op
                 existUser·p0.50:   1.909 ms/op
                 existUser·p0.90:   2.490 ms/op
                 existUser·p0.95:   2.794 ms/op
                 existUser·p0.99:   5.613 ms/op
                 existUser·p0.999:  26.598 ms/op
                 existUser·p0.9999: 27.602 ms/op
                 existUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15295
  mean =      2.091 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13800 
    [ 2.500,  5.000) = 1288 
    [ 5.000,  7.500) = 107 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.794 ms/op
     p(99.0000) =      5.613 ms/op
     p(99.9000) =     26.598 ms/op
     p(99.9900) =     27.602 ms/op
     p(99.9990) =     27.689 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 3.182 ±(99.9%) 0.085 ms/op
Iteration   1: 2.157 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.073 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.867 ms/op
                 getUser·p0.99:   5.029 ms/op
                 getUser·p0.999:  14.735 ms/op
                 getUser·p0.9999: 22.653 ms/op
                 getUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14907
  mean =      2.157 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12516 
    [ 2.500,  5.000) = 2240 
    [ 5.000,  7.500) = 87 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.073 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      5.029 ms/op
     p(99.9000) =     14.735 ms/op
     p(99.9900) =     22.653 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 4.660 ±(99.9%) 0.122 ms/op
Iteration   1: 3.814 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.358 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 16.351 ms/op
                 listUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8376
  mean =      3.814 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1040 
    [ 2.500,  3.750) = 2611 
    [ 3.750,  5.000) = 4166 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      7.358 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     16.351 ms/op
     p(99.9990) =     16.351 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.830          ops/ms
ClientSimple.existUser                       thrpt         11.628          ops/ms
ClientSimple.getUser                         thrpt         12.314          ops/ms
ClientSimple.listUser                        thrpt          8.758          ops/ms
ClientSimple.createUser                       avgt          2.177           ms/op
ClientSimple.existUser                        avgt          1.869           ms/op
ClientSimple.getUser                          avgt          2.105           ms/op
ClientSimple.listUser                         avgt          3.422           ms/op
ClientSimple.createUser                     sample  14647   2.193 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.610           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.052           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.843           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.402           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.181           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.153           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.184           ms/op
ClientSimple.existUser                      sample  15295   2.091 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.508           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.909           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.794           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.613           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.598           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.602           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.689           ms/op
ClientSimple.getUser                        sample  14907   2.157 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.699           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.073           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.867           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.029           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.735           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.653           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.084           ms/op
ClientSimple.listUser                       sample   8376   3.814 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.831           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.784           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.136           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.358           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.286           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.351           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.351           ms/op

Benchmark result is saved to 1720505164058.json
