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
# Warmup Iteration   1: 1.711 ops/ms
Iteration   1: 7.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.093 ops/ms


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
# Warmup Iteration   1: 6.447 ops/ms
Iteration   1: 12.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.286 ops/ms


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
# Warmup Iteration   1: 5.923 ops/ms
Iteration   1: 11.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.765 ops/ms


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
# Warmup Iteration   1: 5.506 ops/ms
Iteration   1: 8.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.698 ops/ms


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
# Warmup Iteration   1: 3.697 ±(99.9%) 0.067 ms/op
Iteration   1: 1.986 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.986 ms/op


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
# Warmup Iteration   1: 3.501 ±(99.9%) 0.061 ms/op
Iteration   1: 2.012 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.012 ms/op


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
# Warmup Iteration   1: 3.243 ±(99.9%) 0.063 ms/op
Iteration   1: 1.964 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.964 ms/op


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.096 ms/op
Iteration   1: 3.186 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.186 ms/op


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
# Warmup Iteration   1: 3.513 ±(99.9%) 0.079 ms/op
Iteration   1: 2.078 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.554 ms/op
                 createUser·p0.50:   1.810 ms/op
                 createUser·p0.90:   2.544 ms/op
                 createUser·p0.95:   2.769 ms/op
                 createUser·p0.99:   10.033 ms/op
                 createUser·p0.999:  14.909 ms/op
                 createUser·p0.9999: 18.285 ms/op
                 createUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15376
  mean =      2.078 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 217 
    [ 1.250,  2.500) = 13404 
    [ 2.500,  3.750) = 1446 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =     10.033 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 2.785 ±(99.9%) 0.060 ms/op
Iteration   1: 2.042 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   1.968 ms/op
                 existUser·p0.90:   2.577 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  21.234 ms/op
                 existUser·p0.9999: 21.341 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15697
  mean =      2.042 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13821 
    [ 2.500,  5.000) = 1768 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.577 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =     21.234 ms/op
     p(99.9900) =     21.341 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 3.592 ±(99.9%) 0.113 ms/op
Iteration   1: 2.261 ±(99.9%) 0.071 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   2.025 ms/op
                 getUser·p0.90:   2.585 ms/op
                 getUser·p0.95:   2.855 ms/op
                 getUser·p0.99:   5.706 ms/op
                 getUser·p0.999:  51.257 ms/op
                 getUser·p0.9999: 54.729 ms/op
                 getUser·p1.00:   54.919 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14146
  mean =      2.261 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13928 
    [ 5.000, 10.000) = 117 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      5.706 ms/op
     p(99.9000) =     51.257 ms/op
     p(99.9900) =     54.729 ms/op
     p(99.9990) =     54.919 ms/op
     p(99.9999) =     54.919 ms/op
    p(100.0000) =     54.919 ms/op


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.126 ms/op
Iteration   1: 3.173 ±(99.9%) 0.059 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   2.855 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  31.240 ms/op
                 listUser·p0.9999: 32.176 ms/op
                 listUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10078
  mean =      3.173 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2228 
    [ 2.500,  5.000) = 7602 
    [ 5.000,  7.500) = 176 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 15 
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
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     31.240 ms/op
     p(99.9900) =     32.176 ms/op
     p(99.9990) =     32.178 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.093          ops/ms
ClientSimple.existUser                       thrpt         12.286          ops/ms
ClientSimple.getUser                         thrpt         11.765          ops/ms
ClientSimple.listUser                        thrpt          8.698          ops/ms
ClientSimple.createUser                       avgt          1.986           ms/op
ClientSimple.existUser                        avgt          2.012           ms/op
ClientSimple.getUser                          avgt          1.964           ms/op
ClientSimple.listUser                         avgt          3.186           ms/op
ClientSimple.createUser                     sample  15376   2.078 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.554           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.810           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.033           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.909           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.285           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.285           ms/op
ClientSimple.existUser                      sample  15697   2.042 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.532           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.968           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.577           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.006           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.580           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.234           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.341           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.398           ms/op
ClientSimple.getUser                        sample  14146   2.261 ± 0.071   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.506           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.025           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.706           ms/op
ClientSimple.getUser:getUser·p0.999         sample         51.257           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         54.729           ms/op
ClientSimple.getUser:getUser·p1.00          sample         54.919           ms/op
ClientSimple.listUser                       sample  10078   3.173 ± 0.059   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.820           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.855           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.949           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.734           ms/op
ClientSimple.listUser:listUser·p0.999       sample         31.240           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.176           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.178           ms/op

Benchmark result is saved to 1722103544863.json
