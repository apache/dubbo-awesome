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
# Warmup Iteration   1: 2.165 ops/ms
Iteration   1: 5.296 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.296 ops/ms


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
# Warmup Iteration   1: 5.658 ops/ms
Iteration   1: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.549 ops/ms


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
# Warmup Iteration   1: 4.241 ops/ms
Iteration   1: 9.452 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.452 ops/ms


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
# Warmup Iteration   1: 2.325 ops/ms
Iteration   1: 3.868 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.868 ops/ms


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
# Warmup Iteration   1: 5.015 ±(99.9%) 0.074 ms/op
Iteration   1: 3.258 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.258 ms/op


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
# Warmup Iteration   1: 3.174 ±(99.9%) 0.027 ms/op
Iteration   1: 1.897 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.897 ms/op


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
# Warmup Iteration   1: 4.711 ±(99.9%) 0.055 ms/op
Iteration   1: 3.103 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.103 ms/op


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
# Warmup Iteration   1: 11.358 ±(99.9%) 0.262 ms/op
Iteration   1: 7.878 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.878 ms/op


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.113 ms/op
Iteration   1: 2.978 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.707 ms/op
                 createUser·p0.90:   3.726 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   7.529 ms/op
                 createUser·p0.999:  28.034 ms/op
                 createUser·p0.9999: 28.594 ms/op
                 createUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10732
  mean =      2.978 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2695 
    [ 2.500,  5.000) = 7789 
    [ 5.000,  7.500) = 139 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      2.707 ms/op
     p(90.0000) =      3.726 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      7.529 ms/op
     p(99.9000) =     28.034 ms/op
     p(99.9900) =     28.594 ms/op
     p(99.9990) =     28.606 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.079 ms/op
Iteration   1: 1.670 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.310 ms/op
                 existUser·p0.50:   1.532 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   2.826 ms/op
                 existUser·p0.999:  6.052 ms/op
                 existUser·p0.9999: 6.342 ms/op
                 existUser·p1.00:   6.816 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19183
  mean =      1.670 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 6 
    [0.500, 1.000) = 52 
    [1.000, 1.500) = 8631 
    [1.500, 2.000) = 6800 
    [2.000, 2.500) = 2704 
    [2.500, 3.000) = 869 
    [3.000, 3.500) = 36 
    [3.500, 4.000) = 24 
    [4.000, 4.500) = 6 
    [4.500, 5.000) = 5 
    [5.000, 5.500) = 10 
    [5.500, 6.000) = 11 
    [6.000, 6.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      1.532 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      2.826 ms/op
     p(99.9000) =      6.052 ms/op
     p(99.9900) =      6.342 ms/op
     p(99.9990) =      6.816 ms/op
     p(99.9999) =      6.816 ms/op
    p(100.0000) =      6.816 ms/op


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
# Warmup Iteration   1: 4.755 ±(99.9%) 0.120 ms/op
Iteration   1: 3.074 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  21.684 ms/op
                 getUser·p0.9999: 23.084 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10414
  mean =      3.074 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1641 
    [ 2.500,  5.000) = 8657 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     21.684 ms/op
     p(99.9900) =     23.084 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 11.613 ±(99.9%) 0.433 ms/op
Iteration   1: 8.571 ±(99.9%) 0.135 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   8.167 ms/op
                 listUser·p0.90:   11.272 ms/op
                 listUser·p0.95:   12.483 ms/op
                 listUser·p0.99:   19.415 ms/op
                 listUser·p0.999:  25.125 ms/op
                 listUser·p0.9999: 25.723 ms/op
                 listUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3750
  mean =      8.571 ±(99.9%) 0.135 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 92 
    [ 5.000,  7.500) = 1189 
    [ 7.500, 10.000) = 1687 
    [10.000, 12.500) = 594 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      8.167 ms/op
     p(90.0000) =     11.272 ms/op
     p(95.0000) =     12.483 ms/op
     p(99.0000) =     19.415 ms/op
     p(99.9000) =     25.125 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.296          ops/ms
Client.existUser                       thrpt         10.549          ops/ms
Client.getUser                         thrpt          9.452          ops/ms
Client.listUser                        thrpt          3.868          ops/ms
Client.createUser                       avgt          3.258           ms/op
Client.existUser                        avgt          1.897           ms/op
Client.getUser                          avgt          3.103           ms/op
Client.listUser                         avgt          7.878           ms/op
Client.createUser                     sample  10732   2.978 ± 0.050   ms/op
Client.createUser:createUser·p0.00    sample          0.987           ms/op
Client.createUser:createUser·p0.50    sample          2.707           ms/op
Client.createUser:createUser·p0.90    sample          3.726           ms/op
Client.createUser:createUser·p0.95    sample          4.141           ms/op
Client.createUser:createUser·p0.99    sample          7.529           ms/op
Client.createUser:createUser·p0.999   sample         28.034           ms/op
Client.createUser:createUser·p0.9999  sample         28.594           ms/op
Client.createUser:createUser·p1.00    sample         28.606           ms/op
Client.existUser                      sample  19183   1.670 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.310           ms/op
Client.existUser:existUser·p0.50      sample          1.532           ms/op
Client.existUser:existUser·p0.90      sample          2.343           ms/op
Client.existUser:existUser·p0.95      sample          2.507           ms/op
Client.existUser:existUser·p0.99      sample          2.826           ms/op
Client.existUser:existUser·p0.999     sample          6.052           ms/op
Client.existUser:existUser·p0.9999    sample          6.342           ms/op
Client.existUser:existUser·p1.00      sample          6.816           ms/op
Client.getUser                        sample  10414   3.074 ± 0.040   ms/op
Client.getUser:getUser·p0.00          sample          0.748           ms/op
Client.getUser:getUser·p0.50          sample          2.982           ms/op
Client.getUser:getUser·p0.90          sample          3.740           ms/op
Client.getUser:getUser·p0.95          sample          4.084           ms/op
Client.getUser:getUser·p0.99          sample          5.251           ms/op
Client.getUser:getUser·p0.999         sample         21.684           ms/op
Client.getUser:getUser·p0.9999        sample         23.084           ms/op
Client.getUser:getUser·p1.00          sample         23.101           ms/op
Client.listUser                       sample   3750   8.571 ± 0.135   ms/op
Client.listUser:listUser·p0.00        sample          2.154           ms/op
Client.listUser:listUser·p0.50        sample          8.167           ms/op
Client.listUser:listUser·p0.90        sample         11.272           ms/op
Client.listUser:listUser·p0.95        sample         12.483           ms/op
Client.listUser:listUser·p0.99        sample         19.415           ms/op
Client.listUser:listUser·p0.999       sample         25.125           ms/op
Client.listUser:listUser·p0.9999      sample         25.723           ms/op
Client.listUser:listUser·p1.00        sample         25.723           ms/op
