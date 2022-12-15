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
# Warmup Iteration   1: 4.516 ops/ms
# Warmup Iteration   2: 8.819 ops/ms
# Warmup Iteration   3: 10.457 ops/ms
Iteration   1: 10.202 ops/ms
Iteration   2: 10.282 ops/ms
Iteration   3: 10.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.315 ±(99.9%) 2.434 ops/ms [Average]
  (min, avg, max) = (10.202, 10.315, 10.462), stdev = 0.133
  CI (99.9%): [7.881, 12.749] (assumes normal distribution)


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
# Warmup Iteration   1: 7.900 ops/ms
# Warmup Iteration   2: 10.459 ops/ms
# Warmup Iteration   3: 10.586 ops/ms
Iteration   1: 11.260 ops/ms
Iteration   2: 11.089 ops/ms
Iteration   3: 10.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.095 ±(99.9%) 2.946 ops/ms [Average]
  (min, avg, max) = (10.937, 11.095, 11.260), stdev = 0.161
  CI (99.9%): [8.149, 14.041] (assumes normal distribution)


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
# Warmup Iteration   1: 6.913 ops/ms
# Warmup Iteration   2: 10.221 ops/ms
# Warmup Iteration   3: 10.614 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.572 ops/ms
Iteration   3: 10.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.499 ±(99.9%) 2.806 ops/ms [Average]
  (min, avg, max) = (10.322, 10.499, 10.602), stdev = 0.154
  CI (99.9%): [7.693, 13.304] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.870 ops/ms
# Warmup Iteration   2: 7.762 ops/ms
# Warmup Iteration   3: 8.189 ops/ms
Iteration   1: 8.311 ops/ms
Iteration   2: 7.971 ops/ms
Iteration   3: 8.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.183 ±(99.9%) 3.365 ops/ms [Average]
  (min, avg, max) = (7.971, 8.183, 8.311), stdev = 0.184
  CI (99.9%): [4.818, 11.548] (assumes normal distribution)


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.003 ms/op
Iteration   1: 3.066 ±(99.9%) 0.002 ms/op
Iteration   2: 3.162 ±(99.9%) 0.002 ms/op
Iteration   3: 3.124 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.117 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (3.066, 3.117, 3.162), stdev = 0.048
  CI (99.9%): [2.233, 4.002] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.776 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.947 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.003 ms/op
Iteration   1: 2.923 ±(99.9%) 0.002 ms/op
Iteration   2: 2.966 ±(99.9%) 0.002 ms/op
Iteration   3: 2.990 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.960 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (2.923, 2.960, 2.990), stdev = 0.034
  CI (99.9%): [2.340, 3.580] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.062 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.003 ms/op
Iteration   1: 3.024 ±(99.9%) 0.003 ms/op
Iteration   2: 3.109 ±(99.9%) 0.004 ms/op
Iteration   3: 3.053 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 0.788 ms/op [Average]
  (min, avg, max) = (3.024, 3.062, 3.109), stdev = 0.043
  CI (99.9%): [2.274, 3.849] (assumes normal distribution)


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
# Warmup Iteration   1: 5.254 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.017 ms/op
Iteration   1: 4.094 ±(99.9%) 0.017 ms/op
Iteration   2: 3.979 ±(99.9%) 0.011 ms/op
Iteration   3: 4.038 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.037 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.979, 4.037, 4.094), stdev = 0.058
  CI (99.9%): [2.986, 5.088] (assumes normal distribution)


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
Iteration   1: 3.202 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.069 ms/op
                 createUser·p0.9999: 17.532 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   2: 3.205 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.484 ms/op
                 createUser·p0.9999: 14.172 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  6.802 ms/op
                 createUser·p0.9999: 15.605 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302272
  mean =      3.174 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 890 
    [ 1.250,  2.500) = 21813 
    [ 2.500,  3.750) = 234007 
    [ 3.750,  5.000) = 44487 
    [ 5.000,  6.250) = 515 
    [ 6.250,  7.500) = 250 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.636 ms/op
     p(99.9900) =     16.868 ms/op
     p(99.9990) =     17.858 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.005 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  5.669 ms/op
                 existUser·p0.9999: 11.764 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  5.984 ms/op
                 existUser·p0.9999: 12.763 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.166 ms/op
                 existUser·p0.9999: 19.202 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324339
  mean =      2.958 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2567 
    [ 1.250,  2.500) = 38625 
    [ 2.500,  3.750) = 265980 
    [ 3.750,  5.000) = 16531 
    [ 5.000,  6.250) = 355 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      5.994 ms/op
     p(99.9900) =     16.768 ms/op
     p(99.9990) =     19.325 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.396 ms/op
                 getUser·p0.999:  7.210 ms/op
                 getUser·p0.9999: 11.895 ms/op
                 getUser·p1.00:   12.141 ms/op

Iteration   2: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.372 ms/op
                 getUser·p0.9999: 13.730 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.260 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  5.843 ms/op
                 getUser·p0.9999: 15.688 ms/op
                 getUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314070
  mean =      3.056 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1213 
    [ 1.250,  2.500) = 27393 
    [ 2.500,  3.750) = 263412 
    [ 3.750,  5.000) = 21128 
    [ 5.000,  6.250) = 582 
    [ 6.250,  7.500) = 116 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.260 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.398 ms/op
     p(99.9900) =     14.123 ms/op
     p(99.9990) =     15.932 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 5.498 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.012 ms/op
Iteration   1: 4.083 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  12.165 ms/op
                 listUser·p0.9999: 14.556 ms/op
                 listUser·p1.00:   16.122 ms/op

Iteration   2: 4.069 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 23.036 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 4.022 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.956 ms/op
                 listUser·p0.9999: 18.679 ms/op
                 listUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236623
  mean =      4.058 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2577 
    [ 2.500,  5.000) = 201305 
    [ 5.000,  7.500) = 31419 
    [ 7.500, 10.000) = 877 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.047 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     23.479 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.315 ± 2.434  ops/ms
ClientGrpc.existUser                       thrpt       3  11.095 ± 2.946  ops/ms
ClientGrpc.getUser                         thrpt       3  10.499 ± 2.806  ops/ms
ClientGrpc.listUser                        thrpt       3   8.183 ± 3.365  ops/ms
ClientGrpc.createUser                       avgt       3   3.117 ± 0.885   ms/op
ClientGrpc.existUser                        avgt       3   2.960 ± 0.620   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 0.788   ms/op
ClientGrpc.listUser                         avgt       3   4.037 ± 1.051   ms/op
ClientGrpc.createUser                     sample  302272   3.174 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.646           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.636           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.868           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.957           ms/op
ClientGrpc.existUser                      sample  324339   2.958 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.510           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.994           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.768           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.530           ms/op
ClientGrpc.getUser                        sample  314070   3.056 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.260           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.398           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.123           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.056           ms/op
ClientGrpc.listUser                       sample  236623   4.058 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.077           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.047           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.627           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.527           ms/op
