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
# Warmup Iteration   1: 4.574 ops/ms
# Warmup Iteration   2: 9.347 ops/ms
# Warmup Iteration   3: 10.307 ops/ms
Iteration   1: 10.836 ops/ms
Iteration   2: 10.680 ops/ms
Iteration   3: 10.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.775 ±(99.9%) 1.518 ops/ms [Average]
  (min, avg, max) = (10.680, 10.775, 10.836), stdev = 0.083
  CI (99.9%): [9.257, 12.293] (assumes normal distribution)


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
# Warmup Iteration   1: 8.749 ops/ms
# Warmup Iteration   2: 10.795 ops/ms
# Warmup Iteration   3: 11.099 ops/ms
Iteration   1: 11.466 ops/ms
Iteration   2: 11.437 ops/ms
Iteration   3: 11.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.403 ±(99.9%) 1.546 ops/ms [Average]
  (min, avg, max) = (11.307, 11.403, 11.466), stdev = 0.085
  CI (99.9%): [9.857, 12.949] (assumes normal distribution)


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
# Warmup Iteration   1: 7.764 ops/ms
# Warmup Iteration   2: 10.488 ops/ms
# Warmup Iteration   3: 10.733 ops/ms
Iteration   1: 10.761 ops/ms
Iteration   2: 10.858 ops/ms
Iteration   3: 10.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.775 ±(99.9%) 1.395 ops/ms [Average]
  (min, avg, max) = (10.707, 10.775, 10.858), stdev = 0.076
  CI (99.9%): [9.380, 12.170] (assumes normal distribution)


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
# Warmup Iteration   1: 6.063 ops/ms
# Warmup Iteration   2: 7.921 ops/ms
# Warmup Iteration   3: 8.357 ops/ms
Iteration   1: 8.382 ops/ms
Iteration   2: 8.415 ops/ms
Iteration   3: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.366 ±(99.9%) 1.069 ops/ms [Average]
  (min, avg, max) = (8.301, 8.366, 8.415), stdev = 0.059
  CI (99.9%): [7.296, 9.435] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.003 ms/op
Iteration   1: 2.889 ±(99.9%) 0.003 ms/op
Iteration   2: 3.039 ±(99.9%) 0.002 ms/op
Iteration   3: 2.961 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.963 ±(99.9%) 1.369 ms/op [Average]
  (min, avg, max) = (2.889, 2.963, 3.039), stdev = 0.075
  CI (99.9%): [1.594, 4.332] (assumes normal distribution)


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 2.935 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.830 ±(99.9%) 0.003 ms/op
Iteration   1: 2.842 ±(99.9%) 0.002 ms/op
Iteration   2: 2.838 ±(99.9%) 0.003 ms/op
Iteration   3: 2.836 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.838 ±(99.9%) 0.051 ms/op [Average]
  (min, avg, max) = (2.836, 2.838, 2.842), stdev = 0.003
  CI (99.9%): [2.787, 2.889] (assumes normal distribution)


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.003 ms/op
Iteration   1: 2.995 ±(99.9%) 0.002 ms/op
Iteration   2: 2.940 ±(99.9%) 0.003 ms/op
Iteration   3: 2.971 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.969 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (2.940, 2.969, 2.995), stdev = 0.028
  CI (99.9%): [2.462, 3.476] (assumes normal distribution)


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
# Warmup Iteration   1: 5.024 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.018 ms/op
Iteration   1: 3.781 ±(99.9%) 0.028 ms/op
Iteration   2: 3.782 ±(99.9%) 0.008 ms/op
Iteration   3: 3.780 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.781 ±(99.9%) 0.021 ms/op [Average]
  (min, avg, max) = (3.780, 3.781, 3.782), stdev = 0.001
  CI (99.9%): [3.761, 3.802] (assumes normal distribution)


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.007 ms/op
Iteration   1: 2.951 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.942 ms/op
                 createUser·p0.9999: 16.489 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  9.961 ms/op
                 createUser·p0.9999: 12.818 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.021 ms/op
                 createUser·p0.9999: 17.433 ms/op
                 createUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324218
  mean =      2.961 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2197 
    [ 1.250,  2.500) = 28403 
    [ 2.500,  3.750) = 278278 
    [ 3.750,  5.000) = 14305 
    [ 5.000,  6.250) = 562 
    [ 6.250,  7.500) = 133 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.795 ms/op
     p(99.9900) =     17.093 ms/op
     p(99.9990) =     18.801 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 3.715 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.005 ms/op
Iteration   1: 2.832 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.205 ms/op
                 existUser·p0.9999: 15.249 ms/op
                 existUser·p1.00:   15.942 ms/op

Iteration   2: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.448 ms/op
                 existUser·p0.9999: 13.433 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.915 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  7.419 ms/op
                 existUser·p0.9999: 16.843 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333202
  mean =      2.881 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2222 
    [ 1.250,  2.500) = 46058 
    [ 2.500,  3.750) = 276231 
    [ 3.750,  5.000) = 7847 
    [ 5.000,  6.250) = 461 
    [ 6.250,  7.500) = 131 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.601 ms/op
     p(99.9900) =     15.936 ms/op
     p(99.9990) =     17.192 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.005 ms/op
Iteration   1: 2.965 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.524 ms/op
                 getUser·p0.9999: 17.629 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   2: 2.913 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.490 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.420 ms/op
                 getUser·p0.9999: 13.108 ms/op
                 getUser·p1.00:   13.206 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.167 ms/op
                 getUser·p0.9999: 14.863 ms/op
                 getUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324056
  mean =      2.961 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2551 
    [ 1.250,  2.500) = 29179 
    [ 2.500,  3.750) = 278431 
    [ 3.750,  5.000) = 12561 
    [ 5.000,  6.250) = 751 
    [ 6.250,  7.500) = 268 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.381 ms/op
     p(99.9900) =     16.031 ms/op
     p(99.9990) =     19.197 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 4.819 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.011 ms/op
Iteration   1: 3.879 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  11.969 ms/op
                 listUser·p0.9999: 18.768 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   2: 3.778 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  13.441 ms/op
                 listUser·p0.9999: 17.024 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 3.808 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.242 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 19.549 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251084
  mean =      3.821 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3718 
    [ 2.500,  5.000) = 230552 
    [ 5.000,  7.500) = 15728 
    [ 7.500, 10.000) = 607 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     18.838 ms/op
     p(99.9990) =     20.675 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.775 ± 1.518  ops/ms
ClientGrpc.existUser                       thrpt       3  11.403 ± 1.546  ops/ms
ClientGrpc.getUser                         thrpt       3  10.775 ± 1.395  ops/ms
ClientGrpc.listUser                        thrpt       3   8.366 ± 1.069  ops/ms
ClientGrpc.createUser                       avgt       3   2.963 ± 1.369   ms/op
ClientGrpc.existUser                        avgt       3   2.838 ± 0.051   ms/op
ClientGrpc.getUser                          avgt       3   2.969 ± 0.507   ms/op
ClientGrpc.listUser                         avgt       3   3.781 ± 0.021   ms/op
ClientGrpc.createUser                     sample  324218   2.961 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.646           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.457           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.795           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.093           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.874           ms/op
ClientGrpc.existUser                      sample  333202   2.881 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.531           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.601           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.936           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.661           ms/op
ClientGrpc.getUser                        sample  324056   2.961 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.640           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.381           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.031           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.759           ms/op
ClientGrpc.listUser                       sample  251084   3.821 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.920           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.206           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.838           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.331           ms/op
