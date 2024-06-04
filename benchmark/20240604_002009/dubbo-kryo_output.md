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
# Warmup Iteration   1: 1.613 ops/ms
Iteration   1: 6.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.163 ops/ms


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
# Warmup Iteration   1: 5.376 ops/ms
Iteration   1: 13.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.480 ops/ms


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
# Warmup Iteration   1: 5.358 ops/ms
Iteration   1: 13.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.373 ops/ms


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
# Warmup Iteration   1: 4.157 ops/ms
Iteration   1: 7.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.424 ops/ms


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.082 ms/op
Iteration   1: 2.047 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.047 ms/op


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
# Warmup Iteration   1: 2.936 ±(99.9%) 0.050 ms/op
Iteration   1: 2.089 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.089 ms/op


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
# Warmup Iteration   1: 3.198 ±(99.9%) 0.051 ms/op
Iteration   1: 2.064 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.064 ms/op


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.076 ms/op
Iteration   1: 3.065 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.065 ms/op


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
# Warmup Iteration   1: 3.352 ±(99.9%) 0.080 ms/op
Iteration   1: 1.997 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   1.806 ms/op
                 createUser·p0.90:   2.362 ms/op
                 createUser·p0.95:   2.556 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  17.989 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16012
  mean =      1.997 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 262 
    [ 1.250,  2.500) = 14851 
    [ 2.500,  3.750) = 585 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 73 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.362 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     17.989 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 3.321 ±(99.9%) 0.074 ms/op
Iteration   1: 1.971 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   1.853 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.945 ms/op
                 existUser·p0.99:   3.720 ms/op
                 existUser·p0.999:  13.386 ms/op
                 existUser·p0.9999: 13.480 ms/op
                 existUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16373
  mean =      1.971 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 235 
    [ 1.250,  2.500) = 14717 
    [ 2.500,  3.750) = 1278 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      3.720 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     13.480 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


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
# Warmup Iteration   1: 2.936 ±(99.9%) 0.070 ms/op
Iteration   1: 2.009 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   1.911 ms/op
                 getUser·p0.90:   2.417 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   4.545 ms/op
                 getUser·p0.999:  16.400 ms/op
                 getUser·p0.9999: 16.604 ms/op
                 getUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15923
  mean =      2.009 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 240 
    [ 1.250,  2.500) = 14576 
    [ 2.500,  3.750) = 909 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      4.545 ms/op
     p(99.9000) =     16.400 ms/op
     p(99.9900) =     16.604 ms/op
     p(99.9990) =     16.613 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.146 ms/op
Iteration   1: 3.513 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.039 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 14.189 ms/op
                 listUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9107
  mean =      3.513 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 314 
    [ 2.500,  3.750) = 5753 
    [ 3.750,  5.000) = 2716 
    [ 5.000,  6.250) = 197 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.039 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     14.189 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.163          ops/ms
ClientSimple.existUser                       thrpt         13.480          ops/ms
ClientSimple.getUser                         thrpt         13.373          ops/ms
ClientSimple.listUser                        thrpt          7.424          ops/ms
ClientSimple.createUser                       avgt          2.047           ms/op
ClientSimple.existUser                        avgt          2.089           ms/op
ClientSimple.getUser                          avgt          2.064           ms/op
ClientSimple.listUser                         avgt          3.065           ms/op
ClientSimple.createUser                     sample  16012   1.997 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.796           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.806           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.362           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.849           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.989           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.743           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.842           ms/op
ClientSimple.existUser                      sample  16373   1.971 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.700           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.853           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.425           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.945           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.720           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.386           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.480           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.500           ms/op
ClientSimple.getUser                        sample  15923   2.009 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.612           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.911           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.545           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.400           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.604           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.613           ms/op
ClientSimple.listUser                       sample   9107   3.513 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.094           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.506           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.039           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.173           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.189           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.189           ms/op

Benchmark result is saved to 1717460141968.json
