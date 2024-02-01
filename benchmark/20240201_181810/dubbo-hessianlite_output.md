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
# Warmup Iteration   1: 2.583 ops/ms
Iteration   1: 6.563 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.563 ops/ms


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
# Warmup Iteration   1: 5.922 ops/ms
Iteration   1: 14.127 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.127 ops/ms


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
# Warmup Iteration   1: 4.445 ops/ms
Iteration   1: 8.305 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.305 ops/ms


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
# Warmup Iteration   1: 1.807 ops/ms
Iteration   1: 3.344 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.344 ops/ms


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
# Warmup Iteration   1: 5.210 ±(99.9%) 0.057 ms/op
Iteration   1: 3.103 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.343 ±(99.9%) 0.033 ms/op
Iteration   1: 1.896 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.896 ms/op


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.040 ms/op
Iteration   1: 3.142 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.142 ms/op


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
# Warmup Iteration   1: 12.457 ±(99.9%) 0.294 ms/op
Iteration   1: 8.434 ±(99.9%) 0.107 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.434 ms/op


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
# Warmup Iteration   1: 5.167 ±(99.9%) 0.115 ms/op
Iteration   1: 3.008 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   2.720 ms/op
                 createUser·p0.90:   3.743 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   8.377 ms/op
                 createUser·p0.999:  17.531 ms/op
                 createUser·p0.9999: 18.121 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10640
  mean =      3.008 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2943 
    [ 2.500,  3.750) = 6647 
    [ 3.750,  5.000) = 829 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      2.720 ms/op
     p(90.0000) =      3.743 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      8.377 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     18.121 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 2.846 ±(99.9%) 0.059 ms/op
Iteration   1: 1.731 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.304 ms/op
                 existUser·p0.50:   1.653 ms/op
                 existUser·p0.90:   2.101 ms/op
                 existUser·p0.95:   2.286 ms/op
                 existUser·p0.99:   2.904 ms/op
                 existUser·p0.999:  15.499 ms/op
                 existUser·p0.9999: 15.679 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18478
  mean =      1.731 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 702 
    [ 1.250,  2.500) = 17348 
    [ 2.500,  3.750) = 349 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.304 ms/op
     p(50.0000) =      1.653 ms/op
     p(90.0000) =      2.101 ms/op
     p(95.0000) =      2.286 ms/op
     p(99.0000) =      2.904 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     15.679 ms/op
     p(99.9990) =     15.679 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.098 ms/op
Iteration   1: 3.309 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.295 ms/op
                 getUser·p0.999:  6.289 ms/op
                 getUser·p0.9999: 7.225 ms/op
                 getUser·p1.00:   7.225 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9659
  mean =      3.309 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 3 
    [1.500, 2.000) = 135 
    [2.000, 2.500) = 862 
    [2.500, 3.000) = 2086 
    [3.000, 3.500) = 3022 
    [3.500, 4.000) = 2409 
    [4.000, 4.500) = 687 
    [4.500, 5.000) = 272 
    [5.000, 5.500) = 109 
    [5.500, 6.000) = 52 
    [6.000, 6.500) = 13 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.295 ms/op
     p(99.9000) =      6.289 ms/op
     p(99.9900) =      7.225 ms/op
     p(99.9990) =      7.225 ms/op
     p(99.9999) =      7.225 ms/op
    p(100.0000) =      7.225 ms/op


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
# Warmup Iteration   1: 11.676 ±(99.9%) 0.504 ms/op
Iteration   1: 8.590 ±(99.9%) 0.153 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   8.028 ms/op
                 listUser·p0.90:   11.616 ms/op
                 listUser·p0.95:   13.631 ms/op
                 listUser·p0.99:   20.283 ms/op
                 listUser·p0.999:  25.636 ms/op
                 listUser·p0.9999: 25.919 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3729
  mean =      8.590 ±(99.9%) 0.153 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 138 
    [ 5.000,  7.500) = 1225 
    [ 7.500, 10.000) = 1540 
    [10.000, 12.500) = 564 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      8.028 ms/op
     p(90.0000) =     11.616 ms/op
     p(95.0000) =     13.631 ms/op
     p(99.0000) =     20.283 ms/op
     p(99.9000) =     25.636 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.563          ops/ms
Client.existUser                       thrpt         14.127          ops/ms
Client.getUser                         thrpt          8.305          ops/ms
Client.listUser                        thrpt          3.344          ops/ms
Client.createUser                       avgt          3.103           ms/op
Client.existUser                        avgt          1.896           ms/op
Client.getUser                          avgt          3.142           ms/op
Client.listUser                         avgt          8.434           ms/op
Client.createUser                     sample  10640   3.008 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          1.147           ms/op
Client.createUser:createUser·p0.50    sample          2.720           ms/op
Client.createUser:createUser·p0.90    sample          3.743           ms/op
Client.createUser:createUser·p0.95    sample          4.010           ms/op
Client.createUser:createUser·p0.99    sample          8.377           ms/op
Client.createUser:createUser·p0.999   sample         17.531           ms/op
Client.createUser:createUser·p0.9999  sample         18.121           ms/op
Client.createUser:createUser·p1.00    sample         18.121           ms/op
Client.existUser                      sample  18478   1.731 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.304           ms/op
Client.existUser:existUser·p0.50      sample          1.653           ms/op
Client.existUser:existUser·p0.90      sample          2.101           ms/op
Client.existUser:existUser·p0.95      sample          2.286           ms/op
Client.existUser:existUser·p0.99      sample          2.904           ms/op
Client.existUser:existUser·p0.999     sample         15.499           ms/op
Client.existUser:existUser·p0.9999    sample         15.679           ms/op
Client.existUser:existUser·p1.00      sample         15.679           ms/op
Client.getUser                        sample   9659   3.309 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.805           ms/op
Client.getUser:getUser·p0.50          sample          3.322           ms/op
Client.getUser:getUser·p0.90          sample          4.063           ms/op
Client.getUser:getUser·p0.95          sample          4.448           ms/op
Client.getUser:getUser·p0.99          sample          5.295           ms/op
Client.getUser:getUser·p0.999         sample          6.289           ms/op
Client.getUser:getUser·p0.9999        sample          7.225           ms/op
Client.getUser:getUser·p1.00          sample          7.225           ms/op
Client.listUser                       sample   3729   8.590 ± 0.153   ms/op
Client.listUser:listUser·p0.00        sample          1.049           ms/op
Client.listUser:listUser·p0.50        sample          8.028           ms/op
Client.listUser:listUser·p0.90        sample         11.616           ms/op
Client.listUser:listUser·p0.95        sample         13.631           ms/op
Client.listUser:listUser·p0.99        sample         20.283           ms/op
Client.listUser:listUser·p0.999       sample         25.636           ms/op
Client.listUser:listUser·p0.9999      sample         25.919           ms/op
Client.listUser:listUser·p1.00        sample         25.919           ms/op
