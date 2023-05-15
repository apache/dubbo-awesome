# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.260 ops/ms
# Warmup Iteration   2: 9.209 ops/ms
# Warmup Iteration   3: 10.318 ops/ms
Iteration   1: 10.593 ops/ms
Iteration   2: 10.612 ops/ms
Iteration   3: 10.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.640 ±(99.9%) 1.196 ops/ms [Average]
  (min, avg, max) = (10.593, 10.640, 10.715), stdev = 0.066
  CI (99.9%): [9.444, 11.836] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.127 ops/ms
# Warmup Iteration   2: 10.790 ops/ms
# Warmup Iteration   3: 11.754 ops/ms
Iteration   1: 11.205 ops/ms
Iteration   2: 11.178 ops/ms
Iteration   3: 11.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.283 ±(99.9%) 2.904 ops/ms [Average]
  (min, avg, max) = (11.178, 11.283, 11.466), stdev = 0.159
  CI (99.9%): [8.379, 14.187] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.684 ops/ms
# Warmup Iteration   2: 10.240 ops/ms
# Warmup Iteration   3: 10.465 ops/ms
Iteration   1: 10.541 ops/ms
Iteration   2: 10.619 ops/ms
Iteration   3: 10.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.654 ±(99.9%) 2.456 ops/ms [Average]
  (min, avg, max) = (10.541, 10.654, 10.803), stdev = 0.135
  CI (99.9%): [8.198, 13.111] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.556 ops/ms
# Warmup Iteration   2: 7.930 ops/ms
# Warmup Iteration   3: 8.302 ops/ms
Iteration   1: 8.180 ops/ms
Iteration   2: 8.401 ops/ms
Iteration   3: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.247 ±(99.9%) 2.438 ops/ms [Average]
  (min, avg, max) = (8.161, 8.247, 8.401), stdev = 0.134
  CI (99.9%): [5.810, 10.685] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.285 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.003 ms/op
Iteration   1: 2.997 ±(99.9%) 0.001 ms/op
Iteration   2: 2.977 ±(99.9%) 0.002 ms/op
Iteration   3: 2.986 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.987 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.977, 2.987, 2.997), stdev = 0.010
  CI (99.9%): [2.803, 3.170] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.099 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.002 ms/op
Iteration   1: 2.847 ±(99.9%) 0.002 ms/op
Iteration   2: 2.988 ±(99.9%) 0.002 ms/op
Iteration   3: 2.877 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.904 ±(99.9%) 1.354 ms/op [Average]
  (min, avg, max) = (2.847, 2.904, 2.988), stdev = 0.074
  CI (99.9%): [1.550, 4.258] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.257 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.004 ms/op
Iteration   1: 3.033 ±(99.9%) 0.003 ms/op
Iteration   2: 2.953 ±(99.9%) 0.004 ms/op
Iteration   3: 2.983 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.990 ±(99.9%) 0.743 ms/op [Average]
  (min, avg, max) = (2.953, 2.990, 3.033), stdev = 0.041
  CI (99.9%): [2.247, 3.732] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.290 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.023 ms/op
Iteration   1: 3.879 ±(99.9%) 0.014 ms/op
Iteration   2: 3.890 ±(99.9%) 0.008 ms/op
Iteration   3: 3.881 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.883 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (3.879, 3.883, 3.890), stdev = 0.006
  CI (99.9%): [3.778, 3.988] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.113 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.176 ms/op
                 createUser·p0.9999: 19.051 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  7.643 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   3: 2.964 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.467 ms/op
                 createUser·p0.999:  11.191 ms/op
                 createUser·p0.9999: 22.322 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320455
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30455 
    [ 2.500,  5.000) = 288699 
    [ 5.000,  7.500) = 941 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     20.511 ms/op
     p(99.9990) =     22.669 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.147 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.920 ±(99.9%) 0.006 ms/op
Iteration   1: 2.931 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.600 ms/op
                 existUser·p0.9999: 12.257 ms/op
                 existUser·p1.00:   12.419 ms/op

Iteration   2: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  5.128 ms/op
                 existUser·p0.9999: 17.302 ms/op
                 existUser·p1.00:   17.760 ms/op

Iteration   3: 2.882 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.061 ms/op
                 existUser·p0.999:  7.218 ms/op
                 existUser·p0.9999: 17.629 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331838
  mean =      2.892 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1395 
    [ 1.250,  2.500) = 38803 
    [ 2.500,  3.750) = 283497 
    [ 3.750,  5.000) = 7328 
    [ 5.000,  6.250) = 441 
    [ 6.250,  7.500) = 149 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 62 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      6.455 ms/op
     p(99.9900) =     17.394 ms/op
     p(99.9990) =     17.717 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.937 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
Iteration   1: 2.978 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.523 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.544 ms/op
                 getUser·p0.9999: 14.135 ms/op
                 getUser·p1.00:   16.531 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.194 ms/op
                 getUser·p0.9999: 22.226 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.959 ms/op
                 getUser·p0.9999: 17.003 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316623
  mean =      3.033 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20380 
    [ 2.500,  5.000) = 294908 
    [ 5.000,  7.500) = 1060 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.196 ms/op
     p(99.9900) =     21.507 ms/op
     p(99.9990) =     22.408 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.430 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.010 ms/op
Iteration   1: 3.918 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.918 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.389 ms/op
                 listUser·p0.9999: 17.787 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 3.887 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.513 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.826 ms/op
                 listUser·p0.9999: 17.720 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.920 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 27.220 ms/op
                 listUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245658
  mean =      3.908 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3505 
    [ 2.500,  5.000) = 223137 
    [ 5.000,  7.500) = 17971 
    [ 7.500, 10.000) = 563 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     15.095 ms/op
     p(99.9900) =     23.097 ms/op
     p(99.9990) =     27.531 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.640 ± 1.196  ops/ms
ClientGrpc.existUser                       thrpt       3  11.283 ± 2.904  ops/ms
ClientGrpc.getUser                         thrpt       3  10.654 ± 2.456  ops/ms
ClientGrpc.listUser                        thrpt       3   8.247 ± 2.438  ops/ms
ClientGrpc.createUser                       avgt       3   2.987 ± 0.183   ms/op
ClientGrpc.existUser                        avgt       3   2.904 ± 1.354   ms/op
ClientGrpc.getUser                          avgt       3   2.990 ± 0.743   ms/op
ClientGrpc.listUser                         avgt       3   3.883 ± 0.105   ms/op
ClientGrpc.createUser                     sample  320455   2.995 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.624           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.758           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.511           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.741           ms/op
ClientGrpc.existUser                      sample  331838   2.892 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.582           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.455           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.394           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.760           ms/op
ClientGrpc.getUser                        sample  316623   3.033 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.868           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.196           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.507           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.479           ms/op
ClientGrpc.listUser                       sample  245658   3.908 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.513           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.694           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.095           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.097           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.656           ms/op
