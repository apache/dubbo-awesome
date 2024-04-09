# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.725 ops/ms
Iteration   1: 7.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.073 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.885 ops/ms
Iteration   1: 14.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.807 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.758 ops/ms
Iteration   1: 13.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.158 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.701 ops/ms
Iteration   1: 7.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.965 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.080 ms/op
Iteration   1: 2.305 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.305 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.621 ±(99.9%) 0.057 ms/op
Iteration   1: 2.046 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.046 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.263 ±(99.9%) 0.059 ms/op
Iteration   1: 1.951 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.951 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.082 ±(99.9%) 0.068 ms/op
Iteration   1: 3.594 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.594 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ±(99.9%) 0.096 ms/op
Iteration   1: 2.063 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.445 ms/op
                 createUser·p0.50:   1.909 ms/op
                 createUser·p0.90:   2.864 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   4.520 ms/op
                 createUser·p0.999:  14.327 ms/op
                 createUser·p0.9999: 14.909 ms/op
                 createUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15527
  mean =      2.063 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 343 
    [ 1.250,  2.500) = 12391 
    [ 2.500,  3.750) = 2588 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.445 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.864 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      4.520 ms/op
     p(99.9000) =     14.327 ms/op
     p(99.9900) =     14.909 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.942 ±(99.9%) 0.076 ms/op
Iteration   1: 1.749 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.527 ms/op
                 existUser·p0.50:   1.630 ms/op
                 existUser·p0.90:   2.195 ms/op
                 existUser·p0.95:   2.347 ms/op
                 existUser·p0.99:   2.843 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 10.389 ms/op
                 existUser·p1.00:   10.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18268
  mean =      1.749 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 531 
    [ 1.250,  2.500) = 17229 
    [ 2.500,  3.750) = 433 
    [ 3.750,  5.000) = 11 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      1.630 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      2.843 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     10.389 ms/op
     p(99.9990) =     10.551 ms/op
     p(99.9999) =     10.551 ms/op
    p(100.0000) =     10.551 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.147 ±(99.9%) 0.075 ms/op
Iteration   1: 2.013 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   1.843 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.675 ms/op
                 getUser·p0.99:   4.499 ms/op
                 getUser·p0.999:  26.149 ms/op
                 getUser·p0.9999: 26.602 ms/op
                 getUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15883
  mean =      2.013 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14394 
    [ 2.500,  5.000) = 1379 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      4.499 ms/op
     p(99.9000) =     26.149 ms/op
     p(99.9900) =     26.602 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.615 ±(99.9%) 0.125 ms/op
Iteration   1: 3.316 ±(99.9%) 0.074 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   4.029 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  38.003 ms/op
                 listUser·p0.9999: 38.339 ms/op
                 listUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9562
  mean =      3.316 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1557 
    [ 2.500,  5.000) = 7646 
    [ 5.000,  7.500) = 257 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      4.029 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     38.003 ms/op
     p(99.9900) =     38.339 ms/op
     p(99.9990) =     38.339 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.073          ops/ms
ClientSimple.existUser                       thrpt         14.807          ops/ms
ClientSimple.getUser                         thrpt         13.158          ops/ms
ClientSimple.listUser                        thrpt          7.965          ops/ms
ClientSimple.createUser                       avgt          2.305           ms/op
ClientSimple.existUser                        avgt          2.046           ms/op
ClientSimple.getUser                          avgt          1.951           ms/op
ClientSimple.listUser                         avgt          3.594           ms/op
ClientSimple.createUser                     sample  15527   2.063 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.445           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.909           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.864           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.076           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.520           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.327           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.909           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.909           ms/op
ClientSimple.existUser                      sample  18268   1.749 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.527           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.630           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.843           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.945           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.389           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.551           ms/op
ClientSimple.getUser                        sample  15883   2.013 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.824           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.843           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.499           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.149           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.602           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.640           ms/op
ClientSimple.listUser                       sample   9562   3.316 ± 0.074   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.999           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.982           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.029           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.643           ms/op
ClientSimple.listUser:listUser·p0.999       sample         38.003           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         38.339           ms/op
ClientSimple.listUser:listUser·p1.00        sample         38.339           ms/op

Benchmark result is saved to 1712642711521.json
