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
# Warmup Iteration   1: 1.774 ops/ms
Iteration   1: 6.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.934 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.503 ops/ms
Iteration   1: 13.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.034 ops/ms


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
# Warmup Iteration   1: 6.811 ops/ms
Iteration   1: 14.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.542 ops/ms


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
# Warmup Iteration   1: 4.964 ops/ms
Iteration   1: 9.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.109 ops/ms


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.079 ms/op
Iteration   1: 2.205 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.205 ms/op


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
# Warmup Iteration   1: 2.886 ±(99.9%) 0.051 ms/op
Iteration   1: 1.731 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.731 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.485 ±(99.9%) 0.128 ms/op
Iteration   1: 2.008 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.008 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.991 ±(99.9%) 0.088 ms/op
Iteration   1: 3.176 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.176 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.762 ±(99.9%) 0.094 ms/op
Iteration   1: 2.278 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.435 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.712 ms/op
                 createUser·p0.95:   3.035 ms/op
                 createUser·p0.99:   8.422 ms/op
                 createUser·p0.999:  15.155 ms/op
                 createUser·p0.9999: 17.851 ms/op
                 createUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14026
  mean =      2.278 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 11061 
    [ 2.500,  3.750) = 2497 
    [ 3.750,  5.000) = 146 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      8.422 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     17.851 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 3.007 ±(99.9%) 0.070 ms/op
Iteration   1: 1.928 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.516 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   2.822 ms/op
                 existUser·p0.999:  22.938 ms/op
                 existUser·p0.9999: 23.201 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16575
  mean =      1.928 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15990 
    [ 2.500,  5.000) = 502 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      2.822 ms/op
     p(99.9000) =     22.938 ms/op
     p(99.9900) =     23.201 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 3.355 ±(99.9%) 0.080 ms/op
Iteration   1: 2.014 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   1.808 ms/op
                 getUser·p0.90:   2.732 ms/op
                 getUser·p0.95:   2.982 ms/op
                 getUser·p0.99:   5.191 ms/op
                 getUser·p0.999:  11.534 ms/op
                 getUser·p0.9999: 12.268 ms/op
                 getUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16037
  mean =      2.014 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 629 
    [ 1.250,  2.500) = 12602 
    [ 2.500,  3.750) = 2507 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 134 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      5.191 ms/op
     p(99.9000) =     11.534 ms/op
     p(99.9900) =     12.268 ms/op
     p(99.9990) =     12.911 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.118 ms/op
Iteration   1: 3.233 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.923 ms/op
                 listUser·p0.999:  23.233 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9883
  mean =      3.233 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1642 
    [ 2.500,  5.000) = 7980 
    [ 5.000,  7.500) = 217 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     23.233 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.934          ops/ms
ClientSimple.existUser                       thrpt         13.034          ops/ms
ClientSimple.getUser                         thrpt         14.542          ops/ms
ClientSimple.listUser                        thrpt          9.109          ops/ms
ClientSimple.createUser                       avgt          2.205           ms/op
ClientSimple.existUser                        avgt          1.731           ms/op
ClientSimple.getUser                          avgt          2.008           ms/op
ClientSimple.listUser                         avgt          3.176           ms/op
ClientSimple.createUser                     sample  14026   2.278 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.435           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.035           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.422           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.155           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.851           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.957           ms/op
ClientSimple.existUser                      sample  16575   1.928 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.516           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.804           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.822           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.938           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.201           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.265           ms/op
ClientSimple.getUser                        sample  16037   2.014 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.530           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.808           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.982           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.191           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.534           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.268           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.911           ms/op
ClientSimple.listUser                       sample   9883   3.233 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.850           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.916           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.923           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.233           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.855           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.855           ms/op

Benchmark result is saved to 1722817053680.json
