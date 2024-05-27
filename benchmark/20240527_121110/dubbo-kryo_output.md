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
# Warmup Iteration   1: 1.669 ops/ms
Iteration   1: 6.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.340 ops/ms


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
# Warmup Iteration   1: 4.977 ops/ms
Iteration   1: 13.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.361 ops/ms


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
# Warmup Iteration   1: 4.474 ops/ms
Iteration   1: 10.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.563 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ops/ms
Iteration   1: 8.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.312 ops/ms


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.096 ms/op
Iteration   1: 2.373 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.373 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.055 ms/op
Iteration   1: 1.881 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.881 ms/op


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
# Warmup Iteration   1: 3.446 ±(99.9%) 0.058 ms/op
Iteration   1: 1.956 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.956 ms/op


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
# Warmup Iteration   1: 5.037 ±(99.9%) 0.111 ms/op
Iteration   1: 3.202 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.202 ms/op


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.105 ms/op
Iteration   1: 2.336 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.513 ms/op
                 createUser·p0.50:   2.146 ms/op
                 createUser·p0.90:   2.888 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   11.010 ms/op
                 createUser·p0.999:  15.160 ms/op
                 createUser·p0.9999: 15.762 ms/op
                 createUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13678
  mean =      2.336 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 366 
    [ 1.250,  2.500) = 9830 
    [ 2.500,  3.750) = 3040 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 119 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     15.160 ms/op
     p(99.9900) =     15.762 ms/op
     p(99.9990) =     15.811 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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
# Warmup Iteration   1: 3.126 ±(99.9%) 0.072 ms/op
Iteration   1: 1.806 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.481 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   2.083 ms/op
                 existUser·p0.95:   2.236 ms/op
                 existUser·p0.99:   3.444 ms/op
                 existUser·p0.999:  11.310 ms/op
                 existUser·p0.9999: 12.369 ms/op
                 existUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17704
  mean =      1.806 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 17057 
    [ 2.500,  3.750) = 326 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      2.083 ms/op
     p(95.0000) =      2.236 ms/op
     p(99.0000) =      3.444 ms/op
     p(99.9000) =     11.310 ms/op
     p(99.9900) =     12.369 ms/op
     p(99.9990) =     13.468 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


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
# Warmup Iteration   1: 3.634 ±(99.9%) 0.107 ms/op
Iteration   1: 2.126 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.435 ms/op
                 getUser·p0.50:   1.966 ms/op
                 getUser·p0.90:   2.720 ms/op
                 getUser·p0.95:   3.002 ms/op
                 getUser·p0.99:   5.145 ms/op
                 getUser·p0.999:  14.172 ms/op
                 getUser·p0.9999: 14.998 ms/op
                 getUser·p1.00:   15.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15151
  mean =      2.126 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 12390 
    [ 2.500,  3.750) = 2370 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     14.998 ms/op
     p(99.9990) =     15.057 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.121 ms/op
Iteration   1: 3.461 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   3.400 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   6.321 ms/op
                 listUser·p0.999:  9.294 ms/op
                 listUser·p0.9999: 9.732 ms/op
                 listUser·p1.00:   9.732 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9260
  mean =      3.461 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 84 
    [ 2.000,  3.000) = 3027 
    [ 3.000,  4.000) = 4221 
    [ 4.000,  5.000) = 1559 
    [ 5.000,  6.000) = 262 
    [ 6.000,  7.000) = 39 
    [ 7.000,  8.000) = 23 
    [ 8.000,  9.000) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.321 ms/op
     p(99.9000) =      9.294 ms/op
     p(99.9900) =      9.732 ms/op
     p(99.9990) =      9.732 ms/op
     p(99.9999) =      9.732 ms/op
    p(100.0000) =      9.732 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.340          ops/ms
ClientSimple.existUser                       thrpt         13.361          ops/ms
ClientSimple.getUser                         thrpt         10.563          ops/ms
ClientSimple.listUser                        thrpt          8.312          ops/ms
ClientSimple.createUser                       avgt          2.373           ms/op
ClientSimple.existUser                        avgt          1.881           ms/op
ClientSimple.getUser                          avgt          1.956           ms/op
ClientSimple.listUser                         avgt          3.202           ms/op
ClientSimple.createUser                     sample  13678   2.336 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.513           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.146           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.273           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.010           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.160           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.762           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.811           ms/op
ClientSimple.existUser                      sample  17704   1.806 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.481           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.083           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.444           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.310           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.369           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.468           ms/op
ClientSimple.getUser                        sample  15151   2.126 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.435           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.966           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.002           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.145           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.172           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.998           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.057           ms/op
ClientSimple.listUser                       sample   9260   3.461 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.974           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.400           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.891           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.321           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.294           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.732           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.732           ms/op

Benchmark result is saved to 1716811601891.json
