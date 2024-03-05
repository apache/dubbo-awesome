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
# Warmup Iteration   1: 1.951 ops/ms
Iteration   1: 5.738 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.738 ops/ms


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
# Warmup Iteration   1: 5.249 ops/ms
Iteration   1: 11.368 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.368 ops/ms


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
# Warmup Iteration   1: 4.142 ops/ms
Iteration   1: 7.841 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.841 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.929 ops/ms
Iteration   1: 3.288 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.288 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.813 ±(99.9%) 0.069 ms/op
Iteration   1: 3.237 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.237 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.346 ±(99.9%) 0.041 ms/op
Iteration   1: 1.754 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.754 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.883 ±(99.9%) 0.074 ms/op
Iteration   1: 3.542 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.542 ms/op


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
# Warmup Iteration   1: 14.407 ±(99.9%) 0.268 ms/op
Iteration   1: 9.837 ±(99.9%) 0.179 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.837 ms/op


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
# Warmup Iteration   1: 4.944 ±(99.9%) 0.102 ms/op
Iteration   1: 3.433 ±(99.9%) 0.071 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   4.209 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   12.108 ms/op
                 createUser·p0.999:  31.086 ms/op
                 createUser·p0.9999: 31.457 ms/op
                 createUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9341
  mean =      3.433 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1542 
    [ 2.500,  5.000) = 7287 
    [ 5.000,  7.500) = 314 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      4.209 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =     12.108 ms/op
     p(99.9000) =     31.086 ms/op
     p(99.9900) =     31.457 ms/op
     p(99.9990) =     31.457 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.193 ±(99.9%) 0.075 ms/op
Iteration   1: 1.853 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   2.957 ms/op
                 existUser·p0.999:  4.102 ms/op
                 existUser·p0.9999: 5.645 ms/op
                 existUser·p1.00:   5.775 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17230
  mean =      1.853 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 39 
    [1.000, 1.500) = 3115 
    [1.500, 2.000) = 8526 
    [2.000, 2.500) = 4607 
    [2.500, 3.000) = 806 
    [3.000, 3.500) = 82 
    [3.500, 4.000) = 30 
    [4.000, 4.500) = 14 
    [4.500, 5.000) = 3 
    [5.000, 5.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      2.957 ms/op
     p(99.9000) =      4.102 ms/op
     p(99.9900) =      5.645 ms/op
     p(99.9990) =      5.775 ms/op
     p(99.9999) =      5.775 ms/op
    p(100.0000) =      5.775 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.510 ±(99.9%) 0.099 ms/op
Iteration   1: 3.569 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.799 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  16.614 ms/op
                 getUser·p0.9999: 17.859 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8962
  mean =      3.569 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 556 
    [ 2.500,  3.750) = 5556 
    [ 3.750,  5.000) = 2468 
    [ 5.000,  6.250) = 196 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.799 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     16.614 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 12.778 ±(99.9%) 0.425 ms/op
Iteration   1: 9.316 ±(99.9%) 0.157 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   8.929 ms/op
                 listUser·p0.90:   12.501 ms/op
                 listUser·p0.95:   13.722 ms/op
                 listUser·p0.99:   19.566 ms/op
                 listUser·p0.999:  26.144 ms/op
                 listUser·p0.9999: 28.803 ms/op
                 listUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3489
  mean =      9.316 ±(99.9%) 0.157 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 60 
    [ 5.000,  7.500) = 796 
    [ 7.500, 10.000) = 1503 
    [10.000, 12.500) = 780 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.548 ms/op
     p(50.0000) =      8.929 ms/op
     p(90.0000) =     12.501 ms/op
     p(95.0000) =     13.722 ms/op
     p(99.0000) =     19.566 ms/op
     p(99.9000) =     26.144 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.738          ops/ms
Client.existUser                       thrpt         11.368          ops/ms
Client.getUser                         thrpt          7.841          ops/ms
Client.listUser                        thrpt          3.288          ops/ms
Client.createUser                       avgt          3.237           ms/op
Client.existUser                        avgt          1.754           ms/op
Client.getUser                          avgt          3.542           ms/op
Client.listUser                         avgt          9.837           ms/op
Client.createUser                     sample   9341   3.433 ± 0.071   ms/op
Client.createUser:createUser·p0.00    sample          1.186           ms/op
Client.createUser:createUser·p0.50    sample          3.170           ms/op
Client.createUser:createUser·p0.90    sample          4.209           ms/op
Client.createUser:createUser·p0.95    sample          5.112           ms/op
Client.createUser:createUser·p0.99    sample         12.108           ms/op
Client.createUser:createUser·p0.999   sample         31.086           ms/op
Client.createUser:createUser·p0.9999  sample         31.457           ms/op
Client.createUser:createUser·p1.00    sample         31.457           ms/op
Client.existUser                      sample  17230   1.853 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.715           ms/op
Client.existUser:existUser·p0.50      sample          1.821           ms/op
Client.existUser:existUser·p0.90      sample          2.339           ms/op
Client.existUser:existUser·p0.95      sample          2.527           ms/op
Client.existUser:existUser·p0.99      sample          2.957           ms/op
Client.existUser:existUser·p0.999     sample          4.102           ms/op
Client.existUser:existUser·p0.9999    sample          5.645           ms/op
Client.existUser:existUser·p1.00      sample          5.775           ms/op
Client.getUser                        sample   8962   3.569 ± 0.045   ms/op
Client.getUser:getUser·p0.00          sample          1.124           ms/op
Client.getUser:getUser·p0.50          sample          3.445           ms/op
Client.getUser:getUser·p0.90          sample          4.309           ms/op
Client.getUser:getUser·p0.95          sample          4.799           ms/op
Client.getUser:getUser·p0.99          sample          6.930           ms/op
Client.getUser:getUser·p0.999         sample         16.614           ms/op
Client.getUser:getUser·p0.9999        sample         17.859           ms/op
Client.getUser:getUser·p1.00          sample         17.859           ms/op
Client.listUser                       sample   3489   9.316 ± 0.157   ms/op
Client.listUser:listUser·p0.00        sample          2.548           ms/op
Client.listUser:listUser·p0.50        sample          8.929           ms/op
Client.listUser:listUser·p0.90        sample         12.501           ms/op
Client.listUser:listUser·p0.95        sample         13.722           ms/op
Client.listUser:listUser·p0.99        sample         19.566           ms/op
Client.listUser:listUser·p0.999       sample         26.144           ms/op
Client.listUser:listUser·p0.9999      sample         28.803           ms/op
Client.listUser:listUser·p1.00        sample         28.803           ms/op
