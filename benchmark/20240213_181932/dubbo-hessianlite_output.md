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
# Warmup Iteration   1: 2.317 ops/ms
Iteration   1: 6.162 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.162 ops/ms


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
# Warmup Iteration   1: 6.139 ops/ms
Iteration   1: 13.507 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.507 ops/ms


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
# Warmup Iteration   1: 4.244 ops/ms
Iteration   1: 8.269 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.269 ops/ms


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
# Warmup Iteration   1: 2.194 ops/ms
Iteration   1: 3.545 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.545 ops/ms


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
# Warmup Iteration   1: 5.623 ±(99.9%) 0.074 ms/op
Iteration   1: 3.051 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.051 ms/op


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.043 ms/op
Iteration   1: 2.027 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.027 ms/op


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
# Warmup Iteration   1: 4.711 ±(99.9%) 0.058 ms/op
Iteration   1: 2.891 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.891 ms/op


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
# Warmup Iteration   1: 12.182 ±(99.9%) 0.188 ms/op
Iteration   1: 8.670 ±(99.9%) 0.178 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.670 ms/op


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
# Warmup Iteration   1: 5.570 ±(99.9%) 0.160 ms/op
Iteration   1: 3.096 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.875 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.400 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  11.305 ms/op
                 createUser·p0.9999: 11.387 ms/op
                 createUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10476
  mean =      3.096 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1373 
    [ 2.500,  3.750) = 7916 
    [ 3.750,  5.000) = 899 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.400 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     11.305 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     11.387 ms/op
     p(99.9999) =     11.387 ms/op
    p(100.0000) =     11.387 ms/op


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
# Warmup Iteration   1: 3.419 ±(99.9%) 0.089 ms/op
Iteration   1: 2.037 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   1.851 ms/op
                 existUser·p0.90:   2.679 ms/op
                 existUser·p0.95:   2.937 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  5.882 ms/op
                 existUser·p0.9999: 7.051 ms/op
                 existUser·p1.00:   8.012 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15691
  mean =      2.037 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 66 
    [1.000, 1.500) = 883 
    [1.500, 2.000) = 8325 
    [2.000, 2.500) = 3673 
    [2.500, 3.000) = 1996 
    [3.000, 3.500) = 311 
    [3.500, 4.000) = 246 
    [4.000, 4.500) = 101 
    [4.500, 5.000) = 17 
    [5.000, 5.500) = 38 
    [5.500, 6.000) = 32 
    [6.000, 6.500) = 2 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      5.882 ms/op
     p(99.9900) =      7.051 ms/op
     p(99.9990) =      8.012 ms/op
     p(99.9999) =      8.012 ms/op
    p(100.0000) =      8.012 ms/op


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.096 ms/op
Iteration   1: 2.915 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.474 ms/op
                 getUser·p0.50:   2.740 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  8.487 ms/op
                 getUser·p0.9999: 12.109 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10949
  mean =      2.915 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 3809 
    [ 2.500,  3.750) = 5552 
    [ 3.750,  5.000) = 1361 
    [ 5.000,  6.250) = 138 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     12.109 ms/op
     p(99.9990) =     12.141 ms/op
     p(99.9999) =     12.141 ms/op
    p(100.0000) =     12.141 ms/op


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
# Warmup Iteration   1: 12.630 ±(99.9%) 0.459 ms/op
Iteration   1: 9.210 ±(99.9%) 0.156 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   8.765 ms/op
                 listUser·p0.90:   12.534 ms/op
                 listUser·p0.95:   14.158 ms/op
                 listUser·p0.99:   20.245 ms/op
                 listUser·p0.999:  24.187 ms/op
                 listUser·p0.9999: 27.886 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3458
  mean =      9.210 ±(99.9%) 0.156 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 55 
    [ 5.000,  7.500) = 932 
    [ 7.500, 10.000) = 1406 
    [10.000, 12.500) = 711 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.142 ms/op
     p(50.0000) =      8.765 ms/op
     p(90.0000) =     12.534 ms/op
     p(95.0000) =     14.158 ms/op
     p(99.0000) =     20.245 ms/op
     p(99.9000) =     24.187 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.162          ops/ms
Client.existUser                       thrpt         13.507          ops/ms
Client.getUser                         thrpt          8.269          ops/ms
Client.listUser                        thrpt          3.545          ops/ms
Client.createUser                       avgt          3.051           ms/op
Client.existUser                        avgt          2.027           ms/op
Client.getUser                          avgt          2.891           ms/op
Client.listUser                         avgt          8.670           ms/op
Client.createUser                     sample  10476   3.096 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          0.874           ms/op
Client.createUser:createUser·p0.50    sample          2.875           ms/op
Client.createUser:createUser·p0.90    sample          3.871           ms/op
Client.createUser:createUser·p0.95    sample          4.400           ms/op
Client.createUser:createUser·p0.99    sample          8.536           ms/op
Client.createUser:createUser·p0.999   sample         11.305           ms/op
Client.createUser:createUser·p0.9999  sample         11.387           ms/op
Client.createUser:createUser·p1.00    sample         11.387           ms/op
Client.existUser                      sample  15691   2.037 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.592           ms/op
Client.existUser:existUser·p0.50      sample          1.851           ms/op
Client.existUser:existUser·p0.90      sample          2.679           ms/op
Client.existUser:existUser·p0.95      sample          2.937           ms/op
Client.existUser:existUser·p0.99      sample          4.108           ms/op
Client.existUser:existUser·p0.999     sample          5.882           ms/op
Client.existUser:existUser·p0.9999    sample          7.051           ms/op
Client.existUser:existUser·p1.00      sample          8.012           ms/op
Client.getUser                        sample  10949   2.915 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.474           ms/op
Client.getUser:getUser·p0.50          sample          2.740           ms/op
Client.getUser:getUser·p0.90          sample          3.920           ms/op
Client.getUser:getUser·p0.95          sample          4.243           ms/op
Client.getUser:getUser·p0.99          sample          5.825           ms/op
Client.getUser:getUser·p0.999         sample          8.487           ms/op
Client.getUser:getUser·p0.9999        sample         12.109           ms/op
Client.getUser:getUser·p1.00          sample         12.141           ms/op
Client.listUser                       sample   3458   9.210 ± 0.156   ms/op
Client.listUser:listUser·p0.00        sample          2.142           ms/op
Client.listUser:listUser·p0.50        sample          8.765           ms/op
Client.listUser:listUser·p0.90        sample         12.534           ms/op
Client.listUser:listUser·p0.95        sample         14.158           ms/op
Client.listUser:listUser·p0.99        sample         20.245           ms/op
Client.listUser:listUser·p0.999       sample         24.187           ms/op
Client.listUser:listUser·p0.9999      sample         27.886           ms/op
Client.listUser:listUser·p1.00        sample         27.886           ms/op
