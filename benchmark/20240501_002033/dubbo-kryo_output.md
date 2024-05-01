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
# Warmup Iteration   1: 0.825 ops/ms
Iteration   1: 5.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.427 ops/ms


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
# Warmup Iteration   1: 5.315 ops/ms
Iteration   1: 11.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.971 ops/ms


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
# Warmup Iteration   1: 5.630 ops/ms
Iteration   1: 12.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.215 ops/ms


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
# Warmup Iteration   1: 4.323 ops/ms
Iteration   1: 8.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.362 ops/ms


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
# Warmup Iteration   1: 5.258 ±(99.9%) 0.093 ms/op
Iteration   1: 2.423 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.423 ms/op


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
# Warmup Iteration   1: 3.218 ±(99.9%) 0.057 ms/op
Iteration   1: 1.946 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.946 ms/op


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
# Warmup Iteration   1: 3.171 ±(99.9%) 0.057 ms/op
Iteration   1: 2.036 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.036 ms/op


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.093 ms/op
Iteration   1: 3.429 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.429 ms/op


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
# Warmup Iteration   1: 3.444 ±(99.9%) 0.099 ms/op
Iteration   1: 2.050 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   1.929 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.843 ms/op
                 createUser·p0.99:   5.342 ms/op
                 createUser·p0.999:  19.170 ms/op
                 createUser·p0.9999: 24.441 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15994
  mean =      2.050 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13986 
    [ 2.500,  5.000) = 1811 
    [ 5.000,  7.500) = 81 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      5.342 ms/op
     p(99.9000) =     19.170 ms/op
     p(99.9900) =     24.441 ms/op
     p(99.9990) =     27.820 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 3.049 ±(99.9%) 0.073 ms/op
Iteration   1: 1.915 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.441 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   4.181 ms/op
                 existUser·p0.999:  25.854 ms/op
                 existUser·p0.9999: 26.072 ms/op
                 existUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16732
  mean =      1.915 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15322 
    [ 2.500,  5.000) = 1337 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      4.181 ms/op
     p(99.9000) =     25.854 ms/op
     p(99.9900) =     26.072 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 3.376 ±(99.9%) 0.081 ms/op
Iteration   1: 2.190 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   2.159 ms/op
                 getUser·p0.90:   2.658 ms/op
                 getUser·p0.95:   2.867 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  11.747 ms/op
                 getUser·p0.9999: 13.234 ms/op
                 getUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14757
  mean =      2.190 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 12107 
    [ 2.500,  3.750) = 2352 
    [ 3.750,  5.000) = 137 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =     11.747 ms/op
     p(99.9900) =     13.234 ms/op
     p(99.9990) =     13.320 ms/op
     p(99.9999) =     13.320 ms/op
    p(100.0000) =     13.320 ms/op


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
# Warmup Iteration   1: 4.729 ±(99.9%) 0.143 ms/op
Iteration   1: 3.119 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   4.885 ms/op
                 listUser·p0.999:  6.082 ms/op
                 listUser·p0.9999: 8.665 ms/op
                 listUser·p1.00:   8.700 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10270
  mean =      3.119 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 37 
    [1.500, 2.000) = 243 
    [2.000, 2.500) = 1110 
    [2.500, 3.000) = 3748 
    [3.000, 3.500) = 2441 
    [3.500, 4.000) = 1691 
    [4.000, 4.500) = 796 
    [4.500, 5.000) = 114 
    [5.000, 5.500) = 52 
    [5.500, 6.000) = 26 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 6 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      4.885 ms/op
     p(99.9000) =      6.082 ms/op
     p(99.9900) =      8.665 ms/op
     p(99.9990) =      8.700 ms/op
     p(99.9999) =      8.700 ms/op
    p(100.0000) =      8.700 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.427          ops/ms
ClientSimple.existUser                       thrpt         11.971          ops/ms
ClientSimple.getUser                         thrpt         12.215          ops/ms
ClientSimple.listUser                        thrpt          8.362          ops/ms
ClientSimple.createUser                       avgt          2.423           ms/op
ClientSimple.existUser                        avgt          1.946           ms/op
ClientSimple.getUser                          avgt          2.036           ms/op
ClientSimple.listUser                         avgt          3.429           ms/op
ClientSimple.createUser                     sample  15994   2.050 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.575           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.929           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.843           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.342           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.170           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.441           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.820           ms/op
ClientSimple.existUser                      sample  16732   1.915 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.582           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.810           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.181           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.854           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.072           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.116           ms/op
ClientSimple.getUser                        sample  14757   2.190 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.816           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.159           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.867           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.912           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.747           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.234           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.320           ms/op
ClientSimple.listUser                       sample  10270   3.119 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.047           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.998           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.990           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.885           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.082           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.665           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.700           ms/op

Benchmark result is saved to 1714522583139.json
