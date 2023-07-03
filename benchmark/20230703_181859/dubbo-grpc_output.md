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
# Warmup Iteration   1: 2.550 ops/ms
# Warmup Iteration   2: 5.786 ops/ms
# Warmup Iteration   3: 7.290 ops/ms
Iteration   1: 7.421 ops/ms
Iteration   2: 7.479 ops/ms
Iteration   3: 7.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.476 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (7.421, 7.476, 7.527), stdev = 0.053
  CI (99.9%): [6.506, 8.446] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.316 ops/ms
# Warmup Iteration   2: 7.150 ops/ms
# Warmup Iteration   3: 7.948 ops/ms
Iteration   1: 8.352 ops/ms
Iteration   2: 8.103 ops/ms
Iteration   3: 8.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.241 ±(99.9%) 2.303 ops/ms [Average]
  (min, avg, max) = (8.103, 8.241, 8.352), stdev = 0.126
  CI (99.9%): [5.937, 10.544] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.572 ops/ms
# Warmup Iteration   2: 6.813 ops/ms
# Warmup Iteration   3: 7.472 ops/ms
Iteration   1: 7.420 ops/ms
Iteration   2: 7.390 ops/ms
Iteration   3: 7.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.439 ±(99.9%) 1.109 ops/ms [Average]
  (min, avg, max) = (7.390, 7.439, 7.507), stdev = 0.061
  CI (99.9%): [6.330, 8.548] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.596 ops/ms
# Warmup Iteration   2: 5.358 ops/ms
# Warmup Iteration   3: 5.780 ops/ms
Iteration   1: 5.882 ops/ms
Iteration   2: 5.846 ops/ms
Iteration   3: 6.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.912 ±(99.9%) 1.542 ops/ms [Average]
  (min, avg, max) = (5.846, 5.912, 6.007), stdev = 0.085
  CI (99.9%): [4.370, 7.454] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.812 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.548 ±(99.9%) 0.006 ms/op
Iteration   1: 4.368 ±(99.9%) 0.002 ms/op
Iteration   2: 4.328 ±(99.9%) 0.003 ms/op
Iteration   3: 4.424 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.373 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (4.328, 4.373, 4.424), stdev = 0.048
  CI (99.9%): [3.489, 5.258] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.202 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.003 ms/op
Iteration   1: 4.016 ±(99.9%) 0.003 ms/op
Iteration   2: 4.061 ±(99.9%) 0.003 ms/op
Iteration   3: 4.160 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.079 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (4.016, 4.079, 4.160), stdev = 0.073
  CI (99.9%): [2.742, 5.416] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.962 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.713 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.472 ±(99.9%) 0.004 ms/op
Iteration   1: 4.355 ±(99.9%) 0.006 ms/op
Iteration   2: 4.278 ±(99.9%) 0.004 ms/op
Iteration   3: 4.238 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.290 ±(99.9%) 1.085 ms/op [Average]
  (min, avg, max) = (4.238, 4.290, 4.355), stdev = 0.059
  CI (99.9%): [3.205, 5.375] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.440 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.887 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.602 ±(99.9%) 0.016 ms/op
Iteration   1: 5.503 ±(99.9%) 0.015 ms/op
Iteration   2: 5.438 ±(99.9%) 0.011 ms/op
Iteration   3: 5.389 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.443 ±(99.9%) 1.044 ms/op [Average]
  (min, avg, max) = (5.389, 5.443, 5.503), stdev = 0.057
  CI (99.9%): [4.399, 6.487] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.989 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.544 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.014 ms/op
Iteration   1: 4.443 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.062 ms/op
                 createUser·p0.99:   7.594 ms/op
                 createUser·p0.999:  10.880 ms/op
                 createUser·p0.9999: 24.773 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   2: 4.362 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   5.890 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  13.042 ms/op
                 createUser·p0.9999: 22.927 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 4.219 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   4.100 ms/op
                 createUser·p0.90:   5.226 ms/op
                 createUser·p0.95:   5.707 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  17.445 ms/op
                 createUser·p0.9999: 28.981 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 221041
  mean =      4.340 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2289 
    [ 2.500,  5.000) = 176495 
    [ 5.000,  7.500) = 40227 
    [ 7.500, 10.000) = 1650 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     13.465 ms/op
     p(99.9900) =     28.439 ms/op
     p(99.9990) =     31.085 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.765 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.012 ms/op
Iteration   1: 3.953 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.243 ms/op
                 existUser·p0.99:   6.446 ms/op
                 existUser·p0.999:  10.093 ms/op
                 existUser·p0.9999: 16.936 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   2: 3.998 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.423 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  13.923 ms/op
                 existUser·p0.9999: 20.806 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   3: 4.086 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   3.994 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  13.156 ms/op
                 existUser·p0.9999: 24.221 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 239450
  mean =      4.011 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5117 
    [ 2.500,  5.000) = 211582 
    [ 5.000,  7.500) = 21442 
    [ 7.500, 10.000) = 884 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     12.494 ms/op
     p(99.9900) =     21.172 ms/op
     p(99.9990) =     24.432 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.362 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.366 ±(99.9%) 0.012 ms/op
Iteration   1: 4.466 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   5.972 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  12.583 ms/op
                 getUser·p0.9999: 16.805 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   2: 4.265 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   4.174 ms/op
                 getUser·p0.90:   5.276 ms/op
                 getUser·p0.95:   5.702 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  12.387 ms/op
                 getUser·p0.9999: 17.154 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   3: 4.252 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.218 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  11.469 ms/op
                 getUser·p0.9999: 22.429 ms/op
                 getUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221799
  mean =      4.325 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2912 
    [ 2.500,  5.000) = 179001 
    [ 5.000,  7.500) = 38143 
    [ 7.500, 10.000) = 1244 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     22.113 ms/op
     p(99.9990) =     22.570 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 7.733 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 6.004 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.596 ±(99.9%) 0.021 ms/op
Iteration   1: 5.593 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.038 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   7.578 ms/op
                 listUser·p0.95:   8.510 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  16.398 ms/op
                 listUser·p0.9999: 18.092 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 5.489 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   5.145 ms/op
                 listUser·p0.90:   7.660 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   10.945 ms/op
                 listUser·p0.999:  23.777 ms/op
                 listUser·p0.9999: 27.296 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   3: 5.510 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  31.027 ms/op
                 listUser·p0.9999: 33.364 ms/op
                 listUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173608
  mean =      5.530 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 236 
    [ 2.500,  5.000) = 73763 
    [ 5.000,  7.500) = 81306 
    [ 7.500, 10.000) = 15649 
    [10.000, 12.500) = 1946 
    [12.500, 15.000) = 316 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      7.578 ms/op
     p(95.0000) =      8.520 ms/op
     p(99.0000) =     10.697 ms/op
     p(99.9000) =     17.937 ms/op
     p(99.9900) =     32.864 ms/op
     p(99.9990) =     33.755 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.476 ± 0.970  ops/ms
ClientGrpc.existUser                       thrpt       3   8.241 ± 2.303  ops/ms
ClientGrpc.getUser                         thrpt       3   7.439 ± 1.109  ops/ms
ClientGrpc.listUser                        thrpt       3   5.912 ± 1.542  ops/ms
ClientGrpc.createUser                       avgt       3   4.373 ± 0.884   ms/op
ClientGrpc.existUser                        avgt       3   4.079 ± 1.337   ms/op
ClientGrpc.getUser                          avgt       3   4.290 ± 1.085   ms/op
ClientGrpc.listUser                         avgt       3   5.443 ± 1.044   ms/op
ClientGrpc.createUser                     sample  221041   4.340 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.027           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.448           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.906           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.373           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.465           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.439           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.047           ms/op
ClientGrpc.existUser                      sample  239450   4.011 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.884           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.973           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.382           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.636           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.494           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.172           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.478           ms/op
ClientGrpc.getUser                        sample  221799   4.325 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.955           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.358           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.759           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.143           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.386           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.113           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.675           ms/op
ClientGrpc.listUser                       sample  173608   5.530 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.165           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.578           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.697           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.937           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.864           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.948           ms/op
