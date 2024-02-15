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
# Warmup Iteration   1: 2.138 ops/ms
Iteration   1: 5.925 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.925 ops/ms


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
# Warmup Iteration   1: 6.201 ops/ms
Iteration   1: 12.132 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.132 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.715 ops/ms
Iteration   1: 8.031 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.031 ops/ms


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
# Warmup Iteration   1: 2.118 ops/ms
Iteration   1: 3.439 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.439 ops/ms


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
# Warmup Iteration   1: 5.275 ±(99.9%) 0.081 ms/op
Iteration   1: 3.112 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.112 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.038 ms/op
Iteration   1: 1.966 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.966 ms/op


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
# Warmup Iteration   1: 4.882 ±(99.9%) 0.055 ms/op
Iteration   1: 3.078 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.078 ms/op


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
# Warmup Iteration   1: 12.563 ±(99.9%) 0.197 ms/op
Iteration   1: 9.079 ±(99.9%) 0.118 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.079 ms/op


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
# Warmup Iteration   1: 5.372 ±(99.9%) 0.124 ms/op
Iteration   1: 3.144 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.468 ms/op
                 createUser·p0.99:   9.470 ms/op
                 createUser·p0.999:  22.014 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10191
  mean =      3.144 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1844 
    [ 2.500,  5.000) = 8108 
    [ 5.000,  7.500) = 130 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.468 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     22.014 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 3.238 ±(99.9%) 0.092 ms/op
Iteration   1: 2.039 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   1.957 ms/op
                 existUser·p0.90:   2.580 ms/op
                 existUser·p0.95:   2.773 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  8.640 ms/op
                 existUser·p0.9999: 12.059 ms/op
                 existUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15670
  mean =      2.039 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 346 
    [ 1.250,  2.500) = 13103 
    [ 2.500,  3.750) = 1997 
    [ 3.750,  5.000) = 132 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      1.957 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.640 ms/op
     p(99.9900) =     12.059 ms/op
     p(99.9990) =     12.059 ms/op
     p(99.9999) =     12.059 ms/op
    p(100.0000) =     12.059 ms/op


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
# Warmup Iteration   1: 4.662 ±(99.9%) 0.121 ms/op
Iteration   1: 3.335 ±(99.9%) 0.043 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.176 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.596 ms/op
                 getUser·p0.999:  16.263 ms/op
                 getUser·p0.9999: 17.334 ms/op
                 getUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9592
  mean =      3.335 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 1800 
    [ 2.500,  3.750) = 5138 
    [ 3.750,  5.000) = 2380 
    [ 5.000,  6.250) = 152 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.176 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.596 ms/op
     p(99.9000) =     16.263 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.454 ±(99.9%) 0.450 ms/op
Iteration   1: 9.277 ±(99.9%) 0.136 ms/op
                 listUser·p0.00:   2.843 ms/op
                 listUser·p0.50:   8.798 ms/op
                 listUser·p0.90:   12.501 ms/op
                 listUser·p0.95:   13.926 ms/op
                 listUser·p0.99:   16.896 ms/op
                 listUser·p0.999:  20.000 ms/op
                 listUser·p0.9999: 23.888 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3438
  mean =      9.277 ±(99.9%) 0.136 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 34 
    [ 5.000,  7.500) = 681 
    [ 7.500, 10.000) = 1690 
    [10.000, 12.500) = 681 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.843 ms/op
     p(50.0000) =      8.798 ms/op
     p(90.0000) =     12.501 ms/op
     p(95.0000) =     13.926 ms/op
     p(99.0000) =     16.896 ms/op
     p(99.9000) =     20.000 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     23.888 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.925          ops/ms
Client.existUser                       thrpt         12.132          ops/ms
Client.getUser                         thrpt          8.031          ops/ms
Client.listUser                        thrpt          3.439          ops/ms
Client.createUser                       avgt          3.112           ms/op
Client.existUser                        avgt          1.966           ms/op
Client.getUser                          avgt          3.078           ms/op
Client.listUser                         avgt          9.079           ms/op
Client.createUser                     sample  10191   3.144 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          1.276           ms/op
Client.createUser:createUser·p0.50    sample          2.937           ms/op
Client.createUser:createUser·p0.90    sample          3.944           ms/op
Client.createUser:createUser·p0.95    sample          4.468           ms/op
Client.createUser:createUser·p0.99    sample          9.470           ms/op
Client.createUser:createUser·p0.999   sample         22.014           ms/op
Client.createUser:createUser·p0.9999  sample         22.118           ms/op
Client.createUser:createUser·p1.00    sample         22.118           ms/op
Client.existUser                      sample  15670   2.039 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.782           ms/op
Client.existUser:existUser·p0.50      sample          1.957           ms/op
Client.existUser:existUser·p0.90      sample          2.580           ms/op
Client.existUser:existUser·p0.95      sample          2.773           ms/op
Client.existUser:existUser·p0.99      sample          4.375           ms/op
Client.existUser:existUser·p0.999     sample          8.640           ms/op
Client.existUser:existUser·p0.9999    sample         12.059           ms/op
Client.existUser:existUser·p1.00      sample         12.059           ms/op
Client.getUser                        sample   9592   3.335 ± 0.043   ms/op
Client.getUser:getUser·p0.00          sample          0.944           ms/op
Client.getUser:getUser·p0.50          sample          3.176           ms/op
Client.getUser:getUser·p0.90          sample          4.325           ms/op
Client.getUser:getUser·p0.95          sample          4.686           ms/op
Client.getUser:getUser·p0.99          sample          6.596           ms/op
Client.getUser:getUser·p0.999         sample         16.263           ms/op
Client.getUser:getUser·p0.9999        sample         17.334           ms/op
Client.getUser:getUser·p1.00          sample         17.334           ms/op
Client.listUser                       sample   3438   9.277 ± 0.136   ms/op
Client.listUser:listUser·p0.00        sample          2.843           ms/op
Client.listUser:listUser·p0.50        sample          8.798           ms/op
Client.listUser:listUser·p0.90        sample         12.501           ms/op
Client.listUser:listUser·p0.95        sample         13.926           ms/op
Client.listUser:listUser·p0.99        sample         16.896           ms/op
Client.listUser:listUser·p0.999       sample         20.000           ms/op
Client.listUser:listUser·p0.9999      sample         23.888           ms/op
Client.listUser:listUser·p1.00        sample         23.888           ms/op
