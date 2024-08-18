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
# Warmup Iteration   1: 1.525 ops/ms
Iteration   1: 6.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.803 ops/ms


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
# Warmup Iteration   1: 5.637 ops/ms
Iteration   1: 13.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.240 ops/ms


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
# Warmup Iteration   1: 5.365 ops/ms
Iteration   1: 11.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.711 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.694 ops/ms
Iteration   1: 8.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.106 ops/ms


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
# Warmup Iteration   1: 4.369 ±(99.9%) 0.093 ms/op
Iteration   1: 1.962 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.962 ms/op


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
# Warmup Iteration   1: 3.346 ±(99.9%) 0.062 ms/op
Iteration   1: 1.895 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.895 ms/op


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
# Warmup Iteration   1: 3.364 ±(99.9%) 0.054 ms/op
Iteration   1: 2.064 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.064 ms/op


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
# Warmup Iteration   1: 5.181 ±(99.9%) 0.073 ms/op
Iteration   1: 3.399 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.399 ms/op


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
# Warmup Iteration   1: 3.678 ±(99.9%) 0.106 ms/op
Iteration   1: 2.229 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   1.993 ms/op
                 createUser·p0.90:   2.616 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  17.782 ms/op
                 createUser·p0.9999: 19.969 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14332
  mean =      2.229 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12534 
    [ 2.500,  5.000) = 1462 
    [ 5.000,  7.500) = 184 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.616 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     17.782 ms/op
     p(99.9900) =     19.969 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 3.095 ±(99.9%) 0.071 ms/op
Iteration   1: 1.979 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   1.853 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.667 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  13.582 ms/op
                 existUser·p0.9999: 13.720 ms/op
                 existUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16158
  mean =      1.979 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 284 
    [ 1.250,  2.500) = 14405 
    [ 2.500,  3.750) = 1327 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.667 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     13.720 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


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
# Warmup Iteration   1: 3.626 ±(99.9%) 0.097 ms/op
Iteration   1: 2.159 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   2.060 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   2.974 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  12.065 ms/op
                 getUser·p0.9999: 14.238 ms/op
                 getUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14804
  mean =      2.159 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 11743 
    [ 2.500,  3.750) = 2689 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      2.974 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     12.065 ms/op
     p(99.9900) =     14.238 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 4.882 ±(99.9%) 0.198 ms/op
Iteration   1: 3.681 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  25.461 ms/op
                 listUser·p0.9999: 25.657 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8716
  mean =      3.681 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 745 
    [ 2.500,  5.000) = 7640 
    [ 5.000,  7.500) = 251 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     25.461 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.803          ops/ms
ClientSimple.existUser                       thrpt         13.240          ops/ms
ClientSimple.getUser                         thrpt         11.711          ops/ms
ClientSimple.listUser                        thrpt          8.106          ops/ms
ClientSimple.createUser                       avgt          1.962           ms/op
ClientSimple.existUser                        avgt          1.895           ms/op
ClientSimple.getUser                          avgt          2.064           ms/op
ClientSimple.listUser                         avgt          3.399           ms/op
ClientSimple.createUser                     sample  14332   2.229 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.790           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.993           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.616           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.256           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.709           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.782           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.969           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.054           ms/op
ClientSimple.existUser                      sample  16158   1.979 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.547           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.853           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.667           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.719           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.582           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.720           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.730           ms/op
ClientSimple.getUser                        sample  14804   2.159 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.671           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.060           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.974           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.497           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.065           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.238           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.238           ms/op
ClientSimple.listUser                       sample   8716   3.681 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.915           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.596           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.422           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.461           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.657           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.657           ms/op

Benchmark result is saved to 1724004316676.json
