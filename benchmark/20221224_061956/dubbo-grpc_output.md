# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.613 ops/ms
# Warmup Iteration   2: 9.562 ops/ms
# Warmup Iteration   3: 10.415 ops/ms
Iteration   1: 10.333 ops/ms
Iteration   2: 10.553 ops/ms
Iteration   3: 10.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.350 ±(99.9%) 3.556 ops/ms [Average]
  (min, avg, max) = (10.164, 10.350, 10.553), stdev = 0.195
  CI (99.9%): [6.793, 13.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.039 ops/ms
# Warmup Iteration   2: 10.307 ops/ms
# Warmup Iteration   3: 10.729 ops/ms
Iteration   1: 10.662 ops/ms
Iteration   2: 10.909 ops/ms
Iteration   3: 10.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.787 ±(99.9%) 2.253 ops/ms [Average]
  (min, avg, max) = (10.662, 10.787, 10.909), stdev = 0.123
  CI (99.9%): [8.534, 13.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.404 ops/ms
# Warmup Iteration   2: 10.274 ops/ms
# Warmup Iteration   3: 10.337 ops/ms
Iteration   1: 10.848 ops/ms
Iteration   2: 10.342 ops/ms
Iteration   3: 10.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.564 ±(99.9%) 4.721 ops/ms [Average]
  (min, avg, max) = (10.342, 10.564, 10.848), stdev = 0.259
  CI (99.9%): [5.843, 15.284] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.609 ops/ms
# Warmup Iteration   2: 7.863 ops/ms
# Warmup Iteration   3: 8.087 ops/ms
Iteration   1: 8.280 ops/ms
Iteration   2: 8.112 ops/ms
Iteration   3: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.171 ±(99.9%) 1.736 ops/ms [Average]
  (min, avg, max) = (8.112, 8.171, 8.280), stdev = 0.095
  CI (99.9%): [6.434, 9.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.904 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.002 ms/op
Iteration   1: 2.992 ±(99.9%) 0.003 ms/op
Iteration   2: 3.182 ±(99.9%) 0.002 ms/op
Iteration   3: 2.953 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.042 ±(99.9%) 2.236 ms/op [Average]
  (min, avg, max) = (2.953, 3.042, 3.182), stdev = 0.123
  CI (99.9%): [0.806, 5.278] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.888 ±(99.9%) 0.004 ms/op
Iteration   1: 2.984 ±(99.9%) 0.002 ms/op
Iteration   2: 2.960 ±(99.9%) 0.003 ms/op
Iteration   3: 2.887 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.944 ±(99.9%) 0.923 ms/op [Average]
  (min, avg, max) = (2.887, 2.944, 2.984), stdev = 0.051
  CI (99.9%): [2.021, 3.866] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.003 ms/op
Iteration   1: 3.072 ±(99.9%) 0.002 ms/op
Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
Iteration   3: 3.076 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.069 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (3.061, 3.069, 3.076), stdev = 0.008
  CI (99.9%): [2.925, 3.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.689 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.017 ms/op
Iteration   1: 3.895 ±(99.9%) 0.010 ms/op
Iteration   2: 3.959 ±(99.9%) 0.040 ms/op
Iteration   3: 3.985 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.946 ±(99.9%) 0.846 ms/op [Average]
  (min, avg, max) = (3.895, 3.946, 3.985), stdev = 0.046
  CI (99.9%): [3.100, 4.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.076 ms/op
                 createUser·p0.999:  6.483 ms/op
                 createUser·p0.9999: 15.198 ms/op
                 createUser·p1.00:   15.614 ms/op

Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.473 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.995 ms/op
                 createUser·p0.9999: 16.168 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   3: 3.101 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.369 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  10.519 ms/op
                 createUser·p0.9999: 26.837 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316065
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33157 
    [ 2.500,  5.000) = 281979 
    [ 5.000,  7.500) = 515 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.369 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.568 ms/op
     p(99.9900) =     26.260 ms/op
     p(99.9990) =     27.034 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.716 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.811 ms/op
                 existUser·p0.9999: 11.452 ms/op
                 existUser·p1.00:   11.846 ms/op

Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.220 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  5.948 ms/op
                 existUser·p0.9999: 17.733 ms/op
                 existUser·p1.00:   18.285 ms/op

Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  5.902 ms/op
                 existUser·p0.9999: 14.360 ms/op
                 existUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323131
  mean =      2.969 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2711 
    [ 1.250,  2.500) = 48836 
    [ 2.500,  3.750) = 249926 
    [ 3.750,  5.000) = 20870 
    [ 5.000,  6.250) = 466 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.220 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.231 ms/op
     p(99.9900) =     16.307 ms/op
     p(99.9990) =     18.164 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.061 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.940 ms/op
                 getUser·p0.9999: 12.796 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  10.174 ms/op
                 getUser·p0.9999: 22.088 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.487 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.594 ms/op
                 getUser·p0.9999: 16.152 ms/op
                 getUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320681
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31466 
    [ 2.500,  5.000) = 288038 
    [ 5.000,  7.500) = 835 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.619 ms/op
     p(99.9900) =     16.512 ms/op
     p(99.9990) =     22.996 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.898 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.011 ms/op
Iteration   1: 3.892 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   3.738 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.754 ms/op
                 listUser·p0.999:  11.932 ms/op
                 listUser·p0.9999: 17.812 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 3.774 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  14.247 ms/op
                 listUser·p0.9999: 18.995 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 4.041 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.032 ms/op
                 listUser·p0.999:  15.842 ms/op
                 listUser·p0.9999: 23.265 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246254
  mean =      3.899 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3764 
    [ 2.500,  5.000) = 218113 
    [ 5.000,  7.500) = 23301 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.644 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     23.449 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.350 ± 3.556  ops/ms
ClientGrpc.existUser                       thrpt       3  10.787 ± 2.253  ops/ms
ClientGrpc.getUser                         thrpt       3  10.564 ± 4.721  ops/ms
ClientGrpc.listUser                        thrpt       3   8.171 ± 1.736  ops/ms
ClientGrpc.createUser                       avgt       3   3.042 ± 2.236   ms/op
ClientGrpc.existUser                        avgt       3   2.944 ± 0.923   ms/op
ClientGrpc.getUser                          avgt       3   3.069 ± 0.144   ms/op
ClientGrpc.listUser                         avgt       3   3.946 ± 0.846   ms/op
ClientGrpc.createUser                     sample  316065   3.038 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.369           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.568           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.260           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.165           ms/op
ClientGrpc.existUser                      sample  323131   2.969 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.220           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.826           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.231           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.307           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.285           ms/op
ClientGrpc.getUser                        sample  320681   2.995 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.487           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.619           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.512           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.101           ms/op
ClientGrpc.listUser                       sample  246254   3.899 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.940           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.644           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.774           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.658           ms/op
