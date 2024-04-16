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
# Warmup Iteration   1: 1.816 ops/ms
Iteration   1: 6.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.137 ops/ms


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
# Warmup Iteration   1: 6.798 ops/ms
Iteration   1: 12.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.809 ops/ms


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
# Warmup Iteration   1: 5.915 ops/ms
Iteration   1: 12.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.883 ops/ms


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
# Warmup Iteration   1: 4.593 ops/ms
Iteration   1: 7.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.350 ops/ms


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.061 ms/op
Iteration   1: 2.593 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.593 ms/op


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
# Warmup Iteration   1: 3.448 ±(99.9%) 0.057 ms/op
Iteration   1: 1.942 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.942 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.051 ms/op
Iteration   1: 2.006 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.006 ms/op


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
# Warmup Iteration   1: 5.457 ±(99.9%) 0.116 ms/op
Iteration   1: 3.864 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.864 ms/op


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
# Warmup Iteration   1: 3.443 ±(99.9%) 0.083 ms/op
Iteration   1: 2.320 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   2.019 ms/op
                 createUser·p0.90:   2.904 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   9.067 ms/op
                 createUser·p0.999:  18.765 ms/op
                 createUser·p0.9999: 19.255 ms/op
                 createUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13778
  mean =      2.320 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 9961 
    [ 2.500,  3.750) = 3147 
    [ 3.750,  5.000) = 146 
    [ 5.000,  6.250) = 181 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      9.067 ms/op
     p(99.9000) =     18.765 ms/op
     p(99.9900) =     19.255 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 2.760 ±(99.9%) 0.064 ms/op
Iteration   1: 2.071 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   2.046 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.761 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  12.162 ms/op
                 existUser·p0.9999: 14.382 ms/op
                 existUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15423
  mean =      2.071 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 398 
    [ 1.250,  2.500) = 13414 
    [ 2.500,  3.750) = 1384 
    [ 3.750,  5.000) = 168 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =     12.162 ms/op
     p(99.9900) =     14.382 ms/op
     p(99.9990) =     14.418 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 3.154 ±(99.9%) 0.074 ms/op
Iteration   1: 2.303 ±(99.9%) 0.050 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   2.204 ms/op
                 getUser·p0.90:   2.769 ms/op
                 getUser·p0.95:   2.963 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  36.372 ms/op
                 getUser·p0.9999: 37.932 ms/op
                 getUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13872
  mean =      2.303 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10681 
    [ 2.500,  5.000) = 3119 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      2.963 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =     36.372 ms/op
     p(99.9900) =     37.932 ms/op
     p(99.9990) =     38.339 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 4.234 ±(99.9%) 0.116 ms/op
Iteration   1: 3.303 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.794 ms/op
                 listUser·p0.999:  17.967 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9680
  mean =      3.303 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 955 
    [ 2.500,  3.750) = 6302 
    [ 3.750,  5.000) = 2246 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.794 ms/op
     p(99.9000) =     17.967 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.137          ops/ms
ClientSimple.existUser                       thrpt         12.809          ops/ms
ClientSimple.getUser                         thrpt         12.883          ops/ms
ClientSimple.listUser                        thrpt          7.350          ops/ms
ClientSimple.createUser                       avgt          2.593           ms/op
ClientSimple.existUser                        avgt          1.942           ms/op
ClientSimple.getUser                          avgt          2.006           ms/op
ClientSimple.listUser                         avgt          3.864           ms/op
ClientSimple.createUser                     sample  13778   2.320 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.599           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.019           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.285           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.067           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.765           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.255           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.268           ms/op
ClientSimple.existUser                      sample  15423   2.071 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.518           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.046           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.761           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.293           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.162           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.382           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.418           ms/op
ClientSimple.getUser                        sample  13872   2.303 ± 0.050   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.732           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.204           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.963           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.125           ms/op
ClientSimple.getUser:getUser·p0.999         sample         36.372           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         37.932           ms/op
ClientSimple.getUser:getUser·p1.00          sample         38.339           ms/op
ClientSimple.listUser                       sample   9680   3.303 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.997           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.966           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.794           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.967           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.776           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.776           ms/op

Benchmark result is saved to 1713290705626.json
