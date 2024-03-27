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
# Warmup Iteration   1: 1.802 ops/ms
Iteration   1: 7.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.248 ops/ms


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
# Warmup Iteration   1: 6.261 ops/ms
Iteration   1: 13.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.415 ops/ms


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
# Warmup Iteration   1: 5.428 ops/ms
Iteration   1: 11.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.507 ops/ms


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
# Warmup Iteration   1: 5.153 ops/ms
Iteration   1: 8.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.778 ops/ms


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
# Warmup Iteration   1: 4.550 ±(99.9%) 0.096 ms/op
Iteration   1: 2.196 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.196 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.053 ms/op
Iteration   1: 1.850 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.850 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.061 ms/op
Iteration   1: 2.147 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.147 ms/op


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.113 ms/op
Iteration   1: 3.733 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.733 ms/op


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
# Warmup Iteration   1: 3.481 ±(99.9%) 0.089 ms/op
Iteration   1: 2.033 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   1.810 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   3.039 ms/op
                 createUser·p0.99:   3.868 ms/op
                 createUser·p0.999:  13.911 ms/op
                 createUser·p0.9999: 14.590 ms/op
                 createUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15728
  mean =      2.033 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 13097 
    [ 2.500,  3.750) = 2291 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.868 ms/op
     p(99.9000) =     13.911 ms/op
     p(99.9900) =     14.590 ms/op
     p(99.9990) =     15.172 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 2.960 ±(99.9%) 0.065 ms/op
Iteration   1: 1.948 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   5.069 ms/op
                 existUser·p0.999:  20.152 ms/op
                 existUser·p0.9999: 20.393 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16416
  mean =      1.948 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15305 
    [ 2.500,  5.000) = 936 
    [ 5.000,  7.500) = 111 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      5.069 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     20.393 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 3.340 ±(99.9%) 0.084 ms/op
Iteration   1: 1.904 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   1.739 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.740 ms/op
                 getUser·p0.99:   3.501 ms/op
                 getUser·p0.999:  12.108 ms/op
                 getUser·p0.9999: 12.563 ms/op
                 getUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16926
  mean =      1.904 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 15254 
    [ 2.500,  3.750) = 1419 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.739 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.501 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     12.563 ms/op
     p(99.9990) =     12.665 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.128 ms/op
Iteration   1: 3.207 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.187 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.278 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 9.322 ms/op
                 listUser·p1.00:   9.322 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9967
  mean =      3.207 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 9 
    [ 1.500,  2.000) = 139 
    [ 2.000,  2.500) = 1641 
    [ 2.500,  3.000) = 2570 
    [ 3.000,  3.500) = 1930 
    [ 3.500,  4.000) = 2574 
    [ 4.000,  4.500) = 762 
    [ 4.500,  5.000) = 205 
    [ 5.000,  5.500) = 61 
    [ 5.500,  6.000) = 38 
    [ 6.000,  6.500) = 4 
    [ 6.500,  7.000) = 2 
    [ 7.000,  7.500) = 5 
    [ 7.500,  8.000) = 9 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 6 
    [ 9.000,  9.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.278 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =      9.322 ms/op
     p(99.9990) =      9.322 ms/op
     p(99.9999) =      9.322 ms/op
    p(100.0000) =      9.322 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.248          ops/ms
ClientSimple.existUser                       thrpt         13.415          ops/ms
ClientSimple.getUser                         thrpt         11.507          ops/ms
ClientSimple.listUser                        thrpt          8.778          ops/ms
ClientSimple.createUser                       avgt          2.196           ms/op
ClientSimple.existUser                        avgt          1.850           ms/op
ClientSimple.getUser                          avgt          2.147           ms/op
ClientSimple.listUser                         avgt          3.733           ms/op
ClientSimple.createUser                     sample  15728   2.033 ± 0.021   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.709           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.810           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.039           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.868           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.911           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.590           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.172           ms/op
ClientSimple.existUser                      sample  16416   1.948 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.607           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.810           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.069           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.152           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.393           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.414           ms/op
ClientSimple.getUser                        sample  16926   1.904 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.564           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.739           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.501           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.108           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.563           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.665           ms/op
ClientSimple.listUser                       sample   9967   3.207 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.116           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.187           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.039           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.278           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.241           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.322           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.322           ms/op

Benchmark result is saved to 1711562721483.json
