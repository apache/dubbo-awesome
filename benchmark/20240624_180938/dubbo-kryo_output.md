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
# Warmup Iteration   1: 1.351 ops/ms
Iteration   1: 5.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.424 ops/ms


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
# Warmup Iteration   1: 6.637 ops/ms
Iteration   1: 14.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.243 ops/ms


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
# Warmup Iteration   1: 5.357 ops/ms
Iteration   1: 11.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.261 ops/ms


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
# Warmup Iteration   1: 3.902 ops/ms
Iteration   1: 8.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.753 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.731 ±(99.9%) 0.091 ms/op
Iteration   1: 2.294 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.294 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.059 ms/op
Iteration   1: 2.172 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.172 ms/op


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
# Warmup Iteration   1: 3.115 ±(99.9%) 0.058 ms/op
Iteration   1: 2.276 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.276 ms/op


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
# Warmup Iteration   1: 4.699 ±(99.9%) 0.106 ms/op
Iteration   1: 3.442 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.442 ms/op


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.099 ms/op
Iteration   1: 2.320 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.032 ms/op
                 createUser·p0.90:   2.925 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  25.461 ms/op
                 createUser·p0.9999: 26.021 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13783
  mean =      2.320 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10721 
    [ 2.500,  5.000) = 2790 
    [ 5.000,  7.500) = 110 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     25.461 ms/op
     p(99.9900) =     26.021 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 3.302 ±(99.9%) 0.091 ms/op
Iteration   1: 2.032 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.257 ms/op
                 existUser·p0.50:   1.874 ms/op
                 existUser·p0.90:   2.556 ms/op
                 existUser·p0.95:   2.732 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  12.931 ms/op
                 existUser·p0.9999: 16.204 ms/op
                 existUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15769
  mean =      2.032 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 218 
    [ 1.250,  2.500) = 13562 
    [ 2.500,  3.750) = 1706 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 145 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.257 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     12.931 ms/op
     p(99.9900) =     16.204 ms/op
     p(99.9990) =     16.204 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.113 ms/op
Iteration   1: 2.430 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   2.269 ms/op
                 getUser·p0.90:   2.830 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  20.972 ms/op
                 getUser·p0.9999: 21.334 ms/op
                 getUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13146
  mean =      2.430 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9646 
    [ 2.500,  5.000) = 3333 
    [ 5.000,  7.500) = 71 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     21.334 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 5.016 ±(99.9%) 0.172 ms/op
Iteration   1: 3.495 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.428 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   8.025 ms/op
                 listUser·p0.999:  19.914 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9141
  mean =      3.495 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 943 
    [ 2.500,  5.000) = 7830 
    [ 5.000,  7.500) = 269 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      8.025 ms/op
     p(99.9000) =     19.914 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.424          ops/ms
ClientSimple.existUser                       thrpt         14.243          ops/ms
ClientSimple.getUser                         thrpt         11.261          ops/ms
ClientSimple.listUser                        thrpt          8.753          ops/ms
ClientSimple.createUser                       avgt          2.294           ms/op
ClientSimple.existUser                        avgt          2.172           ms/op
ClientSimple.getUser                          avgt          2.276           ms/op
ClientSimple.listUser                         avgt          3.442           ms/op
ClientSimple.createUser                     sample  13783   2.320 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.962           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.032           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.925           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.195           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.159           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.461           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.021           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.083           ms/op
ClientSimple.existUser                      sample  15769   2.032 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.257           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.874           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.732           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.325           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.931           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.204           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.204           ms/op
ClientSimple.getUser                        sample  13146   2.430 ± 0.042   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.816           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.269           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.097           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.194           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.972           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.334           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.365           ms/op
ClientSimple.listUser                       sample   9141   3.495 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.992           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.428           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.025           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.914           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.840           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.840           ms/op

Benchmark result is saved to 1719252332032.json
