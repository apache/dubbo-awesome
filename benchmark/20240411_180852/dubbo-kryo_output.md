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
# Warmup Iteration   1: 1.684 ops/ms
Iteration   1: 5.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.921 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.957 ops/ms
Iteration   1: 11.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.373 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.284 ops/ms
Iteration   1: 12.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.803 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.987 ops/ms
Iteration   1: 8.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.365 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.368 ±(99.9%) 0.083 ms/op
Iteration   1: 2.139 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.139 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.254 ±(99.9%) 0.057 ms/op
Iteration   1: 2.057 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.057 ms/op


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
# Warmup Iteration   1: 3.446 ±(99.9%) 0.085 ms/op
Iteration   1: 2.145 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.145 ms/op


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.113 ms/op
Iteration   1: 4.095 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.095 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.087 ms/op
Iteration   1: 2.080 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   1.939 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.788 ms/op
                 createUser·p0.99:   5.030 ms/op
                 createUser·p0.999:  19.385 ms/op
                 createUser·p0.9999: 21.248 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15408
  mean =      2.080 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13895 
    [ 2.500,  5.000) = 1352 
    [ 5.000,  7.500) = 90 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.788 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =     19.385 ms/op
     p(99.9900) =     21.248 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 3.126 ±(99.9%) 0.090 ms/op
Iteration   1: 2.104 ±(99.9%) 0.046 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   1.911 ms/op
                 existUser·p0.90:   2.544 ms/op
                 existUser·p0.95:   2.884 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  29.616 ms/op
                 existUser·p0.9999: 29.900 ms/op
                 existUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15195
  mean =      2.104 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13516 
    [ 2.500,  5.000) = 1534 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =     29.616 ms/op
     p(99.9900) =     29.900 ms/op
     p(99.9990) =     29.917 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 3.709 ±(99.9%) 0.105 ms/op
Iteration   1: 2.289 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   2.154 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.371 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  14.682 ms/op
                 getUser·p0.9999: 15.129 ms/op
                 getUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13959
  mean =      2.289 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 10435 
    [ 2.500,  3.750) = 3065 
    [ 3.750,  5.000) = 199 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.154 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.371 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =     14.682 ms/op
     p(99.9900) =     15.129 ms/op
     p(99.9990) =     15.155 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.830 ±(99.9%) 0.147 ms/op
Iteration   1: 3.291 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.796 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.061 ms/op
                 listUser·p0.999:  19.539 ms/op
                 listUser·p0.9999: 21.955 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9713
  mean =      3.291 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1582 
    [ 2.500,  5.000) = 7746 
    [ 5.000,  7.500) = 351 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.061 ms/op
     p(99.9000) =     19.539 ms/op
     p(99.9900) =     21.955 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.921          ops/ms
ClientSimple.existUser                       thrpt         11.373          ops/ms
ClientSimple.getUser                         thrpt         12.803          ops/ms
ClientSimple.listUser                        thrpt          8.365          ops/ms
ClientSimple.createUser                       avgt          2.139           ms/op
ClientSimple.existUser                        avgt          2.057           ms/op
ClientSimple.getUser                          avgt          2.145           ms/op
ClientSimple.listUser                         avgt          4.095           ms/op
ClientSimple.createUser                     sample  15408   2.080 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.892           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.939           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.788           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.030           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.385           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.248           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.496           ms/op
ClientSimple.existUser                      sample  15195   2.104 ± 0.046   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.482           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.911           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.884           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.940           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.616           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.900           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.917           ms/op
ClientSimple.getUser                        sample  13959   2.289 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.656           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.154           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.027           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.371           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.858           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.682           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.129           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.155           ms/op
ClientSimple.listUser                       sample   9713   3.291 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.796           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.039           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.061           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.539           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.955           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.955           ms/op

Benchmark result is saved to 1712858694797.json
