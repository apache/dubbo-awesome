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
# Warmup Iteration   1: 3.842 ops/ms
# Warmup Iteration   2: 8.780 ops/ms
# Warmup Iteration   3: 9.940 ops/ms
Iteration   1: 9.944 ops/ms
Iteration   2: 9.896 ops/ms
Iteration   3: 10.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.959 ±(99.9%) 1.302 ops/ms [Average]
  (min, avg, max) = (9.896, 9.959, 10.037), stdev = 0.071
  CI (99.9%): [8.657, 11.260] (assumes normal distribution)


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
# Warmup Iteration   1: 7.171 ops/ms
# Warmup Iteration   2: 9.808 ops/ms
# Warmup Iteration   3: 10.253 ops/ms
Iteration   1: 10.257 ops/ms
Iteration   2: 10.150 ops/ms
Iteration   3: 10.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.229 ±(99.9%) 1.263 ops/ms [Average]
  (min, avg, max) = (10.150, 10.229, 10.280), stdev = 0.069
  CI (99.9%): [8.967, 11.492] (assumes normal distribution)


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
# Warmup Iteration   1: 6.617 ops/ms
# Warmup Iteration   2: 9.631 ops/ms
# Warmup Iteration   3: 9.950 ops/ms
Iteration   1: 9.845 ops/ms
Iteration   2: 10.010 ops/ms
Iteration   3: 10.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.982 ±(99.9%) 2.306 ops/ms [Average]
  (min, avg, max) = (9.845, 9.982, 10.093), stdev = 0.126
  CI (99.9%): [7.677, 12.288] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.295 ops/ms
# Warmup Iteration   2: 7.216 ops/ms
# Warmup Iteration   3: 7.707 ops/ms
Iteration   1: 7.918 ops/ms
Iteration   2: 7.790 ops/ms
Iteration   3: 7.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.858 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (7.790, 7.858, 7.918), stdev = 0.065
  CI (99.9%): [6.681, 9.035] (assumes normal distribution)


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
# Warmup Iteration   1: 4.592 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.001 ms/op
Iteration   1: 3.162 ±(99.9%) 0.002 ms/op
Iteration   2: 3.160 ±(99.9%) 0.002 ms/op
Iteration   3: 3.189 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.170 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (3.160, 3.170, 3.189), stdev = 0.016
  CI (99.9%): [2.870, 3.471] (assumes normal distribution)


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.002 ms/op
Iteration   1: 3.066 ±(99.9%) 0.001 ms/op
Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
Iteration   3: 3.076 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.056 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (3.025, 3.056, 3.076), stdev = 0.027
  CI (99.9%): [2.566, 3.546] (assumes normal distribution)


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
# Warmup Iteration   1: 4.629 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.002 ms/op
Iteration   1: 3.202 ±(99.9%) 0.002 ms/op
Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
Iteration   3: 3.207 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.205 ±(99.9%) 0.052 ms/op [Average]
  (min, avg, max) = (3.202, 3.205, 3.207), stdev = 0.003
  CI (99.9%): [3.153, 3.256] (assumes normal distribution)


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
# Warmup Iteration   1: 5.845 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.008 ms/op
Iteration   1: 4.166 ±(99.9%) 0.022 ms/op
Iteration   2: 3.996 ±(99.9%) 0.025 ms/op
Iteration   3: 3.886 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.016 ±(99.9%) 2.565 ms/op [Average]
  (min, avg, max) = (3.886, 4.016, 4.166), stdev = 0.141
  CI (99.9%): [1.451, 6.581] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.529 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
Iteration   1: 3.200 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.422 ms/op
                 createUser·p0.9999: 16.876 ms/op
                 createUser·p1.00:   17.400 ms/op

Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.518 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  10.376 ms/op
                 createUser·p0.9999: 17.791 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   3: 3.230 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  13.205 ms/op
                 createUser·p0.9999: 21.044 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299633
  mean =      3.204 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21024 
    [ 2.500,  5.000) = 277665 
    [ 5.000,  7.500) = 508 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      9.908 ms/op
     p(99.9900) =     19.105 ms/op
     p(99.9990) =     25.068 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 4.293 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
Iteration   1: 3.108 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.389 ms/op
                 existUser·p0.9999: 13.062 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.231 ms/op
                 existUser·p0.9999: 14.493 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.688 ms/op
                 existUser·p0.9999: 17.268 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312367
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 890 
    [ 1.250,  2.500) = 36592 
    [ 2.500,  3.750) = 245100 
    [ 3.750,  5.000) = 28877 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 222 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.644 ms/op
     p(99.9900) =     16.606 ms/op
     p(99.9990) =     17.654 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 4.261 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.006 ms/op
Iteration   1: 3.209 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.523 ms/op
                 getUser·p0.9999: 14.795 ms/op
                 getUser·p1.00:   15.090 ms/op

Iteration   2: 3.162 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.871 ms/op
                 getUser·p0.9999: 14.811 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   3: 3.141 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.840 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302933
  mean =      3.170 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 269 
    [ 1.250,  2.500) = 21243 
    [ 2.500,  3.750) = 243701 
    [ 3.750,  5.000) = 36285 
    [ 5.000,  6.250) = 659 
    [ 6.250,  7.500) = 316 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.045 ms/op
     p(99.9900) =     16.573 ms/op
     p(99.9990) =     17.496 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.409 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.012 ms/op
Iteration   1: 4.115 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  13.143 ms/op
                 listUser·p0.9999: 20.199 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.108 ms/op
                 listUser·p0.999:  14.424 ms/op
                 listUser·p0.9999: 16.602 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   3: 4.057 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  18.812 ms/op
                 listUser·p0.9999: 30.507 ms/op
                 listUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235540
  mean =      4.077 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1869 
    [ 2.500,  5.000) = 207972 
    [ 5.000,  7.500) = 24054 
    [ 7.500, 10.000) = 1103 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     29.284 ms/op
     p(99.9990) =     31.181 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.959 ± 1.302  ops/ms
ClientGrpc.existUser                       thrpt       3  10.229 ± 1.263  ops/ms
ClientGrpc.getUser                         thrpt       3   9.982 ± 2.306  ops/ms
ClientGrpc.listUser                        thrpt       3   7.858 ± 1.177  ops/ms
ClientGrpc.createUser                       avgt       3   3.170 ± 0.301   ms/op
ClientGrpc.existUser                        avgt       3   3.056 ± 0.490   ms/op
ClientGrpc.getUser                          avgt       3   3.205 ± 0.052   ms/op
ClientGrpc.listUser                         avgt       3   4.016 ± 2.565   ms/op
ClientGrpc.createUser                     sample  299633   3.204 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.518           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.170           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.104           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.908           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.105           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.313           ms/op
ClientGrpc.existUser                      sample  312367   3.071 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.573           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.056           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.644           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.606           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.760           ms/op
ClientGrpc.getUser                        sample  302933   3.170 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.700           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.035           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.045           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.573           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.859           ms/op
ClientGrpc.listUser                       sample  235540   4.077 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.141           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.168           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.401           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.284           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.359           ms/op
