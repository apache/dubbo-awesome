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
# Warmup Iteration   1: 2.085 ops/ms
Iteration   1: 6.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.771 ops/ms


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
# Warmup Iteration   1: 5.953 ops/ms
Iteration   1: 12.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.949 ops/ms


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
# Warmup Iteration   1: 5.931 ops/ms
Iteration   1: 13.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.289 ops/ms


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
# Warmup Iteration   1: 5.823 ops/ms
Iteration   1: 8.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.899 ops/ms


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
# Warmup Iteration   1: 3.658 ±(99.9%) 0.065 ms/op
Iteration   1: 2.136 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.136 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.046 ms/op
Iteration   1: 1.745 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.745 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.497 ±(99.9%) 0.058 ms/op
Iteration   1: 2.124 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.124 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ±(99.9%) 0.093 ms/op
Iteration   1: 3.062 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.062 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.241 ±(99.9%) 0.081 ms/op
Iteration   1: 2.443 ±(99.9%) 0.072 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   2.175 ms/op
                 createUser·p0.90:   3.191 ms/op
                 createUser·p0.95:   3.584 ms/op
                 createUser·p0.99:   6.817 ms/op
                 createUser·p0.999:  49.414 ms/op
                 createUser·p0.9999: 50.059 ms/op
                 createUser·p1.00:   50.201 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13079
  mean =      2.443 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12858 
    [ 5.000, 10.000) = 146 
    [10.000, 15.000) = 43 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 31 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      3.191 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      6.817 ms/op
     p(99.9000) =     49.414 ms/op
     p(99.9900) =     50.059 ms/op
     p(99.9990) =     50.201 ms/op
     p(99.9999) =     50.201 ms/op
    p(100.0000) =     50.201 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.090 ms/op
Iteration   1: 1.854 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.361 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.335 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   3.222 ms/op
                 existUser·p0.999:  19.908 ms/op
                 existUser·p0.9999: 20.675 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17230
  mean =      1.854 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16215 
    [ 2.500,  5.000) = 941 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.361 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.222 ms/op
     p(99.9000) =     19.908 ms/op
     p(99.9900) =     20.675 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 3.419 ±(99.9%) 0.091 ms/op
Iteration   1: 2.198 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.419 ms/op
                 getUser·p0.50:   1.960 ms/op
                 getUser·p0.90:   2.748 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   7.815 ms/op
                 getUser·p0.999:  13.366 ms/op
                 getUser·p0.9999: 13.716 ms/op
                 getUser·p1.00:   13.828 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14545
  mean =      2.198 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 11989 
    [ 2.500,  3.750) = 2085 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     13.366 ms/op
     p(99.9900) =     13.716 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.111 ms/op
Iteration   1: 3.348 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.634 ms/op
                 listUser·p0.50:   3.183 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   5.795 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 13.599 ms/op
                 listUser·p1.00:   13.599 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9538
  mean =      3.348 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1308 
    [ 2.500,  3.750) = 5430 
    [ 3.750,  5.000) = 2468 
    [ 5.000,  6.250) = 237 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.795 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     13.599 ms/op
     p(99.9999) =     13.599 ms/op
    p(100.0000) =     13.599 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.771          ops/ms
ClientSimple.existUser                       thrpt         12.949          ops/ms
ClientSimple.getUser                         thrpt         13.289          ops/ms
ClientSimple.listUser                        thrpt          8.899          ops/ms
ClientSimple.createUser                       avgt          2.136           ms/op
ClientSimple.existUser                        avgt          1.745           ms/op
ClientSimple.getUser                          avgt          2.124           ms/op
ClientSimple.listUser                         avgt          3.062           ms/op
ClientSimple.createUser                     sample  13079   2.443 ± 0.072   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.542           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.175           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.191           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.584           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.817           ms/op
ClientSimple.createUser:createUser·p0.999   sample         49.414           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         50.059           ms/op
ClientSimple.createUser:createUser·p1.00    sample         50.201           ms/op
ClientSimple.existUser                      sample  17230   1.854 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.361           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.753           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.222           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.908           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.675           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.840           ms/op
ClientSimple.getUser                        sample  14545   2.198 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.419           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.960           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.99          sample          7.815           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.366           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.716           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.828           ms/op
ClientSimple.listUser                       sample   9538   3.348 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.634           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.183           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.795           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.304           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.599           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.599           ms/op

Benchmark result is saved to 1712708093950.json
