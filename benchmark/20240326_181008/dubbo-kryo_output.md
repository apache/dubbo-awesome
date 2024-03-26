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
# Warmup Iteration   1: 1.824 ops/ms
Iteration   1: 6.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.622 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.133 ops/ms
Iteration   1: 10.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.640 ops/ms


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
# Warmup Iteration   1: 5.960 ops/ms
Iteration   1: 13.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.474 ops/ms


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
# Warmup Iteration   1: 3.896 ops/ms
Iteration   1: 8.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.825 ops/ms


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.076 ms/op
Iteration   1: 2.279 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.279 ms/op


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
# Warmup Iteration   1: 3.080 ±(99.9%) 0.050 ms/op
Iteration   1: 2.032 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.032 ms/op


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
# Warmup Iteration   1: 3.041 ±(99.9%) 0.054 ms/op
Iteration   1: 2.238 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.238 ms/op


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
# Warmup Iteration   1: 4.699 ±(99.9%) 0.093 ms/op
Iteration   1: 3.119 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.119 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.115 ms/op
Iteration   1: 2.247 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   2.026 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.888 ms/op
                 createUser·p0.99:   8.293 ms/op
                 createUser·p0.999:  34.079 ms/op
                 createUser·p0.9999: 35.025 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14260
  mean =      2.247 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12093 
    [ 2.500,  5.000) = 1917 
    [ 5.000,  7.500) = 80 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.026 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      8.293 ms/op
     p(99.9000) =     34.079 ms/op
     p(99.9900) =     35.025 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 2.971 ±(99.9%) 0.065 ms/op
Iteration   1: 1.835 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.374 ms/op
                 existUser·p0.50:   1.716 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.535 ms/op
                 existUser·p0.99:   5.246 ms/op
                 existUser·p0.999:  22.827 ms/op
                 existUser·p0.9999: 25.849 ms/op
                 existUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17366
  mean =      1.835 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16427 
    [ 2.500,  5.000) = 740 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      5.246 ms/op
     p(99.9000) =     22.827 ms/op
     p(99.9900) =     25.849 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 3.429 ±(99.9%) 0.098 ms/op
Iteration   1: 2.256 ±(99.9%) 0.063 ms/op
                 getUser·p0.00:   0.457 ms/op
                 getUser·p0.50:   2.118 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.830 ms/op
                 getUser·p0.99:   4.181 ms/op
                 getUser·p0.999:  49.030 ms/op
                 getUser·p0.9999: 53.215 ms/op
                 getUser·p1.00:   53.215 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14620
  mean =      2.256 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14502 
    [ 5.000, 10.000) = 54 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 25 
    [50.000, 55.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      4.181 ms/op
     p(99.9000) =     49.030 ms/op
     p(99.9900) =     53.215 ms/op
     p(99.9990) =     53.215 ms/op
     p(99.9999) =     53.215 ms/op
    p(100.0000) =     53.215 ms/op


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
# Warmup Iteration   1: 4.218 ±(99.9%) 0.123 ms/op
Iteration   1: 3.116 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   2.826 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.145 ms/op
                 listUser·p0.99:   5.083 ms/op
                 listUser·p0.999:  24.445 ms/op
                 listUser·p0.9999: 25.589 ms/op
                 listUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10247
  mean =      3.116 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1443 
    [ 2.500,  5.000) = 8682 
    [ 5.000,  7.500) = 90 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.083 ms/op
     p(99.9000) =     24.445 ms/op
     p(99.9900) =     25.589 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.622          ops/ms
ClientSimple.existUser                       thrpt         10.640          ops/ms
ClientSimple.getUser                         thrpt         13.474          ops/ms
ClientSimple.listUser                        thrpt          8.825          ops/ms
ClientSimple.createUser                       avgt          2.279           ms/op
ClientSimple.existUser                        avgt          2.032           ms/op
ClientSimple.getUser                          avgt          2.238           ms/op
ClientSimple.listUser                         avgt          3.119           ms/op
ClientSimple.createUser                     sample  14260   2.247 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.571           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.026           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.293           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.079           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.025           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.193           ms/op
ClientSimple.existUser                      sample  17366   1.835 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.374           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.716           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.246           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.827           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.849           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.018           ms/op
ClientSimple.getUser                        sample  14620   2.256 ± 0.063   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.457           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.181           ms/op
ClientSimple.getUser:getUser·p0.999         sample         49.030           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         53.215           ms/op
ClientSimple.getUser:getUser·p1.00          sample         53.215           ms/op
ClientSimple.listUser                       sample  10247   3.116 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.892           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.826           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.903           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.145           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.083           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.445           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.589           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.592           ms/op

Benchmark result is saved to 1711476349734.json
