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
# Warmup Iteration   1: 1.876 ops/ms
Iteration   1: 7.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.605 ops/ms


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
# Warmup Iteration   1: 6.203 ops/ms
Iteration   1: 14.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.320 ops/ms


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
# Warmup Iteration   1: 5.534 ops/ms
Iteration   1: 12.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.187 ops/ms


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
# Warmup Iteration   1: 3.939 ops/ms
Iteration   1: 9.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.366 ops/ms


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
# Warmup Iteration   1: 3.539 ±(99.9%) 0.061 ms/op
Iteration   1: 2.281 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.281 ms/op


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
# Warmup Iteration   1: 3.020 ±(99.9%) 0.051 ms/op
Iteration   1: 1.927 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.927 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.059 ms/op
Iteration   1: 1.890 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.890 ms/op


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.084 ms/op
Iteration   1: 3.546 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.546 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.624 ±(99.9%) 0.107 ms/op
Iteration   1: 2.213 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.579 ms/op
                 createUser·p0.50:   2.054 ms/op
                 createUser·p0.90:   2.810 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 19.775 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14998
  mean =      2.213 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 11366 
    [ 2.500,  3.750) = 3147 
    [ 3.750,  5.000) = 155 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     19.775 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 2.691 ±(99.9%) 0.058 ms/op
Iteration   1: 2.002 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.200 ms/op
                 existUser·p0.50:   1.933 ms/op
                 existUser·p0.90:   2.436 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   4.777 ms/op
                 existUser·p0.999:  22.020 ms/op
                 existUser·p0.9999: 22.617 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15982
  mean =      2.002 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14741 
    [ 2.500,  5.000) = 1113 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.200 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.436 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      4.777 ms/op
     p(99.9000) =     22.020 ms/op
     p(99.9900) =     22.617 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.080 ms/op
Iteration   1: 2.024 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.615 ms/op
                 getUser·p0.50:   1.931 ms/op
                 getUser·p0.90:   2.388 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   4.848 ms/op
                 getUser·p0.999:  11.016 ms/op
                 getUser·p0.9999: 11.276 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15819
  mean =      2.024 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 203 
    [ 1.250,  2.500) = 14539 
    [ 2.500,  3.750) = 802 
    [ 3.750,  5.000) = 141 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      4.848 ms/op
     p(99.9000) =     11.016 ms/op
     p(99.9900) =     11.276 ms/op
     p(99.9990) =     11.305 ms/op
     p(99.9999) =     11.305 ms/op
    p(100.0000) =     11.305 ms/op


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.107 ms/op
Iteration   1: 3.723 ±(99.9%) 0.082 ms/op
                 listUser·p0.00:   0.550 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   19.661 ms/op
                 listUser·p0.999:  24.707 ms/op
                 listUser·p0.9999: 25.395 ms/op
                 listUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8587
  mean =      3.723 ±(99.9%) 0.082 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1588 
    [ 2.500,  5.000) = 6459 
    [ 5.000,  7.500) = 311 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =     19.661 ms/op
     p(99.9000) =     24.707 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.605          ops/ms
ClientSimple.existUser                       thrpt         14.320          ops/ms
ClientSimple.getUser                         thrpt         12.187          ops/ms
ClientSimple.listUser                        thrpt          9.366          ops/ms
ClientSimple.createUser                       avgt          2.281           ms/op
ClientSimple.existUser                        avgt          1.927           ms/op
ClientSimple.getUser                          avgt          1.890           ms/op
ClientSimple.listUser                         avgt          3.546           ms/op
ClientSimple.createUser                     sample  14998   2.213 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.579           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.054           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.088           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.726           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.514           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.775           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.792           ms/op
ClientSimple.existUser                      sample  15982   2.002 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.200           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.933           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.436           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.777           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.020           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.617           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.675           ms/op
ClientSimple.getUser                        sample  15819   2.024 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.615           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.931           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.388           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.848           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.016           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.276           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.305           ms/op
ClientSimple.listUser                       sample   8587   3.723 ± 0.082   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.550           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.506           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.571           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample         19.661           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.707           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.395           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.395           ms/op

Benchmark result is saved to 1717243565502.json
