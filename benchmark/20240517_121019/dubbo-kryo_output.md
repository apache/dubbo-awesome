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
# Warmup Iteration   1: 0.706 ops/ms
Iteration   1: 5.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.339 ops/ms


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
# Warmup Iteration   1: 6.536 ops/ms
Iteration   1: 10.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.735 ops/ms


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
# Warmup Iteration   1: 4.804 ops/ms
Iteration   1: 11.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.771 ops/ms


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
# Warmup Iteration   1: 5.462 ops/ms
Iteration   1: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.374 ops/ms


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.066 ms/op
Iteration   1: 2.118 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.118 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.049 ms/op
Iteration   1: 1.914 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.914 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.056 ms/op
Iteration   1: 2.122 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.122 ms/op


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
# Warmup Iteration   1: 4.705 ±(99.9%) 0.091 ms/op
Iteration   1: 3.354 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.354 ms/op


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
# Warmup Iteration   1: 3.431 ±(99.9%) 0.085 ms/op
Iteration   1: 1.968 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   1.944 ms/op
                 createUser·p0.90:   2.433 ms/op
                 createUser·p0.95:   2.601 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  12.788 ms/op
                 createUser·p0.9999: 13.113 ms/op
                 createUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16505
  mean =      1.968 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 640 
    [ 1.250,  2.500) = 14638 
    [ 2.500,  3.750) = 1035 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =     12.788 ms/op
     p(99.9900) =     13.113 ms/op
     p(99.9990) =     13.124 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


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
# Warmup Iteration   1: 3.036 ±(99.9%) 0.073 ms/op
Iteration   1: 2.109 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.312 ms/op
                 existUser·p0.50:   2.056 ms/op
                 existUser·p0.90:   2.540 ms/op
                 existUser·p0.95:   2.712 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  17.433 ms/op
                 existUser·p0.9999: 17.547 ms/op
                 existUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15153
  mean =      2.109 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 775 
    [ 1.250,  2.500) = 12583 
    [ 2.500,  3.750) = 1565 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.312 ms/op
     p(50.0000) =      2.056 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     17.547 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.530 ±(99.9%) 0.092 ms/op
Iteration   1: 2.140 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.379 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.888 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  10.961 ms/op
                 getUser·p0.9999: 11.659 ms/op
                 getUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14935
  mean =      2.140 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 12026 
    [ 2.500,  3.750) = 2464 
    [ 3.750,  5.000) = 190 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =     10.961 ms/op
     p(99.9900) =     11.659 ms/op
     p(99.9990) =     11.796 ms/op
     p(99.9999) =     11.796 ms/op
    p(100.0000) =     11.796 ms/op


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.137 ms/op
Iteration   1: 3.314 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.581 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.374 ms/op
                 listUser·p0.999:  16.111 ms/op
                 listUser·p0.9999: 16.220 ms/op
                 listUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9687
  mean =      3.314 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 442 
    [ 2.500,  3.750) = 7024 
    [ 3.750,  5.000) = 1923 
    [ 5.000,  6.250) = 132 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.374 ms/op
     p(99.9000) =     16.111 ms/op
     p(99.9900) =     16.220 ms/op
     p(99.9990) =     16.220 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.339          ops/ms
ClientSimple.existUser                       thrpt         10.735          ops/ms
ClientSimple.getUser                         thrpt         11.771          ops/ms
ClientSimple.listUser                        thrpt          8.374          ops/ms
ClientSimple.createUser                       avgt          2.118           ms/op
ClientSimple.existUser                        avgt          1.914           ms/op
ClientSimple.getUser                          avgt          2.122           ms/op
ClientSimple.listUser                         avgt          3.354           ms/op
ClientSimple.createUser                     sample  16505   1.968 ± 0.019   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.692           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.944           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.433           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.325           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.788           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.113           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.124           ms/op
ClientSimple.existUser                      sample  15153   2.109 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.312           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.056           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.712           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.136           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.433           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.547           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.564           ms/op
ClientSimple.getUser                        sample  14935   2.140 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.379           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.248           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.637           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.961           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.659           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.796           ms/op
ClientSimple.listUser                       sample   9687   3.314 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.581           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.974           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.374           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.111           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.220           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.220           ms/op

Benchmark result is saved to 1715947577543.json
