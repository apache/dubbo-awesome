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
# Warmup Iteration   1: 5.069 ops/ms
# Warmup Iteration   2: 9.366 ops/ms
# Warmup Iteration   3: 10.370 ops/ms
Iteration   1: 10.735 ops/ms
Iteration   2: 10.699 ops/ms
Iteration   3: 10.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.802 ±(99.9%) 2.723 ops/ms [Average]
  (min, avg, max) = (10.699, 10.802, 10.973), stdev = 0.149
  CI (99.9%): [8.079, 13.525] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.126 ops/ms
# Warmup Iteration   2: 10.888 ops/ms
# Warmup Iteration   3: 11.478 ops/ms
Iteration   1: 11.154 ops/ms
Iteration   2: 11.353 ops/ms
Iteration   3: 11.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.259 ±(99.9%) 1.822 ops/ms [Average]
  (min, avg, max) = (11.154, 11.259, 11.353), stdev = 0.100
  CI (99.9%): [9.437, 13.080] (assumes normal distribution)


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
# Warmup Iteration   1: 7.647 ops/ms
# Warmup Iteration   2: 10.407 ops/ms
# Warmup Iteration   3: 10.861 ops/ms
Iteration   1: 10.705 ops/ms
Iteration   2: 10.759 ops/ms
Iteration   3: 10.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.766 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (10.705, 10.766, 10.834), stdev = 0.065
  CI (99.9%): [9.588, 11.943] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.355 ops/ms
# Warmup Iteration   2: 8.321 ops/ms
# Warmup Iteration   3: 8.324 ops/ms
Iteration   1: 8.300 ops/ms
Iteration   2: 8.347 ops/ms
Iteration   3: 8.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.302 ±(99.9%) 0.801 ops/ms [Average]
  (min, avg, max) = (8.259, 8.302, 8.347), stdev = 0.044
  CI (99.9%): [7.501, 9.104] (assumes normal distribution)


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.002 ms/op
Iteration   1: 2.955 ±(99.9%) 0.002 ms/op
Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
Iteration   3: 3.024 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.977 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (2.954, 2.977, 3.024), stdev = 0.040
  CI (99.9%): [2.248, 3.707] (assumes normal distribution)


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.940 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.002 ms/op
Iteration   1: 2.840 ±(99.9%) 0.003 ms/op
Iteration   2: 2.849 ±(99.9%) 0.004 ms/op
Iteration   3: 2.847 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.845 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.840, 2.845, 2.849), stdev = 0.005
  CI (99.9%): [2.759, 2.932] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 2.937 ±(99.9%) 0.003 ms/op
Iteration   2: 2.947 ±(99.9%) 0.003 ms/op
Iteration   3: 2.974 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.953 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (2.937, 2.953, 2.974), stdev = 0.019
  CI (99.9%): [2.599, 3.307] (assumes normal distribution)


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
# Warmup Iteration   1: 4.137 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.006 ms/op
Iteration   1: 3.887 ±(99.9%) 0.012 ms/op
Iteration   2: 3.822 ±(99.9%) 0.014 ms/op
Iteration   3: 3.880 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.863 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.822, 3.863, 3.887), stdev = 0.036
  CI (99.9%): [3.214, 4.512] (assumes normal distribution)


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 2.960 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.356 ms/op
                 createUser·p0.999:  11.010 ms/op
                 createUser·p0.9999: 13.526 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 2.962 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 12.636 ms/op
                 createUser·p1.00:   12.780 ms/op

Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.549 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.283 ms/op
                 createUser·p0.9999: 25.599 ms/op
                 createUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323736
  mean =      2.964 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30371 
    [ 2.500,  5.000) = 292262 
    [ 5.000,  7.500) = 691 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      9.630 ms/op
     p(99.9900) =     21.241 ms/op
     p(99.9990) =     25.715 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.889 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
Iteration   1: 2.833 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  5.808 ms/op
                 existUser·p0.9999: 11.267 ms/op
                 existUser·p1.00:   11.469 ms/op

Iteration   2: 2.851 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 14.309 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 2.817 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.401 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338649
  mean =      2.833 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50763 
    [ 2.500,  5.000) = 286733 
    [ 5.000,  7.500) = 823 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     16.847 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 3.736 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.514 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  7.145 ms/op
                 getUser·p0.9999: 14.893 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   2: 2.930 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.128 ms/op
                 getUser·p0.9999: 26.643 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.375 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  5.955 ms/op
                 getUser·p0.9999: 24.418 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325026
  mean =      2.953 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26310 
    [ 2.500,  5.000) = 297794 
    [ 5.000,  7.500) = 719 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      6.742 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     26.763 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 4.930 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.010 ms/op
Iteration   1: 3.778 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  11.840 ms/op
                 listUser·p0.9999: 14.691 ms/op
                 listUser·p1.00:   15.516 ms/op

Iteration   2: 3.915 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  12.321 ms/op
                 listUser·p0.9999: 14.666 ms/op
                 listUser·p1.00:   14.942 ms/op

Iteration   3: 3.811 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.715 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  16.680 ms/op
                 listUser·p0.9999: 21.109 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250340
  mean =      3.834 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4182 
    [ 2.500,  5.000) = 227044 
    [ 5.000,  7.500) = 18145 
    [ 7.500, 10.000) = 552 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     19.821 ms/op
     p(99.9990) =     21.397 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.802 ± 2.723  ops/ms
ClientGrpc.existUser                       thrpt       3  11.259 ± 1.822  ops/ms
ClientGrpc.getUser                         thrpt       3  10.766 ± 1.177  ops/ms
ClientGrpc.listUser                        thrpt       3   8.302 ± 0.801  ops/ms
ClientGrpc.createUser                       avgt       3   2.977 ± 0.730   ms/op
ClientGrpc.existUser                        avgt       3   2.845 ± 0.087   ms/op
ClientGrpc.getUser                          avgt       3   2.953 ± 0.354   ms/op
ClientGrpc.listUser                         avgt       3   3.863 ± 0.649   ms/op
ClientGrpc.createUser                     sample  323736   2.964 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.549           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.630           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.241           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.788           ms/op
ClientGrpc.existUser                      sample  338649   2.833 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.534           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.406           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.847           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.774           ms/op
ClientGrpc.getUser                        sample  325026   2.953 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.375           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.400           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.162           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.742           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.083           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.804           ms/op
ClientGrpc.listUser                       sample  250340   3.834 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.715           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.714           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.821           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.496           ms/op
