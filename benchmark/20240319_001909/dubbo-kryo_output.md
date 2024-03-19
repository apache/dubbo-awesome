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
# Warmup Iteration   1: 1.540 ops/ms
Iteration   1: 6.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.915 ops/ms


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
# Warmup Iteration   1: 6.364 ops/ms
Iteration   1: 11.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.670 ops/ms


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
# Warmup Iteration   1: 4.889 ops/ms
Iteration   1: 11.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.845 ops/ms


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
# Warmup Iteration   1: 5.937 ops/ms
Iteration   1: 9.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.383 ops/ms


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.062 ms/op
Iteration   1: 2.041 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.041 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.056 ms/op
Iteration   1: 2.068 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.068 ms/op


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
# Warmup Iteration   1: 3.298 ±(99.9%) 0.077 ms/op
Iteration   1: 2.085 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.085 ms/op


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.071 ms/op
Iteration   1: 3.245 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.245 ms/op


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
# Warmup Iteration   1: 3.544 ±(99.9%) 0.089 ms/op
Iteration   1: 2.152 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   1.944 ms/op
                 createUser·p0.90:   2.703 ms/op
                 createUser·p0.95:   2.867 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  26.378 ms/op
                 createUser·p0.9999: 28.099 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15001
  mean =      2.152 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12070 
    [ 2.500,  5.000) = 2792 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =     26.378 ms/op
     p(99.9900) =     28.099 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 2.847 ±(99.9%) 0.068 ms/op
Iteration   1: 1.826 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.475 ms/op
                 existUser·p0.50:   1.669 ms/op
                 existUser·p0.90:   2.220 ms/op
                 existUser·p0.95:   2.400 ms/op
                 existUser·p0.99:   4.472 ms/op
                 existUser·p0.999:  26.788 ms/op
                 existUser·p0.9999: 27.606 ms/op
                 existUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17504
  mean =      1.826 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16877 
    [ 2.500,  5.000) = 500 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.220 ms/op
     p(95.0000) =      2.400 ms/op
     p(99.0000) =      4.472 ms/op
     p(99.9000) =     26.788 ms/op
     p(99.9900) =     27.606 ms/op
     p(99.9990) =     29.327 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 3.340 ±(99.9%) 0.081 ms/op
Iteration   1: 2.121 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   1.982 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.978 ms/op
                 getUser·p0.99:   5.024 ms/op
                 getUser·p0.999:  13.799 ms/op
                 getUser·p0.9999: 14.261 ms/op
                 getUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15766
  mean =      2.121 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 13841 
    [ 2.500,  3.750) = 1653 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      1.982 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      5.024 ms/op
     p(99.9000) =     13.799 ms/op
     p(99.9900) =     14.261 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.151 ms/op
Iteration   1: 3.035 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   2.814 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.084 ms/op
                 listUser·p0.99:   5.574 ms/op
                 listUser·p0.999:  16.462 ms/op
                 listUser·p0.9999: 17.195 ms/op
                 listUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10525
  mean =      3.035 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1765 
    [ 2.500,  3.750) = 7486 
    [ 3.750,  5.000) = 1057 
    [ 5.000,  6.250) = 165 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.574 ms/op
     p(99.9000) =     16.462 ms/op
     p(99.9900) =     17.195 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.915          ops/ms
ClientSimple.existUser                       thrpt         11.670          ops/ms
ClientSimple.getUser                         thrpt         11.845          ops/ms
ClientSimple.listUser                        thrpt          9.383          ops/ms
ClientSimple.createUser                       avgt          2.041           ms/op
ClientSimple.existUser                        avgt          2.068           ms/op
ClientSimple.getUser                          avgt          2.085           ms/op
ClientSimple.listUser                         avgt          3.245           ms/op
ClientSimple.createUser                     sample  15001   2.152 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.671           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.944           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.809           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.378           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.099           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.115           ms/op
ClientSimple.existUser                      sample  17504   1.826 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.475           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.669           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.472           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.788           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.606           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.327           ms/op
ClientSimple.getUser                        sample  15766   2.121 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.736           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.982           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.978           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.024           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.799           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.261           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.270           ms/op
ClientSimple.listUser                       sample  10525   3.035 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.843           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.814           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.850           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.084           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.574           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.462           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.195           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.203           ms/op

Benchmark result is saved to 1710807300002.json
