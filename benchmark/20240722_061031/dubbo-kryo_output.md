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
# Warmup Iteration   1: 1.176 ops/ms
Iteration   1: 4.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  4.978 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.938 ops/ms
Iteration   1: 11.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.098 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.653 ops/ms
Iteration   1: 11.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.923 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.705 ops/ms
Iteration   1: 8.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.052 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.831 ±(99.9%) 0.113 ms/op
Iteration   1: 2.598 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.598 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.479 ±(99.9%) 0.061 ms/op
Iteration   1: 2.173 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.173 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ±(99.9%) 0.083 ms/op
Iteration   1: 2.075 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.075 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 5.254 ±(99.9%) 0.108 ms/op
Iteration   1: 3.430 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.430 ms/op


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
# Warmup Iteration   1: 3.464 ±(99.9%) 0.093 ms/op
Iteration   1: 2.610 ±(99.9%) 0.120 ms/op
                 createUser·p0.00:   0.379 ms/op
                 createUser·p0.50:   2.107 ms/op
                 createUser·p0.90:   2.814 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   20.513 ms/op
                 createUser·p0.999:  57.999 ms/op
                 createUser·p0.9999: 67.011 ms/op
                 createUser·p1.00:   67.502 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12416
  mean =      2.610 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12068 
    [ 5.000, 10.000) = 209 
    [10.000, 15.000) = 5 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 33 
    [55.000, 60.000) = 23 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      2.107 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =     20.513 ms/op
     p(99.9000) =     57.999 ms/op
     p(99.9900) =     67.011 ms/op
     p(99.9990) =     67.502 ms/op
     p(99.9999) =     67.502 ms/op
    p(100.0000) =     67.502 ms/op


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
# Warmup Iteration   1: 3.118 ±(99.9%) 0.073 ms/op
Iteration   1: 1.978 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.439 ms/op
                 existUser·p0.50:   1.808 ms/op
                 existUser·p0.90:   2.486 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  16.381 ms/op
                 existUser·p0.9999: 17.019 ms/op
                 existUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16180
  mean =      1.978 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 329 
    [ 1.250,  2.500) = 14270 
    [ 2.500,  3.750) = 1274 
    [ 3.750,  5.000) = 230 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =     16.381 ms/op
     p(99.9900) =     17.019 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.474 ±(99.9%) 0.095 ms/op
Iteration   1: 2.143 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.484 ms/op
                 getUser·p0.50:   2.042 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.671 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  22.118 ms/op
                 getUser·p0.9999: 22.873 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14899
  mean =      2.143 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13058 
    [ 2.500,  5.000) = 1721 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =     22.118 ms/op
     p(99.9900) =     22.873 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 5.015 ±(99.9%) 0.172 ms/op
Iteration   1: 3.707 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   6.169 ms/op
                 listUser·p0.999:  7.547 ms/op
                 listUser·p0.9999: 7.643 ms/op
                 listUser·p1.00:   7.643 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8759
  mean =      3.707 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 2 
    [1.500, 2.000) = 70 
    [2.000, 2.500) = 402 
    [2.500, 3.000) = 1069 
    [3.000, 3.500) = 1779 
    [3.500, 4.000) = 2758 
    [4.000, 4.500) = 1540 
    [4.500, 5.000) = 774 
    [5.000, 5.500) = 151 
    [5.500, 6.000) = 97 
    [6.000, 6.500) = 51 
    [6.500, 7.000) = 33 
    [7.000, 7.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =      7.547 ms/op
     p(99.9900) =      7.643 ms/op
     p(99.9990) =      7.643 ms/op
     p(99.9999) =      7.643 ms/op
    p(100.0000) =      7.643 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          4.978          ops/ms
ClientSimple.existUser                       thrpt         11.098          ops/ms
ClientSimple.getUser                         thrpt         11.923          ops/ms
ClientSimple.listUser                        thrpt          8.052          ops/ms
ClientSimple.createUser                       avgt          2.598           ms/op
ClientSimple.existUser                        avgt          2.173           ms/op
ClientSimple.getUser                          avgt          2.075           ms/op
ClientSimple.listUser                         avgt          3.430           ms/op
ClientSimple.createUser                     sample  12416   2.610 ± 0.120   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.379           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.107           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.269           ms/op
ClientSimple.createUser:createUser·p0.99    sample         20.513           ms/op
ClientSimple.createUser:createUser·p0.999   sample         57.999           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         67.011           ms/op
ClientSimple.createUser:createUser·p1.00    sample         67.502           ms/op
ClientSimple.existUser                      sample  16180   1.978 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.439           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.808           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.076           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.309           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.381           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.019           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.039           ms/op
ClientSimple.getUser                        sample  14899   2.143 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.484           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.042           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.998           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.118           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.873           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.905           ms/op
ClientSimple.listUser                       sample   8759   3.707 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.350           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.686           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.596           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.169           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.547           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.643           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.643           ms/op

Benchmark result is saved to 1721628368841.json
