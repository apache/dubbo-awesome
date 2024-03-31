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
# Warmup Iteration   1: 1.951 ops/ms
Iteration   1: 6.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.248 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.325 ops/ms
Iteration   1: 11.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.895 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.447 ops/ms
Iteration   1: 12.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.242 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.113 ops/ms
Iteration   1: 8.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.478 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ±(99.9%) 0.070 ms/op
Iteration   1: 2.186 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.186 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.059 ms/op
Iteration   1: 2.139 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.139 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.074 ms/op
Iteration   1: 1.985 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.985 ms/op


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.099 ms/op
Iteration   1: 3.852 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.852 ms/op


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.103 ms/op
Iteration   1: 2.186 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   2.007 ms/op
                 createUser·p0.90:   2.646 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  16.024 ms/op
                 createUser·p0.9999: 17.334 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14701
  mean =      2.186 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 165 
    [ 1.250,  2.500) = 12502 
    [ 2.500,  3.750) = 1716 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.075 ms/op
Iteration   1: 1.909 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   1.755 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  12.456 ms/op
                 existUser·p0.9999: 13.096 ms/op
                 existUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16739
  mean =      1.909 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 287 
    [ 1.250,  2.500) = 15028 
    [ 2.500,  3.750) = 1125 
    [ 3.750,  5.000) = 209 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      1.755 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =     12.456 ms/op
     p(99.9900) =     13.096 ms/op
     p(99.9990) =     13.107 ms/op
     p(99.9999) =     13.107 ms/op
    p(100.0000) =     13.107 ms/op


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
# Warmup Iteration   1: 3.587 ±(99.9%) 0.110 ms/op
Iteration   1: 2.055 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   1.956 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.830 ms/op
                 getUser·p0.99:   4.438 ms/op
                 getUser·p0.999:  16.040 ms/op
                 getUser·p0.9999: 17.588 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15563
  mean =      2.055 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 13707 
    [ 2.500,  3.750) = 1568 
    [ 3.750,  5.000) = 125 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      4.438 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     17.588 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.129 ms/op
Iteration   1: 3.581 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.461 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.554 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8945
  mean =      3.581 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1080 
    [ 2.500,  5.000) = 7363 
    [ 5.000,  7.500) = 410 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      7.554 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.248          ops/ms
ClientSimple.existUser                       thrpt         11.895          ops/ms
ClientSimple.getUser                         thrpt         12.242          ops/ms
ClientSimple.listUser                        thrpt          8.478          ops/ms
ClientSimple.createUser                       avgt          2.186           ms/op
ClientSimple.existUser                        avgt          2.139           ms/op
ClientSimple.getUser                          avgt          1.985           ms/op
ClientSimple.listUser                         avgt          3.852           ms/op
ClientSimple.createUser                     sample  14701   2.186 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.575           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.007           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.520           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.024           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.334           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.334           ms/op
ClientSimple.existUser                      sample  16739   1.909 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.664           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.755           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.350           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.456           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.096           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.107           ms/op
ClientSimple.getUser                        sample  15563   2.055 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.777           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.956           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.438           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.040           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.588           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.153           ms/op
ClientSimple.listUser                       sample   8945   3.581 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.206           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.461           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.071           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.554           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.218           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.677           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.677           ms/op

Benchmark result is saved to 1711886737207.json
