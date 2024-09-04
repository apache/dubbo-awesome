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
# Warmup Iteration   1: 2.073 ops/ms
Iteration   1: 6.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.744 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.824 ops/ms
Iteration   1: 12.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.319 ops/ms


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
# Warmup Iteration   1: 6.105 ops/ms
Iteration   1: 13.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.394 ops/ms


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
# Warmup Iteration   1: 4.144 ops/ms
Iteration   1: 7.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.740 ops/ms


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
# Warmup Iteration   1: 4.730 ±(99.9%) 0.086 ms/op
Iteration   1: 2.428 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.428 ms/op


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
# Warmup Iteration   1: 3.589 ±(99.9%) 0.059 ms/op
Iteration   1: 1.929 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.929 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.049 ms/op
Iteration   1: 1.944 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.944 ms/op


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
# Warmup Iteration   1: 4.566 ±(99.9%) 0.076 ms/op
Iteration   1: 3.380 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.380 ms/op


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
# Warmup Iteration   1: 3.451 ±(99.9%) 0.082 ms/op
Iteration   1: 2.159 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.060 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   2.859 ms/op
                 createUser·p0.99:   4.690 ms/op
                 createUser·p0.999:  17.985 ms/op
                 createUser·p0.9999: 18.903 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15142
  mean =      2.159 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 13052 
    [ 2.500,  3.750) = 1747 
    [ 3.750,  5.000) = 141 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      4.690 ms/op
     p(99.9000) =     17.985 ms/op
     p(99.9900) =     18.903 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 3.023 ±(99.9%) 0.076 ms/op
Iteration   1: 2.108 ±(99.9%) 0.070 ms/op
                 existUser·p0.00:   0.423 ms/op
                 existUser·p0.50:   1.944 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   5.233 ms/op
                 existUser·p0.999:  49.420 ms/op
                 existUser·p0.9999: 83.153 ms/op
                 existUser·p1.00:   83.231 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15911
  mean =      2.108 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15714 
    [ 5.000, 10.000) = 103 
    [10.000, 15.000) = 36 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 6 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 2 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 0 
    [75.000, 80.000) = 1 
    [80.000, 85.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      5.233 ms/op
     p(99.9000) =     49.420 ms/op
     p(99.9900) =     83.153 ms/op
     p(99.9990) =     83.231 ms/op
     p(99.9999) =     83.231 ms/op
    p(100.0000) =     83.231 ms/op


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.243 ms/op
Iteration   1: 2.039 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   1.868 ms/op
                 getUser·p0.90:   2.507 ms/op
                 getUser·p0.95:   2.740 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  16.503 ms/op
                 getUser·p0.9999: 17.420 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15990
  mean =      2.039 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 14278 
    [ 2.500,  3.750) = 1368 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =     16.503 ms/op
     p(99.9900) =     17.420 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 4.789 ±(99.9%) 0.141 ms/op
Iteration   1: 3.458 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   3.457 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.942 ms/op
                 listUser·p0.999:  7.826 ms/op
                 listUser·p0.9999: 8.946 ms/op
                 listUser·p1.00:   8.946 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9327
  mean =      3.458 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 5 
    [1.000, 1.500) = 23 
    [1.500, 2.000) = 55 
    [2.000, 2.500) = 551 
    [2.500, 3.000) = 2612 
    [3.000, 3.500) = 1570 
    [3.500, 4.000) = 2552 
    [4.000, 4.500) = 1416 
    [4.500, 5.000) = 298 
    [5.000, 5.500) = 68 
    [5.500, 6.000) = 47 
    [6.000, 6.500) = 27 
    [6.500, 7.000) = 14 
    [7.000, 7.500) = 50 
    [7.500, 8.000) = 37 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.942 ms/op
     p(99.9000) =      7.826 ms/op
     p(99.9900) =      8.946 ms/op
     p(99.9990) =      8.946 ms/op
     p(99.9999) =      8.946 ms/op
    p(100.0000) =      8.946 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.744          ops/ms
ClientSimple.existUser                       thrpt         12.319          ops/ms
ClientSimple.getUser                         thrpt         13.394          ops/ms
ClientSimple.listUser                        thrpt          7.740          ops/ms
ClientSimple.createUser                       avgt          2.428           ms/op
ClientSimple.existUser                        avgt          1.929           ms/op
ClientSimple.getUser                          avgt          1.944           ms/op
ClientSimple.listUser                         avgt          3.380           ms/op
ClientSimple.createUser                     sample  15142   2.159 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.959           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.060           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.859           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.690           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.985           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.903           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.038           ms/op
ClientSimple.existUser                      sample  15911   2.108 ± 0.070   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.423           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.944           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.233           ms/op
ClientSimple.existUser:existUser·p0.999     sample         49.420           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         83.153           ms/op
ClientSimple.existUser:existUser·p1.00      sample         83.231           ms/op
ClientSimple.getUser                        sample  15990   2.039 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.681           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.868           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.038           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.503           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.420           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.891           ms/op
ClientSimple.listUser                       sample   9327   3.458 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.800           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.457           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.563           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.942           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.826           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.946           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.946           ms/op

Benchmark result is saved to 1725429978209.json
