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
# Warmup Iteration   1: 1.304 ops/ms
Iteration   1: 7.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.155 ops/ms


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
# Warmup Iteration   1: 5.027 ops/ms
Iteration   1: 10.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.562 ops/ms


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
# Warmup Iteration   1: 4.508 ops/ms
Iteration   1: 12.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.718 ops/ms


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
# Warmup Iteration   1: 4.329 ops/ms
Iteration   1: 8.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.164 ops/ms


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.073 ms/op
Iteration   1: 2.208 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.208 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.063 ms/op
Iteration   1: 2.022 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.022 ms/op


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
# Warmup Iteration   1: 3.385 ±(99.9%) 0.056 ms/op
Iteration   1: 1.971 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.971 ms/op


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
# Warmup Iteration   1: 4.828 ±(99.9%) 0.106 ms/op
Iteration   1: 3.624 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.624 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.118 ms/op
Iteration   1: 2.143 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   2.021 ms/op
                 createUser·p0.90:   2.585 ms/op
                 createUser·p0.95:   2.961 ms/op
                 createUser·p0.99:   7.540 ms/op
                 createUser·p0.999:  16.747 ms/op
                 createUser·p0.9999: 20.532 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14858
  mean =      2.143 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12987 
    [ 2.500,  5.000) = 1694 
    [ 5.000,  7.500) = 28 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.021 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      7.540 ms/op
     p(99.9000) =     16.747 ms/op
     p(99.9900) =     20.532 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.098 ms/op
Iteration   1: 1.833 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   1.640 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   3.146 ms/op
                 existUser·p0.999:  15.754 ms/op
                 existUser·p0.9999: 16.078 ms/op
                 existUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17446
  mean =      1.833 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 947 
    [ 1.250,  2.500) = 15104 
    [ 2.500,  3.750) = 1295 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      1.640 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.146 ms/op
     p(99.9000) =     15.754 ms/op
     p(99.9900) =     16.078 ms/op
     p(99.9990) =     16.187 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 3.570 ±(99.9%) 0.090 ms/op
Iteration   1: 2.046 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   1.921 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.748 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  14.320 ms/op
                 getUser·p0.9999: 15.996 ms/op
                 getUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15628
  mean =      2.046 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 13434 
    [ 2.500,  3.750) = 1962 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     15.996 ms/op
     p(99.9990) =     16.024 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


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
# Warmup Iteration   1: 5.336 ±(99.9%) 0.161 ms/op
Iteration   1: 3.586 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   3.510 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8930
  mean =      3.586 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 701 
    [ 2.500,  3.750) = 5199 
    [ 3.750,  5.000) = 2624 
    [ 5.000,  6.250) = 277 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.155          ops/ms
ClientSimple.existUser                       thrpt         10.562          ops/ms
ClientSimple.getUser                         thrpt         12.718          ops/ms
ClientSimple.listUser                        thrpt          8.164          ops/ms
ClientSimple.createUser                       avgt          2.208           ms/op
ClientSimple.existUser                        avgt          2.022           ms/op
ClientSimple.getUser                          avgt          1.971           ms/op
ClientSimple.listUser                         avgt          3.624           ms/op
ClientSimple.createUser                     sample  14858   2.143 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.848           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.021           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.540           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.747           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.532           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.644           ms/op
ClientSimple.existUser                      sample  17446   1.833 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.695           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.640           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.146           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.754           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.078           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.187           ms/op
ClientSimple.getUser                        sample  15628   2.046 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.593           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.921           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.654           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.320           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.996           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.024           ms/op
ClientSimple.listUser                       sample   8930   3.586 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.884           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.510           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.832           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.874           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.956           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.956           ms/op

Benchmark result is saved to 1721175408966.json
