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
# Warmup Iteration   1: 4.414 ops/ms
# Warmup Iteration   2: 9.023 ops/ms
# Warmup Iteration   3: 9.939 ops/ms
Iteration   1: 10.322 ops/ms
Iteration   2: 10.169 ops/ms
Iteration   3: 10.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.265 ±(99.9%) 1.529 ops/ms [Average]
  (min, avg, max) = (10.169, 10.265, 10.322), stdev = 0.084
  CI (99.9%): [8.736, 11.794] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.874 ops/ms
# Warmup Iteration   2: 10.259 ops/ms
# Warmup Iteration   3: 10.940 ops/ms
Iteration   1: 11.051 ops/ms
Iteration   2: 10.938 ops/ms
Iteration   3: 10.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.945 ±(99.9%) 1.868 ops/ms [Average]
  (min, avg, max) = (10.846, 10.945, 11.051), stdev = 0.102
  CI (99.9%): [9.077, 12.813] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.577 ops/ms
# Warmup Iteration   2: 9.941 ops/ms
# Warmup Iteration   3: 10.030 ops/ms
Iteration   1: 10.284 ops/ms
Iteration   2: 10.537 ops/ms
Iteration   3: 10.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.409 ±(99.9%) 2.307 ops/ms [Average]
  (min, avg, max) = (10.284, 10.409, 10.537), stdev = 0.126
  CI (99.9%): [8.102, 12.716] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.560 ops/ms
# Warmup Iteration   2: 8.183 ops/ms
# Warmup Iteration   3: 8.293 ops/ms
Iteration   1: 8.237 ops/ms
Iteration   2: 8.372 ops/ms
Iteration   3: 8.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.332 ±(99.9%) 1.509 ops/ms [Average]
  (min, avg, max) = (8.237, 8.332, 8.387), stdev = 0.083
  CI (99.9%): [6.823, 9.841] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.129 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.003 ms/op
Iteration   1: 3.111 ±(99.9%) 0.003 ms/op
Iteration   2: 3.128 ±(99.9%) 0.003 ms/op
Iteration   3: 3.081 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.106 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (3.081, 3.106, 3.128), stdev = 0.024
  CI (99.9%): [2.674, 3.539] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.540 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.005 ms/op
Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
Iteration   3: 2.933 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.987 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (2.933, 2.987, 3.016), stdev = 0.047
  CI (99.9%): [2.135, 3.838] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.083 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.005 ms/op
Iteration   1: 3.073 ±(99.9%) 0.002 ms/op
Iteration   2: 3.094 ±(99.9%) 0.004 ms/op
Iteration   3: 3.074 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.080 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (3.073, 3.080, 3.094), stdev = 0.012
  CI (99.9%): [2.865, 3.296] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.307 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.014 ms/op
Iteration   1: 3.843 ±(99.9%) 0.016 ms/op
Iteration   2: 3.799 ±(99.9%) 0.028 ms/op
Iteration   3: 3.877 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.839 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (3.799, 3.839, 3.877), stdev = 0.039
  CI (99.9%): [3.124, 4.555] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.027 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.008 ms/op
Iteration   1: 3.043 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  13.431 ms/op
                 createUser·p0.9999: 17.187 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.335 ms/op
                 createUser·p0.999:  8.615 ms/op
                 createUser·p0.9999: 15.715 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.607 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  11.412 ms/op
                 createUser·p0.9999: 19.912 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311000
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14825 
    [ 2.500,  5.000) = 294319 
    [ 5.000,  7.500) = 1121 
    [ 7.500, 10.000) = 391 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     20.116 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
Iteration   1: 2.921 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.189 ms/op
                 existUser·p0.9999: 15.879 ms/op
                 existUser·p1.00:   16.499 ms/op

Iteration   2: 2.913 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  10.338 ms/op
                 existUser·p0.9999: 22.151 ms/op
                 existUser·p1.00:   32.014 ms/op

Iteration   3: 2.894 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  8.634 ms/op
                 existUser·p0.9999: 25.199 ms/op
                 existUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329973
  mean =      2.909 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36846 
    [ 2.500,  5.000) = 291633 
    [ 5.000,  7.500) = 1081 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.336 ms/op
     p(99.9000) =      8.184 ms/op
     p(99.9900) =     16.513 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  9.824 ms/op
                 getUser·p0.9999: 15.500 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.419 ms/op
                 getUser·p0.9999: 20.600 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.195 ms/op
                 getUser·p0.9999: 23.810 ms/op
                 getUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311863
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13528 
    [ 2.500,  5.000) = 296864 
    [ 5.000,  7.500) = 1122 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.459 ms/op
     p(99.9900) =     23.128 ms/op
     p(99.9990) =     23.982 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.010 ms/op
Iteration   1: 3.898 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 3.876 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.461 ms/op
                 listUser·p0.9999: 16.663 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 3.843 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  15.573 ms/op
                 listUser·p0.9999: 24.795 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247745
  mean =      3.872 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5486 
    [ 2.500,  5.000) = 225352 
    [ 5.000,  7.500) = 15797 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     14.770 ms/op
     p(99.9900) =     20.389 ms/op
     p(99.9990) =     24.954 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.265 ± 1.529  ops/ms
ClientGrpc.existUser                       thrpt       3  10.945 ± 1.868  ops/ms
ClientGrpc.getUser                         thrpt       3  10.409 ± 2.307  ops/ms
ClientGrpc.listUser                        thrpt       3   8.332 ± 1.509  ops/ms
ClientGrpc.createUser                       avgt       3   3.106 ± 0.432   ms/op
ClientGrpc.existUser                        avgt       3   2.987 ± 0.851   ms/op
ClientGrpc.getUser                          avgt       3   3.080 ± 0.215   ms/op
ClientGrpc.listUser                         avgt       3   3.839 ± 0.716   ms/op
ClientGrpc.createUser                     sample  311000   3.085 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.552           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.239           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.285           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.185           ms/op
ClientGrpc.existUser                      sample  329973   2.909 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.643           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.336           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.184           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.513           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.014           ms/op
ClientGrpc.getUser                        sample  311863   3.079 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.691           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.459           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.128           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.052           ms/op
ClientGrpc.listUser                       sample  247745   3.872 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.005           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.465           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.770           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.389           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
