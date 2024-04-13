# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.748 ops/ms
Iteration   1: 6.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.551 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.010 ops/ms
Iteration   1: 12.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.128 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.891 ops/ms
Iteration   1: 10.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.587 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 3.339 ops/ms
Iteration   1: 7.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.036 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.452 ±(99.9%) 0.096 ms/op
Iteration   1: 2.245 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.245 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.364 ±(99.9%) 0.057 ms/op
Iteration   1: 2.056 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.056 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.397 ±(99.9%) 0.084 ms/op
Iteration   1: 2.070 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.070 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.233 ±(99.9%) 0.148 ms/op
Iteration   1: 3.989 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.989 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.732 ±(99.9%) 0.099 ms/op
Iteration   1: 2.184 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   8.113 ms/op
                 createUser·p0.999:  24.117 ms/op
                 createUser·p0.9999: 25.138 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14630
  mean =      2.184 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12646 
    [ 2.500,  5.000) = 1727 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      8.113 ms/op
     p(99.9000) =     24.117 ms/op
     p(99.9900) =     25.138 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.218 ±(99.9%) 0.097 ms/op
Iteration   1: 1.931 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   1.794 ms/op
                 existUser·p0.90:   2.478 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  13.812 ms/op
                 existUser·p0.9999: 13.899 ms/op
                 existUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16682
  mean =      1.931 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 643 
    [ 1.250,  2.500) = 14470 
    [ 2.500,  3.750) = 1390 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     13.899 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.530 ±(99.9%) 0.100 ms/op
Iteration   1: 2.350 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   2.224 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.205 ms/op
                 getUser·p0.99:   5.013 ms/op
                 getUser·p0.999:  18.645 ms/op
                 getUser·p0.9999: 19.167 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13611
  mean =      2.350 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 8964 
    [ 2.500,  3.750) = 4102 
    [ 3.750,  5.000) = 253 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.205 ms/op
     p(99.0000) =      5.013 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     19.167 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.746 ±(99.9%) 0.143 ms/op
Iteration   1: 3.666 ±(99.9%) 0.142 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   3.346 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   12.467 ms/op
                 listUser·p0.999:  73.068 ms/op
                 listUser·p0.9999: 81.920 ms/op
                 listUser·p1.00:   81.920 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8805
  mean =      3.666 ±(99.9%) 0.142 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8426 
    [ 5.000, 10.000) = 268 
    [10.000, 15.000) = 40 
    [15.000, 20.000) = 27 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 4 
    [60.000, 65.000) = 5 
    [65.000, 70.000) = 4 
    [70.000, 75.000) = 3 
    [75.000, 80.000) = 6 
    [80.000, 85.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =     12.467 ms/op
     p(99.9000) =     73.068 ms/op
     p(99.9900) =     81.920 ms/op
     p(99.9990) =     81.920 ms/op
     p(99.9999) =     81.920 ms/op
    p(100.0000) =     81.920 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.551          ops/ms
ClientSimple.existUser                       thrpt         12.128          ops/ms
ClientSimple.getUser                         thrpt         10.587          ops/ms
ClientSimple.listUser                        thrpt          7.036          ops/ms
ClientSimple.createUser                       avgt          2.245           ms/op
ClientSimple.existUser                        avgt          2.056           ms/op
ClientSimple.getUser                          avgt          2.070           ms/op
ClientSimple.listUser                         avgt          3.989           ms/op
ClientSimple.createUser                     sample  14630   2.184 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.702           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.170           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.113           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.117           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.138           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.199           ms/op
ClientSimple.existUser                      sample  16682   1.931 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.857           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.794           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.675           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.797           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.812           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.899           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.943           ms/op
ClientSimple.getUser                        sample  13611   2.350 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.746           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.224           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.205           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.013           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.645           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.167           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.333           ms/op
ClientSimple.listUser                       sample   8805   3.666 ± 0.142   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.005           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.346           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample         12.467           ms/op
ClientSimple.listUser:listUser·p0.999       sample         73.068           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         81.920           ms/op
ClientSimple.listUser:listUser·p1.00        sample         81.920           ms/op

Benchmark result is saved to 1712967213046.json
