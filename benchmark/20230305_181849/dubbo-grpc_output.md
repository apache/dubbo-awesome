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
# Warmup Iteration   1: 4.519 ops/ms
# Warmup Iteration   2: 9.117 ops/ms
# Warmup Iteration   3: 10.061 ops/ms
Iteration   1: 11.071 ops/ms
Iteration   2: 10.330 ops/ms
Iteration   3: 10.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.513 ±(99.9%) 9.000 ops/ms [Average]
  (min, avg, max) = (10.137, 10.513, 11.071), stdev = 0.493
  CI (99.9%): [1.513, 19.513] (assumes normal distribution)


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
# Warmup Iteration   1: 7.790 ops/ms
# Warmup Iteration   2: 10.540 ops/ms
# Warmup Iteration   3: 11.028 ops/ms
Iteration   1: 11.155 ops/ms
Iteration   2: 10.774 ops/ms
Iteration   3: 11.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.999 ±(99.9%) 3.647 ops/ms [Average]
  (min, avg, max) = (10.774, 10.999, 11.155), stdev = 0.200
  CI (99.9%): [7.352, 14.646] (assumes normal distribution)


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
# Warmup Iteration   1: 7.420 ops/ms
# Warmup Iteration   2: 10.124 ops/ms
# Warmup Iteration   3: 10.370 ops/ms
Iteration   1: 10.230 ops/ms
Iteration   2: 10.449 ops/ms
Iteration   3: 10.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.330 ±(99.9%) 2.019 ops/ms [Average]
  (min, avg, max) = (10.230, 10.330, 10.449), stdev = 0.111
  CI (99.9%): [8.310, 12.349] (assumes normal distribution)


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
# Warmup Iteration   1: 5.518 ops/ms
# Warmup Iteration   2: 7.556 ops/ms
# Warmup Iteration   3: 7.898 ops/ms
Iteration   1: 7.856 ops/ms
Iteration   2: 7.894 ops/ms
Iteration   3: 7.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.873 ±(99.9%) 0.348 ops/ms [Average]
  (min, avg, max) = (7.856, 7.873, 7.894), stdev = 0.019
  CI (99.9%): [7.525, 8.222] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.050 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 3.083 ±(99.9%) 0.003 ms/op
Iteration   3: 3.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.088 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (3.076, 3.088, 3.104), stdev = 0.014
  CI (99.9%): [2.824, 3.351] (assumes normal distribution)


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
# Warmup Iteration   1: 3.620 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.003 ms/op
Iteration   1: 2.995 ±(99.9%) 0.003 ms/op
Iteration   2: 2.882 ±(99.9%) 0.003 ms/op
Iteration   3: 2.906 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.927 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (2.882, 2.927, 2.995), stdev = 0.060
  CI (99.9%): [1.839, 4.016] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.003 ms/op
Iteration   1: 3.140 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.002 ms/op
Iteration   3: 3.112 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.097 ±(99.9%) 0.945 ms/op [Average]
  (min, avg, max) = (3.040, 3.097, 3.140), stdev = 0.052
  CI (99.9%): [2.153, 4.042] (assumes normal distribution)


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
# Warmup Iteration   1: 4.248 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.043 ms/op
Iteration   1: 4.018 ±(99.9%) 0.011 ms/op
Iteration   2: 4.032 ±(99.9%) 0.010 ms/op
Iteration   3: 4.005 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.019 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (4.005, 4.019, 4.032), stdev = 0.013
  CI (99.9%): [3.776, 4.261] (assumes normal distribution)


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
Iteration   1: 3.087 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.630 ms/op
                 createUser·p0.9999: 11.627 ms/op
                 createUser·p1.00:   12.222 ms/op

Iteration   2: 2.952 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.513 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  12.207 ms/op
                 createUser·p0.9999: 17.208 ms/op
                 createUser·p1.00:   19.923 ms/op

Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  10.874 ms/op
                 createUser·p0.9999: 25.303 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316106
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31381 
    [ 2.500,  5.000) = 283614 
    [ 5.000,  7.500) = 681 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      9.812 ms/op
     p(99.9900) =     24.523 ms/op
     p(99.9990) =     25.548 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 3.540 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.767 ms/op
                 existUser·p0.9999: 13.261 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   2: 2.955 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  6.827 ms/op
                 existUser·p0.9999: 14.801 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  5.951 ms/op
                 existUser·p0.9999: 14.778 ms/op
                 existUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324346
  mean =      2.960 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3486 
    [ 1.250,  2.500) = 43790 
    [ 2.500,  3.750) = 256722 
    [ 3.750,  5.000) = 19604 
    [ 5.000,  6.250) = 329 
    [ 6.250,  7.500) = 206 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 92 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      6.742 ms/op
     p(99.9900) =     14.738 ms/op
     p(99.9990) =     15.000 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.006 ms/op
Iteration   1: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.361 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.863 ms/op
                 getUser·p0.9999: 13.681 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.479 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  6.658 ms/op
                 getUser·p0.9999: 14.916 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.570 ms/op
                 getUser·p0.9999: 15.743 ms/op
                 getUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307836
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1148 
    [ 1.250,  2.500) = 20550 
    [ 2.500,  3.750) = 254965 
    [ 3.750,  5.000) = 30043 
    [ 5.000,  6.250) = 588 
    [ 6.250,  7.500) = 216 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.361 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.643 ms/op
     p(99.9900) =     15.172 ms/op
     p(99.9990) =     16.037 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 5.232 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.012 ms/op
Iteration   1: 4.112 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 16.306 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   2: 3.932 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.516 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.123 ms/op
                 listUser·p0.9999: 19.128 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 3.893 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  16.513 ms/op
                 listUser·p0.9999: 28.021 ms/op
                 listUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241417
  mean =      3.977 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2857 
    [ 2.500,  5.000) = 212053 
    [ 5.000,  7.500) = 25619 
    [ 7.500, 10.000) = 536 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     26.149 ms/op
     p(99.9990) =     28.934 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.513 ± 9.000  ops/ms
ClientGrpc.existUser                       thrpt       3  10.999 ± 3.647  ops/ms
ClientGrpc.getUser                         thrpt       3  10.330 ± 2.019  ops/ms
ClientGrpc.listUser                        thrpt       3   7.873 ± 0.348  ops/ms
ClientGrpc.createUser                       avgt       3   3.088 ± 0.263   ms/op
ClientGrpc.existUser                        avgt       3   2.927 ± 1.089   ms/op
ClientGrpc.getUser                          avgt       3   3.097 ± 0.945   ms/op
ClientGrpc.listUser                         avgt       3   4.019 ± 0.243   ms/op
ClientGrpc.createUser                     sample  316106   3.036 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.513           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.812           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.523           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.657           ms/op
ClientGrpc.existUser                      sample  324346   2.960 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.673           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.742           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.738           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.073           ms/op
ClientGrpc.getUser                        sample  307836   3.117 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.361           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.643           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.172           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.924           ms/op
ClientGrpc.listUser                       sample  241417   3.977 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.802           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.647           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.149           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.967           ms/op
