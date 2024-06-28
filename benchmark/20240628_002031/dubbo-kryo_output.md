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
# Warmup Iteration   1: 2.116 ops/ms
Iteration   1: 6.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.843 ops/ms


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
# Warmup Iteration   1: 6.209 ops/ms
Iteration   1: 14.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.885 ops/ms


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
# Warmup Iteration   1: 5.565 ops/ms
Iteration   1: 13.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.106 ops/ms


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
# Warmup Iteration   1: 5.846 ops/ms
Iteration   1: 8.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.320 ops/ms


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.111 ms/op
Iteration   1: 2.084 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.084 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.054 ms/op
Iteration   1: 1.751 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.751 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.055 ms/op
Iteration   1: 2.142 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.142 ms/op


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
# Warmup Iteration   1: 4.902 ±(99.9%) 0.129 ms/op
Iteration   1: 3.612 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.612 ms/op


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
# Warmup Iteration   1: 3.547 ±(99.9%) 0.102 ms/op
Iteration   1: 1.960 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   1.858 ms/op
                 createUser·p0.90:   2.449 ms/op
                 createUser·p0.95:   2.613 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  13.638 ms/op
                 createUser·p0.9999: 15.202 ms/op
                 createUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16310
  mean =      1.960 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 427 
    [ 1.250,  2.500) = 14596 
    [ 2.500,  3.750) = 1021 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     13.638 ms/op
     p(99.9900) =     15.202 ms/op
     p(99.9990) =     15.254 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 2.815 ±(99.9%) 0.068 ms/op
Iteration   1: 2.044 ±(99.9%) 0.043 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   1.956 ms/op
                 existUser·p0.90:   2.597 ms/op
                 existUser·p0.95:   2.769 ms/op
                 existUser·p0.99:   3.234 ms/op
                 existUser·p0.999:  32.351 ms/op
                 existUser·p0.9999: 32.482 ms/op
                 existUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15728
  mean =      2.044 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13525 
    [ 2.500,  5.000) = 2103 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      3.234 ms/op
     p(99.9000) =     32.351 ms/op
     p(99.9900) =     32.482 ms/op
     p(99.9990) =     32.539 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 3.531 ±(99.9%) 0.097 ms/op
Iteration   1: 2.131 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.015 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.811 ms/op
                 getUser·p0.99:   4.884 ms/op
                 getUser·p0.999:  17.531 ms/op
                 getUser·p0.9999: 17.924 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14993
  mean =      2.131 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 13368 
    [ 2.500,  3.750) = 1431 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.811 ms/op
     p(99.0000) =      4.884 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.132 ms/op
Iteration   1: 3.309 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.133 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.178 ms/op
                 listUser·p0.999:  18.285 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9664
  mean =      3.309 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1689 
    [ 2.500,  3.750) = 5926 
    [ 3.750,  5.000) = 1639 
    [ 5.000,  6.250) = 298 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      8.178 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.843          ops/ms
ClientSimple.existUser                       thrpt         14.885          ops/ms
ClientSimple.getUser                         thrpt         13.106          ops/ms
ClientSimple.listUser                        thrpt          8.320          ops/ms
ClientSimple.createUser                       avgt          2.084           ms/op
ClientSimple.existUser                        avgt          1.751           ms/op
ClientSimple.getUser                          avgt          2.142           ms/op
ClientSimple.listUser                         avgt          3.612           ms/op
ClientSimple.createUser                     sample  16310   1.960 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.709           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.858           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.449           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.284           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.638           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.202           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.254           ms/op
ClientSimple.existUser                      sample  15728   2.044 ± 0.043   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.494           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.956           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.769           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.234           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.351           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.482           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.539           ms/op
ClientSimple.getUser                        sample  14993   2.131 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.974           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.015           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.811           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.884           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.531           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.924           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.055           ms/op
ClientSimple.listUser                       sample   9664   3.309 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.159           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.133           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.178           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.285           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.497           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.497           ms/op

Benchmark result is saved to 1719533764956.json
