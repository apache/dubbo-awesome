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
# Warmup Iteration   1: 4.402 ops/ms
# Warmup Iteration   2: 9.002 ops/ms
# Warmup Iteration   3: 10.179 ops/ms
Iteration   1: 10.641 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.523 ±(99.9%) 2.186 ops/ms [Average]
  (min, avg, max) = (10.401, 10.523, 10.641), stdev = 0.120
  CI (99.9%): [8.337, 12.709] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.347 ops/ms
# Warmup Iteration   2: 10.467 ops/ms
# Warmup Iteration   3: 10.685 ops/ms
Iteration   1: 10.933 ops/ms
Iteration   2: 10.625 ops/ms
Iteration   3: 11.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.889 ±(99.9%) 4.466 ops/ms [Average]
  (min, avg, max) = (10.625, 10.889, 11.108), stdev = 0.245
  CI (99.9%): [6.423, 15.354] (assumes normal distribution)


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
# Warmup Iteration   1: 7.424 ops/ms
# Warmup Iteration   2: 10.203 ops/ms
# Warmup Iteration   3: 10.074 ops/ms
Iteration   1: 10.343 ops/ms
Iteration   2: 10.227 ops/ms
Iteration   3: 10.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.322 ±(99.9%) 1.594 ops/ms [Average]
  (min, avg, max) = (10.227, 10.322, 10.398), stdev = 0.087
  CI (99.9%): [8.729, 11.916] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.723 ops/ms
# Warmup Iteration   2: 7.719 ops/ms
# Warmup Iteration   3: 7.861 ops/ms
Iteration   1: 8.316 ops/ms
Iteration   2: 8.252 ops/ms
Iteration   3: 8.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.224 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (8.105, 8.224, 8.316), stdev = 0.108
  CI (99.9%): [6.251, 10.197] (assumes normal distribution)


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.005 ms/op
Iteration   1: 3.029 ±(99.9%) 0.002 ms/op
Iteration   2: 3.130 ±(99.9%) 0.002 ms/op
Iteration   3: 3.087 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.082 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.029, 3.082, 3.130), stdev = 0.051
  CI (99.9%): [2.157, 4.007] (assumes normal distribution)


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.003 ms/op
Iteration   1: 2.934 ±(99.9%) 0.005 ms/op
Iteration   2: 3.007 ±(99.9%) 0.002 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.985 ±(99.9%) 0.806 ms/op [Average]
  (min, avg, max) = (2.934, 2.985, 3.013), stdev = 0.044
  CI (99.9%): [2.178, 3.791] (assumes normal distribution)


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.003 ms/op
Iteration   1: 3.105 ±(99.9%) 0.005 ms/op
Iteration   2: 3.115 ±(99.9%) 0.003 ms/op
Iteration   3: 2.919 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.046 ±(99.9%) 2.014 ms/op [Average]
  (min, avg, max) = (2.919, 3.046, 3.115), stdev = 0.110
  CI (99.9%): [1.032, 5.060] (assumes normal distribution)


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
# Warmup Iteration   1: 4.971 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.011 ms/op
Iteration   1: 3.981 ±(99.9%) 0.020 ms/op
Iteration   2: 3.988 ±(99.9%) 0.009 ms/op
Iteration   3: 3.871 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.947 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.871, 3.947, 3.988), stdev = 0.066
  CI (99.9%): [2.742, 5.151] (assumes normal distribution)


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.472 ms/op
                 createUser·p0.9999: 22.670 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.103 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.273 ms/op
                 createUser·p0.9999: 17.871 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   3: 3.193 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.552 ms/op
                 createUser·p0.9999: 26.017 ms/op
                 createUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304110
  mean =      3.156 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28510 
    [ 2.500,  5.000) = 274538 
    [ 5.000,  7.500) = 717 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.092 ms/op
     p(99.9900) =     24.857 ms/op
     p(99.9990) =     26.376 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 3.607 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
Iteration   1: 2.796 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.245 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  8.228 ms/op
                 existUser·p0.9999: 12.397 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 2.878 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  6.807 ms/op
                 existUser·p0.9999: 14.380 ms/op
                 existUser·p1.00:   15.843 ms/op

Iteration   3: 2.807 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.402 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 16.607 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 339513
  mean =      2.826 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8822 
    [ 1.250,  2.500) = 50213 
    [ 2.500,  3.750) = 268555 
    [ 3.750,  5.000) = 10694 
    [ 5.000,  6.250) = 617 
    [ 6.250,  7.500) = 182 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 123 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.245 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     16.188 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.121 ms/op
                 getUser·p0.9999: 14.767 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   2: 2.997 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.402 ms/op
                 getUser·p0.50:   3.037 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  6.334 ms/op
                 getUser·p0.9999: 28.082 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 2.968 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.244 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.463 ms/op
                 getUser·p0.9999: 18.210 ms/op
                 getUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321395
  mean =      2.987 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32312 
    [ 2.500,  5.000) = 288107 
    [ 5.000,  7.500) = 733 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.244 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.767 ms/op
     p(99.9900) =     27.582 ms/op
     p(99.9990) =     28.232 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.013 ms/op
Iteration   1: 4.048 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  12.894 ms/op
                 listUser·p0.9999: 15.514 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   2: 4.058 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 23.560 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 3.917 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.378 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.456 ms/op
                 listUser·p0.9999: 21.447 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239459
  mean =      4.006 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3882 
    [ 2.500,  5.000) = 203383 
    [ 5.000,  7.500) = 30864 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     22.710 ms/op
     p(99.9990) =     24.013 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.523 ± 2.186  ops/ms
ClientGrpc.existUser                       thrpt       3  10.889 ± 4.466  ops/ms
ClientGrpc.getUser                         thrpt       3  10.322 ± 1.594  ops/ms
ClientGrpc.listUser                        thrpt       3   8.224 ± 1.973  ops/ms
ClientGrpc.createUser                       avgt       3   3.082 ± 0.925   ms/op
ClientGrpc.existUser                        avgt       3   2.985 ± 0.806   ms/op
ClientGrpc.getUser                          avgt       3   3.046 ± 2.014   ms/op
ClientGrpc.listUser                         avgt       3   3.947 ± 1.204   ms/op
ClientGrpc.createUser                     sample  304110   3.156 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.728           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.092           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.857           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.066           ms/op
ClientGrpc.existUser                      sample  339513   2.826 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.245           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.110           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.188           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  321395   2.987 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.244           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.767           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.582           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.312           ms/op
ClientGrpc.listUser                       sample  239459   4.006 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.378           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.172           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.710           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.117           ms/op
