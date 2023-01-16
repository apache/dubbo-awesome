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
# Warmup Iteration   1: 5.339 ops/ms
# Warmup Iteration   2: 9.412 ops/ms
# Warmup Iteration   3: 10.019 ops/ms
Iteration   1: 10.318 ops/ms
Iteration   2: 10.518 ops/ms
Iteration   3: 10.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.402 ±(99.9%) 1.901 ops/ms [Average]
  (min, avg, max) = (10.318, 10.402, 10.518), stdev = 0.104
  CI (99.9%): [8.501, 12.303] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.880 ops/ms
# Warmup Iteration   2: 10.568 ops/ms
# Warmup Iteration   3: 10.915 ops/ms
Iteration   1: 10.457 ops/ms
Iteration   2: 10.829 ops/ms
Iteration   3: 10.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.683 ±(99.9%) 3.614 ops/ms [Average]
  (min, avg, max) = (10.457, 10.683, 10.829), stdev = 0.198
  CI (99.9%): [7.069, 14.297] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.511 ops/ms
# Warmup Iteration   2: 10.394 ops/ms
# Warmup Iteration   3: 10.299 ops/ms
Iteration   1: 10.386 ops/ms
Iteration   2: 10.787 ops/ms
Iteration   3: 10.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.603 ±(99.9%) 3.699 ops/ms [Average]
  (min, avg, max) = (10.386, 10.603, 10.787), stdev = 0.203
  CI (99.9%): [6.905, 14.302] (assumes normal distribution)


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
# Warmup Iteration   1: 6.957 ops/ms
# Warmup Iteration   2: 7.719 ops/ms
# Warmup Iteration   3: 7.987 ops/ms
Iteration   1: 8.041 ops/ms
Iteration   2: 8.326 ops/ms
Iteration   3: 8.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.150 ±(99.9%) 2.819 ops/ms [Average]
  (min, avg, max) = (8.041, 8.150, 8.326), stdev = 0.155
  CI (99.9%): [5.331, 10.968] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.298 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.004 ms/op
Iteration   1: 3.036 ±(99.9%) 0.003 ms/op
Iteration   2: 3.085 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.036 ±(99.9%) 0.891 ms/op [Average]
  (min, avg, max) = (2.987, 3.036, 3.085), stdev = 0.049
  CI (99.9%): [2.145, 3.927] (assumes normal distribution)


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
# Warmup Iteration   1: 3.623 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.953 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.003 ms/op
Iteration   1: 2.996 ±(99.9%) 0.003 ms/op
Iteration   2: 2.936 ±(99.9%) 0.002 ms/op
Iteration   3: 2.946 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.959 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (2.936, 2.959, 2.996), stdev = 0.032
  CI (99.9%): [2.379, 3.540] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.003 ms/op
Iteration   1: 3.047 ±(99.9%) 0.003 ms/op
Iteration   2: 3.006 ±(99.9%) 0.002 ms/op
Iteration   3: 3.045 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.033 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (3.006, 3.033, 3.047), stdev = 0.024
  CI (99.9%): [2.604, 3.461] (assumes normal distribution)


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
# Warmup Iteration   1: 5.182 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.012 ms/op
Iteration   1: 3.949 ±(99.9%) 0.008 ms/op
Iteration   2: 3.958 ±(99.9%) 0.023 ms/op
Iteration   3: 3.924 ±(99.9%) 0.049 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.944 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (3.924, 3.944, 3.958), stdev = 0.017
  CI (99.9%): [3.626, 4.261] (assumes normal distribution)


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
Iteration   1: 3.128 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.870 ms/op
                 createUser·p0.9999: 26.797 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.867 ms/op
                 createUser·p0.9999: 16.025 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   3: 3.193 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.594 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  10.152 ms/op
                 createUser·p0.9999: 17.857 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305633
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18877 
    [ 2.500,  5.000) = 285594 
    [ 5.000,  7.500) = 799 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     25.686 ms/op
     p(99.9990) =     27.257 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.857 ms/op
                 existUser·p0.9999: 12.699 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  5.554 ms/op
                 existUser·p0.9999: 13.032 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.580 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  6.552 ms/op
                 existUser·p0.9999: 14.572 ms/op
                 existUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322591
  mean =      2.975 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2028 
    [ 1.250,  2.500) = 42643 
    [ 2.500,  3.750) = 256206 
    [ 3.750,  5.000) = 20835 
    [ 5.000,  6.250) = 416 
    [ 6.250,  7.500) = 186 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.143 ms/op
     p(99.9900) =     13.653 ms/op
     p(99.9990) =     16.216 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 3.136 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  10.074 ms/op
                 getUser·p0.9999: 11.921 ms/op
                 getUser·p1.00:   12.583 ms/op

Iteration   2: 3.133 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.379 ms/op
                 getUser·p0.9999: 13.975 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   3: 2.960 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.460 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 16.452 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312206
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2457 
    [ 1.250,  2.500) = 26295 
    [ 2.500,  3.750) = 256773 
    [ 3.750,  5.000) = 25451 
    [ 5.000,  6.250) = 713 
    [ 6.250,  7.500) = 166 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     15.516 ms/op
     p(99.9990) =     17.262 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 5.067 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.012 ms/op
Iteration   1: 4.069 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.679 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  18.672 ms/op
                 listUser·p0.9999: 25.180 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   2: 3.912 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.289 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.684 ms/op
                 listUser·p0.9999: 15.477 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.742 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  16.315 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241598
  mean =      3.973 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5604 
    [ 2.500,  5.000) = 205700 
    [ 5.000,  7.500) = 29321 
    [ 7.500, 10.000) = 586 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.289 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     23.555 ms/op
     p(99.9990) =     25.597 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.402 ± 1.901  ops/ms
ClientGrpc.existUser                       thrpt       3  10.683 ± 3.614  ops/ms
ClientGrpc.getUser                         thrpt       3  10.603 ± 3.699  ops/ms
ClientGrpc.listUser                        thrpt       3   8.150 ± 2.819  ops/ms
ClientGrpc.createUser                       avgt       3   3.036 ± 0.891   ms/op
ClientGrpc.existUser                        avgt       3   2.959 ± 0.581   ms/op
ClientGrpc.getUser                          avgt       3   3.033 ± 0.429   ms/op
ClientGrpc.listUser                         avgt       3   3.944 ± 0.317   ms/op
ClientGrpc.createUser                     sample  305633   3.141 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.593           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.998           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.748           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.686           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.361           ms/op
ClientGrpc.existUser                      sample  322591   2.975 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.580           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.143           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.653           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.318           ms/op
ClientGrpc.getUser                        sample  312206   3.074 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.460           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.733           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.516           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.400           ms/op
ClientGrpc.listUser                       sample  241598   3.973 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.289           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.555           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
