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
# Warmup Iteration   1: 0.857 ops/ms
Iteration   1: 6.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.132 ops/ms


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
# Warmup Iteration   1: 5.750 ops/ms
Iteration   1: 12.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.104 ops/ms


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
# Warmup Iteration   1: 6.249 ops/ms
Iteration   1: 13.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.680 ops/ms


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
# Warmup Iteration   1: 4.793 ops/ms
Iteration   1: 8.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.464 ops/ms


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.076 ms/op
Iteration   1: 2.265 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.265 ms/op


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
# Warmup Iteration   1: 2.999 ±(99.9%) 0.051 ms/op
Iteration   1: 1.976 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.976 ms/op


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
# Warmup Iteration   1: 3.266 ±(99.9%) 0.054 ms/op
Iteration   1: 1.977 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.977 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.080 ms/op
Iteration   1: 3.392 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.392 ms/op


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
# Warmup Iteration   1: 3.639 ±(99.9%) 0.085 ms/op
Iteration   1: 2.340 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.535 ms/op
                 createUser·p0.50:   2.130 ms/op
                 createUser·p0.90:   2.761 ms/op
                 createUser·p0.95:   3.391 ms/op
                 createUser·p0.99:   9.667 ms/op
                 createUser·p0.999:  14.866 ms/op
                 createUser·p0.9999: 16.706 ms/op
                 createUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13672
  mean =      2.340 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 11221 
    [ 2.500,  3.750) = 1738 
    [ 3.750,  5.000) = 233 
    [ 5.000,  6.250) = 116 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.391 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     14.866 ms/op
     p(99.9900) =     16.706 ms/op
     p(99.9990) =     16.712 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 2.961 ±(99.9%) 0.076 ms/op
Iteration   1: 2.050 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.498 ms/op
                 existUser·p0.50:   1.901 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   3.367 ms/op
                 existUser·p0.999:  18.907 ms/op
                 existUser·p0.9999: 19.409 ms/op
                 existUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15651
  mean =      2.050 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 14307 
    [ 2.500,  3.750) = 1108 
    [ 3.750,  5.000) = 9 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      3.367 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     19.409 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.095 ms/op
Iteration   1: 1.885 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   1.743 ms/op
                 getUser·p0.90:   2.318 ms/op
                 getUser·p0.95:   2.507 ms/op
                 getUser·p0.99:   4.445 ms/op
                 getUser·p0.999:  10.406 ms/op
                 getUser·p0.9999: 10.802 ms/op
                 getUser·p1.00:   10.813 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16943
  mean =      1.885 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 15932 
    [ 2.500,  3.750) = 659 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      1.743 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      4.445 ms/op
     p(99.9000) =     10.406 ms/op
     p(99.9900) =     10.802 ms/op
     p(99.9990) =     10.813 ms/op
     p(99.9999) =     10.813 ms/op
    p(100.0000) =     10.813 ms/op


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.128 ms/op
Iteration   1: 3.845 ±(99.9%) 0.063 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.670 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  29.022 ms/op
                 listUser·p0.9999: 30.343 ms/op
                 listUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8318
  mean =      3.845 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 345 
    [ 2.500,  5.000) = 7564 
    [ 5.000,  7.500) = 376 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.670 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     29.022 ms/op
     p(99.9900) =     30.343 ms/op
     p(99.9990) =     30.343 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.132          ops/ms
ClientSimple.existUser                       thrpt         12.104          ops/ms
ClientSimple.getUser                         thrpt         13.680          ops/ms
ClientSimple.listUser                        thrpt          8.464          ops/ms
ClientSimple.createUser                       avgt          2.265           ms/op
ClientSimple.existUser                        avgt          1.976           ms/op
ClientSimple.getUser                          avgt          1.977           ms/op
ClientSimple.listUser                         avgt          3.392           ms/op
ClientSimple.createUser                     sample  13672   2.340 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.535           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.130           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.391           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.667           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.866           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.706           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.712           ms/op
ClientSimple.existUser                      sample  15651   2.050 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.498           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.901           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.367           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.907           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.409           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.464           ms/op
ClientSimple.getUser                        sample  16943   1.885 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.764           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.743           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.318           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.445           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.406           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.802           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.813           ms/op
ClientSimple.listUser                       sample   8318   3.845 ± 0.063   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.208           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.777           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.670           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.963           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.022           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         30.343           ms/op
ClientSimple.listUser:listUser·p1.00        sample         30.343           ms/op

Benchmark result is saved to 1716271535125.json
