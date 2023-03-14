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
# Warmup Iteration   1: 4.299 ops/ms
# Warmup Iteration   2: 9.080 ops/ms
# Warmup Iteration   3: 10.213 ops/ms
Iteration   1: 10.536 ops/ms
Iteration   2: 10.703 ops/ms
Iteration   3: 10.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.596 ±(99.9%) 1.708 ops/ms [Average]
  (min, avg, max) = (10.536, 10.596, 10.703), stdev = 0.094
  CI (99.9%): [8.887, 12.304] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.319 ops/ms
# Warmup Iteration   2: 10.685 ops/ms
# Warmup Iteration   3: 11.085 ops/ms
Iteration   1: 11.064 ops/ms
Iteration   2: 11.050 ops/ms
Iteration   3: 11.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.056 ±(99.9%) 0.123 ops/ms [Average]
  (min, avg, max) = (11.050, 11.056, 11.064), stdev = 0.007
  CI (99.9%): [10.933, 11.179] (assumes normal distribution)


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
# Warmup Iteration   1: 6.831 ops/ms
# Warmup Iteration   2: 10.517 ops/ms
# Warmup Iteration   3: 10.791 ops/ms
Iteration   1: 10.744 ops/ms
Iteration   2: 10.797 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.690 ±(99.9%) 2.573 ops/ms [Average]
  (min, avg, max) = (10.530, 10.690, 10.797), stdev = 0.141
  CI (99.9%): [8.117, 13.264] (assumes normal distribution)


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
# Warmup Iteration   1: 5.641 ops/ms
# Warmup Iteration   2: 7.662 ops/ms
# Warmup Iteration   3: 7.996 ops/ms
Iteration   1: 8.185 ops/ms
Iteration   2: 8.147 ops/ms
Iteration   3: 8.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.159 ±(99.9%) 0.404 ops/ms [Average]
  (min, avg, max) = (8.146, 8.159, 8.185), stdev = 0.022
  CI (99.9%): [7.755, 8.564] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.003 ms/op
Iteration   1: 2.996 ±(99.9%) 0.003 ms/op
Iteration   2: 2.919 ±(99.9%) 0.003 ms/op
Iteration   3: 2.907 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.941 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (2.907, 2.941, 2.996), stdev = 0.048
  CI (99.9%): [2.065, 3.816] (assumes normal distribution)


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.920 ±(99.9%) 0.002 ms/op
Iteration   1: 2.826 ±(99.9%) 0.001 ms/op
Iteration   2: 2.886 ±(99.9%) 0.002 ms/op
Iteration   3: 2.878 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.863 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (2.826, 2.863, 2.886), stdev = 0.033
  CI (99.9%): [2.268, 3.459] (assumes normal distribution)


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.025 ms/op
Iteration   1: 3.003 ±(99.9%) 0.002 ms/op
Iteration   2: 2.968 ±(99.9%) 0.002 ms/op
Iteration   3: 2.927 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.966 ±(99.9%) 0.700 ms/op [Average]
  (min, avg, max) = (2.927, 2.966, 3.003), stdev = 0.038
  CI (99.9%): [2.266, 3.666] (assumes normal distribution)


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
# Warmup Iteration   1: 5.180 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.018 ms/op
Iteration   1: 3.908 ±(99.9%) 0.012 ms/op
Iteration   2: 3.897 ±(99.9%) 0.010 ms/op
Iteration   3: 3.904 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.903 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (3.897, 3.903, 3.908), stdev = 0.005
  CI (99.9%): [3.805, 4.001] (assumes normal distribution)


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.573 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  11.272 ms/op
                 createUser·p0.9999: 19.071 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.781 ms/op
                 createUser·p0.9999: 14.074 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.455 ms/op
                 createUser·p0.9999: 20.200 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317352
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30530 
    [ 2.500,  5.000) = 285377 
    [ 5.000,  7.500) = 1048 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =     10.600 ms/op
     p(99.9900) =     19.459 ms/op
     p(99.9990) =     20.474 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.005 ms/op
Iteration   1: 2.891 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  5.950 ms/op
                 existUser·p0.9999: 12.973 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   2: 2.875 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.435 ms/op
                 existUser·p0.999:  7.471 ms/op
                 existUser·p0.9999: 16.504 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 2.856 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  6.431 ms/op
                 existUser·p0.9999: 24.406 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333871
  mean =      2.874 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48701 
    [ 2.500,  5.000) = 284294 
    [ 5.000,  7.500) = 669 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.431 ms/op
     p(99.9900) =     17.285 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
Iteration   1: 3.053 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  7.733 ms/op
                 getUser·p0.9999: 25.036 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.564 ms/op
                 getUser·p0.9999: 14.434 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.895 ms/op
                 getUser·p0.9999: 18.197 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317683
  mean =      3.020 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25810 
    [ 2.500,  5.000) = 290402 
    [ 5.000,  7.500) = 1122 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.711 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 5.172 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.011 ms/op
Iteration   1: 3.892 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.891 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   2: 3.875 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.684 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 24.838 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   3: 3.846 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247901
  mean =      3.871 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2641 
    [ 2.500,  5.000) = 227631 
    [ 5.000,  7.500) = 16674 
    [ 7.500, 10.000) = 540 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     14.616 ms/op
     p(99.9900) =     24.452 ms/op
     p(99.9990) =     26.365 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.596 ± 1.708  ops/ms
ClientGrpc.existUser                       thrpt       3  11.056 ± 0.123  ops/ms
ClientGrpc.getUser                         thrpt       3  10.690 ± 2.573  ops/ms
ClientGrpc.listUser                        thrpt       3   8.159 ± 0.404  ops/ms
ClientGrpc.createUser                       avgt       3   2.941 ± 0.875   ms/op
ClientGrpc.existUser                        avgt       3   2.863 ± 0.596   ms/op
ClientGrpc.getUser                          avgt       3   2.966 ± 0.700   ms/op
ClientGrpc.listUser                         avgt       3   3.903 ± 0.098   ms/op
ClientGrpc.createUser                     sample  317352   3.023 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.573           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.600           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.459           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.513           ms/op
ClientGrpc.existUser                      sample  333871   2.874 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.690           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.431           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.285           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.904           ms/op
ClientGrpc.getUser                        sample  317683   3.020 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.859           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.711           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.150           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.395           ms/op
ClientGrpc.listUser                       sample  247901   3.871 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.100           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.678           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.616           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.452           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.575           ms/op
