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
# Warmup Iteration   1: 1.976 ops/ms
Iteration   1: 8.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.087 ops/ms


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
# Warmup Iteration   1: 5.430 ops/ms
Iteration   1: 12.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.870 ops/ms


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
# Warmup Iteration   1: 5.877 ops/ms
Iteration   1: 11.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.773 ops/ms


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
# Warmup Iteration   1: 5.194 ops/ms
Iteration   1: 8.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.395 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.063 ±(99.9%) 0.082 ms/op
Iteration   1: 2.318 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.318 ms/op


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
# Warmup Iteration   1: 3.014 ±(99.9%) 0.043 ms/op
Iteration   1: 1.849 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.849 ms/op


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
# Warmup Iteration   1: 3.477 ±(99.9%) 0.061 ms/op
Iteration   1: 1.943 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.943 ms/op


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
# Warmup Iteration   1: 4.234 ±(99.9%) 0.080 ms/op
Iteration   1: 3.676 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.676 ms/op


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.101 ms/op
Iteration   1: 2.093 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   1.962 ms/op
                 createUser·p0.90:   2.470 ms/op
                 createUser·p0.95:   2.707 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  13.905 ms/op
                 createUser·p0.9999: 14.478 ms/op
                 createUser·p1.00:   14.565 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15302
  mean =      2.093 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 13808 
    [ 2.500,  3.750) = 1147 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      1.962 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     13.905 ms/op
     p(99.9900) =     14.478 ms/op
     p(99.9990) =     14.565 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.798 ±(99.9%) 0.062 ms/op
Iteration   1: 2.041 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   1.913 ms/op
                 existUser·p0.90:   2.511 ms/op
                 existUser·p0.95:   2.826 ms/op
                 existUser·p0.99:   5.408 ms/op
                 existUser·p0.999:  19.300 ms/op
                 existUser·p0.9999: 19.530 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15661
  mean =      2.041 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 424 
    [ 1.250,  2.500) = 13632 
    [ 2.500,  3.750) = 1234 
    [ 3.750,  5.000) = 178 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      5.408 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 3.413 ±(99.9%) 0.086 ms/op
Iteration   1: 2.170 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.518 ms/op
                 getUser·p0.50:   2.118 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   2.888 ms/op
                 getUser·p0.99:   4.209 ms/op
                 getUser·p0.999:  11.764 ms/op
                 getUser·p0.9999: 12.281 ms/op
                 getUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14734
  mean =      2.170 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 233 
    [ 1.250,  2.500) = 11049 
    [ 2.500,  3.750) = 3278 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      4.209 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     12.281 ms/op
     p(99.9990) =     12.304 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


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
# Warmup Iteration   1: 4.487 ±(99.9%) 0.133 ms/op
Iteration   1: 3.672 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  7.957 ms/op
                 listUser·p0.9999: 8.946 ms/op
                 listUser·p1.00:   8.946 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8709
  mean =      3.672 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 1 
    [1.500, 2.000) = 59 
    [2.000, 2.500) = 544 
    [2.500, 3.000) = 1047 
    [3.000, 3.500) = 1912 
    [3.500, 4.000) = 2426 
    [4.000, 4.500) = 1927 
    [4.500, 5.000) = 487 
    [5.000, 5.500) = 116 
    [5.500, 6.000) = 63 
    [6.000, 6.500) = 25 
    [6.500, 7.000) = 35 
    [7.000, 7.500) = 32 
    [7.500, 8.000) = 31 
    [8.000, 8.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =      7.957 ms/op
     p(99.9900) =      8.946 ms/op
     p(99.9990) =      8.946 ms/op
     p(99.9999) =      8.946 ms/op
    p(100.0000) =      8.946 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.087          ops/ms
ClientSimple.existUser                       thrpt         12.870          ops/ms
ClientSimple.getUser                         thrpt         11.773          ops/ms
ClientSimple.listUser                        thrpt          8.395          ops/ms
ClientSimple.createUser                       avgt          2.318           ms/op
ClientSimple.existUser                        avgt          1.849           ms/op
ClientSimple.getUser                          avgt          1.943           ms/op
ClientSimple.listUser                         avgt          3.676           ms/op
ClientSimple.createUser                     sample  15302   2.093 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.794           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.962           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.470           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.226           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.905           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.478           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.565           ms/op
ClientSimple.existUser                      sample  15661   2.041 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.573           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.913           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.826           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.408           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.300           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.530           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.530           ms/op
ClientSimple.getUser                        sample  14734   2.170 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.518           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.209           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.764           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.281           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.304           ms/op
ClientSimple.listUser                       sample   8709   3.672 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.364           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.690           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.783           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.957           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.946           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.946           ms/op

Benchmark result is saved to 1725797190742.json
