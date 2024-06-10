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
# Warmup Iteration   1: 1.736 ops/ms
Iteration   1: 6.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.377 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.671 ops/ms
Iteration   1: 12.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.989 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.663 ops/ms
Iteration   1: 12.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.466 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.540 ops/ms
Iteration   1: 8.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.401 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.473 ±(99.9%) 0.066 ms/op
Iteration   1: 2.260 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.260 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.307 ±(99.9%) 0.056 ms/op
Iteration   1: 1.809 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.809 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.133 ±(99.9%) 0.046 ms/op
Iteration   1: 1.833 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.833 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.695 ±(99.9%) 0.106 ms/op
Iteration   1: 3.739 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.739 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.816 ±(99.9%) 0.113 ms/op
Iteration   1: 2.109 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   1.963 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.757 ms/op
                 createUser·p0.99:   4.517 ms/op
                 createUser·p0.999:  23.195 ms/op
                 createUser·p0.9999: 24.018 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15138
  mean =      2.109 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13261 
    [ 2.500,  5.000) = 1729 
    [ 5.000,  7.500) = 53 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.963 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      4.517 ms/op
     p(99.9000) =     23.195 ms/op
     p(99.9900) =     24.018 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.455 ±(99.9%) 0.139 ms/op
Iteration   1: 2.076 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   1.946 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.765 ms/op
                 existUser·p0.99:   3.162 ms/op
                 existUser·p0.999:  27.820 ms/op
                 existUser·p0.9999: 30.771 ms/op
                 existUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15391
  mean =      2.076 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13427 
    [ 2.500,  5.000) = 1893 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      3.162 ms/op
     p(99.9000) =     27.820 ms/op
     p(99.9900) =     30.771 ms/op
     p(99.9990) =     30.966 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.101 ms/op
Iteration   1: 2.033 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   1.939 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.757 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  11.834 ms/op
                 getUser·p0.9999: 12.372 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15717
  mean =      2.033 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 217 
    [ 1.250,  2.500) = 13696 
    [ 2.500,  3.750) = 1661 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =     11.834 ms/op
     p(99.9900) =     12.372 ms/op
     p(99.9990) =     12.419 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.143 ms/op
Iteration   1: 3.737 ±(99.9%) 0.185 ms/op
                 listUser·p0.00:   0.432 ms/op
                 listUser·p0.50:   3.228 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   16.390 ms/op
                 listUser·p0.999:  81.322 ms/op
                 listUser·p0.9999: 85.197 ms/op
                 listUser·p1.00:   85.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8560
  mean =      3.737 ±(99.9%) 0.185 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8262 
    [ 5.000, 10.000) = 196 
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 12 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 0 
    [75.000, 80.000) = 16 
    [80.000, 85.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =     16.390 ms/op
     p(99.9000) =     81.322 ms/op
     p(99.9900) =     85.197 ms/op
     p(99.9990) =     85.197 ms/op
     p(99.9999) =     85.197 ms/op
    p(100.0000) =     85.197 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.377          ops/ms
ClientSimple.existUser                       thrpt         12.989          ops/ms
ClientSimple.getUser                         thrpt         12.466          ops/ms
ClientSimple.listUser                        thrpt          8.401          ops/ms
ClientSimple.createUser                       avgt          2.260           ms/op
ClientSimple.existUser                        avgt          1.809           ms/op
ClientSimple.getUser                          avgt          1.833           ms/op
ClientSimple.listUser                         avgt          3.739           ms/op
ClientSimple.createUser                     sample  15138   2.109 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.541           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.963           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.517           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.195           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.018           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.052           ms/op
ClientSimple.existUser                      sample  15391   2.076 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.724           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.946           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.765           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.162           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.820           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.771           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.966           ms/op
ClientSimple.getUser                        sample  15717   2.033 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.716           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.939           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.711           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.834           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.372           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.419           ms/op
ClientSimple.listUser                       sample   8560   3.737 ± 0.185   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.432           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.228           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample         16.390           ms/op
ClientSimple.listUser:listUser·p0.999       sample         81.322           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         85.197           ms/op
ClientSimple.listUser:listUser·p1.00        sample         85.197           ms/op

Benchmark result is saved to 1717999565250.json
