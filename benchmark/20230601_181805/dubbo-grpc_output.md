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
# Warmup Iteration   1: 4.074 ops/ms
# Warmup Iteration   2: 9.004 ops/ms
# Warmup Iteration   3: 10.388 ops/ms
Iteration   1: 10.529 ops/ms
Iteration   2: 10.587 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.565 ±(99.9%) 0.563 ops/ms [Average]
  (min, avg, max) = (10.529, 10.565, 10.587), stdev = 0.031
  CI (99.9%): [10.002, 11.128] (assumes normal distribution)


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
# Warmup Iteration   1: 7.448 ops/ms
# Warmup Iteration   2: 10.523 ops/ms
# Warmup Iteration   3: 10.904 ops/ms
Iteration   1: 11.270 ops/ms
Iteration   2: 10.988 ops/ms
Iteration   3: 10.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.031 ±(99.9%) 4.013 ops/ms [Average]
  (min, avg, max) = (10.836, 11.031, 11.270), stdev = 0.220
  CI (99.9%): [7.018, 15.044] (assumes normal distribution)


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
# Warmup Iteration   1: 7.192 ops/ms
# Warmup Iteration   2: 10.089 ops/ms
# Warmup Iteration   3: 10.365 ops/ms
Iteration   1: 10.553 ops/ms
Iteration   2: 10.439 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.497 ±(99.9%) 1.043 ops/ms [Average]
  (min, avg, max) = (10.439, 10.497, 10.553), stdev = 0.057
  CI (99.9%): [9.454, 11.540] (assumes normal distribution)


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
# Warmup Iteration   1: 5.398 ops/ms
# Warmup Iteration   2: 7.753 ops/ms
# Warmup Iteration   3: 7.854 ops/ms
Iteration   1: 7.909 ops/ms
Iteration   2: 7.716 ops/ms
Iteration   3: 7.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.831 ±(99.9%) 1.851 ops/ms [Average]
  (min, avg, max) = (7.716, 7.831, 7.909), stdev = 0.101
  CI (99.9%): [5.980, 9.683] (assumes normal distribution)


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
# Warmup Iteration   1: 4.913 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.002 ms/op
Iteration   1: 3.081 ±(99.9%) 0.002 ms/op
Iteration   2: 3.122 ±(99.9%) 0.001 ms/op
Iteration   3: 3.111 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.105 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (3.081, 3.105, 3.122), stdev = 0.021
  CI (99.9%): [2.716, 3.493] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.917 ±(99.9%) 0.002 ms/op
Iteration   1: 2.944 ±(99.9%) 0.001 ms/op
Iteration   2: 2.942 ±(99.9%) 0.002 ms/op
Iteration   3: 2.868 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.918 ±(99.9%) 0.784 ms/op [Average]
  (min, avg, max) = (2.868, 2.918, 2.944), stdev = 0.043
  CI (99.9%): [2.134, 3.702] (assumes normal distribution)


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
# Warmup Iteration   1: 4.298 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.003 ms/op
Iteration   1: 3.037 ±(99.9%) 0.002 ms/op
Iteration   2: 2.974 ±(99.9%) 0.003 ms/op
Iteration   3: 3.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.005 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (2.974, 3.005, 3.037), stdev = 0.032
  CI (99.9%): [2.424, 3.587] (assumes normal distribution)


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
# Warmup Iteration   1: 5.646 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.017 ms/op
Iteration   1: 3.967 ±(99.9%) 0.020 ms/op
Iteration   2: 3.931 ±(99.9%) 0.016 ms/op
Iteration   3: 3.877 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.925 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (3.877, 3.925, 3.967), stdev = 0.045
  CI (99.9%): [3.097, 4.752] (assumes normal distribution)


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.007 ms/op
Iteration   1: 2.979 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.133 ms/op
                 createUser·p0.999:  6.545 ms/op
                 createUser·p0.9999: 13.292 ms/op
                 createUser·p1.00:   13.517 ms/op

Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  7.809 ms/op
                 createUser·p0.9999: 14.733 ms/op
                 createUser·p1.00:   15.024 ms/op

Iteration   3: 3.107 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  10.124 ms/op
                 createUser·p0.9999: 17.750 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316312
  mean =      3.036 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 600 
    [ 1.250,  2.500) = 20090 
    [ 2.500,  3.750) = 278853 
    [ 3.750,  5.000) = 15175 
    [ 5.000,  6.250) = 838 
    [ 6.250,  7.500) = 352 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      9.580 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.005 ms/op
Iteration   1: 2.953 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   3.961 ms/op
                 existUser·p0.999:  8.084 ms/op
                 existUser·p0.9999: 12.441 ms/op
                 existUser·p1.00:   12.730 ms/op

Iteration   2: 2.934 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  5.555 ms/op
                 existUser·p0.9999: 13.487 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   3: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.334 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  7.262 ms/op
                 existUser·p0.9999: 16.072 ms/op
                 existUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327340
  mean =      2.930 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 366 
    [ 1.250,  2.500) = 28437 
    [ 2.500,  3.750) = 292058 
    [ 3.750,  5.000) = 5643 
    [ 5.000,  6.250) = 300 
    [ 6.250,  7.500) = 237 
    [ 7.500,  8.750) = 107 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      7.280 ms/op
     p(99.9900) =     15.512 ms/op
     p(99.9990) =     16.363 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  9.626 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 2.939 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.548 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.021 ms/op
                 getUser·p0.9999: 15.013 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.692 ms/op
                 getUser·p0.9999: 16.754 ms/op
                 getUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322644
  mean =      2.977 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2063 
    [ 1.250,  2.500) = 28617 
    [ 2.500,  3.750) = 276800 
    [ 3.750,  5.000) = 13566 
    [ 5.000,  6.250) = 819 
    [ 6.250,  7.500) = 371 
    [ 7.500,  8.750) = 142 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     18.291 ms/op
     p(99.9990) =     19.391 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 5.452 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.011 ms/op
Iteration   1: 3.937 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.009 ms/op
                 listUser·p0.9999: 20.804 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   2: 3.837 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 16.663 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   3: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.357 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 19.850 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245349
  mean =      3.912 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2584 
    [ 2.500,  5.000) = 222096 
    [ 5.000,  7.500) = 19568 
    [ 7.500, 10.000) = 711 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     20.251 ms/op
     p(99.9990) =     21.073 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.565 ± 0.563  ops/ms
ClientGrpc.existUser                       thrpt       3  11.031 ± 4.013  ops/ms
ClientGrpc.getUser                         thrpt       3  10.497 ± 1.043  ops/ms
ClientGrpc.listUser                        thrpt       3   7.831 ± 1.851  ops/ms
ClientGrpc.createUser                       avgt       3   3.105 ± 0.389   ms/op
ClientGrpc.existUser                        avgt       3   2.918 ± 0.784   ms/op
ClientGrpc.getUser                          avgt       3   3.005 ± 0.581   ms/op
ClientGrpc.listUser                         avgt       3   3.925 ± 0.828   ms/op
ClientGrpc.createUser                     sample  316312   3.036 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.691           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.580           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.105           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.055           ms/op
ClientGrpc.existUser                      sample  327340   2.930 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.606           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.280           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.512           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.400           ms/op
ClientGrpc.getUser                        sample  322644   2.977 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.548           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.176           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.291           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.497           ms/op
ClientGrpc.listUser                       sample  245349   3.912 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.357           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.795           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.251           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.168           ms/op
