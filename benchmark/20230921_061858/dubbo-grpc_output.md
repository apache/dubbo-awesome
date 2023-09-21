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
# Warmup Iteration   1: 4.503 ops/ms
# Warmup Iteration   2: 9.129 ops/ms
# Warmup Iteration   3: 10.067 ops/ms
Iteration   1: 10.387 ops/ms
Iteration   2: 10.240 ops/ms
Iteration   3: 10.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.264 ±(99.9%) 2.051 ops/ms [Average]
  (min, avg, max) = (10.166, 10.264, 10.387), stdev = 0.112
  CI (99.9%): [8.214, 12.315] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.468 ops/ms
# Warmup Iteration   2: 10.529 ops/ms
# Warmup Iteration   3: 11.043 ops/ms
Iteration   1: 10.920 ops/ms
Iteration   2: 10.826 ops/ms
Iteration   3: 11.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.989 ±(99.9%) 3.738 ops/ms [Average]
  (min, avg, max) = (10.826, 10.989, 11.219), stdev = 0.205
  CI (99.9%): [7.250, 14.727] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.389 ops/ms
# Warmup Iteration   2: 10.226 ops/ms
# Warmup Iteration   3: 10.254 ops/ms
Iteration   1: 10.318 ops/ms
Iteration   2: 10.002 ops/ms
Iteration   3: 10.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.206 ±(99.9%) 3.232 ops/ms [Average]
  (min, avg, max) = (10.002, 10.206, 10.318), stdev = 0.177
  CI (99.9%): [6.974, 13.438] (assumes normal distribution)


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
# Warmup Iteration   1: 5.533 ops/ms
# Warmup Iteration   2: 7.821 ops/ms
# Warmup Iteration   3: 7.879 ops/ms
Iteration   1: 8.102 ops/ms
Iteration   2: 8.148 ops/ms
Iteration   3: 8.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.151 ±(99.9%) 0.940 ops/ms [Average]
  (min, avg, max) = (8.102, 8.151, 8.205), stdev = 0.052
  CI (99.9%): [7.211, 9.091] (assumes normal distribution)


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.019 ms/op
Iteration   1: 3.213 ±(99.9%) 0.002 ms/op
Iteration   2: 3.163 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.185 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.163, 3.185, 3.213), stdev = 0.026
  CI (99.9%): [2.717, 3.653] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.618 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.002 ms/op
Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
Iteration   3: 2.935 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.021 ±(99.9%) 1.419 ms/op [Average]
  (min, avg, max) = (2.935, 3.021, 3.086), stdev = 0.078
  CI (99.9%): [1.602, 4.440] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.002 ms/op
Iteration   1: 3.178 ±(99.9%) 0.002 ms/op
Iteration   2: 3.148 ±(99.9%) 0.002 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.130 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.063, 3.130, 3.178), stdev = 0.060
  CI (99.9%): [2.042, 4.218] (assumes normal distribution)


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
# Warmup Iteration   1: 5.374 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.013 ms/op
Iteration   1: 3.941 ±(99.9%) 0.026 ms/op
Iteration   2: 3.905 ±(99.9%) 0.017 ms/op
Iteration   3: 3.947 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.931 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (3.905, 3.931, 3.947), stdev = 0.023
  CI (99.9%): [3.515, 4.348] (assumes normal distribution)


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.007 ms/op
Iteration   1: 3.097 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  8.294 ms/op
                 createUser·p0.9999: 14.336 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  7.685 ms/op
                 createUser·p0.9999: 17.550 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  9.724 ms/op
                 createUser·p0.9999: 22.311 ms/op
                 createUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306657
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12160 
    [ 2.500,  5.000) = 292562 
    [ 5.000,  7.500) = 1500 
    [ 7.500, 10.000) = 170 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     22.477 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 3.669 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.011 ms/op
                 existUser·p0.9999: 10.725 ms/op
                 existUser·p1.00:   11.108 ms/op

Iteration   2: 2.945 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  6.565 ms/op
                 existUser·p0.9999: 13.308 ms/op
                 existUser·p1.00:   13.664 ms/op

Iteration   3: 2.901 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.360 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  9.137 ms/op
                 existUser·p0.9999: 13.844 ms/op
                 existUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326939
  mean =      2.936 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2465 
    [ 1.250,  2.500) = 30998 
    [ 2.500,  3.750) = 281678 
    [ 3.750,  5.000) = 10139 
    [ 5.000,  6.250) = 910 
    [ 6.250,  7.500) = 329 
    [ 7.500,  8.750) = 145 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.275 ms/op
     p(99.9900) =     13.374 ms/op
     p(99.9990) =     15.248 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.006 ms/op
Iteration   1: 3.084 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.004 ms/op
                 getUser·p0.9999: 17.343 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.594 ms/op
                 getUser·p0.9999: 21.665 ms/op
                 getUser·p1.00:   21.922 ms/op

Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.273 ms/op
                 getUser·p0.9999: 20.503 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309492
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11421 
    [ 2.500,  5.000) = 296183 
    [ 5.000,  7.500) = 1570 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     21.916 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 4.204 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.009 ms/op
Iteration   1: 4.005 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  12.684 ms/op
                 listUser·p0.9999: 17.892 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 3.848 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  13.107 ms/op
                 listUser·p0.9999: 15.108 ms/op
                 listUser·p1.00:   15.647 ms/op

Iteration   3: 3.841 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.509 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  13.512 ms/op
                 listUser·p0.9999: 16.395 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246226
  mean =      3.896 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2417 
    [ 2.500,  5.000) = 229895 
    [ 5.000,  7.500) = 12454 
    [ 7.500, 10.000) = 959 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     13.022 ms/op
     p(99.9900) =     16.986 ms/op
     p(99.9990) =     20.477 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.264 ± 2.051  ops/ms
ClientGrpc.existUser                       thrpt       3  10.989 ± 3.738  ops/ms
ClientGrpc.getUser                         thrpt       3  10.206 ± 3.232  ops/ms
ClientGrpc.listUser                        thrpt       3   8.151 ± 0.940  ops/ms
ClientGrpc.createUser                       avgt       3   3.185 ± 0.468   ms/op
ClientGrpc.existUser                        avgt       3   3.021 ± 1.419   ms/op
ClientGrpc.getUser                          avgt       3   3.130 ± 1.088   ms/op
ClientGrpc.listUser                         avgt       3   3.931 ± 0.417   ms/op
ClientGrpc.createUser                     sample  306657   3.129 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.834           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.241           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.823           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.544           ms/op
ClientGrpc.existUser                      sample  326939   2.936 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.360           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.275           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.374           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.352           ms/op
ClientGrpc.getUser                        sample  309492   3.100 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.599           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.545           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.513           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.922           ms/op
ClientGrpc.listUser                       sample  246226   3.896 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.362           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.375           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.022           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.986           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.955           ms/op
