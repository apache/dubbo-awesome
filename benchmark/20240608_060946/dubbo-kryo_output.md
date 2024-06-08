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
# Warmup Iteration   1: 1.655 ops/ms
Iteration   1: 6.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.759 ops/ms


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
# Warmup Iteration   1: 5.421 ops/ms
Iteration   1: 12.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.633 ops/ms


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
# Warmup Iteration   1: 5.377 ops/ms
Iteration   1: 12.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.318 ops/ms


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
# Warmup Iteration   1: 4.891 ops/ms
Iteration   1: 8.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.639 ops/ms


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
# Warmup Iteration   1: 4.366 ±(99.9%) 0.090 ms/op
Iteration   1: 2.134 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.134 ms/op


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
# Warmup Iteration   1: 3.196 ±(99.9%) 0.061 ms/op
Iteration   1: 2.175 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.175 ms/op


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.080 ms/op
Iteration   1: 2.272 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.272 ms/op


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
# Warmup Iteration   1: 4.409 ±(99.9%) 0.092 ms/op
Iteration   1: 3.941 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.941 ms/op


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
# Warmup Iteration   1: 3.449 ±(99.9%) 0.088 ms/op
Iteration   1: 2.195 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.475 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.585 ms/op
                 createUser·p0.95:   2.929 ms/op
                 createUser·p0.99:   9.667 ms/op
                 createUser·p0.999:  22.076 ms/op
                 createUser·p0.9999: 23.006 ms/op
                 createUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14572
  mean =      2.195 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12741 
    [ 2.500,  5.000) = 1541 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     22.076 ms/op
     p(99.9900) =     23.006 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 3.232 ±(99.9%) 0.108 ms/op
Iteration   1: 1.912 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   1.759 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.450 ms/op
                 existUser·p0.99:   5.729 ms/op
                 existUser·p0.999:  19.464 ms/op
                 existUser·p0.9999: 19.661 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16716
  mean =      1.912 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 262 
    [ 1.250,  2.500) = 15733 
    [ 2.500,  3.750) = 461 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.450 ms/op
     p(99.0000) =      5.729 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 3.268 ±(99.9%) 0.092 ms/op
Iteration   1: 1.913 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.557 ms/op
                 getUser·p0.50:   1.735 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.769 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  16.843 ms/op
                 getUser·p0.9999: 17.312 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16723
  mean =      1.913 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 651 
    [ 1.250,  2.500) = 14532 
    [ 2.500,  3.750) = 1304 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     17.312 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 4.337 ±(99.9%) 0.128 ms/op
Iteration   1: 3.547 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   3.582 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.577 ms/op
                 listUser·p0.99:   6.257 ms/op
                 listUser·p0.999:  27.556 ms/op
                 listUser·p0.9999: 28.115 ms/op
                 listUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9024
  mean =      3.547 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1045 
    [ 2.500,  5.000) = 7680 
    [ 5.000,  7.500) = 258 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.582 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.577 ms/op
     p(99.0000) =      6.257 ms/op
     p(99.9000) =     27.556 ms/op
     p(99.9900) =     28.115 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.759          ops/ms
ClientSimple.existUser                       thrpt         12.633          ops/ms
ClientSimple.getUser                         thrpt         12.318          ops/ms
ClientSimple.listUser                        thrpt          8.639          ops/ms
ClientSimple.createUser                       avgt          2.134           ms/op
ClientSimple.existUser                        avgt          2.175           ms/op
ClientSimple.getUser                          avgt          2.272           ms/op
ClientSimple.listUser                         avgt          3.941           ms/op
ClientSimple.createUser                     sample  14572   2.195 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.475           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.667           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.076           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.006           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.036           ms/op
ClientSimple.existUser                      sample  16716   1.912 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.595           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.759           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.212           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.450           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.729           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.464           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.661           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.661           ms/op
ClientSimple.getUser                        sample  16723   1.913 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.557           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.735           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.858           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.843           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.312           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.400           ms/op
ClientSimple.listUser                       sample   9024   3.547 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.868           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.582           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.577           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.257           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.556           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.115           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.115           ms/op

Benchmark result is saved to 1717826712381.json
