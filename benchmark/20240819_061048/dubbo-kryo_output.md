# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.351 ops/ms
Iteration   1: 7.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.838 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.883 ops/ms
Iteration   1: 12.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.752 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.553 ops/ms
Iteration   1: 14.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.302 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.210 ops/ms
Iteration   1: 8.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.012 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.709 ±(99.9%) 0.081 ms/op
Iteration   1: 2.181 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.181 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.123 ±(99.9%) 0.070 ms/op
Iteration   1: 1.799 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.799 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ±(99.9%) 0.055 ms/op
Iteration   1: 2.021 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.021 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.515 ±(99.9%) 0.110 ms/op
Iteration   1: 3.001 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.001 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.022 ±(99.9%) 0.134 ms/op
Iteration   1: 2.116 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   1.901 ms/op
                 createUser·p0.90:   2.748 ms/op
                 createUser·p0.95:   2.925 ms/op
                 createUser·p0.99:   4.989 ms/op
                 createUser·p0.999:  14.203 ms/op
                 createUser·p0.9999: 14.446 ms/op
                 createUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15096
  mean =      2.116 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 12071 
    [ 2.500,  3.750) = 2672 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      4.989 ms/op
     p(99.9000) =     14.203 ms/op
     p(99.9900) =     14.446 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.937 ±(99.9%) 0.075 ms/op
Iteration   1: 1.704 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   1.632 ms/op
                 existUser·p0.90:   1.948 ms/op
                 existUser·p0.95:   2.122 ms/op
                 existUser·p0.99:   2.671 ms/op
                 existUser·p0.999:  10.486 ms/op
                 existUser·p0.9999: 11.190 ms/op
                 existUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18778
  mean =      1.704 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 18398 
    [ 2.500,  3.750) = 207 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      1.632 ms/op
     p(90.0000) =      1.948 ms/op
     p(95.0000) =      2.122 ms/op
     p(99.0000) =      2.671 ms/op
     p(99.9000) =     10.486 ms/op
     p(99.9900) =     11.190 ms/op
     p(99.9990) =     11.190 ms/op
     p(99.9999) =     11.190 ms/op
    p(100.0000) =     11.190 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.272 ±(99.9%) 0.081 ms/op
Iteration   1: 1.902 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.519 ms/op
                 getUser·p0.50:   1.761 ms/op
                 getUser·p0.90:   2.413 ms/op
                 getUser·p0.95:   2.675 ms/op
                 getUser·p0.99:   3.101 ms/op
                 getUser·p0.999:  31.228 ms/op
                 getUser·p0.9999: 31.347 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16864
  mean =      1.902 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15523 
    [ 2.500,  5.000) = 1239 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.101 ms/op
     p(99.9000) =     31.228 ms/op
     p(99.9900) =     31.347 ms/op
     p(99.9990) =     31.392 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.256 ±(99.9%) 0.111 ms/op
Iteration   1: 3.051 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   2.822 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.145 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  7.811 ms/op
                 listUser·p0.9999: 8.740 ms/op
                 listUser·p1.00:   8.749 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10499
  mean =      3.051 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 18 
    [1.500, 2.000) = 130 
    [2.000, 2.500) = 2341 
    [2.500, 3.000) = 3552 
    [3.000, 3.500) = 1643 
    [3.500, 4.000) = 1972 
    [4.000, 4.500) = 621 
    [4.500, 5.000) = 28 
    [5.000, 5.500) = 56 
    [5.500, 6.000) = 75 
    [6.000, 6.500) = 19 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 37 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      7.811 ms/op
     p(99.9900) =      8.740 ms/op
     p(99.9990) =      8.749 ms/op
     p(99.9999) =      8.749 ms/op
    p(100.0000) =      8.749 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.838          ops/ms
ClientSimple.existUser                       thrpt         12.752          ops/ms
ClientSimple.getUser                         thrpt         14.302          ops/ms
ClientSimple.listUser                        thrpt          8.012          ops/ms
ClientSimple.createUser                       avgt          2.181           ms/op
ClientSimple.existUser                        avgt          1.799           ms/op
ClientSimple.getUser                          avgt          2.021           ms/op
ClientSimple.listUser                         avgt          3.001           ms/op
ClientSimple.createUser                     sample  15096   2.116 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.722           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.901           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.925           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.989           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.203           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.446           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.680           ms/op
ClientSimple.existUser                      sample  18778   1.704 ± 0.011   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.739           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.632           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.948           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.122           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.671           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.486           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.190           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.190           ms/op
ClientSimple.getUser                        sample  16864   1.902 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.519           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.761           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.999         sample         31.228           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         31.347           ms/op
ClientSimple.getUser:getUser·p1.00          sample         31.392           ms/op
ClientSimple.listUser                       sample  10499   3.051 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.038           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.822           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.920           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.145           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.718           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.811           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.740           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.749           ms/op

Benchmark result is saved to 1724047571248.json
