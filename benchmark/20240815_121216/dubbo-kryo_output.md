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
# Warmup Iteration   1: 1.044 ops/ms
Iteration   1: 6.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.181 ops/ms


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
# Warmup Iteration   1: 6.694 ops/ms
Iteration   1: 13.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.335 ops/ms


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
# Warmup Iteration   1: 6.583 ops/ms
Iteration   1: 15.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.357 ops/ms


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
# Warmup Iteration   1: 4.950 ops/ms
Iteration   1: 8.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.330 ops/ms


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.102 ms/op
Iteration   1: 2.216 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.216 ms/op


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
# Warmup Iteration   1: 3.620 ±(99.9%) 0.057 ms/op
Iteration   1: 2.012 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.012 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.061 ms/op
Iteration   1: 2.278 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.278 ms/op


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
# Warmup Iteration   1: 4.713 ±(99.9%) 0.109 ms/op
Iteration   1: 3.721 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.721 ms/op


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.095 ms/op
Iteration   1: 2.226 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.468 ms/op
                 createUser·p0.50:   2.077 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.933 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  23.369 ms/op
                 createUser·p0.9999: 23.859 ms/op
                 createUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14411
  mean =      2.226 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11655 
    [ 2.500,  5.000) = 2517 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     23.369 ms/op
     p(99.9900) =     23.859 ms/op
     p(99.9990) =     23.888 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 2.936 ±(99.9%) 0.069 ms/op
Iteration   1: 1.786 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.548 ms/op
                 existUser·p0.50:   1.679 ms/op
                 existUser·p0.90:   2.130 ms/op
                 existUser·p0.95:   2.408 ms/op
                 existUser·p0.99:   3.216 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 12.817 ms/op
                 existUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17886
  mean =      1.786 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 278 
    [ 1.250,  2.500) = 16921 
    [ 2.500,  3.750) = 554 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      2.130 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      3.216 ms/op
     p(99.9000) =     12.583 ms/op
     p(99.9900) =     12.817 ms/op
     p(99.9990) =     12.894 ms/op
     p(99.9999) =     12.894 ms/op
    p(100.0000) =     12.894 ms/op


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
# Warmup Iteration   1: 3.391 ±(99.9%) 0.081 ms/op
Iteration   1: 1.916 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   1.767 ms/op
                 getUser·p0.90:   2.372 ms/op
                 getUser·p0.95:   2.540 ms/op
                 getUser·p0.99:   3.413 ms/op
                 getUser·p0.999:  27.925 ms/op
                 getUser·p0.9999: 28.744 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16781
  mean =      1.916 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15761 
    [ 2.500,  5.000) = 929 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.413 ms/op
     p(99.9000) =     27.925 ms/op
     p(99.9900) =     28.744 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.178 ms/op
Iteration   1: 3.509 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.502 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.527 ms/op
                 listUser·p0.999:  8.501 ms/op
                 listUser·p0.9999: 8.552 ms/op
                 listUser·p1.00:   8.552 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9112
  mean =      3.509 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 15 
    [1.500, 2.000) = 122 
    [2.000, 2.500) = 895 
    [2.500, 3.000) = 2143 
    [3.000, 3.500) = 1367 
    [3.500, 4.000) = 1809 
    [4.000, 4.500) = 1884 
    [4.500, 5.000) = 548 
    [5.000, 5.500) = 126 
    [5.500, 6.000) = 69 
    [6.000, 6.500) = 42 
    [6.500, 7.000) = 32 
    [7.000, 7.500) = 8 
    [7.500, 8.000) = 8 
    [8.000, 8.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.527 ms/op
     p(99.9000) =      8.501 ms/op
     p(99.9900) =      8.552 ms/op
     p(99.9990) =      8.552 ms/op
     p(99.9999) =      8.552 ms/op
    p(100.0000) =      8.552 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.181          ops/ms
ClientSimple.existUser                       thrpt         13.335          ops/ms
ClientSimple.getUser                         thrpt         15.357          ops/ms
ClientSimple.listUser                        thrpt          8.330          ops/ms
ClientSimple.createUser                       avgt          2.216           ms/op
ClientSimple.existUser                        avgt          2.012           ms/op
ClientSimple.getUser                          avgt          2.278           ms/op
ClientSimple.listUser                         avgt          3.721           ms/op
ClientSimple.createUser                     sample  14411   2.226 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.468           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.077           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.242           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.369           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.859           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.888           ms/op
ClientSimple.existUser                      sample  17886   1.786 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.548           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.679           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.216           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.583           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.817           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.894           ms/op
ClientSimple.getUser                        sample  16781   1.916 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.529           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.767           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.372           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.413           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.925           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.744           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.032           ms/op
ClientSimple.listUser                       sample   9112   3.509 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.237           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.502           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.527           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.501           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.552           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.552           ms/op

Benchmark result is saved to 1723723669117.json
