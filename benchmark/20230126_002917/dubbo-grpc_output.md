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
# Warmup Iteration   1: 2.216 ops/ms
# Warmup Iteration   2: 5.232 ops/ms
# Warmup Iteration   3: 6.847 ops/ms
Iteration   1: 7.087 ops/ms
Iteration   2: 6.830 ops/ms
Iteration   3: 7.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.034 ±(99.9%) 3.348 ops/ms [Average]
  (min, avg, max) = (6.830, 7.034, 7.186), stdev = 0.183
  CI (99.9%): [3.687, 10.382] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.739 ops/ms
# Warmup Iteration   2: 6.872 ops/ms
# Warmup Iteration   3: 7.190 ops/ms
Iteration   1: 7.619 ops/ms
Iteration   2: 7.327 ops/ms
Iteration   3: 7.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.434 ±(99.9%) 2.937 ops/ms [Average]
  (min, avg, max) = (7.327, 7.434, 7.619), stdev = 0.161
  CI (99.9%): [4.498, 10.371] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.026 ops/ms
# Warmup Iteration   2: 6.620 ops/ms
# Warmup Iteration   3: 6.920 ops/ms
Iteration   1: 6.929 ops/ms
Iteration   2: 6.993 ops/ms
Iteration   3: 6.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.925 ±(99.9%) 1.267 ops/ms [Average]
  (min, avg, max) = (6.854, 6.925, 6.993), stdev = 0.069
  CI (99.9%): [5.659, 8.192] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.753 ops/ms
# Warmup Iteration   2: 4.992 ops/ms
# Warmup Iteration   3: 5.452 ops/ms
Iteration   1: 5.519 ops/ms
Iteration   2: 5.465 ops/ms
Iteration   3: 5.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.550 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (5.465, 5.550, 5.666), stdev = 0.104
  CI (99.9%): [3.653, 7.446] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.539 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.657 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.511 ±(99.9%) 0.003 ms/op
Iteration   1: 4.621 ±(99.9%) 0.004 ms/op
Iteration   2: 4.634 ±(99.9%) 0.004 ms/op
Iteration   3: 4.434 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.563 ±(99.9%) 2.038 ms/op [Average]
  (min, avg, max) = (4.434, 4.563, 4.634), stdev = 0.112
  CI (99.9%): [2.525, 6.601] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.798 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.284 ±(99.9%) 0.003 ms/op
Iteration   1: 4.311 ±(99.9%) 0.004 ms/op
Iteration   2: 4.253 ±(99.9%) 0.003 ms/op
Iteration   3: 4.243 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.269 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (4.243, 4.269, 4.311), stdev = 0.037
  CI (99.9%): [3.598, 4.939] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.097 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.813 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.530 ±(99.9%) 0.004 ms/op
Iteration   1: 4.608 ±(99.9%) 0.004 ms/op
Iteration   2: 4.379 ±(99.9%) 0.003 ms/op
Iteration   3: 4.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.502 ±(99.9%) 2.105 ms/op [Average]
  (min, avg, max) = (4.379, 4.502, 4.608), stdev = 0.115
  CI (99.9%): [2.398, 6.607] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.163 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 6.099 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.289 ±(99.9%) 0.021 ms/op
Iteration   1: 6.088 ±(99.9%) 0.021 ms/op
Iteration   2: 6.112 ±(99.9%) 0.023 ms/op
Iteration   3: 6.119 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.106 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (6.088, 6.106, 6.119), stdev = 0.016
  CI (99.9%): [5.805, 6.407] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.737 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.837 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.541 ±(99.9%) 0.014 ms/op
Iteration   1: 4.458 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   8.309 ms/op
                 createUser·p0.999:  15.159 ms/op
                 createUser·p0.9999: 19.780 ms/op
                 createUser·p1.00:   20.251 ms/op

Iteration   2: 4.604 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.865 ms/op
                 createUser·p0.95:   6.463 ms/op
                 createUser·p0.99:   8.402 ms/op
                 createUser·p0.999:  13.065 ms/op
                 createUser·p0.9999: 20.482 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   3: 4.418 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   5.972 ms/op
                 createUser·p0.99:   8.050 ms/op
                 createUser·p0.999:  12.006 ms/op
                 createUser·p0.9999: 22.160 ms/op
                 createUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 213822
  mean =      4.492 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3308 
    [ 2.500,  5.000) = 164661 
    [ 5.000,  7.500) = 42445 
    [ 7.500, 10.000) = 2596 
    [10.000, 12.500) = 473 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.169 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     13.978 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     25.948 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.488 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.627 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.336 ±(99.9%) 0.014 ms/op
Iteration   1: 4.451 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.620 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   7.774 ms/op
                 existUser·p0.999:  13.625 ms/op
                 existUser·p0.9999: 16.988 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   2: 4.330 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.530 ms/op
                 existUser·p0.95:   5.980 ms/op
                 existUser·p0.99:   8.004 ms/op
                 existUser·p0.999:  12.256 ms/op
                 existUser·p0.9999: 36.937 ms/op
                 existUser·p1.00:   37.552 ms/op

Iteration   3: 4.402 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   4.325 ms/op
                 existUser·p0.90:   5.579 ms/op
                 existUser·p0.95:   6.021 ms/op
                 existUser·p0.99:   8.389 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 23.313 ms/op
                 existUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 218458
  mean =      4.394 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6679 
    [ 2.500,  5.000) = 159737 
    [ 5.000,  7.500) = 49009 
    [ 7.500, 10.000) = 2390 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     34.482 ms/op
     p(99.9990) =     37.474 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.343 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.135 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.658 ±(99.9%) 0.015 ms/op
Iteration   1: 4.574 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   5.759 ms/op
                 getUser·p0.95:   6.373 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  12.456 ms/op
                 getUser·p0.9999: 21.366 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 4.684 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   4.506 ms/op
                 getUser·p0.90:   5.898 ms/op
                 getUser·p0.95:   6.504 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  14.416 ms/op
                 getUser·p0.9999: 24.871 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   3: 4.678 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   5.906 ms/op
                 getUser·p0.95:   6.423 ms/op
                 getUser·p0.99:   8.331 ms/op
                 getUser·p0.999:  18.039 ms/op
                 getUser·p0.9999: 26.056 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 206560
  mean =      4.645 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3259 
    [ 2.500,  5.000) = 144588 
    [ 5.000,  7.500) = 54894 
    [ 7.500, 10.000) = 2823 
    [10.000, 12.500) = 678 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.431 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     25.527 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.555 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.634 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 6.320 ±(99.9%) 0.026 ms/op
Iteration   1: 6.357 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.751 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   8.741 ms/op
                 listUser·p0.95:   9.814 ms/op
                 listUser·p0.99:   12.206 ms/op
                 listUser·p0.999:  17.937 ms/op
                 listUser·p0.9999: 21.396 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 6.100 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   9.617 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  19.661 ms/op
                 listUser·p0.9999: 25.477 ms/op
                 listUser·p1.00:   29.393 ms/op

Iteration   3: 6.250 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   11.649 ms/op
                 listUser·p0.999:  19.022 ms/op
                 listUser·p0.9999: 26.444 ms/op
                 listUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 153951
  mean =      6.234 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 37365 
    [ 5.000,  7.500) = 85836 
    [ 7.500, 10.000) = 24733 
    [10.000, 12.500) = 4845 
    [12.500, 15.000) = 725 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      5.816 ms/op
     p(90.0000) =      8.618 ms/op
     p(95.0000) =      9.650 ms/op
     p(99.0000) =     11.944 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     28.314 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.034 ± 3.348  ops/ms
ClientGrpc.existUser                       thrpt       3   7.434 ± 2.937  ops/ms
ClientGrpc.getUser                         thrpt       3   6.925 ± 1.267  ops/ms
ClientGrpc.listUser                        thrpt       3   5.550 ± 1.896  ops/ms
ClientGrpc.createUser                       avgt       3   4.563 ± 2.038   ms/op
ClientGrpc.existUser                        avgt       3   4.269 ± 0.670   ms/op
ClientGrpc.getUser                          avgt       3   4.502 ± 2.105   ms/op
ClientGrpc.listUser                         avgt       3   6.106 ± 0.301   ms/op
ClientGrpc.createUser                     sample  213822   4.492 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.605           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.603           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.169           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.258           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.978           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.316           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.706           ms/op
ClientGrpc.existUser                      sample  218458   4.394 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.999           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.579           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.021           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.028           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.665           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          34.482           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          37.552           ms/op
ClientGrpc.getUser                        sample  206560   4.645 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.705           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.857           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.431           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.454           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.451           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.527           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.149           ms/op
ClientGrpc.listUser                       sample  153951   6.234 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.491           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.650           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.944           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.169           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.625           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.393           ms/op
