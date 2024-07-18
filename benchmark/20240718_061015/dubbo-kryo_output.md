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
# Warmup Iteration   1: 1.947 ops/ms
Iteration   1: 7.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.677 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.842 ops/ms
Iteration   1: 14.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.004 ops/ms


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
# Warmup Iteration   1: 6.056 ops/ms
Iteration   1: 12.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.488 ops/ms


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
# Warmup Iteration   1: 5.704 ops/ms
Iteration   1: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.354 ops/ms


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.087 ms/op
Iteration   1: 1.912 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.912 ms/op


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
# Warmup Iteration   1: 3.095 ±(99.9%) 0.050 ms/op
Iteration   1: 2.164 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.164 ms/op


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
# Warmup Iteration   1: 3.467 ±(99.9%) 0.062 ms/op
Iteration   1: 1.992 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.992 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.714 ±(99.9%) 0.091 ms/op
Iteration   1: 3.619 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.619 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.079 ms/op
Iteration   1: 2.245 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.901 ms/op
                 createUser·p0.99:   5.701 ms/op
                 createUser·p0.999:  19.293 ms/op
                 createUser·p0.9999: 21.774 ms/op
                 createUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14234
  mean =      2.245 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12514 
    [ 2.500,  5.000) = 1533 
    [ 5.000,  7.500) = 107 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.901 ms/op
     p(99.0000) =      5.701 ms/op
     p(99.9000) =     19.293 ms/op
     p(99.9900) =     21.774 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 2.963 ±(99.9%) 0.077 ms/op
Iteration   1: 1.799 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   1.645 ms/op
                 existUser·p0.90:   2.095 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   4.300 ms/op
                 existUser·p0.999:  17.007 ms/op
                 existUser·p0.9999: 17.196 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17770
  mean =      1.799 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 17070 
    [ 2.500,  3.750) = 329 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      1.645 ms/op
     p(90.0000) =      2.095 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      4.300 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     17.196 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.080 ms/op
Iteration   1: 2.093 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   2.025 ms/op
                 getUser·p0.90:   2.528 ms/op
                 getUser·p0.95:   2.740 ms/op
                 getUser·p0.99:   3.248 ms/op
                 getUser·p0.999:  13.435 ms/op
                 getUser·p0.9999: 13.697 ms/op
                 getUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15268
  mean =      2.093 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 13475 
    [ 2.500,  3.750) = 1634 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.528 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.248 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     13.697 ms/op
     p(99.9990) =     13.697 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


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
# Warmup Iteration   1: 4.679 ±(99.9%) 0.207 ms/op
Iteration   1: 3.618 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   5.632 ms/op
                 listUser·p0.999:  7.142 ms/op
                 listUser·p0.9999: 9.388 ms/op
                 listUser·p1.00:   9.388 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8850
  mean =      3.618 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 15 
    [ 1.500,  2.000) = 105 
    [ 2.000,  2.500) = 489 
    [ 2.500,  3.000) = 910 
    [ 3.000,  3.500) = 1928 
    [ 3.500,  4.000) = 3362 
    [ 4.000,  4.500) = 1230 
    [ 4.500,  5.000) = 429 
    [ 5.000,  5.500) = 268 
    [ 5.500,  6.000) = 60 
    [ 6.000,  6.500) = 42 
    [ 6.500,  7.000) = 3 
    [ 7.000,  7.500) = 2 
    [ 7.500,  8.000) = 4 
    [ 8.000,  8.500) = 2 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      5.632 ms/op
     p(99.9000) =      7.142 ms/op
     p(99.9900) =      9.388 ms/op
     p(99.9990) =      9.388 ms/op
     p(99.9999) =      9.388 ms/op
    p(100.0000) =      9.388 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.677          ops/ms
ClientSimple.existUser                       thrpt         14.004          ops/ms
ClientSimple.getUser                         thrpt         12.488          ops/ms
ClientSimple.listUser                        thrpt          8.354          ops/ms
ClientSimple.createUser                       avgt          1.912           ms/op
ClientSimple.existUser                        avgt          2.164           ms/op
ClientSimple.getUser                          avgt          1.992           ms/op
ClientSimple.listUser                         avgt          3.619           ms/op
ClientSimple.createUser                     sample  14234   2.245 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.773           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.901           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.701           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.293           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.774           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.315           ms/op
ClientSimple.existUser                      sample  17770   1.799 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.763           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.645           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.095           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.300           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.007           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.196           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.400           ms/op
ClientSimple.getUser                        sample  15268   2.093 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.752           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.025           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.528           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.248           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.435           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.697           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.697           ms/op
ClientSimple.listUser                       sample   8850   3.618 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.019           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.637           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.948           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.632           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.142           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.388           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.388           ms/op

Benchmark result is saved to 1721282746621.json
