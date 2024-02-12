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
# Warmup Iteration   1: 2.366 ops/ms
Iteration   1: 5.575 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.575 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.457 ops/ms
Iteration   1: 12.954 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.954 ops/ms


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
# Warmup Iteration   1: 4.755 ops/ms
Iteration   1: 9.005 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.005 ops/ms


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
# Warmup Iteration   1: 2.242 ops/ms
Iteration   1: 3.518 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.518 ops/ms


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
# Warmup Iteration   1: 5.364 ±(99.9%) 0.067 ms/op
Iteration   1: 2.953 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.953 ms/op


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
# Warmup Iteration   1: 3.196 ±(99.9%) 0.030 ms/op
Iteration   1: 1.881 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.881 ms/op


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
# Warmup Iteration   1: 4.765 ±(99.9%) 0.050 ms/op
Iteration   1: 2.726 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.726 ms/op


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
# Warmup Iteration   1: 12.646 ±(99.9%) 0.191 ms/op
Iteration   1: 7.854 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.854 ms/op


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
# Warmup Iteration   1: 4.993 ±(99.9%) 0.123 ms/op
Iteration   1: 3.160 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   2.769 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   12.075 ms/op
                 createUser·p0.999:  19.694 ms/op
                 createUser·p0.9999: 20.476 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10173
  mean =      3.160 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2684 
    [ 2.500,  5.000) = 7089 
    [ 5.000,  7.500) = 152 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      2.769 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     20.476 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.247 ±(99.9%) 0.087 ms/op
Iteration   1: 1.832 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   1.794 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   3.045 ms/op
                 existUser·p0.999:  4.562 ms/op
                 existUser·p0.9999: 6.218 ms/op
                 existUser·p1.00:   6.218 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17460
  mean =      1.832 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 152 
    [1.000, 1.500) = 2890 
    [1.500, 2.000) = 9653 
    [2.000, 2.500) = 4143 
    [2.500, 3.000) = 441 
    [3.000, 3.500) = 41 
    [3.500, 4.000) = 56 
    [4.000, 4.500) = 66 
    [4.500, 5.000) = 6 
    [5.000, 5.500) = 7 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      3.045 ms/op
     p(99.9000) =      4.562 ms/op
     p(99.9900) =      6.218 ms/op
     p(99.9990) =      6.218 ms/op
     p(99.9999) =      6.218 ms/op
    p(100.0000) =      6.218 ms/op


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.100 ms/op
Iteration   1: 3.053 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.237 ms/op
                 getUser·p0.999:  13.294 ms/op
                 getUser·p0.9999: 19.692 ms/op
                 getUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10464
  mean =      3.053 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 2043 
    [ 2.500,  3.750) = 7282 
    [ 3.750,  5.000) = 928 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.237 ms/op
     p(99.9000) =     13.294 ms/op
     p(99.9900) =     19.692 ms/op
     p(99.9990) =     19.694 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 11.138 ±(99.9%) 0.346 ms/op
Iteration   1: 8.485 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   2.060 ms/op
                 listUser·p0.50:   8.086 ms/op
                 listUser·p0.90:   11.390 ms/op
                 listUser·p0.95:   12.550 ms/op
                 listUser·p0.99:   15.015 ms/op
                 listUser·p0.999:  19.788 ms/op
                 listUser·p0.9999: 21.398 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3777
  mean =      8.485 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 77 
    [ 5.000,  7.500) = 1320 
    [ 7.500, 10.000) = 1558 
    [10.000, 12.500) = 620 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.060 ms/op
     p(50.0000) =      8.086 ms/op
     p(90.0000) =     11.390 ms/op
     p(95.0000) =     12.550 ms/op
     p(99.0000) =     15.015 ms/op
     p(99.9000) =     19.788 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.575          ops/ms
Client.existUser                       thrpt         12.954          ops/ms
Client.getUser                         thrpt          9.005          ops/ms
Client.listUser                        thrpt          3.518          ops/ms
Client.createUser                       avgt          2.953           ms/op
Client.existUser                        avgt          1.881           ms/op
Client.getUser                          avgt          2.726           ms/op
Client.listUser                         avgt          7.854           ms/op
Client.createUser                     sample  10173   3.160 ± 0.055   ms/op
Client.createUser:createUser·p0.00    sample          1.122           ms/op
Client.createUser:createUser·p0.50    sample          2.769           ms/op
Client.createUser:createUser·p0.90    sample          3.990           ms/op
Client.createUser:createUser·p0.95    sample          4.473           ms/op
Client.createUser:createUser·p0.99    sample         12.075           ms/op
Client.createUser:createUser·p0.999   sample         19.694           ms/op
Client.createUser:createUser·p0.9999  sample         20.476           ms/op
Client.createUser:createUser·p1.00    sample         20.480           ms/op
Client.existUser                      sample  17460   1.832 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.558           ms/op
Client.existUser:existUser·p0.50      sample          1.794           ms/op
Client.existUser:existUser·p0.90      sample          2.265           ms/op
Client.existUser:existUser·p0.95      sample          2.429           ms/op
Client.existUser:existUser·p0.99      sample          3.045           ms/op
Client.existUser:existUser·p0.999     sample          4.562           ms/op
Client.existUser:existUser·p0.9999    sample          6.218           ms/op
Client.existUser:existUser·p1.00      sample          6.218           ms/op
Client.getUser                        sample  10464   3.053 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          0.859           ms/op
Client.getUser:getUser·p0.50          sample          2.933           ms/op
Client.getUser:getUser·p0.90          sample          3.813           ms/op
Client.getUser:getUser·p0.95          sample          4.227           ms/op
Client.getUser:getUser·p0.99          sample          6.237           ms/op
Client.getUser:getUser·p0.999         sample         13.294           ms/op
Client.getUser:getUser·p0.9999        sample         19.692           ms/op
Client.getUser:getUser·p1.00          sample         19.694           ms/op
Client.listUser                       sample   3777   8.485 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample          2.060           ms/op
Client.listUser:listUser·p0.50        sample          8.086           ms/op
Client.listUser:listUser·p0.90        sample         11.390           ms/op
Client.listUser:listUser·p0.95        sample         12.550           ms/op
Client.listUser:listUser·p0.99        sample         15.015           ms/op
Client.listUser:listUser·p0.999       sample         19.788           ms/op
Client.listUser:listUser·p0.9999      sample         21.398           ms/op
Client.listUser:listUser·p1.00        sample         21.398           ms/op
