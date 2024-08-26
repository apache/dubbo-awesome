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
# Warmup Iteration   1: 1.153 ops/ms
Iteration   1: 5.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.939 ops/ms


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
# Warmup Iteration   1: 5.341 ops/ms
Iteration   1: 10.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.960 ops/ms


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
# Warmup Iteration   1: 5.378 ops/ms
Iteration   1: 11.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.011 ops/ms


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
# Warmup Iteration   1: 4.161 ops/ms
Iteration   1: 8.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.169 ops/ms


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.097 ms/op
Iteration   1: 2.333 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.333 ms/op


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.071 ms/op
Iteration   1: 1.950 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.950 ms/op


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.070 ms/op
Iteration   1: 2.110 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.110 ms/op


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
# Warmup Iteration   1: 4.886 ±(99.9%) 0.099 ms/op
Iteration   1: 3.295 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.295 ms/op


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
# Warmup Iteration   1: 3.609 ±(99.9%) 0.094 ms/op
Iteration   1: 2.538 ±(99.9%) 0.071 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   12.825 ms/op
                 createUser·p0.999:  39.256 ms/op
                 createUser·p0.9999: 41.091 ms/op
                 createUser·p1.00:   41.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12784
  mean =      2.538 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12472 
    [ 5.000, 10.000) = 178 
    [10.000, 15.000) = 69 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 11 
    [25.000, 30.000) = 21 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =     12.825 ms/op
     p(99.9000) =     39.256 ms/op
     p(99.9900) =     41.091 ms/op
     p(99.9990) =     41.091 ms/op
     p(99.9999) =     41.091 ms/op
    p(100.0000) =     41.091 ms/op


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
# Warmup Iteration   1: 3.301 ±(99.9%) 0.078 ms/op
Iteration   1: 1.976 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   3.630 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 13.722 ms/op
                 existUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16143
  mean =      1.976 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 14148 
    [ 2.500,  3.750) = 1716 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.630 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     13.722 ms/op
     p(99.9990) =     13.763 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 2.909 ±(99.9%) 0.069 ms/op
Iteration   1: 2.030 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.468 ms/op
                 getUser·p0.50:   1.860 ms/op
                 getUser·p0.90:   2.552 ms/op
                 getUser·p0.95:   2.748 ms/op
                 getUser·p0.99:   4.718 ms/op
                 getUser·p0.999:  26.968 ms/op
                 getUser·p0.9999: 27.492 ms/op
                 getUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15806
  mean =      2.030 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13932 
    [ 2.500,  5.000) = 1730 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      4.718 ms/op
     p(99.9000) =     26.968 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 4.602 ±(99.9%) 0.123 ms/op
Iteration   1: 3.338 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.696 ms/op
                 listUser·p0.999:  7.448 ms/op
                 listUser·p0.9999: 8.274 ms/op
                 listUser·p1.00:   8.274 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9569
  mean =      3.338 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 3 
    [1.500, 2.000) = 14 
    [2.000, 2.500) = 534 
    [2.500, 3.000) = 4131 
    [3.000, 3.500) = 1123 
    [3.500, 4.000) = 1840 
    [4.000, 4.500) = 1338 
    [4.500, 5.000) = 302 
    [5.000, 5.500) = 158 
    [5.500, 6.000) = 42 
    [6.000, 6.500) = 48 
    [6.500, 7.000) = 15 
    [7.000, 7.500) = 13 
    [7.500, 8.000) = 7 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.696 ms/op
     p(99.9000) =      7.448 ms/op
     p(99.9900) =      8.274 ms/op
     p(99.9990) =      8.274 ms/op
     p(99.9999) =      8.274 ms/op
    p(100.0000) =      8.274 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.939          ops/ms
ClientSimple.existUser                       thrpt         10.960          ops/ms
ClientSimple.getUser                         thrpt         11.011          ops/ms
ClientSimple.listUser                        thrpt          8.169          ops/ms
ClientSimple.createUser                       avgt          2.333           ms/op
ClientSimple.existUser                        avgt          1.950           ms/op
ClientSimple.getUser                          avgt          2.110           ms/op
ClientSimple.listUser                         avgt          3.295           ms/op
ClientSimple.createUser                     sample  12784   2.538 ± 0.071   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.733           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.043           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.219           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.825           ms/op
ClientSimple.createUser:createUser·p0.999   sample         39.256           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         41.091           ms/op
ClientSimple.createUser:createUser·p1.00    sample         41.091           ms/op
ClientSimple.existUser                      sample  16143   1.976 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.711           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.839           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.822           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.630           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.386           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.722           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.763           ms/op
ClientSimple.getUser                        sample  15806   2.030 ± 0.037   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.468           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.860           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.552           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.718           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.968           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.492           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.492           ms/op
ClientSimple.listUser                       sample   9569   3.338 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.413           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.027           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.588           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.696           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.448           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.274           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.274           ms/op

Benchmark result is saved to 1724652365333.json
