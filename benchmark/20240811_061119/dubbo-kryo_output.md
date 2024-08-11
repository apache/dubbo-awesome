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
# Warmup Iteration   1: 2.012 ops/ms
Iteration   1: 7.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.151 ops/ms


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
# Warmup Iteration   1: 5.878 ops/ms
Iteration   1: 10.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.737 ops/ms


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
# Warmup Iteration   1: 4.020 ops/ms
Iteration   1: 11.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.675 ops/ms


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
# Warmup Iteration   1: 4.963 ops/ms
Iteration   1: 8.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.466 ops/ms


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
# Warmup Iteration   1: 4.098 ±(99.9%) 0.086 ms/op
Iteration   1: 2.239 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.239 ms/op


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
# Warmup Iteration   1: 3.151 ±(99.9%) 0.061 ms/op
Iteration   1: 1.810 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.810 ms/op


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
# Warmup Iteration   1: 3.308 ±(99.9%) 0.056 ms/op
Iteration   1: 2.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.027 ms/op


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.104 ms/op
Iteration   1: 3.244 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.244 ms/op


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
# Warmup Iteration   1: 3.715 ±(99.9%) 0.111 ms/op
Iteration   1: 2.152 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   1.980 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.994 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  26.706 ms/op
                 createUser·p0.9999: 27.975 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14844
  mean =      2.152 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12977 
    [ 2.500,  5.000) = 1646 
    [ 5.000,  7.500) = 124 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     26.706 ms/op
     p(99.9900) =     27.975 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 3.273 ±(99.9%) 0.088 ms/op
Iteration   1: 2.113 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.354 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   3.066 ms/op
                 existUser·p0.99:   7.330 ms/op
                 existUser·p0.999:  17.363 ms/op
                 existUser·p0.9999: 18.087 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15126
  mean =      2.113 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 403 
    [ 1.250,  2.500) = 12684 
    [ 2.500,  3.750) = 1576 
    [ 3.750,  5.000) = 240 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      3.066 ms/op
     p(99.0000) =      7.330 ms/op
     p(99.9000) =     17.363 ms/op
     p(99.9900) =     18.087 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.082 ms/op
Iteration   1: 2.163 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.118 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.757 ms/op
                 getUser·p0.99:   3.262 ms/op
                 getUser·p0.999:  11.964 ms/op
                 getUser·p0.9999: 12.845 ms/op
                 getUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14778
  mean =      2.163 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 12241 
    [ 2.500,  3.750) = 2305 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.262 ms/op
     p(99.9000) =     11.964 ms/op
     p(99.9900) =     12.845 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


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
# Warmup Iteration   1: 4.617 ±(99.9%) 0.145 ms/op
Iteration   1: 3.290 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   3.113 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.532 ms/op
                 listUser·p0.99:   6.198 ms/op
                 listUser·p0.999:  11.354 ms/op
                 listUser·p0.9999: 13.418 ms/op
                 listUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9714
  mean =      3.290 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 865 
    [ 2.500,  3.750) = 6465 
    [ 3.750,  5.000) = 2103 
    [ 5.000,  6.250) = 175 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.532 ms/op
     p(99.0000) =      6.198 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     13.418 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.151          ops/ms
ClientSimple.existUser                       thrpt         10.737          ops/ms
ClientSimple.getUser                         thrpt         11.675          ops/ms
ClientSimple.listUser                        thrpt          8.466          ops/ms
ClientSimple.createUser                       avgt          2.239           ms/op
ClientSimple.existUser                        avgt          1.810           ms/op
ClientSimple.getUser                          avgt          2.027           ms/op
ClientSimple.listUser                         avgt          3.244           ms/op
ClientSimple.createUser                     sample  14844   2.152 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.860           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.980           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.751           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.706           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.975           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.213           ms/op
ClientSimple.existUser                      sample  15126   2.113 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.354           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.066           ms/op
ClientSimple.existUser:existUser·p0.99      sample          7.330           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.363           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.087           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.121           ms/op
ClientSimple.getUser                        sample  14778   2.163 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.891           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.262           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.964           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.845           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.845           ms/op
ClientSimple.listUser                       sample   9714   3.290 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.781           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.113           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.092           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.532           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.198           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.354           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.418           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.418           ms/op

Benchmark result is saved to 1723356404557.json
