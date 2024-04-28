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
# Warmup Iteration   1: 2.023 ops/ms
Iteration   1: 6.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.151 ops/ms


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
# Warmup Iteration   1: 5.562 ops/ms
Iteration   1: 13.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.030 ops/ms


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
# Warmup Iteration   1: 4.930 ops/ms
Iteration   1: 12.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.431 ops/ms


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
# Warmup Iteration   1: 4.378 ops/ms
Iteration   1: 7.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.847 ops/ms


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.071 ms/op
Iteration   1: 2.252 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.252 ms/op


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
# Warmup Iteration   1: 2.911 ±(99.9%) 0.056 ms/op
Iteration   1: 1.669 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.669 ms/op


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
# Warmup Iteration   1: 3.143 ±(99.9%) 0.063 ms/op
Iteration   1: 1.839 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.839 ms/op


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
# Warmup Iteration   1: 4.613 ±(99.9%) 0.099 ms/op
Iteration   1: 3.419 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.419 ms/op


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
# Warmup Iteration   1: 3.686 ±(99.9%) 0.114 ms/op
Iteration   1: 2.324 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   2.208 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  21.930 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13759
  mean =      2.324 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9860 
    [ 2.500,  5.000) = 3815 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      2.208 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =     21.930 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 2.722 ±(99.9%) 0.067 ms/op
Iteration   1: 2.162 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   2.118 ms/op
                 existUser·p0.90:   2.732 ms/op
                 existUser·p0.95:   2.925 ms/op
                 existUser·p0.99:   4.171 ms/op
                 existUser·p0.999:  9.355 ms/op
                 existUser·p0.9999: 9.413 ms/op
                 existUser·p1.00:   9.421 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14785
  mean =      2.162 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 44 
    [ 1.000,  2.000) = 6243 
    [ 2.000,  3.000) = 7948 
    [ 3.000,  4.000) = 377 
    [ 4.000,  5.000) = 71 
    [ 5.000,  6.000) = 36 
    [ 6.000,  7.000) = 34 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      4.171 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =      9.413 ms/op
     p(99.9990) =      9.421 ms/op
     p(99.9999) =      9.421 ms/op
    p(100.0000) =      9.421 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.083 ms/op
Iteration   1: 1.969 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.491 ms/op
                 getUser·p0.50:   1.858 ms/op
                 getUser·p0.90:   2.585 ms/op
                 getUser·p0.95:   2.781 ms/op
                 getUser·p0.99:   3.431 ms/op
                 getUser·p0.999:  17.695 ms/op
                 getUser·p0.9999: 18.006 ms/op
                 getUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16247
  mean =      1.969 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 389 
    [ 1.250,  2.500) = 13645 
    [ 2.500,  3.750) = 2092 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.491 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      3.431 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     18.006 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 5.390 ±(99.9%) 0.161 ms/op
Iteration   1: 3.981 ±(99.9%) 0.202 ms/op
                 listUser·p0.00:   0.488 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   15.616 ms/op
                 listUser·p0.999:  87.942 ms/op
                 listUser·p0.9999: 92.013 ms/op
                 listUser·p1.00:   92.013 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8028
  mean =      3.981 ±(99.9%) 0.202 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 7932 
    [ 10.000,  20.000) = 64 
    [ 20.000,  30.000) = 0 
    [ 30.000,  40.000) = 0 
    [ 40.000,  50.000) = 0 
    [ 50.000,  60.000) = 0 
    [ 60.000,  70.000) = 0 
    [ 70.000,  80.000) = 0 
    [ 80.000,  90.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =     15.616 ms/op
     p(99.9000) =     87.942 ms/op
     p(99.9900) =     92.013 ms/op
     p(99.9990) =     92.013 ms/op
     p(99.9999) =     92.013 ms/op
    p(100.0000) =     92.013 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.151          ops/ms
ClientSimple.existUser                       thrpt         13.030          ops/ms
ClientSimple.getUser                         thrpt         12.431          ops/ms
ClientSimple.listUser                        thrpt          7.847          ops/ms
ClientSimple.createUser                       avgt          2.252           ms/op
ClientSimple.existUser                        avgt          1.669           ms/op
ClientSimple.getUser                          avgt          1.839           ms/op
ClientSimple.listUser                         avgt          3.419           ms/op
ClientSimple.createUser                     sample  13759   2.324 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.046           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.208           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.998           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.195           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.125           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.930           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.151           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.151           ms/op
ClientSimple.existUser                      sample  14785   2.162 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.586           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.732           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.925           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.171           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.355           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          9.413           ms/op
ClientSimple.existUser:existUser·p1.00      sample          9.421           ms/op
ClientSimple.getUser                        sample  16247   1.969 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.491           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.858           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.431           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.695           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.006           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.088           ms/op
ClientSimple.listUser                       sample   8028   3.981 ± 0.202   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.488           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.645           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample         15.616           ms/op
ClientSimple.listUser:listUser·p0.999       sample         87.942           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         92.013           ms/op
ClientSimple.listUser:listUser·p1.00        sample         92.013           ms/op

Benchmark result is saved to 1714327491084.json
