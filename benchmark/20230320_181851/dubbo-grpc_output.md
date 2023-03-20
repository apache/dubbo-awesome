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
# Warmup Iteration   1: 4.474 ops/ms
# Warmup Iteration   2: 9.663 ops/ms
# Warmup Iteration   3: 10.618 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.771 ±(99.9%) 1.944 ops/ms [Average]
  (min, avg, max) = (10.655, 10.771, 10.866), stdev = 0.107
  CI (99.9%): [8.827, 12.715] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.149 ops/ms
# Warmup Iteration   2: 10.563 ops/ms
# Warmup Iteration   3: 11.404 ops/ms
Iteration   1: 11.121 ops/ms
Iteration   2: 11.492 ops/ms
Iteration   3: 11.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.293 ±(99.9%) 3.407 ops/ms [Average]
  (min, avg, max) = (11.121, 11.293, 11.492), stdev = 0.187
  CI (99.9%): [7.887, 14.700] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.207 ops/ms
# Warmup Iteration   2: 10.250 ops/ms
# Warmup Iteration   3: 10.672 ops/ms
Iteration   1: 10.796 ops/ms
Iteration   2: 10.695 ops/ms
Iteration   3: 10.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.791 ±(99.9%) 1.713 ops/ms [Average]
  (min, avg, max) = (10.695, 10.791, 10.882), stdev = 0.094
  CI (99.9%): [9.078, 12.504] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.558 ops/ms
# Warmup Iteration   2: 8.040 ops/ms
# Warmup Iteration   3: 8.303 ops/ms
Iteration   1: 8.228 ops/ms
Iteration   2: 8.155 ops/ms
Iteration   3: 8.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.251 ±(99.9%) 1.983 ops/ms [Average]
  (min, avg, max) = (8.155, 8.251, 8.369), stdev = 0.109
  CI (99.9%): [6.268, 10.234] (assumes normal distribution)


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 3.004 ±(99.9%) 0.003 ms/op
Iteration   2: 3.041 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.003 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (2.963, 3.003, 3.041), stdev = 0.039
  CI (99.9%): [2.291, 3.715] (assumes normal distribution)


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
# Warmup Iteration   1: 3.674 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.908 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.832 ±(99.9%) 0.003 ms/op
Iteration   1: 2.920 ±(99.9%) 0.004 ms/op
Iteration   2: 2.916 ±(99.9%) 0.002 ms/op
Iteration   3: 2.866 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.901 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (2.866, 2.901, 2.920), stdev = 0.030
  CI (99.9%): [2.348, 3.453] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.003 ms/op
Iteration   1: 2.980 ±(99.9%) 0.002 ms/op
Iteration   2: 2.974 ±(99.9%) 0.007 ms/op
Iteration   3: 2.931 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.962 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (2.931, 2.962, 2.980), stdev = 0.027
  CI (99.9%): [2.469, 3.454] (assumes normal distribution)


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
# Warmup Iteration   1: 5.092 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.036 ms/op
Iteration   1: 3.797 ±(99.9%) 0.016 ms/op
Iteration   2: 3.881 ±(99.9%) 0.015 ms/op
Iteration   3: 3.870 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.849 ±(99.9%) 0.840 ms/op [Average]
  (min, avg, max) = (3.797, 3.849, 3.881), stdev = 0.046
  CI (99.9%): [3.010, 4.689] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.007 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.455 ms/op
                 createUser·p0.9999: 11.626 ms/op
                 createUser·p1.00:   11.895 ms/op

Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.848 ms/op
                 createUser·p0.9999: 20.382 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.519 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.086 ms/op
                 createUser·p0.9999: 23.270 ms/op
                 createUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323298
  mean =      2.970 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23986 
    [ 2.500,  5.000) = 297949 
    [ 5.000,  7.500) = 1050 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.086 ms/op
     p(99.9900) =     22.236 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.005 ms/op
Iteration   1: 2.871 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.005 ms/op
                 existUser·p0.9999: 15.151 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   2: 2.885 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.311 ms/op
                 existUser·p0.999:  5.792 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   3: 2.811 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.178 ms/op
                 existUser·p0.9999: 14.494 ms/op
                 existUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336078
  mean =      2.855 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3688 
    [ 1.250,  2.500) = 40227 
    [ 2.500,  3.750) = 283827 
    [ 3.750,  5.000) = 7458 
    [ 5.000,  6.250) = 574 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 80 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.029 ms/op
     p(99.9900) =     15.738 ms/op
     p(99.9990) =     19.604 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  6.562 ms/op
                 getUser·p0.9999: 12.738 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.415 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.580 ms/op
                 getUser·p0.9999: 22.080 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   3: 2.952 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.318 ms/op
                 getUser·p0.95:   3.465 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  7.327 ms/op
                 getUser·p0.9999: 15.389 ms/op
                 getUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321707
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28138 
    [ 2.500,  5.000) = 292453 
    [ 5.000,  7.500) = 889 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     19.856 ms/op
     p(99.9990) =     22.687 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 5.205 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.010 ms/op
Iteration   1: 3.837 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.053 ms/op
                 listUser·p0.9999: 15.144 ms/op
                 listUser·p1.00:   15.581 ms/op

Iteration   2: 3.893 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 15.653 ms/op
                 listUser·p1.00:   15.942 ms/op

Iteration   3: 3.823 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.515 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.560 ms/op
                 listUser·p0.9999: 22.151 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249086
  mean =      3.851 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6441 
    [ 2.500,  5.000) = 220959 
    [ 5.000,  7.500) = 20504 
    [ 7.500, 10.000) = 694 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     14.072 ms/op
     p(99.9900) =     21.368 ms/op
     p(99.9990) =     22.430 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.771 ± 1.944  ops/ms
ClientGrpc.existUser                       thrpt       3  11.293 ± 3.407  ops/ms
ClientGrpc.getUser                         thrpt       3  10.791 ± 1.713  ops/ms
ClientGrpc.listUser                        thrpt       3   8.251 ± 1.983  ops/ms
ClientGrpc.createUser                       avgt       3   3.003 ± 0.712   ms/op
ClientGrpc.existUser                        avgt       3   2.901 ± 0.553   ms/op
ClientGrpc.getUser                          avgt       3   2.962 ± 0.493   ms/op
ClientGrpc.listUser                         avgt       3   3.849 ± 0.840   ms/op
ClientGrpc.createUser                     sample  323298   2.970 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.519           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.396           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.086           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.236           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.756           ms/op
ClientGrpc.existUser                      sample  336078   2.855 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.571           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.289           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.029           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.738           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.661           ms/op
ClientGrpc.getUser                        sample  321707   2.986 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.415           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.816           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.856           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.101           ms/op
ClientGrpc.listUser                       sample  249086   3.851 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.515           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.072           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.368           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.446           ms/op
