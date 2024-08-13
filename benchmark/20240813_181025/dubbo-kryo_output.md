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
# Warmup Iteration   1: 1.779 ops/ms
Iteration   1: 7.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.751 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.099 ops/ms
Iteration   1: 12.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.237 ops/ms


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
# Warmup Iteration   1: 6.158 ops/ms
Iteration   1: 13.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.206 ops/ms


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
# Warmup Iteration   1: 5.510 ops/ms
Iteration   1: 9.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.115 ops/ms


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.068 ms/op
Iteration   1: 1.976 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.976 ms/op


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
# Warmup Iteration   1: 3.224 ±(99.9%) 0.044 ms/op
Iteration   1: 1.749 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.749 ms/op


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
# Warmup Iteration   1: 3.540 ±(99.9%) 0.057 ms/op
Iteration   1: 1.905 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.905 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.601 ±(99.9%) 0.078 ms/op
Iteration   1: 3.558 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.558 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.461 ±(99.9%) 0.079 ms/op
Iteration   1: 2.334 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   2.183 ms/op
                 createUser·p0.90:   2.802 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   6.848 ms/op
                 createUser·p0.999:  28.140 ms/op
                 createUser·p0.9999: 31.594 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13705
  mean =      2.334 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10693 
    [ 2.500,  5.000) = 2793 
    [ 5.000,  7.500) = 91 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      6.848 ms/op
     p(99.9000) =     28.140 ms/op
     p(99.9900) =     31.594 ms/op
     p(99.9990) =     31.752 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 3.056 ±(99.9%) 0.071 ms/op
Iteration   1: 1.833 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   1.694 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.512 ms/op
                 existUser·p0.99:   3.895 ms/op
                 existUser·p0.999:  11.553 ms/op
                 existUser·p0.9999: 12.493 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17434
  mean =      1.833 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 16350 
    [ 2.500,  3.750) = 715 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      1.694 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.512 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =     11.553 ms/op
     p(99.9900) =     12.493 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.075 ms/op
Iteration   1: 2.007 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   1.909 ms/op
                 getUser·p0.90:   2.380 ms/op
                 getUser·p0.95:   2.568 ms/op
                 getUser·p0.99:   3.641 ms/op
                 getUser·p0.999:  11.403 ms/op
                 getUser·p0.9999: 12.615 ms/op
                 getUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15926
  mean =      2.007 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 14863 
    [ 2.500,  3.750) = 828 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =     11.403 ms/op
     p(99.9900) =     12.615 ms/op
     p(99.9990) =     13.091 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.137 ms/op
Iteration   1: 3.802 ±(99.9%) 0.244 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   3.285 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   8.236 ms/op
                 listUser·p0.999:  113.583 ms/op
                 listUser·p0.9999: 116.130 ms/op
                 listUser·p1.00:   116.130 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8428
  mean =      3.802 ±(99.9%) 0.244 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 8364 
    [ 12.500,  25.000) = 32 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 14 
    [112.500, 125.000) = 18 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      8.236 ms/op
     p(99.9000) =    113.583 ms/op
     p(99.9900) =    116.130 ms/op
     p(99.9990) =    116.130 ms/op
     p(99.9999) =    116.130 ms/op
    p(100.0000) =    116.130 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.751          ops/ms
ClientSimple.existUser                       thrpt          12.237          ops/ms
ClientSimple.getUser                         thrpt          13.206          ops/ms
ClientSimple.listUser                        thrpt           9.115          ops/ms
ClientSimple.createUser                       avgt           1.976           ms/op
ClientSimple.existUser                        avgt           1.749           ms/op
ClientSimple.getUser                          avgt           1.905           ms/op
ClientSimple.listUser                         avgt           3.558           ms/op
ClientSimple.createUser                     sample  13705    2.334 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.604           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.183           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.802           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.154           ms/op
ClientSimple.createUser:createUser·p0.99    sample           6.848           ms/op
ClientSimple.createUser:createUser·p0.999   sample          28.140           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          31.594           ms/op
ClientSimple.createUser:createUser·p1.00    sample          31.752           ms/op
ClientSimple.existUser                      sample  17434    1.833 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.712           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.694           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.290           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.512           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.895           ms/op
ClientSimple.existUser:existUser·p0.999     sample          11.553           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          12.493           ms/op
ClientSimple.existUser:existUser·p1.00      sample          12.567           ms/op
ClientSimple.getUser                        sample  15926    2.007 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.776           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.909           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.380           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.568           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.641           ms/op
ClientSimple.getUser:getUser·p0.999         sample          11.403           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          12.615           ms/op
ClientSimple.getUser:getUser·p1.00          sample          13.091           ms/op
ClientSimple.listUser                       sample   8428    3.802 ± 0.244   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.924           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.285           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample           8.236           ms/op
ClientSimple.listUser:listUser·p0.999       sample         113.583           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         116.130           ms/op
ClientSimple.listUser:listUser·p1.00        sample         116.130           ms/op

Benchmark result is saved to 1723572368054.json
