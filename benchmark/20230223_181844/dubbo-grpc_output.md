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
# Warmup Iteration   1: 4.052 ops/ms
# Warmup Iteration   2: 8.822 ops/ms
# Warmup Iteration   3: 9.729 ops/ms
Iteration   1: 10.209 ops/ms
Iteration   2: 10.005 ops/ms
Iteration   3: 10.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.082 ±(99.9%) 2.022 ops/ms [Average]
  (min, avg, max) = (10.005, 10.082, 10.209), stdev = 0.111
  CI (99.9%): [8.060, 12.104] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.652 ops/ms
# Warmup Iteration   2: 10.461 ops/ms
# Warmup Iteration   3: 10.349 ops/ms
Iteration   1: 10.441 ops/ms
Iteration   2: 10.830 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.576 ±(99.9%) 4.008 ops/ms [Average]
  (min, avg, max) = (10.441, 10.576, 10.830), stdev = 0.220
  CI (99.9%): [6.568, 14.584] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.667 ops/ms
# Warmup Iteration   2: 10.025 ops/ms
# Warmup Iteration   3: 10.026 ops/ms
Iteration   1: 9.968 ops/ms
Iteration   2: 9.989 ops/ms
Iteration   3: 10.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.118 ±(99.9%) 4.426 ops/ms [Average]
  (min, avg, max) = (9.968, 10.118, 10.398), stdev = 0.243
  CI (99.9%): [5.693, 14.544] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.557 ops/ms
# Warmup Iteration   2: 7.664 ops/ms
# Warmup Iteration   3: 8.113 ops/ms
Iteration   1: 8.204 ops/ms
Iteration   2: 7.762 ops/ms
Iteration   3: 7.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.966 ±(99.9%) 4.063 ops/ms [Average]
  (min, avg, max) = (7.762, 7.966, 8.204), stdev = 0.223
  CI (99.9%): [3.903, 12.030] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.212 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.002 ms/op
Iteration   1: 3.248 ±(99.9%) 0.003 ms/op
Iteration   2: 3.110 ±(99.9%) 0.003 ms/op
Iteration   3: 3.175 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.178 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.110, 3.178, 3.248), stdev = 0.069
  CI (99.9%): [1.913, 4.443] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.070 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.002 ms/op
Iteration   1: 2.930 ±(99.9%) 0.002 ms/op
Iteration   2: 3.050 ±(99.9%) 0.003 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.997 ±(99.9%) 1.120 ms/op [Average]
  (min, avg, max) = (2.930, 2.997, 3.050), stdev = 0.061
  CI (99.9%): [1.877, 4.117] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.227 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.003 ms/op
Iteration   1: 3.156 ±(99.9%) 0.002 ms/op
Iteration   2: 3.147 ±(99.9%) 0.002 ms/op
Iteration   3: 3.206 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.169 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.147, 3.169, 3.206), stdev = 0.032
  CI (99.9%): [2.591, 3.748] (assumes normal distribution)


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.273 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.015 ms/op
Iteration   1: 4.010 ±(99.9%) 0.009 ms/op
Iteration   2: 3.963 ±(99.9%) 0.018 ms/op
Iteration   3: 3.963 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.979 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.963, 3.979, 4.010), stdev = 0.028
  CI (99.9%): [3.476, 4.481] (assumes normal distribution)


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
Iteration   1: 3.159 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.077 ms/op
                 createUser·p0.9999: 19.291 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.966 ms/op
                 createUser·p0.9999: 26.995 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.227 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  10.905 ms/op
                 createUser·p0.9999: 24.513 ms/op
                 createUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301445
  mean =      3.185 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20980 
    [ 2.500,  5.000) = 279338 
    [ 5.000,  7.500) = 646 
    [ 7.500, 10.000) = 190 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.652 ms/op
     p(99.9900) =     25.325 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.007 ms/op
Iteration   1: 3.000 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.349 ms/op
                 existUser·p0.9999: 13.730 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.406 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  8.010 ms/op
                 existUser·p0.9999: 17.974 ms/op
                 existUser·p1.00:   18.416 ms/op

Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.924 ms/op
                 existUser·p0.9999: 17.793 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314366
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1589 
    [ 1.250,  2.500) = 34514 
    [ 2.500,  3.750) = 248650 
    [ 3.750,  5.000) = 28756 
    [ 5.000,  6.250) = 413 
    [ 6.250,  7.500) = 177 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.006 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     18.308 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.007 ms/op
Iteration   1: 3.233 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  5.538 ms/op
                 getUser·p0.9999: 27.951 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   2: 3.193 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.378 ms/op
                 getUser·p0.9999: 22.282 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  8.224 ms/op
                 getUser·p0.9999: 24.241 ms/op
                 getUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300416
  mean =      3.195 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19401 
    [ 2.500,  5.000) = 280171 
    [ 5.000,  7.500) = 554 
    [ 7.500, 10.000) = 130 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.427 ms/op
     p(99.9900) =     27.554 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 5.898 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.013 ms/op
Iteration   1: 3.972 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  13.052 ms/op
                 listUser·p0.9999: 15.584 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   2: 3.911 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  15.590 ms/op
                 listUser·p0.9999: 29.970 ms/op
                 listUser·p1.00:   30.507 ms/op

Iteration   3: 3.906 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  16.639 ms/op
                 listUser·p0.9999: 25.913 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244489
  mean =      3.929 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2392 
    [ 2.500,  5.000) = 221087 
    [ 5.000,  7.500) = 19915 
    [ 7.500, 10.000) = 698 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     28.166 ms/op
     p(99.9990) =     30.369 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.082 ± 2.022  ops/ms
ClientGrpc.existUser                       thrpt       3  10.576 ± 4.008  ops/ms
ClientGrpc.getUser                         thrpt       3  10.118 ± 4.426  ops/ms
ClientGrpc.listUser                        thrpt       3   7.966 ± 4.063  ops/ms
ClientGrpc.createUser                       avgt       3   3.178 ± 1.265   ms/op
ClientGrpc.existUser                        avgt       3   2.997 ± 1.120   ms/op
ClientGrpc.getUser                          avgt       3   3.169 ± 0.578   ms/op
ClientGrpc.listUser                         avgt       3   3.979 ± 0.502   ms/op
ClientGrpc.createUser                     sample  301445   3.185 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.657           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.652           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.325           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.165           ms/op
ClientGrpc.existUser                      sample  314366   3.054 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.406           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.006           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.760           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.416           ms/op
ClientGrpc.getUser                        sample  300416   3.195 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.676           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.039           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.427           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.554           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.148           ms/op
ClientGrpc.listUser                       sample  244489   3.929 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.826           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.549           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.166           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.507           ms/op
