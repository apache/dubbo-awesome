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
# Warmup Iteration   1: 1.661 ops/ms
Iteration   1: 7.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.172 ops/ms


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
# Warmup Iteration   1: 6.878 ops/ms
Iteration   1: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.780 ops/ms


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
# Warmup Iteration   1: 5.044 ops/ms
Iteration   1: 13.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.601 ops/ms


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
# Warmup Iteration   1: 5.348 ops/ms
Iteration   1: 8.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.655 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ±(99.9%) 0.082 ms/op
Iteration   1: 2.168 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.168 ms/op


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
# Warmup Iteration   1: 3.603 ±(99.9%) 0.063 ms/op
Iteration   1: 2.303 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.303 ms/op


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
# Warmup Iteration   1: 3.473 ±(99.9%) 0.054 ms/op
Iteration   1: 2.157 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.157 ms/op


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
# Warmup Iteration   1: 4.366 ±(99.9%) 0.091 ms/op
Iteration   1: 3.485 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.485 ms/op


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
# Warmup Iteration   1: 3.455 ±(99.9%) 0.101 ms/op
Iteration   1: 2.125 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   1.960 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   3.002 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  13.778 ms/op
                 createUser·p0.9999: 16.596 ms/op
                 createUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15039
  mean =      2.125 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 492 
    [ 1.250,  2.500) = 12553 
    [ 2.500,  3.750) = 1544 
    [ 3.750,  5.000) = 184 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     13.778 ms/op
     p(99.9900) =     16.596 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 2.881 ±(99.9%) 0.071 ms/op
Iteration   1: 1.944 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.483 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   3.846 ms/op
                 existUser·p0.999:  17.105 ms/op
                 existUser·p0.9999: 17.313 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16422
  mean =      1.944 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 350 
    [ 1.250,  2.500) = 14783 
    [ 2.500,  3.750) = 1116 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     17.313 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 3.617 ±(99.9%) 0.153 ms/op
Iteration   1: 1.972 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.503 ms/op
                 getUser·p0.50:   1.890 ms/op
                 getUser·p0.90:   2.433 ms/op
                 getUser·p0.95:   2.638 ms/op
                 getUser·p0.99:   3.795 ms/op
                 getUser·p0.999:  12.567 ms/op
                 getUser·p0.9999: 12.857 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16245
  mean =      1.972 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 246 
    [ 1.250,  2.500) = 14771 
    [ 2.500,  3.750) = 1060 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.795 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     12.857 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


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
# Warmup Iteration   1: 4.547 ±(99.9%) 0.136 ms/op
Iteration   1: 3.830 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.472 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8345
  mean =      3.830 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 635 
    [ 2.500,  5.000) = 7340 
    [ 5.000,  7.500) = 336 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     15.472 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     21.430 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.172          ops/ms
ClientSimple.existUser                       thrpt         12.780          ops/ms
ClientSimple.getUser                         thrpt         13.601          ops/ms
ClientSimple.listUser                        thrpt          8.655          ops/ms
ClientSimple.createUser                       avgt          2.168           ms/op
ClientSimple.existUser                        avgt          2.303           ms/op
ClientSimple.getUser                          avgt          2.157           ms/op
ClientSimple.listUser                         avgt          3.485           ms/op
ClientSimple.createUser                     sample  15039   2.125 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.710           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.960           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.002           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.529           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.778           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.596           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.728           ms/op
ClientSimple.existUser                      sample  16422   1.944 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.483           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.804           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.846           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.105           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.313           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.334           ms/op
ClientSimple.getUser                        sample  16245   1.972 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.503           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.890           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.795           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.567           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.857           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.878           ms/op
ClientSimple.listUser                       sample   8345   3.830 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.341           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.822           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.932           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.889           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.472           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.430           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.430           ms/op

Benchmark result is saved to 1723313115649.json
