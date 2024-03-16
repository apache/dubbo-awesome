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
# Warmup Iteration   1: 1.847 ops/ms
Iteration   1: 6.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.843 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.580 ops/ms
Iteration   1: 12.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.908 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.694 ops/ms
Iteration   1: 13.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.480 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.787 ops/ms
Iteration   1: 8.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.841 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.240 ±(99.9%) 0.064 ms/op
Iteration   1: 2.313 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.313 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.212 ±(99.9%) 0.047 ms/op
Iteration   1: 1.988 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.988 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.223 ±(99.9%) 0.056 ms/op
Iteration   1: 1.994 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.994 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.350 ±(99.9%) 0.095 ms/op
Iteration   1: 3.198 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.198 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.273 ±(99.9%) 0.077 ms/op
Iteration   1: 2.049 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   1.882 ms/op
                 createUser·p0.90:   2.449 ms/op
                 createUser·p0.95:   2.675 ms/op
                 createUser·p0.99:   3.701 ms/op
                 createUser·p0.999:  28.410 ms/op
                 createUser·p0.9999: 29.460 ms/op
                 createUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15635
  mean =      2.049 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14275 
    [ 2.500,  5.000) = 1280 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.701 ms/op
     p(99.9000) =     28.410 ms/op
     p(99.9900) =     29.460 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.009 ±(99.9%) 0.065 ms/op
Iteration   1: 1.804 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   1.622 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.503 ms/op
                 existUser·p0.99:   2.978 ms/op
                 existUser·p0.999:  25.985 ms/op
                 existUser·p0.9999: 26.517 ms/op
                 existUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17726
  mean =      1.804 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16826 
    [ 2.500,  5.000) = 836 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      1.622 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      2.978 ms/op
     p(99.9000) =     25.985 ms/op
     p(99.9900) =     26.517 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.088 ms/op
Iteration   1: 1.995 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   1.737 ms/op
                 getUser·p0.90:   2.732 ms/op
                 getUser·p0.95:   2.904 ms/op
                 getUser·p0.99:   3.490 ms/op
                 getUser·p0.999:  14.171 ms/op
                 getUser·p0.9999: 14.470 ms/op
                 getUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16073
  mean =      1.995 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 12602 
    [ 2.500,  3.750) = 3211 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 5 
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
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      3.490 ms/op
     p(99.9000) =     14.171 ms/op
     p(99.9900) =     14.470 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.113 ms/op
Iteration   1: 3.771 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.446 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.310 ms/op
                 listUser·p0.999:  10.822 ms/op
                 listUser·p0.9999: 15.303 ms/op
                 listUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8480
  mean =      3.771 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 700 
    [ 2.500,  3.750) = 3091 
    [ 3.750,  5.000) = 4313 
    [ 5.000,  6.250) = 220 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.310 ms/op
     p(99.9000) =     10.822 ms/op
     p(99.9900) =     15.303 ms/op
     p(99.9990) =     15.303 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.843          ops/ms
ClientSimple.existUser                       thrpt         12.908          ops/ms
ClientSimple.getUser                         thrpt         13.480          ops/ms
ClientSimple.listUser                        thrpt          8.841          ops/ms
ClientSimple.createUser                       avgt          2.313           ms/op
ClientSimple.existUser                        avgt          1.988           ms/op
ClientSimple.getUser                          avgt          1.994           ms/op
ClientSimple.listUser                         avgt          3.198           ms/op
ClientSimple.createUser                     sample  15635   2.049 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.815           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.882           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.449           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.675           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.701           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.410           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.460           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.590           ms/op
ClientSimple.existUser                      sample  17726   1.804 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.509           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.622           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.978           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.985           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.517           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.542           ms/op
ClientSimple.getUser                        sample  16073   1.995 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.629           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.737           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.904           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.490           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.171           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.470           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.500           ms/op
ClientSimple.listUser                       sample   8480   3.771 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.446           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.838           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.310           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.822           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.303           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.303           ms/op

Benchmark result is saved to 1710612288727.json
