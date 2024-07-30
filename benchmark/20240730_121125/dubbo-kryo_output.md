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
# Warmup Iteration   1: 1.809 ops/ms
Iteration   1: 7.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.681 ops/ms


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
# Warmup Iteration   1: 5.967 ops/ms
Iteration   1: 16.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  16.393 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.118 ops/ms
Iteration   1: 11.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.771 ops/ms


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
# Warmup Iteration   1: 5.002 ops/ms
Iteration   1: 8.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.683 ops/ms


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.077 ms/op
Iteration   1: 2.175 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.175 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.065 ms/op
Iteration   1: 1.913 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.913 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.060 ms/op
Iteration   1: 1.992 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.992 ms/op


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
# Warmup Iteration   1: 4.648 ±(99.9%) 0.102 ms/op
Iteration   1: 3.486 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.486 ms/op


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.115 ms/op
Iteration   1: 2.272 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.679 ms/op
                 createUser·p0.95:   3.043 ms/op
                 createUser·p0.99:   5.802 ms/op
                 createUser·p0.999:  23.197 ms/op
                 createUser·p0.9999: 24.216 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14075
  mean =      2.272 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11167 
    [ 2.500,  5.000) = 2629 
    [ 5.000,  7.500) = 209 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      5.802 ms/op
     p(99.9000) =     23.197 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 2.995 ±(99.9%) 0.068 ms/op
Iteration   1: 1.832 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.138 ms/op
                 existUser·p0.95:   2.286 ms/op
                 existUser·p0.99:   2.869 ms/op
                 existUser·p0.999:  10.642 ms/op
                 existUser·p0.9999: 10.818 ms/op
                 existUser·p1.00:   10.830 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17481
  mean =      1.832 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 6 
    [ 1.000,  2.000) = 14117 
    [ 2.000,  3.000) = 3224 
    [ 3.000,  4.000) = 99 
    [ 4.000,  5.000) = 3 
    [ 5.000,  6.000) = 1 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.286 ms/op
     p(99.0000) =      2.869 ms/op
     p(99.9000) =     10.642 ms/op
     p(99.9900) =     10.818 ms/op
     p(99.9990) =     10.830 ms/op
     p(99.9999) =     10.830 ms/op
    p(100.0000) =     10.830 ms/op


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
# Warmup Iteration   1: 3.550 ±(99.9%) 0.099 ms/op
Iteration   1: 2.191 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   1.980 ms/op
                 getUser·p0.90:   2.843 ms/op
                 getUser·p0.95:   3.275 ms/op
                 getUser·p0.99:   6.787 ms/op
                 getUser·p0.999:  15.375 ms/op
                 getUser·p0.9999: 16.374 ms/op
                 getUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14586
  mean =      2.191 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 180 
    [ 1.250,  2.500) = 11256 
    [ 2.500,  3.750) = 2544 
    [ 3.750,  5.000) = 348 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.843 ms/op
     p(95.0000) =      3.275 ms/op
     p(99.0000) =      6.787 ms/op
     p(99.9000) =     15.375 ms/op
     p(99.9900) =     16.374 ms/op
     p(99.9990) =     16.450 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.133 ms/op
Iteration   1: 3.222 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   3.187 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.915 ms/op
                 listUser·p0.999:  22.843 ms/op
                 listUser·p0.9999: 23.331 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9937
  mean =      3.222 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2596 
    [ 2.500,  5.000) = 7088 
    [ 5.000,  7.500) = 189 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     22.843 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.681          ops/ms
ClientSimple.existUser                       thrpt         16.393          ops/ms
ClientSimple.getUser                         thrpt         11.771          ops/ms
ClientSimple.listUser                        thrpt          8.683          ops/ms
ClientSimple.createUser                       avgt          2.175           ms/op
ClientSimple.existUser                        avgt          1.913           ms/op
ClientSimple.getUser                          avgt          1.992           ms/op
ClientSimple.listUser                         avgt          3.486           ms/op
ClientSimple.createUser                     sample  14075   2.272 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.796           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.043           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.802           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.197           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.216           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.216           ms/op
ClientSimple.existUser                      sample  17481   1.832 ± 0.011   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.942           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.138           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.869           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.642           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.818           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.830           ms/op
ClientSimple.getUser                        sample  14586   2.191 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.761           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.980           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.843           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.275           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.787           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.375           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.374           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.450           ms/op
ClientSimple.listUser                       sample   9937   3.222 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.886           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.187           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.981           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.915           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.843           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.331           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.331           ms/op

Benchmark result is saved to 1722341214679.json
