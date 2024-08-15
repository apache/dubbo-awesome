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
# Warmup Iteration   1: 1.648 ops/ms
Iteration   1: 5.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.914 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.778 ops/ms
Iteration   1: 10.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.396 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 5.134 ops/ms
Iteration   1: 11.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.177 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.020 ops/ms
Iteration   1: 7.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.697 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.744 ±(99.9%) 0.101 ms/op
Iteration   1: 2.711 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.711 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.061 ±(99.9%) 0.117 ms/op
Iteration   1: 2.330 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.330 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.600 ±(99.9%) 0.060 ms/op
Iteration   1: 2.204 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.204 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 5.328 ±(99.9%) 0.124 ms/op
Iteration   1: 4.088 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.088 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.320 ±(99.9%) 0.124 ms/op
Iteration   1: 2.538 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   2.273 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.441 ms/op
                 createUser·p0.99:   10.421 ms/op
                 createUser·p0.999:  22.374 ms/op
                 createUser·p0.9999: 24.214 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12596
  mean =      2.538 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7449 
    [ 2.500,  5.000) = 4959 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.273 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.441 ms/op
     p(99.0000) =     10.421 ms/op
     p(99.9000) =     22.374 ms/op
     p(99.9900) =     24.214 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.109 ms/op
Iteration   1: 2.109 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   1.911 ms/op
                 existUser·p0.90:   2.724 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   4.989 ms/op
                 existUser·p0.999:  16.237 ms/op
                 existUser·p0.9999: 17.133 ms/op
                 existUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15148
  mean =      2.109 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 12567 
    [ 2.500,  3.750) = 2224 
    [ 3.750,  5.000) = 185 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      4.989 ms/op
     p(99.9000) =     16.237 ms/op
     p(99.9900) =     17.133 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.124 ms/op
Iteration   1: 2.364 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.261 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.364 ms/op
                 getUser·p0.99:   5.063 ms/op
                 getUser·p0.999:  16.989 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13534
  mean =      2.364 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 8889 
    [ 2.500,  3.750) = 4209 
    [ 3.750,  5.000) = 225 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.261 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.364 ms/op
     p(99.0000) =      5.063 ms/op
     p(99.9000) =     16.989 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 5.038 ±(99.9%) 0.164 ms/op
Iteration   1: 3.879 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   7.852 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8244
  mean =      3.879 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 57 
    [ 2.500,  3.750) = 4087 
    [ 3.750,  5.000) = 3518 
    [ 5.000,  6.250) = 364 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      7.852 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.914          ops/ms
ClientSimple.existUser                       thrpt         10.396          ops/ms
ClientSimple.getUser                         thrpt         11.177          ops/ms
ClientSimple.listUser                        thrpt          7.697          ops/ms
ClientSimple.createUser                       avgt          2.711           ms/op
ClientSimple.existUser                        avgt          2.330           ms/op
ClientSimple.getUser                          avgt          2.204           ms/op
ClientSimple.listUser                         avgt          4.088           ms/op
ClientSimple.createUser                     sample  12596   2.538 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.635           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.273           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.105           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.441           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.421           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.374           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.214           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.248           ms/op
ClientSimple.existUser                      sample  15148   2.109 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.667           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.911           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.724           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.113           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.989           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.237           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.133           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.302           ms/op
ClientSimple.getUser                        sample  13534   2.364 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.916           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.261           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.364           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.063           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.989           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.400           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.400           ms/op
ClientSimple.listUser                       sample   8244   3.879 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.456           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.744           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.852           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.974           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.859           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.859           ms/op

Benchmark result is saved to 1723681004694.json
