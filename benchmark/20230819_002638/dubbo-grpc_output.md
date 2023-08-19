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
# Warmup Iteration   1: 2.553 ops/ms
# Warmup Iteration   2: 5.858 ops/ms
# Warmup Iteration   3: 7.432 ops/ms
Iteration   1: 7.849 ops/ms
Iteration   2: 7.838 ops/ms
Iteration   3: 7.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.888 ±(99.9%) 1.401 ops/ms [Average]
  (min, avg, max) = (7.838, 7.888, 7.976), stdev = 0.077
  CI (99.9%): [6.486, 9.289] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.070 ops/ms
# Warmup Iteration   2: 7.423 ops/ms
# Warmup Iteration   3: 8.036 ops/ms
Iteration   1: 8.211 ops/ms
Iteration   2: 8.385 ops/ms
Iteration   3: 8.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.328 ±(99.9%) 1.860 ops/ms [Average]
  (min, avg, max) = (8.211, 8.328, 8.389), stdev = 0.102
  CI (99.9%): [6.468, 10.189] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.768 ops/ms
# Warmup Iteration   2: 7.358 ops/ms
# Warmup Iteration   3: 7.820 ops/ms
Iteration   1: 8.035 ops/ms
Iteration   2: 8.488 ops/ms
Iteration   3: 8.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.448 ±(99.9%) 7.201 ops/ms [Average]
  (min, avg, max) = (8.035, 8.448, 8.822), stdev = 0.395
  CI (99.9%): [1.247, 15.650] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.248 ops/ms
# Warmup Iteration   2: 6.011 ops/ms
# Warmup Iteration   3: 6.466 ops/ms
Iteration   1: 6.278 ops/ms
Iteration   2: 6.673 ops/ms
Iteration   3: 6.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.525 ±(99.9%) 3.922 ops/ms [Average]
  (min, avg, max) = (6.278, 6.525, 6.673), stdev = 0.215
  CI (99.9%): [2.603, 10.447] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.890 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.015 ms/op
Iteration   1: 3.869 ±(99.9%) 0.003 ms/op
Iteration   2: 3.677 ±(99.9%) 0.003 ms/op
Iteration   3: 3.850 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.799 ±(99.9%) 1.928 ms/op [Average]
  (min, avg, max) = (3.677, 3.799, 3.869), stdev = 0.106
  CI (99.9%): [1.870, 5.727] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.991 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.003 ms/op
Iteration   1: 3.361 ±(99.9%) 0.002 ms/op
Iteration   2: 3.489 ±(99.9%) 0.001 ms/op
Iteration   3: 3.640 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.497 ±(99.9%) 2.544 ms/op [Average]
  (min, avg, max) = (3.361, 3.497, 3.640), stdev = 0.139
  CI (99.9%): [0.952, 6.041] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.459 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.002 ms/op
Iteration   1: 3.698 ±(99.9%) 0.002 ms/op
Iteration   2: 3.884 ±(99.9%) 0.003 ms/op
Iteration   3: 3.765 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.783 ±(99.9%) 1.717 ms/op [Average]
  (min, avg, max) = (3.698, 3.783, 3.884), stdev = 0.094
  CI (99.9%): [2.065, 5.500] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.887 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.465 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.903 ±(99.9%) 0.023 ms/op
Iteration   1: 4.944 ±(99.9%) 0.016 ms/op
Iteration   2: 4.985 ±(99.9%) 0.015 ms/op
Iteration   3: 4.858 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.929 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (4.858, 4.929, 4.985), stdev = 0.065
  CI (99.9%): [3.747, 6.111] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.573 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.010 ms/op
Iteration   1: 3.804 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.375 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  9.637 ms/op
                 createUser·p0.9999: 16.000 ms/op
                 createUser·p1.00:   16.450 ms/op

Iteration   2: 3.595 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  13.137 ms/op
                 createUser·p0.9999: 15.866 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 3.508 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  10.125 ms/op
                 createUser·p0.9999: 20.607 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264409
  mean =      3.632 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7912 
    [ 2.500,  5.000) = 245158 
    [ 5.000,  7.500) = 10323 
    [ 7.500, 10.000) = 719 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     20.171 ms/op
     p(99.9990) =     21.379 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.778 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.009 ms/op
Iteration   1: 3.351 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  9.266 ms/op
                 existUser·p0.9999: 15.232 ms/op
                 existUser·p1.00:   16.220 ms/op

Iteration   2: 3.325 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.607 ms/op
                 existUser·p0.999:  9.049 ms/op
                 existUser·p0.9999: 21.573 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   3: 3.319 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   5.625 ms/op
                 existUser·p0.999:  10.650 ms/op
                 existUser·p0.9999: 17.138 ms/op
                 existUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 288114
  mean =      3.332 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19199 
    [ 2.500,  5.000) = 262598 
    [ 5.000,  7.500) = 5485 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     20.224 ms/op
     p(99.9990) =     22.192 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.000 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.722 ±(99.9%) 0.011 ms/op
Iteration   1: 3.536 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 17.236 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 3.633 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  11.714 ms/op
                 getUser·p0.9999: 27.407 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   3: 3.740 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  11.349 ms/op
                 getUser·p0.9999: 26.196 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264111
  mean =      3.634 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7075 
    [ 2.500,  5.000) = 247243 
    [ 5.000,  7.500) = 8655 
    [ 7.500, 10.000) = 820 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     10.630 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     27.799 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 6.799 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.264 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.016 ±(99.9%) 0.017 ms/op
Iteration   1: 4.956 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.764 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.652 ms/op
                 listUser·p0.95:   7.586 ms/op
                 listUser·p0.99:   9.929 ms/op
                 listUser·p0.999:  15.524 ms/op
                 listUser·p0.9999: 24.225 ms/op
                 listUser·p1.00:   37.880 ms/op

Iteration   2: 4.921 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.242 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  19.137 ms/op
                 listUser·p0.9999: 25.182 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   3: 5.018 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   6.316 ms/op
                 listUser·p0.95:   7.274 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  21.955 ms/op
                 listUser·p0.9999: 35.693 ms/op
                 listUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 193233
  mean =      4.965 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 451 
    [ 2.500,  5.000) = 120730 
    [ 5.000,  7.500) = 63502 
    [ 7.500, 10.000) = 7001 
    [10.000, 12.500) = 933 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     35.172 ms/op
     p(99.9990) =     36.230 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.888 ± 1.401  ops/ms
ClientGrpc.existUser                       thrpt       3   8.328 ± 1.860  ops/ms
ClientGrpc.getUser                         thrpt       3   8.448 ± 7.201  ops/ms
ClientGrpc.listUser                        thrpt       3   6.525 ± 3.922  ops/ms
ClientGrpc.createUser                       avgt       3   3.799 ± 1.928   ms/op
ClientGrpc.existUser                        avgt       3   3.497 ± 2.544   ms/op
ClientGrpc.getUser                          avgt       3   3.783 ± 1.717   ms/op
ClientGrpc.listUser                         avgt       3   4.929 ± 1.182   ms/op
ClientGrpc.createUser                     sample  264409   3.632 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.375           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.907           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.136           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.715           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.171           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.594           ms/op
ClientGrpc.existUser                      sample  288114   3.332 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.592           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.244           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.677           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.372           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.224           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.282           ms/op
ClientGrpc.getUser                        sample  264111   3.634 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.731           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.160           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.630           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.903           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.886           ms/op
ClientGrpc.listUser                       sample  193233   4.965 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.764           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.406           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.348           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.585           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.923           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.172           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.880           ms/op
