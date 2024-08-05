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
# Warmup Iteration   1: 1.388 ops/ms
Iteration   1: 5.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.704 ops/ms


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
# Warmup Iteration   1: 6.011 ops/ms
Iteration   1: 12.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.463 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.801 ops/ms
Iteration   1: 12.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.090 ops/ms


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
# Warmup Iteration   1: 4.414 ops/ms
Iteration   1: 8.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.116 ops/ms


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.074 ms/op
Iteration   1: 2.056 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.056 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.052 ms/op
Iteration   1: 1.920 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.920 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.053 ms/op
Iteration   1: 1.948 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.948 ms/op


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
# Warmup Iteration   1: 4.632 ±(99.9%) 0.090 ms/op
Iteration   1: 2.998 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.998 ms/op


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.087 ms/op
Iteration   1: 2.530 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   2.277 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   13.856 ms/op
                 createUser·p0.999:  19.071 ms/op
                 createUser·p0.9999: 19.202 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12629
  mean =      2.530 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 8036 
    [ 2.500,  3.750) = 4165 
    [ 3.750,  5.000) = 177 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =     13.856 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 2.944 ±(99.9%) 0.072 ms/op
Iteration   1: 1.755 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   1.626 ms/op
                 existUser·p0.90:   2.013 ms/op
                 existUser·p0.95:   2.331 ms/op
                 existUser·p0.99:   3.026 ms/op
                 existUser·p0.999:  26.083 ms/op
                 existUser·p0.9999: 26.280 ms/op
                 existUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18233
  mean =      1.755 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17611 
    [ 2.500,  5.000) = 520 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      1.626 ms/op
     p(90.0000) =      2.013 ms/op
     p(95.0000) =      2.331 ms/op
     p(99.0000) =      3.026 ms/op
     p(99.9000) =     26.083 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 3.228 ±(99.9%) 0.083 ms/op
Iteration   1: 1.747 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   1.663 ms/op
                 getUser·p0.90:   2.048 ms/op
                 getUser·p0.95:   2.265 ms/op
                 getUser·p0.99:   2.895 ms/op
                 getUser·p0.999:  11.567 ms/op
                 getUser·p0.9999: 11.751 ms/op
                 getUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18317
  mean =      1.747 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 213 
    [ 1.250,  2.500) = 17710 
    [ 2.500,  3.750) = 298 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      1.663 ms/op
     p(90.0000) =      2.048 ms/op
     p(95.0000) =      2.265 ms/op
     p(99.0000) =      2.895 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     11.751 ms/op
     p(99.9990) =     12.091 ms/op
     p(99.9999) =     12.091 ms/op
    p(100.0000) =     12.091 ms/op


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.145 ms/op
Iteration   1: 3.354 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.579 ms/op
                 listUser·p0.50:   3.293 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 15.172 ms/op
                 listUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9608
  mean =      3.354 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 877 
    [ 2.500,  3.750) = 6711 
    [ 3.750,  5.000) = 1770 
    [ 5.000,  6.250) = 178 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     15.172 ms/op
     p(99.9990) =     15.172 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.704          ops/ms
ClientSimple.existUser                       thrpt         12.463          ops/ms
ClientSimple.getUser                         thrpt         12.090          ops/ms
ClientSimple.listUser                        thrpt          8.116          ops/ms
ClientSimple.createUser                       avgt          2.056           ms/op
ClientSimple.existUser                        avgt          1.920           ms/op
ClientSimple.getUser                          avgt          1.948           ms/op
ClientSimple.listUser                         avgt          2.998           ms/op
ClientSimple.createUser                     sample  12629   2.530 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.993           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.277           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.011           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.228           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.856           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.071           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.202           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.202           ms/op
ClientSimple.existUser                      sample  18233   1.755 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.742           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.626           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.013           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.026           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.083           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.280           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.280           ms/op
ClientSimple.getUser                        sample  18317   1.747 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.580           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.663           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.048           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.265           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.895           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.567           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.751           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.091           ms/op
ClientSimple.listUser                       sample   9608   3.354 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.579           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.293           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.571           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.107           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.172           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.172           ms/op

Benchmark result is saved to 1722859625740.json
