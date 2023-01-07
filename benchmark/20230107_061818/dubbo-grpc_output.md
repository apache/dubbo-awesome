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
# Warmup Iteration   1: 3.624 ops/ms
# Warmup Iteration   2: 7.809 ops/ms
# Warmup Iteration   3: 9.707 ops/ms
Iteration   1: 10.173 ops/ms
Iteration   2: 9.746 ops/ms
Iteration   3: 10.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.978 ±(99.9%) 3.939 ops/ms [Average]
  (min, avg, max) = (9.746, 9.978, 10.173), stdev = 0.216
  CI (99.9%): [6.040, 13.917] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.902 ops/ms
# Warmup Iteration   2: 10.157 ops/ms
# Warmup Iteration   3: 10.391 ops/ms
Iteration   1: 10.356 ops/ms
Iteration   2: 10.574 ops/ms
Iteration   3: 10.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.418 ±(99.9%) 2.475 ops/ms [Average]
  (min, avg, max) = (10.325, 10.418, 10.574), stdev = 0.136
  CI (99.9%): [7.943, 12.894] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.500 ops/ms
# Warmup Iteration   2: 9.798 ops/ms
# Warmup Iteration   3: 10.229 ops/ms
Iteration   1: 10.127 ops/ms
Iteration   2: 10.030 ops/ms
Iteration   3: 9.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.016 ±(99.9%) 2.159 ops/ms [Average]
  (min, avg, max) = (9.892, 10.016, 10.127), stdev = 0.118
  CI (99.9%): [7.857, 12.175] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.210 ops/ms
# Warmup Iteration   2: 7.347 ops/ms
# Warmup Iteration   3: 7.832 ops/ms
Iteration   1: 7.554 ops/ms
Iteration   2: 7.569 ops/ms
Iteration   3: 7.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.592 ±(99.9%) 0.976 ops/ms [Average]
  (min, avg, max) = (7.554, 7.592, 7.653), stdev = 0.054
  CI (99.9%): [6.615, 8.568] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.689 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.002 ms/op
Iteration   1: 3.177 ±(99.9%) 0.003 ms/op
Iteration   2: 3.201 ±(99.9%) 0.002 ms/op
Iteration   3: 3.181 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.187 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (3.177, 3.187, 3.201), stdev = 0.013
  CI (99.9%): [2.955, 3.418] (assumes normal distribution)


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.002 ms/op
Iteration   1: 3.097 ±(99.9%) 0.002 ms/op
Iteration   2: 3.183 ±(99.9%) 0.002 ms/op
Iteration   3: 3.215 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.165 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.097, 3.165, 3.215), stdev = 0.061
  CI (99.9%): [2.053, 4.277] (assumes normal distribution)


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.002 ms/op
Iteration   1: 3.207 ±(99.9%) 0.003 ms/op
Iteration   2: 3.200 ±(99.9%) 0.003 ms/op
Iteration   3: 3.233 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.214 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (3.200, 3.214, 3.233), stdev = 0.017
  CI (99.9%): [2.895, 3.532] (assumes normal distribution)


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
# Warmup Iteration   1: 4.806 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.021 ms/op
Iteration   1: 4.101 ±(99.9%) 0.007 ms/op
Iteration   2: 4.099 ±(99.9%) 0.025 ms/op
Iteration   3: 4.198 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.133 ±(99.9%) 1.032 ms/op [Average]
  (min, avg, max) = (4.099, 4.133, 4.198), stdev = 0.057
  CI (99.9%): [3.101, 5.165] (assumes normal distribution)


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.007 ms/op
Iteration   1: 3.236 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  7.136 ms/op
                 createUser·p0.9999: 13.735 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 3.254 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  9.939 ms/op
                 createUser·p0.9999: 15.109 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   3: 3.246 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 19.371 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295961
  mean =      3.245 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 368 
    [ 1.250,  2.500) = 15927 
    [ 2.500,  3.750) = 231192 
    [ 3.750,  5.000) = 47000 
    [ 5.000,  6.250) = 923 
    [ 6.250,  7.500) = 136 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     18.409 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.354 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
Iteration   1: 3.087 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  8.661 ms/op
                 existUser·p0.9999: 14.389 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.380 ms/op
                 existUser·p0.9999: 17.160 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 3.179 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  11.803 ms/op
                 existUser·p0.9999: 20.673 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 307412
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34037 
    [ 2.500,  5.000) = 272213 
    [ 5.000,  7.500) = 679 
    [ 7.500, 10.000) = 211 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     18.645 ms/op
     p(99.9990) =     21.226 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 4.574 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
Iteration   1: 3.230 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  7.395 ms/op
                 getUser·p0.9999: 20.879 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.052 ms/op
                 getUser·p0.9999: 23.068 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.996 ms/op
                 getUser·p0.9999: 24.347 ms/op
                 getUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298786
  mean =      3.213 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17364 
    [ 2.500,  5.000) = 280129 
    [ 5.000,  7.500) = 924 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.792 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     25.790 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 5.996 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.012 ms/op
Iteration   1: 4.161 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  14.353 ms/op
                 listUser·p0.9999: 15.815 ms/op
                 listUser·p1.00:   16.318 ms/op

Iteration   2: 4.139 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.374 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  15.404 ms/op
                 listUser·p0.9999: 24.978 ms/op
                 listUser·p1.00:   26.247 ms/op

Iteration   3: 4.049 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.044 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 25.330 ms/op
                 listUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233390
  mean =      4.116 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1990 
    [ 2.500,  5.000) = 200288 
    [ 5.000,  7.500) = 29361 
    [ 7.500, 10.000) = 1311 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     14.870 ms/op
     p(99.9900) =     25.122 ms/op
     p(99.9990) =     26.203 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.978 ± 3.939  ops/ms
ClientGrpc.existUser                       thrpt       3  10.418 ± 2.475  ops/ms
ClientGrpc.getUser                         thrpt       3  10.016 ± 2.159  ops/ms
ClientGrpc.listUser                        thrpt       3   7.592 ± 0.976  ops/ms
ClientGrpc.createUser                       avgt       3   3.187 ± 0.232   ms/op
ClientGrpc.existUser                        avgt       3   3.165 ± 1.112   ms/op
ClientGrpc.getUser                          avgt       3   3.214 ± 0.319   ms/op
ClientGrpc.listUser                         avgt       3   4.133 ± 1.032   ms/op
ClientGrpc.createUser                     sample  295961   3.245 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.857           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.219           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.121           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.471           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.409           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.431           ms/op
ClientGrpc.existUser                      sample  307412   3.122 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.627           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.113           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.022           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.929           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.645           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.332           ms/op
ClientGrpc.getUser                        sample  298786   3.213 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.700           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.187           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.792           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.757           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.985           ms/op
ClientGrpc.listUser                       sample  233390   4.116 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.374           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.870           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.122           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.968           ms/op
