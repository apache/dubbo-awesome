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
# Warmup Iteration   1: 2.135 ops/ms
Iteration   1: 6.526 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.526 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.602 ops/ms
Iteration   1: 12.807 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.807 ops/ms


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
# Warmup Iteration   1: 4.370 ops/ms
Iteration   1: 8.349 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.349 ops/ms


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
# Warmup Iteration   1: 2.126 ops/ms
Iteration   1: 3.559 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.559 ops/ms


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
# Warmup Iteration   1: 5.734 ±(99.9%) 0.096 ms/op
Iteration   1: 3.130 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.130 ms/op


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.045 ms/op
Iteration   1: 1.917 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.917 ms/op


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.056 ms/op
Iteration   1: 2.714 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.714 ms/op


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
# Warmup Iteration   1: 13.270 ±(99.9%) 0.220 ms/op
Iteration   1: 9.644 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.644 ms/op


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
# Warmup Iteration   1: 5.000 ±(99.9%) 0.119 ms/op
Iteration   1: 2.957 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   2.826 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   7.574 ms/op
                 createUser·p0.999:  12.485 ms/op
                 createUser·p0.9999: 12.878 ms/op
                 createUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11045
  mean =      2.957 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 2608 
    [ 2.500,  3.750) = 7645 
    [ 3.750,  5.000) = 536 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      7.574 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.066 ms/op
Iteration   1: 1.848 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   1.706 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   3.109 ms/op
                 existUser·p0.999:  4.561 ms/op
                 existUser·p0.9999: 5.720 ms/op
                 existUser·p1.00:   5.726 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17288
  mean =      1.848 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 64 
    [1.000, 1.500) = 2689 
    [1.500, 2.000) = 9415 
    [2.000, 2.500) = 3696 
    [2.500, 3.000) = 1198 
    [3.000, 3.500) = 128 
    [3.500, 4.000) = 26 
    [4.000, 4.500) = 53 
    [4.500, 5.000) = 12 
    [5.000, 5.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.109 ms/op
     p(99.9000) =      4.561 ms/op
     p(99.9900) =      5.720 ms/op
     p(99.9990) =      5.726 ms/op
     p(99.9999) =      5.726 ms/op
    p(100.0000) =      5.726 ms/op


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
# Warmup Iteration   1: 4.542 ±(99.9%) 0.129 ms/op
Iteration   1: 2.829 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.806 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  5.828 ms/op
                 getUser·p0.9999: 8.617 ms/op
                 getUser·p1.00:   8.765 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11299
  mean =      2.829 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 128 
    [1.500, 2.000) = 643 
    [2.000, 2.500) = 2820 
    [2.500, 3.000) = 3245 
    [3.000, 3.500) = 3206 
    [3.500, 4.000) = 924 
    [4.000, 4.500) = 197 
    [4.500, 5.000) = 55 
    [5.000, 5.500) = 53 
    [5.500, 6.000) = 20 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      5.828 ms/op
     p(99.9900) =      8.617 ms/op
     p(99.9990) =      8.765 ms/op
     p(99.9999) =      8.765 ms/op
    p(100.0000) =      8.765 ms/op


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
# Warmup Iteration   1: 11.892 ±(99.9%) 0.405 ms/op
Iteration   1: 7.498 ±(99.9%) 0.122 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   7.131 ms/op
                 listUser·p0.90:   9.519 ms/op
                 listUser·p0.95:   10.535 ms/op
                 listUser·p0.99:   17.348 ms/op
                 listUser·p0.999:  30.236 ms/op
                 listUser·p0.9999: 30.933 ms/op
                 listUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4258
  mean =      7.498 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 200 
    [ 5.000,  7.500) = 2352 
    [ 7.500, 10.000) = 1410 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.535 ms/op
     p(50.0000) =      7.131 ms/op
     p(90.0000) =      9.519 ms/op
     p(95.0000) =     10.535 ms/op
     p(99.0000) =     17.348 ms/op
     p(99.9000) =     30.236 ms/op
     p(99.9900) =     30.933 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.526          ops/ms
Client.existUser                       thrpt         12.807          ops/ms
Client.getUser                         thrpt          8.349          ops/ms
Client.listUser                        thrpt          3.559          ops/ms
Client.createUser                       avgt          3.130           ms/op
Client.existUser                        avgt          1.917           ms/op
Client.getUser                          avgt          2.714           ms/op
Client.listUser                         avgt          9.644           ms/op
Client.createUser                     sample  11045   2.957 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.139           ms/op
Client.createUser:createUser·p0.50    sample          2.826           ms/op
Client.createUser:createUser·p0.90    sample          3.531           ms/op
Client.createUser:createUser·p0.95    sample          4.145           ms/op
Client.createUser:createUser·p0.99    sample          7.574           ms/op
Client.createUser:createUser·p0.999   sample         12.485           ms/op
Client.createUser:createUser·p0.9999  sample         12.878           ms/op
Client.createUser:createUser·p1.00    sample         12.878           ms/op
Client.existUser                      sample  17288   1.848 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.693           ms/op
Client.existUser:existUser·p0.50      sample          1.706           ms/op
Client.existUser:existUser·p0.90      sample          2.433           ms/op
Client.existUser:existUser·p0.95      sample          2.638           ms/op
Client.existUser:existUser·p0.99      sample          3.109           ms/op
Client.existUser:existUser·p0.999     sample          4.561           ms/op
Client.existUser:existUser·p0.9999    sample          5.720           ms/op
Client.existUser:existUser·p1.00      sample          5.726           ms/op
Client.getUser                        sample  11299   2.829 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          0.951           ms/op
Client.getUser:getUser·p0.50          sample          2.806           ms/op
Client.getUser:getUser·p0.90          sample          3.539           ms/op
Client.getUser:getUser·p0.95          sample          3.781           ms/op
Client.getUser:getUser·p0.99          sample          4.645           ms/op
Client.getUser:getUser·p0.999         sample          5.828           ms/op
Client.getUser:getUser·p0.9999        sample          8.617           ms/op
Client.getUser:getUser·p1.00          sample          8.765           ms/op
Client.listUser                       sample   4258   7.498 ± 0.122   ms/op
Client.listUser:listUser·p0.00        sample          2.535           ms/op
Client.listUser:listUser·p0.50        sample          7.131           ms/op
Client.listUser:listUser·p0.90        sample          9.519           ms/op
Client.listUser:listUser·p0.95        sample         10.535           ms/op
Client.listUser:listUser·p0.99        sample         17.348           ms/op
Client.listUser:listUser·p0.999       sample         30.236           ms/op
Client.listUser:listUser·p0.9999      sample         30.933           ms/op
Client.listUser:listUser·p1.00        sample         30.933           ms/op
