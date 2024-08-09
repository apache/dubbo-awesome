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
# Warmup Iteration   1: 2.059 ops/ms
Iteration   1: 8.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.699 ops/ms


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
# Warmup Iteration   1: 6.360 ops/ms
Iteration   1: 13.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.643 ops/ms


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
# Warmup Iteration   1: 5.675 ops/ms
Iteration   1: 14.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.891 ops/ms


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
# Warmup Iteration   1: 5.600 ops/ms
Iteration   1: 8.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.738 ops/ms


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
# Warmup Iteration   1: 3.487 ±(99.9%) 0.068 ms/op
Iteration   1: 1.966 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.966 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.334 ±(99.9%) 0.052 ms/op
Iteration   1: 1.851 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.851 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.071 ±(99.9%) 0.057 ms/op
Iteration   1: 1.820 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.820 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.190 ±(99.9%) 0.116 ms/op
Iteration   1: 3.467 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.467 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.293 ±(99.9%) 0.087 ms/op
Iteration   1: 2.220 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   2.105 ms/op
                 createUser·p0.90:   2.777 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   5.246 ms/op
                 createUser·p0.999:  15.415 ms/op
                 createUser·p0.9999: 16.220 ms/op
                 createUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14377
  mean =      2.220 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 438 
    [ 1.250,  2.500) = 10332 
    [ 2.500,  3.750) = 3262 
    [ 3.750,  5.000) = 112 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      5.246 ms/op
     p(99.9000) =     15.415 ms/op
     p(99.9900) =     16.220 ms/op
     p(99.9990) =     16.220 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.057 ±(99.9%) 0.074 ms/op
Iteration   1: 1.892 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.535 ms/op
                 existUser·p0.99:   3.240 ms/op
                 existUser·p0.999:  12.239 ms/op
                 existUser·p0.9999: 12.499 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16999
  mean =      1.892 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 410 
    [ 1.250,  2.500) = 15610 
    [ 2.500,  3.750) = 874 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      3.240 ms/op
     p(99.9000) =     12.239 ms/op
     p(99.9900) =     12.499 ms/op
     p(99.9990) =     12.534 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


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
# Warmup Iteration   1: 3.297 ±(99.9%) 0.082 ms/op
Iteration   1: 2.126 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   1.944 ms/op
                 getUser·p0.90:   2.793 ms/op
                 getUser·p0.95:   2.994 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  29.131 ms/op
                 getUser·p0.9999: 29.540 ms/op
                 getUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15030
  mean =      2.126 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12126 
    [ 2.500,  5.000) = 2797 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =     29.131 ms/op
     p(99.9900) =     29.540 ms/op
     p(99.9990) =     29.557 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.106 ms/op
Iteration   1: 3.690 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   5.943 ms/op
                 listUser·p0.999:  7.614 ms/op
                 listUser·p0.9999: 8.897 ms/op
                 listUser·p1.00:   8.897 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8752
  mean =      3.690 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 4 
    [1.500, 2.000) = 61 
    [2.000, 2.500) = 177 
    [2.500, 3.000) = 1012 
    [3.000, 3.500) = 1926 
    [3.500, 4.000) = 3097 
    [4.000, 4.500) = 1784 
    [4.500, 5.000) = 447 
    [5.000, 5.500) = 96 
    [5.500, 6.000) = 62 
    [6.000, 6.500) = 45 
    [6.500, 7.000) = 24 
    [7.000, 7.500) = 6 
    [7.500, 8.000) = 10 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.943 ms/op
     p(99.9000) =      7.614 ms/op
     p(99.9900) =      8.897 ms/op
     p(99.9990) =      8.897 ms/op
     p(99.9999) =      8.897 ms/op
    p(100.0000) =      8.897 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.699          ops/ms
ClientSimple.existUser                       thrpt         13.643          ops/ms
ClientSimple.getUser                         thrpt         14.891          ops/ms
ClientSimple.listUser                        thrpt          8.738          ops/ms
ClientSimple.createUser                       avgt          1.966           ms/op
ClientSimple.existUser                        avgt          1.851           ms/op
ClientSimple.getUser                          avgt          1.820           ms/op
ClientSimple.listUser                         avgt          3.467           ms/op
ClientSimple.createUser                     sample  14377   2.220 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.764           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.105           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.777           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.072           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.246           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.415           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.220           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.220           ms/op
ClientSimple.existUser                      sample  16999   1.892 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.499           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.800           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.240           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.239           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.499           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.534           ms/op
ClientSimple.getUser                        sample  15030   2.126 ± 0.039   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.821           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.944           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.994           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.358           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.131           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.540           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.557           ms/op
ClientSimple.listUser                       sample   8752   3.690 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.225           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.678           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.943           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.614           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.897           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.897           ms/op

Benchmark result is saved to 1723162617430.json
