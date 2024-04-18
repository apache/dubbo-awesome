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
# Warmup Iteration   1: 1.532 ops/ms
Iteration   1: 6.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.957 ops/ms


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
# Warmup Iteration   1: 6.535 ops/ms
Iteration   1: 12.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.497 ops/ms


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
# Warmup Iteration   1: 6.246 ops/ms
Iteration   1: 13.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.021 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.871 ops/ms
Iteration   1: 8.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.433 ops/ms


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
# Warmup Iteration   1: 3.496 ±(99.9%) 0.060 ms/op
Iteration   1: 2.154 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.154 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.220 ±(99.9%) 0.045 ms/op
Iteration   1: 1.811 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.811 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.059 ms/op
Iteration   1: 2.080 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.080 ms/op


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.085 ms/op
Iteration   1: 3.229 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.229 ms/op


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.092 ms/op
Iteration   1: 2.448 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.506 ms/op
                 createUser·p0.50:   2.302 ms/op
                 createUser·p0.90:   2.916 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   5.762 ms/op
                 createUser·p0.999:  24.117 ms/op
                 createUser·p0.9999: 24.632 ms/op
                 createUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13061
  mean =      2.448 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8270 
    [ 2.500,  5.000) = 4632 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      2.302 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      5.762 ms/op
     p(99.9000) =     24.117 ms/op
     p(99.9900) =     24.632 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.197 ±(99.9%) 0.072 ms/op
Iteration   1: 1.898 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.432 ms/op
                 existUser·p0.50:   1.726 ms/op
                 existUser·p0.90:   2.826 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 11.892 ms/op
                 existUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16944
  mean =      1.898 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1809 
    [ 1.250,  2.500) = 12624 
    [ 2.500,  3.750) = 2212 
    [ 3.750,  5.000) = 187 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     11.892 ms/op
     p(99.9990) =     11.960 ms/op
     p(99.9999) =     11.960 ms/op
    p(100.0000) =     11.960 ms/op


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
# Warmup Iteration   1: 3.298 ±(99.9%) 0.098 ms/op
Iteration   1: 1.994 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   1.952 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   3.291 ms/op
                 getUser·p0.999:  15.728 ms/op
                 getUser·p0.9999: 16.874 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16022
  mean =      1.994 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 493 
    [ 1.250,  2.500) = 13804 
    [ 2.500,  3.750) = 1618 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.291 ms/op
     p(99.9000) =     15.728 ms/op
     p(99.9900) =     16.874 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.490 ±(99.9%) 0.122 ms/op
Iteration   1: 3.349 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   5.976 ms/op
                 listUser·p0.999:  20.316 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9544
  mean =      3.349 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 854 
    [ 2.500,  5.000) = 8325 
    [ 5.000,  7.500) = 332 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.976 ms/op
     p(99.9000) =     20.316 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.957          ops/ms
ClientSimple.existUser                       thrpt         12.497          ops/ms
ClientSimple.getUser                         thrpt         13.021          ops/ms
ClientSimple.listUser                        thrpt          8.433          ops/ms
ClientSimple.createUser                       avgt          2.154           ms/op
ClientSimple.existUser                        avgt          1.811           ms/op
ClientSimple.getUser                          avgt          2.080           ms/op
ClientSimple.listUser                         avgt          3.229           ms/op
ClientSimple.createUser                     sample  13061   2.448 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.506           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.302           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.142           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.762           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.117           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.632           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.642           ms/op
ClientSimple.existUser                      sample  16944   1.898 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.432           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.726           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.826           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.105           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.604           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.715           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.892           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.960           ms/op
ClientSimple.getUser                        sample  16022   1.994 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.540           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.952           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.291           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.728           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.874           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.170           ms/op
ClientSimple.listUser                       sample   9544   3.349 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.126           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.976           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.316           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.414           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.414           ms/op

Benchmark result is saved to 1713441970361.json
