# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.344 ops/ms
# Warmup Iteration   2: 8.497 ops/ms
# Warmup Iteration   3: 9.927 ops/ms
Iteration   1: 10.217 ops/ms
Iteration   2: 10.529 ops/ms
Iteration   3: 10.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.405 ±(99.9%) 3.024 ops/ms [Average]
  (min, avg, max) = (10.217, 10.405, 10.529), stdev = 0.166
  CI (99.9%): [7.381, 13.430] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.335 ops/ms
# Warmup Iteration   2: 10.601 ops/ms
# Warmup Iteration   3: 11.093 ops/ms
Iteration   1: 11.077 ops/ms
Iteration   2: 10.844 ops/ms
Iteration   3: 11.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.059 ±(99.9%) 3.780 ops/ms [Average]
  (min, avg, max) = (10.844, 11.059, 11.257), stdev = 0.207
  CI (99.9%): [7.280, 14.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.484 ops/ms
# Warmup Iteration   2: 10.184 ops/ms
# Warmup Iteration   3: 10.720 ops/ms
Iteration   1: 10.628 ops/ms
Iteration   2: 10.618 ops/ms
Iteration   3: 10.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.688 ±(99.9%) 2.034 ops/ms [Average]
  (min, avg, max) = (10.618, 10.688, 10.816), stdev = 0.111
  CI (99.9%): [8.653, 12.722] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.994 ops/ms
# Warmup Iteration   2: 7.899 ops/ms
# Warmup Iteration   3: 7.726 ops/ms
Iteration   1: 8.057 ops/ms
Iteration   2: 8.174 ops/ms
Iteration   3: 8.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.134 ±(99.9%) 1.214 ops/ms [Average]
  (min, avg, max) = (8.057, 8.134, 8.174), stdev = 0.067
  CI (99.9%): [6.920, 9.349] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.013 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.002 ms/op
Iteration   1: 3.065 ±(99.9%) 0.002 ms/op
Iteration   2: 3.002 ±(99.9%) 0.003 ms/op
Iteration   3: 3.025 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.031 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (3.002, 3.031, 3.065), stdev = 0.032
  CI (99.9%): [2.454, 3.607] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 2.860 ±(99.9%) 0.003 ms/op
Iteration   1: 2.932 ±(99.9%) 0.004 ms/op
Iteration   2: 2.830 ±(99.9%) 0.004 ms/op
Iteration   3: 2.890 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.884 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (2.830, 2.884, 2.932), stdev = 0.051
  CI (99.9%): [1.945, 3.823] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.074 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.003 ms/op
Iteration   1: 2.946 ±(99.9%) 0.004 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 2.978 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.970 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (2.946, 2.970, 2.985), stdev = 0.021
  CI (99.9%): [2.595, 3.344] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.013 ms/op
Iteration   1: 3.928 ±(99.9%) 0.026 ms/op
Iteration   2: 3.942 ±(99.9%) 0.024 ms/op
Iteration   3: 3.901 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.924 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (3.901, 3.924, 3.942), stdev = 0.021
  CI (99.9%): [3.543, 4.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.114 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.008 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  8.985 ms/op
                 createUser·p0.9999: 16.287 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  8.366 ms/op
                 createUser·p0.9999: 16.768 ms/op
                 createUser·p1.00:   18.678 ms/op

Iteration   3: 3.027 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.460 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  8.097 ms/op
                 createUser·p0.9999: 26.720 ms/op
                 createUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315991
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20035 
    [ 2.500,  5.000) = 293570 
    [ 5.000,  7.500) = 1778 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     26.990 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.943 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
Iteration   1: 2.942 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  8.492 ms/op
                 existUser·p0.9999: 12.980 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   2: 2.955 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  7.273 ms/op
                 existUser·p0.9999: 12.851 ms/op
                 existUser·p1.00:   13.238 ms/op

Iteration   3: 2.947 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 18.621 ms/op
                 existUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325423
  mean =      2.948 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2238 
    [ 1.250,  2.500) = 38627 
    [ 2.500,  3.750) = 269957 
    [ 3.750,  5.000) = 12382 
    [ 5.000,  6.250) = 1183 
    [ 6.250,  7.500) = 492 
    [ 7.500,  8.750) = 219 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      8.752 ms/op
     p(99.9900) =     17.317 ms/op
     p(99.9990) =     18.989 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.703 ms/op
                 getUser·p0.9999: 13.397 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.971 ms/op
                 getUser·p0.9999: 22.447 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   3: 3.007 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  7.534 ms/op
                 getUser·p0.9999: 24.478 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316931
  mean =      3.027 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23474 
    [ 2.500,  5.000) = 291262 
    [ 5.000,  7.500) = 1776 
    [ 7.500, 10.000) = 203 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.045 ms/op
     p(99.9900) =     23.439 ms/op
     p(99.9990) =     25.777 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.218 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.011 ms/op
Iteration   1: 3.919 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  12.916 ms/op
                 listUser·p0.9999: 19.202 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 3.944 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.472 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  14.267 ms/op
                 listUser·p0.9999: 17.429 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   3: 3.914 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.527 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.569 ms/op
                 listUser·p0.9999: 27.623 ms/op
                 listUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244616
  mean =      3.926 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4710 
    [ 2.500,  5.000) = 215108 
    [ 5.000,  7.500) = 23046 
    [ 7.500, 10.000) = 1137 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     14.555 ms/op
     p(99.9900) =     22.875 ms/op
     p(99.9990) =     27.889 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.405 ± 3.024  ops/ms
ClientGrpc.existUser                       thrpt       3  11.059 ± 3.780  ops/ms
ClientGrpc.getUser                         thrpt       3  10.688 ± 2.034  ops/ms
ClientGrpc.listUser                        thrpt       3   8.134 ± 1.214  ops/ms
ClientGrpc.createUser                       avgt       3   3.031 ± 0.577   ms/op
ClientGrpc.existUser                        avgt       3   2.884 ± 0.939   ms/op
ClientGrpc.getUser                          avgt       3   2.970 ± 0.374   ms/op
ClientGrpc.listUser                         avgt       3   3.924 ± 0.381   ms/op
ClientGrpc.createUser                     sample  315991   3.036 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.460           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.520           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.428           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.296           ms/op
ClientGrpc.existUser                      sample  325423   2.948 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.675           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.702           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.752           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.317           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.137           ms/op
ClientGrpc.getUser                        sample  316931   3.027 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.717           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.045           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.439           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.149           ms/op
ClientGrpc.listUser                       sample  244616   3.926 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.472           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.555           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.875           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.951           ms/op
