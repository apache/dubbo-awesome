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
# Warmup Iteration   1: 1.396 ops/ms
Iteration   1: 6.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.309 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.088 ops/ms
Iteration   1: 8.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  8.794 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.233 ops/ms
Iteration   1: 12.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.756 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.051 ops/ms
Iteration   1: 8.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.066 ops/ms


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.092 ms/op
Iteration   1: 2.382 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.382 ms/op


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.067 ms/op
Iteration   1: 2.183 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.183 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.060 ms/op
Iteration   1: 2.176 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.176 ms/op


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
# Warmup Iteration   1: 5.063 ±(99.9%) 0.122 ms/op
Iteration   1: 3.676 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.676 ms/op


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.085 ms/op
Iteration   1: 2.356 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   2.085 ms/op
                 createUser·p0.90:   2.716 ms/op
                 createUser·p0.95:   3.334 ms/op
                 createUser·p0.99:   12.249 ms/op
                 createUser·p0.999:  23.495 ms/op
                 createUser·p0.9999: 30.169 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13559
  mean =      2.356 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11466 
    [ 2.500,  5.000) = 1670 
    [ 5.000,  7.500) = 218 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      3.334 ms/op
     p(99.0000) =     12.249 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     30.169 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 2.959 ±(99.9%) 0.070 ms/op
Iteration   1: 1.754 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   1.612 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   3.342 ms/op
                 existUser·p0.999:  10.872 ms/op
                 existUser·p0.9999: 11.595 ms/op
                 existUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18200
  mean =      1.754 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 517 
    [ 1.250,  2.500) = 16526 
    [ 2.500,  3.750) = 1049 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      1.612 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.342 ms/op
     p(99.9000) =     10.872 ms/op
     p(99.9900) =     11.595 ms/op
     p(99.9990) =     11.649 ms/op
     p(99.9999) =     11.649 ms/op
    p(100.0000) =     11.649 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.089 ms/op
Iteration   1: 1.858 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.381 ms/op
                 getUser·p0.50:   1.718 ms/op
                 getUser·p0.90:   2.257 ms/op
                 getUser·p0.95:   2.466 ms/op
                 getUser·p0.99:   3.167 ms/op
                 getUser·p0.999:  30.409 ms/op
                 getUser·p0.9999: 30.984 ms/op
                 getUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17178
  mean =      1.858 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16397 
    [ 2.500,  5.000) = 717 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.381 ms/op
     p(50.0000) =      1.718 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.167 ms/op
     p(99.9000) =     30.409 ms/op
     p(99.9900) =     30.984 ms/op
     p(99.9990) =     31.031 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 4.958 ±(99.9%) 0.136 ms/op
Iteration   1: 3.817 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.523 ms/op
                 listUser·p0.999:  17.014 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8384
  mean =      3.817 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 577 
    [ 2.500,  3.750) = 3205 
    [ 3.750,  5.000) = 4248 
    [ 5.000,  6.250) = 241 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.523 ms/op
     p(99.9000) =     17.014 ms/op
     p(99.9900) =     17.138 ms/op
     p(99.9990) =     17.138 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.309          ops/ms
ClientSimple.existUser                       thrpt          8.794          ops/ms
ClientSimple.getUser                         thrpt         12.756          ops/ms
ClientSimple.listUser                        thrpt          8.066          ops/ms
ClientSimple.createUser                       avgt          2.382           ms/op
ClientSimple.existUser                        avgt          2.183           ms/op
ClientSimple.getUser                          avgt          2.176           ms/op
ClientSimple.listUser                         avgt          3.676           ms/op
ClientSimple.createUser                     sample  13559   2.356 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.896           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.085           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.334           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.249           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.495           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.169           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.671           ms/op
ClientSimple.existUser                      sample  18200   1.754 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.829           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.612           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.342           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.872           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.595           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.649           ms/op
ClientSimple.getUser                        sample  17178   1.858 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.381           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.718           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.257           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.167           ms/op
ClientSimple.getUser:getUser·p0.999         sample         30.409           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.984           ms/op
ClientSimple.getUser:getUser·p1.00          sample         31.031           ms/op
ClientSimple.listUser                       sample   8384   3.817 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.178           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.830           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.523           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.014           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.138           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.138           ms/op

Benchmark result is saved to 1713572095297.json
