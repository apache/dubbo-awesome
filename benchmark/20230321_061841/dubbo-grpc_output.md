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
# Warmup Iteration   1: 4.391 ops/ms
# Warmup Iteration   2: 9.050 ops/ms
# Warmup Iteration   3: 10.194 ops/ms
Iteration   1: 10.443 ops/ms
Iteration   2: 10.645 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.539 ±(99.9%) 1.853 ops/ms [Average]
  (min, avg, max) = (10.443, 10.539, 10.645), stdev = 0.102
  CI (99.9%): [8.687, 12.392] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.936 ops/ms
# Warmup Iteration   2: 10.752 ops/ms
# Warmup Iteration   3: 11.098 ops/ms
Iteration   1: 11.374 ops/ms
Iteration   2: 11.352 ops/ms
Iteration   3: 11.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.327 ±(99.9%) 1.171 ops/ms [Average]
  (min, avg, max) = (11.253, 11.327, 11.374), stdev = 0.064
  CI (99.9%): [10.156, 12.497] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.085 ops/ms
# Warmup Iteration   2: 10.175 ops/ms
# Warmup Iteration   3: 10.598 ops/ms
Iteration   1: 10.486 ops/ms
Iteration   2: 10.630 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.604 ±(99.9%) 1.966 ops/ms [Average]
  (min, avg, max) = (10.486, 10.604, 10.697), stdev = 0.108
  CI (99.9%): [8.639, 12.570] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.562 ops/ms
# Warmup Iteration   2: 7.783 ops/ms
# Warmup Iteration   3: 8.173 ops/ms
Iteration   1: 8.195 ops/ms
Iteration   2: 8.272 ops/ms
Iteration   3: 8.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.224 ±(99.9%) 0.766 ops/ms [Average]
  (min, avg, max) = (8.195, 8.224, 8.272), stdev = 0.042
  CI (99.9%): [7.458, 8.989] (assumes normal distribution)


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 3.024 ±(99.9%) 0.004 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.029 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (3.024, 3.029, 3.036), stdev = 0.006
  CI (99.9%): [2.917, 3.142] (assumes normal distribution)


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
# Warmup Iteration   1: 3.570 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.853 ±(99.9%) 0.004 ms/op
Iteration   1: 2.923 ±(99.9%) 0.002 ms/op
Iteration   2: 2.900 ±(99.9%) 0.004 ms/op
Iteration   3: 2.913 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.912 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.900, 2.912, 2.923), stdev = 0.011
  CI (99.9%): [2.703, 3.122] (assumes normal distribution)


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.002 ms/op
Iteration   1: 3.022 ±(99.9%) 0.003 ms/op
Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
Iteration   3: 3.036 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.023 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (3.011, 3.023, 3.036), stdev = 0.012
  CI (99.9%): [2.795, 3.251] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.677 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.027 ms/op
Iteration   1: 3.835 ±(99.9%) 0.007 ms/op
Iteration   2: 3.898 ±(99.9%) 0.036 ms/op
Iteration   3: 3.895 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.876 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (3.835, 3.876, 3.898), stdev = 0.036
  CI (99.9%): [3.226, 4.525] (assumes normal distribution)


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.007 ms/op
Iteration   1: 3.010 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.535 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  8.707 ms/op
                 createUser·p0.9999: 18.940 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.414 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   4.047 ms/op
                 createUser·p0.999:  9.083 ms/op
                 createUser·p0.9999: 15.849 ms/op
                 createUser·p1.00:   15.942 ms/op

Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  10.119 ms/op
                 createUser·p0.9999: 16.105 ms/op
                 createUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318182
  mean =      3.018 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25663 
    [ 2.500,  5.000) = 291005 
    [ 5.000,  7.500) = 1058 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      9.576 ms/op
     p(99.9900) =     18.368 ms/op
     p(99.9990) =     19.452 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 3.435 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.838 ±(99.9%) 0.006 ms/op
Iteration   1: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  7.568 ms/op
                 existUser·p0.9999: 12.094 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   2: 2.877 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.442 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  5.773 ms/op
                 existUser·p0.9999: 21.029 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   3: 2.899 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  7.946 ms/op
                 existUser·p0.9999: 26.080 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330750
  mean =      2.902 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38993 
    [ 2.500,  5.000) = 290803 
    [ 5.000,  7.500) = 617 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.563 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  6.070 ms/op
                 getUser·p0.9999: 12.006 ms/op
                 getUser·p1.00:   12.272 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.264 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.048 ms/op
                 getUser·p0.9999: 13.014 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   3: 2.982 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.565 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.847 ms/op
                 getUser·p0.9999: 27.239 ms/op
                 getUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319838
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35111 
    [ 2.500,  5.000) = 283302 
    [ 5.000,  7.500) = 1177 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.264 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      6.955 ms/op
     p(99.9900) =     26.740 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.010 ms/op
Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.471 ms/op
                 listUser·p0.9999: 23.031 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   2: 3.895 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 22.177 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   3: 3.938 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.680 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 17.395 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245026
  mean =      3.918 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4964 
    [ 2.500,  5.000) = 221550 
    [ 5.000,  7.500) = 17328 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     22.692 ms/op
     p(99.9990) =     25.693 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.539 ± 1.853  ops/ms
ClientGrpc.existUser                       thrpt       3  11.327 ± 1.171  ops/ms
ClientGrpc.getUser                         thrpt       3  10.604 ± 1.966  ops/ms
ClientGrpc.listUser                        thrpt       3   8.224 ± 0.766  ops/ms
ClientGrpc.createUser                       avgt       3   3.029 ± 0.113   ms/op
ClientGrpc.existUser                        avgt       3   2.912 ± 0.210   ms/op
ClientGrpc.getUser                          avgt       3   3.023 ± 0.228   ms/op
ClientGrpc.listUser                         avgt       3   3.876 ± 0.650   ms/op
ClientGrpc.createUser                     sample  318182   3.018 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.414           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.576           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.368           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.968           ms/op
ClientGrpc.existUser                      sample  330750   2.902 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.442           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.563           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.529           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.673           ms/op
ClientGrpc.getUser                        sample  319838   3.001 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.264           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.955           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.740           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.081           ms/op
ClientGrpc.listUser                       sample  245026   3.918 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.014           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.694           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.516           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.692           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.756           ms/op
