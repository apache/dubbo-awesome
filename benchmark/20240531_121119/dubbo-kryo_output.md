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
# Warmup Iteration   1: 1.587 ops/ms
Iteration   1: 7.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.684 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.110 ops/ms
Iteration   1: 10.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.796 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.347 ops/ms
Iteration   1: 11.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.936 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.538 ops/ms
Iteration   1: 8.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.190 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.534 ±(99.9%) 0.083 ms/op
Iteration   1: 2.137 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.137 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ±(99.9%) 0.052 ms/op
Iteration   1: 2.107 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.107 ms/op


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.082 ms/op
Iteration   1: 2.072 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.072 ms/op


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
# Warmup Iteration   1: 5.013 ±(99.9%) 0.129 ms/op
Iteration   1: 3.566 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.566 ms/op


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
# Warmup Iteration   1: 3.697 ±(99.9%) 0.104 ms/op
Iteration   1: 2.404 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.510 ms/op
                 createUser·p0.50:   2.150 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   8.282 ms/op
                 createUser·p0.999:  20.366 ms/op
                 createUser·p0.9999: 21.757 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13432
  mean =      2.404 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9926 
    [ 2.500,  5.000) = 3026 
    [ 5.000,  7.500) = 315 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      8.282 ms/op
     p(99.9000) =     20.366 ms/op
     p(99.9900) =     21.757 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 3.038 ±(99.9%) 0.079 ms/op
Iteration   1: 2.099 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   1.933 ms/op
                 existUser·p0.90:   2.691 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  16.922 ms/op
                 existUser·p0.9999: 18.132 ms/op
                 existUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15296
  mean =      2.099 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 12894 
    [ 2.500,  3.750) = 1918 
    [ 3.750,  5.000) = 201 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      5.063 ms/op
     p(99.9000) =     16.922 ms/op
     p(99.9900) =     18.132 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 3.300 ±(99.9%) 0.095 ms/op
Iteration   1: 1.928 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   1.841 ms/op
                 getUser·p0.90:   2.273 ms/op
                 getUser·p0.95:   2.515 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  12.262 ms/op
                 getUser·p0.9999: 12.414 ms/op
                 getUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16579
  mean =      1.928 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 15613 
    [ 2.500,  3.750) = 683 
    [ 3.750,  5.000) = 122 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =     12.262 ms/op
     p(99.9900) =     12.414 ms/op
     p(99.9990) =     12.435 ms/op
     p(99.9999) =     12.435 ms/op
    p(100.0000) =     12.435 ms/op


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
# Warmup Iteration   1: 4.571 ±(99.9%) 0.118 ms/op
Iteration   1: 3.379 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.203 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   5.939 ms/op
                 listUser·p0.999:  18.448 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9462
  mean =      3.379 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 818 
    [ 2.500,  3.750) = 5962 
    [ 3.750,  5.000) = 2325 
    [ 5.000,  6.250) = 282 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.684          ops/ms
ClientSimple.existUser                       thrpt         10.796          ops/ms
ClientSimple.getUser                         thrpt         11.936          ops/ms
ClientSimple.listUser                        thrpt          8.190          ops/ms
ClientSimple.createUser                       avgt          2.137           ms/op
ClientSimple.existUser                        avgt          2.107           ms/op
ClientSimple.getUser                          avgt          2.072           ms/op
ClientSimple.listUser                         avgt          3.566           ms/op
ClientSimple.createUser                     sample  13432   2.404 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.510           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.150           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.974           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.994           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.282           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.366           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.757           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.791           ms/op
ClientSimple.existUser                      sample  15296   2.099 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.841           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.933           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.691           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.994           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.063           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.922           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.132           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.219           ms/op
ClientSimple.getUser                        sample  16579   1.928 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.629           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.841           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.273           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.309           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.262           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.414           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.435           ms/op
ClientSimple.listUser                       sample   9462   3.379 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.307           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.203           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.939           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.448           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.956           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.956           ms/op

Benchmark result is saved to 1717157201795.json
