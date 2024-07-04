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
# Warmup Iteration   1: 1.588 ops/ms
Iteration   1: 6.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.700 ops/ms


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
# Warmup Iteration   1: 5.927 ops/ms
Iteration   1: 12.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.322 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.198 ops/ms
Iteration   1: 12.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.082 ops/ms


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
# Warmup Iteration   1: 4.000 ops/ms
Iteration   1: 9.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.100 ops/ms


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.081 ms/op
Iteration   1: 2.342 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.342 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.055 ms/op
Iteration   1: 2.187 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.187 ms/op


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
# Warmup Iteration   1: 3.376 ±(99.9%) 0.061 ms/op
Iteration   1: 1.928 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.928 ms/op


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.143 ms/op
Iteration   1: 3.764 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.764 ms/op


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
# Warmup Iteration   1: 3.630 ±(99.9%) 0.104 ms/op
Iteration   1: 2.461 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   0.540 ms/op
                 createUser·p0.50:   2.228 ms/op
                 createUser·p0.90:   2.871 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  42.985 ms/op
                 createUser·p0.9999: 43.516 ms/op
                 createUser·p1.00:   43.516 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13052
  mean =      2.461 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12739 
    [ 5.000, 10.000) = 219 
    [10.000, 15.000) = 30 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.228 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     42.985 ms/op
     p(99.9900) =     43.516 ms/op
     p(99.9990) =     43.516 ms/op
     p(99.9999) =     43.516 ms/op
    p(100.0000) =     43.516 ms/op


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
# Warmup Iteration   1: 2.774 ±(99.9%) 0.068 ms/op
Iteration   1: 1.743 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   1.583 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.441 ms/op
                 existUser·p0.99:   3.656 ms/op
                 existUser·p0.999:  14.664 ms/op
                 existUser·p0.9999: 14.849 ms/op
                 existUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18352
  mean =      1.743 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1400 
    [ 1.250,  2.500) = 16173 
    [ 2.500,  3.750) = 604 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.583 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      3.656 ms/op
     p(99.9000) =     14.664 ms/op
     p(99.9900) =     14.849 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.106 ms/op
Iteration   1: 1.994 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   1.913 ms/op
                 getUser·p0.90:   2.327 ms/op
                 getUser·p0.95:   2.503 ms/op
                 getUser·p0.99:   3.359 ms/op
                 getUser·p0.999:  12.301 ms/op
                 getUser·p0.9999: 13.919 ms/op
                 getUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16071
  mean =      1.994 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 15204 
    [ 2.500,  3.750) = 709 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.359 ms/op
     p(99.9000) =     12.301 ms/op
     p(99.9900) =     13.919 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 4.608 ±(99.9%) 0.127 ms/op
Iteration   1: 4.008 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   7.868 ms/op
                 listUser·p0.999:  24.738 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8057
  mean =      4.008 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 461 
    [ 2.500,  5.000) = 7133 
    [ 5.000,  7.500) = 367 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.868 ms/op
     p(99.9000) =     24.738 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.700          ops/ms
ClientSimple.existUser                       thrpt         12.322          ops/ms
ClientSimple.getUser                         thrpt         12.082          ops/ms
ClientSimple.listUser                        thrpt          9.100          ops/ms
ClientSimple.createUser                       avgt          2.342           ms/op
ClientSimple.existUser                        avgt          2.187           ms/op
ClientSimple.getUser                          avgt          1.928           ms/op
ClientSimple.listUser                         avgt          3.764           ms/op
ClientSimple.createUser                     sample  13052   2.461 ± 0.061   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.540           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.228           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.162           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.496           ms/op
ClientSimple.createUser:createUser·p0.999   sample         42.985           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         43.516           ms/op
ClientSimple.createUser:createUser·p1.00    sample         43.516           ms/op
ClientSimple.existUser                      sample  18352   1.743 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.539           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.583           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.265           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.656           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.664           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.849           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.877           ms/op
ClientSimple.getUser                        sample  16071   1.994 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.907           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.913           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.327           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.359           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.301           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.919           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.959           ms/op
ClientSimple.listUser                       sample   8057   4.008 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.027           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.990           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.104           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.868           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.738           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.494           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.494           ms/op

Benchmark result is saved to 1720116328904.json
