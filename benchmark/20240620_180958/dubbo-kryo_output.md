# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.720 ops/ms
Iteration   1: 6.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.204 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.273 ops/ms
Iteration   1: 12.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.712 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.913 ops/ms
Iteration   1: 13.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.240 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.762 ops/ms
Iteration   1: 9.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.239 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.835 ±(99.9%) 0.063 ms/op
Iteration   1: 1.977 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.977 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.916 ±(99.9%) 0.055 ms/op
Iteration   1: 1.738 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.738 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.248 ±(99.9%) 0.050 ms/op
Iteration   1: 1.920 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.920 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.970 ±(99.9%) 0.132 ms/op
Iteration   1: 3.215 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.215 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.573 ±(99.9%) 0.092 ms/op
Iteration   1: 1.853 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   1.683 ms/op
                 createUser·p0.90:   2.138 ms/op
                 createUser·p0.95:   2.298 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  21.291 ms/op
                 createUser·p0.9999: 23.097 ms/op
                 createUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 17244
  mean =      1.853 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16702 
    [ 2.500,  5.000) = 332 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.298 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     21.291 ms/op
     p(99.9900) =     23.097 ms/op
     p(99.9990) =     23.429 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.903 ±(99.9%) 0.073 ms/op
Iteration   1: 1.940 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   1.858 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  12.247 ms/op
                 existUser·p0.9999: 12.332 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16485
  mean =      1.940 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 573 
    [ 1.250,  2.500) = 14654 
    [ 2.500,  3.750) = 1028 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =     12.247 ms/op
     p(99.9900) =     12.332 ms/op
     p(99.9990) =     12.354 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.310 ±(99.9%) 0.086 ms/op
Iteration   1: 2.037 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   2.003 ms/op
                 getUser·p0.90:   2.445 ms/op
                 getUser·p0.95:   2.650 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  12.141 ms/op
                 getUser·p0.9999: 12.552 ms/op
                 getUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15756
  mean =      2.037 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 265 
    [ 1.250,  2.500) = 14272 
    [ 2.500,  3.750) = 1033 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.003 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =     12.141 ms/op
     p(99.9900) =     12.552 ms/op
     p(99.9990) =     12.599 ms/op
     p(99.9999) =     12.599 ms/op
    p(100.0000) =     12.599 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.351 ±(99.9%) 0.131 ms/op
Iteration   1: 3.330 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   3.162 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.593 ms/op
                 listUser·p0.999:  20.513 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9627
  mean =      3.330 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1308 
    [ 2.500,  5.000) = 8166 
    [ 5.000,  7.500) = 118 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.593 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.204          ops/ms
ClientSimple.existUser                       thrpt         12.712          ops/ms
ClientSimple.getUser                         thrpt         13.240          ops/ms
ClientSimple.listUser                        thrpt          9.239          ops/ms
ClientSimple.createUser                       avgt          1.977           ms/op
ClientSimple.existUser                        avgt          1.738           ms/op
ClientSimple.getUser                          avgt          1.920           ms/op
ClientSimple.listUser                         avgt          3.215           ms/op
ClientSimple.createUser                     sample  17244   1.853 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.526           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.683           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.138           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.298           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.201           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.291           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.097           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.429           ms/op
ClientSimple.existUser                      sample  16485   1.940 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.652           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.858           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.046           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.247           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.332           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.354           ms/op
ClientSimple.getUser                        sample  15756   2.037 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.593           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.003           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.182           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.141           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.552           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.599           ms/op
ClientSimple.listUser                       sample   9627   3.330 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.039           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.162           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.593           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.513           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.332           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.332           ms/op

Benchmark result is saved to 1718906735537.json
