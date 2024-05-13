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
# Warmup Iteration   1: 1.129 ops/ms
Iteration   1: 5.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.299 ops/ms


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
# Warmup Iteration   1: 5.763 ops/ms
Iteration   1: 11.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.287 ops/ms


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
# Warmup Iteration   1: 5.093 ops/ms
Iteration   1: 12.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.790 ops/ms


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
# Warmup Iteration   1: 3.923 ops/ms
Iteration   1: 7.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.832 ops/ms


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.073 ms/op
Iteration   1: 2.199 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.199 ms/op


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
# Warmup Iteration   1: 3.176 ±(99.9%) 0.052 ms/op
Iteration   1: 1.912 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.912 ms/op


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
# Warmup Iteration   1: 3.168 ±(99.9%) 0.054 ms/op
Iteration   1: 1.873 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.873 ms/op


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
# Warmup Iteration   1: 4.632 ±(99.9%) 0.093 ms/op
Iteration   1: 3.163 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.163 ms/op


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
# Warmup Iteration   1: 3.513 ±(99.9%) 0.085 ms/op
Iteration   1: 2.212 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   1.884 ms/op
                 createUser·p0.90:   2.703 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   8.708 ms/op
                 createUser·p0.999:  17.498 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14449
  mean =      2.212 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 12176 
    [ 2.500,  3.750) = 1639 
    [ 3.750,  5.000) = 215 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      8.708 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 2.994 ±(99.9%) 0.072 ms/op
Iteration   1: 2.090 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.465 ms/op
                 existUser·p0.50:   2.025 ms/op
                 existUser·p0.90:   2.589 ms/op
                 existUser·p0.95:   2.808 ms/op
                 existUser·p0.99:   4.743 ms/op
                 existUser·p0.999:  19.094 ms/op
                 existUser·p0.9999: 19.786 ms/op
                 existUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15308
  mean =      2.090 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 481 
    [ 1.250,  2.500) = 12655 
    [ 2.500,  3.750) = 1967 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.808 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =     19.094 ms/op
     p(99.9900) =     19.786 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.086 ms/op
Iteration   1: 2.232 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.630 ms/op
                 getUser·p0.50:   2.150 ms/op
                 getUser·p0.90:   2.781 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  16.089 ms/op
                 getUser·p0.9999: 16.884 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14353
  mean =      2.232 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 330 
    [ 1.250,  2.500) = 10377 
    [ 2.500,  3.750) = 3438 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 72 
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
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =     16.089 ms/op
     p(99.9900) =     16.884 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 4.293 ±(99.9%) 0.121 ms/op
Iteration   1: 3.381 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.209 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   8.361 ms/op
                 listUser·p0.999:  14.198 ms/op
                 listUser·p0.9999: 14.893 ms/op
                 listUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9440
  mean =      3.381 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 643 
    [ 2.500,  3.750) = 6327 
    [ 3.750,  5.000) = 2191 
    [ 5.000,  6.250) = 118 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.209 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      8.361 ms/op
     p(99.9000) =     14.198 ms/op
     p(99.9900) =     14.893 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.299          ops/ms
ClientSimple.existUser                       thrpt         11.287          ops/ms
ClientSimple.getUser                         thrpt         12.790          ops/ms
ClientSimple.listUser                        thrpt          7.832          ops/ms
ClientSimple.createUser                       avgt          2.199           ms/op
ClientSimple.existUser                        avgt          1.912           ms/op
ClientSimple.getUser                          avgt          1.873           ms/op
ClientSimple.listUser                         avgt          3.163           ms/op
ClientSimple.createUser                     sample  14449   2.212 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.762           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.884           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.187           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.708           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.498           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.776           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.776           ms/op
ClientSimple.existUser                      sample  15308   2.090 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.465           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.025           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.808           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.743           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.094           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.786           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.890           ms/op
ClientSimple.getUser                        sample  14353   2.232 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.630           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.150           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.080           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.157           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.089           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.884           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.941           ms/op
ClientSimple.listUser                       sample   9440   3.381 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.147           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.209           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.361           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.198           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.893           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.893           ms/op

Benchmark result is saved to 1715559370244.json
