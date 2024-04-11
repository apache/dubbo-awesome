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
# Warmup Iteration   1: 1.714 ops/ms
Iteration   1: 6.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.718 ops/ms


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
# Warmup Iteration   1: 6.689 ops/ms
Iteration   1: 13.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.010 ops/ms


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
# Warmup Iteration   1: 5.835 ops/ms
Iteration   1: 14.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.324 ops/ms


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
# Warmup Iteration   1: 5.205 ops/ms
Iteration   1: 7.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.872 ops/ms


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.080 ms/op
Iteration   1: 2.291 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.291 ms/op


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
# Warmup Iteration   1: 2.960 ±(99.9%) 0.064 ms/op
Iteration   1: 1.922 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.922 ms/op


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
# Warmup Iteration   1: 3.402 ±(99.9%) 0.054 ms/op
Iteration   1: 2.105 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.105 ms/op


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
# Warmup Iteration   1: 4.458 ±(99.9%) 0.099 ms/op
Iteration   1: 3.039 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.039 ms/op


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.132 ms/op
Iteration   1: 2.269 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.028 ms/op
                 createUser·p0.90:   2.925 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   5.192 ms/op
                 createUser·p0.999:  16.384 ms/op
                 createUser·p0.9999: 16.997 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14262
  mean =      2.269 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 10840 
    [ 2.500,  3.750) = 3057 
    [ 3.750,  5.000) = 139 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      5.192 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     16.997 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 2.926 ±(99.9%) 0.064 ms/op
Iteration   1: 1.732 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   1.585 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   2.916 ms/op
                 existUser·p0.999:  13.657 ms/op
                 existUser·p0.9999: 14.341 ms/op
                 existUser·p1.00:   14.549 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18465
  mean =      1.732 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2151 
    [ 1.250,  2.500) = 15512 
    [ 2.500,  3.750) = 742 
    [ 3.750,  5.000) = 13 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      1.585 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      2.916 ms/op
     p(99.9000) =     13.657 ms/op
     p(99.9900) =     14.341 ms/op
     p(99.9990) =     14.549 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.416 ±(99.9%) 0.098 ms/op
Iteration   1: 2.172 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.333 ms/op
                 getUser·p0.50:   2.066 ms/op
                 getUser·p0.90:   2.624 ms/op
                 getUser·p0.95:   2.798 ms/op
                 getUser·p0.99:   3.341 ms/op
                 getUser·p0.999:  26.903 ms/op
                 getUser·p0.9999: 27.641 ms/op
                 getUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14632
  mean =      2.172 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12500 
    [ 2.500,  5.000) = 2035 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.624 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.341 ms/op
     p(99.9000) =     26.903 ms/op
     p(99.9900) =     27.641 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 4.469 ±(99.9%) 0.147 ms/op
Iteration   1: 3.188 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.157 ms/op
                 listUser·p0.999:  7.152 ms/op
                 listUser·p0.9999: 7.421 ms/op
                 listUser·p1.00:   7.422 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10038
  mean =      3.188 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 0 
    [1.500, 2.000) = 34 
    [2.000, 2.500) = 355 
    [2.500, 3.000) = 5013 
    [3.000, 3.500) = 2021 
    [3.500, 4.000) = 1575 
    [4.000, 4.500) = 641 
    [4.500, 5.000) = 175 
    [5.000, 5.500) = 49 
    [5.500, 6.000) = 33 
    [6.000, 6.500) = 86 
    [6.500, 7.000) = 25 
    [7.000, 7.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.157 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =      7.421 ms/op
     p(99.9990) =      7.422 ms/op
     p(99.9999) =      7.422 ms/op
    p(100.0000) =      7.422 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.718          ops/ms
ClientSimple.existUser                       thrpt         13.010          ops/ms
ClientSimple.getUser                         thrpt         14.324          ops/ms
ClientSimple.listUser                        thrpt          7.872          ops/ms
ClientSimple.createUser                       avgt          2.291           ms/op
ClientSimple.existUser                        avgt          1.922           ms/op
ClientSimple.getUser                          avgt          2.105           ms/op
ClientSimple.listUser                         avgt          3.039           ms/op
ClientSimple.createUser                     sample  14262   2.269 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.996           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.028           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.925           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.166           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.192           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.384           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.997           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.039           ms/op
ClientSimple.existUser                      sample  18465   1.732 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.503           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.585           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.916           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.657           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.341           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.549           ms/op
ClientSimple.getUser                        sample  14632   2.172 ± 0.038   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.333           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.066           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.624           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.341           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.903           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.641           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.656           ms/op
ClientSimple.listUser                       sample  10038   3.188 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.624           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.957           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.010           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.157           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.152           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.421           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.422           ms/op

Benchmark result is saved to 1712815518390.json
