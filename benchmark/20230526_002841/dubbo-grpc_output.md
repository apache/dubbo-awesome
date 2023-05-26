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
# Warmup Iteration   1: 4.498 ops/ms
# Warmup Iteration   2: 9.069 ops/ms
# Warmup Iteration   3: 9.976 ops/ms
Iteration   1: 10.643 ops/ms
Iteration   2: 10.507 ops/ms
Iteration   3: 10.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.662 ±(99.9%) 3.022 ops/ms [Average]
  (min, avg, max) = (10.507, 10.662, 10.836), stdev = 0.166
  CI (99.9%): [7.641, 13.684] (assumes normal distribution)


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
# Warmup Iteration   1: 7.339 ops/ms
# Warmup Iteration   2: 10.510 ops/ms
# Warmup Iteration   3: 11.293 ops/ms
Iteration   1: 11.228 ops/ms
Iteration   2: 11.134 ops/ms
Iteration   3: 11.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.183 ±(99.9%) 0.853 ops/ms [Average]
  (min, avg, max) = (11.134, 11.183, 11.228), stdev = 0.047
  CI (99.9%): [10.330, 12.036] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.169 ops/ms
# Warmup Iteration   2: 10.281 ops/ms
# Warmup Iteration   3: 10.417 ops/ms
Iteration   1: 10.521 ops/ms
Iteration   2: 10.553 ops/ms
Iteration   3: 10.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.584 ±(99.9%) 1.488 ops/ms [Average]
  (min, avg, max) = (10.521, 10.584, 10.676), stdev = 0.082
  CI (99.9%): [9.095, 12.072] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.650 ops/ms
# Warmup Iteration   2: 7.856 ops/ms
# Warmup Iteration   3: 7.964 ops/ms
Iteration   1: 8.095 ops/ms
Iteration   2: 8.083 ops/ms
Iteration   3: 8.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.095 ±(99.9%) 0.229 ops/ms [Average]
  (min, avg, max) = (8.083, 8.095, 8.108), stdev = 0.013
  CI (99.9%): [7.866, 8.324] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.371 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.002 ms/op
Iteration   1: 2.984 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.002 ms/op
Iteration   3: 3.010 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.004 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.984, 3.004, 3.018), stdev = 0.018
  CI (99.9%): [2.681, 3.327] (assumes normal distribution)


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
# Warmup Iteration   1: 4.126 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.882 ±(99.9%) 0.002 ms/op
Iteration   1: 2.962 ±(99.9%) 0.004 ms/op
Iteration   2: 2.878 ±(99.9%) 0.002 ms/op
Iteration   3: 2.837 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (2.837, 2.892, 2.962), stdev = 0.064
  CI (99.9%): [1.729, 4.055] (assumes normal distribution)


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.004 ms/op
Iteration   1: 3.051 ±(99.9%) 0.002 ms/op
Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
Iteration   3: 2.976 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.025 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (2.976, 3.025, 3.051), stdev = 0.043
  CI (99.9%): [2.248, 3.802] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.642 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.013 ms/op
Iteration   1: 3.985 ±(99.9%) 0.014 ms/op
Iteration   2: 3.953 ±(99.9%) 0.021 ms/op
Iteration   3: 4.002 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.980 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (3.953, 3.980, 4.002), stdev = 0.025
  CI (99.9%): [3.524, 4.435] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.102 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.549 ms/op
                 createUser·p0.9999: 18.430 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.896 ms/op
                 createUser·p0.9999: 15.155 ms/op
                 createUser·p1.00:   15.401 ms/op

Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  10.404 ms/op
                 createUser·p0.9999: 17.664 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316223
  mean =      3.035 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 882 
    [ 1.250,  2.500) = 22484 
    [ 2.500,  3.750) = 274574 
    [ 3.750,  5.000) = 17089 
    [ 5.000,  6.250) = 598 
    [ 6.250,  7.500) = 256 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.705 ms/op
     p(99.9900) =     18.035 ms/op
     p(99.9990) =     19.262 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.002 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
Iteration   1: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.594 ms/op
                 existUser·p0.9999: 13.107 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   2: 2.879 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   3.961 ms/op
                 existUser·p0.999:  7.763 ms/op
                 existUser·p0.9999: 15.237 ms/op
                 existUser·p1.00:   16.466 ms/op

Iteration   3: 2.860 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  7.053 ms/op
                 existUser·p0.9999: 29.622 ms/op
                 existUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333591
  mean =      2.877 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44664 
    [ 2.500,  5.000) = 287710 
    [ 5.000,  7.500) = 876 
    [ 7.500, 10.000) = 180 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     18.654 ms/op
     p(99.9990) =     29.961 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.776 ms/op
                 getUser·p0.999:  7.649 ms/op
                 getUser·p0.9999: 12.312 ms/op
                 getUser·p1.00:   12.567 ms/op

Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.615 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  6.291 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.127 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319955
  mean =      3.003 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 416 
    [ 1.250,  2.500) = 26770 
    [ 2.500,  3.750) = 276427 
    [ 3.750,  5.000) = 14738 
    [ 5.000,  6.250) = 1066 
    [ 6.250,  7.500) = 283 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     17.433 ms/op
     p(99.9990) =     19.563 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 5.673 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.011 ms/op
Iteration   1: 4.005 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  13.406 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   2: 3.994 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.965 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 22.314 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 3.865 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  15.452 ms/op
                 listUser·p0.9999: 19.202 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242948
  mean =      3.954 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3130 
    [ 2.500,  5.000) = 216685 
    [ 5.000,  7.500) = 21780 
    [ 7.500, 10.000) = 838 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.600 ms/op
     p(99.9900) =     21.060 ms/op
     p(99.9990) =     22.760 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.662 ± 3.022  ops/ms
ClientGrpc.existUser                       thrpt       3  11.183 ± 0.853  ops/ms
ClientGrpc.getUser                         thrpt       3  10.584 ± 1.488  ops/ms
ClientGrpc.listUser                        thrpt       3   8.095 ± 0.229  ops/ms
ClientGrpc.createUser                       avgt       3   3.004 ± 0.323   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 1.163   ms/op
ClientGrpc.getUser                          avgt       3   3.025 ± 0.777   ms/op
ClientGrpc.listUser                         avgt       3   3.980 ± 0.455   ms/op
ClientGrpc.createUser                     sample  316223   3.035 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.628           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.705           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.035           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.431           ms/op
ClientGrpc.existUser                      sample  333591   2.877 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.554           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.545           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.654           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.114           ms/op
ClientGrpc.getUser                        sample  319955   3.003 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.615           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.152           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.433           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.694           ms/op
ClientGrpc.listUser                       sample  242948   3.954 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.791           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.600           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.060           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.807           ms/op
