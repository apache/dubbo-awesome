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
# Warmup Iteration   1: 1.582 ops/ms
Iteration   1: 8.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.275 ops/ms


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
# Warmup Iteration   1: 5.095 ops/ms
Iteration   1: 12.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.224 ops/ms


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
# Warmup Iteration   1: 6.756 ops/ms
Iteration   1: 14.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.201 ops/ms


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
# Warmup Iteration   1: 5.200 ops/ms
Iteration   1: 8.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.929 ops/ms


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.080 ms/op
Iteration   1: 2.001 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.001 ms/op


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.063 ms/op
Iteration   1: 2.019 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.019 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.060 ms/op
Iteration   1: 1.805 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.805 ms/op


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.095 ms/op
Iteration   1: 3.510 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.510 ms/op


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
# Warmup Iteration   1: 3.613 ±(99.9%) 0.095 ms/op
Iteration   1: 1.980 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   1.886 ms/op
                 createUser·p0.90:   2.380 ms/op
                 createUser·p0.95:   2.621 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  13.140 ms/op
                 createUser·p0.9999: 16.226 ms/op
                 createUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16141
  mean =      1.980 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 519 
    [ 1.250,  2.500) = 14500 
    [ 2.500,  3.750) = 886 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     16.226 ms/op
     p(99.9990) =     16.237 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 3.024 ±(99.9%) 0.075 ms/op
Iteration   1: 2.059 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.005 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.674 ms/op
                 existUser·p0.99:   4.759 ms/op
                 existUser·p0.999:  11.321 ms/op
                 existUser·p0.9999: 12.602 ms/op
                 existUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15604
  mean =      2.059 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 13913 
    [ 2.500,  3.750) = 1278 
    [ 3.750,  5.000) = 123 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.674 ms/op
     p(99.0000) =      4.759 ms/op
     p(99.9000) =     11.321 ms/op
     p(99.9900) =     12.602 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.196 ms/op
Iteration   1: 1.985 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   1.870 ms/op
                 getUser·p0.90:   2.486 ms/op
                 getUser·p0.95:   2.744 ms/op
                 getUser·p0.99:   3.577 ms/op
                 getUser·p0.999:  13.686 ms/op
                 getUser·p0.9999: 14.019 ms/op
                 getUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16130
  mean =      1.985 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 14421 
    [ 2.500,  3.750) = 1419 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.577 ms/op
     p(99.9000) =     13.686 ms/op
     p(99.9900) =     14.019 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.141 ms/op
Iteration   1: 3.222 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   4.963 ms/op
                 listUser·p0.999:  6.557 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9920
  mean =      3.222 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 9 
    [ 2.000,  3.000) = 4890 
    [ 3.000,  4.000) = 3897 
    [ 4.000,  5.000) = 1031 
    [ 5.000,  6.000) = 76 
    [ 6.000,  7.000) = 9 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 5 
    [10.000, 11.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.815 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      4.963 ms/op
     p(99.9000) =      6.557 ms/op
     p(99.9900) =     11.059 ms/op
     p(99.9990) =     11.059 ms/op
     p(99.9999) =     11.059 ms/op
    p(100.0000) =     11.059 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.275          ops/ms
ClientSimple.existUser                       thrpt         12.224          ops/ms
ClientSimple.getUser                         thrpt         14.201          ops/ms
ClientSimple.listUser                        thrpt          8.929          ops/ms
ClientSimple.createUser                       avgt          2.001           ms/op
ClientSimple.existUser                        avgt          2.019           ms/op
ClientSimple.getUser                          avgt          1.805           ms/op
ClientSimple.listUser                         avgt          3.510           ms/op
ClientSimple.createUser                     sample  16141   1.980 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.646           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.886           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.380           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.735           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.140           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.226           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.237           ms/op
ClientSimple.existUser                      sample  15604   2.059 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.768           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.005           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.674           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.759           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.321           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.602           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.943           ms/op
ClientSimple.getUser                        sample  16130   1.985 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.918           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.870           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.486           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.577           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.686           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.019           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.270           ms/op
ClientSimple.listUser                       sample   9920   3.222 ± 0.020   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.815           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.006           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.047           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.963           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.557           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.059           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.059           ms/op

Benchmark result is saved to 1725236294678.json
