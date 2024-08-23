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
# Warmup Iteration   1: 1.622 ops/ms
Iteration   1: 6.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.748 ops/ms


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
# Warmup Iteration   1: 6.301 ops/ms
Iteration   1: 11.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.230 ops/ms


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
# Warmup Iteration   1: 5.069 ops/ms
Iteration   1: 14.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.237 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.697 ops/ms
Iteration   1: 8.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.247 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.641 ±(99.9%) 0.080 ms/op
Iteration   1: 2.333 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.333 ms/op


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.069 ms/op
Iteration   1: 1.911 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.911 ms/op


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
# Warmup Iteration   1: 3.573 ±(99.9%) 0.075 ms/op
Iteration   1: 2.179 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.179 ms/op


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
# Warmup Iteration   1: 4.565 ±(99.9%) 0.093 ms/op
Iteration   1: 3.937 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.937 ms/op


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.101 ms/op
Iteration   1: 2.440 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.459 ms/op
                 createUser·p0.50:   2.228 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   8.897 ms/op
                 createUser·p0.999:  15.319 ms/op
                 createUser·p0.9999: 15.981 ms/op
                 createUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13211
  mean =      2.440 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 216 
    [ 1.250,  2.500) = 9367 
    [ 2.500,  3.750) = 3061 
    [ 3.750,  5.000) = 214 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      2.228 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     15.981 ms/op
     p(99.9990) =     16.007 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 3.471 ±(99.9%) 0.083 ms/op
Iteration   1: 2.281 ±(99.9%) 0.080 ms/op
                 existUser·p0.00:   0.425 ms/op
                 existUser·p0.50:   2.030 ms/op
                 existUser·p0.90:   2.621 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  58.786 ms/op
                 existUser·p0.9999: 61.037 ms/op
                 existUser·p1.00:   61.407 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14030
  mean =      2.281 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13891 
    [ 5.000, 10.000) = 39 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 33 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 21 
    [60.000, 65.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      4.973 ms/op
     p(99.9000) =     58.786 ms/op
     p(99.9900) =     61.037 ms/op
     p(99.9990) =     61.407 ms/op
     p(99.9999) =     61.407 ms/op
    p(100.0000) =     61.407 ms/op


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
# Warmup Iteration   1: 3.538 ±(99.9%) 0.084 ms/op
Iteration   1: 2.207 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   2.105 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  17.826 ms/op
                 getUser·p0.9999: 18.335 ms/op
                 getUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14612
  mean =      2.207 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 164 
    [ 1.250,  2.500) = 12161 
    [ 2.500,  3.750) = 1937 
    [ 3.750,  5.000) = 223 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     18.335 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 4.758 ±(99.9%) 0.151 ms/op
Iteration   1: 3.662 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.764 ms/op
                 listUser·p0.999:  20.063 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8725
  mean =      3.662 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 429 
    [ 2.500,  5.000) = 8026 
    [ 5.000,  7.500) = 215 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.764 ms/op
     p(99.9000) =     20.063 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.748          ops/ms
ClientSimple.existUser                       thrpt         11.230          ops/ms
ClientSimple.getUser                         thrpt         14.237          ops/ms
ClientSimple.listUser                        thrpt          8.247          ops/ms
ClientSimple.createUser                       avgt          2.333           ms/op
ClientSimple.existUser                        avgt          1.911           ms/op
ClientSimple.getUser                          avgt          2.179           ms/op
ClientSimple.listUser                         avgt          3.937           ms/op
ClientSimple.createUser                     sample  13211   2.440 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.459           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.228           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.027           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.551           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.897           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.319           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.981           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.007           ms/op
ClientSimple.existUser                      sample  14030   2.281 ± 0.080   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.425           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.030           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.990           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.973           ms/op
ClientSimple.existUser:existUser·p0.999     sample         58.786           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         61.037           ms/op
ClientSimple.existUser:existUser·p1.00      sample         61.407           ms/op
ClientSimple.getUser                        sample  14612   2.207 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.624           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.105           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.133           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.727           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.826           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.335           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.350           ms/op
ClientSimple.listUser                       sample   8725   3.662 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.421           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.625           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.764           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.063           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.185           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.185           ms/op

Benchmark result is saved to 1724393165415.json
