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
# Warmup Iteration   1: 3.775 ops/ms
# Warmup Iteration   2: 8.677 ops/ms
# Warmup Iteration   3: 9.846 ops/ms
Iteration   1: 9.867 ops/ms
Iteration   2: 9.814 ops/ms
Iteration   3: 9.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.865 ±(99.9%) 0.898 ops/ms [Average]
  (min, avg, max) = (9.814, 9.865, 9.913), stdev = 0.049
  CI (99.9%): [8.967, 10.762] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.674 ops/ms
# Warmup Iteration   2: 10.254 ops/ms
# Warmup Iteration   3: 10.466 ops/ms
Iteration   1: 10.648 ops/ms
Iteration   2: 10.569 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.572 ±(99.9%) 1.373 ops/ms [Average]
  (min, avg, max) = (10.498, 10.572, 10.648), stdev = 0.075
  CI (99.9%): [9.199, 11.945] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.874 ops/ms
# Warmup Iteration   2: 10.039 ops/ms
# Warmup Iteration   3: 10.237 ops/ms
Iteration   1: 10.094 ops/ms
Iteration   2: 10.151 ops/ms
Iteration   3: 10.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.204 ±(99.9%) 2.637 ops/ms [Average]
  (min, avg, max) = (10.094, 10.204, 10.368), stdev = 0.145
  CI (99.9%): [7.567, 12.841] (assumes normal distribution)


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
# Warmup Iteration   1: 5.768 ops/ms
# Warmup Iteration   2: 7.272 ops/ms
# Warmup Iteration   3: 7.529 ops/ms
Iteration   1: 7.431 ops/ms
Iteration   2: 7.928 ops/ms
Iteration   3: 7.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.735 ±(99.9%) 4.867 ops/ms [Average]
  (min, avg, max) = (7.431, 7.735, 7.928), stdev = 0.267
  CI (99.9%): [2.868, 12.602] (assumes normal distribution)


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
# Warmup Iteration   1: 4.546 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.010 ms/op
Iteration   1: 3.173 ±(99.9%) 0.010 ms/op
Iteration   2: 3.243 ±(99.9%) 0.001 ms/op
Iteration   3: 3.105 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.174 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (3.105, 3.174, 3.243), stdev = 0.069
  CI (99.9%): [1.912, 4.435] (assumes normal distribution)


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.003 ms/op
Iteration   1: 3.137 ±(99.9%) 0.001 ms/op
Iteration   2: 3.083 ±(99.9%) 0.002 ms/op
Iteration   3: 3.050 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.090 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.050, 3.090, 3.137), stdev = 0.044
  CI (99.9%): [2.289, 3.891] (assumes normal distribution)


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
# Warmup Iteration   1: 4.183 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.003 ms/op
Iteration   1: 3.158 ±(99.9%) 0.002 ms/op
Iteration   2: 3.146 ±(99.9%) 0.002 ms/op
Iteration   3: 3.099 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.134 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.099, 3.134, 3.158), stdev = 0.031
  CI (99.9%): [2.566, 3.703] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.697 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.008 ms/op
Iteration   1: 4.095 ±(99.9%) 0.012 ms/op
Iteration   2: 4.006 ±(99.9%) 0.024 ms/op
Iteration   3: 3.890 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.997 ±(99.9%) 1.873 ms/op [Average]
  (min, avg, max) = (3.890, 3.997, 4.095), stdev = 0.103
  CI (99.9%): [2.124, 5.870] (assumes normal distribution)


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.006 ms/op
Iteration   1: 3.221 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.366 ms/op
                 createUser·p0.9999: 14.570 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.037 ms/op
                 createUser·p0.9999: 15.247 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.840 ms/op
                 createUser·p0.9999: 17.433 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303101
  mean =      3.168 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 593 
    [ 1.250,  2.500) = 20113 
    [ 2.500,  3.750) = 243562 
    [ 3.750,  5.000) = 37808 
    [ 5.000,  6.250) = 410 
    [ 6.250,  7.500) = 319 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 84 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.471 ms/op
     p(99.9900) =     16.762 ms/op
     p(99.9990) =     17.496 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  4.976 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  9.519 ms/op
                 existUser·p0.9999: 17.558 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  6.500 ms/op
                 existUser·p0.9999: 16.843 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314111
  mean =      3.056 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 758 
    [ 1.250,  2.500) = 31204 
    [ 2.500,  3.750) = 254791 
    [ 3.750,  5.000) = 26744 
    [ 5.000,  6.250) = 227 
    [ 6.250,  7.500) = 157 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      6.470 ms/op
     p(99.9900) =     16.649 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.007 ms/op
Iteration   1: 3.170 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  8.070 ms/op
                 getUser·p0.9999: 12.106 ms/op
                 getUser·p1.00:   12.485 ms/op

Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  11.684 ms/op
                 getUser·p0.9999: 17.689 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   3: 3.251 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.075 ms/op
                 getUser·p0.9999: 17.957 ms/op
                 getUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300161
  mean =      3.196 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 493 
    [ 1.250,  2.500) = 17026 
    [ 2.500,  3.750) = 241177 
    [ 3.750,  5.000) = 40097 
    [ 5.000,  6.250) = 691 
    [ 6.250,  7.500) = 334 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.289 ms/op
     p(99.9900) =     17.563 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 5.548 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.010 ms/op
Iteration   1: 4.086 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.218 ms/op
                 listUser·p0.9999: 21.048 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 4.117 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.756 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.502 ms/op
                 listUser·p0.9999: 23.633 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 4.080 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  16.359 ms/op
                 listUser·p0.9999: 20.550 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234588
  mean =      4.094 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1502 
    [ 2.500,  5.000) = 204560 
    [ 5.000,  7.500) = 27149 
    [ 7.500, 10.000) = 944 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.982 ms/op
     p(99.9900) =     22.449 ms/op
     p(99.9990) =     24.050 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.865 ± 0.898  ops/ms
ClientGrpc.existUser                       thrpt       3  10.572 ± 1.373  ops/ms
ClientGrpc.getUser                         thrpt       3  10.204 ± 2.637  ops/ms
ClientGrpc.listUser                        thrpt       3   7.735 ± 4.867  ops/ms
ClientGrpc.createUser                       avgt       3   3.174 ± 1.261   ms/op
ClientGrpc.existUser                        avgt       3   3.090 ± 0.801   ms/op
ClientGrpc.getUser                          avgt       3   3.134 ± 0.569   ms/op
ClientGrpc.listUser                         avgt       3   3.997 ± 1.873   ms/op
ClientGrpc.createUser                     sample  303101   3.168 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.796           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.471           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.762           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.662           ms/op
ClientGrpc.existUser                      sample  314111   3.056 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.625           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.470           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.649           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.859           ms/op
ClientGrpc.getUser                        sample  300161   3.196 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.635           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.104           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.289           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.563           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.645           ms/op
ClientGrpc.listUser                       sample  234588   4.094 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.756           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.920           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.982           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.449           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.117           ms/op
