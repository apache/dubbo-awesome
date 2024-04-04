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
# Warmup Iteration   1: 1.981 ops/ms
Iteration   1: 7.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.380 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.247 ops/ms
Iteration   1: 13.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.168 ops/ms


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
# Warmup Iteration   1: 5.628 ops/ms
Iteration   1: 13.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.796 ops/ms


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
# Warmup Iteration   1: 4.596 ops/ms
Iteration   1: 9.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.221 ops/ms


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
# Warmup Iteration   1: 3.611 ±(99.9%) 0.065 ms/op
Iteration   1: 2.225 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.225 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.166 ±(99.9%) 0.051 ms/op
Iteration   1: 1.926 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.926 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.159 ±(99.9%) 0.048 ms/op
Iteration   1: 2.289 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.289 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.638 ±(99.9%) 0.113 ms/op
Iteration   1: 3.326 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.326 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.578 ±(99.9%) 0.085 ms/op
Iteration   1: 2.105 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.579 ms/op
                 createUser·p0.50:   1.870 ms/op
                 createUser·p0.90:   2.679 ms/op
                 createUser·p0.95:   3.058 ms/op
                 createUser·p0.99:   5.623 ms/op
                 createUser·p0.999:  17.748 ms/op
                 createUser·p0.9999: 20.406 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15185
  mean =      2.105 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13195 
    [ 2.500,  5.000) = 1749 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      3.058 ms/op
     p(99.0000) =      5.623 ms/op
     p(99.9000) =     17.748 ms/op
     p(99.9900) =     20.406 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.974 ±(99.9%) 0.070 ms/op
Iteration   1: 1.704 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   1.591 ms/op
                 existUser·p0.90:   2.101 ms/op
                 existUser·p0.95:   2.290 ms/op
                 existUser·p0.99:   2.781 ms/op
                 existUser·p0.999:  11.083 ms/op
                 existUser·p0.9999: 11.536 ms/op
                 existUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18773
  mean =      1.704 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 426 
    [ 1.250,  2.500) = 17900 
    [ 2.500,  3.750) = 351 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      1.591 ms/op
     p(90.0000) =      2.101 ms/op
     p(95.0000) =      2.290 ms/op
     p(99.0000) =      2.781 ms/op
     p(99.9000) =     11.083 ms/op
     p(99.9900) =     11.536 ms/op
     p(99.9990) =     11.551 ms/op
     p(99.9999) =     11.551 ms/op
    p(100.0000) =     11.551 ms/op


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
# Warmup Iteration   1: 3.346 ±(99.9%) 0.103 ms/op
Iteration   1: 1.833 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.573 ms/op
                 getUser·p0.50:   1.749 ms/op
                 getUser·p0.90:   2.224 ms/op
                 getUser·p0.95:   2.376 ms/op
                 getUser·p0.99:   3.175 ms/op
                 getUser·p0.999:  16.450 ms/op
                 getUser·p0.9999: 16.785 ms/op
                 getUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17474
  mean =      1.833 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 181 
    [ 1.250,  2.500) = 16744 
    [ 2.500,  3.750) = 466 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      3.175 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     16.785 ms/op
     p(99.9990) =     16.810 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.129 ms/op
Iteration   1: 3.561 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 13.484 ms/op
                 listUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8985
  mean =      3.561 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 712 
    [ 2.500,  3.750) = 5407 
    [ 3.750,  5.000) = 2518 
    [ 5.000,  6.250) = 230 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     13.484 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.380          ops/ms
ClientSimple.existUser                       thrpt         13.168          ops/ms
ClientSimple.getUser                         thrpt         13.796          ops/ms
ClientSimple.listUser                        thrpt          9.221          ops/ms
ClientSimple.createUser                       avgt          2.225           ms/op
ClientSimple.existUser                        avgt          1.926           ms/op
ClientSimple.getUser                          avgt          2.289           ms/op
ClientSimple.listUser                         avgt          3.326           ms/op
ClientSimple.createUser                     sample  15185   2.105 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.579           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.870           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.058           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.623           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.748           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.406           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.644           ms/op
ClientSimple.existUser                      sample  18773   1.704 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.531           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.591           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.101           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.781           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.083           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.536           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.551           ms/op
ClientSimple.getUser                        sample  17474   1.833 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.573           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.749           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.224           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.175           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.450           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.785           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.810           ms/op
ClientSimple.listUser                       sample   8985   3.561 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.931           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.486           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.891           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.643           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.304           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.484           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.484           ms/op

Benchmark result is saved to 1712253948158.json
