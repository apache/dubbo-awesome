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
# Warmup Iteration   1: 3.192 ops/ms
# Warmup Iteration   2: 6.672 ops/ms
# Warmup Iteration   3: 6.701 ops/ms
Iteration   1: 7.060 ops/ms
Iteration   2: 7.970 ops/ms
Iteration   3: 8.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.758 ±(99.9%) 11.303 ops/ms [Average]
  (min, avg, max) = (7.060, 7.758, 8.244), stdev = 0.620
  CI (99.9%): [≈ 0, 19.061] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.441 ops/ms
# Warmup Iteration   2: 7.878 ops/ms
# Warmup Iteration   3: 8.387 ops/ms
Iteration   1: 8.607 ops/ms
Iteration   2: 7.620 ops/ms
Iteration   3: 5.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.329 ±(99.9%) 26.382 ops/ms [Average]
  (min, avg, max) = (5.759, 7.329, 8.607), stdev = 1.446
  CI (99.9%): [≈ 0, 33.710] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.722 ops/ms
# Warmup Iteration   2: 6.677 ops/ms
# Warmup Iteration   3: 6.729 ops/ms
Iteration   1: 7.262 ops/ms
Iteration   2: 7.357 ops/ms
Iteration   3: 5.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.818 ±(99.9%) 15.559 ops/ms [Average]
  (min, avg, max) = (5.835, 6.818, 7.357), stdev = 0.853
  CI (99.9%): [≈ 0, 22.377] (assumes normal distribution)


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
# Warmup Iteration   1: 3.943 ops/ms
# Warmup Iteration   2: 4.764 ops/ms
# Warmup Iteration   3: 4.944 ops/ms
Iteration   1: 5.774 ops/ms
Iteration   2: 5.789 ops/ms
Iteration   3: 5.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.750 ±(99.9%) 1.010 ops/ms [Average]
  (min, avg, max) = (5.686, 5.750, 5.789), stdev = 0.055
  CI (99.9%): [4.740, 6.760] (assumes normal distribution)


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
# Warmup Iteration   1: 5.894 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.559 ±(99.9%) 0.005 ms/op
Iteration   1: 4.641 ±(99.9%) 0.005 ms/op
Iteration   2: 4.762 ±(99.9%) 0.004 ms/op
Iteration   3: 4.329 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.577 ±(99.9%) 4.076 ms/op [Average]
  (min, avg, max) = (4.329, 4.577, 4.762), stdev = 0.223
  CI (99.9%): [0.501, 8.653] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.034 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.303 ±(99.9%) 0.008 ms/op
Iteration   1: 4.185 ±(99.9%) 0.005 ms/op
Iteration   2: 4.130 ±(99.9%) 0.005 ms/op
Iteration   3: 4.263 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.193 ±(99.9%) 1.222 ms/op [Average]
  (min, avg, max) = (4.130, 4.193, 4.263), stdev = 0.067
  CI (99.9%): [2.971, 5.415] (assumes normal distribution)


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
# Warmup Iteration   1: 5.699 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.882 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.505 ±(99.9%) 0.023 ms/op
Iteration   1: 4.571 ±(99.9%) 0.004 ms/op
Iteration   2: 4.491 ±(99.9%) 0.004 ms/op
Iteration   3: 4.234 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.432 ±(99.9%) 3.210 ms/op [Average]
  (min, avg, max) = (4.234, 4.432, 4.571), stdev = 0.176
  CI (99.9%): [1.222, 7.642] (assumes normal distribution)


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
# Warmup Iteration   1: 7.186 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.936 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.624 ±(99.9%) 0.012 ms/op
Iteration   1: 5.618 ±(99.9%) 0.010 ms/op
Iteration   2: 5.426 ±(99.9%) 0.019 ms/op
Iteration   3: 5.436 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.493 ±(99.9%) 1.969 ms/op [Average]
  (min, avg, max) = (5.426, 5.493, 5.618), stdev = 0.108
  CI (99.9%): [3.524, 7.462] (assumes normal distribution)


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
# Warmup Iteration   1: 5.443 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.660 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.604 ±(99.9%) 0.019 ms/op
Iteration   1: 4.549 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   6.103 ms/op
                 createUser·p0.95:   7.021 ms/op
                 createUser·p0.99:   9.732 ms/op
                 createUser·p0.999:  15.533 ms/op
                 createUser·p0.9999: 21.001 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   2: 4.602 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   6.332 ms/op
                 createUser·p0.95:   7.512 ms/op
                 createUser·p0.99:   10.238 ms/op
                 createUser·p0.999:  12.919 ms/op
                 createUser·p0.9999: 23.144 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 4.500 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   6.070 ms/op
                 createUser·p0.95:   7.086 ms/op
                 createUser·p0.99:   9.552 ms/op
                 createUser·p0.999:  19.071 ms/op
                 createUser·p0.9999: 53.035 ms/op
                 createUser·p1.00:   54.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 210908
  mean =      4.550 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 155612 
    [ 5.000, 10.000) = 53385 
    [10.000, 15.000) = 1685 
    [15.000, 20.000) = 99 
    [20.000, 25.000) = 72 
    [25.000, 30.000) = 23 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      7.201 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     36.176 ms/op
     p(99.9990) =     53.995 ms/op
     p(99.9999) =     54.002 ms/op
    p(100.0000) =     54.002 ms/op


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
# Warmup Iteration   1: 5.255 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.638 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.016 ms/op
Iteration   1: 4.402 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   6.005 ms/op
                 existUser·p0.95:   7.184 ms/op
                 existUser·p0.99:   9.667 ms/op
                 existUser·p0.999:  14.723 ms/op
                 existUser·p0.9999: 19.859 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 4.295 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.923 ms/op
                 existUser·p0.95:   7.070 ms/op
                 existUser·p0.99:   9.683 ms/op
                 existUser·p0.999:  12.780 ms/op
                 existUser·p0.9999: 25.002 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 4.154 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   3.920 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.668 ms/op
                 existUser·p0.99:   9.236 ms/op
                 existUser·p0.999:  15.171 ms/op
                 existUser·p0.9999: 25.579 ms/op
                 existUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 224143
  mean =      4.281 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11324 
    [ 2.500,  5.000) = 167674 
    [ 5.000,  7.500) = 36904 
    [ 7.500, 10.000) = 6590 
    [10.000, 12.500) = 1252 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.874 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =      9.552 ms/op
     p(99.9000) =     14.212 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     25.904 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.017 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.185 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.136 ±(99.9%) 0.026 ms/op
Iteration   1: 5.084 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   7.438 ms/op
                 getUser·p0.95:   8.651 ms/op
                 getUser·p0.99:   11.174 ms/op
                 getUser·p0.999:  21.013 ms/op
                 getUser·p0.9999: 33.208 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   2: 4.898 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   7.291 ms/op
                 getUser·p0.95:   8.716 ms/op
                 getUser·p0.99:   11.567 ms/op
                 getUser·p0.999:  15.157 ms/op
                 getUser·p0.9999: 24.771 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   3: 5.229 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   4.727 ms/op
                 getUser·p0.90:   7.963 ms/op
                 getUser·p0.95:   9.290 ms/op
                 getUser·p0.99:   11.911 ms/op
                 getUser·p0.999:  16.347 ms/op
                 getUser·p0.9999: 32.993 ms/op
                 getUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 189431
  mean =      5.067 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5574 
    [ 2.500,  5.000) = 109961 
    [ 5.000,  7.500) = 54430 
    [ 7.500, 10.000) = 14543 
    [10.000, 12.500) = 3889 
    [12.500, 15.000) = 781 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      7.553 ms/op
     p(95.0000) =      8.897 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     16.131 ms/op
     p(99.9900) =     32.837 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 6.863 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.720 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.987 ±(99.9%) 0.031 ms/op
Iteration   1: 5.641 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   12.583 ms/op
                 listUser·p0.999:  19.358 ms/op
                 listUser·p0.9999: 23.473 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   2: 5.434 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   7.700 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   12.091 ms/op
                 listUser·p0.999:  20.447 ms/op
                 listUser·p0.9999: 25.738 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   3: 5.574 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   5.022 ms/op
                 listUser·p0.90:   7.930 ms/op
                 listUser·p0.95:   9.201 ms/op
                 listUser·p0.99:   12.304 ms/op
                 listUser·p0.999:  23.596 ms/op
                 listUser·p0.9999: 25.289 ms/op
                 listUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173042
  mean =      5.549 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 372 
    [ 2.500,  5.000) = 86184 
    [ 5.000,  7.500) = 64490 
    [ 7.500, 10.000) = 16663 
    [10.000, 12.500) = 3731 
    [12.500, 15.000) = 1009 
    [15.000, 17.500) = 269 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      7.905 ms/op
     p(95.0000) =      9.110 ms/op
     p(99.0000) =     12.314 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     25.025 ms/op
     p(99.9990) =     27.009 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score    Error   Units
ClientGrpc.createUser                      thrpt       3   7.758 ± 11.303  ops/ms
ClientGrpc.existUser                       thrpt       3   7.329 ± 26.382  ops/ms
ClientGrpc.getUser                         thrpt       3   6.818 ± 15.559  ops/ms
ClientGrpc.listUser                        thrpt       3   5.750 ±  1.010  ops/ms
ClientGrpc.createUser                       avgt       3   4.577 ±  4.076   ms/op
ClientGrpc.existUser                        avgt       3   4.193 ±  1.222   ms/op
ClientGrpc.getUser                          avgt       3   4.432 ±  3.210   ms/op
ClientGrpc.listUser                         avgt       3   5.493 ±  1.969   ms/op
ClientGrpc.createUser                     sample  210908   4.550 ±  0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.738            ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.252            ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.160            ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.201            ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.847            ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.466            ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          36.176            ms/op
ClientGrpc.createUser:createUser·p1.00    sample          54.002            ms/op
ClientGrpc.existUser                      sample  224143   4.281 ±  0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.862            ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.994            ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.874            ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.980            ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.552            ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.212            ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.002            ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.985            ms/op
ClientGrpc.getUser                        sample  189431   5.067 ±  0.015   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.819            ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.596            ms/op
ClientGrpc.getUser:getUser·p0.90          sample           7.553            ms/op
ClientGrpc.getUser:getUser·p0.95          sample           8.897            ms/op
ClientGrpc.getUser:getUser·p0.99          sample          11.567            ms/op
ClientGrpc.getUser:getUser·p0.999         sample          16.131            ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.837            ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.817            ms/op
ClientGrpc.listUser                       sample  173042   5.549 ±  0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.358            ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.997            ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.905            ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.110            ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.314            ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.972            ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.025            ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.296            ms/op
