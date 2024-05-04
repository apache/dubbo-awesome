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
# Warmup Iteration   1: 1.818 ops/ms
Iteration   1: 7.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.620 ops/ms


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
# Warmup Iteration   1: 6.869 ops/ms
Iteration   1: 13.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.305 ops/ms


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
# Warmup Iteration   1: 5.750 ops/ms
Iteration   1: 14.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.223 ops/ms


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
# Warmup Iteration   1: 4.294 ops/ms
Iteration   1: 8.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.660 ops/ms


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.081 ms/op
Iteration   1: 2.519 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.519 ms/op


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
# Warmup Iteration   1: 3.450 ±(99.9%) 0.052 ms/op
Iteration   1: 2.074 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.074 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.061 ms/op
Iteration   1: 2.172 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.172 ms/op


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
# Warmup Iteration   1: 4.482 ±(99.9%) 0.091 ms/op
Iteration   1: 3.358 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.358 ms/op


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
# Warmup Iteration   1: 3.380 ±(99.9%) 0.084 ms/op
Iteration   1: 2.329 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   2.224 ms/op
                 createUser·p0.90:   2.773 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   5.143 ms/op
                 createUser·p0.999:  15.094 ms/op
                 createUser·p0.9999: 16.241 ms/op
                 createUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13730
  mean =      2.329 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 9449 
    [ 2.500,  3.750) = 3851 
    [ 3.750,  5.000) = 148 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      2.773 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      5.143 ms/op
     p(99.9000) =     15.094 ms/op
     p(99.9900) =     16.241 ms/op
     p(99.9990) =     16.351 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


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
# Warmup Iteration   1: 3.146 ±(99.9%) 0.088 ms/op
Iteration   1: 2.210 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   2.081 ms/op
                 existUser·p0.90:   2.646 ms/op
                 existUser·p0.95:   2.884 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  21.561 ms/op
                 existUser·p0.9999: 22.870 ms/op
                 existUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14461
  mean =      2.210 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11549 
    [ 2.500,  5.000) = 2746 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     21.561 ms/op
     p(99.9900) =     22.870 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 3.406 ±(99.9%) 0.091 ms/op
Iteration   1: 1.926 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.349 ms/op
                 getUser·p0.50:   1.808 ms/op
                 getUser·p0.90:   2.335 ms/op
                 getUser·p0.95:   2.605 ms/op
                 getUser·p0.99:   3.345 ms/op
                 getUser·p0.999:  12.418 ms/op
                 getUser·p0.9999: 13.825 ms/op
                 getUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16842
  mean =      1.926 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 15690 
    [ 2.500,  3.750) = 956 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      3.345 ms/op
     p(99.9000) =     12.418 ms/op
     p(99.9900) =     13.825 ms/op
     p(99.9990) =     13.926 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 4.461 ±(99.9%) 0.133 ms/op
Iteration   1: 3.111 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   4.032 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.160 ms/op
                 listUser·p0.999:  16.722 ms/op
                 listUser·p0.9999: 18.999 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10376
  mean =      3.111 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2129 
    [ 2.500,  3.750) = 6434 
    [ 3.750,  5.000) = 1602 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      4.032 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     16.722 ms/op
     p(99.9900) =     18.999 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.620          ops/ms
ClientSimple.existUser                       thrpt         13.305          ops/ms
ClientSimple.getUser                         thrpt         14.223          ops/ms
ClientSimple.listUser                        thrpt          8.660          ops/ms
ClientSimple.createUser                       avgt          2.519           ms/op
ClientSimple.existUser                        avgt          2.074           ms/op
ClientSimple.getUser                          avgt          2.172           ms/op
ClientSimple.listUser                         avgt          3.358           ms/op
ClientSimple.createUser                     sample  13730   2.329 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.522           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.224           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.047           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.143           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.094           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.241           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.351           ms/op
ClientSimple.existUser                      sample  14461   2.210 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.567           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.081           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.646           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.884           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.718           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.561           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.870           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.396           ms/op
ClientSimple.getUser                        sample  16842   1.926 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.349           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.808           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.335           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.345           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.418           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.825           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.926           ms/op
ClientSimple.listUser                       sample  10376   3.111 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.200           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.863           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.032           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.160           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.722           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.999           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.005           ms/op

Benchmark result is saved to 1714845884619.json
