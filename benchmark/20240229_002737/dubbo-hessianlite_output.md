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
# Warmup Iteration   1: 2.364 ops/ms
Iteration   1: 6.336 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.336 ops/ms


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
# Warmup Iteration   1: 5.508 ops/ms
Iteration   1: 13.615 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.615 ops/ms


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
# Warmup Iteration   1: 3.744 ops/ms
Iteration   1: 8.012 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.012 ops/ms


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
# Warmup Iteration   1: 2.012 ops/ms
Iteration   1: 3.747 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.747 ops/ms


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
# Warmup Iteration   1: 5.224 ±(99.9%) 0.072 ms/op
Iteration   1: 3.110 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.110 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.036 ms/op
Iteration   1: 2.018 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.018 ms/op


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.047 ms/op
Iteration   1: 2.993 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.993 ms/op


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
# Warmup Iteration   1: 12.542 ±(99.9%) 0.206 ms/op
Iteration   1: 7.803 ±(99.9%) 0.122 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.803 ms/op


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
# Warmup Iteration   1: 4.743 ±(99.9%) 0.111 ms/op
Iteration   1: 3.139 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   2.904 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   7.045 ms/op
                 createUser·p0.999:  18.973 ms/op
                 createUser·p0.9999: 19.693 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10153
  mean =      3.139 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1865 
    [ 2.500,  3.750) = 6988 
    [ 3.750,  5.000) = 1088 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     19.693 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.161 ±(99.9%) 0.087 ms/op
Iteration   1: 2.001 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.342 ms/op
                 existUser·p0.50:   1.915 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   4.255 ms/op
                 existUser·p0.999:  20.515 ms/op
                 existUser·p0.9999: 21.162 ms/op
                 existUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15962
  mean =      2.001 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14877 
    [ 2.500,  5.000) = 977 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      4.255 ms/op
     p(99.9000) =     20.515 ms/op
     p(99.9900) =     21.162 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.095 ms/op
Iteration   1: 2.937 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   2.851 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.934 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  7.015 ms/op
                 getUser·p0.9999: 9.041 ms/op
                 getUser·p1.00:   9.126 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10891
  mean =      2.937 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 6 
    [ 1.500,  2.000) = 198 
    [ 2.000,  2.500) = 2655 
    [ 2.500,  3.000) = 3598 
    [ 3.000,  3.500) = 2817 
    [ 3.500,  4.000) = 1119 
    [ 4.000,  4.500) = 236 
    [ 4.500,  5.000) = 126 
    [ 5.000,  5.500) = 73 
    [ 5.500,  6.000) = 25 
    [ 6.000,  6.500) = 24 
    [ 6.500,  7.000) = 4 
    [ 7.000,  7.500) = 2 
    [ 7.500,  8.000) = 5 
    [ 8.000,  8.500) = 2 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.934 ms/op
     p(99.0000) =      5.153 ms/op
     p(99.9000) =      7.015 ms/op
     p(99.9900) =      9.041 ms/op
     p(99.9990) =      9.126 ms/op
     p(99.9999) =      9.126 ms/op
    p(100.0000) =      9.126 ms/op


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
# Warmup Iteration   1: 11.993 ±(99.9%) 0.402 ms/op
Iteration   1: 7.626 ±(99.9%) 0.099 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   7.274 ms/op
                 listUser·p0.90:   9.907 ms/op
                 listUser·p0.95:   10.863 ms/op
                 listUser·p0.99:   15.284 ms/op
                 listUser·p0.999:  19.819 ms/op
                 listUser·p0.9999: 22.872 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4172
  mean =      7.626 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 103 
    [ 5.000,  7.500) = 2240 
    [ 7.500, 10.000) = 1427 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.679 ms/op
     p(50.0000) =      7.274 ms/op
     p(90.0000) =      9.907 ms/op
     p(95.0000) =     10.863 ms/op
     p(99.0000) =     15.284 ms/op
     p(99.9000) =     19.819 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.336          ops/ms
Client.existUser                       thrpt         13.615          ops/ms
Client.getUser                         thrpt          8.012          ops/ms
Client.listUser                        thrpt          3.747          ops/ms
Client.createUser                       avgt          3.110           ms/op
Client.existUser                        avgt          2.018           ms/op
Client.getUser                          avgt          2.993           ms/op
Client.listUser                         avgt          7.803           ms/op
Client.createUser                     sample  10153   3.139 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          1.120           ms/op
Client.createUser:createUser·p0.50    sample          2.904           ms/op
Client.createUser:createUser·p0.90    sample          3.863           ms/op
Client.createUser:createUser·p0.95    sample          4.129           ms/op
Client.createUser:createUser·p0.99    sample          7.045           ms/op
Client.createUser:createUser·p0.999   sample         18.973           ms/op
Client.createUser:createUser·p0.9999  sample         19.693           ms/op
Client.createUser:createUser·p1.00    sample         19.694           ms/op
Client.existUser                      sample  15962   2.001 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.342           ms/op
Client.existUser:existUser·p0.50      sample          1.915           ms/op
Client.existUser:existUser·p0.90      sample          2.367           ms/op
Client.existUser:existUser·p0.95      sample          2.630           ms/op
Client.existUser:existUser·p0.99      sample          4.255           ms/op
Client.existUser:existUser·p0.999     sample         20.515           ms/op
Client.existUser:existUser·p0.9999    sample         21.162           ms/op
Client.existUser:existUser·p1.00      sample         21.201           ms/op
Client.getUser                        sample  10891   2.937 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          1.065           ms/op
Client.getUser:getUser·p0.50          sample          2.851           ms/op
Client.getUser:getUser·p0.90          sample          3.658           ms/op
Client.getUser:getUser·p0.95          sample          3.934           ms/op
Client.getUser:getUser·p0.99          sample          5.153           ms/op
Client.getUser:getUser·p0.999         sample          7.015           ms/op
Client.getUser:getUser·p0.9999        sample          9.041           ms/op
Client.getUser:getUser·p1.00          sample          9.126           ms/op
Client.listUser                       sample   4172   7.626 ± 0.099   ms/op
Client.listUser:listUser·p0.00        sample          2.679           ms/op
Client.listUser:listUser·p0.50        sample          7.274           ms/op
Client.listUser:listUser·p0.90        sample          9.907           ms/op
Client.listUser:listUser·p0.95        sample         10.863           ms/op
Client.listUser:listUser·p0.99        sample         15.284           ms/op
Client.listUser:listUser·p0.999       sample         19.819           ms/op
Client.listUser:listUser·p0.9999      sample         22.872           ms/op
Client.listUser:listUser·p1.00        sample         22.872           ms/op
