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
# Warmup Iteration   1: 1.832 ops/ms
Iteration   1: 7.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.406 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.692 ops/ms
Iteration   1: 13.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.394 ops/ms


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
# Warmup Iteration   1: 5.570 ops/ms
Iteration   1: 12.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.211 ops/ms


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
# Warmup Iteration   1: 5.564 ops/ms
Iteration   1: 8.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.813 ops/ms


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
# Warmup Iteration   1: 4.139 ±(99.9%) 0.073 ms/op
Iteration   1: 2.289 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.289 ms/op


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
# Warmup Iteration   1: 3.529 ±(99.9%) 0.062 ms/op
Iteration   1: 1.947 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.947 ms/op


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
# Warmup Iteration   1: 3.387 ±(99.9%) 0.073 ms/op
Iteration   1: 2.054 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.054 ms/op


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
# Warmup Iteration   1: 5.354 ±(99.9%) 0.137 ms/op
Iteration   1: 3.560 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.560 ms/op


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
# Warmup Iteration   1: 3.785 ±(99.9%) 0.126 ms/op
Iteration   1: 2.434 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   2.310 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.326 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  12.694 ms/op
                 createUser·p0.9999: 12.994 ms/op
                 createUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13200
  mean =      2.434 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 8208 
    [ 2.500,  3.750) = 4565 
    [ 3.750,  5.000) = 178 
    [ 5.000,  6.250) = 121 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      2.310 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.326 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     12.694 ms/op
     p(99.9900) =     12.994 ms/op
     p(99.9990) =     13.025 ms/op
     p(99.9999) =     13.025 ms/op
    p(100.0000) =     13.025 ms/op


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
# Warmup Iteration   1: 2.984 ±(99.9%) 0.064 ms/op
Iteration   1: 2.215 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.179 ms/op
                 existUser·p0.90:   2.699 ms/op
                 existUser·p0.95:   2.855 ms/op
                 existUser·p0.99:   4.552 ms/op
                 existUser·p0.999:  17.449 ms/op
                 existUser·p0.9999: 19.387 ms/op
                 existUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14506
  mean =      2.215 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 562 
    [ 1.250,  2.500) = 10468 
    [ 2.500,  3.750) = 3282 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.179 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      4.552 ms/op
     p(99.9000) =     17.449 ms/op
     p(99.9900) =     19.387 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 3.038 ±(99.9%) 0.081 ms/op
Iteration   1: 2.037 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   1.980 ms/op
                 getUser·p0.90:   2.490 ms/op
                 getUser·p0.95:   2.650 ms/op
                 getUser·p0.99:   4.091 ms/op
                 getUser·p0.999:  11.958 ms/op
                 getUser·p0.9999: 12.400 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15825
  mean =      2.037 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 200 
    [ 1.250,  2.500) = 14094 
    [ 2.500,  3.750) = 1335 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 18 
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
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      4.091 ms/op
     p(99.9000) =     11.958 ms/op
     p(99.9900) =     12.400 ms/op
     p(99.9990) =     12.419 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.119 ms/op
Iteration   1: 3.832 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.050 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  22.512 ms/op
                 listUser·p0.9999: 22.577 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8331
  mean =      3.832 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 629 
    [ 2.500,  5.000) = 7276 
    [ 5.000,  7.500) = 316 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.050 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     22.512 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     22.577 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.406          ops/ms
ClientSimple.existUser                       thrpt         13.394          ops/ms
ClientSimple.getUser                         thrpt         12.211          ops/ms
ClientSimple.listUser                        thrpt          8.813          ops/ms
ClientSimple.createUser                       avgt          2.289           ms/op
ClientSimple.existUser                        avgt          1.947           ms/op
ClientSimple.getUser                          avgt          2.054           ms/op
ClientSimple.listUser                         avgt          3.560           ms/op
ClientSimple.createUser                     sample  13200   2.434 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.575           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.310           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.109           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.326           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.415           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.694           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         12.994           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.025           ms/op
ClientSimple.existUser                      sample  14506   2.215 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.515           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.179           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.699           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.552           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.449           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.387           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.431           ms/op
ClientSimple.getUser                        sample  15825   2.037 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.770           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.980           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.091           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.958           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.400           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.419           ms/op
ClientSimple.listUser                       sample   8331   3.832 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.487           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.781           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.563           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.050           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.963           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.512           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.577           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.577           ms/op

Benchmark result is saved to 1722146727089.json
