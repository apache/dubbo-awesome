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
# Warmup Iteration   1: 4.292 ops/ms
# Warmup Iteration   2: 8.936 ops/ms
# Warmup Iteration   3: 10.077 ops/ms
Iteration   1: 10.418 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.553 ±(99.9%) 2.228 ops/ms [Average]
  (min, avg, max) = (10.418, 10.553, 10.655), stdev = 0.122
  CI (99.9%): [8.325, 12.781] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.240 ops/ms
# Warmup Iteration   2: 10.441 ops/ms
# Warmup Iteration   3: 11.041 ops/ms
Iteration   1: 11.124 ops/ms
Iteration   2: 11.090 ops/ms
Iteration   3: 11.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.091 ±(99.9%) 0.602 ops/ms [Average]
  (min, avg, max) = (11.058, 11.091, 11.124), stdev = 0.033
  CI (99.9%): [10.489, 11.692] (assumes normal distribution)


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
# Warmup Iteration   1: 7.339 ops/ms
# Warmup Iteration   2: 10.088 ops/ms
# Warmup Iteration   3: 10.408 ops/ms
Iteration   1: 10.499 ops/ms
Iteration   2: 10.405 ops/ms
Iteration   3: 10.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.515 ±(99.9%) 2.167 ops/ms [Average]
  (min, avg, max) = (10.405, 10.515, 10.641), stdev = 0.119
  CI (99.9%): [8.348, 12.681] (assumes normal distribution)


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
# Warmup Iteration   1: 5.482 ops/ms
# Warmup Iteration   2: 7.647 ops/ms
# Warmup Iteration   3: 8.053 ops/ms
Iteration   1: 8.044 ops/ms
Iteration   2: 8.287 ops/ms
Iteration   3: 8.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.165 ±(99.9%) 2.212 ops/ms [Average]
  (min, avg, max) = (8.044, 8.165, 8.287), stdev = 0.121
  CI (99.9%): [5.952, 10.377] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.421 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
Iteration   2: 3.053 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.051 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.027, 3.051, 3.072), stdev = 0.022
  CI (99.9%): [2.641, 3.460] (assumes normal distribution)


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.002 ms/op
Iteration   1: 3.011 ±(99.9%) 0.001 ms/op
Iteration   2: 2.903 ±(99.9%) 0.002 ms/op
Iteration   3: 2.925 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.946 ±(99.9%) 1.043 ms/op [Average]
  (min, avg, max) = (2.903, 2.946, 3.011), stdev = 0.057
  CI (99.9%): [1.903, 3.990] (assumes normal distribution)


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.003 ms/op
Iteration   1: 3.052 ±(99.9%) 0.004 ms/op
Iteration   2: 3.042 ±(99.9%) 0.004 ms/op
Iteration   3: 3.069 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.054 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (3.042, 3.054, 3.069), stdev = 0.014
  CI (99.9%): [2.804, 3.304] (assumes normal distribution)


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.022 ms/op
Iteration   1: 3.932 ±(99.9%) 0.018 ms/op
Iteration   2: 3.941 ±(99.9%) 0.012 ms/op
Iteration   3: 3.909 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.927 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (3.909, 3.927, 3.941), stdev = 0.016
  CI (99.9%): [3.629, 4.225] (assumes normal distribution)


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
# Warmup Iteration   1: 4.328 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
Iteration   1: 3.088 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  8.559 ms/op
                 createUser·p0.9999: 12.861 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  10.346 ms/op
                 createUser·p0.9999: 14.133 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.979 ms/op
                 createUser·p0.9999: 17.682 ms/op
                 createUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312449
  mean =      3.072 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 375 
    [ 1.250,  2.500) = 21017 
    [ 2.500,  3.750) = 272497 
    [ 3.750,  5.000) = 17189 
    [ 5.000,  6.250) = 640 
    [ 6.250,  7.500) = 275 
    [ 7.500,  8.750) = 129 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      9.841 ms/op
     p(99.9900) =     17.187 ms/op
     p(99.9990) =     17.756 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 3.883 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.006 ms/op
Iteration   1: 2.872 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.657 ms/op
                 existUser·p0.9999: 12.384 ms/op
                 existUser·p1.00:   12.550 ms/op

Iteration   2: 2.889 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.320 ms/op
                 existUser·p0.9999: 13.005 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   3: 2.895 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 28.015 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332605
  mean =      2.885 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41159 
    [ 2.500,  5.000) = 290433 
    [ 5.000,  7.500) = 740 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      6.966 ms/op
     p(99.9900) =     16.101 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 4.610 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
Iteration   1: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  6.410 ms/op
                 getUser·p0.9999: 25.341 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  7.427 ms/op
                 getUser·p0.9999: 27.639 ms/op
                 getUser·p1.00:   28.770 ms/op

Iteration   3: 3.001 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.524 ms/op
                 getUser·p0.9999: 21.070 ms/op
                 getUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318495
  mean =      3.013 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23456 
    [ 2.500,  5.000) = 293856 
    [ 5.000,  7.500) = 957 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.869 ms/op
     p(99.9900) =     27.039 ms/op
     p(99.9990) =     27.754 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 5.289 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.012 ms/op
Iteration   1: 4.014 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.006 ms/op
                 listUser·p0.999:  12.599 ms/op
                 listUser·p0.9999: 14.927 ms/op
                 listUser·p1.00:   16.220 ms/op

Iteration   2: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.043 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 16.405 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 4.089 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.676 ms/op
                 listUser·p0.9999: 27.629 ms/op
                 listUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236702
  mean =      4.054 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2432 
    [ 2.500,  5.000) = 208823 
    [ 5.000,  7.500) = 24031 
    [ 7.500, 10.000) = 983 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     14.292 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     29.255 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.553 ± 2.228  ops/ms
ClientGrpc.existUser                       thrpt       3  11.091 ± 0.602  ops/ms
ClientGrpc.getUser                         thrpt       3  10.515 ± 2.167  ops/ms
ClientGrpc.listUser                        thrpt       3   8.165 ± 2.212  ops/ms
ClientGrpc.createUser                       avgt       3   3.051 ± 0.410   ms/op
ClientGrpc.existUser                        avgt       3   2.946 ± 1.043   ms/op
ClientGrpc.getUser                          avgt       3   3.054 ± 0.250   ms/op
ClientGrpc.listUser                         avgt       3   3.927 ± 0.298   ms/op
ClientGrpc.createUser                     sample  312449   3.072 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.755           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.841           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.187           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.252           ms/op
ClientGrpc.existUser                      sample  332605   2.885 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.670           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.966           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.101           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.279           ms/op
ClientGrpc.getUser                        sample  318495   3.013 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.676           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.869           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.039           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.770           ms/op
ClientGrpc.listUser                       sample  236702   4.054 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.198           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.292           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.099           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.884           ms/op
