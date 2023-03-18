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
# Warmup Iteration   1: 4.418 ops/ms
# Warmup Iteration   2: 9.277 ops/ms
# Warmup Iteration   3: 10.541 ops/ms
Iteration   1: 10.792 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.750 ±(99.9%) 3.212 ops/ms [Average]
  (min, avg, max) = (10.557, 10.750, 10.901), stdev = 0.176
  CI (99.9%): [7.538, 13.962] (assumes normal distribution)


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
# Warmup Iteration   1: 7.944 ops/ms
# Warmup Iteration   2: 11.016 ops/ms
# Warmup Iteration   3: 11.170 ops/ms
Iteration   1: 11.289 ops/ms
Iteration   2: 11.249 ops/ms
Iteration   3: 11.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.210 ±(99.9%) 1.900 ops/ms [Average]
  (min, avg, max) = (11.092, 11.210, 11.289), stdev = 0.104
  CI (99.9%): [9.310, 13.110] (assumes normal distribution)


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
# Warmup Iteration   1: 8.979 ops/ms
# Warmup Iteration   2: 10.272 ops/ms
# Warmup Iteration   3: 10.738 ops/ms
Iteration   1: 10.718 ops/ms
Iteration   2: 10.829 ops/ms
Iteration   3: 10.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.807 ±(99.9%) 1.455 ops/ms [Average]
  (min, avg, max) = (10.718, 10.807, 10.873), stdev = 0.080
  CI (99.9%): [9.352, 12.261] (assumes normal distribution)


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
# Warmup Iteration   1: 6.120 ops/ms
# Warmup Iteration   2: 8.061 ops/ms
# Warmup Iteration   3: 8.159 ops/ms
Iteration   1: 8.229 ops/ms
Iteration   2: 8.246 ops/ms
Iteration   3: 8.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.331 ±(99.9%) 2.958 ops/ms [Average]
  (min, avg, max) = (8.229, 8.331, 8.518), stdev = 0.162
  CI (99.9%): [5.373, 11.290] (assumes normal distribution)


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.002 ms/op
Iteration   1: 3.007 ±(99.9%) 0.005 ms/op
Iteration   2: 2.960 ±(99.9%) 0.002 ms/op
Iteration   3: 2.960 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.976 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (2.960, 2.976, 3.007), stdev = 0.027
  CI (99.9%): [2.483, 3.469] (assumes normal distribution)


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
# Warmup Iteration   1: 3.645 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.895 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.856 ±(99.9%) 0.002 ms/op
Iteration   1: 2.806 ±(99.9%) 0.003 ms/op
Iteration   2: 2.846 ±(99.9%) 0.003 ms/op
Iteration   3: 2.911 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.854 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (2.806, 2.854, 2.911), stdev = 0.053
  CI (99.9%): [1.888, 3.821] (assumes normal distribution)


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
# Warmup Iteration   1: 3.638 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.003 ms/op
Iteration   1: 2.983 ±(99.9%) 0.003 ms/op
Iteration   2: 2.931 ±(99.9%) 0.002 ms/op
Iteration   3: 2.949 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.954 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (2.931, 2.954, 2.983), stdev = 0.027
  CI (99.9%): [2.466, 3.443] (assumes normal distribution)


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
# Warmup Iteration   1: 4.688 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.028 ms/op
Iteration   1: 3.843 ±(99.9%) 0.013 ms/op
Iteration   2: 3.594 ±(99.9%) 0.008 ms/op
Iteration   3: 3.792 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.743 ±(99.9%) 2.407 ms/op [Average]
  (min, avg, max) = (3.594, 3.743, 3.843), stdev = 0.132
  CI (99.9%): [1.336, 6.150] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.425 ms/op
                 createUser·p0.9999: 12.730 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  6.569 ms/op
                 createUser·p0.9999: 21.902 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.461 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  14.715 ms/op
                 createUser·p0.9999: 27.407 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317237
  mean =      3.029 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28022 
    [ 2.500,  5.000) = 287879 
    [ 5.000,  7.500) = 1059 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      6.904 ms/op
     p(99.9900) =     25.944 ms/op
     p(99.9990) =     27.809 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 3.590 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.953 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.005 ms/op
Iteration   1: 2.887 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.454 ms/op
                 existUser·p0.9999: 11.993 ms/op
                 existUser·p1.00:   12.419 ms/op

Iteration   2: 2.867 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.453 ms/op
                 existUser·p0.9999: 13.989 ms/op
                 existUser·p1.00:   15.942 ms/op

Iteration   3: 2.908 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.516 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.115 ms/op
                 existUser·p0.999:  7.698 ms/op
                 existUser·p0.9999: 15.008 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332514
  mean =      2.887 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2156 
    [ 1.250,  2.500) = 40555 
    [ 2.500,  3.750) = 280810 
    [ 3.750,  5.000) = 8188 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 188 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.660 ms/op
     p(99.9900) =     14.725 ms/op
     p(99.9990) =     15.801 ms/op
     p(99.9999) =     15.942 ms/op
    p(100.0000) =     15.942 ms/op


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 2.920 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.314 ms/op
                 getUser·p0.95:   3.535 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.054 ms/op
                 getUser·p0.9999: 12.405 ms/op
                 getUser·p1.00:   12.894 ms/op

Iteration   2: 2.950 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.005 ms/op
                 getUser·p0.9999: 14.044 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 3.023 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.466 ms/op
                 getUser·p0.9999: 13.807 ms/op
                 getUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323593
  mean =      2.964 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1512 
    [ 1.250,  2.500) = 27959 
    [ 2.500,  3.750) = 281278 
    [ 3.750,  5.000) = 11952 
    [ 5.000,  6.250) = 477 
    [ 6.250,  7.500) = 175 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.937 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     15.016 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 4.543 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.010 ms/op
Iteration   1: 3.813 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.652 ms/op
                 listUser·p0.9999: 14.245 ms/op
                 listUser·p1.00:   14.549 ms/op

Iteration   2: 3.823 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  17.706 ms/op
                 listUser·p0.9999: 24.117 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   3: 3.849 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.090 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250637
  mean =      3.828 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8097 
    [ 2.500,  5.000) = 220957 
    [ 5.000,  7.500) = 20483 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     22.507 ms/op
     p(99.9990) =     25.095 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.750 ± 3.212  ops/ms
ClientGrpc.existUser                       thrpt       3  11.210 ± 1.900  ops/ms
ClientGrpc.getUser                         thrpt       3  10.807 ± 1.455  ops/ms
ClientGrpc.listUser                        thrpt       3   8.331 ± 2.958  ops/ms
ClientGrpc.createUser                       avgt       3   2.976 ± 0.493   ms/op
ClientGrpc.existUser                        avgt       3   2.854 ± 0.966   ms/op
ClientGrpc.getUser                          avgt       3   2.954 ± 0.489   ms/op
ClientGrpc.listUser                         avgt       3   3.743 ± 2.407   ms/op
ClientGrpc.createUser                     sample  317237   3.029 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.461           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.904           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.944           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.820           ms/op
ClientGrpc.existUser                      sample  332514   2.887 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.516           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.660           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.725           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.942           ms/op
ClientGrpc.getUser                        sample  323593   2.964 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.632           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.937           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.730           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.450           ms/op
ClientGrpc.listUser                       sample  250637   3.828 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.905           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.844           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.507           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.756           ms/op
