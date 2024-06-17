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
# Warmup Iteration   1: 1.738 ops/ms
Iteration   1: 7.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.189 ops/ms


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
# Warmup Iteration   1: 5.154 ops/ms
Iteration   1: 12.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.811 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.451 ops/ms
Iteration   1: 12.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.750 ops/ms


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
# Warmup Iteration   1: 4.807 ops/ms
Iteration   1: 8.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.106 ops/ms


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.061 ms/op
Iteration   1: 2.032 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.032 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.057 ms/op
Iteration   1: 1.804 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.804 ms/op


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
# Warmup Iteration   1: 3.516 ±(99.9%) 0.075 ms/op
Iteration   1: 2.214 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.214 ms/op


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
# Warmup Iteration   1: 4.897 ±(99.9%) 0.116 ms/op
Iteration   1: 3.315 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.315 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.096 ms/op
Iteration   1: 2.569 ±(99.9%) 0.163 ms/op
                 createUser·p0.00:   0.329 ms/op
                 createUser·p0.50:   2.042 ms/op
                 createUser·p0.90:   2.871 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   14.520 ms/op
                 createUser·p0.999:  106.497 ms/op
                 createUser·p0.9999: 131.891 ms/op
                 createUser·p1.00:   133.169 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12436
  mean =      2.569 ±(99.9%) 0.163 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 12290 
    [ 12.500,  25.000) = 71 
    [ 25.000,  37.500) = 25 
    [ 37.500,  50.000) = 13 
    [ 50.000,  62.500) = 10 
    [ 62.500,  75.000) = 2 
    [ 75.000,  87.500) = 2 
    [ 87.500, 100.000) = 4 
    [100.000, 112.500) = 12 
    [112.500, 125.000) = 4 
    [125.000, 137.500) = 3 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =     14.520 ms/op
     p(99.9000) =    106.497 ms/op
     p(99.9900) =    131.891 ms/op
     p(99.9990) =    133.169 ms/op
     p(99.9999) =    133.169 ms/op
    p(100.0000) =    133.169 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.085 ms/op
Iteration   1: 1.820 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   1.694 ms/op
                 existUser·p0.90:   2.253 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   3.218 ms/op
                 existUser·p0.999:  21.379 ms/op
                 existUser·p0.9999: 22.094 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17562
  mean =      1.820 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16888 
    [ 2.500,  5.000) = 538 
    [ 5.000,  7.500) = 71 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      1.694 ms/op
     p(90.0000) =      2.253 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      3.218 ms/op
     p(99.9000) =     21.379 ms/op
     p(99.9900) =     22.094 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.087 ms/op
Iteration   1: 1.946 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.596 ms/op
                 getUser·p0.50:   1.833 ms/op
                 getUser·p0.90:   2.540 ms/op
                 getUser·p0.95:   2.822 ms/op
                 getUser·p0.99:   4.029 ms/op
                 getUser·p0.999:  12.960 ms/op
                 getUser·p0.9999: 13.250 ms/op
                 getUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16429
  mean =      1.946 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 403 
    [ 1.250,  2.500) = 14241 
    [ 2.500,  3.750) = 1581 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      4.029 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     13.250 ms/op
     p(99.9990) =     13.271 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.137 ms/op
Iteration   1: 3.789 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  8.173 ms/op
                 listUser·p0.9999: 11.813 ms/op
                 listUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8463
  mean =      3.789 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 118 
    [ 2.500,  3.750) = 4158 
    [ 3.750,  5.000) = 3762 
    [ 5.000,  6.250) = 308 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =      8.173 ms/op
     p(99.9900) =     11.813 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.189          ops/ms
ClientSimple.existUser                       thrpt          12.811          ops/ms
ClientSimple.getUser                         thrpt          12.750          ops/ms
ClientSimple.listUser                        thrpt           8.106          ops/ms
ClientSimple.createUser                       avgt           2.032           ms/op
ClientSimple.existUser                        avgt           1.804           ms/op
ClientSimple.getUser                          avgt           2.214           ms/op
ClientSimple.listUser                         avgt           3.315           ms/op
ClientSimple.createUser                     sample  12436    2.569 ± 0.163   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.329           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.042           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.871           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.072           ms/op
ClientSimple.createUser:createUser·p0.99    sample          14.520           ms/op
ClientSimple.createUser:createUser·p0.999   sample         106.497           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         131.891           ms/op
ClientSimple.createUser:createUser·p1.00    sample         133.169           ms/op
ClientSimple.existUser                      sample  17562    1.820 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.536           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.694           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.253           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.429           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.218           ms/op
ClientSimple.existUser:existUser·p0.999     sample          21.379           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          22.094           ms/op
ClientSimple.existUser:existUser·p1.00      sample          22.118           ms/op
ClientSimple.getUser                        sample  16429    1.946 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.596           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.833           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.540           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.822           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.029           ms/op
ClientSimple.getUser:getUser·p0.999         sample          12.960           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          13.250           ms/op
ClientSimple.getUser:getUser·p1.00          sample          13.271           ms/op
ClientSimple.listUser                       sample   8463    3.789 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.973           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.744           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.612           ms/op
ClientSimple.listUser:listUser·p0.95        sample           5.005           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.963           ms/op
ClientSimple.listUser:listUser·p0.999       sample           8.173           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          11.813           ms/op
ClientSimple.listUser:listUser·p1.00        sample          11.813           ms/op

Benchmark result is saved to 1718647534174.json
