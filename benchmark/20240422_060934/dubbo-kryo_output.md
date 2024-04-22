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
# Warmup Iteration   1: 1.383 ops/ms
Iteration   1: 5.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.618 ops/ms


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
# Warmup Iteration   1: 5.608 ops/ms
Iteration   1: 10.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.560 ops/ms


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
# Warmup Iteration   1: 4.535 ops/ms
Iteration   1: 10.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.602 ops/ms


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
# Warmup Iteration   1: 4.437 ops/ms
Iteration   1: 8.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.738 ops/ms


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.091 ms/op
Iteration   1: 2.103 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.103 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.058 ms/op
Iteration   1: 2.097 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.097 ms/op


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
# Warmup Iteration   1: 3.410 ±(99.9%) 0.066 ms/op
Iteration   1: 1.950 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.950 ms/op


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
# Warmup Iteration   1: 5.496 ±(99.9%) 0.118 ms/op
Iteration   1: 3.663 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.663 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.115 ms/op
Iteration   1: 2.321 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  14.778 ms/op
                 createUser·p0.9999: 15.188 ms/op
                 createUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13807
  mean =      2.321 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 9887 
    [ 2.500,  3.750) = 3069 
    [ 3.750,  5.000) = 515 
    [ 5.000,  6.250) = 191 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     14.778 ms/op
     p(99.9900) =     15.188 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 3.118 ±(99.9%) 0.072 ms/op
Iteration   1: 2.140 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   1.995 ms/op
                 existUser·p0.90:   2.634 ms/op
                 existUser·p0.95:   2.897 ms/op
                 existUser·p0.99:   5.048 ms/op
                 existUser·p0.999:  18.645 ms/op
                 existUser·p0.9999: 18.743 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15014
  mean =      2.140 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 236 
    [ 1.250,  2.500) = 12689 
    [ 2.500,  3.750) = 1851 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.897 ms/op
     p(99.0000) =      5.048 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.112 ms/op
Iteration   1: 2.482 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   2.384 ms/op
                 getUser·p0.90:   2.912 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   6.946 ms/op
                 getUser·p0.999:  12.321 ms/op
                 getUser·p0.9999: 12.661 ms/op
                 getUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13111
  mean =      2.482 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 8002 
    [ 2.500,  3.750) = 4665 
    [ 3.750,  5.000) = 191 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      2.384 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      6.946 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     12.661 ms/op
     p(99.9990) =     12.681 ms/op
     p(99.9999) =     12.681 ms/op
    p(100.0000) =     12.681 ms/op


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
# Warmup Iteration   1: 6.959 ±(99.9%) 0.191 ms/op
Iteration   1: 3.617 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.531 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   9.432 ms/op
                 listUser·p0.999:  20.709 ms/op
                 listUser·p0.9999: 21.037 ms/op
                 listUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8831
  mean =      3.617 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 691 
    [ 2.500,  5.000) = 7787 
    [ 5.000,  7.500) = 216 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      9.432 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.618          ops/ms
ClientSimple.existUser                       thrpt         10.560          ops/ms
ClientSimple.getUser                         thrpt         10.602          ops/ms
ClientSimple.listUser                        thrpt          8.738          ops/ms
ClientSimple.createUser                       avgt          2.103           ms/op
ClientSimple.existUser                        avgt          2.097           ms/op
ClientSimple.getUser                          avgt          1.950           ms/op
ClientSimple.listUser                         avgt          3.663           ms/op
ClientSimple.createUser                     sample  13807   2.321 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.919           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.113           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.912           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.349           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.778           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.188           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.188           ms/op
ClientSimple.existUser                      sample  15014   2.140 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.636           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.995           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.634           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.897           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.048           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.645           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.743           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.743           ms/op
ClientSimple.getUser                        sample  13111   2.482 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.011           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.384           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.162           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.946           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.321           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.661           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.681           ms/op
ClientSimple.listUser                       sample   8831   3.617 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.325           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.531           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.432           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.709           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.037           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.037           ms/op

Benchmark result is saved to 1713765936265.json
