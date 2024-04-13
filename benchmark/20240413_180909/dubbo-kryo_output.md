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
# Warmup Iteration   1: 1.682 ops/ms
Iteration   1: 7.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.185 ops/ms


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
# Warmup Iteration   1: 5.313 ops/ms
Iteration   1: 12.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.368 ops/ms


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
# Warmup Iteration   1: 5.001 ops/ms
Iteration   1: 12.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.254 ops/ms


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
# Warmup Iteration   1: 4.208 ops/ms
Iteration   1: 9.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.013 ops/ms


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.074 ms/op
Iteration   1: 2.078 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.078 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.053 ms/op
Iteration   1: 2.120 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.120 ms/op


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
# Warmup Iteration   1: 3.347 ±(99.9%) 0.061 ms/op
Iteration   1: 1.893 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.893 ms/op


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.096 ms/op
Iteration   1: 3.492 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.492 ms/op


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
# Warmup Iteration   1: 3.416 ±(99.9%) 0.099 ms/op
Iteration   1: 2.301 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.375 ms/op
                 createUser·p0.50:   2.195 ms/op
                 createUser·p0.90:   2.798 ms/op
                 createUser·p0.95:   3.019 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  19.304 ms/op
                 createUser·p0.9999: 20.258 ms/op
                 createUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13899
  mean =      2.301 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10375 
    [ 2.500,  5.000) = 3290 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     19.304 ms/op
     p(99.9900) =     20.258 ms/op
     p(99.9990) =     20.283 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.073 ms/op
Iteration   1: 1.941 ±(99.9%) 0.060 ms/op
                 existUser·p0.00:   0.269 ms/op
                 existUser·p0.50:   1.767 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.408 ms/op
                 existUser·p0.99:   4.274 ms/op
                 existUser·p0.999:  42.749 ms/op
                 existUser·p0.9999: 67.289 ms/op
                 existUser·p1.00:   68.420 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16632
  mean =      1.941 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16520 
    [ 5.000, 10.000) = 23 
    [10.000, 15.000) = 36 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 12 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 7 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.269 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      4.274 ms/op
     p(99.9000) =     42.749 ms/op
     p(99.9900) =     67.289 ms/op
     p(99.9990) =     68.420 ms/op
     p(99.9999) =     68.420 ms/op
    p(100.0000) =     68.420 ms/op


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
# Warmup Iteration   1: 3.639 ±(99.9%) 0.106 ms/op
Iteration   1: 2.233 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   2.062 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.929 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  21.791 ms/op
                 getUser·p0.9999: 24.402 ms/op
                 getUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14297
  mean =      2.233 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12347 
    [ 2.500,  5.000) = 1760 
    [ 5.000,  7.500) = 120 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     21.791 ms/op
     p(99.9900) =     24.402 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.154 ms/op
Iteration   1: 3.480 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.248 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.163 ms/op
                 listUser·p0.999:  26.083 ms/op
                 listUser·p0.9999: 26.280 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9243
  mean =      3.480 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 451 
    [ 2.500,  5.000) = 8598 
    [ 5.000,  7.500) = 146 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.163 ms/op
     p(99.9000) =     26.083 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.185          ops/ms
ClientSimple.existUser                       thrpt         12.368          ops/ms
ClientSimple.getUser                         thrpt         12.254          ops/ms
ClientSimple.listUser                        thrpt          9.013          ops/ms
ClientSimple.createUser                       avgt          2.078           ms/op
ClientSimple.existUser                        avgt          2.120           ms/op
ClientSimple.getUser                          avgt          1.893           ms/op
ClientSimple.listUser                         avgt          3.492           ms/op
ClientSimple.createUser                     sample  13899   2.301 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.375           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.195           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.019           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.906           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.304           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.258           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.283           ms/op
ClientSimple.existUser                      sample  16632   1.941 ± 0.060   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.269           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.767           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.274           ms/op
ClientSimple.existUser:existUser·p0.999     sample         42.749           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         67.289           ms/op
ClientSimple.existUser:existUser·p1.00      sample         68.420           ms/op
ClientSimple.getUser                        sample  14297   2.233 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.569           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.062           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.062           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.791           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.402           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.642           ms/op
ClientSimple.listUser                       sample   9243   3.480 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.067           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.248           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.571           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.163           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.083           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.280           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.280           ms/op

Benchmark result is saved to 1713031504962.json
