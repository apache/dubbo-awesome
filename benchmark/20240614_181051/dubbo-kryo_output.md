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
# Warmup Iteration   1: 1.831 ops/ms
Iteration   1: 6.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.491 ops/ms


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
# Warmup Iteration   1: 7.201 ops/ms
Iteration   1: 14.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.316 ops/ms


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
# Warmup Iteration   1: 5.597 ops/ms
Iteration   1: 13.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.559 ops/ms


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
# Warmup Iteration   1: 5.206 ops/ms
Iteration   1: 8.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.459 ops/ms


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.071 ms/op
Iteration   1: 2.081 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.081 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.053 ms/op
Iteration   1: 1.986 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.986 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.058 ms/op
Iteration   1: 2.181 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.181 ms/op


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.086 ms/op
Iteration   1: 3.596 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.596 ms/op


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
# Warmup Iteration   1: 3.977 ±(99.9%) 0.126 ms/op
Iteration   1: 2.604 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.302 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   13.042 ms/op
                 createUser·p0.999:  27.787 ms/op
                 createUser·p0.9999: 28.042 ms/op
                 createUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12281
  mean =      2.604 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7183 
    [ 2.500,  5.000) = 4821 
    [ 5.000,  7.500) = 109 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.302 ms/op
     p(90.0000) =      3.166 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =     13.042 ms/op
     p(99.9000) =     27.787 ms/op
     p(99.9900) =     28.042 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 2.962 ±(99.9%) 0.079 ms/op
Iteration   1: 1.922 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.282 ms/op
                 existUser·p0.50:   1.751 ms/op
                 existUser·p0.90:   2.284 ms/op
                 existUser·p0.95:   2.441 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  16.941 ms/op
                 existUser·p0.9999: 17.083 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16642
  mean =      1.922 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 563 
    [ 1.250,  2.500) = 15452 
    [ 2.500,  3.750) = 297 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.284 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     17.083 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 3.154 ±(99.9%) 0.074 ms/op
Iteration   1: 2.172 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.391 ms/op
                 getUser·p0.50:   2.030 ms/op
                 getUser·p0.90:   2.777 ms/op
                 getUser·p0.95:   3.128 ms/op
                 getUser·p0.99:   4.241 ms/op
                 getUser·p0.999:  21.398 ms/op
                 getUser·p0.9999: 24.316 ms/op
                 getUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14728
  mean =      2.172 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11344 
    [ 2.500,  5.000) = 3264 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      3.128 ms/op
     p(99.0000) =      4.241 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     24.316 ms/op
     p(99.9990) =     24.347 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 4.533 ±(99.9%) 0.124 ms/op
Iteration   1: 3.315 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.060 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  7.166 ms/op
                 listUser·p0.9999: 9.667 ms/op
                 listUser·p1.00:   9.667 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9645
  mean =      3.315 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 15 
    [ 1.500,  2.000) = 116 
    [ 2.000,  2.500) = 1477 
    [ 2.500,  3.000) = 3094 
    [ 3.000,  3.500) = 990 
    [ 3.500,  4.000) = 1641 
    [ 4.000,  4.500) = 1508 
    [ 4.500,  5.000) = 430 
    [ 5.000,  5.500) = 137 
    [ 5.500,  6.000) = 76 
    [ 6.000,  6.500) = 75 
    [ 6.500,  7.000) = 66 
    [ 7.000,  7.500) = 19 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =      7.166 ms/op
     p(99.9900) =      9.667 ms/op
     p(99.9990) =      9.667 ms/op
     p(99.9999) =      9.667 ms/op
    p(100.0000) =      9.667 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.491          ops/ms
ClientSimple.existUser                       thrpt         14.316          ops/ms
ClientSimple.getUser                         thrpt         13.559          ops/ms
ClientSimple.listUser                        thrpt          8.459          ops/ms
ClientSimple.createUser                       avgt          2.081           ms/op
ClientSimple.existUser                        avgt          1.986           ms/op
ClientSimple.getUser                          avgt          2.181           ms/op
ClientSimple.listUser                         avgt          3.596           ms/op
ClientSimple.createUser                     sample  12281   2.604 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.903           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.302           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.166           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.551           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.042           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.787           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.042           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.049           ms/op
ClientSimple.existUser                      sample  16642   1.922 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.282           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.751           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.284           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.996           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.941           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.083           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.170           ms/op
ClientSimple.getUser                        sample  14728   2.172 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.391           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.030           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.128           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.241           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.398           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.316           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.347           ms/op
ClientSimple.listUser                       sample   9645   3.315 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.014           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.060           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.801           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.480           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.166           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.667           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.667           ms/op

Benchmark result is saved to 1718388365896.json
