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
# Warmup Iteration   1: 4.010 ops/ms
# Warmup Iteration   2: 9.040 ops/ms
# Warmup Iteration   3: 10.070 ops/ms
Iteration   1: 10.358 ops/ms
Iteration   2: 10.607 ops/ms
Iteration   3: 10.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.507 ±(99.9%) 2.402 ops/ms [Average]
  (min, avg, max) = (10.358, 10.507, 10.607), stdev = 0.132
  CI (99.9%): [8.106, 12.909] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.510 ops/ms
# Warmup Iteration   2: 10.423 ops/ms
# Warmup Iteration   3: 11.162 ops/ms
Iteration   1: 10.758 ops/ms
Iteration   2: 11.228 ops/ms
Iteration   3: 11.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.070 ±(99.9%) 4.924 ops/ms [Average]
  (min, avg, max) = (10.758, 11.070, 11.228), stdev = 0.270
  CI (99.9%): [6.146, 15.994] (assumes normal distribution)


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
# Warmup Iteration   1: 6.420 ops/ms
# Warmup Iteration   2: 10.111 ops/ms
# Warmup Iteration   3: 10.545 ops/ms
Iteration   1: 10.499 ops/ms
Iteration   2: 10.531 ops/ms
Iteration   3: 10.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.571 ±(99.9%) 1.788 ops/ms [Average]
  (min, avg, max) = (10.499, 10.571, 10.683), stdev = 0.098
  CI (99.9%): [8.783, 12.359] (assumes normal distribution)


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
# Warmup Iteration   1: 5.822 ops/ms
# Warmup Iteration   2: 7.562 ops/ms
# Warmup Iteration   3: 8.020 ops/ms
Iteration   1: 7.858 ops/ms
Iteration   2: 8.114 ops/ms
Iteration   3: 8.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.068 ±(99.9%) 3.492 ops/ms [Average]
  (min, avg, max) = (7.858, 8.068, 8.232), stdev = 0.191
  CI (99.9%): [4.576, 11.560] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.515 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.040 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.002 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.025 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (2.992, 3.025, 3.044), stdev = 0.029
  CI (99.9%): [2.499, 3.552] (assumes normal distribution)


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.002 ms/op
Iteration   1: 2.860 ±(99.9%) 0.002 ms/op
Iteration   2: 2.886 ±(99.9%) 0.003 ms/op
Iteration   3: 2.937 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (2.860, 2.894, 2.937), stdev = 0.039
  CI (99.9%): [2.186, 3.603] (assumes normal distribution)


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
# Warmup Iteration   1: 4.147 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.004 ms/op
Iteration   1: 3.037 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
Iteration   3: 3.030 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.031 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (3.025, 3.031, 3.037), stdev = 0.006
  CI (99.9%): [2.922, 3.140] (assumes normal distribution)


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
# Warmup Iteration   1: 4.824 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.009 ms/op
Iteration   1: 3.998 ±(99.9%) 0.013 ms/op
Iteration   2: 3.957 ±(99.9%) 0.018 ms/op
Iteration   3: 3.858 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.938 ±(99.9%) 1.315 ms/op [Average]
  (min, avg, max) = (3.858, 3.938, 3.998), stdev = 0.072
  CI (99.9%): [2.623, 5.252] (assumes normal distribution)


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
# Warmup Iteration   1: 4.436 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.318 ms/op
                 createUser·p0.999:  6.521 ms/op
                 createUser·p0.9999: 18.088 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  7.043 ms/op
                 createUser·p0.9999: 19.196 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  11.043 ms/op
                 createUser·p0.9999: 23.331 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318934
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24561 
    [ 2.500,  5.000) = 292743 
    [ 5.000,  7.500) = 1279 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.437 ms/op
     p(99.9000) =      7.783 ms/op
     p(99.9900) =     22.471 ms/op
     p(99.9990) =     23.652 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.006 ms/op
Iteration   1: 2.925 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  5.846 ms/op
                 existUser·p0.9999: 12.487 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.873 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  7.201 ms/op
                 existUser·p0.9999: 19.001 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   3: 2.885 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  6.603 ms/op
                 existUser·p0.9999: 17.298 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331787
  mean =      2.894 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 913 
    [ 1.250,  2.500) = 35001 
    [ 2.500,  3.750) = 288560 
    [ 3.750,  5.000) = 6339 
    [ 5.000,  6.250) = 585 
    [ 6.250,  7.500) = 153 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      6.564 ms/op
     p(99.9900) =     17.525 ms/op
     p(99.9990) =     19.355 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 4.333 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 2.972 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.314 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.650 ms/op
                 getUser·p0.9999: 13.173 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   2: 2.970 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  6.744 ms/op
                 getUser·p0.9999: 17.592 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   3: 2.990 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  12.288 ms/op
                 getUser·p0.9999: 19.661 ms/op
                 getUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322357
  mean =      2.977 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21443 
    [ 2.500,  5.000) = 299369 
    [ 5.000,  7.500) = 1208 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.690 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     19.916 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 5.610 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.013 ms/op
Iteration   1: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  13.832 ms/op
                 listUser·p0.9999: 19.165 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 4.003 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.817 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  16.283 ms/op
                 listUser·p0.9999: 24.411 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   3: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 24.606 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241382
  mean =      3.979 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2638 
    [ 2.500,  5.000) = 216619 
    [ 5.000,  7.500) = 20943 
    [ 7.500, 10.000) = 811 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     15.755 ms/op
     p(99.9900) =     24.211 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.507 ± 2.402  ops/ms
ClientGrpc.existUser                       thrpt       3  11.070 ± 4.924  ops/ms
ClientGrpc.getUser                         thrpt       3  10.571 ± 1.788  ops/ms
ClientGrpc.listUser                        thrpt       3   8.068 ± 3.492  ops/ms
ClientGrpc.createUser                       avgt       3   3.025 ± 0.527   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.708   ms/op
ClientGrpc.getUser                          avgt       3   3.031 ± 0.109   ms/op
ClientGrpc.listUser                         avgt       3   3.938 ± 1.315   ms/op
ClientGrpc.createUser                     sample  318934   3.010 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.744           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.437           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.783           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.471           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.281           ms/op
ClientGrpc.existUser                      sample  331787   2.894 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.733           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.564           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.525           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.431           ms/op
ClientGrpc.getUser                        sample  322357   2.977 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.801           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.690           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.038           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.120           ms/op
ClientGrpc.listUser                       sample  241382   3.979 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.817           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.755           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.211           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
