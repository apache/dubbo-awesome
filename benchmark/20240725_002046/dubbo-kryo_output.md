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
# Warmup Iteration   1: 0.753 ops/ms
Iteration   1: 5.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.410 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.553 ops/ms
Iteration   1: 11.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.685 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.158 ops/ms
Iteration   1: 12.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.151 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.719 ops/ms
Iteration   1: 7.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.194 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.647 ±(99.9%) 0.120 ms/op
Iteration   1: 2.173 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.173 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.429 ±(99.9%) 0.052 ms/op
Iteration   1: 1.965 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.965 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.264 ±(99.9%) 0.063 ms/op
Iteration   1: 1.992 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.992 ms/op


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
# Warmup Iteration   1: 4.615 ±(99.9%) 0.103 ms/op
Iteration   1: 3.644 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.644 ms/op


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
# Warmup Iteration   1: 4.797 ±(99.9%) 0.137 ms/op
Iteration   1: 2.100 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   1.858 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   8.171 ms/op
                 createUser·p0.999:  15.729 ms/op
                 createUser·p0.9999: 16.228 ms/op
                 createUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15158
  mean =      2.100 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 307 
    [ 1.250,  2.500) = 13094 
    [ 2.500,  3.750) = 1206 
    [ 3.750,  5.000) = 195 
    [ 5.000,  6.250) = 123 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      8.171 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     16.228 ms/op
     p(99.9990) =     16.253 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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
# Warmup Iteration   1: 3.072 ±(99.9%) 0.067 ms/op
Iteration   1: 2.195 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   1.913 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.348 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  23.329 ms/op
                 existUser·p0.9999: 24.377 ms/op
                 existUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14530
  mean =      2.195 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11841 
    [ 2.500,  5.000) = 2392 
    [ 5.000,  7.500) = 161 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.348 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     23.329 ms/op
     p(99.9900) =     24.377 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 3.335 ±(99.9%) 0.084 ms/op
Iteration   1: 2.163 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   2.034 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.781 ms/op
                 getUser·p0.99:   5.437 ms/op
                 getUser·p0.999:  22.282 ms/op
                 getUser·p0.9999: 22.752 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14752
  mean =      2.163 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12905 
    [ 2.500,  5.000) = 1697 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      5.437 ms/op
     p(99.9000) =     22.282 ms/op
     p(99.9900) =     22.752 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 5.018 ±(99.9%) 0.197 ms/op
Iteration   1: 3.617 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8848
  mean =      3.617 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 846 
    [ 2.500,  3.750) = 4731 
    [ 3.750,  5.000) = 2748 
    [ 5.000,  6.250) = 260 
    [ 6.250,  7.500) = 149 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     17.531 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.410          ops/ms
ClientSimple.existUser                       thrpt         11.685          ops/ms
ClientSimple.getUser                         thrpt         12.151          ops/ms
ClientSimple.listUser                        thrpt          7.194          ops/ms
ClientSimple.createUser                       avgt          2.173           ms/op
ClientSimple.existUser                        avgt          1.965           ms/op
ClientSimple.getUser                          avgt          1.992           ms/op
ClientSimple.listUser                         avgt          3.644           ms/op
ClientSimple.createUser                     sample  15158   2.100 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.578           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.858           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.244           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.171           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.729           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.228           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.253           ms/op
ClientSimple.existUser                      sample  14530   2.195 ± 0.041   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.613           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.913           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.961           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.348           ms/op
ClientSimple.existUser:existUser·p0.99      sample          7.111           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.329           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.377           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.510           ms/op
ClientSimple.getUser                        sample  14752   2.163 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.752           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.034           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.437           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.282           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.752           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.970           ms/op
ClientSimple.listUser                       sample   8848   3.617 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.020           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.486           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.390           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.684           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.433           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.531           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.531           ms/op

Benchmark result is saved to 1721866582602.json
