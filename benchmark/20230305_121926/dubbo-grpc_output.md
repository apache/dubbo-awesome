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
# Warmup Iteration   1: 4.860 ops/ms
# Warmup Iteration   2: 9.678 ops/ms
# Warmup Iteration   3: 10.871 ops/ms
Iteration   1: 11.043 ops/ms
Iteration   2: 11.004 ops/ms
Iteration   3: 10.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.885 ±(99.9%) 4.397 ops/ms [Average]
  (min, avg, max) = (10.607, 10.885, 11.043), stdev = 0.241
  CI (99.9%): [6.487, 15.282] (assumes normal distribution)


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
# Warmup Iteration   1: 8.169 ops/ms
# Warmup Iteration   2: 11.423 ops/ms
# Warmup Iteration   3: 11.263 ops/ms
Iteration   1: 11.117 ops/ms
Iteration   2: 11.101 ops/ms
Iteration   3: 11.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.237 ±(99.9%) 4.050 ops/ms [Average]
  (min, avg, max) = (11.101, 11.237, 11.493), stdev = 0.222
  CI (99.9%): [7.187, 15.287] (assumes normal distribution)


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
# Warmup Iteration   1: 7.576 ops/ms
# Warmup Iteration   2: 10.416 ops/ms
# Warmup Iteration   3: 11.051 ops/ms
Iteration   1: 10.722 ops/ms
Iteration   2: 11.075 ops/ms
Iteration   3: 10.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.809 ±(99.9%) 4.283 ops/ms [Average]
  (min, avg, max) = (10.631, 10.809, 11.075), stdev = 0.235
  CI (99.9%): [6.526, 15.093] (assumes normal distribution)


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
# Warmup Iteration   1: 6.420 ops/ms
# Warmup Iteration   2: 7.878 ops/ms
# Warmup Iteration   3: 8.327 ops/ms
Iteration   1: 8.312 ops/ms
Iteration   2: 8.389 ops/ms
Iteration   3: 8.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.380 ±(99.9%) 1.168 ops/ms [Average]
  (min, avg, max) = (8.312, 8.380, 8.439), stdev = 0.064
  CI (99.9%): [7.212, 9.548] (assumes normal distribution)


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.003 ms/op
Iteration   1: 2.939 ±(99.9%) 0.002 ms/op
Iteration   2: 2.909 ±(99.9%) 0.003 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.962 ±(99.9%) 1.238 ms/op [Average]
  (min, avg, max) = (2.909, 2.962, 3.038), stdev = 0.068
  CI (99.9%): [1.724, 4.200] (assumes normal distribution)


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
# Warmup Iteration   1: 3.678 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.831 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.003 ms/op
Iteration   1: 2.773 ±(99.9%) 0.003 ms/op
Iteration   2: 2.788 ±(99.9%) 0.002 ms/op
Iteration   3: 2.661 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.741 ±(99.9%) 1.266 ms/op [Average]
  (min, avg, max) = (2.661, 2.741, 2.788), stdev = 0.069
  CI (99.9%): [1.475, 4.007] (assumes normal distribution)


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.004 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 2.925 ±(99.9%) 0.002 ms/op
Iteration   3: 2.957 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.958 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (2.925, 2.958, 2.991), stdev = 0.033
  CI (99.9%): [2.352, 3.563] (assumes normal distribution)


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
# Warmup Iteration   1: 4.434 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.021 ms/op
Iteration   1: 3.932 ±(99.9%) 0.011 ms/op
Iteration   2: 3.846 ±(99.9%) 0.006 ms/op
Iteration   3: 3.853 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.877 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (3.846, 3.877, 3.932), stdev = 0.048
  CI (99.9%): [2.999, 4.755] (assumes normal distribution)


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
Iteration   1: 2.950 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  5.826 ms/op
                 createUser·p0.9999: 13.700 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.725 ms/op
                 createUser·p0.9999: 12.960 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  6.988 ms/op
                 createUser·p0.9999: 15.385 ms/op
                 createUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317842
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1243 
    [ 1.250,  2.500) = 37786 
    [ 2.500,  3.750) = 252460 
    [ 3.750,  5.000) = 25671 
    [ 5.000,  6.250) = 266 
    [ 6.250,  7.500) = 134 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.981 ms/op
     p(99.9900) =     13.943 ms/op
     p(99.9990) =     15.575 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.910 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.006 ms/op
Iteration   1: 2.813 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  6.571 ms/op
                 existUser·p0.9999: 12.970 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   2: 2.798 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  7.291 ms/op
                 existUser·p0.9999: 12.961 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.893 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.549 ms/op
                 existUser·p0.9999: 23.788 ms/op
                 existUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338850
  mean =      2.834 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77416 
    [ 2.500,  5.000) = 260619 
    [ 5.000,  7.500) = 570 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      6.997 ms/op
     p(99.9900) =     13.260 ms/op
     p(99.9990) =     23.928 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  6.352 ms/op
                 getUser·p0.9999: 16.949 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  6.154 ms/op
                 getUser·p0.9999: 12.833 ms/op
                 getUser·p1.00:   13.124 ms/op

Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  7.396 ms/op
                 getUser·p0.9999: 22.532 ms/op
                 getUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318930
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43564 
    [ 2.500,  5.000) = 274691 
    [ 5.000,  7.500) = 456 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      6.358 ms/op
     p(99.9900) =     21.572 ms/op
     p(99.9990) =     23.554 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 4.723 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.010 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.463 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  11.333 ms/op
                 listUser·p0.9999: 13.924 ms/op
                 listUser·p1.00:   15.155 ms/op

Iteration   2: 3.836 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.715 ms/op
                 listUser·p0.9999: 24.051 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   3: 3.674 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.618 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  17.169 ms/op
                 listUser·p0.9999: 22.063 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250713
  mean =      3.827 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6588 
    [ 2.500,  5.000) = 221281 
    [ 5.000,  7.500) = 21914 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.456 ms/op
     p(99.9900) =     22.409 ms/op
     p(99.9990) =     24.443 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.885 ± 4.397  ops/ms
ClientGrpc.existUser                       thrpt       3  11.237 ± 4.050  ops/ms
ClientGrpc.getUser                         thrpt       3  10.809 ± 4.283  ops/ms
ClientGrpc.listUser                        thrpt       3   8.380 ± 1.168  ops/ms
ClientGrpc.createUser                       avgt       3   2.962 ± 1.238   ms/op
ClientGrpc.existUser                        avgt       3   2.741 ± 1.266   ms/op
ClientGrpc.getUser                          avgt       3   2.958 ± 0.606   ms/op
ClientGrpc.listUser                         avgt       3   3.877 ± 0.878   ms/op
ClientGrpc.createUser                     sample  317842   3.018 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.697           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.981           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          13.943           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.630           ms/op
ClientGrpc.existUser                      sample  338850   2.834 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.973           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.997           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.260           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.052           ms/op
ClientGrpc.getUser                        sample  318930   3.010 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.609           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.137           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.358           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.572           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.724           ms/op
ClientGrpc.listUser                       sample  250713   3.827 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.463           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.674           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.456           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.409           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.674           ms/op
