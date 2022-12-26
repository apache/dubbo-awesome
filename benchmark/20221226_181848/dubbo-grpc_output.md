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
# Warmup Iteration   1: 2.187 ops/ms
# Warmup Iteration   2: 5.371 ops/ms
# Warmup Iteration   3: 6.822 ops/ms
Iteration   1: 7.038 ops/ms
Iteration   2: 7.126 ops/ms
Iteration   3: 7.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.181 ±(99.9%) 3.225 ops/ms [Average]
  (min, avg, max) = (7.038, 7.181, 7.379), stdev = 0.177
  CI (99.9%): [3.956, 10.406] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.586 ops/ms
# Warmup Iteration   2: 7.166 ops/ms
# Warmup Iteration   3: 7.218 ops/ms
Iteration   1: 7.271 ops/ms
Iteration   2: 7.319 ops/ms
Iteration   3: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.550 ±(99.9%) 8.073 ops/ms [Average]
  (min, avg, max) = (7.271, 7.550, 8.060), stdev = 0.443
  CI (99.9%): [≈ 0, 15.623] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ops/ms
# Warmup Iteration   2: 6.577 ops/ms
# Warmup Iteration   3: 6.860 ops/ms
Iteration   1: 6.971 ops/ms
Iteration   2: 7.167 ops/ms
Iteration   3: 7.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.092 ±(99.9%) 1.943 ops/ms [Average]
  (min, avg, max) = (6.971, 7.092, 7.167), stdev = 0.107
  CI (99.9%): [5.149, 9.036] (assumes normal distribution)


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
# Warmup Iteration   1: 3.657 ops/ms
# Warmup Iteration   2: 5.215 ops/ms
# Warmup Iteration   3: 5.760 ops/ms
Iteration   1: 5.788 ops/ms
Iteration   2: 5.739 ops/ms
Iteration   3: 5.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.765 ±(99.9%) 0.451 ops/ms [Average]
  (min, avg, max) = (5.739, 5.765, 5.788), stdev = 0.025
  CI (99.9%): [5.313, 6.216] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.490 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.809 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.484 ±(99.9%) 0.010 ms/op
Iteration   1: 4.506 ±(99.9%) 0.004 ms/op
Iteration   2: 4.416 ±(99.9%) 0.004 ms/op
Iteration   3: 4.373 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.432 ±(99.9%) 1.234 ms/op [Average]
  (min, avg, max) = (4.373, 4.432, 4.506), stdev = 0.068
  CI (99.9%): [3.198, 5.665] (assumes normal distribution)


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
# Warmup Iteration   1: 6.164 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.004 ms/op
Iteration   1: 4.254 ±(99.9%) 0.005 ms/op
Iteration   2: 4.283 ±(99.9%) 0.004 ms/op
Iteration   3: 4.265 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.267 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (4.254, 4.267, 4.283), stdev = 0.015
  CI (99.9%): [4.000, 4.534] (assumes normal distribution)


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
# Warmup Iteration   1: 6.684 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.725 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.543 ±(99.9%) 0.006 ms/op
Iteration   1: 4.405 ±(99.9%) 0.003 ms/op
Iteration   2: 4.472 ±(99.9%) 0.004 ms/op
Iteration   3: 4.631 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.503 ±(99.9%) 2.114 ms/op [Average]
  (min, avg, max) = (4.405, 4.503, 4.631), stdev = 0.116
  CI (99.9%): [2.388, 6.617] (assumes normal distribution)


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
# Warmup Iteration   1: 8.093 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.072 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.730 ±(99.9%) 0.018 ms/op
Iteration   1: 5.443 ±(99.9%) 0.016 ms/op
Iteration   2: 5.449 ±(99.9%) 0.022 ms/op
Iteration   3: 5.509 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.467 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (5.443, 5.467, 5.509), stdev = 0.037
  CI (99.9%): [4.799, 6.135] (assumes normal distribution)


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
# Warmup Iteration   1: 6.875 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.706 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.587 ±(99.9%) 0.016 ms/op
Iteration   1: 4.504 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.767 ms/op
                 createUser·p0.95:   6.275 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  14.696 ms/op
                 createUser·p0.9999: 22.410 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 4.469 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   4.293 ms/op
                 createUser·p0.90:   5.792 ms/op
                 createUser·p0.95:   6.504 ms/op
                 createUser·p0.99:   9.395 ms/op
                 createUser·p0.999:  14.573 ms/op
                 createUser·p0.9999: 26.963 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   3: 4.477 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.784 ms/op
                 createUser·p0.95:   6.414 ms/op
                 createUser·p0.99:   8.880 ms/op
                 createUser·p0.999:  13.290 ms/op
                 createUser·p0.9999: 27.717 ms/op
                 createUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214134
  mean =      4.483 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5014 
    [ 2.500,  5.000) = 154074 
    [ 5.000,  7.500) = 50406 
    [ 7.500, 10.000) = 3444 
    [10.000, 12.500) = 766 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.382 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     27.413 ms/op
     p(99.9990) =     28.167 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 6.085 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.201 ±(99.9%) 0.014 ms/op
Iteration   1: 4.080 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   3.928 ms/op
                 existUser·p0.90:   5.235 ms/op
                 existUser·p0.95:   5.906 ms/op
                 existUser·p0.99:   7.881 ms/op
                 existUser·p0.999:  13.582 ms/op
                 existUser·p0.9999: 18.905 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   2: 3.819 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.932 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   7.406 ms/op
                 existUser·p0.999:  12.723 ms/op
                 existUser·p0.9999: 19.452 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   3: 4.067 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   5.071 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   7.356 ms/op
                 existUser·p0.999:  10.070 ms/op
                 existUser·p0.9999: 22.684 ms/op
                 existUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 240849
  mean =      3.985 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15056 
    [ 2.500,  5.000) = 199446 
    [ 5.000,  7.500) = 23835 
    [ 7.500, 10.000) = 1969 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     12.635 ms/op
     p(99.9900) =     21.097 ms/op
     p(99.9990) =     23.206 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 6.893 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.828 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 4.439 ±(99.9%) 0.015 ms/op
Iteration   1: 4.456 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.808 ms/op
                 getUser·p0.95:   6.335 ms/op
                 getUser·p0.99:   8.634 ms/op
                 getUser·p0.999:  12.410 ms/op
                 getUser·p0.9999: 15.417 ms/op
                 getUser·p1.00:   15.892 ms/op

Iteration   2: 4.539 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.825 ms/op
                 getUser·p0.95:   6.300 ms/op
                 getUser·p0.99:   8.364 ms/op
                 getUser·p0.999:  12.322 ms/op
                 getUser·p0.9999: 18.773 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   3: 4.202 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   4.071 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  12.352 ms/op
                 getUser·p0.9999: 21.270 ms/op
                 getUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218425
  mean =      4.394 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6314 
    [ 2.500,  5.000) = 162661 
    [ 5.000,  7.500) = 45718 
    [ 7.500, 10.000) = 2904 
    [10.000, 12.500) = 625 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     12.370 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     23.288 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 8.671 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 5.785 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.673 ±(99.9%) 0.024 ms/op
Iteration   1: 5.549 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   7.578 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  22.524 ms/op
                 listUser·p0.9999: 28.694 ms/op
                 listUser·p1.00:   32.408 ms/op

Iteration   2: 5.555 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  24.285 ms/op
                 listUser·p0.9999: 29.294 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   3: 5.429 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   5.153 ms/op
                 listUser·p0.90:   7.102 ms/op
                 listUser·p0.95:   8.094 ms/op
                 listUser·p0.99:   10.532 ms/op
                 listUser·p0.999:  23.855 ms/op
                 listUser·p0.9999: 26.018 ms/op
                 listUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174118
  mean =      5.510 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 270 
    [ 2.500,  5.000) = 73906 
    [ 5.000,  7.500) = 83473 
    [ 7.500, 10.000) = 13548 
    [10.000, 12.500) = 2083 
    [12.500, 15.000) = 431 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.422 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     31.485 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.181 ± 3.225  ops/ms
ClientGrpc.existUser                       thrpt       3   7.550 ± 8.073  ops/ms
ClientGrpc.getUser                         thrpt       3   7.092 ± 1.943  ops/ms
ClientGrpc.listUser                        thrpt       3   5.765 ± 0.451  ops/ms
ClientGrpc.createUser                       avgt       3   4.432 ± 1.234   ms/op
ClientGrpc.existUser                        avgt       3   4.267 ± 0.267   ms/op
ClientGrpc.getUser                          avgt       3   4.503 ± 2.114   ms/op
ClientGrpc.listUser                         avgt       3   5.467 ± 0.668   ms/op
ClientGrpc.createUser                     sample  214134   4.483 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.908           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.784           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.382           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.929           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.189           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.413           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.246           ms/op
ClientGrpc.existUser                      sample  240849   3.985 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.593           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.891           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.071           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.685           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.561           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.635           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.097           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.183           ms/op
ClientGrpc.getUser                        sample  218425   4.394 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.848           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.685           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.218           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.471           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.370           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.087           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.396           ms/op
ClientGrpc.listUser                       sample  174118   5.510 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.380           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.422           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.389           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.879           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          23.626           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.869           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.408           ms/op
