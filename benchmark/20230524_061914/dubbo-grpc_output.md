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
# Warmup Iteration   1: 4.354 ops/ms
# Warmup Iteration   2: 9.360 ops/ms
# Warmup Iteration   3: 10.073 ops/ms
Iteration   1: 10.515 ops/ms
Iteration   2: 10.368 ops/ms
Iteration   3: 10.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.457 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (10.368, 10.457, 10.515), stdev = 0.078
  CI (99.9%): [9.040, 11.873] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.591 ops/ms
# Warmup Iteration   2: 10.794 ops/ms
# Warmup Iteration   3: 10.996 ops/ms
Iteration   1: 10.857 ops/ms
Iteration   2: 11.066 ops/ms
Iteration   3: 11.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.000 ±(99.9%) 2.261 ops/ms [Average]
  (min, avg, max) = (10.857, 11.000, 11.077), stdev = 0.124
  CI (99.9%): [8.739, 13.261] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.239 ops/ms
# Warmup Iteration   2: 10.143 ops/ms
# Warmup Iteration   3: 10.424 ops/ms
Iteration   1: 10.537 ops/ms
Iteration   2: 10.660 ops/ms
Iteration   3: 10.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.588 ±(99.9%) 1.174 ops/ms [Average]
  (min, avg, max) = (10.537, 10.588, 10.660), stdev = 0.064
  CI (99.9%): [9.413, 11.762] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.596 ops/ms
# Warmup Iteration   2: 7.994 ops/ms
# Warmup Iteration   3: 7.986 ops/ms
Iteration   1: 8.070 ops/ms
Iteration   2: 8.454 ops/ms
Iteration   3: 8.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.231 ±(99.9%) 3.641 ops/ms [Average]
  (min, avg, max) = (8.070, 8.231, 8.454), stdev = 0.200
  CI (99.9%): [4.591, 11.872] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.003 ms/op
Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
Iteration   3: 3.048 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.026 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (3.003, 3.026, 3.048), stdev = 0.023
  CI (99.9%): [2.612, 3.441] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.003 ms/op
Iteration   1: 2.916 ±(99.9%) 0.003 ms/op
Iteration   2: 2.855 ±(99.9%) 0.003 ms/op
Iteration   3: 2.946 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.906 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (2.855, 2.906, 2.946), stdev = 0.046
  CI (99.9%): [2.058, 3.754] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.080 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.002 ms/op
Iteration   1: 3.003 ±(99.9%) 0.002 ms/op
Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
Iteration   3: 2.979 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.974 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (2.939, 2.974, 3.003), stdev = 0.032
  CI (99.9%): [2.383, 3.564] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.474 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.010 ms/op
Iteration   1: 3.907 ±(99.9%) 0.054 ms/op
Iteration   2: 3.894 ±(99.9%) 0.013 ms/op
Iteration   3: 3.878 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.893 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.878, 3.893, 3.907), stdev = 0.014
  CI (99.9%): [3.631, 4.155] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.053 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.031 ms/op
                 createUser·p0.9999: 11.835 ms/op
                 createUser·p1.00:   12.124 ms/op

Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  8.194 ms/op
                 createUser·p0.9999: 15.371 ms/op
                 createUser·p1.00:   15.761 ms/op

Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  9.767 ms/op
                 createUser·p0.9999: 16.085 ms/op
                 createUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319790
  mean =      3.002 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1194 
    [ 1.250,  2.500) = 22407 
    [ 2.500,  3.750) = 283190 
    [ 3.750,  5.000) = 11783 
    [ 5.000,  6.250) = 597 
    [ 6.250,  7.500) = 216 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     15.319 ms/op
     p(99.9990) =     16.473 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.598 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.843 ±(99.9%) 0.006 ms/op
Iteration   1: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  7.242 ms/op
                 existUser·p0.9999: 17.267 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   2: 2.829 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  6.587 ms/op
                 existUser·p0.9999: 14.752 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.476 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  11.747 ms/op
                 existUser·p0.9999: 14.390 ms/op
                 existUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332376
  mean =      2.886 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2606 
    [ 1.250,  2.500) = 39658 
    [ 2.500,  3.750) = 281237 
    [ 3.750,  5.000) = 7833 
    [ 5.000,  6.250) = 508 
    [ 6.250,  7.500) = 191 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.648 ms/op
     p(99.9900) =     15.045 ms/op
     p(99.9990) =     17.389 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  6.232 ms/op
                 getUser·p0.9999: 18.260 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.639 ms/op
                 getUser·p0.9999: 12.981 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   3: 2.990 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.232 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  8.365 ms/op
                 getUser·p0.9999: 24.760 ms/op
                 getUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321785
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28817 
    [ 2.500,  5.000) = 291786 
    [ 5.000,  7.500) = 864 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.232 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.411 ms/op
     p(99.9900) =     23.090 ms/op
     p(99.9990) =     25.053 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 5.439 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.010 ms/op
Iteration   1: 3.905 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  11.239 ms/op
                 listUser·p0.9999: 14.805 ms/op
                 listUser·p1.00:   16.105 ms/op

Iteration   2: 3.760 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   3: 3.900 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  13.074 ms/op
                 listUser·p0.9999: 16.082 ms/op
                 listUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249060
  mean =      3.854 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2899 
    [ 2.500,  5.000) = 228193 
    [ 5.000,  7.500) = 16870 
    [ 7.500, 10.000) = 688 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     18.976 ms/op
     p(99.9990) =     20.530 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.457 ± 1.416  ops/ms
ClientGrpc.existUser                       thrpt       3  11.000 ± 2.261  ops/ms
ClientGrpc.getUser                         thrpt       3  10.588 ± 1.174  ops/ms
ClientGrpc.listUser                        thrpt       3   8.231 ± 3.641  ops/ms
ClientGrpc.createUser                       avgt       3   3.026 ± 0.414   ms/op
ClientGrpc.existUser                        avgt       3   2.906 ± 0.848   ms/op
ClientGrpc.getUser                          avgt       3   2.974 ± 0.591   ms/op
ClientGrpc.listUser                         avgt       3   3.893 ± 0.262   ms/op
ClientGrpc.createUser                     sample  319790   3.002 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.672           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.897           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.319           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.581           ms/op
ClientGrpc.existUser                      sample  332376   2.886 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.476           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.648           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.045           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.433           ms/op
ClientGrpc.getUser                        sample  321785   2.983 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.232           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.411           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.090           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.133           ms/op
ClientGrpc.listUser                       sample  249060   3.854 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.225           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.861           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.976           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.578           ms/op
