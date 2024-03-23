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
# Warmup Iteration   1: 1.961 ops/ms
Iteration   1: 7.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.386 ops/ms


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
# Warmup Iteration   1: 7.634 ops/ms
Iteration   1: 12.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.960 ops/ms


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
# Warmup Iteration   1: 5.102 ops/ms
Iteration   1: 14.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.216 ops/ms


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
# Warmup Iteration   1: 4.660 ops/ms
Iteration   1: 8.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.930 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.739 ±(99.9%) 0.064 ms/op
Iteration   1: 2.122 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.122 ms/op


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
# Warmup Iteration   1: 3.037 ±(99.9%) 0.048 ms/op
Iteration   1: 1.990 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.990 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.056 ms/op
Iteration   1: 2.007 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.007 ms/op


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.079 ms/op
Iteration   1: 3.079 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.079 ms/op


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
# Warmup Iteration   1: 3.485 ±(99.9%) 0.082 ms/op
Iteration   1: 2.108 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.343 ms/op
                 createUser·p0.50:   1.845 ms/op
                 createUser·p0.90:   2.445 ms/op
                 createUser·p0.95:   2.766 ms/op
                 createUser·p0.99:   11.227 ms/op
                 createUser·p0.999:  23.161 ms/op
                 createUser·p0.9999: 23.377 ms/op
                 createUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15174
  mean =      2.108 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13849 
    [ 2.500,  5.000) = 962 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.766 ms/op
     p(99.0000) =     11.227 ms/op
     p(99.9000) =     23.161 ms/op
     p(99.9900) =     23.377 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 2.815 ±(99.9%) 0.059 ms/op
Iteration   1: 1.695 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   1.577 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.245 ms/op
                 existUser·p0.99:   2.589 ms/op
                 existUser·p0.999:  13.265 ms/op
                 existUser·p0.9999: 13.797 ms/op
                 existUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18869
  mean =      1.695 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 368 
    [ 1.250,  2.500) = 18233 
    [ 2.500,  3.750) = 214 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.577 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.245 ms/op
     p(99.0000) =      2.589 ms/op
     p(99.9000) =     13.265 ms/op
     p(99.9900) =     13.797 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 3.334 ±(99.9%) 0.079 ms/op
Iteration   1: 2.157 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   2.052 ms/op
                 getUser·p0.90:   2.621 ms/op
                 getUser·p0.95:   2.818 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  15.402 ms/op
                 getUser·p0.9999: 15.663 ms/op
                 getUser·p1.00:   15.663 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14826
  mean =      2.157 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 12289 
    [ 2.500,  3.750) = 2212 
    [ 3.750,  5.000) = 107 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.052 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =     15.402 ms/op
     p(99.9900) =     15.663 ms/op
     p(99.9990) =     15.663 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.114 ms/op
Iteration   1: 3.128 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.774 ms/op
                 listUser·p0.999:  7.152 ms/op
                 listUser·p0.9999: 10.941 ms/op
                 listUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10317
  mean =      3.128 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 125 
    [ 2.000,  3.000) = 5913 
    [ 3.000,  4.000) = 3324 
    [ 4.000,  5.000) = 730 
    [ 5.000,  6.000) = 165 
    [ 6.000,  7.000) = 49 
    [ 7.000,  8.000) = 10 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 
    [10.000, 11.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.774 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     10.941 ms/op
     p(99.9990) =     11.059 ms/op
     p(99.9999) =     11.059 ms/op
    p(100.0000) =     11.059 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.386          ops/ms
ClientSimple.existUser                       thrpt         12.960          ops/ms
ClientSimple.getUser                         thrpt         14.216          ops/ms
ClientSimple.listUser                        thrpt          8.930          ops/ms
ClientSimple.createUser                       avgt          2.122           ms/op
ClientSimple.existUser                        avgt          1.990           ms/op
ClientSimple.getUser                          avgt          2.007           ms/op
ClientSimple.listUser                         avgt          3.079           ms/op
ClientSimple.createUser                     sample  15174   2.108 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.343           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.845           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.445           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.766           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.227           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.161           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.377           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.462           ms/op
ClientSimple.existUser                      sample  18869   1.695 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.583           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.577           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.126           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.245           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.265           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.797           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.943           ms/op
ClientSimple.getUser                        sample  14826   2.157 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.597           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.052           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.268           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.402           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.663           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.663           ms/op
ClientSimple.listUser                       sample  10317   3.128 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.188           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.892           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.961           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.774           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.152           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.941           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.059           ms/op

Benchmark result is saved to 1711195575469.json
