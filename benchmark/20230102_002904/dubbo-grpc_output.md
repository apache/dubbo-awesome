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
# Warmup Iteration   1: 4.721 ops/ms
# Warmup Iteration   2: 9.177 ops/ms
# Warmup Iteration   3: 10.241 ops/ms
Iteration   1: 10.609 ops/ms
Iteration   2: 10.206 ops/ms
Iteration   3: 10.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.325 ±(99.9%) 4.503 ops/ms [Average]
  (min, avg, max) = (10.161, 10.325, 10.609), stdev = 0.247
  CI (99.9%): [5.823, 14.828] (assumes normal distribution)


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
# Warmup Iteration   1: 8.304 ops/ms
# Warmup Iteration   2: 10.557 ops/ms
# Warmup Iteration   3: 10.856 ops/ms
Iteration   1: 11.087 ops/ms
Iteration   2: 11.038 ops/ms
Iteration   3: 10.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.971 ±(99.9%) 2.937 ops/ms [Average]
  (min, avg, max) = (10.787, 10.971, 11.087), stdev = 0.161
  CI (99.9%): [8.034, 13.907] (assumes normal distribution)


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
# Warmup Iteration   1: 7.775 ops/ms
# Warmup Iteration   2: 10.323 ops/ms
# Warmup Iteration   3: 10.444 ops/ms
Iteration   1: 10.516 ops/ms
Iteration   2: 10.139 ops/ms
Iteration   3: 10.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.265 ±(99.9%) 3.966 ops/ms [Average]
  (min, avg, max) = (10.139, 10.265, 10.516), stdev = 0.217
  CI (99.9%): [6.300, 14.231] (assumes normal distribution)


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
# Warmup Iteration   1: 6.291 ops/ms
# Warmup Iteration   2: 7.879 ops/ms
# Warmup Iteration   3: 7.998 ops/ms
Iteration   1: 8.068 ops/ms
Iteration   2: 7.957 ops/ms
Iteration   3: 7.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.005 ±(99.9%) 1.043 ops/ms [Average]
  (min, avg, max) = (7.957, 8.005, 8.068), stdev = 0.057
  CI (99.9%): [6.962, 9.048] (assumes normal distribution)


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.002 ms/op
Iteration   1: 3.074 ±(99.9%) 0.003 ms/op
Iteration   2: 3.006 ±(99.9%) 0.002 ms/op
Iteration   3: 3.073 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.051 ±(99.9%) 0.718 ms/op [Average]
  (min, avg, max) = (3.006, 3.051, 3.074), stdev = 0.039
  CI (99.9%): [2.333, 3.769] (assumes normal distribution)


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 2.870 ±(99.9%) 0.003 ms/op
Iteration   2: 2.971 ±(99.9%) 0.002 ms/op
Iteration   3: 2.877 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.906 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (2.870, 2.906, 2.971), stdev = 0.057
  CI (99.9%): [1.874, 3.937] (assumes normal distribution)


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
# Warmup Iteration   1: 3.525 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.060 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 3.060 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.056 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (3.047, 3.056, 3.060), stdev = 0.007
  CI (99.9%): [2.919, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.902 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.023 ms/op
Iteration   1: 3.823 ±(99.9%) 0.020 ms/op
Iteration   2: 3.871 ±(99.9%) 0.016 ms/op
Iteration   3: 3.973 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.889 ±(99.9%) 1.405 ms/op [Average]
  (min, avg, max) = (3.823, 3.889, 3.973), stdev = 0.077
  CI (99.9%): [2.484, 5.293] (assumes normal distribution)


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
# Warmup Iteration   1: 3.590 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.007 ms/op
Iteration   1: 3.057 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  5.867 ms/op
                 createUser·p0.9999: 11.650 ms/op
                 createUser·p1.00:   11.911 ms/op

Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.529 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.758 ms/op
                 createUser·p0.9999: 14.819 ms/op
                 createUser·p1.00:   15.909 ms/op

Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.116 ms/op
                 createUser·p0.999:  12.190 ms/op
                 createUser·p0.9999: 25.378 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314790
  mean =      3.048 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26441 
    [ 2.500,  5.000) = 287320 
    [ 5.000,  7.500) = 684 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.760 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.620 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.006 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  5.949 ms/op
                 existUser·p0.9999: 11.633 ms/op
                 existUser·p1.00:   12.026 ms/op

Iteration   2: 2.938 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.472 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  10.146 ms/op
                 existUser·p0.9999: 12.607 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  5.785 ms/op
                 existUser·p0.9999: 14.987 ms/op
                 existUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322925
  mean =      2.971 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3424 
    [ 1.250,  2.500) = 43630 
    [ 2.500,  3.750) = 253541 
    [ 3.750,  5.000) = 21449 
    [ 5.000,  6.250) = 442 
    [ 6.250,  7.500) = 155 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.947 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     15.206 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.007 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.707 ms/op
                 getUser·p0.9999: 15.233 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   2: 3.089 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  5.816 ms/op
                 getUser·p0.9999: 25.526 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.595 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  5.714 ms/op
                 getUser·p0.9999: 22.938 ms/op
                 getUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316287
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28399 
    [ 2.500,  5.000) = 287113 
    [ 5.000,  7.500) = 539 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.390 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     25.816 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 5.533 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.012 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.801 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  11.773 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   2: 3.984 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  13.840 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 3.943 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 23.314 ms/op
                 listUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241994
  mean =      3.970 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3014 
    [ 2.500,  5.000) = 215766 
    [ 5.000,  7.500) = 22141 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     21.679 ms/op
     p(99.9990) =     23.776 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.325 ± 4.503  ops/ms
ClientGrpc.existUser                       thrpt       3  10.971 ± 2.937  ops/ms
ClientGrpc.getUser                         thrpt       3  10.265 ± 3.966  ops/ms
ClientGrpc.listUser                        thrpt       3   8.005 ± 1.043  ops/ms
ClientGrpc.createUser                       avgt       3   3.051 ± 0.718   ms/op
ClientGrpc.existUser                        avgt       3   2.906 ± 1.031   ms/op
ClientGrpc.getUser                          avgt       3   3.056 ± 0.136   ms/op
ClientGrpc.listUser                         avgt       3   3.889 ± 1.405   ms/op
ClientGrpc.createUser                     sample  314790   3.048 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.529           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.760           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.150           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.525           ms/op
ClientGrpc.existUser                      sample  322925   2.971 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.472           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.947           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.812           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.368           ms/op
ClientGrpc.getUser                        sample  316287   3.033 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.595           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.390           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.576           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.887           ms/op
ClientGrpc.listUser                       sample  241994   3.970 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.801           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.156           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.679           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.790           ms/op
