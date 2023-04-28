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
# Warmup Iteration   1: 4.156 ops/ms
# Warmup Iteration   2: 9.081 ops/ms
# Warmup Iteration   3: 10.169 ops/ms
Iteration   1: 10.589 ops/ms
Iteration   2: 10.607 ops/ms
Iteration   3: 10.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.591 ±(99.9%) 0.287 ops/ms [Average]
  (min, avg, max) = (10.576, 10.591, 10.607), stdev = 0.016
  CI (99.9%): [10.303, 10.878] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.605 ops/ms
# Warmup Iteration   2: 10.489 ops/ms
# Warmup Iteration   3: 11.041 ops/ms
Iteration   1: 11.212 ops/ms
Iteration   2: 11.277 ops/ms
Iteration   3: 11.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.182 ±(99.9%) 2.069 ops/ms [Average]
  (min, avg, max) = (11.056, 11.182, 11.277), stdev = 0.113
  CI (99.9%): [9.113, 13.251] (assumes normal distribution)


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
# Warmup Iteration   1: 6.683 ops/ms
# Warmup Iteration   2: 10.183 ops/ms
# Warmup Iteration   3: 10.566 ops/ms
Iteration   1: 10.654 ops/ms
Iteration   2: 10.650 ops/ms
Iteration   3: 10.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.622 ±(99.9%) 0.948 ops/ms [Average]
  (min, avg, max) = (10.562, 10.622, 10.654), stdev = 0.052
  CI (99.9%): [9.674, 11.570] (assumes normal distribution)


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
# Warmup Iteration   1: 5.392 ops/ms
# Warmup Iteration   2: 7.742 ops/ms
# Warmup Iteration   3: 7.988 ops/ms
Iteration   1: 8.172 ops/ms
Iteration   2: 8.052 ops/ms
Iteration   3: 8.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.078 ±(99.9%) 1.542 ops/ms [Average]
  (min, avg, max) = (8.009, 8.078, 8.172), stdev = 0.085
  CI (99.9%): [6.536, 9.619] (assumes normal distribution)


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
# Warmup Iteration   1: 4.517 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.003 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.018 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (2.979, 3.018, 3.049), stdev = 0.035
  CI (99.9%): [2.374, 3.662] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.002 ms/op
Iteration   1: 2.922 ±(99.9%) 0.002 ms/op
Iteration   2: 2.932 ±(99.9%) 0.002 ms/op
Iteration   3: 2.826 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.893 ±(99.9%) 1.066 ms/op [Average]
  (min, avg, max) = (2.826, 2.893, 2.932), stdev = 0.058
  CI (99.9%): [1.827, 3.960] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.263 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.004 ms/op
Iteration   1: 3.072 ±(99.9%) 0.004 ms/op
Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.054 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.039, 3.054, 3.072), stdev = 0.017
  CI (99.9%): [2.745, 3.363] (assumes normal distribution)


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
# Warmup Iteration   1: 5.278 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.014 ms/op
Iteration   1: 4.039 ±(99.9%) 0.024 ms/op
Iteration   2: 4.039 ±(99.9%) 0.013 ms/op
Iteration   3: 4.028 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.036 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (4.028, 4.036, 4.039), stdev = 0.006
  CI (99.9%): [3.920, 4.151] (assumes normal distribution)


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  7.373 ms/op
                 createUser·p0.9999: 13.043 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.441 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.467 ms/op
                 createUser·p0.999:  7.647 ms/op
                 createUser·p0.9999: 14.074 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  12.531 ms/op
                 createUser·p0.9999: 21.669 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321251
  mean =      2.991 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28261 
    [ 2.500,  5.000) = 291460 
    [ 5.000,  7.500) = 1155 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.441 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.196 ms/op
     p(99.9900) =     20.504 ms/op
     p(99.9990) =     21.941 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  7.050 ms/op
                 existUser·p0.9999: 12.616 ms/op
                 existUser·p1.00:   12.747 ms/op

Iteration   2: 2.980 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.894 ms/op
                 existUser·p0.9999: 14.557 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  7.137 ms/op
                 existUser·p0.9999: 26.083 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323489
  mean =      2.969 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25891 
    [ 2.500,  5.000) = 296478 
    [ 5.000,  7.500) = 903 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      7.037 ms/op
     p(99.9900) =     22.113 ms/op
     p(99.9990) =     26.305 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.864 ms/op
                 getUser·p0.9999: 15.827 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  9.363 ms/op
                 getUser·p0.9999: 17.463 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.708 ms/op
                 getUser·p0.9999: 19.285 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312029
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16898 
    [ 2.500,  5.000) = 293406 
    [ 5.000,  7.500) = 1379 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.676 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     19.362 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 5.543 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.012 ms/op
Iteration   1: 4.081 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.385 ms/op
                 listUser·p0.9999: 17.826 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   2: 3.917 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.811 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 18.541 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 4.097 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  15.252 ms/op
                 listUser·p0.9999: 29.038 ms/op
                 listUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238172
  mean =      4.030 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1880 
    [ 2.500,  5.000) = 211760 
    [ 5.000,  7.500) = 22830 
    [ 7.500, 10.000) = 1234 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     14.431 ms/op
     p(99.9900) =     27.597 ms/op
     p(99.9990) =     29.728 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.591 ± 0.287  ops/ms
ClientGrpc.existUser                       thrpt       3  11.182 ± 2.069  ops/ms
ClientGrpc.getUser                         thrpt       3  10.622 ± 0.948  ops/ms
ClientGrpc.listUser                        thrpt       3   8.078 ± 1.542  ops/ms
ClientGrpc.createUser                       avgt       3   3.018 ± 0.644   ms/op
ClientGrpc.existUser                        avgt       3   2.893 ± 1.066   ms/op
ClientGrpc.getUser                          avgt       3   3.054 ± 0.309   ms/op
ClientGrpc.listUser                         avgt       3   4.036 ± 0.115   ms/op
ClientGrpc.createUser                     sample  321251   2.991 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.441           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.196           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.504           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  323489   2.969 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.767           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.037           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.113           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.508           ms/op
ClientGrpc.getUser                        sample  312029   3.076 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.649           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.676           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.104           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.447           ms/op
ClientGrpc.listUser                       sample  238172   4.030 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.811           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.431           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.597           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.343           ms/op
