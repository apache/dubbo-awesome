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
# Warmup Iteration   1: 4.524 ops/ms
# Warmup Iteration   2: 9.211 ops/ms
# Warmup Iteration   3: 10.079 ops/ms
Iteration   1: 10.518 ops/ms
Iteration   2: 10.525 ops/ms
Iteration   3: 10.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.459 ±(99.9%) 1.975 ops/ms [Average]
  (min, avg, max) = (10.334, 10.459, 10.525), stdev = 0.108
  CI (99.9%): [8.484, 12.433] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.514 ops/ms
# Warmup Iteration   2: 10.750 ops/ms
# Warmup Iteration   3: 10.992 ops/ms
Iteration   1: 11.096 ops/ms
Iteration   2: 11.168 ops/ms
Iteration   3: 11.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.123 ±(99.9%) 0.718 ops/ms [Average]
  (min, avg, max) = (11.096, 11.123, 11.168), stdev = 0.039
  CI (99.9%): [10.405, 11.841] (assumes normal distribution)


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
# Warmup Iteration   1: 7.239 ops/ms
# Warmup Iteration   2: 10.365 ops/ms
# Warmup Iteration   3: 10.435 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.637 ops/ms
Iteration   3: 10.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.620 ±(99.9%) 0.272 ops/ms [Average]
  (min, avg, max) = (10.609, 10.620, 10.637), stdev = 0.015
  CI (99.9%): [10.348, 10.892] (assumes normal distribution)


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
# Warmup Iteration   1: 5.708 ops/ms
# Warmup Iteration   2: 8.046 ops/ms
# Warmup Iteration   3: 8.194 ops/ms
Iteration   1: 8.312 ops/ms
Iteration   2: 8.328 ops/ms
Iteration   3: 8.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.282 ±(99.9%) 1.214 ops/ms [Average]
  (min, avg, max) = (8.205, 8.282, 8.328), stdev = 0.067
  CI (99.9%): [7.067, 9.496] (assumes normal distribution)


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.002 ms/op
Iteration   1: 2.974 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
Iteration   3: 3.019 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.004 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (2.974, 3.004, 3.019), stdev = 0.026
  CI (99.9%): [2.533, 3.475] (assumes normal distribution)


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.004 ms/op
Iteration   2: 2.897 ±(99.9%) 0.004 ms/op
Iteration   3: 2.932 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.930 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (2.897, 2.930, 2.961), stdev = 0.032
  CI (99.9%): [2.345, 3.514] (assumes normal distribution)


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.003 ms/op
Iteration   1: 3.046 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.002 ms/op
Iteration   3: 2.990 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.027 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (2.990, 3.027, 3.046), stdev = 0.032
  CI (99.9%): [2.451, 3.603] (assumes normal distribution)


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
# Warmup Iteration   1: 4.844 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.025 ms/op
Iteration   1: 3.928 ±(99.9%) 0.018 ms/op
Iteration   2: 3.856 ±(99.9%) 0.010 ms/op
Iteration   3: 3.892 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (3.856, 3.892, 3.928), stdev = 0.036
  CI (99.9%): [3.239, 4.545] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
Iteration   1: 3.036 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.327 ms/op
                 createUser·p0.9999: 13.058 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  8.004 ms/op
                 createUser·p0.9999: 18.528 ms/op
                 createUser·p1.00:   19.137 ms/op

Iteration   3: 2.975 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.564 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  11.420 ms/op
                 createUser·p0.9999: 19.128 ms/op
                 createUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318472
  mean =      3.012 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29319 
    [ 2.500,  5.000) = 287183 
    [ 5.000,  7.500) = 1360 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     10.143 ms/op
     p(99.9900) =     18.781 ms/op
     p(99.9990) =     26.274 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
Iteration   1: 2.868 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.857 ms/op
                 existUser·p0.9999: 11.125 ms/op
                 existUser·p1.00:   11.600 ms/op

Iteration   2: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  7.730 ms/op
                 existUser·p0.9999: 13.633 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.643 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.667 ms/op
                 existUser·p0.9999: 15.068 ms/op
                 existUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330899
  mean =      2.898 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2728 
    [ 1.250,  2.500) = 35644 
    [ 2.500,  3.750) = 281613 
    [ 3.750,  5.000) = 9320 
    [ 5.000,  6.250) = 834 
    [ 6.250,  7.500) = 436 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.480 ms/op
     p(99.9900) =     13.794 ms/op
     p(99.9990) =     15.374 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
Iteration   1: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.572 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.716 ms/op
                 getUser·p0.9999: 12.657 ms/op
                 getUser·p1.00:   12.894 ms/op

Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.744 ms/op
                 getUser·p0.9999: 14.433 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.933 ms/op
                 getUser·p0.9999: 24.201 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314948
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19305 
    [ 2.500,  5.000) = 293837 
    [ 5.000,  7.500) = 1393 
    [ 7.500, 10.000) = 252 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     23.529 ms/op
     p(99.9990) =     24.543 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 5.565 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.012 ms/op
Iteration   1: 3.978 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.353 ms/op
                 listUser·p0.999:  12.820 ms/op
                 listUser·p0.9999: 15.071 ms/op
                 listUser·p1.00:   15.876 ms/op

Iteration   2: 3.904 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   3: 3.889 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.771 ms/op
                 listUser·p0.9999: 15.481 ms/op
                 listUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244684
  mean =      3.923 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3618 
    [ 2.500,  5.000) = 219203 
    [ 5.000,  7.500) = 20225 
    [ 7.500, 10.000) = 1058 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 278 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     24.514 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.459 ± 1.975  ops/ms
ClientGrpc.existUser                       thrpt       3  11.123 ± 0.718  ops/ms
ClientGrpc.getUser                         thrpt       3  10.620 ± 0.272  ops/ms
ClientGrpc.listUser                        thrpt       3   8.282 ± 1.214  ops/ms
ClientGrpc.createUser                       avgt       3   3.004 ± 0.471   ms/op
ClientGrpc.existUser                        avgt       3   2.930 ± 0.584   ms/op
ClientGrpc.getUser                          avgt       3   3.027 ± 0.576   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 0.653   ms/op
ClientGrpc.createUser                     sample  318472   3.012 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.564           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.143           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.781           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.280           ms/op
ClientGrpc.existUser                      sample  330899   2.898 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.667           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.480           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.794           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.483           ms/op
ClientGrpc.getUser                        sample  314948   3.044 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.572           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.815           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.529           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.609           ms/op
ClientGrpc.listUser                       sample  244684   3.923 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.809           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.041           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.381           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.674           ms/op
