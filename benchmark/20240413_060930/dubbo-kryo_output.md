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
# Warmup Iteration   1: 1.761 ops/ms
Iteration   1: 5.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.766 ops/ms


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
# Warmup Iteration   1: 5.569 ops/ms
Iteration   1: 12.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.582 ops/ms


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
# Warmup Iteration   1: 5.141 ops/ms
Iteration   1: 11.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.915 ops/ms


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
# Warmup Iteration   1: 5.206 ops/ms
Iteration   1: 8.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.897 ops/ms


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.061 ms/op
Iteration   1: 2.401 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.401 ms/op


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
# Warmup Iteration   1: 3.261 ±(99.9%) 0.082 ms/op
Iteration   1: 2.022 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.022 ms/op


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
# Warmup Iteration   1: 3.478 ±(99.9%) 0.064 ms/op
Iteration   1: 2.316 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.316 ms/op


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
# Warmup Iteration   1: 4.517 ±(99.9%) 0.093 ms/op
Iteration   1: 3.312 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.312 ms/op


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.129 ms/op
Iteration   1: 2.160 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   1.974 ms/op
                 createUser·p0.90:   2.585 ms/op
                 createUser·p0.95:   3.031 ms/op
                 createUser·p0.99:   6.134 ms/op
                 createUser·p0.999:  18.088 ms/op
                 createUser·p0.9999: 18.848 ms/op
                 createUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14815
  mean =      2.160 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 176 
    [ 1.250,  2.500) = 12783 
    [ 2.500,  3.750) = 1418 
    [ 3.750,  5.000) = 233 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      6.134 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     18.848 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 2.929 ±(99.9%) 0.073 ms/op
Iteration   1: 2.197 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.334 ms/op
                 existUser·p0.50:   2.195 ms/op
                 existUser·p0.90:   2.695 ms/op
                 existUser·p0.95:   2.855 ms/op
                 existUser·p0.99:   3.792 ms/op
                 existUser·p0.999:  19.938 ms/op
                 existUser·p0.9999: 20.424 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14532
  mean =      2.197 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11194 
    [ 2.500,  5.000) = 3256 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      3.792 ms/op
     p(99.9000) =     19.938 ms/op
     p(99.9900) =     20.424 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 3.302 ±(99.9%) 0.077 ms/op
Iteration   1: 2.312 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.538 ms/op
                 getUser·p0.50:   2.277 ms/op
                 getUser·p0.90:   2.941 ms/op
                 getUser·p0.95:   3.342 ms/op
                 getUser·p0.99:   4.314 ms/op
                 getUser·p0.999:  15.237 ms/op
                 getUser·p0.9999: 15.739 ms/op
                 getUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13836
  mean =      2.312 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 302 
    [ 1.250,  2.500) = 9125 
    [ 2.500,  3.750) = 4122 
    [ 3.750,  5.000) = 186 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.342 ms/op
     p(99.0000) =      4.314 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     15.739 ms/op
     p(99.9990) =     15.745 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.126 ms/op
Iteration   1: 3.543 ±(99.9%) 0.068 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.416 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  32.309 ms/op
                 listUser·p0.9999: 32.702 ms/op
                 listUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9013
  mean =      3.543 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 779 
    [ 2.500,  5.000) = 7847 
    [ 5.000,  7.500) = 277 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     32.309 ms/op
     p(99.9900) =     32.702 ms/op
     p(99.9990) =     32.702 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.766          ops/ms
ClientSimple.existUser                       thrpt         12.582          ops/ms
ClientSimple.getUser                         thrpt         11.915          ops/ms
ClientSimple.listUser                        thrpt          8.897          ops/ms
ClientSimple.createUser                       avgt          2.401           ms/op
ClientSimple.existUser                        avgt          2.022           ms/op
ClientSimple.getUser                          avgt          2.316           ms/op
ClientSimple.listUser                         avgt          3.312           ms/op
ClientSimple.createUser                     sample  14815   2.160 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.987           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.974           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.031           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.134           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.088           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.848           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.005           ms/op
ClientSimple.existUser                      sample  14532   2.197 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.334           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.792           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.938           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.424           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.513           ms/op
ClientSimple.getUser                        sample  13836   2.312 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.538           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.277           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.342           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.314           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.237           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.739           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.745           ms/op
ClientSimple.listUser                       sample   9013   3.543 ± 0.068   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.145           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.416           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.315           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.309           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.702           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.702           ms/op

Benchmark result is saved to 1712988291204.json
