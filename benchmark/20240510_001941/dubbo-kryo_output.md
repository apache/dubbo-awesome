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
# Warmup Iteration   1: 1.774 ops/ms
Iteration   1: 6.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.823 ops/ms


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
# Warmup Iteration   1: 5.942 ops/ms
Iteration   1: 12.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.233 ops/ms


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
# Warmup Iteration   1: 4.880 ops/ms
Iteration   1: 8.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  8.965 ops/ms


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
# Warmup Iteration   1: 4.293 ops/ms
Iteration   1: 8.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.907 ops/ms


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.071 ms/op
Iteration   1: 2.290 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.290 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.054 ms/op
Iteration   1: 1.927 ±(99.9%) 0.007 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.058 ms/op
Iteration   1: 1.789 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.789 ms/op


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
# Warmup Iteration   1: 4.882 ±(99.9%) 0.092 ms/op
Iteration   1: 3.960 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.960 ms/op


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
# Warmup Iteration   1: 3.499 ±(99.9%) 0.097 ms/op
Iteration   1: 2.087 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   1.843 ms/op
                 createUser·p0.90:   2.810 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   8.179 ms/op
                 createUser·p0.999:  15.548 ms/op
                 createUser·p0.9999: 16.637 ms/op
                 createUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15320
  mean =      2.087 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 386 
    [ 1.250,  2.500) = 12383 
    [ 2.500,  3.750) = 2269 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      8.179 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     16.637 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 3.053 ±(99.9%) 0.081 ms/op
Iteration   1: 2.077 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.023 ms/op
                 existUser·p0.90:   2.482 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   4.127 ms/op
                 existUser·p0.999:  14.830 ms/op
                 existUser·p0.9999: 17.014 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15638
  mean =      2.077 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 283 
    [ 1.250,  2.500) = 13937 
    [ 2.500,  3.750) = 1231 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      4.127 ms/op
     p(99.9000) =     14.830 ms/op
     p(99.9900) =     17.014 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.047 ±(99.9%) 0.070 ms/op
Iteration   1: 2.053 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.525 ms/op
                 getUser·p0.50:   1.956 ms/op
                 getUser·p0.90:   2.490 ms/op
                 getUser·p0.95:   2.650 ms/op
                 getUser·p0.99:   4.302 ms/op
                 getUser·p0.999:  30.455 ms/op
                 getUser·p0.9999: 34.960 ms/op
                 getUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15586
  mean =      2.053 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14106 
    [ 2.500,  5.000) = 1377 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      4.302 ms/op
     p(99.9000) =     30.455 ms/op
     p(99.9900) =     34.960 ms/op
     p(99.9990) =     34.996 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.143 ms/op
Iteration   1: 3.050 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.785 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.783 ms/op
                 listUser·p0.999:  7.315 ms/op
                 listUser·p0.9999: 8.835 ms/op
                 listUser·p1.00:   8.880 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10636
  mean =      3.050 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 17 
    [1.500, 2.000) = 27 
    [2.000, 2.500) = 1797 
    [2.500, 3.000) = 4891 
    [3.000, 3.500) = 1639 
    [3.500, 4.000) = 1282 
    [4.000, 4.500) = 456 
    [4.500, 5.000) = 197 
    [5.000, 5.500) = 150 
    [5.500, 6.000) = 102 
    [6.000, 6.500) = 43 
    [6.500, 7.000) = 18 
    [7.000, 7.500) = 5 
    [7.500, 8.000) = 6 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.783 ms/op
     p(99.9000) =      7.315 ms/op
     p(99.9900) =      8.835 ms/op
     p(99.9990) =      8.880 ms/op
     p(99.9999) =      8.880 ms/op
    p(100.0000) =      8.880 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.823          ops/ms
ClientSimple.existUser                       thrpt         12.233          ops/ms
ClientSimple.getUser                         thrpt          8.965          ops/ms
ClientSimple.listUser                        thrpt          8.907          ops/ms
ClientSimple.createUser                       avgt          2.290           ms/op
ClientSimple.existUser                        avgt          1.927           ms/op
ClientSimple.getUser                          avgt          1.789           ms/op
ClientSimple.listUser                         avgt          3.960           ms/op
ClientSimple.createUser                     sample  15320   2.087 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.752           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.843           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.092           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.179           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.548           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.637           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.646           ms/op
ClientSimple.existUser                      sample  15638   2.077 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.664           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.023           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.127           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.830           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.014           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.236           ms/op
ClientSimple.getUser                        sample  15586   2.053 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.525           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.956           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.302           ms/op
ClientSimple.getUser:getUser·p0.999         sample         30.455           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         34.960           ms/op
ClientSimple.getUser:getUser·p1.00          sample         34.996           ms/op
ClientSimple.listUser                       sample  10636   3.050 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.885           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.785           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.932           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.783           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.315           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.835           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.880           ms/op

Benchmark result is saved to 1715300137437.json
