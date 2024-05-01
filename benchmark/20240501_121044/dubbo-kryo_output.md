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
# Warmup Iteration   1: 1.810 ops/ms
Iteration   1: 7.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.612 ops/ms


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
# Warmup Iteration   1: 5.819 ops/ms
Iteration   1: 13.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.741 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.558 ops/ms
Iteration   1: 12.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.088 ops/ms


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
# Warmup Iteration   1: 4.708 ops/ms
Iteration   1: 8.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.924 ops/ms


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
# Warmup Iteration   1: 4.699 ±(99.9%) 0.091 ms/op
Iteration   1: 2.161 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.161 ms/op


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
# Warmup Iteration   1: 3.281 ±(99.9%) 0.058 ms/op
Iteration   1: 2.050 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.050 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.057 ms/op
Iteration   1: 2.050 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.050 ms/op


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
# Warmup Iteration   1: 5.137 ±(99.9%) 0.115 ms/op
Iteration   1: 3.653 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.653 ms/op


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.105 ms/op
Iteration   1: 2.164 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.607 ms/op
                 createUser·p0.50:   1.976 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.851 ms/op
                 createUser·p0.99:   6.228 ms/op
                 createUser·p0.999:  32.186 ms/op
                 createUser·p0.9999: 33.030 ms/op
                 createUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15195
  mean =      2.164 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13575 
    [ 2.500,  5.000) = 1383 
    [ 5.000,  7.500) = 133 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      1.976 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      6.228 ms/op
     p(99.9000) =     32.186 ms/op
     p(99.9900) =     33.030 ms/op
     p(99.9990) =     33.030 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.103 ms/op
Iteration   1: 1.825 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.505 ms/op
                 existUser·p0.50:   1.743 ms/op
                 existUser·p0.90:   2.355 ms/op
                 existUser·p0.95:   2.703 ms/op
                 existUser·p0.99:   3.232 ms/op
                 existUser·p0.999:  11.469 ms/op
                 existUser·p0.9999: 12.648 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17481
  mean =      1.825 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 644 
    [ 1.250,  2.500) = 15577 
    [ 2.500,  3.750) = 1171 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      1.743 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      3.232 ms/op
     p(99.9000) =     11.469 ms/op
     p(99.9900) =     12.648 ms/op
     p(99.9990) =     12.648 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


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
# Warmup Iteration   1: 3.438 ±(99.9%) 0.101 ms/op
Iteration   1: 1.907 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.581 ms/op
                 getUser·p0.50:   1.798 ms/op
                 getUser·p0.90:   2.327 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   3.097 ms/op
                 getUser·p0.999:  12.288 ms/op
                 getUser·p0.9999: 13.096 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16719
  mean =      1.907 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 198 
    [ 1.250,  2.500) = 15474 
    [ 2.500,  3.750) = 963 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.097 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     13.096 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


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
# Warmup Iteration   1: 4.679 ±(99.9%) 0.153 ms/op
Iteration   1: 3.459 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.428 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.976 ms/op
                 listUser·p0.999:  17.786 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9226
  mean =      3.459 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1024 
    [ 2.500,  3.750) = 5514 
    [ 3.750,  5.000) = 2478 
    [ 5.000,  6.250) = 135 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.976 ms/op
     p(99.9000) =     17.786 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.612          ops/ms
ClientSimple.existUser                       thrpt         13.741          ops/ms
ClientSimple.getUser                         thrpt         12.088          ops/ms
ClientSimple.listUser                        thrpt          8.924          ops/ms
ClientSimple.createUser                       avgt          2.161           ms/op
ClientSimple.existUser                        avgt          2.050           ms/op
ClientSimple.getUser                          avgt          2.050           ms/op
ClientSimple.listUser                         avgt          3.653           ms/op
ClientSimple.createUser                     sample  15195   2.164 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.607           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.976           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.228           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.186           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.030           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.030           ms/op
ClientSimple.existUser                      sample  17481   1.825 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.505           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.743           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.355           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.232           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.469           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.648           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.648           ms/op
ClientSimple.getUser                        sample  16719   1.907 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.581           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.798           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.327           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.097           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.288           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.096           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.173           ms/op
ClientSimple.listUser                       sample   9226   3.459 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.051           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.428           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.116           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.976           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.786           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.383           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.383           ms/op

Benchmark result is saved to 1714565175389.json
