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
# Warmup Iteration   1: 1.520 ops/ms
Iteration   1: 5.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.008 ops/ms


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
# Warmup Iteration   1: 5.184 ops/ms
Iteration   1: 11.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.154 ops/ms


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
# Warmup Iteration   1: 4.538 ops/ms
Iteration   1: 12.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.407 ops/ms


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
# Warmup Iteration   1: 5.288 ops/ms
Iteration   1: 8.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.569 ops/ms


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.095 ms/op
Iteration   1: 2.185 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.185 ms/op


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
# Warmup Iteration   1: 3.217 ±(99.9%) 0.053 ms/op
Iteration   1: 1.937 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.937 ms/op


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
# Warmup Iteration   1: 3.439 ±(99.9%) 0.059 ms/op
Iteration   1: 2.166 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.166 ms/op


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.088 ms/op
Iteration   1: 3.762 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.762 ms/op


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
# Warmup Iteration   1: 3.562 ±(99.9%) 0.080 ms/op
Iteration   1: 2.303 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.474 ms/op
                 createUser·p0.50:   2.017 ms/op
                 createUser·p0.90:   2.839 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   10.075 ms/op
                 createUser·p0.999:  17.727 ms/op
                 createUser·p0.9999: 21.955 ms/op
                 createUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14007
  mean =      2.303 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10675 
    [ 2.500,  5.000) = 3061 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =     10.075 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     21.955 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 2.945 ±(99.9%) 0.076 ms/op
Iteration   1: 2.035 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   1.958 ms/op
                 existUser·p0.90:   2.613 ms/op
                 existUser·p0.95:   2.843 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  10.254 ms/op
                 existUser·p0.9999: 11.094 ms/op
                 existUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15712
  mean =      2.035 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 642 
    [ 1.250,  2.500) = 12919 
    [ 2.500,  3.750) = 2004 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =     10.254 ms/op
     p(99.9900) =     11.094 ms/op
     p(99.9990) =     11.534 ms/op
     p(99.9999) =     11.534 ms/op
    p(100.0000) =     11.534 ms/op


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
# Warmup Iteration   1: 3.160 ±(99.9%) 0.086 ms/op
Iteration   1: 2.112 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.486 ms/op
                 getUser·p0.50:   1.974 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   3.024 ms/op
                 getUser·p0.99:   4.912 ms/op
                 getUser·p0.999:  18.252 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15233
  mean =      2.112 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 282 
    [ 1.250,  2.500) = 11945 
    [ 2.500,  3.750) = 2745 
    [ 3.750,  5.000) = 120 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      3.024 ms/op
     p(99.0000) =      4.912 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.119 ms/op
Iteration   1: 3.556 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   3.445 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   6.384 ms/op
                 listUser·p0.999:  10.585 ms/op
                 listUser·p0.9999: 11.043 ms/op
                 listUser·p1.00:   11.043 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8994
  mean =      3.556 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 360 
    [ 2.500,  3.750) = 5273 
    [ 3.750,  5.000) = 2812 
    [ 5.000,  6.250) = 439 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      6.384 ms/op
     p(99.9000) =     10.585 ms/op
     p(99.9900) =     11.043 ms/op
     p(99.9990) =     11.043 ms/op
     p(99.9999) =     11.043 ms/op
    p(100.0000) =     11.043 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.008          ops/ms
ClientSimple.existUser                       thrpt         11.154          ops/ms
ClientSimple.getUser                         thrpt         12.407          ops/ms
ClientSimple.listUser                        thrpt          8.569          ops/ms
ClientSimple.createUser                       avgt          2.185           ms/op
ClientSimple.existUser                        avgt          1.937           ms/op
ClientSimple.getUser                          avgt          2.166           ms/op
ClientSimple.listUser                         avgt          3.762           ms/op
ClientSimple.createUser                     sample  14007   2.303 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.474           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.017           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.219           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.075           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.727           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.955           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.955           ms/op
ClientSimple.existUser                      sample  15712   2.035 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.562           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.958           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.613           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.843           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.629           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.254           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.094           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.534           ms/op
ClientSimple.getUser                        sample  15233   2.112 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.486           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.974           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.024           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.912           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.252           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.235           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.235           ms/op
ClientSimple.listUser                       sample   8994   3.556 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.821           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.445           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.177           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.384           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.585           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.043           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.043           ms/op

Benchmark result is saved to 1725516372473.json
