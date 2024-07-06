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
# Warmup Iteration   1: 1.794 ops/ms
Iteration   1: 6.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.893 ops/ms


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
# Warmup Iteration   1: 5.944 ops/ms
Iteration   1: 11.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.933 ops/ms


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
# Warmup Iteration   1: 6.139 ops/ms
Iteration   1: 13.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.429 ops/ms


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
# Warmup Iteration   1: 3.981 ops/ms
Iteration   1: 8.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.598 ops/ms


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.081 ms/op
Iteration   1: 2.145 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.145 ms/op


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
# Warmup Iteration   1: 3.079 ±(99.9%) 0.055 ms/op
Iteration   1: 1.773 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.773 ms/op


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
# Warmup Iteration   1: 3.073 ±(99.9%) 0.048 ms/op
Iteration   1: 2.035 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.035 ms/op


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
# Warmup Iteration   1: 4.397 ±(99.9%) 0.106 ms/op
Iteration   1: 3.040 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.040 ms/op


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
# Warmup Iteration   1: 3.506 ±(99.9%) 0.092 ms/op
Iteration   1: 2.200 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   1.985 ms/op
                 createUser·p0.90:   2.761 ms/op
                 createUser·p0.95:   2.961 ms/op
                 createUser·p0.99:   6.519 ms/op
                 createUser·p0.999:  13.639 ms/op
                 createUser·p0.9999: 14.315 ms/op
                 createUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14525
  mean =      2.200 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 11378 
    [ 2.500,  3.750) = 2634 
    [ 3.750,  5.000) = 164 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      6.519 ms/op
     p(99.9000) =     13.639 ms/op
     p(99.9900) =     14.315 ms/op
     p(99.9990) =     14.352 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.090 ms/op
Iteration   1: 2.076 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.505 ms/op
                 existUser·p0.50:   2.023 ms/op
                 existUser·p0.90:   2.646 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   3.258 ms/op
                 existUser·p0.999:  15.027 ms/op
                 existUser·p0.9999: 15.252 ms/op
                 existUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15453
  mean =      2.076 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 12645 
    [ 2.500,  3.750) = 2588 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.258 ms/op
     p(99.9000) =     15.027 ms/op
     p(99.9900) =     15.252 ms/op
     p(99.9990) =     15.270 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 3.194 ±(99.9%) 0.072 ms/op
Iteration   1: 2.150 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.118 ms/op
                 getUser·p0.90:   2.613 ms/op
                 getUser·p0.95:   2.782 ms/op
                 getUser·p0.99:   3.338 ms/op
                 getUser·p0.999:  12.208 ms/op
                 getUser·p0.9999: 12.543 ms/op
                 getUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14876
  mean =      2.150 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 12241 
    [ 2.500,  3.750) = 2424 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.782 ms/op
     p(99.0000) =      3.338 ms/op
     p(99.9000) =     12.208 ms/op
     p(99.9900) =     12.543 ms/op
     p(99.9990) =     12.583 ms/op
     p(99.9999) =     12.583 ms/op
    p(100.0000) =     12.583 ms/op


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.153 ms/op
Iteration   1: 3.620 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  12.381 ms/op
                 listUser·p0.9999: 12.763 ms/op
                 listUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8833
  mean =      3.620 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 422 
    [ 2.500,  3.750) = 5123 
    [ 3.750,  5.000) = 3081 
    [ 5.000,  6.250) = 139 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     12.381 ms/op
     p(99.9900) =     12.763 ms/op
     p(99.9990) =     12.763 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.893          ops/ms
ClientSimple.existUser                       thrpt         11.933          ops/ms
ClientSimple.getUser                         thrpt         13.429          ops/ms
ClientSimple.listUser                        thrpt          8.598          ops/ms
ClientSimple.createUser                       avgt          2.145           ms/op
ClientSimple.existUser                        avgt          1.773           ms/op
ClientSimple.getUser                          avgt          2.035           ms/op
ClientSimple.listUser                         avgt          3.040           ms/op
ClientSimple.createUser                     sample  14525   2.200 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.577           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.985           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.519           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.639           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.315           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.352           ms/op
ClientSimple.existUser                      sample  15453   2.076 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.505           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.023           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.646           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.258           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.027           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.252           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.270           ms/op
ClientSimple.getUser                        sample  14876   2.150 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.736           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.782           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.338           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.208           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.543           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.583           ms/op
ClientSimple.listUser                       sample   8833   3.620 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.405           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.596           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.751           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.381           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.763           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.763           ms/op

Benchmark result is saved to 1720224945023.json
