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
# Warmup Iteration   1: 2.145 ops/ms
Iteration   1: 7.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.059 ops/ms


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
# Warmup Iteration   1: 5.918 ops/ms
Iteration   1: 12.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.583 ops/ms


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
# Warmup Iteration   1: 6.388 ops/ms
Iteration   1: 14.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.025 ops/ms


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
# Warmup Iteration   1: 4.620 ops/ms
Iteration   1: 9.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.427 ops/ms


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
# Warmup Iteration   1: 3.510 ±(99.9%) 0.054 ms/op
Iteration   1: 2.115 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.115 ms/op


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
# Warmup Iteration   1: 2.938 ±(99.9%) 0.048 ms/op
Iteration   1: 1.897 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.897 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.056 ms/op
Iteration   1: 1.955 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.955 ms/op


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
# Warmup Iteration   1: 4.293 ±(99.9%) 0.082 ms/op
Iteration   1: 3.551 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.551 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.095 ms/op
Iteration   1: 2.016 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   1.837 ms/op
                 createUser·p0.90:   2.490 ms/op
                 createUser·p0.95:   2.691 ms/op
                 createUser·p0.99:   5.362 ms/op
                 createUser·p0.999:  18.073 ms/op
                 createUser·p0.9999: 19.019 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15872
  mean =      2.016 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 14212 
    [ 2.500,  3.750) = 1244 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      5.362 ms/op
     p(99.9000) =     18.073 ms/op
     p(99.9900) =     19.019 ms/op
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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.065 ms/op
Iteration   1: 1.979 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.597 ms/op
                 existUser·p0.95:   2.793 ms/op
                 existUser·p0.99:   3.525 ms/op
                 existUser·p0.999:  13.812 ms/op
                 existUser·p0.9999: 15.490 ms/op
                 existUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16154
  mean =      1.979 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 265 
    [ 1.250,  2.500) = 13784 
    [ 2.500,  3.750) = 1957 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      3.525 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     15.490 ms/op
     p(99.9990) =     16.761 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 3.086 ±(99.9%) 0.083 ms/op
Iteration   1: 2.135 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   2.085 ms/op
                 getUser·p0.90:   2.585 ms/op
                 getUser·p0.95:   2.781 ms/op
                 getUser·p0.99:   3.933 ms/op
                 getUser·p0.999:  12.272 ms/op
                 getUser·p0.9999: 13.066 ms/op
                 getUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14988
  mean =      2.135 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 12837 
    [ 2.500,  3.750) = 1828 
    [ 3.750,  5.000) = 121 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      3.933 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     13.066 ms/op
     p(99.9990) =     13.156 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.128 ms/op
Iteration   1: 3.230 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.544 ms/op
                 listUser·p0.99:   6.348 ms/op
                 listUser·p0.999:  11.338 ms/op
                 listUser·p0.9999: 11.420 ms/op
                 listUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9905
  mean =      3.230 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 359 
    [ 2.500,  3.750) = 7461 
    [ 3.750,  5.000) = 1857 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.544 ms/op
     p(99.0000) =      6.348 ms/op
     p(99.9000) =     11.338 ms/op
     p(99.9900) =     11.420 ms/op
     p(99.9990) =     11.420 ms/op
     p(99.9999) =     11.420 ms/op
    p(100.0000) =     11.420 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.059          ops/ms
ClientSimple.existUser                       thrpt         12.583          ops/ms
ClientSimple.getUser                         thrpt         14.025          ops/ms
ClientSimple.listUser                        thrpt          9.427          ops/ms
ClientSimple.createUser                       avgt          2.115           ms/op
ClientSimple.existUser                        avgt          1.897           ms/op
ClientSimple.getUser                          avgt          1.955           ms/op
ClientSimple.listUser                         avgt          3.551           ms/op
ClientSimple.createUser                     sample  15872   2.016 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.575           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.837           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.490           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.362           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.073           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.019           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.038           ms/op
ClientSimple.existUser                      sample  16154   1.979 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.641           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.747           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.793           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.525           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.812           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.490           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.761           ms/op
ClientSimple.getUser                        sample  14988   2.135 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.604           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.085           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.933           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.272           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.066           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.156           ms/op
ClientSimple.listUser                       sample   9905   3.230 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.300           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.904           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.544           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.348           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.338           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.420           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.420           ms/op

Benchmark result is saved to 1725084322995.json
