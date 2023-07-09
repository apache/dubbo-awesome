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
# Warmup Iteration   1: 3.915 ops/ms
# Warmup Iteration   2: 8.367 ops/ms
# Warmup Iteration   3: 9.824 ops/ms
Iteration   1: 10.149 ops/ms
Iteration   2: 10.271 ops/ms
Iteration   3: 10.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.241 ±(99.9%) 1.479 ops/ms [Average]
  (min, avg, max) = (10.149, 10.241, 10.302), stdev = 0.081
  CI (99.9%): [8.762, 11.719] (assumes normal distribution)


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
# Warmup Iteration   1: 7.339 ops/ms
# Warmup Iteration   2: 10.286 ops/ms
# Warmup Iteration   3: 10.982 ops/ms
Iteration   1: 10.761 ops/ms
Iteration   2: 10.943 ops/ms
Iteration   3: 10.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.855 ±(99.9%) 1.665 ops/ms [Average]
  (min, avg, max) = (10.761, 10.855, 10.943), stdev = 0.091
  CI (99.9%): [9.190, 12.520] (assumes normal distribution)


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
# Warmup Iteration   1: 6.669 ops/ms
# Warmup Iteration   2: 9.913 ops/ms
# Warmup Iteration   3: 10.110 ops/ms
Iteration   1: 10.248 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 10.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.280 ±(99.9%) 2.555 ops/ms [Average]
  (min, avg, max) = (10.160, 10.280, 10.434), stdev = 0.140
  CI (99.9%): [7.725, 12.835] (assumes normal distribution)


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
# Warmup Iteration   1: 6.082 ops/ms
# Warmup Iteration   2: 7.224 ops/ms
# Warmup Iteration   3: 7.582 ops/ms
Iteration   1: 7.523 ops/ms
Iteration   2: 7.901 ops/ms
Iteration   3: 7.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.699 ±(99.9%) 3.471 ops/ms [Average]
  (min, avg, max) = (7.523, 7.699, 7.901), stdev = 0.190
  CI (99.9%): [4.227, 11.170] (assumes normal distribution)


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
# Warmup Iteration   1: 4.234 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.002 ms/op
Iteration   2: 3.060 ±(99.9%) 0.001 ms/op
Iteration   3: 3.122 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.090 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (3.060, 3.090, 3.122), stdev = 0.031
  CI (99.9%): [2.521, 3.658] (assumes normal distribution)


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
# Warmup Iteration   1: 4.350 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.002 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.868 ±(99.9%) 0.002 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.956 ±(99.9%) 1.407 ms/op [Average]
  (min, avg, max) = (2.868, 2.956, 3.013), stdev = 0.077
  CI (99.9%): [1.549, 4.363] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.003 ms/op
Iteration   1: 3.118 ±(99.9%) 0.002 ms/op
Iteration   2: 3.056 ±(99.9%) 0.004 ms/op
Iteration   3: 3.047 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.074 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (3.047, 3.074, 3.118), stdev = 0.038
  CI (99.9%): [2.376, 3.771] (assumes normal distribution)


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
# Warmup Iteration   1: 5.027 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.423 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.190 ±(99.9%) 0.009 ms/op
Iteration   1: 4.120 ±(99.9%) 0.018 ms/op
Iteration   2: 4.081 ±(99.9%) 0.022 ms/op
Iteration   3: 4.159 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.120 ±(99.9%) 0.711 ms/op [Average]
  (min, avg, max) = (4.081, 4.120, 4.159), stdev = 0.039
  CI (99.9%): [3.410, 4.831] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  11.796 ms/op
                 createUser·p0.9999: 13.740 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.684 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  10.977 ms/op
                 createUser·p0.9999: 17.274 ms/op
                 createUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309020
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16862 
    [ 2.500,  5.000) = 289980 
    [ 5.000,  7.500) = 1586 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =     10.796 ms/op
     p(99.9900) =     21.142 ms/op
     p(99.9990) =     22.765 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.007 ms/op
Iteration   1: 2.904 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  7.429 ms/op
                 existUser·p0.9999: 16.777 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.378 ms/op
                 existUser·p0.9999: 14.189 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 2.946 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.554 ms/op
                 existUser·p0.9999: 17.555 ms/op
                 existUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327054
  mean =      2.935 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1988 
    [ 1.250,  2.500) = 36413 
    [ 2.500,  3.750) = 278464 
    [ 3.750,  5.000) = 8941 
    [ 5.000,  6.250) = 812 
    [ 6.250,  7.500) = 230 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 63 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.643 ms/op
     p(99.9900) =     17.049 ms/op
     p(99.9990) =     18.282 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 4.397 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.006 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.889 ms/op
                 getUser·p0.9999: 12.102 ms/op
                 getUser·p1.00:   12.403 ms/op

Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.047 ms/op
                 getUser·p0.9999: 15.024 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   3: 3.101 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.528 ms/op
                 getUser·p0.9999: 16.707 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310056
  mean =      3.094 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 234 
    [ 1.250,  2.500) = 13836 
    [ 2.500,  3.750) = 276280 
    [ 3.750,  5.000) = 18085 
    [ 5.000,  6.250) = 1046 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 101 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     15.204 ms/op
     p(99.9990) =     17.000 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 5.166 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.012 ms/op
Iteration   1: 4.113 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 4.153 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  14.191 ms/op
                 listUser·p0.9999: 17.148 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 4.238 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.293 ms/op
                 listUser·p0.999:  18.393 ms/op
                 listUser·p0.9999: 26.097 ms/op
                 listUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230403
  mean =      4.167 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1683 
    [ 2.500,  5.000) = 199748 
    [ 5.000,  7.500) = 27211 
    [ 7.500, 10.000) = 1320 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.345 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     28.088 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.241 ± 1.479  ops/ms
ClientGrpc.existUser                       thrpt       3  10.855 ± 1.665  ops/ms
ClientGrpc.getUser                         thrpt       3  10.280 ± 2.555  ops/ms
ClientGrpc.listUser                        thrpt       3   7.699 ± 3.471  ops/ms
ClientGrpc.createUser                       avgt       3   3.090 ± 0.568   ms/op
ClientGrpc.existUser                        avgt       3   2.956 ± 1.407   ms/op
ClientGrpc.getUser                          avgt       3   3.074 ± 0.698   ms/op
ClientGrpc.listUser                         avgt       3   4.120 ± 0.711   ms/op
ClientGrpc.createUser                     sample  309020   3.105 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.702           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.796           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.142           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.905           ms/op
ClientGrpc.existUser                      sample  327054   2.935 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.596           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.643           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.049           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.481           ms/op
ClientGrpc.getUser                        sample  310056   3.094 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.945           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.299           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.204           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.924           ms/op
ClientGrpc.listUser                       sample  230403   4.167 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.943           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.994           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.345           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.348           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.246           ms/op
