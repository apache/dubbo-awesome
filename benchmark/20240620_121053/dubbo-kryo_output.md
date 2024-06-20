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
# Warmup Iteration   1: 1.708 ops/ms
Iteration   1: 7.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.002 ops/ms


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
# Warmup Iteration   1: 5.874 ops/ms
Iteration   1: 13.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.155 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.540 ops/ms
Iteration   1: 13.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.855 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.300 ops/ms
Iteration   1: 9.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.063 ops/ms


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.059 ms/op
Iteration   1: 1.903 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.903 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.048 ms/op
Iteration   1: 2.092 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.092 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.056 ±(99.9%) 0.045 ms/op
Iteration   1: 1.955 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.955 ms/op


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.077 ms/op
Iteration   1: 3.255 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.255 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.616 ±(99.9%) 0.118 ms/op
Iteration   1: 2.274 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.518 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.839 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   7.575 ms/op
                 createUser·p0.999:  17.138 ms/op
                 createUser·p0.9999: 17.439 ms/op
                 createUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14062
  mean =      2.274 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 282 
    [ 1.250,  2.500) = 10534 
    [ 2.500,  3.750) = 2862 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      7.575 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     17.439 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.832 ±(99.9%) 0.066 ms/op
Iteration   1: 1.596 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.504 ms/op
                 existUser·p0.50:   1.468 ms/op
                 existUser·p0.90:   2.013 ms/op
                 existUser·p0.95:   2.241 ms/op
                 existUser·p0.99:   3.639 ms/op
                 existUser·p0.999:  11.714 ms/op
                 existUser·p0.9999: 12.173 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 20033
  mean =      1.596 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1217 
    [ 1.250,  2.500) = 18384 
    [ 2.500,  3.750) = 288 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      1.468 ms/op
     p(90.0000) =      2.013 ms/op
     p(95.0000) =      2.241 ms/op
     p(99.0000) =      3.639 ms/op
     p(99.9000) =     11.714 ms/op
     p(99.9900) =     12.173 ms/op
     p(99.9990) =     12.501 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.936 ±(99.9%) 0.081 ms/op
Iteration   1: 2.032 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.646 ms/op
                 getUser·p0.99:   3.491 ms/op
                 getUser·p0.999:  18.307 ms/op
                 getUser·p0.9999: 19.263 ms/op
                 getUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15773
  mean =      2.032 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 271 
    [ 1.250,  2.500) = 14065 
    [ 2.500,  3.750) = 1322 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      3.491 ms/op
     p(99.9000) =     18.307 ms/op
     p(99.9900) =     19.263 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ±(99.9%) 0.104 ms/op
Iteration   1: 3.397 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   3.375 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.217 ms/op
                 listUser·p0.999:  9.266 ms/op
                 listUser·p0.9999: 9.322 ms/op
                 listUser·p1.00:   9.322 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9417
  mean =      3.397 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 55 
    [ 2.000,  3.000) = 3238 
    [ 3.000,  4.000) = 4419 
    [ 4.000,  5.000) = 1565 
    [ 5.000,  6.000) = 104 
    [ 6.000,  7.000) = 3 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.217 ms/op
     p(99.9000) =      9.266 ms/op
     p(99.9900) =      9.322 ms/op
     p(99.9990) =      9.322 ms/op
     p(99.9999) =      9.322 ms/op
    p(100.0000) =      9.322 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.002          ops/ms
ClientSimple.existUser                       thrpt         13.155          ops/ms
ClientSimple.getUser                         thrpt         13.855          ops/ms
ClientSimple.listUser                        thrpt          9.063          ops/ms
ClientSimple.createUser                       avgt          1.903           ms/op
ClientSimple.existUser                        avgt          2.092           ms/op
ClientSimple.getUser                          avgt          1.955           ms/op
ClientSimple.listUser                         avgt          3.255           ms/op
ClientSimple.createUser                     sample  14062   2.274 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.518           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.138           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.575           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.138           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.439           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.465           ms/op
ClientSimple.existUser                      sample  20033   1.596 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.504           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.468           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.013           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.639           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.714           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.173           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.501           ms/op
ClientSimple.getUser                        sample  15773   2.032 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.755           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.491           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.307           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.263           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.300           ms/op
ClientSimple.listUser                       sample   9417   3.397 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.987           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.375           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.217           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.266           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.322           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.322           ms/op

Benchmark result is saved to 1718885210437.json
