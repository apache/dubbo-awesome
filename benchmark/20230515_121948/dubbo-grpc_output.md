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
# Warmup Iteration   1: 3.927 ops/ms
# Warmup Iteration   2: 8.817 ops/ms
# Warmup Iteration   3: 10.090 ops/ms
Iteration   1: 10.394 ops/ms
Iteration   2: 10.561 ops/ms
Iteration   3: 10.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.485 ±(99.9%) 1.543 ops/ms [Average]
  (min, avg, max) = (10.394, 10.485, 10.561), stdev = 0.085
  CI (99.9%): [8.942, 12.028] (assumes normal distribution)


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
# Warmup Iteration   1: 7.225 ops/ms
# Warmup Iteration   2: 10.578 ops/ms
# Warmup Iteration   3: 11.082 ops/ms
Iteration   1: 11.222 ops/ms
Iteration   2: 11.184 ops/ms
Iteration   3: 11.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.271 ±(99.9%) 2.165 ops/ms [Average]
  (min, avg, max) = (11.184, 11.271, 11.406), stdev = 0.119
  CI (99.9%): [9.106, 13.436] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.470 ops/ms
# Warmup Iteration   2: 9.948 ops/ms
# Warmup Iteration   3: 10.460 ops/ms
Iteration   1: 10.484 ops/ms
Iteration   2: 10.302 ops/ms
Iteration   3: 10.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.419 ±(99.9%) 1.864 ops/ms [Average]
  (min, avg, max) = (10.302, 10.419, 10.484), stdev = 0.102
  CI (99.9%): [8.556, 12.283] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.705 ops/ms
# Warmup Iteration   2: 7.580 ops/ms
# Warmup Iteration   3: 8.028 ops/ms
Iteration   1: 7.970 ops/ms
Iteration   2: 8.209 ops/ms
Iteration   3: 8.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.116 ±(99.9%) 2.339 ops/ms [Average]
  (min, avg, max) = (7.970, 8.116, 8.209), stdev = 0.128
  CI (99.9%): [5.777, 10.455] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.479 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.004 ms/op
Iteration   1: 3.117 ±(99.9%) 0.002 ms/op
Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
Iteration   3: 3.091 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.071 ±(99.9%) 1.066 ms/op [Average]
  (min, avg, max) = (3.005, 3.071, 3.117), stdev = 0.058
  CI (99.9%): [2.006, 4.137] (assumes normal distribution)


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.003 ms/op
Iteration   1: 2.862 ±(99.9%) 0.002 ms/op
Iteration   2: 2.898 ±(99.9%) 0.002 ms/op
Iteration   3: 2.830 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.863 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (2.830, 2.863, 2.898), stdev = 0.034
  CI (99.9%): [2.251, 3.476] (assumes normal distribution)


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.003 ms/op
Iteration   1: 2.998 ±(99.9%) 0.003 ms/op
Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
Iteration   3: 2.966 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.987 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (2.966, 2.987, 2.998), stdev = 0.019
  CI (99.9%): [2.647, 3.328] (assumes normal distribution)


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
# Warmup Iteration   1: 5.009 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.006 ms/op
Iteration   1: 3.836 ±(99.9%) 0.008 ms/op
Iteration   2: 3.866 ±(99.9%) 0.025 ms/op
Iteration   3: 3.961 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.888 ±(99.9%) 1.197 ms/op [Average]
  (min, avg, max) = (3.836, 3.888, 3.961), stdev = 0.066
  CI (99.9%): [2.691, 5.085] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.406 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
Iteration   1: 3.032 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.815 ms/op
                 createUser·p0.9999: 31.502 ms/op
                 createUser·p1.00:   32.178 ms/op

Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  6.488 ms/op
                 createUser·p0.9999: 19.576 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.518 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  8.373 ms/op
                 createUser·p0.9999: 20.293 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318498
  mean =      3.013 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22861 
    [ 2.500,  5.000) = 294370 
    [ 5.000,  7.500) = 935 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     29.960 ms/op
     p(99.9990) =     32.041 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.129 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
Iteration   1: 2.880 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  6.414 ms/op
                 existUser·p0.9999: 14.467 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.828 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.569 ms/op
                 existUser·p0.9999: 14.529 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   3: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  12.485 ms/op
                 existUser·p0.9999: 18.219 ms/op
                 existUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334755
  mean =      2.868 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2027 
    [ 1.250,  2.500) = 44332 
    [ 2.500,  3.750) = 281143 
    [ 3.750,  5.000) = 6072 
    [ 5.000,  6.250) = 620 
    [ 6.250,  7.500) = 236 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.502 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     17.974 ms/op
     p(99.9990) =     18.458 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.034 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.913 ms/op
                 getUser·p0.9999: 22.905 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   2: 3.005 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  8.019 ms/op
                 getUser·p0.9999: 29.491 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.104 ms/op
                 getUser·p0.9999: 21.782 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318180
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21647 
    [ 2.500,  5.000) = 295168 
    [ 5.000,  7.500) = 1026 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.824 ms/op
     p(99.9900) =     28.395 ms/op
     p(99.9990) =     30.102 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 5.486 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.010 ms/op
Iteration   1: 4.050 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 20.654 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   2: 3.891 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.250 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 24.831 ms/op
                 listUser·p1.00:   25.395 ms/op

Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 19.613 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242638
  mean =      3.955 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1629 
    [ 2.500,  5.000) = 219146 
    [ 5.000,  7.500) = 20554 
    [ 7.500, 10.000) = 894 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     24.059 ms/op
     p(99.9990) =     25.227 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.485 ± 1.543  ops/ms
ClientGrpc.existUser                       thrpt       3  11.271 ± 2.165  ops/ms
ClientGrpc.getUser                         thrpt       3  10.419 ± 1.864  ops/ms
ClientGrpc.listUser                        thrpt       3   8.116 ± 2.339  ops/ms
ClientGrpc.createUser                       avgt       3   3.071 ± 1.066   ms/op
ClientGrpc.existUser                        avgt       3   2.863 ± 0.612   ms/op
ClientGrpc.getUser                          avgt       3   2.987 ± 0.341   ms/op
ClientGrpc.listUser                         avgt       3   3.888 ± 1.197   ms/op
ClientGrpc.createUser                     sample  318498   3.013 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.674           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.758           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.960           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.178           ms/op
ClientGrpc.existUser                      sample  334755   2.868 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.820           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.974           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.547           ms/op
ClientGrpc.getUser                        sample  318180   3.015 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.659           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.824           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.395           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.179           ms/op
ClientGrpc.listUser                       sample  242638   3.955 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.202           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.318           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.059           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.395           ms/op
