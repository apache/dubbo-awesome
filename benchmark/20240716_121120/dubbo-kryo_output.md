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
# Warmup Iteration   1: 1.539 ops/ms
Iteration   1: 6.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.744 ops/ms


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
# Warmup Iteration   1: 6.491 ops/ms
Iteration   1: 13.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.268 ops/ms


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
# Warmup Iteration   1: 5.131 ops/ms
Iteration   1: 11.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.988 ops/ms


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
# Warmup Iteration   1: 4.214 ops/ms
Iteration   1: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.581 ops/ms


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
# Warmup Iteration   1: 4.259 ±(99.9%) 0.064 ms/op
Iteration   1: 2.581 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.581 ms/op


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
# Warmup Iteration   1: 3.111 ±(99.9%) 0.048 ms/op
Iteration   1: 1.707 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.707 ms/op


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
# Warmup Iteration   1: 3.330 ±(99.9%) 0.058 ms/op
Iteration   1: 1.881 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.881 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.093 ms/op
Iteration   1: 4.030 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.030 ms/op


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
# Warmup Iteration   1: 3.553 ±(99.9%) 0.084 ms/op
Iteration   1: 2.110 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   1.927 ms/op
                 createUser·p0.90:   2.757 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   5.879 ms/op
                 createUser·p0.999:  12.337 ms/op
                 createUser·p0.9999: 14.721 ms/op
                 createUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15138
  mean =      2.110 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 439 
    [ 1.250,  2.500) = 11778 
    [ 2.500,  3.750) = 2430 
    [ 3.750,  5.000) = 285 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      1.927 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      5.879 ms/op
     p(99.9000) =     12.337 ms/op
     p(99.9900) =     14.721 ms/op
     p(99.9990) =     14.729 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 2.970 ±(99.9%) 0.062 ms/op
Iteration   1: 1.486 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   1.360 ms/op
                 existUser·p0.90:   1.942 ms/op
                 existUser·p0.95:   2.150 ms/op
                 existUser·p0.99:   2.580 ms/op
                 existUser·p0.999:  16.269 ms/op
                 existUser·p0.9999: 16.382 ms/op
                 existUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 21505
  mean =      1.486 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5818 
    [ 1.250,  2.500) = 15417 
    [ 2.500,  3.750) = 200 
    [ 3.750,  5.000) = 0 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.360 ms/op
     p(90.0000) =      1.942 ms/op
     p(95.0000) =      2.150 ms/op
     p(99.0000) =      2.580 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     16.382 ms/op
     p(99.9990) =     16.384 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.085 ms/op
Iteration   1: 2.042 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   1.942 ms/op
                 getUser·p0.90:   2.429 ms/op
                 getUser·p0.95:   2.757 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  14.616 ms/op
                 getUser·p0.9999: 14.805 ms/op
                 getUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15891
  mean =      2.042 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 14430 
    [ 2.500,  3.750) = 1164 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =     14.616 ms/op
     p(99.9900) =     14.805 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.654 ±(99.9%) 0.135 ms/op
Iteration   1: 3.150 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.778 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 9.385 ms/op
                 listUser·p1.00:   9.388 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10203
  mean =      3.150 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 63 
    [ 2.000,  3.000) = 5903 
    [ 3.000,  4.000) = 3055 
    [ 4.000,  5.000) = 975 
    [ 5.000,  6.000) = 69 
    [ 6.000,  7.000) = 38 
    [ 7.000,  8.000) = 8 
    [ 8.000,  9.000) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =      9.385 ms/op
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
ClientSimple.createUser                      thrpt          6.744          ops/ms
ClientSimple.existUser                       thrpt         13.268          ops/ms
ClientSimple.getUser                         thrpt         11.988          ops/ms
ClientSimple.listUser                        thrpt          8.581          ops/ms
ClientSimple.createUser                       avgt          2.581           ms/op
ClientSimple.existUser                        avgt          1.707           ms/op
ClientSimple.getUser                          avgt          1.881           ms/op
ClientSimple.listUser                         avgt          4.030           ms/op
ClientSimple.createUser                     sample  15138   2.110 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.692           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.927           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.203           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.879           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.337           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.721           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.729           ms/op
ClientSimple.existUser                      sample  21505   1.486 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.583           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.360           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.942           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.269           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.382           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.384           ms/op
ClientSimple.getUser                        sample  15891   2.042 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.580           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.942           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.429           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.871           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.616           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.805           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.844           ms/op
ClientSimple.listUser                       sample  10203   3.150 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.778           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.067           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.914           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.126           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.385           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.388           ms/op

Benchmark result is saved to 1721131607202.json
