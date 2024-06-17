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
# Warmup Iteration   1: 1.443 ops/ms
Iteration   1: 5.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.926 ops/ms


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
# Warmup Iteration   1: 5.423 ops/ms
Iteration   1: 12.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.744 ops/ms


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
# Warmup Iteration   1: 5.498 ops/ms
Iteration   1: 11.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.801 ops/ms


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
# Warmup Iteration   1: 4.575 ops/ms
Iteration   1: 9.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.143 ops/ms


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.067 ms/op
Iteration   1: 2.142 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.142 ms/op


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
# Warmup Iteration   1: 3.463 ±(99.9%) 0.048 ms/op
Iteration   1: 1.805 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.805 ms/op


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
# Warmup Iteration   1: 3.445 ±(99.9%) 0.065 ms/op
Iteration   1: 2.346 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.346 ms/op


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
# Warmup Iteration   1: 4.697 ±(99.9%) 0.099 ms/op
Iteration   1: 3.333 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.333 ms/op


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
# Warmup Iteration   1: 3.374 ±(99.9%) 0.092 ms/op
Iteration   1: 2.144 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   1.942 ms/op
                 createUser·p0.90:   2.826 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   6.061 ms/op
                 createUser·p0.999:  18.874 ms/op
                 createUser·p0.9999: 19.448 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14905
  mean =      2.144 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 12440 
    [ 2.500,  3.750) = 2104 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      6.061 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     19.448 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 3.513 ±(99.9%) 0.084 ms/op
Iteration   1: 2.027 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   1.925 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  19.172 ms/op
                 existUser·p0.9999: 19.944 ms/op
                 existUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15920
  mean =      2.027 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15018 
    [ 2.500,  5.000) = 836 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =     19.172 ms/op
     p(99.9900) =     19.944 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.120 ms/op
Iteration   1: 1.945 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.479 ms/op
                 getUser·p0.50:   1.855 ms/op
                 getUser·p0.90:   2.474 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   4.449 ms/op
                 getUser·p0.999:  13.992 ms/op
                 getUser·p0.9999: 14.186 ms/op
                 getUser·p1.00:   14.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16492
  mean =      1.945 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 465 
    [ 1.250,  2.500) = 14492 
    [ 2.500,  3.750) = 1339 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.449 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     14.186 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.164 ms/op
Iteration   1: 3.246 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.068 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.995 ms/op
                 listUser·p0.999:  13.047 ms/op
                 listUser·p0.9999: 14.172 ms/op
                 listUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9921
  mean =      3.246 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 1343 
    [ 2.500,  3.750) = 6095 
    [ 3.750,  5.000) = 2213 
    [ 5.000,  6.250) = 184 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.995 ms/op
     p(99.9000) =     13.047 ms/op
     p(99.9900) =     14.172 ms/op
     p(99.9990) =     14.172 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.926          ops/ms
ClientSimple.existUser                       thrpt         12.744          ops/ms
ClientSimple.getUser                         thrpt         11.801          ops/ms
ClientSimple.listUser                        thrpt          9.143          ops/ms
ClientSimple.createUser                       avgt          2.142           ms/op
ClientSimple.existUser                        avgt          1.805           ms/op
ClientSimple.getUser                          avgt          2.346           ms/op
ClientSimple.listUser                         avgt          3.333           ms/op
ClientSimple.createUser                     sample  14905   2.144 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.023           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.942           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.826           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.105           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.061           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.874           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.448           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.464           ms/op
ClientSimple.existUser                      sample  15920   2.027 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.598           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.925           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.785           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.172           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.944           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.021           ms/op
ClientSimple.getUser                        sample  16492   1.945 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.479           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.855           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.474           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.449           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.992           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.186           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.303           ms/op
ClientSimple.listUser                       sample   9921   3.246 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.947           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.068           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.995           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.047           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.172           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.172           ms/op

Benchmark result is saved to 1718604364049.json
