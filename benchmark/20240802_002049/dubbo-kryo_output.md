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
# Warmup Iteration   1: 1.638 ops/ms
Iteration   1: 6.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.506 ops/ms


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
# Warmup Iteration   1: 6.685 ops/ms
Iteration   1: 11.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.884 ops/ms


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
# Warmup Iteration   1: 5.151 ops/ms
Iteration   1: 14.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.291 ops/ms


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
# Warmup Iteration   1: 5.770 ops/ms
Iteration   1: 9.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.045 ops/ms


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.076 ms/op
Iteration   1: 2.149 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.149 ms/op


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
# Warmup Iteration   1: 2.995 ±(99.9%) 0.052 ms/op
Iteration   1: 1.993 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.993 ms/op


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
# Warmup Iteration   1: 3.233 ±(99.9%) 0.058 ms/op
Iteration   1: 1.893 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.893 ms/op


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.093 ms/op
Iteration   1: 3.356 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.356 ms/op


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.095 ms/op
Iteration   1: 2.190 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.638 ms/op
                 createUser·p0.95:   2.879 ms/op
                 createUser·p0.99:   5.716 ms/op
                 createUser·p0.999:  14.874 ms/op
                 createUser·p0.9999: 15.819 ms/op
                 createUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14585
  mean =      2.190 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 176 
    [ 1.250,  2.500) = 12093 
    [ 2.500,  3.750) = 2090 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      5.716 ms/op
     p(99.9000) =     14.874 ms/op
     p(99.9900) =     15.819 ms/op
     p(99.9990) =     15.827 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 2.783 ±(99.9%) 0.066 ms/op
Iteration   1: 1.843 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   1.700 ms/op
                 existUser·p0.90:   2.208 ms/op
                 existUser·p0.95:   2.359 ms/op
                 existUser·p0.99:   3.310 ms/op
                 existUser·p0.999:  26.804 ms/op
                 existUser·p0.9999: 26.968 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17341
  mean =      1.843 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16869 
    [ 2.500,  5.000) = 364 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.700 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.359 ms/op
     p(99.0000) =      3.310 ms/op
     p(99.9000) =     26.804 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 3.394 ±(99.9%) 0.104 ms/op
Iteration   1: 2.033 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   1.868 ms/op
                 getUser·p0.90:   2.692 ms/op
                 getUser·p0.95:   2.870 ms/op
                 getUser·p0.99:   3.297 ms/op
                 getUser·p0.999:  12.517 ms/op
                 getUser·p0.9999: 12.616 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15726
  mean =      2.033 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 12922 
    [ 2.500,  3.750) = 2612 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.692 ms/op
     p(95.0000) =      2.870 ms/op
     p(99.0000) =      3.297 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     12.616 ms/op
     p(99.9990) =     12.616 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


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
# Warmup Iteration   1: 4.677 ±(99.9%) 0.136 ms/op
Iteration   1: 3.275 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.158 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.346 ms/op
                 listUser·p0.99:   6.864 ms/op
                 listUser·p0.999:  12.847 ms/op
                 listUser·p0.9999: 13.697 ms/op
                 listUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9908
  mean =      3.275 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1013 
    [ 2.500,  3.750) = 6533 
    [ 3.750,  5.000) = 2083 
    [ 5.000,  6.250) = 173 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.346 ms/op
     p(99.0000) =      6.864 ms/op
     p(99.9000) =     12.847 ms/op
     p(99.9900) =     13.697 ms/op
     p(99.9990) =     13.697 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.506          ops/ms
ClientSimple.existUser                       thrpt         11.884          ops/ms
ClientSimple.getUser                         thrpt         14.291          ops/ms
ClientSimple.listUser                        thrpt          9.045          ops/ms
ClientSimple.createUser                       avgt          2.149           ms/op
ClientSimple.existUser                        avgt          1.993           ms/op
ClientSimple.getUser                          avgt          1.893           ms/op
ClientSimple.listUser                         avgt          3.356           ms/op
ClientSimple.createUser                     sample  14585   2.190 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.995           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.716           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.874           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.819           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.827           ms/op
ClientSimple.existUser                      sample  17341   1.843 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.535           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.700           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.208           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.310           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.804           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.968           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.968           ms/op
ClientSimple.getUser                        sample  15726   2.033 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.768           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.868           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.692           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.870           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.297           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.517           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.616           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.616           ms/op
ClientSimple.listUser                       sample   9908   3.275 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.403           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.158           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.047           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.346           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.864           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.847           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.697           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.697           ms/op

Benchmark result is saved to 1722557792634.json
