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
# Warmup Iteration   1: 1.504 ops/ms
Iteration   1: 6.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.139 ops/ms


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
# Warmup Iteration   1: 5.290 ops/ms
Iteration   1: 11.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.451 ops/ms


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
# Warmup Iteration   1: 5.343 ops/ms
Iteration   1: 12.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.920 ops/ms


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
# Warmup Iteration   1: 4.255 ops/ms
Iteration   1: 8.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.134 ops/ms


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.076 ms/op
Iteration   1: 2.075 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.075 ms/op


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
# Warmup Iteration   1: 3.376 ±(99.9%) 0.059 ms/op
Iteration   1: 1.895 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.895 ms/op


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
# Warmup Iteration   1: 3.282 ±(99.9%) 0.063 ms/op
Iteration   1: 1.879 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.879 ms/op


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
# Warmup Iteration   1: 4.572 ±(99.9%) 0.099 ms/op
Iteration   1: 3.717 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.717 ms/op


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.091 ms/op
Iteration   1: 2.049 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.447 ms/op
                 createUser·p0.50:   1.948 ms/op
                 createUser·p0.90:   2.474 ms/op
                 createUser·p0.95:   2.680 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  14.778 ms/op
                 createUser·p0.9999: 15.959 ms/op
                 createUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15593
  mean =      2.049 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 273 
    [ 1.250,  2.500) = 13884 
    [ 2.500,  3.750) = 1245 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.680 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     14.778 ms/op
     p(99.9900) =     15.959 ms/op
     p(99.9990) =     16.105 ms/op
     p(99.9999) =     16.105 ms/op
    p(100.0000) =     16.105 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.075 ms/op
Iteration   1: 1.948 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.474 ms/op
                 existUser·p0.50:   1.815 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   3.278 ms/op
                 existUser·p0.999:  19.838 ms/op
                 existUser·p0.9999: 20.164 ms/op
                 existUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16581
  mean =      1.948 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15534 
    [ 2.500,  5.000) = 981 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      3.278 ms/op
     p(99.9000) =     19.838 ms/op
     p(99.9900) =     20.164 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 3.208 ±(99.9%) 0.073 ms/op
Iteration   1: 1.750 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   1.624 ms/op
                 getUser·p0.90:   2.159 ms/op
                 getUser·p0.95:   2.351 ms/op
                 getUser·p0.99:   3.597 ms/op
                 getUser·p0.999:  13.337 ms/op
                 getUser·p0.9999: 13.587 ms/op
                 getUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18436
  mean =      1.750 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 469 
    [ 1.250,  2.500) = 17322 
    [ 2.500,  3.750) = 472 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      1.624 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      3.597 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     13.587 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


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
# Warmup Iteration   1: 4.752 ±(99.9%) 0.131 ms/op
Iteration   1: 3.192 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   2.931 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  7.741 ms/op
                 listUser·p0.9999: 7.823 ms/op
                 listUser·p1.00:   7.823 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10050
  mean =      3.192 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 4 
    [1.500, 2.000) = 40 
    [2.000, 2.500) = 476 
    [2.500, 3.000) = 5066 
    [3.000, 3.500) = 1734 
    [3.500, 4.000) = 1535 
    [4.000, 4.500) = 757 
    [4.500, 5.000) = 239 
    [5.000, 5.500) = 81 
    [5.500, 6.000) = 39 
    [6.000, 6.500) = 44 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      2.931 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      7.741 ms/op
     p(99.9900) =      7.823 ms/op
     p(99.9990) =      7.823 ms/op
     p(99.9999) =      7.823 ms/op
    p(100.0000) =      7.823 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.139          ops/ms
ClientSimple.existUser                       thrpt         11.451          ops/ms
ClientSimple.getUser                         thrpt         12.920          ops/ms
ClientSimple.listUser                        thrpt          8.134          ops/ms
ClientSimple.createUser                       avgt          2.075           ms/op
ClientSimple.existUser                        avgt          1.895           ms/op
ClientSimple.getUser                          avgt          1.879           ms/op
ClientSimple.listUser                         avgt          3.717           ms/op
ClientSimple.createUser                     sample  15593   2.049 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.447           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.948           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.474           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.680           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.358           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.778           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.959           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.105           ms/op
ClientSimple.existUser                      sample  16581   1.948 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.474           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.815           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.278           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.838           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.164           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.185           ms/op
ClientSimple.getUser                        sample  18436   1.750 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.767           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.624           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.159           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.351           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.597           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.337           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.587           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.615           ms/op
ClientSimple.listUser                       sample  10050   3.192 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.225           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.931           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.652           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.741           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.823           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.823           ms/op

Benchmark result is saved to 1710849995041.json
