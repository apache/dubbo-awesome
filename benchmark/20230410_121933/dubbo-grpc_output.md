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
# Warmup Iteration   1: 4.301 ops/ms
# Warmup Iteration   2: 8.858 ops/ms
# Warmup Iteration   3: 10.098 ops/ms
Iteration   1: 10.378 ops/ms
Iteration   2: 10.622 ops/ms
Iteration   3: 10.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.477 ±(99.9%) 2.343 ops/ms [Average]
  (min, avg, max) = (10.378, 10.477, 10.622), stdev = 0.128
  CI (99.9%): [8.134, 12.820] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.284 ops/ms
# Warmup Iteration   2: 10.539 ops/ms
# Warmup Iteration   3: 10.883 ops/ms
Iteration   1: 10.833 ops/ms
Iteration   2: 11.104 ops/ms
Iteration   3: 11.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.025 ±(99.9%) 3.051 ops/ms [Average]
  (min, avg, max) = (10.833, 11.025, 11.138), stdev = 0.167
  CI (99.9%): [7.974, 14.076] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.809 ops/ms
# Warmup Iteration   2: 9.995 ops/ms
# Warmup Iteration   3: 10.401 ops/ms
Iteration   1: 10.531 ops/ms
Iteration   2: 10.479 ops/ms
Iteration   3: 10.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.525 ±(99.9%) 0.787 ops/ms [Average]
  (min, avg, max) = (10.479, 10.525, 10.564), stdev = 0.043
  CI (99.9%): [9.738, 11.311] (assumes normal distribution)


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
# Warmup Iteration   1: 5.295 ops/ms
# Warmup Iteration   2: 7.680 ops/ms
# Warmup Iteration   3: 7.914 ops/ms
Iteration   1: 8.058 ops/ms
Iteration   2: 8.162 ops/ms
Iteration   3: 8.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.105 ±(99.9%) 0.958 ops/ms [Average]
  (min, avg, max) = (8.058, 8.105, 8.162), stdev = 0.052
  CI (99.9%): [7.148, 9.063] (assumes normal distribution)


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
# Warmup Iteration   1: 4.130 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.003 ms/op
Iteration   1: 3.138 ±(99.9%) 0.003 ms/op
Iteration   2: 3.109 ±(99.9%) 0.002 ms/op
Iteration   3: 3.052 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.100 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.052, 3.100, 3.138), stdev = 0.043
  CI (99.9%): [2.307, 3.893] (assumes normal distribution)


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.002 ms/op
Iteration   1: 2.892 ±(99.9%) 0.004 ms/op
Iteration   2: 2.908 ±(99.9%) 0.003 ms/op
Iteration   3: 2.927 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.909 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.892, 2.909, 2.927), stdev = 0.017
  CI (99.9%): [2.590, 3.228] (assumes normal distribution)


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.002 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
Iteration   3: 3.069 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.070 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (3.045, 3.070, 3.095), stdev = 0.025
  CI (99.9%): [2.620, 3.520] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.622 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.034 ms/op
Iteration   1: 3.996 ±(99.9%) 0.015 ms/op
Iteration   2: 4.020 ±(99.9%) 0.020 ms/op
Iteration   3: 3.957 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.991 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (3.957, 3.991, 4.020), stdev = 0.032
  CI (99.9%): [3.411, 4.571] (assumes normal distribution)


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
# Warmup Iteration   1: 4.290 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  7.692 ms/op
                 createUser·p0.9999: 15.135 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 3.178 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.108 ms/op
                 createUser·p0.9999: 15.415 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  10.385 ms/op
                 createUser·p0.9999: 16.717 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309551
  mean =      3.099 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 386 
    [ 1.250,  2.500) = 13714 
    [ 2.500,  3.750) = 276622 
    [ 3.750,  5.000) = 17030 
    [ 5.000,  6.250) = 983 
    [ 6.250,  7.500) = 352 
    [ 7.500,  8.750) = 123 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 76 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.493 ms/op
     p(99.9000) =      9.658 ms/op
     p(99.9900) =     16.253 ms/op
     p(99.9990) =     17.003 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.927 ±(99.9%) 0.006 ms/op
Iteration   1: 2.935 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  5.932 ms/op
                 existUser·p0.9999: 12.257 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.600 ms/op
                 existUser·p0.9999: 13.176 ms/op
                 existUser·p1.00:   15.827 ms/op

Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.372 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.439 ms/op
                 existUser·p0.999:  7.009 ms/op
                 existUser·p0.9999: 17.451 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324410
  mean =      2.960 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 759 
    [ 1.250,  2.500) = 26672 
    [ 2.500,  3.750) = 284577 
    [ 3.750,  5.000) = 11108 
    [ 5.000,  6.250) = 756 
    [ 6.250,  7.500) = 246 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.288 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.090 ms/op
                 getUser·p0.9999: 17.875 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   2: 3.017 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.927 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  7.510 ms/op
                 getUser·p0.9999: 19.000 ms/op
                 getUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314968
  mean =      3.047 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14873 
    [ 2.500,  5.000) = 298670 
    [ 5.000,  7.500) = 1162 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     18.137 ms/op
     p(99.9990) =     19.459 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 5.551 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.011 ms/op
Iteration   1: 3.894 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.221 ms/op
                 listUser·p0.9999: 26.563 ms/op
                 listUser·p1.00:   27.689 ms/op

Iteration   2: 3.990 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  14.020 ms/op
                 listUser·p0.9999: 16.695 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   3: 3.918 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.189 ms/op
                 listUser·p0.9999: 21.829 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244194
  mean =      3.934 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2648 
    [ 2.500,  5.000) = 220299 
    [ 5.000,  7.500) = 19939 
    [ 7.500, 10.000) = 907 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.044 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     27.547 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.477 ± 2.343  ops/ms
ClientGrpc.existUser                       thrpt       3  11.025 ± 3.051  ops/ms
ClientGrpc.getUser                         thrpt       3  10.525 ± 0.787  ops/ms
ClientGrpc.listUser                        thrpt       3   8.105 ± 0.958  ops/ms
ClientGrpc.createUser                       avgt       3   3.100 ± 0.793   ms/op
ClientGrpc.existUser                        avgt       3   2.909 ± 0.319   ms/op
ClientGrpc.getUser                          avgt       3   3.070 ± 0.450   ms/op
ClientGrpc.listUser                         avgt       3   3.991 ± 0.580   ms/op
ClientGrpc.createUser                     sample  309551   3.099 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.723           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.493           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.658           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.253           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.138           ms/op
ClientGrpc.existUser                      sample  324410   2.960 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.372           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.288           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.039           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.629           ms/op
ClientGrpc.getUser                        sample  314968   3.047 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.590           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.152           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.137           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.349           ms/op
ClientGrpc.listUser                       sample  244194   3.934 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.760           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.044           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.199           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.689           ms/op
