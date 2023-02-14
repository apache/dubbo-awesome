# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.166 ops/ms
# Warmup Iteration   2: 9.444 ops/ms
# Warmup Iteration   3: 10.203 ops/ms
Iteration   1: 10.395 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.351 ±(99.9%) 4.217 ops/ms [Average]
  (min, avg, max) = (10.101, 10.351, 10.557), stdev = 0.231
  CI (99.9%): [6.134, 14.568] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.232 ops/ms
# Warmup Iteration   2: 10.860 ops/ms
# Warmup Iteration   3: 10.846 ops/ms
Iteration   1: 11.182 ops/ms
Iteration   2: 10.954 ops/ms
Iteration   3: 10.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.967 ±(99.9%) 3.806 ops/ms [Average]
  (min, avg, max) = (10.765, 10.967, 11.182), stdev = 0.209
  CI (99.9%): [7.161, 14.774] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.169 ops/ms
# Warmup Iteration   2: 10.535 ops/ms
# Warmup Iteration   3: 10.369 ops/ms
Iteration   1: 10.352 ops/ms
Iteration   2: 10.379 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.428 ±(99.9%) 2.004 ops/ms [Average]
  (min, avg, max) = (10.352, 10.428, 10.554), stdev = 0.110
  CI (99.9%): [8.424, 12.432] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.735 ops/ms
# Warmup Iteration   2: 8.101 ops/ms
# Warmup Iteration   3: 8.113 ops/ms
Iteration   1: 8.097 ops/ms
Iteration   2: 8.191 ops/ms
Iteration   3: 8.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.214 ±(99.9%) 2.357 ops/ms [Average]
  (min, avg, max) = (8.097, 8.214, 8.353), stdev = 0.129
  CI (99.9%): [5.857, 10.571] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.003 ms/op
Iteration   1: 3.062 ±(99.9%) 0.003 ms/op
Iteration   2: 3.050 ±(99.9%) 0.002 ms/op
Iteration   3: 3.075 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.063 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (3.050, 3.063, 3.075), stdev = 0.013
  CI (99.9%): [2.829, 3.296] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.466 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.002 ms/op
Iteration   1: 2.986 ±(99.9%) 0.002 ms/op
Iteration   2: 2.977 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.980 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.977, 2.980, 2.986), stdev = 0.005
  CI (99.9%): [2.895, 3.066] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.825 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.002 ms/op
Iteration   1: 3.054 ±(99.9%) 0.003 ms/op
Iteration   2: 3.121 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.068 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.031, 3.068, 3.121), stdev = 0.047
  CI (99.9%): [2.213, 3.924] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.253 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.016 ms/op
Iteration   1: 4.040 ±(99.9%) 0.011 ms/op
Iteration   2: 3.805 ±(99.9%) 0.018 ms/op
Iteration   3: 3.922 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 2.137 ms/op [Average]
  (min, avg, max) = (3.805, 3.922, 4.040), stdev = 0.117
  CI (99.9%): [1.786, 6.059] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.025 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.118 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  9.969 ms/op
                 createUser·p0.9999: 14.355 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   2: 3.148 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  5.962 ms/op
                 createUser·p0.9999: 13.072 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   3: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  11.141 ms/op
                 createUser·p0.9999: 23.069 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304510
  mean =      3.152 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23299 
    [ 2.500,  5.000) = 280073 
    [ 5.000,  7.500) = 661 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =     10.264 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.705 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.006 ms/op
Iteration   1: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  5.704 ms/op
                 existUser·p0.9999: 11.406 ms/op
                 existUser·p1.00:   11.895 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  8.087 ms/op
                 existUser·p0.9999: 15.843 ms/op
                 existUser·p1.00:   16.056 ms/op

Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.469 ms/op
                 existUser·p0.9999: 16.024 ms/op
                 existUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322220
  mean =      2.978 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2353 
    [ 1.250,  2.500) = 42060 
    [ 2.500,  3.750) = 255565 
    [ 3.750,  5.000) = 21559 
    [ 5.000,  6.250) = 344 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 63 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.452 ms/op
     p(99.9900) =     15.450 ms/op
     p(99.9990) =     16.253 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.809 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.440 ms/op
                 getUser·p0.9999: 12.198 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.468 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.039 ms/op
                 getUser·p0.9999: 13.613 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   3: 3.043 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  7.027 ms/op
                 getUser·p0.9999: 15.294 ms/op
                 getUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315722
  mean =      3.039 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1393 
    [ 1.250,  2.500) = 26115 
    [ 2.500,  3.750) = 267617 
    [ 3.750,  5.000) = 19761 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 246 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     14.858 ms/op
     p(99.9990) =     15.538 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.922 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.011 ms/op
Iteration   1: 3.839 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  11.458 ms/op
                 listUser·p0.9999: 16.024 ms/op
                 listUser·p1.00:   16.417 ms/op

Iteration   2: 3.923 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 27.023 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   3: 4.087 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  13.792 ms/op
                 listUser·p0.9999: 17.410 ms/op
                 listUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243406
  mean =      3.947 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3201 
    [ 2.500,  5.000) = 212024 
    [ 5.000,  7.500) = 27165 
    [ 7.500, 10.000) = 605 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.356 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     27.150 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.351 ± 4.217  ops/ms
ClientGrpc.existUser                       thrpt       3  10.967 ± 3.806  ops/ms
ClientGrpc.getUser                         thrpt       3  10.428 ± 2.004  ops/ms
ClientGrpc.listUser                        thrpt       3   8.214 ± 2.357  ops/ms
ClientGrpc.createUser                       avgt       3   3.063 ± 0.233   ms/op
ClientGrpc.existUser                        avgt       3   2.980 ± 0.086   ms/op
ClientGrpc.getUser                          avgt       3   3.068 ± 0.856   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 2.137   ms/op
ClientGrpc.createUser                     sample  304510   3.152 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.527           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.264           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.348           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.200           ms/op
ClientGrpc.existUser                      sample  322220   2.978 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.729           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.452           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.450           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.269           ms/op
ClientGrpc.getUser                        sample  315722   3.039 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.468           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.816           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.858           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.679           ms/op
ClientGrpc.listUser                       sample  243406   3.947 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.896           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.356           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.133           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
