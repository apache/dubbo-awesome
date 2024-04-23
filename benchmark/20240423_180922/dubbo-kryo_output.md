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
# Warmup Iteration   1: 1.944 ops/ms
Iteration   1: 6.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.569 ops/ms


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
# Warmup Iteration   1: 4.773 ops/ms
Iteration   1: 11.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.520 ops/ms


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
# Warmup Iteration   1: 6.185 ops/ms
Iteration   1: 13.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.881 ops/ms


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
# Warmup Iteration   1: 5.155 ops/ms
Iteration   1: 8.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.651 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.556 ±(99.9%) 0.069 ms/op
Iteration   1: 2.115 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.115 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.329 ±(99.9%) 0.052 ms/op
Iteration   1: 2.008 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.008 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.324 ±(99.9%) 0.067 ms/op
Iteration   1: 2.027 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.027 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.456 ±(99.9%) 0.102 ms/op
Iteration   1: 3.622 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.622 ms/op


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.128 ms/op
Iteration   1: 2.127 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.423 ms/op
                 createUser·p0.50:   2.007 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   2.785 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  15.605 ms/op
                 createUser·p0.9999: 19.556 ms/op
                 createUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15494
  mean =      2.127 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 192 
    [ 1.250,  2.500) = 12825 
    [ 2.500,  3.750) = 2298 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =     15.605 ms/op
     p(99.9900) =     19.556 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.079 ms/op
Iteration   1: 1.912 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.318 ms/op
                 existUser·p0.95:   2.503 ms/op
                 existUser·p0.99:   3.105 ms/op
                 existUser·p0.999:  12.980 ms/op
                 existUser·p0.9999: 14.127 ms/op
                 existUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16756
  mean =      1.912 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 15726 
    [ 2.500,  3.750) = 737 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.105 ms/op
     p(99.9000) =     12.980 ms/op
     p(99.9900) =     14.127 ms/op
     p(99.9990) =     14.205 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.497 ±(99.9%) 0.111 ms/op
Iteration   1: 1.938 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.451 ms/op
                 getUser·p0.50:   1.841 ms/op
                 getUser·p0.90:   2.499 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   3.470 ms/op
                 getUser·p0.999:  12.730 ms/op
                 getUser·p0.9999: 13.600 ms/op
                 getUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16493
  mean =      1.938 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 488 
    [ 1.250,  2.500) = 14363 
    [ 2.500,  3.750) = 1508 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.470 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     13.600 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 5.040 ±(99.9%) 0.139 ms/op
Iteration   1: 3.450 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.289 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.710 ms/op
                 listUser·p0.9999: 13.550 ms/op
                 listUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9269
  mean =      3.450 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 656 
    [ 2.500,  3.750) = 5807 
    [ 3.750,  5.000) = 2413 
    [ 5.000,  6.250) = 258 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     12.710 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     13.550 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.569          ops/ms
ClientSimple.existUser                       thrpt         11.520          ops/ms
ClientSimple.getUser                         thrpt         13.881          ops/ms
ClientSimple.listUser                        thrpt          8.651          ops/ms
ClientSimple.createUser                       avgt          2.115           ms/op
ClientSimple.existUser                        avgt          2.008           ms/op
ClientSimple.getUser                          avgt          2.027           ms/op
ClientSimple.listUser                         avgt          3.622           ms/op
ClientSimple.createUser                     sample  15494   2.127 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.423           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.007           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.785           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.863           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.605           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.556           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.628           ms/op
ClientSimple.existUser                      sample  16756   1.912 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.769           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.796           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.318           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.105           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.980           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.127           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.205           ms/op
ClientSimple.getUser                        sample  16493   1.938 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.451           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.841           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.470           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.730           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.600           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.057           ms/op
ClientSimple.listUser                       sample   9269   3.450 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.200           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.289           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.685           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.710           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.550           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.550           ms/op

Benchmark result is saved to 1713895498730.json
