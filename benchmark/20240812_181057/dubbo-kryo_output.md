# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.594 ops/ms
Iteration   1: 7.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.617 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.858 ops/ms
Iteration   1: 12.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.288 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.263 ops/ms
Iteration   1: 11.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.218 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.508 ops/ms
Iteration   1: 8.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.360 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.930 ±(99.9%) 0.083 ms/op
Iteration   1: 2.325 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.325 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.351 ±(99.9%) 0.049 ms/op
Iteration   1: 1.970 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.970 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.272 ±(99.9%) 0.053 ms/op
Iteration   1: 2.057 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.057 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.351 ±(99.9%) 0.088 ms/op
Iteration   1: 3.333 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.333 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ±(99.9%) 0.110 ms/op
Iteration   1: 2.097 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   1.929 ms/op
                 createUser·p0.90:   2.511 ms/op
                 createUser·p0.95:   2.728 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  15.315 ms/op
                 createUser·p0.9999: 15.923 ms/op
                 createUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15247
  mean =      2.097 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 13527 
    [ 2.500,  3.750) = 1264 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     15.315 ms/op
     p(99.9900) =     15.923 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.133 ±(99.9%) 0.065 ms/op
Iteration   1: 2.143 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.030 ms/op
                 existUser·p0.90:   2.662 ms/op
                 existUser·p0.95:   2.892 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  19.562 ms/op
                 existUser·p0.9999: 19.628 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15169
  mean =      2.143 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 420 
    [ 1.250,  2.500) = 12299 
    [ 2.500,  3.750) = 2238 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.435 ±(99.9%) 0.092 ms/op
Iteration   1: 2.061 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   1.970 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  13.943 ms/op
                 getUser·p0.9999: 14.343 ms/op
                 getUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15507
  mean =      2.061 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 219 
    [ 1.250,  2.500) = 13315 
    [ 2.500,  3.750) = 1859 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     14.343 ms/op
     p(99.9990) =     14.352 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.797 ±(99.9%) 0.161 ms/op
Iteration   1: 3.481 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.363 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.761 ms/op
                 listUser·p0.99:   11.109 ms/op
                 listUser·p0.999:  21.424 ms/op
                 listUser·p0.9999: 22.086 ms/op
                 listUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9195
  mean =      3.481 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1034 
    [ 2.500,  5.000) = 7830 
    [ 5.000,  7.500) = 235 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.761 ms/op
     p(99.0000) =     11.109 ms/op
     p(99.9000) =     21.424 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.617          ops/ms
ClientSimple.existUser                       thrpt         12.288          ops/ms
ClientSimple.getUser                         thrpt         11.218          ops/ms
ClientSimple.listUser                        thrpt          8.360          ops/ms
ClientSimple.createUser                       avgt          2.325           ms/op
ClientSimple.existUser                        avgt          1.970           ms/op
ClientSimple.getUser                          avgt          2.057           ms/op
ClientSimple.listUser                         avgt          3.333           ms/op
ClientSimple.createUser                     sample  15247   2.097 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.667           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.929           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.511           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.939           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.315           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.923           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.974           ms/op
ClientSimple.existUser                      sample  15169   2.143 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.735           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.030           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.892           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.473           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.562           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.628           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.628           ms/op
ClientSimple.getUser                        sample  15507   2.061 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.799           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.970           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.621           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.943           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.343           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.352           ms/op
ClientSimple.listUser                       sample   9195   3.481 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.227           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.363           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.761           ms/op
ClientSimple.listUser:listUser·p0.99        sample         11.109           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.424           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.086           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.086           ms/op

Benchmark result is saved to 1723485988526.json
