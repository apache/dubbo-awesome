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
# Warmup Iteration   1: 4.082 ops/ms
# Warmup Iteration   2: 8.645 ops/ms
# Warmup Iteration   3: 10.008 ops/ms
Iteration   1: 10.154 ops/ms
Iteration   2: 10.458 ops/ms
Iteration   3: 10.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.478 ±(99.9%) 6.097 ops/ms [Average]
  (min, avg, max) = (10.154, 10.478, 10.822), stdev = 0.334
  CI (99.9%): [4.381, 16.576] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.418 ops/ms
# Warmup Iteration   2: 10.287 ops/ms
# Warmup Iteration   3: 10.849 ops/ms
Iteration   1: 10.908 ops/ms
Iteration   2: 11.025 ops/ms
Iteration   3: 11.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.026 ±(99.9%) 2.163 ops/ms [Average]
  (min, avg, max) = (10.908, 11.026, 11.145), stdev = 0.119
  CI (99.9%): [8.863, 13.189] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.980 ops/ms
# Warmup Iteration   2: 10.205 ops/ms
# Warmup Iteration   3: 10.419 ops/ms
Iteration   1: 10.548 ops/ms
Iteration   2: 10.473 ops/ms
Iteration   3: 10.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.450 ±(99.9%) 2.034 ops/ms [Average]
  (min, avg, max) = (10.329, 10.450, 10.548), stdev = 0.111
  CI (99.9%): [8.417, 12.484] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.674 ops/ms
# Warmup Iteration   2: 7.573 ops/ms
# Warmup Iteration   3: 7.988 ops/ms
Iteration   1: 7.865 ops/ms
Iteration   2: 7.886 ops/ms
Iteration   3: 7.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.859 ±(99.9%) 0.534 ops/ms [Average]
  (min, avg, max) = (7.828, 7.859, 7.886), stdev = 0.029
  CI (99.9%): [7.326, 8.393] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.303 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.004 ms/op
Iteration   1: 3.060 ±(99.9%) 0.003 ms/op
Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
Iteration   3: 3.057 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.069 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.057, 3.069, 3.089), stdev = 0.018
  CI (99.9%): [2.747, 3.390] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.948 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.003 ms/op
Iteration   1: 2.979 ±(99.9%) 0.002 ms/op
Iteration   2: 2.914 ±(99.9%) 0.003 ms/op
Iteration   3: 2.919 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.937 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (2.914, 2.937, 2.979), stdev = 0.036
  CI (99.9%): [2.283, 3.591] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.297 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.004 ms/op
Iteration   1: 3.072 ±(99.9%) 0.003 ms/op
Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
Iteration   3: 3.042 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (3.042, 3.062, 3.072), stdev = 0.017
  CI (99.9%): [2.749, 3.375] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.217 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.014 ms/op
Iteration   1: 4.017 ±(99.9%) 0.007 ms/op
Iteration   2: 4.016 ±(99.9%) 0.009 ms/op
Iteration   3: 4.081 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.038 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (4.016, 4.038, 4.081), stdev = 0.037
  CI (99.9%): [3.365, 4.711] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.456 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.006 ms/op
Iteration   1: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  10.430 ms/op
                 createUser·p0.9999: 13.845 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  7.801 ms/op
                 createUser·p0.9999: 16.499 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   3: 3.126 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  9.311 ms/op
                 createUser·p0.9999: 28.969 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310843
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21856 
    [ 2.500,  5.000) = 286483 
    [ 5.000,  7.500) = 1873 
    [ 7.500, 10.000) = 341 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      9.136 ms/op
     p(99.9900) =     26.796 ms/op
     p(99.9990) =     29.160 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.944 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 2.924 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.894 ms/op
                 existUser·p0.9999: 12.879 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   2: 2.968 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  8.733 ms/op
                 existUser·p0.9999: 13.180 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   3: 2.912 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 16.466 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326769
  mean =      2.935 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1647 
    [ 1.250,  2.500) = 36048 
    [ 2.500,  3.750) = 279067 
    [ 3.750,  5.000) = 8169 
    [ 5.000,  6.250) = 951 
    [ 6.250,  7.500) = 360 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     15.647 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.509 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
Iteration   1: 3.101 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.577 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  8.013 ms/op
                 getUser·p0.9999: 19.039 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  9.476 ms/op
                 getUser·p0.9999: 14.920 ms/op
                 getUser·p1.00:   15.892 ms/op

Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.094 ms/op
                 getUser·p0.9999: 15.925 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311905
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 937 
    [ 1.250,  2.500) = 17705 
    [ 2.500,  3.750) = 272711 
    [ 3.750,  5.000) = 18431 
    [ 5.000,  6.250) = 1077 
    [ 6.250,  7.500) = 599 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.071 ms/op
     p(99.9900) =     17.885 ms/op
     p(99.9990) =     19.325 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 5.331 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.011 ms/op
Iteration   1: 4.125 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.237 ms/op
                 listUser·p0.999:  14.850 ms/op
                 listUser·p0.9999: 22.887 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   2: 4.094 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 17.576 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 4.066 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  19.343 ms/op
                 listUser·p0.9999: 23.728 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234513
  mean =      4.095 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2477 
    [ 2.500,  5.000) = 203985 
    [ 5.000,  7.500) = 26104 
    [ 7.500, 10.000) = 1393 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     15.720 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     24.279 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.478 ± 6.097  ops/ms
ClientGrpc.existUser                       thrpt       3  11.026 ± 2.163  ops/ms
ClientGrpc.getUser                         thrpt       3  10.450 ± 2.034  ops/ms
ClientGrpc.listUser                        thrpt       3   7.859 ± 0.534  ops/ms
ClientGrpc.createUser                       avgt       3   3.069 ± 0.322   ms/op
ClientGrpc.existUser                        avgt       3   2.937 ± 0.654   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 0.313   ms/op
ClientGrpc.listUser                         avgt       3   4.038 ± 0.673   ms/op
ClientGrpc.createUser                     sample  310843   3.089 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.683           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.136           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.796           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.295           ms/op
ClientGrpc.existUser                      sample  326769   2.935 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.589           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.684           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.647           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.285           ms/op
ClientGrpc.getUser                        sample  311905   3.078 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.577           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.071           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.885           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.333           ms/op
ClientGrpc.listUser                       sample  234513   4.095 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.993           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.283           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.720           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.429           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.478           ms/op
