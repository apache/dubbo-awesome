# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.128 ops/ms
# Warmup Iteration   2: 8.520 ops/ms
# Warmup Iteration   3: 10.104 ops/ms
Iteration   1: 10.440 ops/ms
Iteration   2: 10.450 ops/ms
Iteration   3: 10.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.480 ±(99.9%) 1.119 ops/ms [Average]
  (min, avg, max) = (10.440, 10.480, 10.551), stdev = 0.061
  CI (99.9%): [9.361, 11.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.368 ops/ms
# Warmup Iteration   2: 10.644 ops/ms
# Warmup Iteration   3: 10.876 ops/ms
Iteration   1: 11.305 ops/ms
Iteration   2: 10.923 ops/ms
Iteration   3: 10.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.006 ±(99.9%) 4.863 ops/ms [Average]
  (min, avg, max) = (10.791, 11.006, 11.305), stdev = 0.267
  CI (99.9%): [6.143, 15.870] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.605 ops/ms
# Warmup Iteration   2: 10.131 ops/ms
# Warmup Iteration   3: 10.406 ops/ms
Iteration   1: 10.544 ops/ms
Iteration   2: 10.508 ops/ms
Iteration   3: 10.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.484 ±(99.9%) 1.368 ops/ms [Average]
  (min, avg, max) = (10.400, 10.484, 10.544), stdev = 0.075
  CI (99.9%): [9.116, 11.852] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.107 ops/ms
# Warmup Iteration   2: 7.746 ops/ms
# Warmup Iteration   3: 8.122 ops/ms
Iteration   1: 8.039 ops/ms
Iteration   2: 8.060 ops/ms
Iteration   3: 7.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.986 ±(99.9%) 2.002 ops/ms [Average]
  (min, avg, max) = (7.860, 7.986, 8.060), stdev = 0.110
  CI (99.9%): [5.984, 9.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.004 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
Iteration   2: 3.102 ±(99.9%) 0.001 ms/op
Iteration   3: 3.068 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.076 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (3.057, 3.076, 3.102), stdev = 0.023
  CI (99.9%): [2.648, 3.504] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.002 ms/op
Iteration   1: 2.931 ±(99.9%) 0.002 ms/op
Iteration   2: 2.969 ±(99.9%) 0.002 ms/op
Iteration   3: 2.924 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.941 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (2.924, 2.941, 2.969), stdev = 0.025
  CI (99.9%): [2.494, 3.389] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.321 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.003 ms/op
Iteration   2: 3.126 ±(99.9%) 0.003 ms/op
Iteration   3: 3.034 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.084 ±(99.9%) 0.850 ms/op [Average]
  (min, avg, max) = (3.034, 3.084, 3.126), stdev = 0.047
  CI (99.9%): [2.235, 3.934] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.854 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.012 ms/op
Iteration   1: 3.979 ±(99.9%) 0.019 ms/op
Iteration   2: 3.880 ±(99.9%) 0.005 ms/op
Iteration   3: 3.964 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.941 ±(99.9%) 0.970 ms/op [Average]
  (min, avg, max) = (3.880, 3.941, 3.979), stdev = 0.053
  CI (99.9%): [2.970, 4.911] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.238 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 3.087 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  8.068 ms/op
                 createUser·p0.9999: 12.501 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.953 ms/op
                 createUser·p0.9999: 14.100 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  8.040 ms/op
                 createUser·p0.9999: 16.466 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311869
  mean =      3.077 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 594 
    [ 1.250,  2.500) = 17926 
    [ 2.500,  3.750) = 273340 
    [ 3.750,  5.000) = 18631 
    [ 5.000,  6.250) = 789 
    [ 6.250,  7.500) = 220 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.922 ms/op
     p(99.9900) =     16.021 ms/op
     p(99.9990) =     16.704 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.005 ms/op
Iteration   1: 2.902 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.043 ms/op
                 existUser·p0.9999: 18.382 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   2: 2.909 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  6.086 ms/op
                 existUser·p0.9999: 13.468 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  9.748 ms/op
                 existUser·p0.9999: 24.685 ms/op
                 existUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327058
  mean =      2.936 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27095 
    [ 2.500,  5.000) = 298933 
    [ 5.000,  7.500) = 789 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      6.553 ms/op
     p(99.9900) =     24.202 ms/op
     p(99.9990) =     24.928 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.005 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.006 ms/op
Iteration   1: 3.154 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.753 ms/op
                 getUser·p0.9999: 14.200 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 3.111 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.597 ms/op
                 getUser·p0.9999: 14.909 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.423 ms/op
                 getUser·p0.999:  7.376 ms/op
                 getUser·p0.9999: 16.270 ms/op
                 getUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307422
  mean =      3.120 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 329 
    [ 1.250,  2.500) = 11433 
    [ 2.500,  3.750) = 274279 
    [ 3.750,  5.000) = 20028 
    [ 5.000,  6.250) = 820 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.062 ms/op
     p(99.9900) =     15.594 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.153 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.011 ms/op
Iteration   1: 4.068 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.437 ms/op
                 listUser·p0.999:  15.848 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   2: 3.974 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 23.821 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 3.994 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.799 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.345 ms/op
                 listUser·p0.9999: 17.563 ms/op
                 listUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239357
  mean =      4.012 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2775 
    [ 2.500,  5.000) = 214217 
    [ 5.000,  7.500) = 20913 
    [ 7.500, 10.000) = 943 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     16.798 ms/op
     p(99.9900) =     23.075 ms/op
     p(99.9990) =     24.672 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.480 ± 1.119  ops/ms
ClientGrpc.existUser                       thrpt       3  11.006 ± 4.863  ops/ms
ClientGrpc.getUser                         thrpt       3  10.484 ± 1.368  ops/ms
ClientGrpc.listUser                        thrpt       3   7.986 ± 2.002  ops/ms
ClientGrpc.createUser                       avgt       3   3.076 ± 0.428   ms/op
ClientGrpc.existUser                        avgt       3   2.941 ± 0.448   ms/op
ClientGrpc.getUser                          avgt       3   3.084 ± 0.850   ms/op
ClientGrpc.listUser                         avgt       3   3.941 ± 0.970   ms/op
ClientGrpc.createUser                     sample  311869   3.077 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.582           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.922           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.021           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.777           ms/op
ClientGrpc.existUser                      sample  327058   2.936 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.712           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.553           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.202           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.068           ms/op
ClientGrpc.getUser                        sample  307422   3.120 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.781           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.062           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.594           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.105           ms/op
ClientGrpc.listUser                       sample  239357   4.012 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.799           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.798           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.075           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.166           ms/op
