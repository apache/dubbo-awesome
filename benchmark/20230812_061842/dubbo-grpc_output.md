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
# Warmup Iteration   1: 3.350 ops/ms
# Warmup Iteration   2: 7.442 ops/ms
# Warmup Iteration   3: 8.629 ops/ms
Iteration   1: 9.142 ops/ms
Iteration   2: 8.860 ops/ms
Iteration   3: 9.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.134 ±(99.9%) 4.923 ops/ms [Average]
  (min, avg, max) = (8.860, 9.134, 9.400), stdev = 0.270
  CI (99.9%): [4.212, 14.057] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.674 ops/ms
# Warmup Iteration   2: 8.886 ops/ms
# Warmup Iteration   3: 9.586 ops/ms
Iteration   1: 9.956 ops/ms
Iteration   2: 9.403 ops/ms
Iteration   3: 9.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.702 ±(99.9%) 5.097 ops/ms [Average]
  (min, avg, max) = (9.403, 9.702, 9.956), stdev = 0.279
  CI (99.9%): [4.604, 14.799] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.148 ops/ms
# Warmup Iteration   2: 8.699 ops/ms
# Warmup Iteration   3: 9.037 ops/ms
Iteration   1: 9.099 ops/ms
Iteration   2: 8.976 ops/ms
Iteration   3: 9.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.059 ±(99.9%) 1.320 ops/ms [Average]
  (min, avg, max) = (8.976, 9.059, 9.103), stdev = 0.072
  CI (99.9%): [7.739, 10.379] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.708 ops/ms
# Warmup Iteration   2: 6.557 ops/ms
# Warmup Iteration   3: 6.812 ops/ms
Iteration   1: 6.876 ops/ms
Iteration   2: 7.073 ops/ms
Iteration   3: 6.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.963 ±(99.9%) 1.829 ops/ms [Average]
  (min, avg, max) = (6.876, 6.963, 7.073), stdev = 0.100
  CI (99.9%): [5.135, 8.792] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.275 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.011 ms/op
Iteration   1: 3.394 ±(99.9%) 0.004 ms/op
Iteration   2: 3.432 ±(99.9%) 0.004 ms/op
Iteration   3: 3.359 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.395 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (3.359, 3.395, 3.432), stdev = 0.036
  CI (99.9%): [2.733, 4.057] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.444 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.004 ms/op
Iteration   1: 3.430 ±(99.9%) 0.004 ms/op
Iteration   2: 3.306 ±(99.9%) 0.003 ms/op
Iteration   3: 3.243 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.327 ±(99.9%) 1.737 ms/op [Average]
  (min, avg, max) = (3.243, 3.327, 3.430), stdev = 0.095
  CI (99.9%): [1.590, 5.063] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.970 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.003 ms/op
Iteration   1: 3.536 ±(99.9%) 0.006 ms/op
Iteration   2: 3.356 ±(99.9%) 0.003 ms/op
Iteration   3: 3.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.476 ±(99.9%) 1.895 ms/op [Average]
  (min, avg, max) = (3.356, 3.476, 3.537), stdev = 0.104
  CI (99.9%): [1.582, 5.371] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.787 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.654 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.632 ±(99.9%) 0.024 ms/op
Iteration   1: 4.547 ±(99.9%) 0.010 ms/op
Iteration   2: 4.526 ±(99.9%) 0.016 ms/op
Iteration   3: 4.403 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.492 ±(99.9%) 1.420 ms/op [Average]
  (min, avg, max) = (4.403, 4.492, 4.547), stdev = 0.078
  CI (99.9%): [3.073, 5.912] (assumes normal distribution)


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
# Warmup Iteration   1: 5.101 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.009 ms/op
Iteration   1: 3.407 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  10.764 ms/op
                 createUser·p0.9999: 17.944 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   2: 3.556 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  7.882 ms/op
                 createUser·p0.9999: 15.795 ms/op
                 createUser·p1.00:   17.236 ms/op

Iteration   3: 3.513 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  17.354 ms/op
                 createUser·p0.9999: 30.474 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 275064
  mean =      3.491 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9710 
    [ 2.500,  5.000) = 260649 
    [ 5.000,  7.500) = 4108 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     10.763 ms/op
     p(99.9900) =     29.966 ms/op
     p(99.9990) =     30.548 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 4.709 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.008 ms/op
Iteration   1: 3.411 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  8.556 ms/op
                 existUser·p0.9999: 14.530 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 3.303 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  8.717 ms/op
                 existUser·p0.9999: 19.956 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   3: 3.389 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  8.413 ms/op
                 existUser·p0.9999: 18.022 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 285253
  mean =      3.367 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11568 
    [ 2.500,  5.000) = 269948 
    [ 5.000,  7.500) = 3205 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =      8.548 ms/op
     p(99.9900) =     19.430 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 4.442 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.008 ms/op
Iteration   1: 3.387 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  8.946 ms/op
                 getUser·p0.9999: 15.050 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   2: 3.420 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.218 ms/op
                 getUser·p0.999:  8.946 ms/op
                 getUser·p0.9999: 28.824 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   3: 3.678 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.384 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  9.289 ms/op
                 getUser·p0.9999: 21.266 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 275032
  mean =      3.490 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9980 
    [ 2.500,  5.000) = 260298 
    [ 5.000,  7.500) = 3967 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.384 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     29.213 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 7.329 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.848 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.768 ±(99.9%) 0.014 ms/op
Iteration   1: 4.511 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.473 ms/op
                 listUser·p0.95:   6.414 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  15.157 ms/op
                 listUser·p0.9999: 22.732 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   2: 4.562 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.324 ms/op
                 listUser·p0.99:   8.035 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 25.394 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   3: 4.681 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  18.973 ms/op
                 listUser·p0.9999: 32.349 ms/op
                 listUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 209385
  mean =      4.584 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 466 
    [ 2.500,  5.000) = 173055 
    [ 5.000,  7.500) = 31931 
    [ 7.500, 10.000) = 3346 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      6.406 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     16.892 ms/op
     p(99.9900) =     31.265 ms/op
     p(99.9990) =     33.652 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.134 ± 4.923  ops/ms
ClientGrpc.existUser                       thrpt       3   9.702 ± 5.097  ops/ms
ClientGrpc.getUser                         thrpt       3   9.059 ± 1.320  ops/ms
ClientGrpc.listUser                        thrpt       3   6.963 ± 1.829  ops/ms
ClientGrpc.createUser                       avgt       3   3.395 ± 0.662   ms/op
ClientGrpc.existUser                        avgt       3   3.327 ± 1.737   ms/op
ClientGrpc.getUser                          avgt       3   3.476 ± 1.895   ms/op
ClientGrpc.listUser                         avgt       3   4.492 ± 1.420   ms/op
ClientGrpc.createUser                     sample  275064   3.491 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.483           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.449           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.137           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.464           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.763           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.966           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.671           ms/op
ClientGrpc.existUser                      sample  285253   3.367 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.758           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.548           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.430           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.283           ms/op
ClientGrpc.getUser                        sample  275032   3.490 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.384           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.449           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.084           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.962           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.984           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.327           ms/op
ClientGrpc.listUser                       sample  209385   4.584 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.108           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.406           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.118           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.892           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.265           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.865           ms/op
