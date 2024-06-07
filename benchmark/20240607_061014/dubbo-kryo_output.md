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
# Warmup Iteration   1: 1.337 ops/ms
Iteration   1: 5.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.450 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.749 ops/ms
Iteration   1: 10.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.907 ops/ms


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
# Warmup Iteration   1: 4.206 ops/ms
Iteration   1: 9.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.460 ops/ms


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
# Warmup Iteration   1: 3.699 ops/ms
Iteration   1: 8.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.142 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.343 ±(99.9%) 0.109 ms/op
Iteration   1: 2.489 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.489 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ±(99.9%) 0.086 ms/op
Iteration   1: 2.126 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.126 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.663 ±(99.9%) 0.079 ms/op
Iteration   1: 2.204 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.204 ms/op


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
# Warmup Iteration   1: 4.860 ±(99.9%) 0.093 ms/op
Iteration   1: 3.674 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.674 ms/op


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.132 ms/op
Iteration   1: 2.476 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   2.179 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.387 ms/op
                 createUser·p0.99:   13.238 ms/op
                 createUser·p0.999:  16.533 ms/op
                 createUser·p0.9999: 17.701 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12990
  mean =      2.476 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 9376 
    [ 2.500,  3.750) = 3014 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 85 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.179 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.387 ms/op
     p(99.0000) =     13.238 ms/op
     p(99.9000) =     16.533 ms/op
     p(99.9900) =     17.701 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.085 ms/op
Iteration   1: 2.156 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   2.054 ms/op
                 existUser·p0.90:   2.875 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  12.239 ms/op
                 existUser·p0.9999: 12.304 ms/op
                 existUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14895
  mean =      2.156 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 239 
    [ 1.250,  2.500) = 11424 
    [ 2.500,  3.750) = 3088 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =     12.239 ms/op
     p(99.9900) =     12.304 ms/op
     p(99.9990) =     12.304 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.098 ms/op
Iteration   1: 2.071 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.534 ms/op
                 getUser·p0.50:   1.944 ms/op
                 getUser·p0.90:   2.400 ms/op
                 getUser·p0.95:   2.671 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  14.762 ms/op
                 getUser·p0.9999: 14.924 ms/op
                 getUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15419
  mean =      2.071 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 14132 
    [ 2.500,  3.750) = 965 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     14.924 ms/op
     p(99.9990) =     14.942 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 4.990 ±(99.9%) 0.138 ms/op
Iteration   1: 3.819 ±(99.9%) 0.073 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   15.614 ms/op
                 listUser·p0.999:  20.047 ms/op
                 listUser·p0.9999: 23.658 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8367
  mean =      3.819 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 748 
    [ 2.500,  5.000) = 7001 
    [ 5.000,  7.500) = 413 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =     15.614 ms/op
     p(99.9000) =     20.047 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.450          ops/ms
ClientSimple.existUser                       thrpt         10.907          ops/ms
ClientSimple.getUser                         thrpt          9.460          ops/ms
ClientSimple.listUser                        thrpt          8.142          ops/ms
ClientSimple.createUser                       avgt          2.489           ms/op
ClientSimple.existUser                        avgt          2.126           ms/op
ClientSimple.getUser                          avgt          2.204           ms/op
ClientSimple.listUser                         avgt          3.674           ms/op
ClientSimple.createUser                     sample  12990   2.476 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.804           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.179           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.011           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.387           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.238           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.533           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.701           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.760           ms/op
ClientSimple.existUser                      sample  14895   2.156 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.601           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.054           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.875           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.178           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.736           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.239           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.304           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.304           ms/op
ClientSimple.getUser                        sample  15419   2.071 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.534           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.944           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.358           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.762           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.924           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.942           ms/op
ClientSimple.listUser                       sample   8367   3.819 ± 0.073   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.877           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.486           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.792           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.702           ms/op
ClientSimple.listUser:listUser·p0.99        sample         15.614           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.047           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.658           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.658           ms/op

Benchmark result is saved to 1717740364321.json
