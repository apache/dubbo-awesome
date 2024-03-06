# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.107 ops/ms
Iteration   1: 6.263 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.263 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.308 ops/ms
Iteration   1: 12.346 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.346 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.203 ops/ms
Iteration   1: 8.654 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.654 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.133 ops/ms
Iteration   1: 3.755 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.755 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.269 ±(99.9%) 0.066 ms/op
Iteration   1: 3.088 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.088 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.126 ±(99.9%) 0.034 ms/op
Iteration   1: 1.874 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.874 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.302 ±(99.9%) 0.046 ms/op
Iteration   1: 3.118 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.118 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.474 ±(99.9%) 0.231 ms/op
Iteration   1: 7.972 ±(99.9%) 0.123 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.972 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.666 ±(99.9%) 0.210 ms/op
Iteration   1: 3.178 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   2.892 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.425 ms/op
                 createUser·p0.99:   11.270 ms/op
                 createUser·p0.999:  19.628 ms/op
                 createUser·p0.9999: 19.661 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10055
  mean =      3.178 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1262 
    [ 2.500,  3.750) = 7894 
    [ 3.750,  5.000) = 518 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 128 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.425 ms/op
     p(99.0000) =     11.270 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.011 ±(99.9%) 0.063 ms/op
Iteration   1: 1.797 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.446 ms/op
                 existUser·p0.50:   1.670 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   3.060 ms/op
                 existUser·p0.999:  6.029 ms/op
                 existUser·p0.9999: 6.218 ms/op
                 existUser·p1.00:   6.275 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17792
  mean =      1.797 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 93 
    [1.000, 1.500) = 4232 
    [1.500, 2.000) = 8781 
    [2.000, 2.500) = 3694 
    [2.500, 3.000) = 796 
    [3.000, 3.500) = 93 
    [3.500, 4.000) = 20 
    [4.000, 4.500) = 2 
    [4.500, 5.000) = 4 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 51 
    [6.000, 6.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      1.670 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.060 ms/op
     p(99.9000) =      6.029 ms/op
     p(99.9900) =      6.218 ms/op
     p(99.9990) =      6.275 ms/op
     p(99.9999) =      6.275 ms/op
    p(100.0000) =      6.275 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.656 ±(99.9%) 0.216 ms/op
Iteration   1: 3.323 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   4.061 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   7.778 ms/op
                 getUser·p0.999:  19.235 ms/op
                 getUser·p0.9999: 20.808 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9624
  mean =      3.323 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1321 
    [ 2.500,  5.000) = 7977 
    [ 5.000,  7.500) = 224 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      4.061 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.778 ms/op
     p(99.9000) =     19.235 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.030 ±(99.9%) 0.370 ms/op
Iteration   1: 7.801 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   2.089 ms/op
                 listUser·p0.50:   7.373 ms/op
                 listUser·p0.90:   10.129 ms/op
                 listUser·p0.95:   11.272 ms/op
                 listUser·p0.99:   17.367 ms/op
                 listUser·p0.999:  22.998 ms/op
                 listUser·p0.9999: 26.739 ms/op
                 listUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4127
  mean =      7.801 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 169 
    [ 5.000,  7.500) = 2014 
    [ 7.500, 10.000) = 1508 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.089 ms/op
     p(50.0000) =      7.373 ms/op
     p(90.0000) =     10.129 ms/op
     p(95.0000) =     11.272 ms/op
     p(99.0000) =     17.367 ms/op
     p(99.9000) =     22.998 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     26.739 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.263          ops/ms
Client.existUser                       thrpt         12.346          ops/ms
Client.getUser                         thrpt          8.654          ops/ms
Client.listUser                        thrpt          3.755          ops/ms
Client.createUser                       avgt          3.088           ms/op
Client.existUser                        avgt          1.874           ms/op
Client.getUser                          avgt          3.118           ms/op
Client.listUser                         avgt          7.972           ms/op
Client.createUser                     sample  10055   3.178 ± 0.053   ms/op
Client.createUser:createUser·p0.00    sample          1.247           ms/op
Client.createUser:createUser·p0.50    sample          2.892           ms/op
Client.createUser:createUser·p0.90    sample          3.686           ms/op
Client.createUser:createUser·p0.95    sample          4.425           ms/op
Client.createUser:createUser·p0.99    sample         11.270           ms/op
Client.createUser:createUser·p0.999   sample         19.628           ms/op
Client.createUser:createUser·p0.9999  sample         19.661           ms/op
Client.createUser:createUser·p1.00    sample         19.661           ms/op
Client.existUser                      sample  17792   1.797 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.446           ms/op
Client.existUser:existUser·p0.50      sample          1.670           ms/op
Client.existUser:existUser·p0.90      sample          2.327           ms/op
Client.existUser:existUser·p0.95      sample          2.540           ms/op
Client.existUser:existUser·p0.99      sample          3.060           ms/op
Client.existUser:existUser·p0.999     sample          6.029           ms/op
Client.existUser:existUser·p0.9999    sample          6.218           ms/op
Client.existUser:existUser·p1.00      sample          6.275           ms/op
Client.getUser                        sample   9624   3.323 ± 0.046   ms/op
Client.getUser:getUser·p0.00          sample          1.007           ms/op
Client.getUser:getUser·p0.50          sample          3.199           ms/op
Client.getUser:getUser·p0.90          sample          4.061           ms/op
Client.getUser:getUser·p0.95          sample          4.588           ms/op
Client.getUser:getUser·p0.99          sample          7.778           ms/op
Client.getUser:getUser·p0.999         sample         19.235           ms/op
Client.getUser:getUser·p0.9999        sample         20.808           ms/op
Client.getUser:getUser·p1.00          sample         20.808           ms/op
Client.listUser                       sample   4127   7.801 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample          2.089           ms/op
Client.listUser:listUser·p0.50        sample          7.373           ms/op
Client.listUser:listUser·p0.90        sample         10.129           ms/op
Client.listUser:listUser·p0.95        sample         11.272           ms/op
Client.listUser:listUser·p0.99        sample         17.367           ms/op
Client.listUser:listUser·p0.999       sample         22.998           ms/op
Client.listUser:listUser·p0.9999      sample         26.739           ms/op
Client.listUser:listUser·p1.00        sample         26.739           ms/op
