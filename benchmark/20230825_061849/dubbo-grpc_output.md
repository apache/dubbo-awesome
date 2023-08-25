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
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 5.075 ops/ms
# Warmup Iteration   3: 6.798 ops/ms
Iteration   1: 7.366 ops/ms
Iteration   2: 7.293 ops/ms
Iteration   3: 7.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.310 ±(99.9%) 0.898 ops/ms [Average]
  (min, avg, max) = (7.272, 7.310, 7.366), stdev = 0.049
  CI (99.9%): [6.413, 8.208] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.817 ops/ms
# Warmup Iteration   2: 7.084 ops/ms
# Warmup Iteration   3: 7.694 ops/ms
Iteration   1: 7.783 ops/ms
Iteration   2: 7.818 ops/ms
Iteration   3: 7.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.786 ±(99.9%) 0.561 ops/ms [Average]
  (min, avg, max) = (7.757, 7.786, 7.818), stdev = 0.031
  CI (99.9%): [7.226, 8.347] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.983 ops/ms
# Warmup Iteration   2: 6.812 ops/ms
# Warmup Iteration   3: 7.155 ops/ms
Iteration   1: 7.464 ops/ms
Iteration   2: 7.416 ops/ms
Iteration   3: 7.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.451 ±(99.9%) 0.554 ops/ms [Average]
  (min, avg, max) = (7.416, 7.451, 7.472), stdev = 0.030
  CI (99.9%): [6.897, 8.004] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.578 ops/ms
# Warmup Iteration   2: 5.350 ops/ms
# Warmup Iteration   3: 5.746 ops/ms
Iteration   1: 5.848 ops/ms
Iteration   2: 5.814 ops/ms
Iteration   3: 5.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.814 ±(99.9%) 0.611 ops/ms [Average]
  (min, avg, max) = (5.781, 5.814, 5.848), stdev = 0.034
  CI (99.9%): [5.203, 6.426] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.171 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.606 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.434 ±(99.9%) 0.003 ms/op
Iteration   1: 4.326 ±(99.9%) 0.003 ms/op
Iteration   2: 4.250 ±(99.9%) 0.003 ms/op
Iteration   3: 4.351 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.309 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (4.250, 4.309, 4.351), stdev = 0.052
  CI (99.9%): [3.354, 5.264] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.993 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.003 ms/op
Iteration   1: 4.150 ±(99.9%) 0.006 ms/op
Iteration   2: 4.049 ±(99.9%) 0.004 ms/op
Iteration   3: 4.002 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.067 ±(99.9%) 1.377 ms/op [Average]
  (min, avg, max) = (4.002, 4.067, 4.150), stdev = 0.075
  CI (99.9%): [2.690, 5.444] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.605 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.551 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.464 ±(99.9%) 0.003 ms/op
Iteration   1: 4.279 ±(99.9%) 0.004 ms/op
Iteration   2: 4.394 ±(99.9%) 0.003 ms/op
Iteration   3: 4.300 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.324 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (4.279, 4.324, 4.394), stdev = 0.061
  CI (99.9%): [3.207, 5.441] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.821 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 6.061 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.581 ±(99.9%) 0.015 ms/op
Iteration   1: 5.454 ±(99.9%) 0.016 ms/op
Iteration   2: 5.313 ±(99.9%) 0.011 ms/op
Iteration   3: 5.297 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.354 ±(99.9%) 1.577 ms/op [Average]
  (min, avg, max) = (5.297, 5.354, 5.454), stdev = 0.086
  CI (99.9%): [3.777, 6.932] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.422 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.790 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.449 ±(99.9%) 0.014 ms/op
Iteration   1: 4.333 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  13.422 ms/op
                 createUser·p0.9999: 15.411 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   2: 4.410 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   7.944 ms/op
                 createUser·p0.999:  12.812 ms/op
                 createUser·p0.9999: 19.726 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   3: 4.353 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.554 ms/op
                 createUser·p0.95:   6.087 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  12.912 ms/op
                 createUser·p0.9999: 19.617 ms/op
                 createUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219877
  mean =      4.365 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5405 
    [ 2.500,  5.000) = 168470 
    [ 5.000,  7.500) = 43292 
    [ 7.500, 10.000) = 2025 
    [10.000, 12.500) = 419 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.054 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     13.224 ms/op
     p(99.9900) =     19.563 ms/op
     p(99.9990) =     20.467 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.245 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.011 ms/op
Iteration   1: 4.048 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   3.944 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  9.896 ms/op
                 existUser·p0.9999: 15.635 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 4.057 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.505 ms/op
                 existUser·p0.99:   6.881 ms/op
                 existUser·p0.999:  10.978 ms/op
                 existUser·p0.9999: 18.754 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   3: 4.075 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.977 ms/op
                 existUser·p0.90:   5.104 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  13.387 ms/op
                 existUser·p0.9999: 21.342 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236392
  mean =      4.060 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7855 
    [ 2.500,  5.000) = 201734 
    [ 5.000,  7.500) = 25272 
    [ 7.500, 10.000) = 1124 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     12.275 ms/op
     p(99.9900) =     20.429 ms/op
     p(99.9990) =     21.621 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.872 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.348 ±(99.9%) 0.013 ms/op
Iteration   1: 4.433 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.685 ms/op
                 getUser·p0.95:   6.185 ms/op
                 getUser·p0.99:   8.118 ms/op
                 getUser·p0.999:  14.364 ms/op
                 getUser·p0.9999: 16.403 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 4.332 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   7.075 ms/op
                 getUser·p0.999:  11.303 ms/op
                 getUser·p0.9999: 20.684 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   3: 4.364 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  11.911 ms/op
                 getUser·p0.9999: 20.753 ms/op
                 getUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 219238
  mean =      4.376 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5446 
    [ 2.500,  5.000) = 168537 
    [ 5.000,  7.500) = 42980 
    [ 7.500, 10.000) = 1751 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     12.300 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     20.998 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.991 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.952 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.325 ±(99.9%) 0.022 ms/op
Iteration   1: 5.412 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   7.176 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   10.562 ms/op
                 listUser·p0.999:  16.251 ms/op
                 listUser·p0.9999: 24.546 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 5.485 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.804 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.184 ms/op
                 listUser·p0.99:   10.538 ms/op
                 listUser·p0.999:  18.174 ms/op
                 listUser·p0.9999: 26.127 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   3: 5.481 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   8.061 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  22.336 ms/op
                 listUser·p0.9999: 24.838 ms/op
                 listUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175858
  mean =      5.459 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 119 
    [ 2.500,  5.000) = 74316 
    [ 5.000,  7.500) = 87619 
    [ 7.500, 10.000) = 11420 
    [10.000, 12.500) = 1679 
    [12.500, 15.000) = 333 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.143 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     19.146 ms/op
     p(99.9900) =     25.253 ms/op
     p(99.9990) =     27.557 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.310 ± 0.898  ops/ms
ClientGrpc.existUser                       thrpt       3   7.786 ± 0.561  ops/ms
ClientGrpc.getUser                         thrpt       3   7.451 ± 0.554  ops/ms
ClientGrpc.listUser                        thrpt       3   5.814 ± 0.611  ops/ms
ClientGrpc.createUser                       avgt       3   4.309 ± 0.955   ms/op
ClientGrpc.existUser                        avgt       3   4.067 ± 1.377   ms/op
ClientGrpc.getUser                          avgt       3   4.324 ± 1.117   ms/op
ClientGrpc.listUser                         avgt       3   5.354 ± 1.577   ms/op
ClientGrpc.createUser                     sample  219877   4.365 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.996           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.546           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.054           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.782           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.224           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.563           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.970           ms/op
ClientGrpc.existUser                      sample  236392   4.060 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.892           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.079           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.505           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.857           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.275           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.429           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.758           ms/op
ClientGrpc.getUser                        sample  219238   4.376 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.079           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.472           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.915           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.553           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.300           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.546           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.070           ms/op
ClientGrpc.listUser                       sample  175858   5.459 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.464           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.126           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.584           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.146           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.253           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.656           ms/op
