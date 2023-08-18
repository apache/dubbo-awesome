# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ops/ms
# Warmup Iteration   2: 8.656 ops/ms
# Warmup Iteration   3: 9.864 ops/ms
Iteration   1: 10.237 ops/ms
Iteration   2: 10.730 ops/ms
Iteration   3: 10.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.518 ±(99.9%) 4.629 ops/ms [Average]
  (min, avg, max) = (10.237, 10.518, 10.730), stdev = 0.254
  CI (99.9%): [5.889, 15.147] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.317 ops/ms
# Warmup Iteration   2: 10.470 ops/ms
# Warmup Iteration   3: 10.948 ops/ms
Iteration   1: 11.245 ops/ms
Iteration   2: 11.716 ops/ms
Iteration   3: 10.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.305 ±(99.9%) 7.020 ops/ms [Average]
  (min, avg, max) = (10.953, 11.305, 11.716), stdev = 0.385
  CI (99.9%): [4.284, 18.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.858 ops/ms
# Warmup Iteration   2: 9.859 ops/ms
# Warmup Iteration   3: 10.433 ops/ms
Iteration   1: 10.247 ops/ms
Iteration   2: 10.176 ops/ms
Iteration   3: 10.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.251 ±(99.9%) 1.408 ops/ms [Average]
  (min, avg, max) = (10.176, 10.251, 10.331), stdev = 0.077
  CI (99.9%): [8.844, 11.659] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.416 ops/ms
# Warmup Iteration   2: 7.744 ops/ms
# Warmup Iteration   3: 7.968 ops/ms
Iteration   1: 8.183 ops/ms
Iteration   2: 8.121 ops/ms
Iteration   3: 8.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.131 ±(99.9%) 0.886 ops/ms [Average]
  (min, avg, max) = (8.087, 8.131, 8.183), stdev = 0.049
  CI (99.9%): [7.245, 9.016] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.337 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.001 ms/op
Iteration   1: 3.102 ±(99.9%) 0.003 ms/op
Iteration   2: 3.029 ±(99.9%) 0.004 ms/op
Iteration   3: 3.071 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.067 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.029, 3.067, 3.102), stdev = 0.037
  CI (99.9%): [2.401, 3.734] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.002 ms/op
Iteration   1: 2.848 ±(99.9%) 0.003 ms/op
Iteration   2: 2.922 ±(99.9%) 0.002 ms/op
Iteration   3: 2.881 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.884 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (2.848, 2.884, 2.922), stdev = 0.037
  CI (99.9%): [2.205, 3.563] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.002 ms/op
Iteration   1: 3.074 ±(99.9%) 0.004 ms/op
Iteration   2: 3.072 ±(99.9%) 0.003 ms/op
Iteration   3: 3.037 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.061 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.037, 3.061, 3.074), stdev = 0.021
  CI (99.9%): [2.678, 3.444] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.064 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.023 ms/op
Iteration   1: 3.979 ±(99.9%) 0.020 ms/op
Iteration   2: 3.987 ±(99.9%) 0.014 ms/op
Iteration   3: 3.909 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.958 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (3.909, 3.958, 3.987), stdev = 0.043
  CI (99.9%): [3.177, 4.740] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.268 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 3.090 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  10.087 ms/op
                 createUser·p0.9999: 21.320 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.573 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 23.989 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   3: 3.035 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.632 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  10.348 ms/op
                 createUser·p0.9999: 25.559 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313550
  mean =      3.061 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19889 
    [ 2.500,  5.000) = 291460 
    [ 5.000,  7.500) = 1556 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     24.454 ms/op
     p(99.9990) =     25.784 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.530 ms/op
                 existUser·p0.9999: 13.877 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.424 ms/op
                 existUser·p0.9999: 14.881 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   3: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  9.769 ms/op
                 existUser·p0.9999: 16.683 ms/op
                 existUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322205
  mean =      2.978 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1358 
    [ 1.250,  2.500) = 30545 
    [ 2.500,  3.750) = 275348 
    [ 3.750,  5.000) = 13245 
    [ 5.000,  6.250) = 886 
    [ 6.250,  7.500) = 425 
    [ 7.500,  8.750) = 142 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.873 ms/op
     p(99.9900) =     16.151 ms/op
     p(99.9990) =     16.828 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.251 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.006 ms/op
Iteration   1: 3.044 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.388 ms/op
                 getUser·p0.999:  8.469 ms/op
                 getUser·p0.9999: 12.501 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.154 ms/op
                 getUser·p0.9999: 17.450 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  10.127 ms/op
                 getUser·p0.9999: 16.949 ms/op
                 getUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313403
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 533 
    [ 1.250,  2.500) = 17597 
    [ 2.500,  3.750) = 279057 
    [ 3.750,  5.000) = 14087 
    [ 5.000,  6.250) = 1029 
    [ 6.250,  7.500) = 477 
    [ 7.500,  8.750) = 330 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 50 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     17.138 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.757 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.012 ms/op
Iteration   1: 3.974 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.017 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 21.689 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 3.997 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.510 ms/op
                 listUser·p0.9999: 19.593 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 3.769 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.354 ms/op
                 listUser·p0.9999: 17.483 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245551
  mean =      3.911 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3751 
    [ 2.500,  5.000) = 217002 
    [ 5.000,  7.500) = 23122 
    [ 7.500, 10.000) = 1098 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     16.168 ms/op
     p(99.9900) =     21.215 ms/op
     p(99.9990) =     21.862 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.518 ± 4.629  ops/ms
ClientGrpc.existUser                       thrpt       3  11.305 ± 7.020  ops/ms
ClientGrpc.getUser                         thrpt       3  10.251 ± 1.408  ops/ms
ClientGrpc.listUser                        thrpt       3   8.131 ± 0.886  ops/ms
ClientGrpc.createUser                       avgt       3   3.067 ± 0.667   ms/op
ClientGrpc.existUser                        avgt       3   2.884 ± 0.679   ms/op
ClientGrpc.getUser                          avgt       3   3.061 ± 0.383   ms/op
ClientGrpc.listUser                         avgt       3   3.958 ± 0.782   ms/op
ClientGrpc.createUser                     sample  313550   3.061 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.573           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.880           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.454           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.083           ms/op
ClientGrpc.existUser                      sample  322205   2.978 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.518           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.873           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.151           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.876           ms/op
ClientGrpc.getUser                        sample  313403   3.063 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.545           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.651           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.138           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.990           ms/op
ClientGrpc.listUser                       sample  245551   3.911 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.964           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.168           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.215           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.413           ms/op
