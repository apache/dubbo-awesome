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
# Warmup Iteration   1: 2.053 ops/ms
Iteration   1: 6.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.841 ops/ms


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
# Warmup Iteration   1: 4.686 ops/ms
Iteration   1: 11.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.369 ops/ms


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
# Warmup Iteration   1: 5.828 ops/ms
Iteration   1: 14.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.144 ops/ms


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
# Warmup Iteration   1: 5.097 ops/ms
Iteration   1: 8.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.462 ops/ms


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.067 ms/op
Iteration   1: 2.251 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.251 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.053 ms/op
Iteration   1: 1.930 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.930 ms/op


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
# Warmup Iteration   1: 3.171 ±(99.9%) 0.056 ms/op
Iteration   1: 1.993 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.993 ms/op


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
# Warmup Iteration   1: 4.937 ±(99.9%) 0.087 ms/op
Iteration   1: 3.083 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.083 ms/op


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.116 ms/op
Iteration   1: 2.158 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   1.929 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.879 ms/op
                 createUser·p0.99:   5.790 ms/op
                 createUser·p0.999:  31.854 ms/op
                 createUser·p0.9999: 37.953 ms/op
                 createUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14816
  mean =      2.158 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12792 
    [ 2.500,  5.000) = 1846 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      5.790 ms/op
     p(99.9000) =     31.854 ms/op
     p(99.9900) =     37.953 ms/op
     p(99.9990) =     38.142 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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
# Warmup Iteration   1: 3.634 ±(99.9%) 0.220 ms/op
Iteration   1: 1.950 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   1.864 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.765 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  11.216 ms/op
                 existUser·p0.9999: 12.015 ms/op
                 existUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16407
  mean =      1.950 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 840 
    [ 1.250,  2.500) = 14063 
    [ 2.500,  3.750) = 1279 
    [ 3.750,  5.000) = 164 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =     11.216 ms/op
     p(99.9900) =     12.015 ms/op
     p(99.9990) =     12.026 ms/op
     p(99.9999) =     12.026 ms/op
    p(100.0000) =     12.026 ms/op


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
# Warmup Iteration   1: 3.228 ±(99.9%) 0.076 ms/op
Iteration   1: 1.759 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   1.653 ms/op
                 getUser·p0.90:   2.306 ms/op
                 getUser·p0.95:   2.589 ms/op
                 getUser·p0.99:   3.039 ms/op
                 getUser·p0.999:  14.595 ms/op
                 getUser·p0.9999: 14.814 ms/op
                 getUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18167
  mean =      1.759 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 755 
    [ 1.250,  2.500) = 16243 
    [ 2.500,  3.750) = 1054 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      1.653 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.039 ms/op
     p(99.9000) =     14.595 ms/op
     p(99.9900) =     14.814 ms/op
     p(99.9990) =     14.828 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.125 ms/op
Iteration   1: 3.229 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.087 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 15.811 ms/op
                 listUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9985
  mean =      3.229 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1502 
    [ 2.500,  3.750) = 6450 
    [ 3.750,  5.000) = 1765 
    [ 5.000,  6.250) = 119 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      7.087 ms/op
     p(99.9000) =     15.712 ms/op
     p(99.9900) =     15.811 ms/op
     p(99.9990) =     15.811 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.841          ops/ms
ClientSimple.existUser                       thrpt         11.369          ops/ms
ClientSimple.getUser                         thrpt         14.144          ops/ms
ClientSimple.listUser                        thrpt          8.462          ops/ms
ClientSimple.createUser                       avgt          2.251           ms/op
ClientSimple.existUser                        avgt          1.930           ms/op
ClientSimple.getUser                          avgt          1.993           ms/op
ClientSimple.listUser                         avgt          3.083           ms/op
ClientSimple.createUser                     sample  14816   2.158 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.684           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.929           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.790           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.854           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.953           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.142           ms/op
ClientSimple.existUser                      sample  16407   1.950 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.537           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.864           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.765           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.276           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.216           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.015           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.026           ms/op
ClientSimple.getUser                        sample  18167   1.759 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.779           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.653           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.306           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.039           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.595           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.814           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.828           ms/op
ClientSimple.listUser                       sample   9985   3.229 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.530           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.978           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.084           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.087           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.712           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.811           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.811           ms/op

Benchmark result is saved to 1720721115124.json
