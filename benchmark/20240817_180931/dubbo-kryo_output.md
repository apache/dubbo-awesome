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
# Warmup Iteration   1: 1.878 ops/ms
Iteration   1: 6.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.799 ops/ms


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
# Warmup Iteration   1: 6.794 ops/ms
Iteration   1: 15.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.380 ops/ms


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
# Warmup Iteration   1: 6.210 ops/ms
Iteration   1: 14.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.566 ops/ms


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
# Warmup Iteration   1: 5.225 ops/ms
Iteration   1: 8.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.413 ops/ms


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.075 ms/op
Iteration   1: 2.181 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.181 ms/op


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
# Warmup Iteration   1: 3.639 ±(99.9%) 0.063 ms/op
Iteration   1: 1.806 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.806 ms/op


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
# Warmup Iteration   1: 3.497 ±(99.9%) 0.081 ms/op
Iteration   1: 2.027 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.027 ms/op


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.115 ms/op
Iteration   1: 3.975 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.975 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.075 ms/op
Iteration   1: 2.101 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   1.909 ms/op
                 createUser·p0.90:   2.650 ms/op
                 createUser·p0.95:   2.904 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  23.699 ms/op
                 createUser·p0.9999: 24.393 ms/op
                 createUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15774
  mean =      2.101 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13402 
    [ 2.500,  5.000) = 2135 
    [ 5.000,  7.500) = 129 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     23.699 ms/op
     p(99.9900) =     24.393 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 3.116 ±(99.9%) 0.105 ms/op
Iteration   1: 2.060 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   1.849 ms/op
                 existUser·p0.90:   2.511 ms/op
                 existUser·p0.95:   2.695 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  21.660 ms/op
                 existUser·p0.9999: 22.290 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15509
  mean =      2.060 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13908 
    [ 2.500,  5.000) = 1495 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.473 ms/op
     p(99.9000) =     21.660 ms/op
     p(99.9900) =     22.290 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 3.304 ±(99.9%) 0.093 ms/op
Iteration   1: 2.083 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.417 ms/op
                 getUser·p0.50:   2.030 ms/op
                 getUser·p0.90:   2.613 ms/op
                 getUser·p0.95:   2.773 ms/op
                 getUser·p0.99:   3.559 ms/op
                 getUser·p0.999:  11.194 ms/op
                 getUser·p0.9999: 11.542 ms/op
                 getUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15380
  mean =      2.083 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 12952 
    [ 2.500,  3.750) = 2143 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =     11.194 ms/op
     p(99.9900) =     11.542 ms/op
     p(99.9990) =     11.551 ms/op
     p(99.9999) =     11.551 ms/op
    p(100.0000) =     11.551 ms/op


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
# Warmup Iteration   1: 4.909 ±(99.9%) 0.196 ms/op
Iteration   1: 3.352 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.097 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.644 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  18.488 ms/op
                 listUser·p0.9999: 18.809 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9541
  mean =      3.352 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 439 
    [ 2.500,  3.750) = 7081 
    [ 3.750,  5.000) = 1650 
    [ 5.000,  6.250) = 223 
    [ 6.250,  7.500) = 106 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.644 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     18.488 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.799          ops/ms
ClientSimple.existUser                       thrpt         15.380          ops/ms
ClientSimple.getUser                         thrpt         14.566          ops/ms
ClientSimple.listUser                        thrpt          8.413          ops/ms
ClientSimple.createUser                       avgt          2.181           ms/op
ClientSimple.existUser                        avgt          1.806           ms/op
ClientSimple.getUser                          avgt          2.027           ms/op
ClientSimple.listUser                         avgt          3.975           ms/op
ClientSimple.createUser                     sample  15774   2.101 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.634           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.909           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.650           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.463           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.699           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.393           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.412           ms/op
ClientSimple.existUser                      sample  15509   2.060 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.659           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.849           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.473           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.660           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.290           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.381           ms/op
ClientSimple.getUser                        sample  15380   2.083 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.417           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.030           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.773           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.559           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.194           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.542           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.551           ms/op
ClientSimple.listUser                       sample   9541   3.352 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.380           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.097           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.137           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.644           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.644           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.488           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.809           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.809           ms/op

Benchmark result is saved to 1723917914386.json
