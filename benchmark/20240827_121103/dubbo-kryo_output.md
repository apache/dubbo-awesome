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
# Warmup Iteration   1: 1.753 ops/ms
Iteration   1: 7.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.108 ops/ms


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
# Warmup Iteration   1: 6.516 ops/ms
Iteration   1: 12.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.538 ops/ms


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
# Warmup Iteration   1: 5.292 ops/ms
Iteration   1: 9.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.748 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.190 ops/ms
Iteration   1: 8.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.826 ops/ms


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.100 ms/op
Iteration   1: 2.126 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.126 ms/op


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
# Warmup Iteration   1: 2.913 ±(99.9%) 0.059 ms/op
Iteration   1: 1.816 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.816 ms/op


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
# Warmup Iteration   1: 3.579 ±(99.9%) 0.059 ms/op
Iteration   1: 2.052 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.052 ms/op


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
# Warmup Iteration   1: 4.922 ±(99.9%) 0.086 ms/op
Iteration   1: 3.377 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.377 ms/op


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
# Warmup Iteration   1: 3.501 ±(99.9%) 0.084 ms/op
Iteration   1: 2.210 ±(99.9%) 0.085 ms/op
                 createUser·p0.00:   0.503 ms/op
                 createUser·p0.50:   1.896 ms/op
                 createUser·p0.90:   2.458 ms/op
                 createUser·p0.95:   2.712 ms/op
                 createUser·p0.99:   4.540 ms/op
                 createUser·p0.999:  49.462 ms/op
                 createUser·p0.9999: 59.324 ms/op
                 createUser·p1.00:   60.752 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14447
  mean =      2.210 ±(99.9%) 0.085 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14307 
    [ 5.000, 10.000) = 13 
    [10.000, 15.000) = 63 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 26 
    [45.000, 50.000) = 25 
    [50.000, 55.000) = 10 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      4.540 ms/op
     p(99.9000) =     49.462 ms/op
     p(99.9900) =     59.324 ms/op
     p(99.9990) =     60.752 ms/op
     p(99.9999) =     60.752 ms/op
    p(100.0000) =     60.752 ms/op


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
# Warmup Iteration   1: 2.880 ±(99.9%) 0.070 ms/op
Iteration   1: 2.094 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.352 ms/op
                 existUser·p0.50:   2.040 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.691 ms/op
                 existUser·p0.99:   4.937 ms/op
                 existUser·p0.999:  15.409 ms/op
                 existUser·p0.9999: 15.687 ms/op
                 existUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15267
  mean =      2.094 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 13561 
    [ 2.500,  3.750) = 1350 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.352 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      4.937 ms/op
     p(99.9000) =     15.409 ms/op
     p(99.9900) =     15.687 ms/op
     p(99.9990) =     15.696 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 3.024 ±(99.9%) 0.075 ms/op
Iteration   1: 2.173 ±(99.9%) 0.077 ms/op
                 getUser·p0.00:   0.485 ms/op
                 getUser·p0.50:   1.972 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.707 ms/op
                 getUser·p0.99:   7.282 ms/op
                 getUser·p0.999:  64.706 ms/op
                 getUser·p0.9999: 75.615 ms/op
                 getUser·p1.00:   77.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14718
  mean =      2.173 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14554 
    [ 5.000, 10.000) = 70 
    [10.000, 15.000) = 51 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 7 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 3 
    [65.000, 70.000) = 11 
    [70.000, 75.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      7.282 ms/op
     p(99.9000) =     64.706 ms/op
     p(99.9900) =     75.615 ms/op
     p(99.9990) =     77.595 ms/op
     p(99.9999) =     77.595 ms/op
    p(100.0000) =     77.595 ms/op


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
# Warmup Iteration   1: 4.421 ±(99.9%) 0.142 ms/op
Iteration   1: 3.071 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.071 ms/op
                 listUser·p0.999:  6.709 ms/op
                 listUser·p0.9999: 8.442 ms/op
                 listUser·p1.00:   8.503 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10392
  mean =      3.071 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 61 
    [2.000, 2.500) = 2013 
    [2.500, 3.000) = 3894 
    [3.000, 3.500) = 1590 
    [3.500, 4.000) = 1812 
    [4.000, 4.500) = 699 
    [4.500, 5.000) = 192 
    [5.000, 5.500) = 56 
    [5.500, 6.000) = 15 
    [6.000, 6.500) = 20 
    [6.500, 7.000) = 26 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.071 ms/op
     p(99.9000) =      6.709 ms/op
     p(99.9900) =      8.442 ms/op
     p(99.9990) =      8.503 ms/op
     p(99.9999) =      8.503 ms/op
    p(100.0000) =      8.503 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.108          ops/ms
ClientSimple.existUser                       thrpt         12.538          ops/ms
ClientSimple.getUser                         thrpt          9.748          ops/ms
ClientSimple.listUser                        thrpt          8.826          ops/ms
ClientSimple.createUser                       avgt          2.126           ms/op
ClientSimple.existUser                        avgt          1.816           ms/op
ClientSimple.getUser                          avgt          2.052           ms/op
ClientSimple.listUser                         avgt          3.377           ms/op
ClientSimple.createUser                     sample  14447   2.210 ± 0.085   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.503           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.896           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.458           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.540           ms/op
ClientSimple.createUser:createUser·p0.999   sample         49.462           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         59.324           ms/op
ClientSimple.createUser:createUser·p1.00    sample         60.752           ms/op
ClientSimple.existUser                      sample  15267   2.094 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.352           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.040           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.691           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.937           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.409           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.687           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.696           ms/op
ClientSimple.getUser                        sample  14718   2.173 ± 0.077   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.485           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.972           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.99          sample          7.282           ms/op
ClientSimple.getUser:getUser·p0.999         sample         64.706           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         75.615           ms/op
ClientSimple.getUser:getUser·p1.00          sample         77.595           ms/op
ClientSimple.listUser                       sample  10392   3.071 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.313           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.867           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.985           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.071           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.709           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.442           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.503           ms/op

Benchmark result is saved to 1724760417546.json
