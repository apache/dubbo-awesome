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
# Warmup Iteration   1: 1.887 ops/ms
Iteration   1: 7.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.191 ops/ms


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
# Warmup Iteration   1: 6.737 ops/ms
Iteration   1: 14.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.095 ops/ms


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
# Warmup Iteration   1: 5.418 ops/ms
Iteration   1: 12.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.387 ops/ms


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
# Warmup Iteration   1: 5.058 ops/ms
Iteration   1: 9.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.440 ops/ms


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.069 ms/op
Iteration   1: 2.356 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.356 ms/op


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
# Warmup Iteration   1: 2.926 ±(99.9%) 0.043 ms/op
Iteration   1: 1.837 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.837 ms/op


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
# Warmup Iteration   1: 3.179 ±(99.9%) 0.052 ms/op
Iteration   1: 1.749 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.749 ms/op


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
# Warmup Iteration   1: 4.756 ±(99.9%) 0.099 ms/op
Iteration   1: 3.171 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.171 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.128 ms/op
Iteration   1: 2.172 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   2.055 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.781 ms/op
                 createUser·p0.99:   9.022 ms/op
                 createUser·p0.999:  15.324 ms/op
                 createUser·p0.9999: 16.279 ms/op
                 createUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14716
  mean =      2.172 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 450 
    [ 1.250,  2.500) = 12631 
    [ 2.500,  3.750) = 1341 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.055 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      9.022 ms/op
     p(99.9000) =     15.324 ms/op
     p(99.9900) =     16.279 ms/op
     p(99.9990) =     16.581 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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
# Warmup Iteration   1: 3.130 ±(99.9%) 0.082 ms/op
Iteration   1: 1.914 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   1.815 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   2.884 ms/op
                 existUser·p0.999:  17.826 ms/op
                 existUser·p0.9999: 18.567 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16701
  mean =      1.914 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 15918 
    [ 2.500,  3.750) = 465 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      2.884 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     18.567 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.276 ms/op
Iteration   1: 2.288 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   2.220 ms/op
                 getUser·p0.90:   2.875 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.870 ms/op
                 getUser·p0.999:  10.305 ms/op
                 getUser·p0.9999: 11.275 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14012
  mean =      2.288 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 10514 
    [ 2.500,  3.750) = 3134 
    [ 3.750,  5.000) = 121 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.870 ms/op
     p(99.9000) =     10.305 ms/op
     p(99.9900) =     11.275 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


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
# Warmup Iteration   1: 4.708 ±(99.9%) 0.155 ms/op
Iteration   1: 3.377 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   3.437 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.174 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 15.532 ms/op
                 listUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9465
  mean =      3.377 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 1431 
    [ 2.500,  3.750) = 5503 
    [ 3.750,  5.000) = 2166 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.174 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     15.532 ms/op
     p(99.9990) =     15.532 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.191          ops/ms
ClientSimple.existUser                       thrpt         14.095          ops/ms
ClientSimple.getUser                         thrpt         12.387          ops/ms
ClientSimple.listUser                        thrpt          9.440          ops/ms
ClientSimple.createUser                       avgt          2.356           ms/op
ClientSimple.existUser                        avgt          1.837           ms/op
ClientSimple.getUser                          avgt          1.749           ms/op
ClientSimple.listUser                         avgt          3.171           ms/op
ClientSimple.createUser                     sample  14716   2.172 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.733           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.055           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.022           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.324           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.279           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.581           ms/op
ClientSimple.existUser                      sample  16701   1.914 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.644           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.815           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.884           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.826           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.567           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.809           ms/op
ClientSimple.getUser                        sample  14012   2.288 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.695           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.220           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.232           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.870           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.305           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.275           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.518           ms/op
ClientSimple.listUser                       sample   9465   3.377 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.835           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.437           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.153           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.174           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.795           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.532           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.532           ms/op

Benchmark result is saved to 1716682615276.json
