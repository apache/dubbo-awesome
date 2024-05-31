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
# Warmup Iteration   1: 1.570 ops/ms
Iteration   1: 7.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.061 ops/ms


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
# Warmup Iteration   1: 6.274 ops/ms
Iteration   1: 11.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.559 ops/ms


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
# Warmup Iteration   1: 5.443 ops/ms
Iteration   1: 12.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.357 ops/ms


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
# Warmup Iteration   1: 5.031 ops/ms
Iteration   1: 9.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.015 ops/ms


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
# Warmup Iteration   1: 4.433 ±(99.9%) 0.094 ms/op
Iteration   1: 2.256 ±(99.9%) 0.005 ms/op


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.056 ms/op
Iteration   1: 1.755 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.755 ms/op


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
# Warmup Iteration   1: 3.115 ±(99.9%) 0.055 ms/op
Iteration   1: 2.085 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.085 ms/op


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.067 ms/op
Iteration   1: 3.073 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.073 ms/op


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
# Warmup Iteration   1: 3.346 ±(99.9%) 0.098 ms/op
Iteration   1: 2.158 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.455 ms/op
                 createUser·p0.50:   2.030 ms/op
                 createUser·p0.90:   2.597 ms/op
                 createUser·p0.95:   2.790 ms/op
                 createUser·p0.99:   6.166 ms/op
                 createUser·p0.999:  20.597 ms/op
                 createUser·p0.9999: 21.201 ms/op
                 createUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14936
  mean =      2.158 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12732 
    [ 2.500,  5.000) = 1995 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.790 ms/op
     p(99.0000) =      6.166 ms/op
     p(99.9000) =     20.597 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 2.996 ±(99.9%) 0.076 ms/op
Iteration   1: 1.582 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   1.468 ms/op
                 existUser·p0.90:   1.937 ms/op
                 existUser·p0.95:   2.150 ms/op
                 existUser·p0.99:   2.847 ms/op
                 existUser·p0.999:  15.483 ms/op
                 existUser·p0.9999: 15.581 ms/op
                 existUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 20330
  mean =      1.582 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1584 
    [ 1.250,  2.500) = 18364 
    [ 2.500,  3.750) = 254 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      1.468 ms/op
     p(90.0000) =      1.937 ms/op
     p(95.0000) =      2.150 ms/op
     p(99.0000) =      2.847 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     15.581 ms/op
     p(99.9990) =     15.581 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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
# Warmup Iteration   1: 3.348 ±(99.9%) 0.090 ms/op
Iteration   1: 1.947 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   1.774 ms/op
                 getUser·p0.90:   2.376 ms/op
                 getUser·p0.95:   2.568 ms/op
                 getUser·p0.99:   3.255 ms/op
                 getUser·p0.999:  27.050 ms/op
                 getUser·p0.9999: 27.700 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16485
  mean =      1.947 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15456 
    [ 2.500,  5.000) = 992 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.255 ms/op
     p(99.9000) =     27.050 ms/op
     p(99.9900) =     27.700 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.130 ms/op
Iteration   1: 3.381 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.754 ms/op
                 listUser·p0.50:   3.363 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.597 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9468
  mean =      3.381 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1255 
    [ 2.500,  3.750) = 5557 
    [ 3.750,  5.000) = 2383 
    [ 5.000,  6.250) = 122 
    [ 6.250,  7.500) = 106 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.597 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.061          ops/ms
ClientSimple.existUser                       thrpt         11.559          ops/ms
ClientSimple.getUser                         thrpt         12.357          ops/ms
ClientSimple.listUser                        thrpt          9.015          ops/ms
ClientSimple.createUser                       avgt          2.256           ms/op
ClientSimple.existUser                        avgt          1.755           ms/op
ClientSimple.getUser                          avgt          2.085           ms/op
ClientSimple.listUser                         avgt          3.073           ms/op
ClientSimple.createUser                     sample  14936   2.158 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.455           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.030           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.790           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.166           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.597           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.201           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.201           ms/op
ClientSimple.existUser                      sample  20330   1.582 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.761           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.468           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.937           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.847           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.483           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.581           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.581           ms/op
ClientSimple.getUser                        sample  16485   1.947 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.878           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.774           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.255           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.050           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.700           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.722           ms/op
ClientSimple.listUser                       sample   9468   3.381 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.754           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.363           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.597           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.105           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.383           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.383           ms/op

Benchmark result is saved to 1717114522695.json
