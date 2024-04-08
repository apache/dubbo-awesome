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
# Warmup Iteration   1: 1.856 ops/ms
Iteration   1: 6.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.461 ops/ms


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
# Warmup Iteration   1: 6.193 ops/ms
Iteration   1: 12.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.978 ops/ms


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
# Warmup Iteration   1: 5.920 ops/ms
Iteration   1: 13.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.156 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.638 ops/ms
Iteration   1: 9.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.082 ops/ms


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.070 ms/op
Iteration   1: 2.159 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.159 ms/op


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
# Warmup Iteration   1: 3.005 ±(99.9%) 0.042 ms/op
Iteration   1: 1.847 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.847 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.051 ms/op
Iteration   1: 1.822 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.822 ms/op


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.094 ms/op
Iteration   1: 3.597 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.597 ms/op


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
# Warmup Iteration   1: 3.584 ±(99.9%) 0.107 ms/op
Iteration   1: 2.025 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   1.812 ms/op
                 createUser·p0.90:   2.515 ms/op
                 createUser·p0.95:   2.687 ms/op
                 createUser·p0.99:   3.306 ms/op
                 createUser·p0.999:  19.438 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15788
  mean =      2.025 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14103 
    [ 2.500,  5.000) = 1555 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.306 ms/op
     p(99.9000) =     19.438 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 3.642 ±(99.9%) 0.136 ms/op
Iteration   1: 1.998 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   1.851 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  17.203 ms/op
                 existUser·p0.9999: 18.016 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15998
  mean =      1.998 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 366 
    [ 1.250,  2.500) = 13866 
    [ 2.500,  3.750) = 1558 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     18.016 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.135 ±(99.9%) 0.074 ms/op
Iteration   1: 1.743 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   1.614 ms/op
                 getUser·p0.90:   2.261 ms/op
                 getUser·p0.95:   2.478 ms/op
                 getUser·p0.99:   3.701 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 10.002 ms/op
                 getUser·p1.00:   10.125 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18383
  mean =      1.743 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 42 
    [ 1.000,  2.000) = 14812 
    [ 2.000,  3.000) = 3237 
    [ 3.000,  4.000) = 143 
    [ 4.000,  5.000) = 71 
    [ 5.000,  6.000) = 29 
    [ 6.000,  7.000) = 17 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      1.614 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.701 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     10.002 ms/op
     p(99.9990) =     10.125 ms/op
     p(99.9999) =     10.125 ms/op
    p(100.0000) =     10.125 ms/op


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
# Warmup Iteration   1: 4.410 ±(99.9%) 0.140 ms/op
Iteration   1: 3.610 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.571 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   6.851 ms/op
                 listUser·p0.999:  12.468 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8865
  mean =      3.610 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 717 
    [ 2.500,  5.000) = 7798 
    [ 5.000,  7.500) = 278 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.851 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.461          ops/ms
ClientSimple.existUser                       thrpt         12.978          ops/ms
ClientSimple.getUser                         thrpt         13.156          ops/ms
ClientSimple.listUser                        thrpt          9.082          ops/ms
ClientSimple.createUser                       avgt          2.159           ms/op
ClientSimple.existUser                        avgt          1.847           ms/op
ClientSimple.getUser                          avgt          1.822           ms/op
ClientSimple.listUser                         avgt          3.597           ms/op
ClientSimple.createUser                     sample  15788   2.025 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.744           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.812           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.515           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.306           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.438           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.724           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.724           ms/op
ClientSimple.existUser                      sample  15998   1.998 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.503           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.851           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.760           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.203           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.016           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.055           ms/op
ClientSimple.getUser                        sample  18383   1.743 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.727           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.614           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.261           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.701           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.290           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.002           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.125           ms/op
ClientSimple.listUser                       sample   8865   3.610 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.571           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.596           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.882           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.851           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.468           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.775           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.775           ms/op

Benchmark result is saved to 1712556344879.json
