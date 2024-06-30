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
# Warmup Iteration   1: 1.435 ops/ms
Iteration   1: 7.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.033 ops/ms


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
# Warmup Iteration   1: 6.334 ops/ms
Iteration   1: 12.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.481 ops/ms


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
# Warmup Iteration   1: 5.701 ops/ms
Iteration   1: 13.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.282 ops/ms


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
# Warmup Iteration   1: 4.462 ops/ms
Iteration   1: 8.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.849 ops/ms


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
# Warmup Iteration   1: 4.623 ±(99.9%) 0.080 ms/op
Iteration   1: 1.884 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.884 ms/op


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
# Warmup Iteration   1: 3.177 ±(99.9%) 0.050 ms/op
Iteration   1: 1.956 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.956 ms/op


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
# Warmup Iteration   1: 3.252 ±(99.9%) 0.055 ms/op
Iteration   1: 1.847 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.847 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ±(99.9%) 0.077 ms/op
Iteration   1: 3.390 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.390 ms/op


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
# Warmup Iteration   1: 3.671 ±(99.9%) 0.101 ms/op
Iteration   1: 2.189 ±(99.9%) 0.059 ms/op
                 createUser·p0.00:   0.491 ms/op
                 createUser·p0.50:   1.833 ms/op
                 createUser·p0.90:   2.691 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   10.207 ms/op
                 createUser·p0.999:  43.516 ms/op
                 createUser·p0.9999: 48.860 ms/op
                 createUser·p1.00:   48.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14611
  mean =      2.189 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14234 
    [ 5.000, 10.000) = 228 
    [10.000, 15.000) = 106 
    [15.000, 20.000) = 9 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.491 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     43.516 ms/op
     p(99.9900) =     48.860 ms/op
     p(99.9990) =     48.890 ms/op
     p(99.9999) =     48.890 ms/op
    p(100.0000) =     48.890 ms/op


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
# Warmup Iteration   1: 2.986 ±(99.9%) 0.072 ms/op
Iteration   1: 2.060 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.410 ms/op
                 existUser·p0.50:   1.939 ms/op
                 existUser·p0.90:   2.535 ms/op
                 existUser·p0.95:   2.795 ms/op
                 existUser·p0.99:   4.155 ms/op
                 existUser·p0.999:  18.940 ms/op
                 existUser·p0.9999: 19.541 ms/op
                 existUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15553
  mean =      2.060 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 708 
    [ 1.250,  2.500) = 13043 
    [ 2.500,  3.750) = 1621 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.795 ms/op
     p(99.0000) =      4.155 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.541 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 3.023 ±(99.9%) 0.081 ms/op
Iteration   1: 1.755 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.595 ms/op
                 getUser·p0.50:   1.667 ms/op
                 getUser·p0.90:   1.966 ms/op
                 getUser·p0.95:   2.167 ms/op
                 getUser·p0.99:   3.052 ms/op
                 getUser·p0.999:  12.976 ms/op
                 getUser·p0.9999: 16.558 ms/op
                 getUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18474
  mean =      1.755 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 17852 
    [ 2.500,  3.750) = 358 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      1.966 ms/op
     p(95.0000) =      2.167 ms/op
     p(99.0000) =      3.052 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     16.558 ms/op
     p(99.9990) =     17.072 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.122 ms/op
Iteration   1: 3.571 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.285 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 14.254 ms/op
                 listUser·p1.00:   14.254 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8977
  mean =      3.571 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 367 
    [ 2.500,  3.750) = 5348 
    [ 3.750,  5.000) = 3006 
    [ 5.000,  6.250) = 152 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.285 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     14.254 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.033          ops/ms
ClientSimple.existUser                       thrpt         12.481          ops/ms
ClientSimple.getUser                         thrpt         13.282          ops/ms
ClientSimple.listUser                        thrpt          8.849          ops/ms
ClientSimple.createUser                       avgt          1.884           ms/op
ClientSimple.existUser                        avgt          1.956           ms/op
ClientSimple.getUser                          avgt          1.847           ms/op
ClientSimple.listUser                         avgt          3.390           ms/op
ClientSimple.createUser                     sample  14611   2.189 ± 0.059   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.491           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.833           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.047           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.207           ms/op
ClientSimple.createUser:createUser·p0.999   sample         43.516           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         48.860           ms/op
ClientSimple.createUser:createUser·p1.00    sample         48.890           ms/op
ClientSimple.existUser                      sample  15553   2.060 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.410           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.939           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.795           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.155           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.940           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.541           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.595           ms/op
ClientSimple.getUser                        sample  18474   1.755 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.595           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.667           ms/op
ClientSimple.getUser:getUser·p0.90          sample          1.966           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.167           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.052           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.976           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.558           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.072           ms/op
ClientSimple.listUser                       sample   8977   3.571 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.942           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.285           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.107           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.254           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.254           ms/op

Benchmark result is saved to 1719770687780.json
