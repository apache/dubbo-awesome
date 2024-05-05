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
# Warmup Iteration   1: 1.714 ops/ms
Iteration   1: 6.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.656 ops/ms


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
# Warmup Iteration   1: 6.555 ops/ms
Iteration   1: 12.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.685 ops/ms


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
# Warmup Iteration   1: 5.487 ops/ms
Iteration   1: 11.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.158 ops/ms


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
# Warmup Iteration   1: 4.928 ops/ms
Iteration   1: 8.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.848 ops/ms


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.070 ms/op
Iteration   1: 2.164 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.164 ms/op


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
# Warmup Iteration   1: 3.026 ±(99.9%) 0.049 ms/op
Iteration   1: 1.978 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.978 ms/op


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
# Warmup Iteration   1: 3.233 ±(99.9%) 0.062 ms/op
Iteration   1: 2.034 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.034 ms/op


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.077 ms/op
Iteration   1: 3.246 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.246 ms/op


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
# Warmup Iteration   1: 3.391 ±(99.9%) 0.075 ms/op
Iteration   1: 2.256 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.781 ms/op
                 createUser·p0.95:   3.043 ms/op
                 createUser·p0.99:   6.408 ms/op
                 createUser·p0.999:  15.529 ms/op
                 createUser·p0.9999: 17.581 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14188
  mean =      2.256 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 10595 
    [ 2.500,  3.750) = 3266 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      6.408 ms/op
     p(99.9000) =     15.529 ms/op
     p(99.9900) =     17.581 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.085 ms/op
Iteration   1: 2.257 ±(99.9%) 0.045 ms/op
                 existUser·p0.00:   0.447 ms/op
                 existUser·p0.50:   2.146 ms/op
                 existUser·p0.90:   2.650 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  27.613 ms/op
                 existUser·p0.9999: 28.506 ms/op
                 existUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14160
  mean =      2.257 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11696 
    [ 2.500,  5.000) = 2311 
    [ 5.000,  7.500) = 57 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     27.613 ms/op
     p(99.9900) =     28.506 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.098 ms/op
Iteration   1: 2.121 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   2.036 ms/op
                 getUser·p0.90:   2.490 ms/op
                 getUser·p0.95:   2.728 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  12.943 ms/op
                 getUser·p0.9999: 13.785 ms/op
                 getUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15100
  mean =      2.121 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 13586 
    [ 2.500,  3.750) = 1281 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     13.785 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.132 ms/op
Iteration   1: 3.381 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.305 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.005 ms/op
                 listUser·p0.999:  21.496 ms/op
                 listUser·p0.9999: 21.955 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9504
  mean =      3.381 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1131 
    [ 2.500,  5.000) = 8092 
    [ 5.000,  7.500) = 246 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     21.496 ms/op
     p(99.9900) =     21.955 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.656          ops/ms
ClientSimple.existUser                       thrpt         12.685          ops/ms
ClientSimple.getUser                         thrpt         11.158          ops/ms
ClientSimple.listUser                        thrpt          8.848          ops/ms
ClientSimple.createUser                       avgt          2.164           ms/op
ClientSimple.existUser                        avgt          1.978           ms/op
ClientSimple.getUser                          avgt          2.034           ms/op
ClientSimple.listUser                         avgt          3.246           ms/op
ClientSimple.createUser                     sample  14188   2.256 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.894           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.043           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.408           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.529           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.581           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.514           ms/op
ClientSimple.existUser                      sample  14160   2.257 ± 0.045   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.447           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.146           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.027           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.128           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.613           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.506           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.574           ms/op
ClientSimple.getUser                        sample  15100   2.121 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.791           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.036           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.834           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.943           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.785           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.910           ms/op
ClientSimple.listUser                       sample   9504   3.381 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.069           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.305           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.005           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.496           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.955           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.955           ms/op

Benchmark result is saved to 1714889084997.json
