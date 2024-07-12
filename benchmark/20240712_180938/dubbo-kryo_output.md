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
# Warmup Iteration   1: 2.162 ops/ms
Iteration   1: 7.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.073 ops/ms


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
# Warmup Iteration   1: 6.183 ops/ms
Iteration   1: 12.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.865 ops/ms


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
# Warmup Iteration   1: 6.179 ops/ms
Iteration   1: 13.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.713 ops/ms


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
# Warmup Iteration   1: 5.219 ops/ms
Iteration   1: 7.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.769 ops/ms


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.073 ms/op
Iteration   1: 2.330 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.330 ms/op


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
# Warmup Iteration   1: 3.409 ±(99.9%) 0.058 ms/op
Iteration   1: 1.818 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.818 ms/op


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
# Warmup Iteration   1: 3.121 ±(99.9%) 0.054 ms/op
Iteration   1: 1.841 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.841 ms/op


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
# Warmup Iteration   1: 4.515 ±(99.9%) 0.092 ms/op
Iteration   1: 3.366 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.366 ms/op


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
# Warmup Iteration   1: 3.472 ±(99.9%) 0.084 ms/op
Iteration   1: 1.948 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   1.720 ms/op
                 createUser·p0.90:   2.363 ms/op
                 createUser·p0.95:   2.576 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  18.497 ms/op
                 createUser·p0.9999: 19.383 ms/op
                 createUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16390
  mean =      1.948 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 434 
    [ 1.250,  2.500) = 14879 
    [ 2.500,  3.750) = 630 
    [ 3.750,  5.000) = 162 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      1.720 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     18.497 ms/op
     p(99.9900) =     19.383 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 2.848 ±(99.9%) 0.060 ms/op
Iteration   1: 1.708 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   1.550 ms/op
                 existUser·p0.90:   2.109 ms/op
                 existUser·p0.95:   2.359 ms/op
                 existUser·p0.99:   3.384 ms/op
                 existUser·p0.999:  18.973 ms/op
                 existUser·p0.9999: 19.145 ms/op
                 existUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18675
  mean =      1.708 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1081 
    [ 1.250,  2.500) = 16942 
    [ 2.500,  3.750) = 533 
    [ 3.750,  5.000) = 8 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      1.550 ms/op
     p(90.0000) =      2.109 ms/op
     p(95.0000) =      2.359 ms/op
     p(99.0000) =      3.384 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     19.145 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 3.359 ±(99.9%) 0.087 ms/op
Iteration   1: 1.953 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.310 ms/op
                 getUser·p0.95:   2.577 ms/op
                 getUser·p0.99:   3.556 ms/op
                 getUser·p0.999:  11.747 ms/op
                 getUser·p0.9999: 12.122 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16378
  mean =      1.953 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 15344 
    [ 2.500,  3.750) = 896 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.577 ms/op
     p(99.0000) =      3.556 ms/op
     p(99.9000) =     11.747 ms/op
     p(99.9900) =     12.122 ms/op
     p(99.9990) =     12.206 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


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
# Warmup Iteration   1: 4.629 ±(99.9%) 0.128 ms/op
Iteration   1: 3.443 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   0.658 ms/op
                 listUser·p0.50:   3.260 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   14.402 ms/op
                 listUser·p0.999:  17.094 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9341
  mean =      3.443 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 1247 
    [ 2.500,  3.750) = 4827 
    [ 3.750,  5.000) = 3019 
    [ 5.000,  6.250) = 136 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =     14.402 ms/op
     p(99.9000) =     17.094 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.073          ops/ms
ClientSimple.existUser                       thrpt         12.865          ops/ms
ClientSimple.getUser                         thrpt         13.713          ops/ms
ClientSimple.listUser                        thrpt          7.769          ops/ms
ClientSimple.createUser                       avgt          2.330           ms/op
ClientSimple.existUser                        avgt          1.818           ms/op
ClientSimple.getUser                          avgt          1.841           ms/op
ClientSimple.listUser                         avgt          3.366           ms/op
ClientSimple.createUser                     sample  16390   1.948 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.886           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.720           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.363           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.356           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.497           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.383           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.530           ms/op
ClientSimple.existUser                      sample  18675   1.708 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.643           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.550           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.109           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.384           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.973           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.145           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.202           ms/op
ClientSimple.getUser                        sample  16378   1.953 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.755           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.310           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.577           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.556           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.747           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.122           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.206           ms/op
ClientSimple.listUser                       sample   9341   3.443 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.658           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.260           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.596           ms/op
ClientSimple.listUser:listUser·p0.99        sample         14.402           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.094           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.891           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.891           ms/op

Benchmark result is saved to 1720807524387.json
