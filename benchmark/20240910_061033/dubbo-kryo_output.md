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
# Warmup Iteration   1: 0.906 ops/ms
Iteration   1: 5.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.629 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.063 ops/ms
Iteration   1: 12.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.043 ops/ms


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
# Warmup Iteration   1: 6.171 ops/ms
Iteration   1: 11.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.619 ops/ms


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
# Warmup Iteration   1: 3.428 ops/ms
Iteration   1: 7.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.799 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.017 ±(99.9%) 0.076 ms/op
Iteration   1: 2.243 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.243 ms/op


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
# Warmup Iteration   1: 3.314 ±(99.9%) 0.065 ms/op
Iteration   1: 1.938 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.938 ms/op


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
# Warmup Iteration   1: 3.654 ±(99.9%) 0.080 ms/op
Iteration   1: 2.496 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.496 ms/op


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
# Warmup Iteration   1: 4.729 ±(99.9%) 0.107 ms/op
Iteration   1: 3.240 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.240 ms/op


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.116 ms/op
Iteration   1: 2.569 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.327 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.656 ms/op
                 createUser·p0.99:   11.469 ms/op
                 createUser·p0.999:  19.262 ms/op
                 createUser·p0.9999: 19.587 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12429
  mean =      2.569 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 7846 
    [ 2.500,  3.750) = 3951 
    [ 3.750,  5.000) = 269 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      2.327 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.656 ms/op
     p(99.0000) =     11.469 ms/op
     p(99.9000) =     19.262 ms/op
     p(99.9900) =     19.587 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 3.005 ±(99.9%) 0.071 ms/op
Iteration   1: 2.107 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.034 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.826 ms/op
                 existUser·p0.99:   5.097 ms/op
                 existUser·p0.999:  10.748 ms/op
                 existUser·p0.9999: 11.075 ms/op
                 existUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15184
  mean =      2.107 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 13168 
    [ 2.500,  3.750) = 1652 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      5.097 ms/op
     p(99.9000) =     10.748 ms/op
     p(99.9900) =     11.075 ms/op
     p(99.9990) =     11.092 ms/op
     p(99.9999) =     11.092 ms/op
    p(100.0000) =     11.092 ms/op


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.085 ms/op
Iteration   1: 1.982 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.523 ms/op
                 getUser·p0.50:   1.855 ms/op
                 getUser·p0.90:   2.331 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  12.960 ms/op
                 getUser·p0.9999: 13.162 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16377
  mean =      1.982 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 15112 
    [ 2.500,  3.750) = 976 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     13.162 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.129 ms/op
Iteration   1: 3.187 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  7.491 ms/op
                 listUser·p0.9999: 8.978 ms/op
                 listUser·p1.00:   8.978 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10033
  mean =      3.187 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 26 
    [1.500, 2.000) = 40 
    [2.000, 2.500) = 210 
    [2.500, 3.000) = 4796 
    [3.000, 3.500) = 2781 
    [3.500, 4.000) = 1175 
    [4.000, 4.500) = 688 
    [4.500, 5.000) = 163 
    [5.000, 5.500) = 45 
    [5.500, 6.000) = 20 
    [6.000, 6.500) = 49 
    [6.500, 7.000) = 15 
    [7.000, 7.500) = 15 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =      7.491 ms/op
     p(99.9900) =      8.978 ms/op
     p(99.9990) =      8.978 ms/op
     p(99.9999) =      8.978 ms/op
    p(100.0000) =      8.978 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.629          ops/ms
ClientSimple.existUser                       thrpt         12.043          ops/ms
ClientSimple.getUser                         thrpt         11.619          ops/ms
ClientSimple.listUser                        thrpt          7.799          ops/ms
ClientSimple.createUser                       avgt          2.243           ms/op
ClientSimple.existUser                        avgt          1.938           ms/op
ClientSimple.getUser                          avgt          2.496           ms/op
ClientSimple.listUser                         avgt          3.240           ms/op
ClientSimple.createUser                     sample  12429   2.569 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.920           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.327           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.113           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.656           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.469           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.262           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.587           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.595           ms/op
ClientSimple.existUser                      sample  15184   2.107 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.665           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.034           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.826           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.097           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.748           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.075           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.092           ms/op
ClientSimple.getUser                        sample  16377   1.982 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.523           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.855           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.331           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.998           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.960           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.162           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.173           ms/op
ClientSimple.listUser                       sample  10033   3.187 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.805           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.994           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.002           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.833           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.491           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.978           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.978           ms/op

Benchmark result is saved to 1725948379152.json
