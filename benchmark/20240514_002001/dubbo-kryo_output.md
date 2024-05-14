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
# Warmup Iteration   1: 1.875 ops/ms
Iteration   1: 7.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.549 ops/ms


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
# Warmup Iteration   1: 7.168 ops/ms
Iteration   1: 14.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.232 ops/ms


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
# Warmup Iteration   1: 7.008 ops/ms
Iteration   1: 14.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.516 ops/ms


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
# Warmup Iteration   1: 5.174 ops/ms
Iteration   1: 9.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.583 ops/ms


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.073 ms/op
Iteration   1: 2.242 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.242 ms/op


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
# Warmup Iteration   1: 2.980 ±(99.9%) 0.054 ms/op
Iteration   1: 1.913 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.913 ms/op


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
# Warmup Iteration   1: 3.121 ±(99.9%) 0.060 ms/op
Iteration   1: 2.034 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.034 ms/op


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.083 ms/op
Iteration   1: 3.247 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.247 ms/op


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
# Warmup Iteration   1: 3.116 ±(99.9%) 0.073 ms/op
Iteration   1: 1.920 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.440 ms/op
                 createUser·p0.50:   1.731 ms/op
                 createUser·p0.90:   2.351 ms/op
                 createUser·p0.95:   2.585 ms/op
                 createUser·p0.99:   6.168 ms/op
                 createUser·p0.999:  28.246 ms/op
                 createUser·p0.9999: 32.834 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16654
  mean =      1.920 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15599 
    [ 2.500,  5.000) = 855 
    [ 5.000,  7.500) = 88 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      6.168 ms/op
     p(99.9000) =     28.246 ms/op
     p(99.9900) =     32.834 ms/op
     p(99.9990) =     32.834 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.865 ±(99.9%) 0.062 ms/op
Iteration   1: 1.912 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.236 ms/op
                 existUser·p0.95:   2.359 ms/op
                 existUser·p0.99:   3.843 ms/op
                 existUser·p0.999:  13.746 ms/op
                 existUser·p0.9999: 14.444 ms/op
                 existUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16743
  mean =      1.912 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 16091 
    [ 2.500,  3.750) = 328 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.359 ms/op
     p(99.0000) =      3.843 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     14.444 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.067 ms/op
Iteration   1: 1.906 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.613 ms/op
                 getUser·p0.99:   3.494 ms/op
                 getUser·p0.999:  10.142 ms/op
                 getUser·p0.9999: 10.245 ms/op
                 getUser·p1.00:   10.289 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16800
  mean =      1.906 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 54 
    [ 1.000,  2.000) = 10826 
    [ 2.000,  3.000) = 5582 
    [ 3.000,  4.000) = 205 
    [ 4.000,  5.000) = 87 
    [ 5.000,  6.000) = 0 
    [ 6.000,  7.000) = 5 
    [ 7.000,  8.000) = 7 
    [ 8.000,  9.000) = 2 
    [ 9.000, 10.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      3.494 ms/op
     p(99.9000) =     10.142 ms/op
     p(99.9900) =     10.245 ms/op
     p(99.9990) =     10.289 ms/op
     p(99.9999) =     10.289 ms/op
    p(100.0000) =     10.289 ms/op


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
# Warmup Iteration   1: 6.090 ±(99.9%) 0.187 ms/op
Iteration   1: 3.733 ±(99.9%) 0.078 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   11.972 ms/op
                 listUser·p0.999:  37.249 ms/op
                 listUser·p0.9999: 41.812 ms/op
                 listUser·p1.00:   41.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8628
  mean =      3.733 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8252 
    [ 5.000, 10.000) = 272 
    [10.000, 15.000) = 65 
    [15.000, 20.000) = 6 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 6 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =     11.972 ms/op
     p(99.9000) =     37.249 ms/op
     p(99.9900) =     41.812 ms/op
     p(99.9990) =     41.812 ms/op
     p(99.9999) =     41.812 ms/op
    p(100.0000) =     41.812 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.549          ops/ms
ClientSimple.existUser                       thrpt         14.232          ops/ms
ClientSimple.getUser                         thrpt         14.516          ops/ms
ClientSimple.listUser                        thrpt          9.583          ops/ms
ClientSimple.createUser                       avgt          2.242           ms/op
ClientSimple.existUser                        avgt          1.913           ms/op
ClientSimple.getUser                          avgt          2.034           ms/op
ClientSimple.listUser                         avgt          3.247           ms/op
ClientSimple.createUser                     sample  16654   1.920 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.440           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.731           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.351           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.168           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.246           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.834           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.834           ms/op
ClientSimple.existUser                      sample  16743   1.912 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.819           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.800           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.843           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.746           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.444           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.533           ms/op
ClientSimple.getUser                        sample  16800   1.906 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.782           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.494           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.142           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.245           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.289           ms/op
ClientSimple.listUser                       sample   8628   3.733 ± 0.078   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.883           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample         11.972           ms/op
ClientSimple.listUser:listUser·p0.999       sample         37.249           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         41.812           ms/op
ClientSimple.listUser:listUser·p1.00        sample         41.812           ms/op

Benchmark result is saved to 1715645728925.json
