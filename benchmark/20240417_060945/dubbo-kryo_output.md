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
# Warmup Iteration   1: 1.730 ops/ms
Iteration   1: 6.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.630 ops/ms


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
# Warmup Iteration   1: 5.909 ops/ms
Iteration   1: 13.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.942 ops/ms


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
# Warmup Iteration   1: 6.091 ops/ms
Iteration   1: 12.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.463 ops/ms


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
# Warmup Iteration   1: 4.943 ops/ms
Iteration   1: 8.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.151 ops/ms


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.078 ms/op
Iteration   1: 1.840 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.840 ms/op


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
# Warmup Iteration   1: 3.328 ±(99.9%) 0.079 ms/op
Iteration   1: 2.001 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.001 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.063 ms/op
Iteration   1: 2.005 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.005 ms/op


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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.088 ms/op
Iteration   1: 3.623 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.623 ms/op


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
# Warmup Iteration   1: 3.391 ±(99.9%) 0.086 ms/op
Iteration   1: 2.065 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   1.935 ms/op
                 createUser·p0.90:   2.327 ms/op
                 createUser·p0.95:   2.568 ms/op
                 createUser·p0.99:   5.057 ms/op
                 createUser·p0.999:  13.293 ms/op
                 createUser·p0.9999: 13.905 ms/op
                 createUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15633
  mean =      2.065 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 14636 
    [ 2.500,  3.750) = 624 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      5.057 ms/op
     p(99.9000) =     13.293 ms/op
     p(99.9900) =     13.905 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 3.198 ±(99.9%) 0.074 ms/op
Iteration   1: 2.168 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   2.146 ms/op
                 existUser·p0.90:   2.626 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  16.834 ms/op
                 existUser·p0.9999: 18.088 ms/op
                 existUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14755
  mean =      2.168 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 344 
    [ 1.250,  2.500) = 11806 
    [ 2.500,  3.750) = 2505 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =     16.834 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 3.427 ±(99.9%) 0.086 ms/op
Iteration   1: 2.017 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.504 ms/op
                 getUser·p0.50:   1.972 ms/op
                 getUser·p0.90:   2.449 ms/op
                 getUser·p0.95:   2.585 ms/op
                 getUser·p0.99:   3.174 ms/op
                 getUser·p0.999:  13.402 ms/op
                 getUser·p0.9999: 13.540 ms/op
                 getUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15859
  mean =      2.017 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 210 
    [ 1.250,  2.500) = 14469 
    [ 2.500,  3.750) = 1083 
    [ 3.750,  5.000) = 6 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.174 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     13.540 ms/op
     p(99.9990) =     13.550 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


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
# Warmup Iteration   1: 4.446 ±(99.9%) 0.134 ms/op
Iteration   1: 3.051 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.691 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   4.712 ms/op
                 listUser·p0.999:  6.141 ms/op
                 listUser·p0.9999: 6.537 ms/op
                 listUser·p1.00:   6.537 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10484
  mean =      3.051 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 21 
    [1.500, 2.000) = 30 
    [2.000, 2.500) = 222 
    [2.500, 3.000) = 6584 
    [3.000, 3.500) = 2030 
    [3.500, 4.000) = 639 
    [4.000, 4.500) = 801 
    [4.500, 5.000) = 125 
    [5.000, 5.500) = 6 
    [5.500, 6.000) = 10 
    [6.000, 6.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      4.712 ms/op
     p(99.9000) =      6.141 ms/op
     p(99.9900) =      6.537 ms/op
     p(99.9990) =      6.537 ms/op
     p(99.9999) =      6.537 ms/op
    p(100.0000) =      6.537 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.630          ops/ms
ClientSimple.existUser                       thrpt         13.942          ops/ms
ClientSimple.getUser                         thrpt         12.463          ops/ms
ClientSimple.listUser                        thrpt          8.151          ops/ms
ClientSimple.createUser                       avgt          1.840           ms/op
ClientSimple.existUser                        avgt          2.001           ms/op
ClientSimple.getUser                          avgt          2.005           ms/op
ClientSimple.listUser                         avgt          3.623           ms/op
ClientSimple.createUser                     sample  15633   2.065 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.679           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.935           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.327           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.057           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.293           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.905           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.025           ms/op
ClientSimple.existUser                      sample  14755   2.168 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.524           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.146           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.514           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.834           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.088           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.088           ms/op
ClientSimple.getUser                        sample  15859   2.017 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.504           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.972           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.449           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.174           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.402           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.540           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.550           ms/op
ClientSimple.listUser                       sample  10484   3.051 ± 0.017   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.691           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.888           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.949           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.712           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.141           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.537           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.537           ms/op

Benchmark result is saved to 1713333915384.json
