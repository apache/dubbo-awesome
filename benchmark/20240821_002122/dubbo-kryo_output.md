# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.791 ops/ms
Iteration   1: 6.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.772 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.124 ops/ms
Iteration   1: 11.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.330 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.005 ops/ms
Iteration   1: 13.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.331 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.311 ops/ms
Iteration   1: 8.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.877 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.564 ±(99.9%) 0.057 ms/op
Iteration   1: 2.011 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.011 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.525 ±(99.9%) 0.053 ms/op
Iteration   1: 2.016 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.016 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.530 ±(99.9%) 0.072 ms/op
Iteration   1: 2.297 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.297 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.024 ±(99.9%) 0.086 ms/op
Iteration   1: 3.743 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.743 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.490 ±(99.9%) 0.095 ms/op
Iteration   1: 2.425 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.309 ms/op
                 createUser·p0.50:   2.310 ms/op
                 createUser·p0.90:   2.904 ms/op
                 createUser·p0.95:   3.394 ms/op
                 createUser·p0.99:   5.884 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 17.732 ms/op
                 createUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13185
  mean =      2.425 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 218 
    [ 1.250,  2.500) = 8508 
    [ 2.500,  3.750) = 3933 
    [ 3.750,  5.000) = 278 
    [ 5.000,  6.250) = 121 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.309 ms/op
     p(50.0000) =      2.310 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.394 ms/op
     p(99.0000) =      5.884 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     17.732 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.104 ±(99.9%) 0.082 ms/op
Iteration   1: 1.693 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.707 ms/op
                 existUser·p0.50:   1.567 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   3.082 ms/op
                 existUser·p0.999:  21.255 ms/op
                 existUser·p0.9999: 21.806 ms/op
                 existUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18870
  mean =      1.693 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18388 
    [ 2.500,  5.000) = 324 
    [ 5.000,  7.500) = 62 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      1.567 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      3.082 ms/op
     p(99.9000) =     21.255 ms/op
     p(99.9900) =     21.806 ms/op
     p(99.9990) =     21.922 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.763 ±(99.9%) 0.089 ms/op
Iteration   1: 1.984 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   1.888 ms/op
                 getUser·p0.90:   2.515 ms/op
                 getUser·p0.95:   2.789 ms/op
                 getUser·p0.99:   3.273 ms/op
                 getUser·p0.999:  15.907 ms/op
                 getUser·p0.9999: 16.040 ms/op
                 getUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16108
  mean =      1.984 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 14244 
    [ 2.500,  3.750) = 1611 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.273 ms/op
     p(99.9000) =     15.907 ms/op
     p(99.9900) =     16.040 ms/op
     p(99.9990) =     16.040 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ±(99.9%) 0.156 ms/op
Iteration   1: 3.653 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  6.958 ms/op
                 listUser·p0.9999: 7.528 ms/op
                 listUser·p1.00:   7.528 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8904
  mean =      3.653 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 14 
    [1.500, 2.000) = 64 
    [2.000, 2.500) = 475 
    [2.500, 3.000) = 1585 
    [3.000, 3.500) = 1528 
    [3.500, 4.000) = 2646 
    [4.000, 4.500) = 1633 
    [4.500, 5.000) = 433 
    [5.000, 5.500) = 241 
    [5.500, 6.000) = 126 
    [6.000, 6.500) = 46 
    [6.500, 7.000) = 105 
    [7.000, 7.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =      6.958 ms/op
     p(99.9900) =      7.528 ms/op
     p(99.9990) =      7.528 ms/op
     p(99.9999) =      7.528 ms/op
    p(100.0000) =      7.528 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.772          ops/ms
ClientSimple.existUser                       thrpt         11.330          ops/ms
ClientSimple.getUser                         thrpt         13.331          ops/ms
ClientSimple.listUser                        thrpt          8.877          ops/ms
ClientSimple.createUser                       avgt          2.011           ms/op
ClientSimple.existUser                        avgt          2.016           ms/op
ClientSimple.getUser                          avgt          2.297           ms/op
ClientSimple.listUser                         avgt          3.743           ms/op
ClientSimple.createUser                     sample  13185   2.425 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.309           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.310           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.394           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.884           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.203           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.732           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.826           ms/op
ClientSimple.existUser                      sample  18870   1.693 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.707           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.567           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.126           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.082           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.255           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.806           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.922           ms/op
ClientSimple.getUser                        sample  16108   1.984 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.926           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.888           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.273           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.907           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.040           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.040           ms/op
ClientSimple.listUser                       sample   8904   3.653 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.940           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.695           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.153           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.562           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.958           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.528           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.528           ms/op

Benchmark result is saved to 1724199406885.json
