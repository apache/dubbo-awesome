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
# Warmup Iteration   1: 2.211 ops/ms
Iteration   1: 6.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.624 ops/ms


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
# Warmup Iteration   1: 5.767 ops/ms
Iteration   1: 10.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.944 ops/ms


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
# Warmup Iteration   1: 6.655 ops/ms
Iteration   1: 13.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.716 ops/ms


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
# Warmup Iteration   1: 5.863 ops/ms
Iteration   1: 8.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.421 ops/ms


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.077 ms/op
Iteration   1: 2.197 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.197 ms/op


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.077 ms/op
Iteration   1: 2.073 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.073 ms/op


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
# Warmup Iteration   1: 3.321 ±(99.9%) 0.058 ms/op
Iteration   1: 2.078 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.078 ms/op


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
# Warmup Iteration   1: 4.515 ±(99.9%) 0.081 ms/op
Iteration   1: 3.752 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.752 ms/op


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
# Warmup Iteration   1: 3.382 ±(99.9%) 0.076 ms/op
Iteration   1: 2.196 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   2.081 ms/op
                 createUser·p0.90:   2.688 ms/op
                 createUser·p0.95:   3.060 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  16.876 ms/op
                 createUser·p0.9999: 17.564 ms/op
                 createUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14647
  mean =      2.196 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 11924 
    [ 2.500,  3.750) = 2184 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.688 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.361 ±(99.9%) 0.076 ms/op
Iteration   1: 1.985 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   1.819 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.757 ms/op
                 existUser·p0.99:   4.327 ms/op
                 existUser·p0.999:  17.695 ms/op
                 existUser·p0.9999: 18.297 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16095
  mean =      1.985 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 14652 
    [ 2.500,  3.750) = 1121 
    [ 3.750,  5.000) = 157 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      4.327 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     18.297 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.092 ms/op
Iteration   1: 2.172 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   2.068 ms/op
                 getUser·p0.90:   2.761 ms/op
                 getUser·p0.95:   3.019 ms/op
                 getUser·p0.99:   4.156 ms/op
                 getUser·p0.999:  12.583 ms/op
                 getUser·p0.9999: 12.632 ms/op
                 getUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14667
  mean =      2.172 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 200 
    [ 1.250,  2.500) = 11860 
    [ 2.500,  3.750) = 2397 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.068 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      4.156 ms/op
     p(99.9000) =     12.583 ms/op
     p(99.9900) =     12.632 ms/op
     p(99.9990) =     12.632 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


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
# Warmup Iteration   1: 4.276 ±(99.9%) 0.126 ms/op
Iteration   1: 3.496 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.893 ms/op
                 listUser·p0.999:  10.256 ms/op
                 listUser·p0.9999: 12.698 ms/op
                 listUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9158
  mean =      3.496 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1150 
    [ 2.500,  3.750) = 4549 
    [ 3.750,  5.000) = 3181 
    [ 5.000,  6.250) = 157 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.893 ms/op
     p(99.9000) =     10.256 ms/op
     p(99.9900) =     12.698 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.624          ops/ms
ClientSimple.existUser                       thrpt         10.944          ops/ms
ClientSimple.getUser                         thrpt         13.716          ops/ms
ClientSimple.listUser                        thrpt          8.421          ops/ms
ClientSimple.createUser                       avgt          2.197           ms/op
ClientSimple.existUser                        avgt          2.073           ms/op
ClientSimple.getUser                          avgt          2.078           ms/op
ClientSimple.listUser                         avgt          3.752           ms/op
ClientSimple.createUser                     sample  14647   2.196 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.629           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.081           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.688           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.060           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.619           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.876           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.564           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.564           ms/op
ClientSimple.existUser                      sample  16095   1.985 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.835           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.819           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.757           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.327           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.695           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.297           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.317           ms/op
ClientSimple.getUser                        sample  14667   2.172 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.648           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.068           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.019           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.156           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.583           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.632           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.632           ms/op
ClientSimple.listUser                       sample   9158   3.496 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.878           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.527           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.893           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.256           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.698           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.698           ms/op

Benchmark result is saved to 1723032444585.json
