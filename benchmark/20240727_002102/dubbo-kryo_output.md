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
# Warmup Iteration   1: 1.829 ops/ms
Iteration   1: 8.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.087 ops/ms


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
# Warmup Iteration   1: 5.560 ops/ms
Iteration   1: 12.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.315 ops/ms


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
# Warmup Iteration   1: 5.701 ops/ms
Iteration   1: 12.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.706 ops/ms


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
# Warmup Iteration   1: 4.048 ops/ms
Iteration   1: 8.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.688 ops/ms


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.068 ms/op
Iteration   1: 2.226 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.226 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.046 ms/op
Iteration   1: 1.717 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.717 ms/op


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
# Warmup Iteration   1: 3.119 ±(99.9%) 0.049 ms/op
Iteration   1: 1.884 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.884 ms/op


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
# Warmup Iteration   1: 4.520 ±(99.9%) 0.086 ms/op
Iteration   1: 3.216 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.216 ms/op


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
# Warmup Iteration   1: 3.294 ±(99.9%) 0.085 ms/op
Iteration   1: 2.146 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.378 ms/op
                 createUser·p0.50:   1.939 ms/op
                 createUser·p0.90:   2.699 ms/op
                 createUser·p0.95:   2.925 ms/op
                 createUser·p0.99:   4.074 ms/op
                 createUser·p0.999:  30.981 ms/op
                 createUser·p0.9999: 32.579 ms/op
                 createUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14908
  mean =      2.146 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12191 
    [ 2.500,  5.000) = 2582 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      4.074 ms/op
     p(99.9000) =     30.981 ms/op
     p(99.9900) =     32.579 ms/op
     p(99.9990) =     32.997 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 3.057 ±(99.9%) 0.063 ms/op
Iteration   1: 1.869 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.347 ms/op
                 existUser·p0.50:   1.731 ms/op
                 existUser·p0.90:   2.216 ms/op
                 existUser·p0.95:   2.351 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  16.237 ms/op
                 existUser·p0.9999: 17.245 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17105
  mean =      1.869 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 292 
    [ 1.250,  2.500) = 16322 
    [ 2.500,  3.750) = 322 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      3.564 ms/op
     p(99.9000) =     16.237 ms/op
     p(99.9900) =     17.245 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 3.210 ±(99.9%) 0.075 ms/op
Iteration   1: 1.848 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   1.745 ms/op
                 getUser·p0.90:   2.216 ms/op
                 getUser·p0.95:   2.400 ms/op
                 getUser·p0.99:   3.555 ms/op
                 getUser·p0.999:  18.840 ms/op
                 getUser·p0.9999: 19.458 ms/op
                 getUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17345
  mean =      1.848 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 272 
    [ 1.250,  2.500) = 16514 
    [ 2.500,  3.750) = 418 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.400 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =     18.840 ms/op
     p(99.9900) =     19.458 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 5.222 ±(99.9%) 0.160 ms/op
Iteration   1: 3.384 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   3.203 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  14.820 ms/op
                 listUser·p0.9999: 15.303 ms/op
                 listUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9443
  mean =      3.384 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 904 
    [ 2.500,  3.750) = 6202 
    [ 3.750,  5.000) = 2003 
    [ 5.000,  6.250) = 154 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     14.820 ms/op
     p(99.9900) =     15.303 ms/op
     p(99.9990) =     15.303 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.087          ops/ms
ClientSimple.existUser                       thrpt         12.315          ops/ms
ClientSimple.getUser                         thrpt         12.706          ops/ms
ClientSimple.listUser                        thrpt          8.688          ops/ms
ClientSimple.createUser                       avgt          2.226           ms/op
ClientSimple.existUser                        avgt          1.717           ms/op
ClientSimple.getUser                          avgt          1.884           ms/op
ClientSimple.listUser                         avgt          3.216           ms/op
ClientSimple.createUser                     sample  14908   2.146 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.378           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.939           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.925           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.074           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.981           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.579           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.997           ms/op
ClientSimple.existUser                      sample  17105   1.869 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.347           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.731           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.216           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.351           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.564           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.237           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.245           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.269           ms/op
ClientSimple.getUser                        sample  17345   1.848 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.535           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.745           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.216           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.555           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.840           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.458           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.530           ms/op
ClientSimple.listUser                       sample   9443   3.384 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.902           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.203           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.749           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.820           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.303           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.303           ms/op

Benchmark result is saved to 1722039376178.json
