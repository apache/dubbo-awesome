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
# Warmup Iteration   1: 1.988 ops/ms
Iteration   1: 6.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.452 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.757 ops/ms
Iteration   1: 12.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.839 ops/ms


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
# Warmup Iteration   1: 5.709 ops/ms
Iteration   1: 13.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.231 ops/ms


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
# Warmup Iteration   1: 4.539 ops/ms
Iteration   1: 8.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.313 ops/ms


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
# Warmup Iteration   1: 3.602 ±(99.9%) 0.081 ms/op
Iteration   1: 2.103 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.103 ms/op


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
# Warmup Iteration   1: 3.130 ±(99.9%) 0.053 ms/op
Iteration   1: 1.788 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.788 ms/op


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
# Warmup Iteration   1: 3.430 ±(99.9%) 0.064 ms/op
Iteration   1: 2.073 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.073 ms/op


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
# Warmup Iteration   1: 4.867 ±(99.9%) 0.092 ms/op
Iteration   1: 3.501 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.501 ms/op


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.290 ms/op
Iteration   1: 2.162 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.460 ms/op
                 createUser·p0.50:   2.058 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   4.279 ms/op
                 createUser·p0.999:  21.960 ms/op
                 createUser·p0.9999: 22.776 ms/op
                 createUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14820
  mean =      2.162 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12998 
    [ 2.500,  5.000) = 1691 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      4.279 ms/op
     p(99.9000) =     21.960 ms/op
     p(99.9900) =     22.776 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 3.029 ±(99.9%) 0.091 ms/op
Iteration   1: 1.881 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.350 ms/op
                 existUser·p0.50:   1.733 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  18.187 ms/op
                 existUser·p0.9999: 18.678 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16988
  mean =      1.881 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 517 
    [ 1.250,  2.500) = 15488 
    [ 2.500,  3.750) = 821 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.350 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =     18.187 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 3.266 ±(99.9%) 0.077 ms/op
Iteration   1: 2.048 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   1.976 ms/op
                 getUser·p0.90:   2.503 ms/op
                 getUser·p0.95:   2.662 ms/op
                 getUser·p0.99:   3.240 ms/op
                 getUser·p0.999:  17.138 ms/op
                 getUser·p0.9999: 17.513 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15605
  mean =      2.048 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 13897 
    [ 2.500,  3.750) = 1539 
    [ 3.750,  5.000) = 1 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      1.976 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      3.240 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     17.513 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.116 ms/op
Iteration   1: 3.590 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.111 ms/op
                 listUser·p0.999:  23.593 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8903
  mean =      3.590 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1185 
    [ 2.500,  5.000) = 7427 
    [ 5.000,  7.500) = 259 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     23.593 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.452          ops/ms
ClientSimple.existUser                       thrpt         12.839          ops/ms
ClientSimple.getUser                         thrpt         13.231          ops/ms
ClientSimple.listUser                        thrpt          8.313          ops/ms
ClientSimple.createUser                       avgt          2.103           ms/op
ClientSimple.existUser                        avgt          1.788           ms/op
ClientSimple.getUser                          avgt          2.073           ms/op
ClientSimple.listUser                         avgt          3.501           ms/op
ClientSimple.createUser                     sample  14820   2.162 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.460           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.058           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.279           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.960           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.776           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.839           ms/op
ClientSimple.existUser                      sample  16988   1.881 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.350           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.733           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.351           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.678           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.187           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.678           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.678           ms/op
ClientSimple.getUser                        sample  15605   2.048 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.654           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.976           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.240           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.138           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.513           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.531           ms/op
ClientSimple.listUser                       sample   8903   3.590 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.893           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.523           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.596           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.111           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.593           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.510           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.510           ms/op

Benchmark result is saved to 1714436081248.json
