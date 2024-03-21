# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.466 ops/ms
Iteration   1: 6.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.622 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.584 ops/ms
Iteration   1: 12.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.464 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.720 ops/ms
Iteration   1: 12.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.890 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.830 ops/ms
Iteration   1: 7.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.921 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.748 ±(99.9%) 0.070 ms/op
Iteration   1: 2.252 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.252 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.877 ±(99.9%) 0.065 ms/op
Iteration   1: 1.797 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.797 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.155 ±(99.9%) 0.060 ms/op
Iteration   1: 1.921 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.921 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.036 ±(99.9%) 0.105 ms/op
Iteration   1: 3.315 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.315 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.103 ±(99.9%) 0.132 ms/op
Iteration   1: 2.365 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   2.212 ms/op
                 createUser·p0.90:   2.871 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   10.961 ms/op
                 createUser·p0.999:  14.115 ms/op
                 createUser·p0.9999: 14.838 ms/op
                 createUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13503
  mean =      2.365 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 216 
    [ 1.250,  2.500) = 9050 
    [ 2.500,  3.750) = 3922 
    [ 3.750,  5.000) = 107 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.212 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     14.115 ms/op
     p(99.9900) =     14.838 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.733 ±(99.9%) 0.071 ms/op
Iteration   1: 2.135 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.462 ms/op
                 existUser·p0.50:   2.042 ms/op
                 existUser·p0.90:   2.662 ms/op
                 existUser·p0.95:   2.830 ms/op
                 existUser·p0.99:   3.810 ms/op
                 existUser·p0.999:  13.730 ms/op
                 existUser·p0.9999: 18.268 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14998
  mean =      2.135 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 376 
    [ 1.250,  2.500) = 11667 
    [ 2.500,  3.750) = 2798 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      3.810 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     18.268 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.062 ±(99.9%) 0.072 ms/op
Iteration   1: 1.831 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   1.706 ms/op
                 getUser·p0.90:   2.302 ms/op
                 getUser·p0.95:   2.535 ms/op
                 getUser·p0.99:   3.326 ms/op
                 getUser·p0.999:  13.992 ms/op
                 getUser·p0.9999: 14.278 ms/op
                 getUser·p1.00:   14.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17570
  mean =      1.831 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 400 
    [ 1.250,  2.500) = 16161 
    [ 2.500,  3.750) = 930 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      3.326 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     14.278 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.334 ±(99.9%) 0.138 ms/op
Iteration   1: 3.584 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  16.128 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8902
  mean =      3.584 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 963 
    [ 2.500,  3.750) = 3691 
    [ 3.750,  5.000) = 3994 
    [ 5.000,  6.250) = 180 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     16.128 ms/op
     p(99.9900) =     17.662 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.622          ops/ms
ClientSimple.existUser                       thrpt         12.464          ops/ms
ClientSimple.getUser                         thrpt         12.890          ops/ms
ClientSimple.listUser                        thrpt          7.921          ops/ms
ClientSimple.createUser                       avgt          2.252           ms/op
ClientSimple.existUser                        avgt          1.797           ms/op
ClientSimple.getUser                          avgt          1.921           ms/op
ClientSimple.listUser                         avgt          3.315           ms/op
ClientSimple.createUser                     sample  13503   2.365 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.644           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.212           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.076           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.961           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.115           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.838           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.844           ms/op
ClientSimple.existUser                      sample  14998   2.135 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.462           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.042           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.830           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.810           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.730           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.268           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.317           ms/op
ClientSimple.getUser                        sample  17570   1.831 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.656           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.706           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.302           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.326           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.992           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.278           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.303           ms/op
ClientSimple.listUser                       sample   8902   3.584 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.794           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.682           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.784           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.710           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.128           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.662           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.662           ms/op

Benchmark result is saved to 1710980137058.json
