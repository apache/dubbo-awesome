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
# Warmup Iteration   1: 1.666 ops/ms
Iteration   1: 7.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.219 ops/ms


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
# Warmup Iteration   1: 5.564 ops/ms
Iteration   1: 12.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.251 ops/ms


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
# Warmup Iteration   1: 5.521 ops/ms
Iteration   1: 13.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.281 ops/ms


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
# Warmup Iteration   1: 4.573 ops/ms
Iteration   1: 9.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.415 ops/ms


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
# Warmup Iteration   1: 4.619 ±(99.9%) 0.083 ms/op
Iteration   1: 2.207 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.207 ms/op


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
# Warmup Iteration   1: 2.949 ±(99.9%) 0.053 ms/op
Iteration   1: 1.687 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.687 ms/op


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
# Warmup Iteration   1: 3.267 ±(99.9%) 0.065 ms/op
Iteration   1: 1.952 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.952 ms/op


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.106 ms/op
Iteration   1: 3.535 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.535 ms/op


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
# Warmup Iteration   1: 3.556 ±(99.9%) 0.091 ms/op
Iteration   1: 2.156 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.484 ms/op
                 createUser·p0.50:   1.970 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.884 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  14.109 ms/op
                 createUser·p0.9999: 15.139 ms/op
                 createUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14839
  mean =      2.156 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 12725 
    [ 2.500,  3.750) = 1570 
    [ 3.750,  5.000) = 122 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     14.109 ms/op
     p(99.9900) =     15.139 ms/op
     p(99.9990) =     15.139 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 3.205 ±(99.9%) 0.077 ms/op
Iteration   1: 1.768 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   1.651 ms/op
                 existUser·p0.90:   2.204 ms/op
                 existUser·p0.95:   2.359 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  11.928 ms/op
                 existUser·p0.9999: 12.500 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18159
  mean =      1.768 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 821 
    [ 1.250,  2.500) = 16876 
    [ 2.500,  3.750) = 268 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      1.651 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.359 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =     11.928 ms/op
     p(99.9900) =     12.500 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.088 ms/op
Iteration   1: 2.105 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   1.960 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.798 ms/op
                 getUser·p0.99:   4.869 ms/op
                 getUser·p0.999:  20.513 ms/op
                 getUser·p0.9999: 21.181 ms/op
                 getUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15231
  mean =      2.105 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13244 
    [ 2.500,  5.000) = 1855 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      4.869 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     21.181 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 4.541 ±(99.9%) 0.134 ms/op
Iteration   1: 3.461 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   3.396 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.510 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 13.451 ms/op
                 listUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9227
  mean =      3.461 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1031 
    [ 2.500,  3.750) = 4953 
    [ 3.750,  5.000) = 2983 
    [ 5.000,  6.250) = 138 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.510 ms/op
     p(99.9000) =     13.320 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     13.451 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.219          ops/ms
ClientSimple.existUser                       thrpt         12.251          ops/ms
ClientSimple.getUser                         thrpt         13.281          ops/ms
ClientSimple.listUser                        thrpt          9.415          ops/ms
ClientSimple.createUser                       avgt          2.207           ms/op
ClientSimple.existUser                        avgt          1.687           ms/op
ClientSimple.getUser                          avgt          1.952           ms/op
ClientSimple.listUser                         avgt          3.535           ms/op
ClientSimple.createUser                     sample  14839   2.156 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.484           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.970           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.454           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.109           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.139           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.139           ms/op
ClientSimple.existUser                      sample  18159   1.768 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.532           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.651           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.204           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.949           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.928           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.500           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.567           ms/op
ClientSimple.getUser                        sample  15231   2.105 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.667           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.960           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.869           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.513           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.181           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.266           ms/op
ClientSimple.listUser                       sample   9227   3.461 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.768           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.396           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.510           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.320           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.451           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.451           ms/op

Benchmark result is saved to 1722989819277.json
