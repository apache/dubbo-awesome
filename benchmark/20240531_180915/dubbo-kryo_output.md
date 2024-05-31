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
# Warmup Iteration   1: 1.811 ops/ms
Iteration   1: 7.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.536 ops/ms


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
# Warmup Iteration   1: 5.264 ops/ms
Iteration   1: 11.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.782 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.220 ops/ms
Iteration   1: 11.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.945 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ops/ms
Iteration   1: 7.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.256 ops/ms


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.079 ms/op
Iteration   1: 2.281 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.281 ms/op


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
# Warmup Iteration   1: 3.307 ±(99.9%) 0.073 ms/op
Iteration   1: 2.016 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.016 ms/op


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
# Warmup Iteration   1: 3.239 ±(99.9%) 0.069 ms/op
Iteration   1: 2.140 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.140 ms/op


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
# Warmup Iteration   1: 4.973 ±(99.9%) 0.113 ms/op
Iteration   1: 3.253 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.253 ms/op


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.089 ms/op
Iteration   1: 2.239 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   1.937 ms/op
                 createUser·p0.90:   2.867 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   7.906 ms/op
                 createUser·p0.999:  21.520 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14265
  mean =      2.239 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10871 
    [ 2.500,  5.000) = 3201 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      7.906 ms/op
     p(99.9000) =     21.520 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 3.092 ±(99.9%) 0.081 ms/op
Iteration   1: 1.861 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.580 ms/op
                 existUser·p0.50:   1.694 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  11.698 ms/op
                 existUser·p0.9999: 11.829 ms/op
                 existUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17199
  mean =      1.861 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 577 
    [ 1.250,  2.500) = 15012 
    [ 2.500,  3.750) = 1452 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      1.694 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.478 ms/op
     p(99.9000) =     11.698 ms/op
     p(99.9900) =     11.829 ms/op
     p(99.9990) =     11.829 ms/op
     p(99.9999) =     11.829 ms/op
    p(100.0000) =     11.829 ms/op


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.110 ms/op
Iteration   1: 2.127 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.054 ms/op
                 getUser·p0.90:   2.712 ms/op
                 getUser·p0.95:   2.970 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  21.037 ms/op
                 getUser·p0.9999: 22.167 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15019
  mean =      2.127 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12321 
    [ 2.500,  5.000) = 2593 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     22.167 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 5.630 ±(99.9%) 0.160 ms/op
Iteration   1: 3.307 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   0.546 ms/op
                 listUser·p0.50:   3.256 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  18.066 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9678
  mean =      3.307 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 2333 
    [ 2.500,  3.750) = 5066 
    [ 3.750,  5.000) = 1962 
    [ 5.000,  6.250) = 188 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     18.066 ms/op
     p(99.9900) =     18.186 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.536          ops/ms
ClientSimple.existUser                       thrpt         11.782          ops/ms
ClientSimple.getUser                         thrpt         11.945          ops/ms
ClientSimple.listUser                        thrpt          7.256          ops/ms
ClientSimple.createUser                       avgt          2.281           ms/op
ClientSimple.existUser                        avgt          2.016           ms/op
ClientSimple.getUser                          avgt          2.140           ms/op
ClientSimple.listUser                         avgt          3.253           ms/op
ClientSimple.createUser                     sample  14265   2.239 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.628           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.937           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.088           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.906           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.520           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.347           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.445           ms/op
ClientSimple.existUser                      sample  17199   1.861 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.580           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.694           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.675           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.478           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.698           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.829           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.829           ms/op
ClientSimple.getUser                        sample  15019   2.127 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.554           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.054           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.970           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.100           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.037           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.167           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.217           ms/op
ClientSimple.listUser                       sample   9678   3.307 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.546           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.256           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.121           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.497           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.545           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.066           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.186           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.186           ms/op

Benchmark result is saved to 1717178708304.json
