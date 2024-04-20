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
# Warmup Iteration   1: 1.760 ops/ms
Iteration   1: 6.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.297 ops/ms


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
# Warmup Iteration   1: 6.333 ops/ms
Iteration   1: 12.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.358 ops/ms


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
# Warmup Iteration   1: 5.107 ops/ms
Iteration   1: 12.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.900 ops/ms


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
# Warmup Iteration   1: 5.255 ops/ms
Iteration   1: 8.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.984 ops/ms


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.070 ms/op
Iteration   1: 2.006 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.206 ±(99.9%) 0.051 ms/op
Iteration   1: 1.781 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.781 ms/op


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
# Warmup Iteration   1: 3.652 ±(99.9%) 0.066 ms/op
Iteration   1: 2.245 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.245 ms/op


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.096 ms/op
Iteration   1: 3.510 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.510 ms/op


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
# Warmup Iteration   1: 3.615 ±(99.9%) 0.097 ms/op
Iteration   1: 2.121 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.651 ms/op
                 createUser·p0.95:   2.916 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  25.625 ms/op
                 createUser·p0.9999: 26.575 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15066
  mean =      2.121 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12962 
    [ 2.500,  5.000) = 1940 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.651 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     25.625 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     26.575 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 3.018 ±(99.9%) 0.073 ms/op
Iteration   1: 1.873 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.425 ms/op
                 existUser·p0.50:   1.724 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  21.987 ms/op
                 existUser·p0.9999: 22.905 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17086
  mean =      1.873 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16421 
    [ 2.500,  5.000) = 568 
    [ 5.000,  7.500) = 48 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      1.724 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.077 ms/op
Iteration   1: 1.910 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   1.735 ms/op
                 getUser·p0.90:   2.376 ms/op
                 getUser·p0.95:   2.568 ms/op
                 getUser·p0.99:   3.105 ms/op
                 getUser·p0.999:  28.015 ms/op
                 getUser·p0.9999: 28.454 ms/op
                 getUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17034
  mean =      1.910 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15956 
    [ 2.500,  5.000) = 1014 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.105 ms/op
     p(99.9000) =     28.015 ms/op
     p(99.9900) =     28.454 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.128 ms/op
Iteration   1: 3.301 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   3.265 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.019 ms/op
                 listUser·p0.999:  8.590 ms/op
                 listUser·p0.9999: 8.733 ms/op
                 listUser·p1.00:   8.733 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9681
  mean =      3.301 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 21 
    [1.500, 2.000) = 134 
    [2.000, 2.500) = 1083 
    [2.500, 3.000) = 2878 
    [3.000, 3.500) = 1489 
    [3.500, 4.000) = 2322 
    [4.000, 4.500) = 1373 
    [4.500, 5.000) = 226 
    [5.000, 5.500) = 41 
    [5.500, 6.000) = 17 
    [6.000, 6.500) = 56 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 19 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.019 ms/op
     p(99.9000) =      8.590 ms/op
     p(99.9900) =      8.733 ms/op
     p(99.9990) =      8.733 ms/op
     p(99.9999) =      8.733 ms/op
    p(100.0000) =      8.733 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.297          ops/ms
ClientSimple.existUser                       thrpt         12.358          ops/ms
ClientSimple.getUser                         thrpt         12.900          ops/ms
ClientSimple.listUser                        thrpt          8.984          ops/ms
ClientSimple.createUser                       avgt          2.006           ms/op
ClientSimple.existUser                        avgt          1.781           ms/op
ClientSimple.getUser                          avgt          2.245           ms/op
ClientSimple.listUser                         avgt          3.510           ms/op
ClientSimple.createUser                     sample  15066   2.121 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.805           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.651           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.251           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.625           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.575           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.575           ms/op
ClientSimple.existUser                      sample  17086   1.873 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.425           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.724           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.871           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.987           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.905           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.905           ms/op
ClientSimple.getUser                        sample  17034   1.910 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.744           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.735           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.105           ms/op
ClientSimple.getUser:getUser·p0.999         sample         28.015           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.454           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.869           ms/op
ClientSimple.listUser                       sample   9681   3.301 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.048           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.265           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.019           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.590           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.733           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.733           ms/op

Benchmark result is saved to 1713593110043.json
