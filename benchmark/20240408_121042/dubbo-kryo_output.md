# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.819 ops/ms
Iteration   1: 7.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.128 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.780 ops/ms
Iteration   1: 12.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.272 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.607 ops/ms
Iteration   1: 12.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.257 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.586 ops/ms
Iteration   1: 8.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.102 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.032 ±(99.9%) 0.077 ms/op
Iteration   1: 2.172 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.172 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.295 ±(99.9%) 0.057 ms/op
Iteration   1: 1.978 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.978 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.159 ±(99.9%) 0.054 ms/op
Iteration   1: 2.052 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.052 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.744 ±(99.9%) 0.110 ms/op
Iteration   1: 3.881 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.881 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.301 ±(99.9%) 0.075 ms/op
Iteration   1: 2.090 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.467 ms/op
                 createUser·p0.50:   1.976 ms/op
                 createUser·p0.90:   2.560 ms/op
                 createUser·p0.95:   2.753 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  14.900 ms/op
                 createUser·p0.9999: 15.340 ms/op
                 createUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15295
  mean =      2.090 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 467 
    [ 1.250,  2.500) = 12915 
    [ 2.500,  3.750) = 1756 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      1.976 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =     14.900 ms/op
     p(99.9900) =     15.340 ms/op
     p(99.9990) =     15.401 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.056 ±(99.9%) 0.113 ms/op
Iteration   1: 1.947 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   1.853 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.072 ms/op
                 existUser·p0.999:  28.723 ms/op
                 existUser·p0.9999: 29.421 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16439
  mean =      1.947 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15288 
    [ 2.500,  5.000) = 1084 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.072 ms/op
     p(99.9000) =     28.723 ms/op
     p(99.9900) =     29.421 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.778 ±(99.9%) 0.096 ms/op
Iteration   1: 2.073 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   1.892 ms/op
                 getUser·p0.90:   2.683 ms/op
                 getUser·p0.95:   2.960 ms/op
                 getUser·p0.99:   3.862 ms/op
                 getUser·p0.999:  13.281 ms/op
                 getUser·p0.9999: 14.385 ms/op
                 getUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15405
  mean =      2.073 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 12568 
    [ 2.500,  3.750) = 2514 
    [ 3.750,  5.000) = 120 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.960 ms/op
     p(99.0000) =      3.862 ms/op
     p(99.9000) =     13.281 ms/op
     p(99.9900) =     14.385 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.900 ±(99.9%) 0.152 ms/op
Iteration   1: 3.288 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.634 ms/op
                 listUser·p0.50:   3.293 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  14.078 ms/op
                 listUser·p0.9999: 14.680 ms/op
                 listUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9732
  mean =      3.288 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 678 
    [ 2.500,  3.750) = 7107 
    [ 3.750,  5.000) = 1788 
    [ 5.000,  6.250) = 107 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     14.078 ms/op
     p(99.9900) =     14.680 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.128          ops/ms
ClientSimple.existUser                       thrpt         12.272          ops/ms
ClientSimple.getUser                         thrpt         12.257          ops/ms
ClientSimple.listUser                        thrpt          8.102          ops/ms
ClientSimple.createUser                       avgt          2.172           ms/op
ClientSimple.existUser                        avgt          1.978           ms/op
ClientSimple.getUser                          avgt          2.052           ms/op
ClientSimple.listUser                         avgt          3.881           ms/op
ClientSimple.createUser                     sample  15295   2.090 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.467           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.976           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.560           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.842           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.900           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.340           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.401           ms/op
ClientSimple.existUser                      sample  16439   1.947 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.642           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.853           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.072           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.723           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.421           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.590           ms/op
ClientSimple.getUser                        sample  15405   2.073 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.929           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.892           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.960           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.862           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.281           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.385           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.385           ms/op
ClientSimple.listUser                       sample   9732   3.288 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.634           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.293           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.990           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.571           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.078           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.680           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.680           ms/op

Benchmark result is saved to 1712577983440.json
