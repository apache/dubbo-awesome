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
# Warmup Iteration   1: 1.768 ops/ms
Iteration   1: 7.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.724 ops/ms


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
# Warmup Iteration   1: 6.231 ops/ms
Iteration   1: 13.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.739 ops/ms


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
# Warmup Iteration   1: 5.890 ops/ms
Iteration   1: 11.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.914 ops/ms


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
# Warmup Iteration   1: 4.377 ops/ms
Iteration   1: 7.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.658 ops/ms


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.105 ms/op
Iteration   1: 2.079 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.079 ms/op


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
# Warmup Iteration   1: 3.411 ±(99.9%) 0.062 ms/op
Iteration   1: 1.894 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.894 ms/op


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.066 ms/op
Iteration   1: 2.099 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.099 ms/op


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.089 ms/op
Iteration   1: 3.414 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.414 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.086 ms/op
Iteration   1: 2.309 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.287 ms/op
                 createUser·p0.50:   2.146 ms/op
                 createUser·p0.90:   2.736 ms/op
                 createUser·p0.95:   3.027 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  15.172 ms/op
                 createUser·p0.9999: 15.848 ms/op
                 createUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13683
  mean =      2.309 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 236 
    [ 1.250,  2.500) = 10829 
    [ 2.500,  3.750) = 2328 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.287 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     15.848 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 3.267 ±(99.9%) 0.075 ms/op
Iteration   1: 1.859 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.483 ms/op
                 existUser·p0.50:   1.714 ms/op
                 existUser·p0.90:   2.245 ms/op
                 existUser·p0.95:   2.408 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  15.073 ms/op
                 existUser·p0.9999: 15.218 ms/op
                 existUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17223
  mean =      1.859 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 380 
    [ 1.250,  2.500) = 16214 
    [ 2.500,  3.750) = 370 
    [ 3.750,  5.000) = 112 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     15.218 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.248 ±(99.9%) 0.077 ms/op
Iteration   1: 1.892 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   1.772 ms/op
                 getUser·p0.90:   2.269 ms/op
                 getUser·p0.95:   2.511 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  11.633 ms/op
                 getUser·p0.9999: 12.124 ms/op
                 getUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16942
  mean =      1.892 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 15989 
    [ 2.500,  3.750) = 687 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     12.124 ms/op
     p(99.9990) =     12.124 ms/op
     p(99.9999) =     12.124 ms/op
    p(100.0000) =     12.124 ms/op


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.159 ms/op
Iteration   1: 3.500 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   3.342 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   5.535 ms/op
                 listUser·p0.999:  11.452 ms/op
                 listUser·p0.9999: 11.518 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9179
  mean =      3.500 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 291 
    [ 2.500,  3.750) = 5655 
    [ 3.750,  5.000) = 2979 
    [ 5.000,  6.250) = 216 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.535 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     11.518 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.724          ops/ms
ClientSimple.existUser                       thrpt         13.739          ops/ms
ClientSimple.getUser                         thrpt         11.914          ops/ms
ClientSimple.listUser                        thrpt          7.658          ops/ms
ClientSimple.createUser                       avgt          2.079           ms/op
ClientSimple.existUser                        avgt          1.894           ms/op
ClientSimple.getUser                          avgt          2.099           ms/op
ClientSimple.listUser                         avgt          3.414           ms/op
ClientSimple.createUser                     sample  13683   2.309 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.287           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.146           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.736           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.027           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.716           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.172           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.848           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.974           ms/op
ClientSimple.existUser                      sample  17223   1.859 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.483           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.714           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.245           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.579           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.073           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.218           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.254           ms/op
ClientSimple.getUser                        sample  16942   1.892 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.912           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.772           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.269           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.235           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.633           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.124           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.124           ms/op
ClientSimple.listUser                       sample   9179   3.500 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.966           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.342           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.535           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.452           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.518           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.518           ms/op

Benchmark result is saved to 1715450677335.json
