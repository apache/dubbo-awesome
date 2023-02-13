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
# Warmup Iteration   1: 3.902 ops/ms
# Warmup Iteration   2: 8.497 ops/ms
# Warmup Iteration   3: 9.757 ops/ms
Iteration   1: 9.980 ops/ms
Iteration   2: 9.849 ops/ms
Iteration   3: 9.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.894 ±(99.9%) 1.356 ops/ms [Average]
  (min, avg, max) = (9.849, 9.894, 9.980), stdev = 0.074
  CI (99.9%): [8.538, 11.250] (assumes normal distribution)


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
# Warmup Iteration   1: 6.935 ops/ms
# Warmup Iteration   2: 10.284 ops/ms
# Warmup Iteration   3: 10.513 ops/ms
Iteration   1: 10.455 ops/ms
Iteration   2: 10.512 ops/ms
Iteration   3: 10.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.448 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (10.377, 10.448, 10.512), stdev = 0.068
  CI (99.9%): [9.213, 11.684] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.551 ops/ms
# Warmup Iteration   2: 9.749 ops/ms
# Warmup Iteration   3: 9.957 ops/ms
Iteration   1: 9.854 ops/ms
Iteration   2: 9.902 ops/ms
Iteration   3: 9.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.870 ±(99.9%) 0.499 ops/ms [Average]
  (min, avg, max) = (9.854, 9.870, 9.902), stdev = 0.027
  CI (99.9%): [9.371, 10.369] (assumes normal distribution)


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
# Warmup Iteration   1: 4.990 ops/ms
# Warmup Iteration   2: 7.498 ops/ms
# Warmup Iteration   3: 7.743 ops/ms
Iteration   1: 7.896 ops/ms
Iteration   2: 7.814 ops/ms
Iteration   3: 7.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.863 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (7.814, 7.863, 7.896), stdev = 0.043
  CI (99.9%): [7.070, 8.656] (assumes normal distribution)


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
# Warmup Iteration   1: 4.554 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.003 ms/op
Iteration   1: 3.196 ±(99.9%) 0.004 ms/op
Iteration   2: 3.234 ±(99.9%) 0.001 ms/op
Iteration   3: 3.198 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.210 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.196, 3.210, 3.234), stdev = 0.021
  CI (99.9%): [2.825, 3.594] (assumes normal distribution)


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
# Warmup Iteration   1: 4.139 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.002 ms/op
Iteration   1: 3.128 ±(99.9%) 0.001 ms/op
Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
Iteration   3: 3.067 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.091 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.067, 3.091, 3.128), stdev = 0.033
  CI (99.9%): [2.493, 3.689] (assumes normal distribution)


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
# Warmup Iteration   1: 4.261 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.002 ms/op
Iteration   1: 3.281 ±(99.9%) 0.002 ms/op
Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
Iteration   3: 3.245 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.252 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (3.231, 3.252, 3.281), stdev = 0.026
  CI (99.9%): [2.782, 3.722] (assumes normal distribution)


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
# Warmup Iteration   1: 6.078 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.274 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.062 ms/op
Iteration   1: 4.071 ±(99.9%) 0.018 ms/op
Iteration   2: 3.865 ±(99.9%) 0.016 ms/op
Iteration   3: 4.089 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.008 ±(99.9%) 2.273 ms/op [Average]
  (min, avg, max) = (3.865, 4.008, 4.089), stdev = 0.125
  CI (99.9%): [1.735, 6.281] (assumes normal distribution)


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
# Warmup Iteration   1: 4.331 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.008 ms/op
Iteration   1: 3.326 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  9.976 ms/op
                 createUser·p0.9999: 13.638 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   2: 3.369 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  12.108 ms/op
                 createUser·p0.9999: 16.089 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  14.771 ms/op
                 createUser·p0.9999: 20.912 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 289307
  mean =      3.319 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12456 
    [ 2.500,  5.000) = 275111 
    [ 5.000,  7.500) = 1044 
    [ 7.500, 10.000) = 305 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =     10.879 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     21.273 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
Iteration   1: 3.117 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.671 ms/op
                 existUser·p0.9999: 12.713 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  9.809 ms/op
                 existUser·p0.9999: 14.909 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.096 ms/op
                 existUser·p0.9999: 15.980 ms/op
                 existUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311730
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1369 
    [ 1.250,  2.500) = 35504 
    [ 2.500,  3.750) = 240076 
    [ 3.750,  5.000) = 33870 
    [ 5.000,  6.250) = 420 
    [ 6.250,  7.500) = 219 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.099 ms/op
     p(99.9900) =     15.035 ms/op
     p(99.9990) =     16.200 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
Iteration   1: 3.208 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  6.989 ms/op
                 getUser·p0.9999: 13.305 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   2: 3.208 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.761 ms/op
                 getUser·p0.9999: 15.501 ms/op
                 getUser·p1.00:   16.155 ms/op

Iteration   3: 3.277 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  6.210 ms/op
                 getUser·p0.9999: 19.505 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297298
  mean =      3.231 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15791 
    [ 2.500,  5.000) = 280633 
    [ 5.000,  7.500) = 688 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      6.764 ms/op
     p(99.9900) =     17.909 ms/op
     p(99.9990) =     20.422 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 6.303 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.270 ±(99.9%) 0.013 ms/op
Iteration   1: 4.063 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.044 ms/op
                 listUser·p0.999:  12.435 ms/op
                 listUser·p0.9999: 16.239 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   2: 4.245 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.229 ms/op
                 listUser·p0.999:  16.368 ms/op
                 listUser·p0.9999: 23.867 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   3: 4.198 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.087 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  16.432 ms/op
                 listUser·p0.9999: 21.883 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230549
  mean =      4.167 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1917 
    [ 2.500,  5.000) = 196568 
    [ 5.000,  7.500) = 30421 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      6.013 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.834 ms/op
     p(99.9900) =     22.477 ms/op
     p(99.9990) =     24.206 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.894 ± 1.356  ops/ms
ClientGrpc.existUser                       thrpt       3  10.448 ± 1.236  ops/ms
ClientGrpc.getUser                         thrpt       3   9.870 ± 0.499  ops/ms
ClientGrpc.listUser                        thrpt       3   7.863 ± 0.793  ops/ms
ClientGrpc.createUser                       avgt       3   3.210 ± 0.385   ms/op
ClientGrpc.existUser                        avgt       3   3.091 ± 0.598   ms/op
ClientGrpc.getUser                          avgt       3   3.252 ± 0.470   ms/op
ClientGrpc.listUser                         avgt       3   4.008 ± 2.273   ms/op
ClientGrpc.createUser                     sample  289307   3.319 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.790           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.277           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.022           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.879           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.087           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.398           ms/op
ClientGrpc.existUser                      sample  311730   3.079 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.746           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.064           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.099           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.035           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.564           ms/op
ClientGrpc.getUser                        sample  297298   3.231 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.725           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.207           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.125           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.764           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.909           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.742           ms/op
ClientGrpc.listUser                       sample  230549   4.167 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.870           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.973           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.382           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.834           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.477           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.297           ms/op
