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
# Warmup Iteration   1: 1.715 ops/ms
Iteration   1: 7.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.887 ops/ms


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
# Warmup Iteration   1: 6.967 ops/ms
Iteration   1: 12.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.700 ops/ms


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
# Warmup Iteration   1: 5.942 ops/ms
Iteration   1: 14.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.978 ops/ms


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
# Warmup Iteration   1: 5.550 ops/ms
Iteration   1: 8.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.812 ops/ms


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.068 ms/op
Iteration   1: 2.166 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.166 ms/op


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
# Warmup Iteration   1: 3.056 ±(99.9%) 0.057 ms/op
Iteration   1: 1.677 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.677 ms/op


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
# Warmup Iteration   1: 3.371 ±(99.9%) 0.057 ms/op
Iteration   1: 1.786 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.786 ms/op


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
# Warmup Iteration   1: 4.392 ±(99.9%) 0.078 ms/op
Iteration   1: 3.973 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.973 ms/op


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
# Warmup Iteration   1: 3.542 ±(99.9%) 0.098 ms/op
Iteration   1: 2.233 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.429 ms/op
                 createUser·p0.50:   2.054 ms/op
                 createUser·p0.90:   2.671 ms/op
                 createUser·p0.95:   2.994 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  32.623 ms/op
                 createUser·p0.9999: 34.283 ms/op
                 createUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14427
  mean =      2.233 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11806 
    [ 2.500,  5.000) = 2439 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     32.623 ms/op
     p(99.9900) =     34.283 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 2.945 ±(99.9%) 0.057 ms/op
Iteration   1: 2.051 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   1.935 ms/op
                 existUser·p0.90:   2.576 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   3.920 ms/op
                 existUser·p0.999:  19.431 ms/op
                 existUser·p0.9999: 19.530 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15693
  mean =      2.051 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 221 
    [ 1.250,  2.500) = 13304 
    [ 2.500,  3.750) = 1971 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.087 ms/op
Iteration   1: 2.102 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   2.105 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.800 ms/op
                 getUser·p0.99:   4.210 ms/op
                 getUser·p0.999:  15.401 ms/op
                 getUser·p0.9999: 15.725 ms/op
                 getUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15205
  mean =      2.102 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 454 
    [ 1.250,  2.500) = 12192 
    [ 2.500,  3.750) = 2340 
    [ 3.750,  5.000) = 147 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.800 ms/op
     p(99.0000) =      4.210 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     15.725 ms/op
     p(99.9990) =     15.827 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.324 ms/op
Iteration   1: 3.600 ±(99.9%) 0.065 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  32.117 ms/op
                 listUser·p0.9999: 33.030 ms/op
                 listUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8881
  mean =      3.600 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 489 
    [ 2.500,  5.000) = 8085 
    [ 5.000,  7.500) = 268 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     32.117 ms/op
     p(99.9900) =     33.030 ms/op
     p(99.9990) =     33.030 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.887          ops/ms
ClientSimple.existUser                       thrpt         12.700          ops/ms
ClientSimple.getUser                         thrpt         14.978          ops/ms
ClientSimple.listUser                        thrpt          8.812          ops/ms
ClientSimple.createUser                       avgt          2.166           ms/op
ClientSimple.existUser                        avgt          1.677           ms/op
ClientSimple.getUser                          avgt          1.786           ms/op
ClientSimple.listUser                         avgt          3.973           ms/op
ClientSimple.createUser                     sample  14427   2.233 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.429           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.054           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.923           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.623           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.283           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.341           ms/op
ClientSimple.existUser                      sample  15693   2.051 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.687           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.935           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.920           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.431           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.530           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.530           ms/op
ClientSimple.getUser                        sample  15205   2.102 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.728           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.105           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.800           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.210           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.401           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.725           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.827           ms/op
ClientSimple.listUser                       sample   8881   3.600 ± 0.065   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.176           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.486           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.898           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.117           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         33.030           ms/op
ClientSimple.listUser:listUser·p1.00        sample         33.030           ms/op

Benchmark result is saved to 1717632953589.json
