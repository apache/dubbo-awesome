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
# Warmup Iteration   1: 1.817 ops/ms
Iteration   1: 7.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.303 ops/ms


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
# Warmup Iteration   1: 6.079 ops/ms
Iteration   1: 15.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.181 ops/ms


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
# Warmup Iteration   1: 6.082 ops/ms
Iteration   1: 14.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.548 ops/ms


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
# Warmup Iteration   1: 4.212 ops/ms
Iteration   1: 8.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.937 ops/ms


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.076 ms/op
Iteration   1: 2.147 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.147 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.300 ±(99.9%) 0.056 ms/op
Iteration   1: 1.804 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.804 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.536 ±(99.9%) 0.065 ms/op
Iteration   1: 2.153 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.153 ms/op


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.091 ms/op
Iteration   1: 3.597 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.597 ms/op


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
# Warmup Iteration   1: 3.516 ±(99.9%) 0.084 ms/op
Iteration   1: 2.310 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.338 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  15.292 ms/op
                 createUser·p0.9999: 16.019 ms/op
                 createUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13835
  mean =      2.310 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 10337 
    [ 2.500,  3.750) = 3167 
    [ 3.750,  5.000) = 133 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.338 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =     15.292 ms/op
     p(99.9900) =     16.019 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 2.942 ±(99.9%) 0.076 ms/op
Iteration   1: 1.796 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   1.683 ms/op
                 existUser·p0.90:   2.134 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   3.019 ms/op
                 existUser·p0.999:  20.100 ms/op
                 existUser·p0.9999: 20.968 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17803
  mean =      1.796 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17193 
    [ 2.500,  5.000) = 541 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      2.134 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      3.019 ms/op
     p(99.9000) =     20.100 ms/op
     p(99.9900) =     20.968 ms/op
     p(99.9990) =     21.070 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 3.453 ±(99.9%) 0.118 ms/op
Iteration   1: 2.204 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.501 ms/op
                 getUser·p0.50:   2.109 ms/op
                 getUser·p0.90:   2.687 ms/op
                 getUser·p0.95:   2.888 ms/op
                 getUser·p0.99:   3.728 ms/op
                 getUser·p0.999:  16.794 ms/op
                 getUser·p0.9999: 16.941 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14479
  mean =      2.204 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 322 
    [ 1.250,  2.500) = 11608 
    [ 2.500,  3.750) = 2406 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      3.728 ms/op
     p(99.9000) =     16.794 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.126 ms/op
Iteration   1: 3.083 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.839 ms/op
                 listUser·p0.50:   2.847 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.110 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  6.294 ms/op
                 listUser·p0.9999: 7.811 ms/op
                 listUser·p1.00:   7.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10569
  mean =      3.083 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 0 
    [1.500, 2.000) = 16 
    [2.000, 2.500) = 560 
    [2.500, 3.000) = 6149 
    [3.000, 3.500) = 1457 
    [3.500, 4.000) = 1743 
    [4.000, 4.500) = 329 
    [4.500, 5.000) = 133 
    [5.000, 5.500) = 75 
    [5.500, 6.000) = 50 
    [6.000, 6.500) = 52 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.839 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.110 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      6.294 ms/op
     p(99.9900) =      7.811 ms/op
     p(99.9990) =      7.840 ms/op
     p(99.9999) =      7.840 ms/op
    p(100.0000) =      7.840 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.303          ops/ms
ClientSimple.existUser                       thrpt         15.181          ops/ms
ClientSimple.getUser                         thrpt         14.548          ops/ms
ClientSimple.listUser                        thrpt          8.937          ops/ms
ClientSimple.createUser                       avgt          2.147           ms/op
ClientSimple.existUser                        avgt          1.804           ms/op
ClientSimple.getUser                          avgt          2.153           ms/op
ClientSimple.listUser                         avgt          3.597           ms/op
ClientSimple.createUser                     sample  13835   2.310 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.717           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.338           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.145           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.292           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.019           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.056           ms/op
ClientSimple.existUser                      sample  17803   1.796 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.529           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.683           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.134           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.019           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.100           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.968           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.070           ms/op
ClientSimple.getUser                        sample  14479   2.204 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.501           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.109           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.728           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.794           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.941           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.941           ms/op
ClientSimple.listUser                       sample  10569   3.083 ± 0.020   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.839           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.847           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.838           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.110           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.603           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.294           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.811           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.840           ms/op

Benchmark result is saved to 1722060317003.json
