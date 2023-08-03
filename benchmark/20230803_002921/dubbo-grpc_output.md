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
# Warmup Iteration   1: 2.139 ops/ms
# Warmup Iteration   2: 5.545 ops/ms
# Warmup Iteration   3: 7.450 ops/ms
Iteration   1: 7.246 ops/ms
Iteration   2: 7.778 ops/ms
Iteration   3: 7.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.566 ±(99.9%) 5.142 ops/ms [Average]
  (min, avg, max) = (7.246, 7.566, 7.778), stdev = 0.282
  CI (99.9%): [2.424, 12.707] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.341 ops/ms
# Warmup Iteration   2: 7.497 ops/ms
# Warmup Iteration   3: 7.768 ops/ms
Iteration   1: 8.332 ops/ms
Iteration   2: 8.134 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.169 ±(99.9%) 2.721 ops/ms [Average]
  (min, avg, max) = (8.040, 8.169, 8.332), stdev = 0.149
  CI (99.9%): [5.448, 10.890] (assumes normal distribution)


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
# Warmup Iteration   1: 4.001 ops/ms
# Warmup Iteration   2: 6.222 ops/ms
# Warmup Iteration   3: 7.158 ops/ms
Iteration   1: 7.332 ops/ms
Iteration   2: 6.968 ops/ms
Iteration   3: 7.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.194 ±(99.9%) 3.592 ops/ms [Average]
  (min, avg, max) = (6.968, 7.194, 7.332), stdev = 0.197
  CI (99.9%): [3.602, 10.785] (assumes normal distribution)


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
# Warmup Iteration   1: 3.871 ops/ms
# Warmup Iteration   2: 5.036 ops/ms
# Warmup Iteration   3: 5.397 ops/ms
Iteration   1: 5.459 ops/ms
Iteration   2: 5.825 ops/ms
Iteration   3: 5.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.645 ±(99.9%) 3.344 ops/ms [Average]
  (min, avg, max) = (5.459, 5.645, 5.825), stdev = 0.183
  CI (99.9%): [2.302, 8.989] (assumes normal distribution)


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
# Warmup Iteration   1: 6.901 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.792 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.383 ±(99.9%) 0.020 ms/op
Iteration   1: 4.124 ±(99.9%) 0.003 ms/op
Iteration   2: 4.103 ±(99.9%) 0.002 ms/op
Iteration   3: 3.963 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.064 ±(99.9%) 1.593 ms/op [Average]
  (min, avg, max) = (3.963, 4.064, 4.124), stdev = 0.087
  CI (99.9%): [2.470, 5.657] (assumes normal distribution)


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
# Warmup Iteration   1: 6.974 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.246 ±(99.9%) 0.006 ms/op
Iteration   1: 4.170 ±(99.9%) 0.003 ms/op
Iteration   2: 4.111 ±(99.9%) 0.004 ms/op
Iteration   3: 4.314 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.198 ±(99.9%) 1.902 ms/op [Average]
  (min, avg, max) = (4.111, 4.198, 4.314), stdev = 0.104
  CI (99.9%): [2.297, 6.100] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.798 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.582 ±(99.9%) 0.003 ms/op
Iteration   1: 4.412 ±(99.9%) 0.004 ms/op
Iteration   2: 4.536 ±(99.9%) 0.004 ms/op
Iteration   3: 4.514 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.487 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (4.412, 4.487, 4.536), stdev = 0.066
  CI (99.9%): [3.283, 5.691] (assumes normal distribution)


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
# Warmup Iteration   1: 7.739 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.965 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.905 ±(99.9%) 0.022 ms/op
Iteration   1: 5.883 ±(99.9%) 0.016 ms/op
Iteration   2: 5.745 ±(99.9%) 0.035 ms/op
Iteration   3: 5.565 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.731 ±(99.9%) 2.907 ms/op [Average]
  (min, avg, max) = (5.565, 5.731, 5.883), stdev = 0.159
  CI (99.9%): [2.824, 8.638] (assumes normal distribution)


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
# Warmup Iteration   1: 7.140 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.717 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.465 ±(99.9%) 0.015 ms/op
Iteration   1: 4.487 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   5.587 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   7.471 ms/op
                 createUser·p0.999:  13.746 ms/op
                 createUser·p0.9999: 24.502 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   2: 4.593 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   4.497 ms/op
                 createUser·p0.90:   5.644 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   7.824 ms/op
                 createUser·p0.999:  12.911 ms/op
                 createUser·p0.9999: 17.794 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   3: 4.272 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   4.137 ms/op
                 createUser·p0.90:   5.284 ms/op
                 createUser·p0.95:   5.759 ms/op
                 createUser·p0.99:   7.772 ms/op
                 createUser·p0.999:  12.783 ms/op
                 createUser·p0.9999: 27.608 ms/op
                 createUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215901
  mean =      4.447 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2900 
    [ 2.500,  5.000) = 164472 
    [ 5.000,  7.500) = 46149 
    [ 7.500, 10.000) = 1577 
    [10.000, 12.500) = 471 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     13.305 ms/op
     p(99.9900) =     25.815 ms/op
     p(99.9990) =     28.301 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 6.312 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.012 ms/op
Iteration   1: 4.313 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   4.190 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   5.816 ms/op
                 existUser·p0.99:   7.627 ms/op
                 existUser·p0.999:  11.679 ms/op
                 existUser·p0.9999: 18.631 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   2: 4.123 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   4.018 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  15.899 ms/op
                 existUser·p0.9999: 17.957 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 4.198 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   7.350 ms/op
                 existUser·p0.999:  12.254 ms/op
                 existUser·p0.9999: 27.079 ms/op
                 existUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 227964
  mean =      4.210 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4035 
    [ 2.500,  5.000) = 190823 
    [ 5.000,  7.500) = 31010 
    [ 7.500, 10.000) = 1651 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     25.697 ms/op
     p(99.9990) =     27.479 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 6.729 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.014 ms/op
Iteration   1: 4.431 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.587 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  15.090 ms/op
                 getUser·p0.9999: 17.163 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   2: 4.282 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   4.170 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  10.661 ms/op
                 getUser·p0.9999: 18.140 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   3: 4.254 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   4.116 ms/op
                 getUser·p0.90:   5.374 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   7.406 ms/op
                 getUser·p0.999:  14.093 ms/op
                 getUser·p0.9999: 23.069 ms/op
                 getUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221942
  mean =      4.321 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3792 
    [ 2.500,  5.000) = 176028 
    [ 5.000,  7.500) = 39623 
    [ 7.500, 10.000) = 1860 
    [10.000, 12.500) = 412 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     20.555 ms/op
     p(99.9990) =     23.185 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 8.228 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.741 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.629 ±(99.9%) 0.021 ms/op
Iteration   1: 5.746 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   7.399 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.243 ms/op
                 listUser·p0.999:  24.586 ms/op
                 listUser·p0.9999: 26.406 ms/op
                 listUser·p1.00:   27.558 ms/op

Iteration   2: 5.945 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.688 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.305 ms/op
                 listUser·p0.999:  30.416 ms/op
                 listUser·p0.9999: 32.772 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   3: 5.890 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.754 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   7.709 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.633 ms/op
                 listUser·p0.999:  29.458 ms/op
                 listUser·p0.9999: 32.295 ms/op
                 listUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 163769
  mean =      5.859 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 112 
    [ 2.500,  5.000) = 44581 
    [ 5.000,  7.500) = 101592 
    [ 7.500, 10.000) = 13911 
    [10.000, 12.500) = 2498 
    [12.500, 15.000) = 601 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 75 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      5.554 ms/op
     p(90.0000) =      7.610 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     11.403 ms/op
     p(99.9000) =     26.532 ms/op
     p(99.9900) =     32.264 ms/op
     p(99.9990) =     33.429 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.566 ± 5.142  ops/ms
ClientGrpc.existUser                       thrpt       3   8.169 ± 2.721  ops/ms
ClientGrpc.getUser                         thrpt       3   7.194 ± 3.592  ops/ms
ClientGrpc.listUser                        thrpt       3   5.645 ± 3.344  ops/ms
ClientGrpc.createUser                       avgt       3   4.064 ± 1.593   ms/op
ClientGrpc.existUser                        avgt       3   4.198 ± 1.902   ms/op
ClientGrpc.getUser                          avgt       3   4.487 ± 1.204   ms/op
ClientGrpc.listUser                         avgt       3   5.731 ± 2.907   ms/op
ClientGrpc.createUser                     sample  215901   4.447 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.174           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.956           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.676           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.305           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.815           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.312           ms/op
ClientGrpc.existUser                      sample  227964   4.210 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.726           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.096           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.235           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.661           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.299           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.402           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.697           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.656           ms/op
ClientGrpc.getUser                        sample  221942   4.321 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.742           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.431           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.906           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.741           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.074           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.555           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.200           ms/op
ClientGrpc.listUser                       sample  163769   5.859 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.754           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.610           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.651           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.403           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          26.532           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.264           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.554           ms/op
