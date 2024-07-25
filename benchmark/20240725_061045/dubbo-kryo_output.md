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
# Warmup Iteration   1: 1.562 ops/ms
Iteration   1: 7.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.018 ops/ms


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
# Warmup Iteration   1: 5.963 ops/ms
Iteration   1: 11.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.354 ops/ms


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
# Warmup Iteration   1: 5.245 ops/ms
Iteration   1: 11.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.797 ops/ms


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
# Warmup Iteration   1: 4.523 ops/ms
Iteration   1: 8.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.303 ops/ms


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.061 ms/op
Iteration   1: 2.261 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.261 ms/op


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
# Warmup Iteration   1: 3.364 ±(99.9%) 0.059 ms/op
Iteration   1: 2.155 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.155 ms/op


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.064 ms/op
Iteration   1: 2.046 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.046 ms/op


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
# Warmup Iteration   1: 5.078 ±(99.9%) 0.097 ms/op
Iteration   1: 3.480 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.480 ms/op


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.104 ms/op
Iteration   1: 2.421 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.517 ms/op
                 createUser·p0.50:   2.228 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   9.093 ms/op
                 createUser·p0.999:  20.939 ms/op
                 createUser·p0.9999: 21.474 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13314
  mean =      2.421 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9623 
    [ 2.500,  5.000) = 3484 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.228 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.330 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     20.939 ms/op
     p(99.9900) =     21.474 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.093 ms/op
Iteration   1: 2.002 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.527 ms/op
                 existUser·p0.50:   1.976 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  12.780 ms/op
                 existUser·p0.9999: 13.635 ms/op
                 existUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15967
  mean =      2.002 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 701 
    [ 1.250,  2.500) = 13936 
    [ 2.500,  3.750) = 1127 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      1.976 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     13.635 ms/op
     p(99.9990) =     13.763 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 3.238 ±(99.9%) 0.078 ms/op
Iteration   1: 2.202 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.668 ms/op
                 getUser·p0.50:   2.089 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.875 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  29.011 ms/op
                 getUser·p0.9999: 29.509 ms/op
                 getUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14657
  mean =      2.202 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12407 
    [ 2.500,  5.000) = 2144 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =     29.011 ms/op
     p(99.9900) =     29.509 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.123 ms/op
Iteration   1: 3.696 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   5.514 ms/op
                 listUser·p0.999:  8.574 ms/op
                 listUser·p0.9999: 8.667 ms/op
                 listUser·p1.00:   8.667 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8691
  mean =      3.696 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 18 
    [1.500, 2.000) = 137 
    [2.000, 2.500) = 624 
    [2.500, 3.000) = 764 
    [3.000, 3.500) = 1378 
    [3.500, 4.000) = 2782 
    [4.000, 4.500) = 1990 
    [4.500, 5.000) = 752 
    [5.000, 5.500) = 154 
    [5.500, 6.000) = 44 
    [6.000, 6.500) = 26 
    [6.500, 7.000) = 6 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      5.514 ms/op
     p(99.9000) =      8.574 ms/op
     p(99.9900) =      8.667 ms/op
     p(99.9990) =      8.667 ms/op
     p(99.9999) =      8.667 ms/op
    p(100.0000) =      8.667 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.018          ops/ms
ClientSimple.existUser                       thrpt         11.354          ops/ms
ClientSimple.getUser                         thrpt         11.797          ops/ms
ClientSimple.listUser                        thrpt          8.303          ops/ms
ClientSimple.createUser                       avgt          2.261           ms/op
ClientSimple.existUser                        avgt          2.155           ms/op
ClientSimple.getUser                          avgt          2.046           ms/op
ClientSimple.listUser                         avgt          3.480           ms/op
ClientSimple.createUser                     sample  13314   2.421 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.517           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.228           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.330           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.093           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.939           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.474           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.496           ms/op
ClientSimple.existUser                      sample  15967   2.002 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.527           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.976           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.916           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.780           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.635           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.763           ms/op
ClientSimple.getUser                        sample  14657   2.202 ± 0.039   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.668           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.089           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.415           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.011           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.509           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.524           ms/op
ClientSimple.listUser                       sample   8691   3.696 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.083           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.764           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.514           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.574           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.667           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.667           ms/op

Benchmark result is saved to 1721887564862.json
