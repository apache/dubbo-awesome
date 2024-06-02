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
# Warmup Iteration   1: 1.843 ops/ms
Iteration   1: 7.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.192 ops/ms


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
# Warmup Iteration   1: 7.420 ops/ms
Iteration   1: 13.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.699 ops/ms


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
# Warmup Iteration   1: 6.500 ops/ms
Iteration   1: 13.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.213 ops/ms


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
# Warmup Iteration   1: 6.032 ops/ms
Iteration   1: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.301 ops/ms


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.070 ms/op
Iteration   1: 2.227 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.227 ms/op


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
# Warmup Iteration   1: 3.125 ±(99.9%) 0.048 ms/op
Iteration   1: 1.877 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.877 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.075 ms/op
Iteration   1: 2.124 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.124 ms/op


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
# Warmup Iteration   1: 4.531 ±(99.9%) 0.075 ms/op
Iteration   1: 3.421 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.421 ms/op


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.245 ms/op
Iteration   1: 1.984 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   1.823 ms/op
                 createUser·p0.90:   2.482 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   5.553 ms/op
                 createUser·p0.999:  14.727 ms/op
                 createUser·p0.9999: 14.817 ms/op
                 createUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16116
  mean =      1.984 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 383 
    [ 1.250,  2.500) = 14173 
    [ 2.500,  3.750) = 1285 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      5.553 ms/op
     p(99.9000) =     14.727 ms/op
     p(99.9900) =     14.817 ms/op
     p(99.9990) =     14.828 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.077 ms/op
Iteration   1: 1.753 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   1.726 ms/op
                 existUser·p0.90:   2.175 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   2.822 ms/op
                 existUser·p0.999:  5.785 ms/op
                 existUser·p0.9999: 7.262 ms/op
                 existUser·p1.00:   7.356 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18251
  mean =      1.753 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 37 
    [1.000, 1.500) = 5455 
    [1.500, 2.000) = 8860 
    [2.000, 2.500) = 3433 
    [2.500, 3.000) = 329 
    [3.000, 3.500) = 23 
    [3.500, 4.000) = 29 
    [4.000, 4.500) = 16 
    [4.500, 5.000) = 31 
    [5.000, 5.500) = 19 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 8 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.175 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      2.822 ms/op
     p(99.9000) =      5.785 ms/op
     p(99.9900) =      7.262 ms/op
     p(99.9990) =      7.356 ms/op
     p(99.9999) =      7.356 ms/op
    p(100.0000) =      7.356 ms/op


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
# Warmup Iteration   1: 3.304 ±(99.9%) 0.088 ms/op
Iteration   1: 2.382 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.466 ms/op
                 getUser·p0.50:   2.417 ms/op
                 getUser·p0.90:   2.777 ms/op
                 getUser·p0.95:   2.925 ms/op
                 getUser·p0.99:   3.178 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 12.631 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13508
  mean =      2.382 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 7742 
    [ 2.500,  3.750) = 5543 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      2.417 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      3.178 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     12.631 ms/op
     p(99.9990) =     12.648 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


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
# Warmup Iteration   1: 4.610 ±(99.9%) 0.149 ms/op
Iteration   1: 3.286 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.694 ms/op
                 listUser·p0.50:   3.207 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.582 ms/op
                 listUser·p0.999:  6.740 ms/op
                 listUser·p0.9999: 8.503 ms/op
                 listUser·p1.00:   8.503 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9756
  mean =      3.286 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 10 
    [1.000, 1.500) = 20 
    [1.500, 2.000) = 158 
    [2.000, 2.500) = 876 
    [2.500, 3.000) = 2704 
    [3.000, 3.500) = 2433 
    [3.500, 4.000) = 2151 
    [4.000, 4.500) = 1017 
    [4.500, 5.000) = 152 
    [5.000, 5.500) = 125 
    [5.500, 6.000) = 61 
    [6.000, 6.500) = 26 
    [6.500, 7.000) = 15 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.582 ms/op
     p(99.9000) =      6.740 ms/op
     p(99.9900) =      8.503 ms/op
     p(99.9990) =      8.503 ms/op
     p(99.9999) =      8.503 ms/op
    p(100.0000) =      8.503 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.192          ops/ms
ClientSimple.existUser                       thrpt         13.699          ops/ms
ClientSimple.getUser                         thrpt         13.213          ops/ms
ClientSimple.listUser                        thrpt          8.301          ops/ms
ClientSimple.createUser                       avgt          2.227           ms/op
ClientSimple.existUser                        avgt          1.877           ms/op
ClientSimple.getUser                          avgt          2.124           ms/op
ClientSimple.listUser                         avgt          3.421           ms/op
ClientSimple.createUser                     sample  16116   1.984 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.670           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.823           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.482           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.553           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.727           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.817           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.828           ms/op
ClientSimple.existUser                      sample  18251   1.753 ± 0.010   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.604           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.726           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.175           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.822           ms/op
ClientSimple.existUser:existUser·p0.999     sample          5.785           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          7.262           ms/op
ClientSimple.existUser:existUser·p1.00      sample          7.356           ms/op
ClientSimple.getUser                        sample  13508   2.382 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.466           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.925           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.178           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.059           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.631           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.648           ms/op
ClientSimple.listUser                       sample   9756   3.286 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.694           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.207           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.582           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.740           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.503           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.503           ms/op

Benchmark result is saved to 1717287422789.json
