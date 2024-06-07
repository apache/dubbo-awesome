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
# Warmup Iteration   1: 1.470 ops/ms
Iteration   1: 7.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.415 ops/ms


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
# Warmup Iteration   1: 5.478 ops/ms
Iteration   1: 11.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.654 ops/ms


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
# Warmup Iteration   1: 5.783 ops/ms
Iteration   1: 10.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.997 ops/ms


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
# Warmup Iteration   1: 4.938 ops/ms
Iteration   1: 7.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.968 ops/ms


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.073 ms/op
Iteration   1: 2.256 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.256 ms/op


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
# Warmup Iteration   1: 3.201 ±(99.9%) 0.062 ms/op
Iteration   1: 1.907 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.907 ms/op


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
# Warmup Iteration   1: 3.475 ±(99.9%) 0.077 ms/op
Iteration   1: 1.936 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.936 ms/op


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
# Warmup Iteration   1: 4.521 ±(99.9%) 0.087 ms/op
Iteration   1: 3.487 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.487 ms/op


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
# Warmup Iteration   1: 3.435 ±(99.9%) 0.086 ms/op
Iteration   1: 2.263 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   2.167 ms/op
                 createUser·p0.90:   2.716 ms/op
                 createUser·p0.95:   3.015 ms/op
                 createUser·p0.99:   8.143 ms/op
                 createUser·p0.999:  16.196 ms/op
                 createUser·p0.9999: 16.590 ms/op
                 createUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14125
  mean =      2.263 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 11032 
    [ 2.500,  3.750) = 2787 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     16.196 ms/op
     p(99.9900) =     16.590 ms/op
     p(99.9990) =     16.597 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 3.070 ±(99.9%) 0.076 ms/op
Iteration   1: 1.855 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   1.700 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.551 ms/op
                 existUser·p0.99:   4.803 ms/op
                 existUser·p0.999:  15.872 ms/op
                 existUser·p0.9999: 16.164 ms/op
                 existUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17244
  mean =      1.855 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 599 
    [ 1.250,  2.500) = 15669 
    [ 2.500,  3.750) = 732 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      1.700 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.551 ms/op
     p(99.0000) =      4.803 ms/op
     p(99.9000) =     15.872 ms/op
     p(99.9900) =     16.164 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 3.395 ±(99.9%) 0.086 ms/op
Iteration   1: 2.050 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   1.989 ms/op
                 getUser·p0.90:   2.556 ms/op
                 getUser·p0.95:   2.741 ms/op
                 getUser·p0.99:   3.959 ms/op
                 getUser·p0.999:  11.928 ms/op
                 getUser·p0.9999: 12.495 ms/op
                 getUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15656
  mean =      2.050 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 453 
    [ 1.250,  2.500) = 13313 
    [ 2.500,  3.750) = 1721 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.741 ms/op
     p(99.0000) =      3.959 ms/op
     p(99.9000) =     11.928 ms/op
     p(99.9900) =     12.495 ms/op
     p(99.9990) =     12.550 ms/op
     p(99.9999) =     12.550 ms/op
    p(100.0000) =     12.550 ms/op


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
# Warmup Iteration   1: 4.417 ±(99.9%) 0.135 ms/op
Iteration   1: 3.572 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.169 ms/op
                 listUser·p0.999:  7.291 ms/op
                 listUser·p0.9999: 7.905 ms/op
                 listUser·p1.00:   7.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8988
  mean =      3.572 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 1 
    [1.500, 2.000) = 64 
    [2.000, 2.500) = 324 
    [2.500, 3.000) = 918 
    [3.000, 3.500) = 2493 
    [3.500, 4.000) = 3487 
    [4.000, 4.500) = 1324 
    [4.500, 5.000) = 277 
    [5.000, 5.500) = 48 
    [5.500, 6.000) = 12 
    [6.000, 6.500) = 8 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =      7.291 ms/op
     p(99.9900) =      7.905 ms/op
     p(99.9990) =      7.905 ms/op
     p(99.9999) =      7.905 ms/op
    p(100.0000) =      7.905 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.415          ops/ms
ClientSimple.existUser                       thrpt         11.654          ops/ms
ClientSimple.getUser                         thrpt         10.997          ops/ms
ClientSimple.listUser                        thrpt          7.968          ops/ms
ClientSimple.createUser                       avgt          2.256           ms/op
ClientSimple.existUser                        avgt          1.907           ms/op
ClientSimple.getUser                          avgt          1.936           ms/op
ClientSimple.listUser                         avgt          3.487           ms/op
ClientSimple.createUser                     sample  14125   2.263 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.522           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.167           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.143           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.196           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.590           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.597           ms/op
ClientSimple.existUser                      sample  17244   1.855 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.686           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.700           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.551           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.803           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.872           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.164           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.318           ms/op
ClientSimple.getUser                        sample  15656   2.050 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.610           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.989           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.741           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.959           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.928           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.495           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.550           ms/op
ClientSimple.listUser                       sample   8988   3.572 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.391           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.600           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.169           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.291           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.905           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.905           ms/op

Benchmark result is saved to 1717783547470.json
