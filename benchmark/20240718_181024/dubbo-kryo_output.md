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
# Warmup Iteration   1: 1.591 ops/ms
Iteration   1: 7.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.867 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.945 ops/ms
Iteration   1: 12.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.037 ops/ms


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
# Warmup Iteration   1: 5.326 ops/ms
Iteration   1: 13.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.430 ops/ms


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
# Warmup Iteration   1: 3.889 ops/ms
Iteration   1: 8.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.876 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.126 ±(99.9%) 0.092 ms/op
Iteration   1: 2.394 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.394 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.149 ±(99.9%) 0.068 ms/op
Iteration   1: 1.779 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.779 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.185 ±(99.9%) 0.054 ms/op
Iteration   1: 2.094 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.094 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.021 ±(99.9%) 0.126 ms/op
Iteration   1: 3.103 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.103 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.103 ms/op
Iteration   1: 2.503 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.594 ms/op
                 createUser·p0.50:   2.367 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.363 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  19.659 ms/op
                 createUser·p0.9999: 20.896 ms/op
                 createUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13020
  mean =      2.503 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7850 
    [ 2.500,  5.000) = 4987 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      2.367 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.363 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     19.659 ms/op
     p(99.9900) =     20.896 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 3.019 ±(99.9%) 0.074 ms/op
Iteration   1: 1.937 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.384 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   4.045 ms/op
                 existUser·p0.999:  20.390 ms/op
                 existUser·p0.9999: 20.577 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16750
  mean =      1.937 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15739 
    [ 2.500,  5.000) = 896 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      4.045 ms/op
     p(99.9000) =     20.390 ms/op
     p(99.9900) =     20.577 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 3.518 ±(99.9%) 0.098 ms/op
Iteration   1: 1.951 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.668 ms/op
                 getUser·p0.50:   1.726 ms/op
                 getUser·p0.90:   2.499 ms/op
                 getUser·p0.95:   2.753 ms/op
                 getUser·p0.99:   4.338 ms/op
                 getUser·p0.999:  16.861 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16447
  mean =      1.951 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 186 
    [ 1.250,  2.500) = 14623 
    [ 2.500,  3.750) = 1417 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      4.338 ms/op
     p(99.9000) =     16.861 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.883 ±(99.9%) 0.163 ms/op
Iteration   1: 3.481 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.774 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.722 ms/op
                 listUser·p0.99:   6.893 ms/op
                 listUser·p0.999:  14.576 ms/op
                 listUser·p0.9999: 14.762 ms/op
                 listUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9351
  mean =      3.481 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 1808 
    [ 2.500,  3.750) = 4073 
    [ 3.750,  5.000) = 3100 
    [ 5.000,  6.250) = 213 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.722 ms/op
     p(99.0000) =      6.893 ms/op
     p(99.9000) =     14.576 ms/op
     p(99.9900) =     14.762 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.867          ops/ms
ClientSimple.existUser                       thrpt         12.037          ops/ms
ClientSimple.getUser                         thrpt         13.430          ops/ms
ClientSimple.listUser                        thrpt          8.876          ops/ms
ClientSimple.createUser                       avgt          2.394           ms/op
ClientSimple.existUser                        avgt          1.779           ms/op
ClientSimple.getUser                          avgt          2.094           ms/op
ClientSimple.listUser                         avgt          3.103           ms/op
ClientSimple.createUser                     sample  13020   2.503 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.594           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.367           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.117           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.363           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.177           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.659           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.896           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.906           ms/op
ClientSimple.existUser                      sample  16750   1.937 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.521           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.761           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.045           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.390           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.577           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.644           ms/op
ClientSimple.getUser                        sample  16447   1.951 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.668           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.726           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.338           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.861           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.974           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.974           ms/op
ClientSimple.listUser                       sample   9351   3.481 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.774           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.486           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.722           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.893           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.576           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.762           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.762           ms/op

Benchmark result is saved to 1721325970939.json
