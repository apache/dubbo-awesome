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
# Warmup Iteration   1: 2.349 ops/ms
Iteration   1: 6.205 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.205 ops/ms


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
# Warmup Iteration   1: 6.051 ops/ms
Iteration   1: 13.418 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.418 ops/ms


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
# Warmup Iteration   1: 4.223 ops/ms
Iteration   1: 9.219 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.219 ops/ms


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
# Warmup Iteration   1: 2.418 ops/ms
Iteration   1: 3.456 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.456 ops/ms


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
# Warmup Iteration   1: 5.407 ±(99.9%) 0.077 ms/op
Iteration   1: 3.267 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.267 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.033 ms/op
Iteration   1: 1.900 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.900 ms/op


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
# Warmup Iteration   1: 4.198 ±(99.9%) 0.052 ms/op
Iteration   1: 3.153 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.153 ms/op


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
# Warmup Iteration   1: 12.914 ±(99.9%) 0.186 ms/op
Iteration   1: 8.669 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.669 ms/op


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
# Warmup Iteration   1: 5.058 ±(99.9%) 0.120 ms/op
Iteration   1: 3.114 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   2.851 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   8.143 ms/op
                 createUser·p0.999:  19.988 ms/op
                 createUser·p0.9999: 21.353 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10501
  mean =      3.114 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2366 
    [ 2.500,  5.000) = 7860 
    [ 5.000,  7.500) = 124 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     21.353 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.079 ms/op
Iteration   1: 1.906 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  7.112 ms/op
                 existUser·p0.9999: 7.248 ms/op
                 existUser·p1.00:   7.348 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16790
  mean =      1.906 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 24 
    [1.000, 1.500) = 1819 
    [1.500, 2.000) = 9545 
    [2.000, 2.500) = 4232 
    [2.500, 3.000) = 705 
    [3.000, 3.500) = 215 
    [3.500, 4.000) = 70 
    [4.000, 4.500) = 70 
    [4.500, 5.000) = 19 
    [5.000, 5.500) = 3 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 45 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      4.039 ms/op
     p(99.9000) =      7.112 ms/op
     p(99.9900) =      7.248 ms/op
     p(99.9990) =      7.348 ms/op
     p(99.9999) =      7.348 ms/op
    p(100.0000) =      7.348 ms/op


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
# Warmup Iteration   1: 4.554 ±(99.9%) 0.098 ms/op
Iteration   1: 2.813 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.501 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.814 ms/op
                 getUser·p0.99:   5.615 ms/op
                 getUser·p0.999:  16.581 ms/op
                 getUser·p0.9999: 21.857 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11356
  mean =      2.813 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4553 
    [ 2.500,  5.000) = 6583 
    [ 5.000,  7.500) = 154 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.814 ms/op
     p(99.0000) =      5.615 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     21.857 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 11.766 ±(99.9%) 0.374 ms/op
Iteration   1: 9.190 ±(99.9%) 0.155 ms/op
                 listUser·p0.00:   3.203 ms/op
                 listUser·p0.50:   8.684 ms/op
                 listUser·p0.90:   12.298 ms/op
                 listUser·p0.95:   13.882 ms/op
                 listUser·p0.99:   20.357 ms/op
                 listUser·p0.999:  25.832 ms/op
                 listUser·p0.9999: 28.049 ms/op
                 listUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3473
  mean =      9.190 ±(99.9%) 0.155 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 51 
    [ 5.000,  7.500) = 901 
    [ 7.500, 10.000) = 1486 
    [10.000, 12.500) = 711 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      3.203 ms/op
     p(50.0000) =      8.684 ms/op
     p(90.0000) =     12.298 ms/op
     p(95.0000) =     13.882 ms/op
     p(99.0000) =     20.357 ms/op
     p(99.9000) =     25.832 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.205          ops/ms
Client.existUser                       thrpt         13.418          ops/ms
Client.getUser                         thrpt          9.219          ops/ms
Client.listUser                        thrpt          3.456          ops/ms
Client.createUser                       avgt          3.267           ms/op
Client.existUser                        avgt          1.900           ms/op
Client.getUser                          avgt          3.153           ms/op
Client.listUser                         avgt          8.669           ms/op
Client.createUser                     sample  10501   3.114 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          0.755           ms/op
Client.createUser:createUser·p0.50    sample          2.851           ms/op
Client.createUser:createUser·p0.90    sample          3.965           ms/op
Client.createUser:createUser·p0.95    sample          4.358           ms/op
Client.createUser:createUser·p0.99    sample          8.143           ms/op
Client.createUser:createUser·p0.999   sample         19.988           ms/op
Client.createUser:createUser·p0.9999  sample         21.353           ms/op
Client.createUser:createUser·p1.00    sample         21.398           ms/op
Client.existUser                      sample  16790   1.906 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.622           ms/op
Client.existUser:existUser·p0.50      sample          1.772           ms/op
Client.existUser:existUser·p0.90      sample          2.388           ms/op
Client.existUser:existUser·p0.95      sample          2.621           ms/op
Client.existUser:existUser·p0.99      sample          4.039           ms/op
Client.existUser:existUser·p0.999     sample          7.112           ms/op
Client.existUser:existUser·p0.9999    sample          7.248           ms/op
Client.existUser:existUser·p1.00      sample          7.348           ms/op
Client.getUser                        sample  11356   2.813 ± 0.037   ms/op
Client.getUser:getUser·p0.00          sample          0.501           ms/op
Client.getUser:getUser·p0.50          sample          2.593           ms/op
Client.getUser:getUser·p0.90          sample          3.473           ms/op
Client.getUser:getUser·p0.95          sample          3.814           ms/op
Client.getUser:getUser·p0.99          sample          5.615           ms/op
Client.getUser:getUser·p0.999         sample         16.581           ms/op
Client.getUser:getUser·p0.9999        sample         21.857           ms/op
Client.getUser:getUser·p1.00          sample         22.053           ms/op
Client.listUser                       sample   3473   9.190 ± 0.155   ms/op
Client.listUser:listUser·p0.00        sample          3.203           ms/op
Client.listUser:listUser·p0.50        sample          8.684           ms/op
Client.listUser:listUser·p0.90        sample         12.298           ms/op
Client.listUser:listUser·p0.95        sample         13.882           ms/op
Client.listUser:listUser·p0.99        sample         20.357           ms/op
Client.listUser:listUser·p0.999       sample         25.832           ms/op
Client.listUser:listUser·p0.9999      sample         28.049           ms/op
Client.listUser:listUser·p1.00        sample         28.049           ms/op
