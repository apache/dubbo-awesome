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
# Warmup Iteration   1: 2.326 ops/ms
Iteration   1: 7.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.604 ops/ms


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
# Warmup Iteration   1: 6.218 ops/ms
Iteration   1: 11.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.945 ops/ms


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
# Warmup Iteration   1: 6.153 ops/ms
Iteration   1: 13.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.968 ops/ms


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
# Warmup Iteration   1: 4.523 ops/ms
Iteration   1: 8.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.442 ops/ms


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.072 ms/op
Iteration   1: 2.158 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.158 ms/op


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
# Warmup Iteration   1: 3.440 ±(99.9%) 0.060 ms/op
Iteration   1: 1.755 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.755 ms/op


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
# Warmup Iteration   1: 3.026 ±(99.9%) 0.056 ms/op
Iteration   1: 1.718 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.718 ms/op


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
# Warmup Iteration   1: 4.287 ±(99.9%) 0.079 ms/op
Iteration   1: 3.492 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.492 ms/op


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
# Warmup Iteration   1: 3.565 ±(99.9%) 0.092 ms/op
Iteration   1: 2.264 ±(99.9%) 0.106 ms/op
                 createUser·p0.00:   0.480 ms/op
                 createUser·p0.50:   1.858 ms/op
                 createUser·p0.90:   2.560 ms/op
                 createUser·p0.95:   2.986 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  76.946 ms/op
                 createUser·p0.9999: 99.259 ms/op
                 createUser·p1.00:   101.319 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14246
  mean =      2.264 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 14160 
    [ 12.500,  25.000) = 39 
    [ 25.000,  37.500) = 5 
    [ 37.500,  50.000) = 10 
    [ 50.000,  62.500) = 11 
    [ 62.500,  75.000) = 6 
    [ 75.000,  87.500) = 7 
    [ 87.500, 100.000) = 7 
    [100.000, 112.500) = 1 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     76.946 ms/op
     p(99.9900) =     99.259 ms/op
     p(99.9990) =    101.319 ms/op
     p(99.9999) =    101.319 ms/op
    p(100.0000) =    101.319 ms/op


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
# Warmup Iteration   1: 2.881 ±(99.9%) 0.060 ms/op
Iteration   1: 1.914 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.541 ms/op
                 existUser·p0.50:   1.859 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.541 ms/op
                 existUser·p0.99:   4.290 ms/op
                 existUser·p0.999:  11.628 ms/op
                 existUser·p0.9999: 11.818 ms/op
                 existUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16712
  mean =      1.914 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 620 
    [ 1.250,  2.500) = 15051 
    [ 2.500,  3.750) = 834 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.859 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.541 ms/op
     p(99.0000) =      4.290 ms/op
     p(99.9000) =     11.628 ms/op
     p(99.9900) =     11.818 ms/op
     p(99.9990) =     11.829 ms/op
     p(99.9999) =     11.829 ms/op
    p(100.0000) =     11.829 ms/op


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
# Warmup Iteration   1: 3.407 ±(99.9%) 0.099 ms/op
Iteration   1: 2.127 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   1.942 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.682 ms/op
                 getUser·p0.99:   4.041 ms/op
                 getUser·p0.999:  30.441 ms/op
                 getUser·p0.9999: 32.168 ms/op
                 getUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15061
  mean =      2.127 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13293 
    [ 2.500,  5.000) = 1682 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.682 ms/op
     p(99.0000) =      4.041 ms/op
     p(99.9000) =     30.441 ms/op
     p(99.9900) =     32.168 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ±(99.9%) 0.178 ms/op
Iteration   1: 3.445 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.561 ms/op
                 listUser·p0.50:   3.412 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  19.137 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9282
  mean =      3.445 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 936 
    [ 2.500,  3.750) = 5611 
    [ 3.750,  5.000) = 2399 
    [ 5.000,  6.250) = 180 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.604          ops/ms
ClientSimple.existUser                       thrpt          11.945          ops/ms
ClientSimple.getUser                         thrpt          13.968          ops/ms
ClientSimple.listUser                        thrpt           8.442          ops/ms
ClientSimple.createUser                       avgt           2.158           ms/op
ClientSimple.existUser                        avgt           1.755           ms/op
ClientSimple.getUser                          avgt           1.718           ms/op
ClientSimple.listUser                         avgt           3.492           ms/op
ClientSimple.createUser                     sample  14246    2.264 ± 0.106   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.480           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.858           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.560           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.986           ms/op
ClientSimple.createUser:createUser·p0.99    sample           9.159           ms/op
ClientSimple.createUser:createUser·p0.999   sample          76.946           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          99.259           ms/op
ClientSimple.createUser:createUser·p1.00    sample         101.319           ms/op
ClientSimple.existUser                      sample  16712    1.914 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.541           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.859           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.541           ms/op
ClientSimple.existUser:existUser·p0.99      sample           4.290           ms/op
ClientSimple.existUser:existUser·p0.999     sample          11.628           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          11.818           ms/op
ClientSimple.existUser:existUser·p1.00      sample          11.829           ms/op
ClientSimple.getUser                        sample  15061    2.127 ± 0.041   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.811           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.942           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.682           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.041           ms/op
ClientSimple.getUser:getUser·p0.999         sample          30.441           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          32.168           ms/op
ClientSimple.getUser:getUser·p1.00          sample          32.997           ms/op
ClientSimple.listUser                       sample   9282    3.445 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.561           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.412           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.571           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.570           ms/op
ClientSimple.listUser:listUser·p0.999       sample          19.137           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          19.825           ms/op
ClientSimple.listUser:listUser·p1.00        sample          19.825           ms/op

Benchmark result is saved to 1721714741953.json
