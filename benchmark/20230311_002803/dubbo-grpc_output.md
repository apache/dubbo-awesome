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
# Warmup Iteration   1: 3.910 ops/ms
# Warmup Iteration   2: 7.427 ops/ms
# Warmup Iteration   3: 8.742 ops/ms
Iteration   1: 9.219 ops/ms
Iteration   2: 9.274 ops/ms
Iteration   3: 9.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.304 ±(99.9%) 1.886 ops/ms [Average]
  (min, avg, max) = (9.219, 9.304, 9.419), stdev = 0.103
  CI (99.9%): [7.418, 11.190] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.466 ops/ms
# Warmup Iteration   2: 9.139 ops/ms
# Warmup Iteration   3: 9.836 ops/ms
Iteration   1: 9.856 ops/ms
Iteration   2: 9.606 ops/ms
Iteration   3: 9.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.710 ±(99.9%) 2.369 ops/ms [Average]
  (min, avg, max) = (9.606, 9.710, 9.856), stdev = 0.130
  CI (99.9%): [7.342, 12.079] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.285 ops/ms
# Warmup Iteration   2: 8.772 ops/ms
# Warmup Iteration   3: 9.032 ops/ms
Iteration   1: 9.210 ops/ms
Iteration   2: 9.233 ops/ms
Iteration   3: 9.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.229 ±(99.9%) 0.315 ops/ms [Average]
  (min, avg, max) = (9.210, 9.229, 9.244), stdev = 0.017
  CI (99.9%): [8.914, 9.544] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.566 ops/ms
# Warmup Iteration   2: 7.071 ops/ms
# Warmup Iteration   3: 7.015 ops/ms
Iteration   1: 7.083 ops/ms
Iteration   2: 7.118 ops/ms
Iteration   3: 7.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.112 ±(99.9%) 0.476 ops/ms [Average]
  (min, avg, max) = (7.083, 7.112, 7.134), stdev = 0.026
  CI (99.9%): [6.635, 7.588] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.936 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.004 ms/op
Iteration   1: 3.466 ±(99.9%) 0.002 ms/op
Iteration   2: 3.466 ±(99.9%) 0.003 ms/op
Iteration   3: 3.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.460 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (3.448, 3.460, 3.466), stdev = 0.010
  CI (99.9%): [3.277, 3.643] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.615 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.003 ms/op
Iteration   1: 3.335 ±(99.9%) 0.002 ms/op
Iteration   2: 3.312 ±(99.9%) 0.003 ms/op
Iteration   3: 3.358 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.335 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.312, 3.335, 3.358), stdev = 0.023
  CI (99.9%): [2.912, 3.758] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.211 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.004 ms/op
Iteration   1: 3.242 ±(99.9%) 0.003 ms/op
Iteration   2: 3.155 ±(99.9%) 0.004 ms/op
Iteration   3: 3.211 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.203 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (3.155, 3.203, 3.242), stdev = 0.044
  CI (99.9%): [2.397, 4.008] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.794 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.031 ms/op
Iteration   1: 4.134 ±(99.9%) 0.017 ms/op
Iteration   2: 4.199 ±(99.9%) 0.019 ms/op
Iteration   3: 3.978 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.104 ±(99.9%) 2.078 ms/op [Average]
  (min, avg, max) = (3.978, 4.104, 4.199), stdev = 0.114
  CI (99.9%): [2.025, 6.182] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.535 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
Iteration   1: 3.087 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  8.701 ms/op
                 createUser·p0.9999: 17.496 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   2: 3.177 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  7.512 ms/op
                 createUser·p0.9999: 15.971 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   3: 3.402 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  15.118 ms/op
                 createUser·p0.9999: 21.070 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298450
  mean =      3.217 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22680 
    [ 2.500,  5.000) = 273641 
    [ 5.000,  7.500) = 1761 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     19.419 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.607 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.007 ms/op
Iteration   1: 3.314 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  7.884 ms/op
                 existUser·p0.9999: 14.408 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   2: 3.315 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  7.303 ms/op
                 existUser·p0.9999: 20.438 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   3: 3.347 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   4.809 ms/op
                 existUser·p0.999:  10.000 ms/op
                 existUser·p0.9999: 19.970 ms/op
                 existUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 288507
  mean =      3.325 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12183 
    [ 2.500,  5.000) = 274469 
    [ 5.000,  7.500) = 1513 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     20.914 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.334 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.007 ms/op
Iteration   1: 3.486 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  10.127 ms/op
                 getUser·p0.9999: 14.068 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 3.509 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  11.493 ms/op
                 getUser·p0.9999: 17.891 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 3.463 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  7.247 ms/op
                 getUser·p0.9999: 18.466 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 275356
  mean =      3.486 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 8902 
    [ 2.500,  3.750) = 193830 
    [ 3.750,  5.000) = 68733 
    [ 5.000,  6.250) = 2792 
    [ 6.250,  7.500) = 468 
    [ 7.500,  8.750) = 166 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =      8.743 ms/op
     p(99.9900) =     17.907 ms/op
     p(99.9990) =     18.792 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.481 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.880 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.521 ±(99.9%) 0.013 ms/op
Iteration   1: 4.367 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.243 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.291 ms/op
                 listUser·p0.99:   7.913 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 23.560 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 4.539 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.634 ms/op
                 listUser·p0.99:   7.941 ms/op
                 listUser·p0.999:  15.639 ms/op
                 listUser·p0.9999: 23.688 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 4.446 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  21.403 ms/op
                 listUser·p0.9999: 31.877 ms/op
                 listUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 215755
  mean =      4.450 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 992 
    [ 2.500,  5.000) = 180650 
    [ 5.000,  7.500) = 30596 
    [ 7.500, 10.000) = 2997 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.414 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     17.031 ms/op
     p(99.9900) =     30.324 ms/op
     p(99.9990) =     32.097 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.304 ± 1.886  ops/ms
ClientGrpc.existUser                       thrpt       3   9.710 ± 2.369  ops/ms
ClientGrpc.getUser                         thrpt       3   9.229 ± 0.315  ops/ms
ClientGrpc.listUser                        thrpt       3   7.112 ± 0.476  ops/ms
ClientGrpc.createUser                       avgt       3   3.460 ± 0.183   ms/op
ClientGrpc.existUser                        avgt       3   3.335 ± 0.423   ms/op
ClientGrpc.getUser                          avgt       3   3.203 ± 0.805   ms/op
ClientGrpc.listUser                         avgt       3   4.104 ± 2.078   ms/op
ClientGrpc.createUser                     sample  298450   3.217 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.667           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.187           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.667           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.419           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.463           ms/op
ClientGrpc.existUser                      sample  288507   3.325 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.746           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.850           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.719           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.799           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.054           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.004           ms/op
ClientGrpc.getUser                        sample  275356   3.486 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.695           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.071           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.267           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.743           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.907           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.907           ms/op
ClientGrpc.listUser                       sample  215755   4.450 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.913           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.301           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.414           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.031           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.324           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.178           ms/op
