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
# Warmup Iteration   1: 1.626 ops/ms
Iteration   1: 6.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.779 ops/ms


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
# Warmup Iteration   1: 5.372 ops/ms
Iteration   1: 12.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.478 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.603 ops/ms
Iteration   1: 10.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.520 ops/ms


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
# Warmup Iteration   1: 3.992 ops/ms
Iteration   1: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.288 ops/ms


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.088 ms/op
Iteration   1: 2.099 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.099 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.097 ±(99.9%) 0.056 ms/op
Iteration   1: 2.018 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.018 ms/op


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
# Warmup Iteration   1: 3.224 ±(99.9%) 0.054 ms/op
Iteration   1: 2.012 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.012 ms/op


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
# Warmup Iteration   1: 5.088 ±(99.9%) 0.125 ms/op
Iteration   1: 3.294 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.294 ms/op


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
# Warmup Iteration   1: 3.541 ±(99.9%) 0.093 ms/op
Iteration   1: 2.185 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   1.964 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.986 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  18.088 ms/op
                 createUser·p0.9999: 19.687 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14779
  mean =      2.185 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 201 
    [ 1.250,  2.500) = 12734 
    [ 2.500,  3.750) = 1399 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 128 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     19.687 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 3.137 ±(99.9%) 0.093 ms/op
Iteration   1: 1.903 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   1.825 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   3.086 ms/op
                 existUser·p0.999:  11.292 ms/op
                 existUser·p0.9999: 12.915 ms/op
                 existUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16793
  mean =      1.903 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 405 
    [ 1.250,  2.500) = 15376 
    [ 2.500,  3.750) = 887 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.086 ms/op
     p(99.9000) =     11.292 ms/op
     p(99.9900) =     12.915 ms/op
     p(99.9990) =     12.960 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


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
# Warmup Iteration   1: 3.451 ±(99.9%) 0.082 ms/op
Iteration   1: 2.281 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.327 ms/op
                 getUser·p0.50:   2.083 ms/op
                 getUser·p0.90:   2.888 ms/op
                 getUser·p0.95:   3.437 ms/op
                 getUser·p0.99:   5.265 ms/op
                 getUser·p0.999:  18.773 ms/op
                 getUser·p0.9999: 24.981 ms/op
                 getUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14033
  mean =      2.281 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10708 
    [ 2.500,  5.000) = 3158 
    [ 5.000,  7.500) = 91 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.437 ms/op
     p(99.0000) =      5.265 ms/op
     p(99.9000) =     18.773 ms/op
     p(99.9900) =     24.981 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 5.630 ±(99.9%) 0.174 ms/op
Iteration   1: 4.004 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   0.796 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   8.160 ms/op
                 listUser·p0.999:  14.599 ms/op
                 listUser·p0.9999: 14.959 ms/op
                 listUser·p1.00:   14.959 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7987
  mean =      4.004 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 427 
    [ 2.500,  3.750) = 2856 
    [ 3.750,  5.000) = 3743 
    [ 5.000,  6.250) = 712 
    [ 6.250,  7.500) = 106 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      8.160 ms/op
     p(99.9000) =     14.599 ms/op
     p(99.9900) =     14.959 ms/op
     p(99.9990) =     14.959 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.779          ops/ms
ClientSimple.existUser                       thrpt         12.478          ops/ms
ClientSimple.getUser                         thrpt         10.520          ops/ms
ClientSimple.listUser                        thrpt          8.288          ops/ms
ClientSimple.createUser                       avgt          2.099           ms/op
ClientSimple.existUser                        avgt          2.018           ms/op
ClientSimple.getUser                          avgt          2.012           ms/op
ClientSimple.listUser                         avgt          3.294           ms/op
ClientSimple.createUser                     sample  14779   2.185 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.727           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.964           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.986           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.438           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.088           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.687           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.890           ms/op
ClientSimple.existUser                      sample  16793   1.903 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.494           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.825           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.086           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.292           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.915           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.960           ms/op
ClientSimple.getUser                        sample  14033   2.281 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.327           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.083           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.437           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.265           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.773           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.981           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.166           ms/op
ClientSimple.listUser                       sample   7987   4.004 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.796           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.994           ms/op
ClientSimple.listUser:listUser·p0.90        sample          5.095           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.587           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.160           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.599           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.959           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.959           ms/op

Benchmark result is saved to 1714263418392.json
