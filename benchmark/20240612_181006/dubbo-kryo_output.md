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
# Warmup Iteration   1: 1.554 ops/ms
Iteration   1: 7.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.425 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.806 ops/ms
Iteration   1: 12.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.794 ops/ms


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
# Warmup Iteration   1: 6.493 ops/ms
Iteration   1: 15.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.041 ops/ms


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
# Warmup Iteration   1: 5.615 ops/ms
Iteration   1: 8.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.498 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.884 ±(99.9%) 0.092 ms/op
Iteration   1: 2.213 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.213 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.087 ±(99.9%) 0.047 ms/op
Iteration   1: 1.860 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.860 ms/op


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
# Warmup Iteration   1: 3.263 ±(99.9%) 0.065 ms/op
Iteration   1: 1.850 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.850 ms/op


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.082 ms/op
Iteration   1: 3.413 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.413 ms/op


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
# Warmup Iteration   1: 3.350 ±(99.9%) 0.080 ms/op
Iteration   1: 2.134 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   1.979 ms/op
                 createUser·p0.90:   2.585 ms/op
                 createUser·p0.95:   2.810 ms/op
                 createUser·p0.99:   5.541 ms/op
                 createUser·p0.999:  44.827 ms/op
                 createUser·p0.9999: 45.581 ms/op
                 createUser·p1.00:   46.006 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14986
  mean =      2.134 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14820 
    [ 5.000, 10.000) = 130 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      1.979 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      5.541 ms/op
     p(99.9000) =     44.827 ms/op
     p(99.9900) =     45.581 ms/op
     p(99.9990) =     46.006 ms/op
     p(99.9999) =     46.006 ms/op
    p(100.0000) =     46.006 ms/op


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
# Warmup Iteration   1: 2.953 ±(99.9%) 0.068 ms/op
Iteration   1: 1.840 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   4.155 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 10.638 ms/op
                 existUser·p1.00:   10.650 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17377
  mean =      1.840 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 259 
    [ 1.250,  2.500) = 16446 
    [ 2.500,  3.750) = 464 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      4.155 ms/op
     p(99.9000) =      9.978 ms/op
     p(99.9900) =     10.638 ms/op
     p(99.9990) =     10.650 ms/op
     p(99.9999) =     10.650 ms/op
    p(100.0000) =     10.650 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.085 ms/op
Iteration   1: 1.839 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   1.679 ms/op
                 getUser·p0.90:   2.220 ms/op
                 getUser·p0.95:   2.413 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  18.186 ms/op
                 getUser·p0.9999: 18.260 ms/op
                 getUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17377
  mean =      1.839 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 16557 
    [ 2.500,  3.750) = 462 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      2.220 ms/op
     p(95.0000) =      2.413 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     18.260 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.756 ±(99.9%) 0.145 ms/op
Iteration   1: 3.189 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.195 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.421 ms/op
                 listUser·p0.99:   5.519 ms/op
                 listUser·p0.999:  12.532 ms/op
                 listUser·p0.9999: 13.844 ms/op
                 listUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10025
  mean =      3.189 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 2557 
    [ 2.500,  3.750) = 5279 
    [ 3.750,  5.000) = 1976 
    [ 5.000,  6.250) = 141 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.421 ms/op
     p(99.0000) =      5.519 ms/op
     p(99.9000) =     12.532 ms/op
     p(99.9900) =     13.844 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.425          ops/ms
ClientSimple.existUser                       thrpt         12.794          ops/ms
ClientSimple.getUser                         thrpt         15.041          ops/ms
ClientSimple.listUser                        thrpt          8.498          ops/ms
ClientSimple.createUser                       avgt          2.213           ms/op
ClientSimple.existUser                        avgt          1.860           ms/op
ClientSimple.getUser                          avgt          1.850           ms/op
ClientSimple.listUser                         avgt          3.413           ms/op
ClientSimple.createUser                     sample  14986   2.134 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.657           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.979           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.541           ms/op
ClientSimple.createUser:createUser·p0.999   sample         44.827           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         45.581           ms/op
ClientSimple.createUser:createUser·p1.00    sample         46.006           ms/op
ClientSimple.existUser                      sample  17377   1.840 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.607           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.735           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.155           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.978           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.638           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.650           ms/op
ClientSimple.getUser                        sample  17377   1.839 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.773           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.679           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.220           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.998           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.186           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.260           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.285           ms/op
ClientSimple.listUser                       sample  10025   3.189 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.202           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.195           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.421           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.519           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.532           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.844           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.844           ms/op

Benchmark result is saved to 1718215548738.json
