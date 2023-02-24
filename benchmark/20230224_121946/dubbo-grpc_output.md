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
# Warmup Iteration   1: 4.665 ops/ms
# Warmup Iteration   2: 9.402 ops/ms
# Warmup Iteration   3: 10.511 ops/ms
Iteration   1: 10.518 ops/ms
Iteration   2: 10.328 ops/ms
Iteration   3: 10.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.299 ±(99.9%) 4.283 ops/ms [Average]
  (min, avg, max) = (10.051, 10.299, 10.518), stdev = 0.235
  CI (99.9%): [6.016, 14.582] (assumes normal distribution)


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
# Warmup Iteration   1: 7.771 ops/ms
# Warmup Iteration   2: 10.511 ops/ms
# Warmup Iteration   3: 10.997 ops/ms
Iteration   1: 10.839 ops/ms
Iteration   2: 11.218 ops/ms
Iteration   3: 10.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.826 ±(99.9%) 7.268 ops/ms [Average]
  (min, avg, max) = (10.422, 10.826, 11.218), stdev = 0.398
  CI (99.9%): [3.558, 18.095] (assumes normal distribution)


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
# Warmup Iteration   1: 7.820 ops/ms
# Warmup Iteration   2: 9.866 ops/ms
# Warmup Iteration   3: 10.135 ops/ms
Iteration   1: 10.080 ops/ms
Iteration   2: 10.346 ops/ms
Iteration   3: 10.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.169 ±(99.9%) 2.797 ops/ms [Average]
  (min, avg, max) = (10.080, 10.169, 10.346), stdev = 0.153
  CI (99.9%): [7.372, 12.966] (assumes normal distribution)


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
# Warmup Iteration   1: 5.498 ops/ms
# Warmup Iteration   2: 7.598 ops/ms
# Warmup Iteration   3: 7.682 ops/ms
Iteration   1: 7.654 ops/ms
Iteration   2: 7.945 ops/ms
Iteration   3: 7.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.835 ±(99.9%) 2.886 ops/ms [Average]
  (min, avg, max) = (7.654, 7.835, 7.945), stdev = 0.158
  CI (99.9%): [4.949, 10.721] (assumes normal distribution)


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.003 ms/op
Iteration   1: 3.109 ±(99.9%) 0.003 ms/op
Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
Iteration   3: 3.183 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.138 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.109, 3.138, 3.183), stdev = 0.040
  CI (99.9%): [2.415, 3.861] (assumes normal distribution)


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.937 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.002 ms/op
Iteration   1: 2.982 ±(99.9%) 0.003 ms/op
Iteration   2: 2.978 ±(99.9%) 0.002 ms/op
Iteration   3: 2.966 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.976 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (2.966, 2.976, 2.982), stdev = 0.008
  CI (99.9%): [2.825, 3.126] (assumes normal distribution)


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
# Warmup Iteration   1: 3.997 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.003 ms/op
Iteration   1: 3.166 ±(99.9%) 0.002 ms/op
Iteration   2: 3.169 ±(99.9%) 0.004 ms/op
Iteration   3: 3.094 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.143 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (3.094, 3.143, 3.169), stdev = 0.042
  CI (99.9%): [2.372, 3.914] (assumes normal distribution)


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
# Warmup Iteration   1: 5.163 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
Iteration   1: 4.015 ±(99.9%) 0.006 ms/op
Iteration   2: 4.014 ±(99.9%) 0.017 ms/op
Iteration   3: 4.039 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.023 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (4.014, 4.023, 4.039), stdev = 0.014
  CI (99.9%): [3.763, 4.283] (assumes normal distribution)


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.006 ms/op
Iteration   1: 3.101 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.554 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.212 ms/op
                 createUser·p0.9999: 12.032 ms/op
                 createUser·p1.00:   12.337 ms/op

Iteration   2: 3.146 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.992 ms/op
                 createUser·p0.9999: 14.510 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  6.565 ms/op
                 createUser·p0.9999: 15.752 ms/op
                 createUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307941
  mean =      3.119 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 871 
    [ 1.250,  2.500) = 19781 
    [ 2.500,  3.750) = 258109 
    [ 3.750,  5.000) = 28042 
    [ 5.000,  6.250) = 444 
    [ 6.250,  7.500) = 297 
    [ 7.500,  8.750) = 105 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     15.159 ms/op
     p(99.9990) =     16.037 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


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
# Warmup Iteration   1: 3.624 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.272 ms/op
                 existUser·p0.9999: 17.746 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.188 ms/op
                 existUser·p0.9999: 13.598 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  10.294 ms/op
                 existUser·p0.9999: 17.390 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318359
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1765 
    [ 1.250,  2.500) = 33662 
    [ 2.500,  3.750) = 261268 
    [ 3.750,  5.000) = 20754 
    [ 5.000,  6.250) = 473 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 90 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.591 ms/op
     p(99.9900) =     17.471 ms/op
     p(99.9990) =     17.978 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.007 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.904 ms/op
                 getUser·p0.9999: 15.892 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.318 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.407 ms/op
                 getUser·p0.9999: 15.870 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.633 ms/op
                 getUser·p0.9999: 28.606 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306456
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20365 
    [ 2.500,  5.000) = 285010 
    [ 5.000,  7.500) = 833 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.318 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.025 ms/op
     p(99.9900) =     26.785 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 4.676 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.011 ms/op
Iteration   1: 4.199 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.141 ms/op
                 listUser·p0.999:  11.824 ms/op
                 listUser·p0.9999: 16.134 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   2: 4.006 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.283 ms/op
                 listUser·p0.9999: 23.856 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 4.053 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.691 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.687 ms/op
                 listUser·p0.9999: 25.872 ms/op
                 listUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235094
  mean =      4.085 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3335 
    [ 2.500,  5.000) = 195752 
    [ 5.000,  7.500) = 34463 
    [ 7.500, 10.000) = 1066 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     13.515 ms/op
     p(99.9900) =     24.166 ms/op
     p(99.9990) =     26.322 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.299 ± 4.283  ops/ms
ClientGrpc.existUser                       thrpt       3  10.826 ± 7.268  ops/ms
ClientGrpc.getUser                         thrpt       3  10.169 ± 2.797  ops/ms
ClientGrpc.listUser                        thrpt       3   7.835 ± 2.886  ops/ms
ClientGrpc.createUser                       avgt       3   3.138 ± 0.723   ms/op
ClientGrpc.existUser                        avgt       3   2.976 ± 0.150   ms/op
ClientGrpc.getUser                          avgt       3   3.143 ± 0.771   ms/op
ClientGrpc.listUser                         avgt       3   4.023 ± 0.260   ms/op
ClientGrpc.createUser                     sample  307941   3.119 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.554           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.471           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.159           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.548           ms/op
ClientGrpc.existUser                      sample  318359   3.015 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.517           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.826           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.591           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.471           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.121           ms/op
ClientGrpc.getUser                        sample  306456   3.134 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.318           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.025           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.785           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.655           ms/op
ClientGrpc.listUser                       sample  235094   4.085 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.971           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.515           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.166           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.411           ms/op
