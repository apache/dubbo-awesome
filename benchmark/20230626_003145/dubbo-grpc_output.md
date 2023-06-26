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
# Warmup Iteration   1: 4.419 ops/ms
# Warmup Iteration   2: 9.129 ops/ms
# Warmup Iteration   3: 10.001 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.631 ops/ms
Iteration   3: 10.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.703 ±(99.9%) 2.039 ops/ms [Average]
  (min, avg, max) = (10.631, 10.703, 10.832), stdev = 0.112
  CI (99.9%): [8.665, 12.742] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.259 ops/ms
# Warmup Iteration   2: 10.528 ops/ms
# Warmup Iteration   3: 11.256 ops/ms
Iteration   1: 11.058 ops/ms
Iteration   2: 10.987 ops/ms
Iteration   3: 11.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.020 ±(99.9%) 0.652 ops/ms [Average]
  (min, avg, max) = (10.987, 11.020, 11.058), stdev = 0.036
  CI (99.9%): [10.368, 11.671] (assumes normal distribution)


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
# Warmup Iteration   1: 7.307 ops/ms
# Warmup Iteration   2: 10.220 ops/ms
# Warmup Iteration   3: 10.403 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.641 ops/ms
Iteration   3: 10.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.605 ±(99.9%) 0.570 ops/ms [Average]
  (min, avg, max) = (10.583, 10.605, 10.641), stdev = 0.031
  CI (99.9%): [10.034, 11.175] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.504 ops/ms
# Warmup Iteration   2: 7.551 ops/ms
# Warmup Iteration   3: 8.021 ops/ms
Iteration   1: 8.045 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.089 ±(99.9%) 0.833 ops/ms [Average]
  (min, avg, max) = (8.045, 8.089, 8.136), stdev = 0.046
  CI (99.9%): [7.256, 8.921] (assumes normal distribution)


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
# Warmup Iteration   1: 4.170 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.097 ±(99.9%) 0.002 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.045 ±(99.9%) 0.846 ms/op [Average]
  (min, avg, max) = (3.006, 3.045, 3.097), stdev = 0.046
  CI (99.9%): [2.199, 3.892] (assumes normal distribution)


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
# Warmup Iteration   1: 3.458 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.858 ±(99.9%) 0.002 ms/op
Iteration   1: 2.736 ±(99.9%) 0.003 ms/op
Iteration   2: 2.858 ±(99.9%) 0.003 ms/op
Iteration   3: 2.841 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.812 ±(99.9%) 1.210 ms/op [Average]
  (min, avg, max) = (2.736, 2.812, 2.858), stdev = 0.066
  CI (99.9%): [1.601, 4.022] (assumes normal distribution)


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.004 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
Iteration   3: 3.046 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.030 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (3.005, 3.030, 3.046), stdev = 0.022
  CI (99.9%): [2.632, 3.428] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.639 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.008 ms/op
Iteration   1: 4.018 ±(99.9%) 0.038 ms/op
Iteration   2: 4.007 ±(99.9%) 0.023 ms/op
Iteration   3: 3.993 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.006 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (3.993, 4.006, 4.018), stdev = 0.013
  CI (99.9%): [3.773, 4.240] (assumes normal distribution)


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
# Warmup Iteration   1: 4.271 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.282 ms/op
                 createUser·p0.9999: 12.336 ms/op
                 createUser·p1.00:   12.632 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  9.611 ms/op
                 createUser·p0.9999: 18.726 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  9.648 ms/op
                 createUser·p0.9999: 16.073 ms/op
                 createUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315859
  mean =      3.042 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 561 
    [ 1.250,  2.500) = 19886 
    [ 2.500,  3.750) = 279994 
    [ 3.750,  5.000) = 13747 
    [ 5.000,  6.250) = 903 
    [ 6.250,  7.500) = 285 
    [ 7.500,  8.750) = 132 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     18.902 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.890 ±(99.9%) 0.005 ms/op
Iteration   1: 2.839 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 12.272 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   2: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  8.026 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.897 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  7.046 ms/op
                 existUser·p0.9999: 29.295 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333362
  mean =      2.880 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40318 
    [ 2.500,  5.000) = 291866 
    [ 5.000,  7.500) = 776 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      8.094 ms/op
     p(99.9900) =     15.405 ms/op
     p(99.9990) =     29.513 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.444 ms/op
                 getUser·p0.9999: 17.629 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.805 ms/op
                 getUser·p0.9999: 15.340 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.314 ms/op
                 getUser·p0.9999: 27.591 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314505
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21155 
    [ 2.500,  5.000) = 292011 
    [ 5.000,  7.500) = 1030 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =     26.822 ms/op
     p(99.9990) =     27.778 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 4.694 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.011 ms/op
Iteration   1: 3.970 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.221 ms/op
                 listUser·p0.9999: 16.280 ms/op
                 listUser·p1.00:   16.695 ms/op

Iteration   2: 3.962 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.565 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 3.989 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.648 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  20.689 ms/op
                 listUser·p0.9999: 30.571 ms/op
                 listUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241407
  mean =      3.974 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2283 
    [ 2.500,  5.000) = 219433 
    [ 5.000,  7.500) = 18487 
    [ 7.500, 10.000) = 795 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     26.238 ms/op
     p(99.9990) =     30.827 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.703 ± 2.039  ops/ms
ClientGrpc.existUser                       thrpt       3  11.020 ± 0.652  ops/ms
ClientGrpc.getUser                         thrpt       3  10.605 ± 0.570  ops/ms
ClientGrpc.listUser                        thrpt       3   8.089 ± 0.833  ops/ms
ClientGrpc.createUser                       avgt       3   3.045 ± 0.846   ms/op
ClientGrpc.existUser                        avgt       3   2.812 ± 1.210   ms/op
ClientGrpc.getUser                          avgt       3   3.030 ± 0.398   ms/op
ClientGrpc.listUser                         avgt       3   4.006 ± 0.233   ms/op
ClientGrpc.createUser                     sample  315859   3.042 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.726           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.224           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.793           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.973           ms/op
ClientGrpc.existUser                      sample  333362   2.880 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.708           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.094           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.405           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.590           ms/op
ClientGrpc.getUser                        sample  314505   3.052 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.758           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.487           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.822           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.886           ms/op
ClientGrpc.listUser                       sample  241407   3.974 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.648           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.713           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.238           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.867           ms/op
