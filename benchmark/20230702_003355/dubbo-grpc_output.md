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
# Warmup Iteration   1: 3.920 ops/ms
# Warmup Iteration   2: 8.846 ops/ms
# Warmup Iteration   3: 10.014 ops/ms
Iteration   1: 10.341 ops/ms
Iteration   2: 10.366 ops/ms
Iteration   3: 10.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.411 ±(99.9%) 1.841 ops/ms [Average]
  (min, avg, max) = (10.341, 10.411, 10.527), stdev = 0.101
  CI (99.9%): [8.570, 12.253] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.496 ops/ms
# Warmup Iteration   2: 10.462 ops/ms
# Warmup Iteration   3: 11.071 ops/ms
Iteration   1: 11.157 ops/ms
Iteration   2: 10.951 ops/ms
Iteration   3: 11.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.053 ±(99.9%) 1.874 ops/ms [Average]
  (min, avg, max) = (10.951, 11.053, 11.157), stdev = 0.103
  CI (99.9%): [9.179, 12.927] (assumes normal distribution)


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
# Warmup Iteration   1: 6.630 ops/ms
# Warmup Iteration   2: 9.644 ops/ms
# Warmup Iteration   3: 10.127 ops/ms
Iteration   1: 10.451 ops/ms
Iteration   2: 10.358 ops/ms
Iteration   3: 10.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.387 ±(99.9%) 1.023 ops/ms [Average]
  (min, avg, max) = (10.350, 10.387, 10.451), stdev = 0.056
  CI (99.9%): [9.364, 11.409] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.340 ops/ms
# Warmup Iteration   2: 7.516 ops/ms
# Warmup Iteration   3: 8.010 ops/ms
Iteration   1: 7.953 ops/ms
Iteration   2: 7.939 ops/ms
Iteration   3: 7.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.962 ±(99.9%) 0.526 ops/ms [Average]
  (min, avg, max) = (7.939, 7.962, 7.994), stdev = 0.029
  CI (99.9%): [7.435, 8.488] (assumes normal distribution)


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
# Warmup Iteration   1: 4.496 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.003 ms/op
Iteration   1: 3.109 ±(99.9%) 0.005 ms/op
Iteration   2: 3.100 ±(99.9%) 0.003 ms/op
Iteration   3: 3.065 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.091 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (3.065, 3.091, 3.109), stdev = 0.023
  CI (99.9%): [2.671, 3.512] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.182 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.002 ms/op
Iteration   1: 2.975 ±(99.9%) 0.003 ms/op
Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
Iteration   3: 3.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.992 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.975, 2.992, 3.003), stdev = 0.015
  CI (99.9%): [2.723, 3.260] (assumes normal distribution)


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.004 ms/op
Iteration   1: 3.044 ±(99.9%) 0.004 ms/op
Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
Iteration   3: 3.065 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.052 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.044, 3.052, 3.065), stdev = 0.011
  CI (99.9%): [2.853, 3.252] (assumes normal distribution)


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
# Warmup Iteration   1: 5.654 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.021 ms/op
Iteration   1: 4.044 ±(99.9%) 0.017 ms/op
Iteration   2: 4.062 ±(99.9%) 0.014 ms/op
Iteration   3: 3.988 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.032 ±(99.9%) 0.700 ms/op [Average]
  (min, avg, max) = (3.988, 4.032, 4.062), stdev = 0.038
  CI (99.9%): [3.332, 4.731] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  10.568 ms/op
                 createUser·p0.9999: 13.188 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  9.994 ms/op
                 createUser·p0.9999: 24.856 ms/op
                 createUser·p1.00:   30.835 ms/op

Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  11.613 ms/op
                 createUser·p0.9999: 20.204 ms/op
                 createUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314181
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17313 
    [ 2.500,  5.000) = 295127 
    [ 5.000,  7.500) = 1039 
    [ 7.500, 10.000) = 288 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     10.854 ms/op
     p(99.9900) =     21.556 ms/op
     p(99.9990) =     26.889 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 2.943 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.021 ms/op
                 existUser·p0.9999: 13.486 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   2: 2.928 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  7.498 ms/op
                 existUser·p0.9999: 15.173 ms/op
                 existUser·p1.00:   15.401 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  11.780 ms/op
                 existUser·p0.9999: 16.915 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325788
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 795 
    [ 1.250,  2.500) = 24632 
    [ 2.500,  3.750) = 291102 
    [ 3.750,  5.000) = 8108 
    [ 5.000,  6.250) = 507 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.913 ms/op
     p(99.9900) =     16.571 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.007 ms/op
Iteration   1: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.873 ms/op
                 getUser·p0.9999: 13.174 ms/op
                 getUser·p1.00:   13.533 ms/op

Iteration   2: 3.067 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.725 ms/op
                 getUser·p0.9999: 14.568 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.588 ms/op
                 getUser·p0.9999: 18.481 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313775
  mean =      3.060 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 538 
    [ 1.250,  2.500) = 17817 
    [ 2.500,  3.750) = 277232 
    [ 3.750,  5.000) = 16591 
    [ 5.000,  6.250) = 979 
    [ 6.250,  7.500) = 257 
    [ 7.500,  8.750) = 142 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.823 ms/op
     p(99.9900) =     16.296 ms/op
     p(99.9990) =     18.734 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 5.853 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.341 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.012 ms/op
Iteration   1: 4.064 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  15.247 ms/op
                 listUser·p0.9999: 22.713 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   2: 4.049 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.120 ms/op
                 listUser·p0.999:  16.024 ms/op
                 listUser·p0.9999: 27.201 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   3: 4.010 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.965 ms/op
                 listUser·p0.999:  17.502 ms/op
                 listUser·p0.9999: 21.300 ms/op
                 listUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237549
  mean =      4.041 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1801 
    [ 2.500,  5.000) = 211689 
    [ 5.000,  7.500) = 22546 
    [ 7.500, 10.000) = 1031 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     16.162 ms/op
     p(99.9900) =     25.436 ms/op
     p(99.9990) =     27.423 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.411 ± 1.841  ops/ms
ClientGrpc.existUser                       thrpt       3  11.053 ± 1.874  ops/ms
ClientGrpc.getUser                         thrpt       3  10.387 ± 1.023  ops/ms
ClientGrpc.listUser                        thrpt       3   7.962 ± 0.526  ops/ms
ClientGrpc.createUser                       avgt       3   3.091 ± 0.421   ms/op
ClientGrpc.existUser                        avgt       3   2.992 ± 0.268   ms/op
ClientGrpc.getUser                          avgt       3   3.052 ± 0.199   ms/op
ClientGrpc.listUser                         avgt       3   4.032 ± 0.700   ms/op
ClientGrpc.createUser                     sample  314181   3.059 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.716           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.854           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.556           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.835           ms/op
ClientGrpc.existUser                      sample  325788   2.946 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.765           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.913           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.571           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.007           ms/op
ClientGrpc.getUser                        sample  313775   3.060 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.771           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.823           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.296           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.874           ms/op
ClientGrpc.listUser                       sample  237549   4.041 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.130           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.162           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.436           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.591           ms/op
