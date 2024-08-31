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
# Warmup Iteration   1: 1.831 ops/ms
Iteration   1: 7.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.942 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.569 ops/ms
Iteration   1: 12.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.796 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.479 ops/ms
Iteration   1: 11.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.783 ops/ms


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
# Warmup Iteration   1: 5.210 ops/ms
Iteration   1: 8.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.866 ops/ms


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
# Warmup Iteration   1: 3.574 ±(99.9%) 0.066 ms/op
Iteration   1: 2.361 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.361 ms/op


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
# Warmup Iteration   1: 3.191 ±(99.9%) 0.048 ms/op
Iteration   1: 1.990 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.990 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.055 ms/op
Iteration   1: 1.964 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.964 ms/op


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.090 ms/op
Iteration   1: 3.273 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.273 ms/op


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
# Warmup Iteration   1: 4.503 ±(99.9%) 0.160 ms/op
Iteration   1: 2.184 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   1.929 ms/op
                 createUser·p0.90:   2.646 ms/op
                 createUser·p0.95:   3.322 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  18.918 ms/op
                 createUser·p0.9999: 21.710 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14653
  mean =      2.184 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12770 
    [ 2.500,  5.000) = 1636 
    [ 5.000,  7.500) = 109 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      3.322 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     18.918 ms/op
     p(99.9900) =     21.710 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.079 ms/op
Iteration   1: 1.882 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   1.819 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.503 ms/op
                 existUser·p0.99:   3.138 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 13.342 ms/op
                 existUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16984
  mean =      1.882 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 805 
    [ 1.250,  2.500) = 15321 
    [ 2.500,  3.750) = 742 
    [ 3.750,  5.000) = 9 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.138 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     13.342 ms/op
     p(99.9990) =     13.353 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


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
# Warmup Iteration   1: 3.233 ±(99.9%) 0.091 ms/op
Iteration   1: 2.237 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   2.142 ms/op
                 getUser·p0.90:   2.777 ms/op
                 getUser·p0.95:   2.970 ms/op
                 getUser·p0.99:   5.033 ms/op
                 getUser·p0.999:  13.173 ms/op
                 getUser·p0.9999: 17.077 ms/op
                 getUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14317
  mean =      2.237 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 10865 
    [ 2.500,  3.750) = 3135 
    [ 3.750,  5.000) = 107 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.142 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      5.033 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     17.077 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 5.060 ±(99.9%) 0.144 ms/op
Iteration   1: 3.434 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   0.627 ms/op
                 listUser·p0.50:   3.232 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  18.279 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9307
  mean =      3.434 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1096 
    [ 2.500,  5.000) = 7693 
    [ 5.000,  7.500) = 394 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     18.279 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.942          ops/ms
ClientSimple.existUser                       thrpt         12.796          ops/ms
ClientSimple.getUser                         thrpt         11.783          ops/ms
ClientSimple.listUser                        thrpt          8.866          ops/ms
ClientSimple.createUser                       avgt          2.361           ms/op
ClientSimple.existUser                        avgt          1.990           ms/op
ClientSimple.getUser                          avgt          1.964           ms/op
ClientSimple.listUser                         avgt          3.273           ms/op
ClientSimple.createUser                     sample  14653   2.184 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.730           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.929           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.322           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.742           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.918           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.710           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.725           ms/op
ClientSimple.existUser                      sample  16984   1.882 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.637           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.819           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.351           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.138           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.256           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.342           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.353           ms/op
ClientSimple.getUser                        sample  14317   2.237 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.808           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.142           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.970           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.033           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.173           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.077           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.105           ms/op
ClientSimple.listUser                       sample   9307   3.434 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.627           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.232           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.063           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.946           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.279           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.054           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.054           ms/op

Benchmark result is saved to 1725127517361.json
