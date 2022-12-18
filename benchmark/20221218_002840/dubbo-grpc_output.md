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
# Warmup Iteration   1: 2.197 ops/ms
# Warmup Iteration   2: 5.452 ops/ms
# Warmup Iteration   3: 6.737 ops/ms
Iteration   1: 7.062 ops/ms
Iteration   2: 7.000 ops/ms
Iteration   3: 6.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.013 ±(99.9%) 0.798 ops/ms [Average]
  (min, avg, max) = (6.977, 7.013, 7.062), stdev = 0.044
  CI (99.9%): [6.215, 7.811] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.004 ops/ms
# Warmup Iteration   2: 6.600 ops/ms
# Warmup Iteration   3: 7.011 ops/ms
Iteration   1: 7.563 ops/ms
Iteration   2: 7.362 ops/ms
Iteration   3: 7.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.471 ±(99.9%) 1.851 ops/ms [Average]
  (min, avg, max) = (7.362, 7.471, 7.563), stdev = 0.101
  CI (99.9%): [5.619, 9.322] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.377 ops/ms
# Warmup Iteration   2: 6.628 ops/ms
# Warmup Iteration   3: 7.149 ops/ms
Iteration   1: 7.017 ops/ms
Iteration   2: 7.070 ops/ms
Iteration   3: 7.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.071 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (7.017, 7.071, 7.124), stdev = 0.053
  CI (99.9%): [6.101, 8.040] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ops/ms
# Warmup Iteration   2: 5.002 ops/ms
# Warmup Iteration   3: 5.535 ops/ms
Iteration   1: 5.470 ops/ms
Iteration   2: 5.473 ops/ms
Iteration   3: 5.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.462 ±(99.9%) 0.294 ops/ms [Average]
  (min, avg, max) = (5.444, 5.462, 5.473), stdev = 0.016
  CI (99.9%): [5.168, 5.756] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.737 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.755 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.623 ±(99.9%) 0.004 ms/op
Iteration   1: 4.514 ±(99.9%) 0.004 ms/op
Iteration   2: 4.584 ±(99.9%) 0.003 ms/op
Iteration   3: 4.591 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.563 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (4.514, 4.563, 4.591), stdev = 0.042
  CI (99.9%): [3.790, 5.336] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.288 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.473 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.287 ±(99.9%) 0.004 ms/op
Iteration   1: 4.387 ±(99.9%) 0.003 ms/op
Iteration   2: 4.369 ±(99.9%) 0.003 ms/op
Iteration   3: 4.240 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.332 ±(99.9%) 1.463 ms/op [Average]
  (min, avg, max) = (4.240, 4.332, 4.387), stdev = 0.080
  CI (99.9%): [2.869, 5.795] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.572 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.854 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.571 ±(99.9%) 0.003 ms/op
Iteration   1: 4.375 ±(99.9%) 0.004 ms/op
Iteration   2: 4.504 ±(99.9%) 0.004 ms/op
Iteration   3: 4.446 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.442 ±(99.9%) 1.173 ms/op [Average]
  (min, avg, max) = (4.375, 4.442, 4.504), stdev = 0.064
  CI (99.9%): [3.268, 5.615] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.863 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 6.120 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.814 ±(99.9%) 0.029 ms/op
Iteration   1: 5.776 ±(99.9%) 0.018 ms/op
Iteration   2: 5.675 ±(99.9%) 0.015 ms/op
Iteration   3: 5.681 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.711 ±(99.9%) 1.030 ms/op [Average]
  (min, avg, max) = (5.675, 5.711, 5.776), stdev = 0.056
  CI (99.9%): [4.681, 6.741] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.681 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 4.764 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.429 ±(99.9%) 0.015 ms/op
Iteration   1: 4.514 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.382 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.808 ms/op
                 createUser·p0.95:   6.373 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  11.357 ms/op
                 createUser·p0.9999: 18.279 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   2: 4.504 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.833 ms/op
                 createUser·p0.95:   6.529 ms/op
                 createUser·p0.99:   8.880 ms/op
                 createUser·p0.999:  14.154 ms/op
                 createUser·p0.9999: 17.314 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   3: 4.708 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   4.497 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   6.595 ms/op
                 createUser·p0.99:   9.290 ms/op
                 createUser·p0.999:  18.317 ms/op
                 createUser·p0.9999: 22.100 ms/op
                 createUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 209982
  mean =      4.573 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2548 
    [ 2.500,  5.000) = 148280 
    [ 5.000,  7.500) = 54213 
    [ 7.500, 10.000) = 3818 
    [10.000, 12.500) = 801 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.865 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     23.737 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.702 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.458 ±(99.9%) 0.014 ms/op
Iteration   1: 4.356 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.587 ms/op
                 existUser·p0.95:   6.152 ms/op
                 existUser·p0.99:   8.266 ms/op
                 existUser·p0.999:  10.996 ms/op
                 existUser·p0.9999: 27.262 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   2: 4.248 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   4.141 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   6.005 ms/op
                 existUser·p0.99:   8.233 ms/op
                 existUser·p0.999:  12.736 ms/op
                 existUser·p0.9999: 19.691 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   3: 4.337 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   4.166 ms/op
                 existUser·p0.90:   5.603 ms/op
                 existUser·p0.95:   6.250 ms/op
                 existUser·p0.99:   8.471 ms/op
                 existUser·p0.999:  11.865 ms/op
                 existUser·p0.9999: 23.654 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 222550
  mean =      4.313 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6402 
    [ 2.500,  5.000) = 168838 
    [ 5.000,  7.500) = 43452 
    [ 7.500, 10.000) = 3315 
    [10.000, 12.500) = 386 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      4.178 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      8.331 ms/op
     p(99.9000) =     11.731 ms/op
     p(99.9900) =     25.542 ms/op
     p(99.9990) =     27.510 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.726 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.480 ±(99.9%) 0.014 ms/op
Iteration   1: 4.517 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.874 ms/op
                 getUser·p0.95:   6.472 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  13.809 ms/op
                 getUser·p0.9999: 17.717 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 4.448 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.644 ms/op
                 getUser·p0.95:   6.275 ms/op
                 getUser·p0.99:   8.716 ms/op
                 getUser·p0.999:  11.948 ms/op
                 getUser·p0.9999: 17.682 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   3: 4.484 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.685 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   8.387 ms/op
                 getUser·p0.999:  14.167 ms/op
                 getUser·p0.9999: 23.027 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214056
  mean =      4.483 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4284 
    [ 2.500,  5.000) = 155767 
    [ 5.000,  7.500) = 49515 
    [ 7.500, 10.000) = 3488 
    [10.000, 12.500) = 730 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     13.857 ms/op
     p(99.9900) =     22.141 ms/op
     p(99.9990) =     23.504 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.862 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.154 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.756 ±(99.9%) 0.023 ms/op
Iteration   1: 5.854 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   11.813 ms/op
                 listUser·p0.999:  18.621 ms/op
                 listUser·p0.9999: 20.306 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   2: 5.941 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   5.521 ms/op
                 listUser·p0.90:   8.217 ms/op
                 listUser·p0.95:   9.454 ms/op
                 listUser·p0.99:   12.321 ms/op
                 listUser·p0.999:  17.675 ms/op
                 listUser·p0.9999: 22.253 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   3: 6.184 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   5.775 ms/op
                 listUser·p0.90:   8.298 ms/op
                 listUser·p0.95:   9.470 ms/op
                 listUser·p0.99:   12.616 ms/op
                 listUser·p0.999:  23.404 ms/op
                 listUser·p0.9999: 35.993 ms/op
                 listUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 160273
  mean =      5.990 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 45551 
    [ 5.000,  7.500) = 91440 
    [ 7.500, 10.000) = 18004 
    [10.000, 12.500) = 3753 
    [12.500, 15.000) = 929 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =      8.143 ms/op
     p(95.0000) =      9.290 ms/op
     p(99.0000) =     12.321 ms/op
     p(99.9000) =     20.438 ms/op
     p(99.9900) =     33.618 ms/op
     p(99.9990) =     37.053 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.013 ± 0.798  ops/ms
ClientGrpc.existUser                       thrpt       3   7.471 ± 1.851  ops/ms
ClientGrpc.getUser                         thrpt       3   7.071 ± 0.970  ops/ms
ClientGrpc.listUser                        thrpt       3   5.462 ± 0.294  ops/ms
ClientGrpc.createUser                       avgt       3   4.563 ± 0.773   ms/op
ClientGrpc.existUser                        avgt       3   4.332 ± 1.463   ms/op
ClientGrpc.getUser                          avgt       3   4.442 ± 1.173   ms/op
ClientGrpc.listUser                         avgt       3   5.711 ± 1.030   ms/op
ClientGrpc.createUser                     sample  209982   4.573 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.382           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.865           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.496           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.946           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.812           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.742           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.921           ms/op
ClientGrpc.existUser                      sample  222550   4.313 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.931           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.571           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.128           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.331           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.731           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.542           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.591           ms/op
ClientGrpc.getUser                        sample  214056   4.483 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.848           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.743           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.332           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.667           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.857           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.141           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.626           ms/op
ClientGrpc.listUser                       sample  160273   5.990 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.027           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.143           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.290           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.321           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.438           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.618           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.290           ms/op
