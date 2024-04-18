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
# Warmup Iteration   1: 1.853 ops/ms
Iteration   1: 6.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.995 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.671 ops/ms
Iteration   1: 14.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.386 ops/ms


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
# Warmup Iteration   1: 5.529 ops/ms
Iteration   1: 13.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.230 ops/ms


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
# Warmup Iteration   1: 5.124 ops/ms
Iteration   1: 8.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.029 ops/ms


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.066 ms/op
Iteration   1: 1.939 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.939 ms/op


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
# Warmup Iteration   1: 3.237 ±(99.9%) 0.045 ms/op
Iteration   1: 1.838 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.838 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.052 ms/op
Iteration   1: 1.854 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.854 ms/op


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.097 ms/op
Iteration   1: 3.601 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.601 ms/op


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.113 ms/op
Iteration   1: 2.127 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.368 ms/op
                 createUser·p0.50:   1.962 ms/op
                 createUser·p0.90:   2.544 ms/op
                 createUser·p0.95:   2.945 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  13.795 ms/op
                 createUser·p0.9999: 14.801 ms/op
                 createUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15049
  mean =      2.127 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 770 
    [ 1.250,  2.500) = 12556 
    [ 2.500,  3.750) = 1188 
    [ 3.750,  5.000) = 163 
    [ 5.000,  6.250) = 131 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      1.962 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     14.801 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.392 ±(99.9%) 0.088 ms/op
Iteration   1: 2.021 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.620 ms/op
                 existUser·p0.50:   1.964 ms/op
                 existUser·p0.90:   2.576 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  15.421 ms/op
                 existUser·p0.9999: 16.618 ms/op
                 existUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15961
  mean =      2.021 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 359 
    [ 1.250,  2.500) = 13493 
    [ 2.500,  3.750) = 1979 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.535 ms/op
     p(99.9000) =     15.421 ms/op
     p(99.9900) =     16.618 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.082 ms/op
Iteration   1: 2.075 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   1.935 ms/op
                 getUser·p0.90:   2.671 ms/op
                 getUser·p0.95:   2.839 ms/op
                 getUser·p0.99:   3.546 ms/op
                 getUser·p0.999:  9.946 ms/op
                 getUser·p0.9999: 10.468 ms/op
                 getUser·p1.00:   10.486 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15436
  mean =      2.075 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 9 
    [ 1.000,  2.000) = 8275 
    [ 2.000,  3.000) = 6815 
    [ 3.000,  4.000) = 231 
    [ 4.000,  5.000) = 28 
    [ 5.000,  6.000) = 41 
    [ 6.000,  7.000) = 5 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      3.546 ms/op
     p(99.9000) =      9.946 ms/op
     p(99.9900) =     10.468 ms/op
     p(99.9990) =     10.486 ms/op
     p(99.9999) =     10.486 ms/op
    p(100.0000) =     10.486 ms/op


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.136 ms/op
Iteration   1: 3.687 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  15.783 ms/op
                 listUser·p0.9999: 16.286 ms/op
                 listUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8704
  mean =      3.687 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 395 
    [ 2.500,  3.750) = 5011 
    [ 3.750,  5.000) = 2963 
    [ 5.000,  6.250) = 176 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     15.783 ms/op
     p(99.9900) =     16.286 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.995          ops/ms
ClientSimple.existUser                       thrpt         14.386          ops/ms
ClientSimple.getUser                         thrpt         13.230          ops/ms
ClientSimple.listUser                        thrpt          8.029          ops/ms
ClientSimple.createUser                       avgt          1.939           ms/op
ClientSimple.existUser                        avgt          1.838           ms/op
ClientSimple.getUser                          avgt          1.854           ms/op
ClientSimple.listUser                         avgt          3.601           ms/op
ClientSimple.createUser                     sample  15049   2.127 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.368           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.962           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.945           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.749           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.795           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.801           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.991           ms/op
ClientSimple.existUser                      sample  15961   2.021 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.620           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.964           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.535           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.421           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.618           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.843           ms/op
ClientSimple.getUser                        sample  15436   2.075 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.880           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.935           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.546           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.946           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.468           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.486           ms/op
ClientSimple.listUser                       sample   8704   3.687 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.901           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.782           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.783           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.286           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.286           ms/op

Benchmark result is saved to 1713420332964.json
