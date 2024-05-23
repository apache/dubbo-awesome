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
# Warmup Iteration   1: 2.105 ops/ms
Iteration   1: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.203 ops/ms


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
# Warmup Iteration   1: 6.184 ops/ms
Iteration   1: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.780 ops/ms


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
# Warmup Iteration   1: 5.284 ops/ms
Iteration   1: 13.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.281 ops/ms


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
# Warmup Iteration   1: 5.383 ops/ms
Iteration   1: 8.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.352 ops/ms


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.065 ms/op
Iteration   1: 2.180 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.180 ms/op


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
# Warmup Iteration   1: 3.040 ±(99.9%) 0.043 ms/op
Iteration   1: 2.113 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.113 ms/op


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
# Warmup Iteration   1: 3.350 ±(99.9%) 0.058 ms/op
Iteration   1: 2.031 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.031 ms/op


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
# Warmup Iteration   1: 5.560 ±(99.9%) 0.113 ms/op
Iteration   1: 3.546 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.546 ms/op


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
# Warmup Iteration   1: 3.479 ±(99.9%) 0.080 ms/op
Iteration   1: 2.070 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.460 ms/op
                 createUser·p0.50:   1.896 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.810 ms/op
                 createUser·p0.99:   6.564 ms/op
                 createUser·p0.999:  19.988 ms/op
                 createUser·p0.9999: 22.510 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15578
  mean =      2.070 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13785 
    [ 2.500,  5.000) = 1619 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      6.564 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     22.510 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.076 ms/op
Iteration   1: 1.689 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.325 ms/op
                 existUser·p0.50:   1.550 ms/op
                 existUser·p0.90:   2.195 ms/op
                 existUser·p0.95:   2.367 ms/op
                 existUser·p0.99:   3.276 ms/op
                 existUser·p0.999:  16.876 ms/op
                 existUser·p0.9999: 17.007 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18918
  mean =      1.689 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2443 
    [ 1.250,  2.500) = 15893 
    [ 2.500,  3.750) = 442 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.325 ms/op
     p(50.0000) =      1.550 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.367 ms/op
     p(99.0000) =      3.276 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.072 ms/op
Iteration   1: 1.949 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.549 ms/op
                 getUser·p0.50:   1.864 ms/op
                 getUser·p0.90:   2.507 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   3.088 ms/op
                 getUser·p0.999:  13.410 ms/op
                 getUser·p0.9999: 14.877 ms/op
                 getUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16517
  mean =      1.949 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 376 
    [ 1.250,  2.500) = 14448 
    [ 2.500,  3.750) = 1621 
    [ 3.750,  5.000) = 8 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.088 ms/op
     p(99.9000) =     13.410 ms/op
     p(99.9900) =     14.877 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.602 ±(99.9%) 0.140 ms/op
Iteration   1: 3.222 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.556 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  7.157 ms/op
                 listUser·p0.9999: 7.610 ms/op
                 listUser·p1.00:   7.610 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9936
  mean =      3.222 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 6 
    [1.500, 2.000) = 29 
    [2.000, 2.500) = 246 
    [2.500, 3.000) = 5490 
    [3.000, 3.500) = 1699 
    [3.500, 4.000) = 843 
    [4.000, 4.500) = 1040 
    [4.500, 5.000) = 386 
    [5.000, 5.500) = 92 
    [5.500, 6.000) = 47 
    [6.000, 6.500) = 20 
    [6.500, 7.000) = 20 
    [7.000, 7.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.556 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      7.157 ms/op
     p(99.9900) =      7.610 ms/op
     p(99.9990) =      7.610 ms/op
     p(99.9999) =      7.610 ms/op
    p(100.0000) =      7.610 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.203          ops/ms
ClientSimple.existUser                       thrpt         12.780          ops/ms
ClientSimple.getUser                         thrpt         13.281          ops/ms
ClientSimple.listUser                        thrpt          8.352          ops/ms
ClientSimple.createUser                       avgt          2.180           ms/op
ClientSimple.existUser                        avgt          2.113           ms/op
ClientSimple.getUser                          avgt          2.031           ms/op
ClientSimple.listUser                         avgt          3.546           ms/op
ClientSimple.createUser                     sample  15578   2.070 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.460           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.896           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.564           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.988           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.510           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.576           ms/op
ClientSimple.existUser                      sample  18918   1.689 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.325           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.550           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.276           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.876           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.007           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.007           ms/op
ClientSimple.getUser                        sample  16517   1.949 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.549           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.864           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.088           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.410           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.877           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.877           ms/op
ClientSimple.listUser                       sample   9936   3.222 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.141           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.941           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.556           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.530           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.157           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.610           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.610           ms/op

Benchmark result is saved to 1716465982505.json
