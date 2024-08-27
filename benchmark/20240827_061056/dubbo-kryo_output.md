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
# Warmup Iteration   1: 1.792 ops/ms
Iteration   1: 6.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.695 ops/ms


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
# Warmup Iteration   1: 6.389 ops/ms
Iteration   1: 13.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.705 ops/ms


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
# Warmup Iteration   1: 4.851 ops/ms
Iteration   1: 12.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.558 ops/ms


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
# Warmup Iteration   1: 4.856 ops/ms
Iteration   1: 8.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.636 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.786 ±(99.9%) 0.072 ms/op
Iteration   1: 2.187 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.187 ms/op


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
# Warmup Iteration   1: 3.350 ±(99.9%) 0.060 ms/op
Iteration   1: 1.768 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.768 ms/op


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
# Warmup Iteration   1: 3.375 ±(99.9%) 0.054 ms/op
Iteration   1: 1.874 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.874 ms/op


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
# Warmup Iteration   1: 4.487 ±(99.9%) 0.087 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.190 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.084 ms/op
Iteration   1: 1.943 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   1.696 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.888 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  21.870 ms/op
                 createUser·p0.9999: 22.862 ms/op
                 createUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16584
  mean =      1.943 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14503 
    [ 2.500,  5.000) = 1940 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     21.870 ms/op
     p(99.9900) =     22.862 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 3.094 ±(99.9%) 0.087 ms/op
Iteration   1: 1.960 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   1.878 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   3.087 ms/op
                 existUser·p0.999:  15.477 ms/op
                 existUser·p0.9999: 15.918 ms/op
                 existUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16344
  mean =      1.960 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 15442 
    [ 2.500,  3.750) = 629 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      3.087 ms/op
     p(99.9000) =     15.477 ms/op
     p(99.9900) =     15.918 ms/op
     p(99.9990) =     15.991 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 3.088 ±(99.9%) 0.072 ms/op
Iteration   1: 2.227 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   2.152 ms/op
                 getUser·p0.90:   2.925 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  12.811 ms/op
                 getUser·p0.9999: 13.483 ms/op
                 getUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14356
  mean =      2.227 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 215 
    [ 1.250,  2.500) = 9759 
    [ 2.500,  3.750) = 4106 
    [ 3.750,  5.000) = 160 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      2.152 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =     12.811 ms/op
     p(99.9900) =     13.483 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.131 ms/op
Iteration   1: 3.516 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  7.397 ms/op
                 listUser·p0.9999: 7.963 ms/op
                 listUser·p1.00:   7.963 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9095
  mean =      3.516 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 9 
    [1.500, 2.000) = 145 
    [2.000, 2.500) = 410 
    [2.500, 3.000) = 1884 
    [3.000, 3.500) = 1787 
    [3.500, 4.000) = 2951 
    [4.000, 4.500) = 1235 
    [4.500, 5.000) = 312 
    [5.000, 5.500) = 207 
    [5.500, 6.000) = 97 
    [6.000, 6.500) = 13 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =      7.397 ms/op
     p(99.9900) =      7.963 ms/op
     p(99.9990) =      7.963 ms/op
     p(99.9999) =      7.963 ms/op
    p(100.0000) =      7.963 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.695          ops/ms
ClientSimple.existUser                       thrpt         13.705          ops/ms
ClientSimple.getUser                         thrpt         12.558          ops/ms
ClientSimple.listUser                        thrpt          8.636          ops/ms
ClientSimple.createUser                       avgt          2.187           ms/op
ClientSimple.existUser                        avgt          1.768           ms/op
ClientSimple.getUser                          avgt          1.874           ms/op
ClientSimple.listUser                         avgt          3.190           ms/op
ClientSimple.createUser                     sample  16584   1.943 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.766           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.696           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.522           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.870           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.862           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.970           ms/op
ClientSimple.existUser                      sample  16344   1.960 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.613           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.878           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.087           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.477           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.918           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.991           ms/op
ClientSimple.getUser                        sample  14356   2.227 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.610           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.152           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.925           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.183           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.415           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.811           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.483           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.533           ms/op
ClientSimple.listUser                       sample   9095   3.516 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.770           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.559           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.800           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.397           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.963           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.963           ms/op

Benchmark result is saved to 1724738787257.json
