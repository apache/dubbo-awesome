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
# Warmup Iteration   1: 4.485 ops/ms
# Warmup Iteration   2: 9.088 ops/ms
# Warmup Iteration   3: 9.937 ops/ms
Iteration   1: 10.357 ops/ms
Iteration   2: 10.284 ops/ms
Iteration   3: 10.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.222 ±(99.9%) 3.158 ops/ms [Average]
  (min, avg, max) = (10.027, 10.222, 10.357), stdev = 0.173
  CI (99.9%): [7.064, 13.380] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.774 ops/ms
# Warmup Iteration   2: 10.530 ops/ms
# Warmup Iteration   3: 10.827 ops/ms
Iteration   1: 10.863 ops/ms
Iteration   2: 10.540 ops/ms
Iteration   3: 10.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.732 ±(99.9%) 3.097 ops/ms [Average]
  (min, avg, max) = (10.540, 10.732, 10.863), stdev = 0.170
  CI (99.9%): [7.636, 13.829] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.464 ops/ms
# Warmup Iteration   2: 10.121 ops/ms
# Warmup Iteration   3: 10.462 ops/ms
Iteration   1: 10.167 ops/ms
Iteration   2: 10.296 ops/ms
Iteration   3: 10.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.271 ±(99.9%) 1.700 ops/ms [Average]
  (min, avg, max) = (10.167, 10.271, 10.348), stdev = 0.093
  CI (99.9%): [8.571, 11.971] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.912 ops/ms
# Warmup Iteration   2: 7.827 ops/ms
# Warmup Iteration   3: 7.925 ops/ms
Iteration   1: 8.161 ops/ms
Iteration   2: 7.931 ops/ms
Iteration   3: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.045 ±(99.9%) 2.096 ops/ms [Average]
  (min, avg, max) = (7.931, 8.045, 8.161), stdev = 0.115
  CI (99.9%): [5.949, 10.141] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.757 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.002 ms/op
Iteration   1: 3.064 ±(99.9%) 0.002 ms/op
Iteration   2: 3.105 ±(99.9%) 0.002 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.083 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (3.064, 3.083, 3.105), stdev = 0.021
  CI (99.9%): [2.707, 3.459] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.775 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.003 ms/op
Iteration   1: 2.955 ±(99.9%) 0.003 ms/op
Iteration   2: 3.074 ±(99.9%) 0.002 ms/op
Iteration   3: 3.042 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.024 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (2.955, 3.024, 3.074), stdev = 0.062
  CI (99.9%): [1.900, 4.147] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.879 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.001 ms/op
Iteration   1: 3.117 ±(99.9%) 0.002 ms/op
Iteration   2: 3.068 ±(99.9%) 0.003 ms/op
Iteration   3: 3.105 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.097 ±(99.9%) 0.467 ms/op [Average]
  (min, avg, max) = (3.068, 3.097, 3.117), stdev = 0.026
  CI (99.9%): [2.630, 3.563] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.341 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.012 ms/op
Iteration   1: 4.020 ±(99.9%) 0.021 ms/op
Iteration   2: 3.959 ±(99.9%) 0.064 ms/op
Iteration   3: 3.985 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.988 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (3.959, 3.988, 4.020), stdev = 0.030
  CI (99.9%): [3.438, 4.539] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.496 ms/op
                 createUser·p0.9999: 13.085 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 3.125 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 13.926 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   3: 3.126 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.564 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  13.074 ms/op
                 createUser·p0.9999: 22.667 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308608
  mean =      3.112 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24502 
    [ 2.500,  5.000) = 282889 
    [ 5.000,  7.500) = 737 
    [ 7.500, 10.000) = 183 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      9.706 ms/op
     p(99.9900) =     21.813 ms/op
     p(99.9990) =     22.804 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.054 ms/op
                 existUser·p0.9999: 17.445 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   2: 2.900 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.188 ms/op
                 existUser·p0.999:  9.131 ms/op
                 existUser·p0.9999: 17.039 ms/op
                 existUser·p1.00:   17.957 ms/op

Iteration   3: 2.929 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.515 ms/op
                 existUser·p0.9999: 15.923 ms/op
                 existUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325923
  mean =      2.946 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3880 
    [ 1.250,  2.500) = 44436 
    [ 2.500,  3.750) = 257759 
    [ 3.750,  5.000) = 18993 
    [ 5.000,  6.250) = 449 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 60 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.128 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.752 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.973 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.473 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  8.418 ms/op
                 getUser·p0.9999: 12.060 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.352 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.357 ms/op
                 getUser·p0.9999: 12.943 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.082 ms/op
                 getUser·p0.9999: 14.418 ms/op
                 getUser·p1.00:   14.795 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313235
  mean =      3.063 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1522 
    [ 1.250,  2.500) = 21552 
    [ 2.500,  3.750) = 267338 
    [ 3.750,  5.000) = 21695 
    [ 5.000,  6.250) = 632 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.352 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.381 ms/op
     p(99.9900) =     13.064 ms/op
     p(99.9990) =     14.627 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.012 ms/op
Iteration   1: 4.040 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  11.321 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   2: 3.850 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.497 ms/op
                 listUser·p0.9999: 21.442 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.810 ms/op
                 listUser·p0.999:  16.042 ms/op
                 listUser·p0.9999: 19.170 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242199
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4407 
    [ 2.500,  5.000) = 210968 
    [ 5.000,  7.500) = 25750 
    [ 7.500, 10.000) = 617 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     23.482 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.222 ± 3.158  ops/ms
ClientGrpc.existUser                       thrpt       3  10.732 ± 3.097  ops/ms
ClientGrpc.getUser                         thrpt       3  10.271 ± 1.700  ops/ms
ClientGrpc.listUser                        thrpt       3   8.045 ± 2.096  ops/ms
ClientGrpc.createUser                       avgt       3   3.083 ± 0.376   ms/op
ClientGrpc.existUser                        avgt       3   3.024 ± 1.123   ms/op
ClientGrpc.getUser                          avgt       3   3.097 ± 0.467   ms/op
ClientGrpc.listUser                         avgt       3   3.988 ± 0.550   ms/op
ClientGrpc.createUser                     sample  308608   3.112 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.526           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.706           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.813           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.872           ms/op
ClientGrpc.existUser                      sample  325923   2.946 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.551           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.128           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.039           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.957           ms/op
ClientGrpc.getUser                        sample  313235   3.063 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.352           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.381           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.064           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.795           ms/op
ClientGrpc.listUser                       sample  242199   3.967 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.019           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.074           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.972           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.593           ms/op
