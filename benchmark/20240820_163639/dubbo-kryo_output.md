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
# Warmup Iteration   1: 1.796 ops/ms
Iteration   1: 7.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.112 ops/ms


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
# Warmup Iteration   1: 6.916 ops/ms
Iteration   1: 13.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.592 ops/ms


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
# Warmup Iteration   1: 4.882 ops/ms
Iteration   1: 13.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.279 ops/ms


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
# Warmup Iteration   1: 4.980 ops/ms
Iteration   1: 8.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.289 ops/ms


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.083 ms/op
Iteration   1: 2.001 ±(99.9%) 0.017 ms/op


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
# Warmup Iteration   1: 3.109 ±(99.9%) 0.052 ms/op
Iteration   1: 1.801 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.801 ms/op


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.066 ms/op
Iteration   1: 1.953 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.953 ms/op


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
# Warmup Iteration   1: 4.521 ±(99.9%) 0.133 ms/op
Iteration   1: 3.557 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.557 ms/op


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
# Warmup Iteration   1: 3.509 ±(99.9%) 0.086 ms/op
Iteration   1: 2.414 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   2.114 ms/op
                 createUser·p0.90:   2.847 ms/op
                 createUser·p0.95:   3.441 ms/op
                 createUser·p0.99:   12.075 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 24.969 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13246
  mean =      2.414 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10439 
    [ 2.500,  5.000) = 2407 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.441 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 2.936 ±(99.9%) 0.066 ms/op
Iteration   1: 1.916 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.502 ms/op
                 existUser·p0.50:   1.876 ms/op
                 existUser·p0.90:   2.355 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.691 ms/op
                 existUser·p0.999:  12.900 ms/op
                 existUser·p0.9999: 14.667 ms/op
                 existUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16877
  mean =      1.916 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 628 
    [ 1.250,  2.500) = 15310 
    [ 2.500,  3.750) = 794 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.691 ms/op
     p(99.9000) =     12.900 ms/op
     p(99.9900) =     14.667 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 3.238 ±(99.9%) 0.073 ms/op
Iteration   1: 2.090 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   1.997 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   4.057 ms/op
                 getUser·p0.999:  12.173 ms/op
                 getUser·p0.9999: 12.546 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15286
  mean =      2.090 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 235 
    [ 1.250,  2.500) = 12003 
    [ 2.500,  3.750) = 2817 
    [ 3.750,  5.000) = 173 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      4.057 ms/op
     p(99.9000) =     12.173 ms/op
     p(99.9900) =     12.546 ms/op
     p(99.9990) =     12.616 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.131 ms/op
Iteration   1: 3.548 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   5.997 ms/op
                 listUser·p0.999:  7.446 ms/op
                 listUser·p0.9999: 7.660 ms/op
                 listUser·p1.00:   7.660 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9018
  mean =      3.548 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 157 
    [2.000, 2.500) = 441 
    [2.500, 3.000) = 1527 
    [3.000, 3.500) = 2013 
    [3.500, 4.000) = 2827 
    [4.000, 4.500) = 1376 
    [4.500, 5.000) = 345 
    [5.000, 5.500) = 180 
    [5.500, 6.000) = 57 
    [6.000, 6.500) = 34 
    [6.500, 7.000) = 11 
    [7.000, 7.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =      7.446 ms/op
     p(99.9900) =      7.660 ms/op
     p(99.9990) =      7.660 ms/op
     p(99.9999) =      7.660 ms/op
    p(100.0000) =      7.660 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.112          ops/ms
ClientSimple.existUser                       thrpt         13.592          ops/ms
ClientSimple.getUser                         thrpt         13.279          ops/ms
ClientSimple.listUser                        thrpt          8.289          ops/ms
ClientSimple.createUser                       avgt          2.001           ms/op
ClientSimple.existUser                        avgt          1.801           ms/op
ClientSimple.getUser                          avgt          1.953           ms/op
ClientSimple.listUser                         avgt          3.557           ms/op
ClientSimple.createUser                     sample  13246   2.414 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.706           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.114           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.441           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.075           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.957           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.969           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.969           ms/op
ClientSimple.existUser                      sample  16877   1.916 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.502           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.876           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.355           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.691           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.900           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.667           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.746           ms/op
ClientSimple.getUser                        sample  15286   2.090 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.558           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.997           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.117           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.057           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.173           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.546           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.616           ms/op
ClientSimple.listUser                       sample   9018   3.548 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.000           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.997           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.446           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.660           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.660           ms/op

Benchmark result is saved to 1724163836009.json
