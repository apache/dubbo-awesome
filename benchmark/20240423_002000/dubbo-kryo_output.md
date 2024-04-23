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
# Warmup Iteration   1: 1.777 ops/ms
Iteration   1: 6.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.850 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.169 ops/ms
Iteration   1: 12.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.633 ops/ms


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
# Warmup Iteration   1: 5.458 ops/ms
Iteration   1: 13.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.747 ops/ms


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
# Warmup Iteration   1: 5.309 ops/ms
Iteration   1: 8.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.694 ops/ms


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
# Warmup Iteration   1: 3.813 ±(99.9%) 0.067 ms/op
Iteration   1: 2.121 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.121 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.061 ms/op
Iteration   1: 1.784 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.784 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.054 ms/op
Iteration   1: 2.108 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.108 ms/op


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.098 ms/op
Iteration   1: 3.090 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.090 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.079 ms/op
Iteration   1: 2.002 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.384 ms/op
                 createUser·p0.50:   1.860 ms/op
                 createUser·p0.90:   2.171 ms/op
                 createUser·p0.95:   2.503 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  34.734 ms/op
                 createUser·p0.9999: 34.996 ms/op
                 createUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16032
  mean =      2.002 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15230 
    [ 2.500,  5.000) = 599 
    [ 5.000,  7.500) = 110 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.384 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.171 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     34.734 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     34.996 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 2.717 ±(99.9%) 0.076 ms/op
Iteration   1: 1.837 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.204 ms/op
                 existUser·p0.95:   2.445 ms/op
                 existUser·p0.99:   3.334 ms/op
                 existUser·p0.999:  14.831 ms/op
                 existUser·p0.9999: 15.595 ms/op
                 existUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17395
  mean =      1.837 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 288 
    [ 1.250,  2.500) = 16323 
    [ 2.500,  3.750) = 669 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.445 ms/op
     p(99.0000) =      3.334 ms/op
     p(99.9000) =     14.831 ms/op
     p(99.9900) =     15.595 ms/op
     p(99.9990) =     16.007 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 3.210 ±(99.9%) 0.072 ms/op
Iteration   1: 2.014 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.502 ms/op
                 getUser·p0.50:   1.833 ms/op
                 getUser·p0.90:   2.666 ms/op
                 getUser·p0.95:   2.896 ms/op
                 getUser·p0.99:   4.159 ms/op
                 getUser·p0.999:  31.789 ms/op
                 getUser·p0.9999: 32.907 ms/op
                 getUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15871
  mean =      2.014 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13156 
    [ 2.500,  5.000) = 2599 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      4.159 ms/op
     p(99.9000) =     31.789 ms/op
     p(99.9900) =     32.907 ms/op
     p(99.9990) =     32.965 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 4.430 ±(99.9%) 0.116 ms/op
Iteration   1: 3.616 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   6.150 ms/op
                 listUser·p0.999:  9.294 ms/op
                 listUser·p0.9999: 9.470 ms/op
                 listUser·p1.00:   9.470 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8864
  mean =      3.616 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 76 
    [ 2.000,  3.000) = 2152 
    [ 3.000,  4.000) = 4048 
    [ 4.000,  5.000) = 2216 
    [ 5.000,  6.000) = 269 
    [ 6.000,  7.000) = 56 
    [ 7.000,  8.000) = 32 
    [ 8.000,  9.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.150 ms/op
     p(99.9000) =      9.294 ms/op
     p(99.9900) =      9.470 ms/op
     p(99.9990) =      9.470 ms/op
     p(99.9999) =      9.470 ms/op
    p(100.0000) =      9.470 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.850          ops/ms
ClientSimple.existUser                       thrpt         12.633          ops/ms
ClientSimple.getUser                         thrpt         13.747          ops/ms
ClientSimple.listUser                        thrpt          8.694          ops/ms
ClientSimple.createUser                       avgt          2.121           ms/op
ClientSimple.existUser                        avgt          1.784           ms/op
ClientSimple.getUser                          avgt          2.108           ms/op
ClientSimple.listUser                         avgt          3.090           ms/op
ClientSimple.createUser                     sample  16032   2.002 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.384           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.860           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.171           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.503           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.341           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.734           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.996           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.996           ms/op
ClientSimple.existUser                      sample  17395   1.837 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.482           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.735           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.204           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.334           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.831           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.595           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.007           ms/op
ClientSimple.getUser                        sample  15871   2.014 ± 0.039   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.502           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.833           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.896           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.159           ms/op
ClientSimple.getUser:getUser·p0.999         sample         31.789           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         32.907           ms/op
ClientSimple.getUser:getUser·p1.00          sample         32.965           ms/op
ClientSimple.listUser                       sample   8864   3.616 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.843           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.613           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.841           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.150           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.294           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.470           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.470           ms/op

Benchmark result is saved to 1713831334972.json
