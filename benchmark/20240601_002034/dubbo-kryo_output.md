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
# Warmup Iteration   1: 1.542 ops/ms
Iteration   1: 6.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.069 ops/ms


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
# Warmup Iteration   1: 6.092 ops/ms
Iteration   1: 12.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.658 ops/ms


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
# Warmup Iteration   1: 5.982 ops/ms
Iteration   1: 12.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.914 ops/ms


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
# Warmup Iteration   1: 4.528 ops/ms
Iteration   1: 8.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.910 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.784 ±(99.9%) 0.078 ms/op
Iteration   1: 2.372 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.372 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.051 ms/op
Iteration   1: 1.869 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.869 ms/op


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
# Warmup Iteration   1: 3.309 ±(99.9%) 0.070 ms/op
Iteration   1: 2.222 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.222 ms/op


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.076 ms/op
Iteration   1: 3.406 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.406 ms/op


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
# Warmup Iteration   1: 3.306 ±(99.9%) 0.084 ms/op
Iteration   1: 2.320 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   9.653 ms/op
                 createUser·p0.999:  30.867 ms/op
                 createUser·p0.9999: 31.361 ms/op
                 createUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13779
  mean =      2.320 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10857 
    [ 2.500,  5.000) = 2739 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      9.653 ms/op
     p(99.9000) =     30.867 ms/op
     p(99.9900) =     31.361 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.077 ms/op
Iteration   1: 2.141 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   2.101 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   2.761 ms/op
                 existUser·p0.99:   3.574 ms/op
                 existUser·p0.999:  15.761 ms/op
                 existUser·p0.9999: 16.171 ms/op
                 existUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14937
  mean =      2.141 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 264 
    [ 1.250,  2.500) = 11916 
    [ 2.500,  3.750) = 2614 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      3.574 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     16.171 ms/op
     p(99.9990) =     16.171 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.083 ms/op
Iteration   1: 2.035 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.372 ms/op
                 getUser·p0.95:   2.609 ms/op
                 getUser·p0.99:   4.414 ms/op
                 getUser·p0.999:  18.022 ms/op
                 getUser·p0.9999: 18.415 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15722
  mean =      2.035 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 14562 
    [ 2.500,  3.750) = 908 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      4.414 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     18.415 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 4.371 ±(99.9%) 0.132 ms/op
Iteration   1: 3.372 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.375 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  20.546 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9485
  mean =      3.372 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1364 
    [ 2.500,  5.000) = 7918 
    [ 5.000,  7.500) = 162 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.069          ops/ms
ClientSimple.existUser                       thrpt         12.658          ops/ms
ClientSimple.getUser                         thrpt         12.914          ops/ms
ClientSimple.listUser                        thrpt          8.910          ops/ms
ClientSimple.createUser                       avgt          2.372           ms/op
ClientSimple.existUser                        avgt          1.869           ms/op
ClientSimple.getUser                          avgt          2.222           ms/op
ClientSimple.listUser                         avgt          3.406           ms/op
ClientSimple.createUser                     sample  13779   2.320 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.678           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.068           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.653           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.867           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.361           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.621           ms/op
ClientSimple.existUser                      sample  14937   2.141 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.622           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.101           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.761           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.574           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.761           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.171           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.171           ms/op
ClientSimple.getUser                        sample  15722   2.035 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.759           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.372           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.414           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.022           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.415           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.547           ms/op
ClientSimple.listUser                       sample   9485   3.372 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.329           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.375           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.611           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.546           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.692           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.692           ms/op

Benchmark result is saved to 1717201001979.json
