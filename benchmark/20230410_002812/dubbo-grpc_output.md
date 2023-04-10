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
# Warmup Iteration   1: 3.358 ops/ms
# Warmup Iteration   2: 7.493 ops/ms
# Warmup Iteration   3: 8.542 ops/ms
Iteration   1: 8.932 ops/ms
Iteration   2: 9.212 ops/ms
Iteration   3: 9.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.098 ±(99.9%) 2.690 ops/ms [Average]
  (min, avg, max) = (8.932, 9.098, 9.212), stdev = 0.147
  CI (99.9%): [6.408, 11.788] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.384 ops/ms
# Warmup Iteration   2: 8.964 ops/ms
# Warmup Iteration   3: 9.481 ops/ms
Iteration   1: 9.484 ops/ms
Iteration   2: 9.851 ops/ms
Iteration   3: 9.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.634 ±(99.9%) 3.513 ops/ms [Average]
  (min, avg, max) = (9.484, 9.634, 9.851), stdev = 0.193
  CI (99.9%): [6.121, 13.146] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.760 ops/ms
# Warmup Iteration   2: 8.817 ops/ms
# Warmup Iteration   3: 9.191 ops/ms
Iteration   1: 9.339 ops/ms
Iteration   2: 9.452 ops/ms
Iteration   3: 9.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.353 ±(99.9%) 1.698 ops/ms [Average]
  (min, avg, max) = (9.268, 9.353, 9.452), stdev = 0.093
  CI (99.9%): [7.655, 11.052] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.557 ops/ms
# Warmup Iteration   2: 6.867 ops/ms
# Warmup Iteration   3: 7.142 ops/ms
Iteration   1: 7.123 ops/ms
Iteration   2: 7.197 ops/ms
Iteration   3: 7.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.228 ±(99.9%) 2.256 ops/ms [Average]
  (min, avg, max) = (7.123, 7.228, 7.364), stdev = 0.124
  CI (99.9%): [4.972, 9.484] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.615 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.003 ms/op
Iteration   1: 3.419 ±(99.9%) 0.004 ms/op
Iteration   2: 3.399 ±(99.9%) 0.004 ms/op
Iteration   3: 3.346 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.388 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (3.346, 3.388, 3.419), stdev = 0.038
  CI (99.9%): [2.702, 4.074] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.624 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.002 ms/op
Iteration   1: 3.322 ±(99.9%) 0.002 ms/op
Iteration   2: 3.404 ±(99.9%) 0.003 ms/op
Iteration   3: 3.299 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.342 ±(99.9%) 1.005 ms/op [Average]
  (min, avg, max) = (3.299, 3.342, 3.404), stdev = 0.055
  CI (99.9%): [2.336, 4.347] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.040 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.004 ms/op
Iteration   1: 3.367 ±(99.9%) 0.006 ms/op
Iteration   2: 3.429 ±(99.9%) 0.004 ms/op
Iteration   3: 3.488 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.428 ±(99.9%) 1.103 ms/op [Average]
  (min, avg, max) = (3.367, 3.428, 3.488), stdev = 0.060
  CI (99.9%): [2.325, 4.531] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.524 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.591 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.439 ±(99.9%) 0.014 ms/op
Iteration   1: 4.406 ±(99.9%) 0.017 ms/op
Iteration   2: 4.462 ±(99.9%) 0.014 ms/op
Iteration   3: 4.295 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.388 ±(99.9%) 1.549 ms/op [Average]
  (min, avg, max) = (4.295, 4.388, 4.462), stdev = 0.085
  CI (99.9%): [2.839, 5.937] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.898 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.006 ms/op
Iteration   1: 3.410 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  8.282 ms/op
                 createUser·p0.9999: 13.691 ms/op
                 createUser·p1.00:   13.828 ms/op

Iteration   2: 3.377 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   4.904 ms/op
                 createUser·p0.999:  7.318 ms/op
                 createUser·p0.9999: 25.218 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.451 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.338 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  16.607 ms/op
                 createUser·p0.9999: 19.390 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 281346
  mean =      3.412 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6661 
    [ 2.500,  5.000) = 271702 
    [ 5.000,  7.500) = 2550 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.338 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.054 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     24.469 ms/op
     p(99.9990) =     25.538 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.761 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.007 ms/op
Iteration   1: 3.268 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.861 ms/op
                 existUser·p0.999:  6.874 ms/op
                 existUser·p0.9999: 14.752 ms/op
                 existUser·p1.00:   15.598 ms/op

Iteration   2: 3.296 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  11.449 ms/op
                 existUser·p0.9999: 15.394 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  8.401 ms/op
                 existUser·p0.9999: 15.991 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 295310
  mean =      3.253 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1396 
    [ 1.250,  2.500) = 13950 
    [ 2.500,  3.750) = 246838 
    [ 3.750,  5.000) = 30591 
    [ 5.000,  6.250) = 2000 
    [ 6.250,  7.500) = 209 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      7.821 ms/op
     p(99.9900) =     15.540 ms/op
     p(99.9990) =     17.635 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.012 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.010 ms/op
Iteration   1: 3.404 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  10.406 ms/op
                 getUser·p0.9999: 13.530 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 3.442 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  9.731 ms/op
                 getUser·p0.9999: 20.939 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   3: 3.393 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.233 ms/op
                 getUser·p0.999:  7.125 ms/op
                 getUser·p0.9999: 17.947 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 281291
  mean =      3.413 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9143 
    [ 2.500,  5.000) = 269049 
    [ 5.000,  7.500) = 2740 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.087 ms/op
     p(99.9000) =      8.582 ms/op
     p(99.9900) =     19.263 ms/op
     p(99.9990) =     21.043 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 6.448 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.669 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.438 ±(99.9%) 0.013 ms/op
Iteration   1: 4.420 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.587 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  15.673 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 4.465 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  15.315 ms/op
                 listUser·p0.9999: 19.191 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 4.478 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.477 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  20.120 ms/op
                 listUser·p0.9999: 30.530 ms/op
                 listUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 215520
  mean =      4.454 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 640 
    [ 2.500,  5.000) = 186301 
    [ 5.000,  7.500) = 25756 
    [ 7.500, 10.000) = 2240 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     30.940 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.098 ± 2.690  ops/ms
ClientGrpc.existUser                       thrpt       3   9.634 ± 3.513  ops/ms
ClientGrpc.getUser                         thrpt       3   9.353 ± 1.698  ops/ms
ClientGrpc.listUser                        thrpt       3   7.228 ± 2.256  ops/ms
ClientGrpc.createUser                       avgt       3   3.388 ± 0.686   ms/op
ClientGrpc.existUser                        avgt       3   3.342 ± 1.005   ms/op
ClientGrpc.getUser                          avgt       3   3.428 ± 1.103   ms/op
ClientGrpc.listUser                         avgt       3   4.388 ± 1.549   ms/op
ClientGrpc.createUser                     sample  281346   3.412 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.338           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.375           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.054           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.486           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.469           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.723           ms/op
ClientGrpc.existUser                      sample  295310   3.253 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.633           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.248           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.014           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.866           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.821           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.540           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.793           ms/op
ClientGrpc.getUser                        sample  281291   3.413 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.682           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.391           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.087           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.582           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.263           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.135           ms/op
ClientGrpc.listUser                       sample  215520   4.454 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.984           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.301           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.218           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.766           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.269           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.871           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.966           ms/op
