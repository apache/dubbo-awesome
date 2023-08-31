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
# Warmup Iteration   1: 2.152 ops/ms
# Warmup Iteration   2: 5.126 ops/ms
# Warmup Iteration   3: 6.821 ops/ms
Iteration   1: 7.025 ops/ms
Iteration   2: 6.804 ops/ms
Iteration   3: 6.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.882 ±(99.9%) 2.267 ops/ms [Average]
  (min, avg, max) = (6.804, 6.882, 7.025), stdev = 0.124
  CI (99.9%): [4.614, 9.149] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.962 ops/ms
# Warmup Iteration   2: 6.601 ops/ms
# Warmup Iteration   3: 7.184 ops/ms
Iteration   1: 7.371 ops/ms
Iteration   2: 7.492 ops/ms
Iteration   3: 7.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.404 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (7.348, 7.404, 7.492), stdev = 0.078
  CI (99.9%): [5.988, 8.820] (assumes normal distribution)


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
# Warmup Iteration   1: 4.173 ops/ms
# Warmup Iteration   2: 6.678 ops/ms
# Warmup Iteration   3: 7.342 ops/ms
Iteration   1: 7.357 ops/ms
Iteration   2: 7.263 ops/ms
Iteration   3: 7.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.399 ±(99.9%) 2.949 ops/ms [Average]
  (min, avg, max) = (7.263, 7.399, 7.578), stdev = 0.162
  CI (99.9%): [4.450, 10.348] (assumes normal distribution)


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
# Warmup Iteration   1: 3.651 ops/ms
# Warmup Iteration   2: 5.116 ops/ms
# Warmup Iteration   3: 5.636 ops/ms
Iteration   1: 5.752 ops/ms
Iteration   2: 5.468 ops/ms
Iteration   3: 5.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.599 ±(99.9%) 2.614 ops/ms [Average]
  (min, avg, max) = (5.468, 5.599, 5.752), stdev = 0.143
  CI (99.9%): [2.985, 8.213] (assumes normal distribution)


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
# Warmup Iteration   1: 6.873 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.761 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.504 ±(99.9%) 0.006 ms/op
Iteration   1: 4.392 ±(99.9%) 0.003 ms/op
Iteration   2: 4.350 ±(99.9%) 0.002 ms/op
Iteration   3: 4.517 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.419 ±(99.9%) 1.584 ms/op [Average]
  (min, avg, max) = (4.350, 4.419, 4.517), stdev = 0.087
  CI (99.9%): [2.835, 6.004] (assumes normal distribution)


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
# Warmup Iteration   1: 6.442 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.006 ms/op
Iteration   1: 4.102 ±(99.9%) 0.003 ms/op
Iteration   2: 4.136 ±(99.9%) 0.003 ms/op
Iteration   3: 4.309 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.182 ±(99.9%) 2.030 ms/op [Average]
  (min, avg, max) = (4.102, 4.182, 4.309), stdev = 0.111
  CI (99.9%): [2.152, 6.212] (assumes normal distribution)


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
# Warmup Iteration   1: 6.614 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.733 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.476 ±(99.9%) 0.003 ms/op
Iteration   1: 4.334 ±(99.9%) 0.004 ms/op
Iteration   2: 4.411 ±(99.9%) 0.004 ms/op
Iteration   3: 4.284 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.343 ±(99.9%) 1.169 ms/op [Average]
  (min, avg, max) = (4.284, 4.343, 4.411), stdev = 0.064
  CI (99.9%): [3.174, 5.512] (assumes normal distribution)


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
# Warmup Iteration   1: 7.580 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 6.197 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.675 ±(99.9%) 0.011 ms/op
Iteration   1: 5.597 ±(99.9%) 0.026 ms/op
Iteration   2: 5.580 ±(99.9%) 0.013 ms/op
Iteration   3: 5.552 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.576 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (5.552, 5.576, 5.597), stdev = 0.023
  CI (99.9%): [5.164, 5.989] (assumes normal distribution)


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
# Warmup Iteration   1: 6.650 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.775 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.417 ±(99.9%) 0.013 ms/op
Iteration   1: 4.449 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.652 ms/op
                 createUser·p0.95:   6.070 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  12.945 ms/op
                 createUser·p0.9999: 16.090 ms/op
                 createUser·p1.00:   16.531 ms/op

Iteration   2: 4.485 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.554 ms/op
                 createUser·p0.95:   5.964 ms/op
                 createUser·p0.99:   7.806 ms/op
                 createUser·p0.999:  15.560 ms/op
                 createUser·p0.9999: 20.294 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   3: 4.412 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.358 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.497 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   7.455 ms/op
                 createUser·p0.999:  13.763 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215719
  mean =      4.448 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2353 
    [ 2.500,  5.000) = 165007 
    [ 5.000,  7.500) = 46023 
    [ 7.500, 10.000) = 1733 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     14.341 ms/op
     p(99.9900) =     21.950 ms/op
     p(99.9990) =     22.702 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.266 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.455 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.012 ms/op
Iteration   1: 4.123 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   4.006 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.538 ms/op
                 existUser·p0.99:   7.274 ms/op
                 existUser·p0.999:  11.972 ms/op
                 existUser·p0.9999: 19.021 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   2: 4.052 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.432 ms/op
                 existUser·p0.50:   3.944 ms/op
                 existUser·p0.90:   4.989 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   7.036 ms/op
                 existUser·p0.999:  12.370 ms/op
                 existUser·p0.9999: 18.488 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   3: 4.091 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   5.431 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  11.854 ms/op
                 existUser·p0.9999: 19.562 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 234634
  mean =      4.089 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4758 
    [ 2.500,  5.000) = 205235 
    [ 5.000,  7.500) = 22998 
    [ 7.500, 10.000) = 1193 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     12.038 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     19.802 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 6.354 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.567 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.437 ±(99.9%) 0.013 ms/op
Iteration   1: 4.382 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  11.553 ms/op
                 getUser·p0.9999: 21.703 ms/op
                 getUser·p1.00:   22.217 ms/op

Iteration   2: 4.333 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.358 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  10.488 ms/op
                 getUser·p0.9999: 22.368 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   3: 4.193 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   4.108 ms/op
                 getUser·p0.90:   5.259 ms/op
                 getUser·p0.95:   5.734 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  12.968 ms/op
                 getUser·p0.9999: 24.916 ms/op
                 getUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 223256
  mean =      4.301 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5066 
    [ 2.500,  5.000) = 179793 
    [ 5.000,  7.500) = 36556 
    [ 7.500, 10.000) = 1412 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     11.645 ms/op
     p(99.9900) =     24.425 ms/op
     p(99.9990) =     25.332 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 8.230 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.313 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.748 ±(99.9%) 0.022 ms/op
Iteration   1: 5.699 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.793 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.414 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  17.688 ms/op
                 listUser·p0.9999: 20.366 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 5.749 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.506 ms/op
                 listUser·p0.99:   11.007 ms/op
                 listUser·p0.999:  17.540 ms/op
                 listUser·p0.9999: 22.057 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 5.819 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   7.635 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   10.764 ms/op
                 listUser·p0.999:  26.805 ms/op
                 listUser·p0.9999: 30.327 ms/op
                 listUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166886
  mean =      5.755 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 49918 
    [ 5.000,  7.500) = 99750 
    [ 7.500, 10.000) = 14055 
    [10.000, 12.500) = 2331 
    [12.500, 15.000) = 425 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.545 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     18.354 ms/op
     p(99.9900) =     29.927 ms/op
     p(99.9990) =     32.331 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.882 ± 2.267  ops/ms
ClientGrpc.existUser                       thrpt       3   7.404 ± 1.416  ops/ms
ClientGrpc.getUser                         thrpt       3   7.399 ± 2.949  ops/ms
ClientGrpc.listUser                        thrpt       3   5.599 ± 2.614  ops/ms
ClientGrpc.createUser                       avgt       3   4.419 ± 1.584   ms/op
ClientGrpc.existUser                        avgt       3   4.182 ± 2.030   ms/op
ClientGrpc.getUser                          avgt       3   4.343 ± 1.169   ms/op
ClientGrpc.listUser                         avgt       3   5.576 ± 0.413   ms/op
ClientGrpc.createUser                     sample  215719   4.448 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.919           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.997           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.627           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.341           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.950           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.364           ms/op
ClientGrpc.existUser                      sample  234634   4.089 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.432           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.038           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.489           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.988           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.038           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.071           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.709           ms/op
ClientGrpc.getUser                        sample  223256   4.301 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.830           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.366           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.792           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.176           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.645           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.425           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.657           ms/op
ClientGrpc.listUser                       sample  166886   5.755 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.793           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.536           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.961           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.354           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.927           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.375           ms/op
