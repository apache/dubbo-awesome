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
# Warmup Iteration   1: 1.479 ops/ms
Iteration   1: 7.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.107 ops/ms


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
# Warmup Iteration   1: 6.088 ops/ms
Iteration   1: 12.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.336 ops/ms


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
# Warmup Iteration   1: 5.402 ops/ms
Iteration   1: 12.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.054 ops/ms


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
# Warmup Iteration   1: 5.538 ops/ms
Iteration   1: 8.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.719 ops/ms


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
# Warmup Iteration   1: 3.845 ±(99.9%) 0.074 ms/op
Iteration   1: 2.175 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.175 ms/op


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
# Warmup Iteration   1: 3.084 ±(99.9%) 0.049 ms/op
Iteration   1: 2.038 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.038 ms/op


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.091 ms/op
Iteration   1: 2.065 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.065 ms/op


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
# Warmup Iteration   1: 4.601 ±(99.9%) 0.089 ms/op
Iteration   1: 3.373 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.373 ms/op


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.097 ms/op
Iteration   1: 2.334 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.452 ms/op
                 createUser·p0.50:   2.146 ms/op
                 createUser·p0.90:   2.871 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   5.181 ms/op
                 createUser·p0.999:  30.616 ms/op
                 createUser·p0.9999: 31.123 ms/op
                 createUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13688
  mean =      2.334 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10153 
    [ 2.500,  5.000) = 3396 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.452 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      5.181 ms/op
     p(99.9000) =     30.616 ms/op
     p(99.9900) =     31.123 ms/op
     p(99.9990) =     31.195 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 2.999 ±(99.9%) 0.067 ms/op
Iteration   1: 1.917 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.377 ms/op
                 existUser·p0.50:   1.808 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.506 ms/op
                 existUser·p0.99:   3.006 ms/op
                 existUser·p0.999:  16.454 ms/op
                 existUser·p0.9999: 18.491 ms/op
                 existUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16704
  mean =      1.917 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 350 
    [ 1.250,  2.500) = 15502 
    [ 2.500,  3.750) = 737 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.506 ms/op
     p(99.0000) =      3.006 ms/op
     p(99.9000) =     16.454 ms/op
     p(99.9900) =     18.491 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.080 ms/op
Iteration   1: 1.974 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.455 ms/op
                 getUser·p0.50:   1.819 ms/op
                 getUser·p0.90:   2.384 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  19.294 ms/op
                 getUser·p0.9999: 20.867 ms/op
                 getUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16199
  mean =      1.974 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15152 
    [ 2.500,  5.000) = 932 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.994 ms/op
     p(99.9000) =     19.294 ms/op
     p(99.9900) =     20.867 ms/op
     p(99.9990) =     21.070 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 4.298 ±(99.9%) 0.126 ms/op
Iteration   1: 3.196 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.203 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.145 ms/op
                 listUser·p0.99:   5.308 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10005
  mean =      3.196 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1954 
    [ 2.500,  3.750) = 6379 
    [ 3.750,  5.000) = 1515 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.107          ops/ms
ClientSimple.existUser                       thrpt         12.336          ops/ms
ClientSimple.getUser                         thrpt         12.054          ops/ms
ClientSimple.listUser                        thrpt          8.719          ops/ms
ClientSimple.createUser                       avgt          2.175           ms/op
ClientSimple.existUser                        avgt          2.038           ms/op
ClientSimple.getUser                          avgt          2.065           ms/op
ClientSimple.listUser                         avgt          3.373           ms/op
ClientSimple.createUser                     sample  13688   2.334 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.452           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.146           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.260           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.181           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.616           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.123           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.195           ms/op
ClientSimple.existUser                      sample  16704   1.917 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.377           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.808           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.506           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.006           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.454           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.491           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.711           ms/op
ClientSimple.getUser                        sample  16199   1.974 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.455           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.819           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.384           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.994           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.294           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.867           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.070           ms/op
ClientSimple.listUser                       sample  10005   3.196 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.253           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.203           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.928           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.145           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.308           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.007           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.039           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.039           ms/op

Benchmark result is saved to 1714586692774.json
