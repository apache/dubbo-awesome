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
# Warmup Iteration   1: 2.293 ops/ms
# Warmup Iteration   2: 5.476 ops/ms
# Warmup Iteration   3: 6.924 ops/ms
Iteration   1: 7.230 ops/ms
Iteration   2: 7.360 ops/ms
Iteration   3: 8.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.531 ±(99.9%) 7.528 ops/ms [Average]
  (min, avg, max) = (7.230, 7.531, 8.001), stdev = 0.413
  CI (99.9%): [0.003, 15.058] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.194 ops/ms
# Warmup Iteration   2: 7.542 ops/ms
# Warmup Iteration   3: 7.956 ops/ms
Iteration   1: 8.693 ops/ms
Iteration   2: 8.109 ops/ms
Iteration   3: 8.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.412 ±(99.9%) 5.341 ops/ms [Average]
  (min, avg, max) = (8.109, 8.412, 8.693), stdev = 0.293
  CI (99.9%): [3.071, 13.752] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.714 ops/ms
# Warmup Iteration   2: 7.131 ops/ms
# Warmup Iteration   3: 7.511 ops/ms
Iteration   1: 7.297 ops/ms
Iteration   2: 7.857 ops/ms
Iteration   3: 7.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.617 ±(99.9%) 5.267 ops/ms [Average]
  (min, avg, max) = (7.297, 7.617, 7.857), stdev = 0.289
  CI (99.9%): [2.350, 12.884] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ops/ms
# Warmup Iteration   2: 5.631 ops/ms
# Warmup Iteration   3: 5.992 ops/ms
Iteration   1: 6.005 ops/ms
Iteration   2: 6.029 ops/ms
Iteration   3: 5.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.975 ±(99.9%) 1.348 ops/ms [Average]
  (min, avg, max) = (5.891, 5.975, 6.029), stdev = 0.074
  CI (99.9%): [4.627, 7.323] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.499 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.619 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.005 ms/op
Iteration   1: 4.100 ±(99.9%) 0.005 ms/op
Iteration   2: 4.291 ±(99.9%) 0.002 ms/op
Iteration   3: 3.890 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.093 ±(99.9%) 3.660 ms/op [Average]
  (min, avg, max) = (3.890, 4.093, 4.291), stdev = 0.201
  CI (99.9%): [0.433, 7.754] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.737 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.003 ms/op
Iteration   1: 3.926 ±(99.9%) 0.004 ms/op
Iteration   2: 3.866 ±(99.9%) 0.004 ms/op
Iteration   3: 3.936 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.909 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (3.866, 3.909, 3.936), stdev = 0.038
  CI (99.9%): [3.222, 4.597] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.426 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.005 ms/op
Iteration   1: 4.099 ±(99.9%) 0.004 ms/op
Iteration   2: 4.178 ±(99.9%) 0.004 ms/op
Iteration   3: 4.123 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.134 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (4.099, 4.134, 4.178), stdev = 0.041
  CI (99.9%): [3.393, 4.874] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.626 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.658 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.499 ±(99.9%) 0.018 ms/op
Iteration   1: 5.358 ±(99.9%) 0.036 ms/op
Iteration   2: 5.335 ±(99.9%) 0.021 ms/op
Iteration   3: 5.390 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.361 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (5.335, 5.361, 5.390), stdev = 0.027
  CI (99.9%): [4.860, 5.863] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.218 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.014 ms/op
Iteration   1: 4.219 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.592 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  14.795 ms/op
                 createUser·p0.9999: 17.596 ms/op
                 createUser·p1.00:   18.317 ms/op

Iteration   2: 4.372 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.439 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.218 ms/op
                 createUser·p0.99:   8.880 ms/op
                 createUser·p0.999:  12.365 ms/op
                 createUser·p0.9999: 20.306 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 4.174 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   8.294 ms/op
                 createUser·p0.999:  13.473 ms/op
                 createUser·p0.9999: 24.020 ms/op
                 createUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 225747
  mean =      4.253 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8495 
    [ 2.500,  5.000) = 173972 
    [ 5.000,  7.500) = 39009 
    [ 7.500, 10.000) = 3336 
    [10.000, 12.500) = 639 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     14.000 ms/op
     p(99.9900) =     20.658 ms/op
     p(99.9990) =     25.517 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.476 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.014 ms/op
Iteration   1: 3.928 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.408 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   5.128 ms/op
                 existUser·p0.95:   5.644 ms/op
                 existUser·p0.99:   8.339 ms/op
                 existUser·p0.999:  13.074 ms/op
                 existUser·p0.9999: 16.395 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   2: 3.886 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.472 ms/op
                 existUser·p0.99:   7.631 ms/op
                 existUser·p0.999:  13.592 ms/op
                 existUser·p0.9999: 18.728 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   3: 3.819 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.358 ms/op
                 existUser·p0.99:   7.782 ms/op
                 existUser·p0.999:  11.993 ms/op
                 existUser·p0.9999: 20.873 ms/op
                 existUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 247624
  mean =      3.877 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17279 
    [ 2.500,  5.000) = 205657 
    [ 5.000,  7.500) = 21474 
    [ 7.500, 10.000) = 2437 
    [10.000, 12.500) = 504 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     12.917 ms/op
     p(99.9900) =     20.102 ms/op
     p(99.9990) =     21.039 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.159 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.293 ±(99.9%) 0.014 ms/op
Iteration   1: 4.201 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   8.656 ms/op
                 getUser·p0.999:  11.972 ms/op
                 getUser·p0.9999: 14.434 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   2: 4.174 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   4.067 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.733 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 19.219 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   3: 4.081 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  12.815 ms/op
                 getUser·p0.9999: 20.201 ms/op
                 getUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231283
  mean =      4.151 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8891 
    [ 2.500,  5.000) = 186067 
    [ 5.000,  7.500) = 33037 
    [ 7.500, 10.000) = 2663 
    [10.000, 12.500) = 421 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     12.190 ms/op
     p(99.9900) =     19.919 ms/op
     p(99.9990) =     20.767 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 8.261 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.476 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.404 ±(99.9%) 0.020 ms/op
Iteration   1: 5.337 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.110 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  17.897 ms/op
                 listUser·p0.9999: 22.709 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 5.377 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.726 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.175 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  17.447 ms/op
                 listUser·p0.9999: 21.070 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 5.304 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   4.997 ms/op
                 listUser·p0.90:   7.119 ms/op
                 listUser·p0.95:   8.028 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  23.977 ms/op
                 listUser·p0.9999: 32.011 ms/op
                 listUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179832
  mean =      5.339 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 317 
    [ 2.500,  5.000) = 88589 
    [ 5.000,  7.500) = 76545 
    [ 7.500, 10.000) = 11670 
    [10.000, 12.500) = 1889 
    [12.500, 15.000) = 422 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      7.193 ms/op
     p(95.0000) =      8.102 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     30.903 ms/op
     p(99.9990) =     32.572 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.531 ± 7.528  ops/ms
ClientGrpc.existUser                       thrpt       3   8.412 ± 5.341  ops/ms
ClientGrpc.getUser                         thrpt       3   7.617 ± 5.267  ops/ms
ClientGrpc.listUser                        thrpt       3   5.975 ± 1.348  ops/ms
ClientGrpc.createUser                       avgt       3   4.093 ± 3.660   ms/op
ClientGrpc.existUser                        avgt       3   3.909 ± 0.687   ms/op
ClientGrpc.getUser                          avgt       3   4.134 ± 0.741   ms/op
ClientGrpc.listUser                         avgt       3   5.361 ± 0.502   ms/op
ClientGrpc.createUser                     sample  225747   4.253 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.439           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.464           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.021           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.585           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.000           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.658           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.625           ms/op
ClientGrpc.existUser                      sample  247624   3.877 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.408           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.997           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.020           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.917           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.102           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.201           ms/op
ClientGrpc.getUser                        sample  231283   4.151 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.948           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.022           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.898           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.077           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.190           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.919           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.840           ms/op
ClientGrpc.listUser                       sample  179832   5.339 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.726           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.102           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.748           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.252           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.903           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.702           ms/op
