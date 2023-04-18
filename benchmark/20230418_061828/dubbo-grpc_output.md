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
# Warmup Iteration   1: 3.117 ops/ms
# Warmup Iteration   2: 7.751 ops/ms
# Warmup Iteration   3: 9.582 ops/ms
Iteration   1: 9.899 ops/ms
Iteration   2: 10.234 ops/ms
Iteration   3: 10.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.077 ±(99.9%) 3.074 ops/ms [Average]
  (min, avg, max) = (9.899, 10.077, 10.234), stdev = 0.168
  CI (99.9%): [7.003, 13.150] (assumes normal distribution)


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
# Warmup Iteration   1: 6.848 ops/ms
# Warmup Iteration   2: 10.094 ops/ms
# Warmup Iteration   3: 10.808 ops/ms
Iteration   1: 10.842 ops/ms
Iteration   2: 10.710 ops/ms
Iteration   3: 10.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.837 ±(99.9%) 2.288 ops/ms [Average]
  (min, avg, max) = (10.710, 10.837, 10.960), stdev = 0.125
  CI (99.9%): [8.549, 13.125] (assumes normal distribution)


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
# Warmup Iteration   1: 6.612 ops/ms
# Warmup Iteration   2: 9.829 ops/ms
# Warmup Iteration   3: 10.364 ops/ms
Iteration   1: 10.190 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.359 ±(99.9%) 3.240 ops/ms [Average]
  (min, avg, max) = (10.190, 10.359, 10.544), stdev = 0.178
  CI (99.9%): [7.119, 13.598] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.503 ops/ms
# Warmup Iteration   2: 7.138 ops/ms
# Warmup Iteration   3: 7.716 ops/ms
Iteration   1: 7.620 ops/ms
Iteration   2: 7.802 ops/ms
Iteration   3: 8.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.811 ±(99.9%) 3.557 ops/ms [Average]
  (min, avg, max) = (7.620, 7.811, 8.010), stdev = 0.195
  CI (99.9%): [4.253, 11.368] (assumes normal distribution)


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.003 ms/op
Iteration   1: 3.141 ±(99.9%) 0.002 ms/op
Iteration   2: 3.063 ±(99.9%) 0.002 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.095 ±(99.9%) 0.751 ms/op [Average]
  (min, avg, max) = (3.063, 3.095, 3.141), stdev = 0.041
  CI (99.9%): [2.344, 3.846] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.279 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 2.952 ±(99.9%) 0.002 ms/op
Iteration   3: 2.912 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.936 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.912, 2.936, 2.952), stdev = 0.021
  CI (99.9%): [2.550, 3.321] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.605 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.002 ms/op
Iteration   1: 3.086 ±(99.9%) 0.002 ms/op
Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
Iteration   3: 3.119 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.098 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (3.086, 3.098, 3.119), stdev = 0.019
  CI (99.9%): [2.757, 3.438] (assumes normal distribution)


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
# Warmup Iteration   1: 5.994 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.322 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.010 ms/op
Iteration   1: 4.085 ±(99.9%) 0.027 ms/op
Iteration   2: 4.008 ±(99.9%) 0.005 ms/op
Iteration   3: 4.148 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.080 ±(99.9%) 1.282 ms/op [Average]
  (min, avg, max) = (4.008, 4.080, 4.148), stdev = 0.070
  CI (99.9%): [2.799, 5.362] (assumes normal distribution)


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
# Warmup Iteration   1: 4.448 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.107 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  13.733 ms/op
                 createUser·p0.9999: 23.036 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.635 ms/op
                 createUser·p0.9999: 16.042 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.795 ms/op
                 createUser·p0.9999: 20.414 ms/op
                 createUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308298
  mean =      3.112 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15160 
    [ 2.500,  5.000) = 291760 
    [ 5.000,  7.500) = 923 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =     10.743 ms/op
     p(99.9900) =     21.403 ms/op
     p(99.9990) =     23.290 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.202 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.005 ms/op
Iteration   1: 2.970 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.295 ms/op
                 existUser·p0.9999: 13.823 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 2.929 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.206 ms/op
                 existUser·p0.9999: 15.500 ms/op
                 existUser·p1.00:   15.860 ms/op

Iteration   3: 2.947 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  10.658 ms/op
                 existUser·p0.9999: 30.971 ms/op
                 existUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325464
  mean =      2.949 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32244 
    [ 2.500,  5.000) = 291970 
    [ 5.000,  7.500) = 956 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.283 ms/op
     p(99.9900) =     22.919 ms/op
     p(99.9990) =     32.866 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 4.843 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  8.781 ms/op
                 getUser·p0.9999: 14.442 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.944 ms/op
                 getUser·p0.9999: 15.340 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  7.171 ms/op
                 getUser·p0.9999: 18.678 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308606
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16032 
    [ 2.500,  5.000) = 290507 
    [ 5.000,  7.500) = 1759 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      7.499 ms/op
     p(99.9900) =     18.252 ms/op
     p(99.9990) =     20.671 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 5.939 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.012 ms/op
Iteration   1: 4.133 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  15.149 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 4.128 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 4.138 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.284 ms/op
                 listUser·p0.999:  19.324 ms/op
                 listUser·p0.9999: 28.180 ms/op
                 listUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232270
  mean =      4.133 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1505 
    [ 2.500,  5.000) = 203653 
    [ 5.000,  7.500) = 25149 
    [ 7.500, 10.000) = 1438 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     16.466 ms/op
     p(99.9900) =     27.714 ms/op
     p(99.9990) =     28.876 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.077 ± 3.074  ops/ms
ClientGrpc.existUser                       thrpt       3  10.837 ± 2.288  ops/ms
ClientGrpc.getUser                         thrpt       3  10.359 ± 3.240  ops/ms
ClientGrpc.listUser                        thrpt       3   7.811 ± 3.557  ops/ms
ClientGrpc.createUser                       avgt       3   3.095 ± 0.751   ms/op
ClientGrpc.existUser                        avgt       3   2.936 ± 0.386   ms/op
ClientGrpc.getUser                          avgt       3   3.098 ± 0.341   ms/op
ClientGrpc.listUser                         avgt       3   4.080 ± 1.282   ms/op
ClientGrpc.createUser                     sample  308298   3.112 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.757           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.743           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.403           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.396           ms/op
ClientGrpc.existUser                      sample  325464   2.949 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.671           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.283           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.919           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.997           ms/op
ClientGrpc.getUser                        sample  308606   3.110 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.642           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.499           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.252           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.808           ms/op
ClientGrpc.listUser                       sample  232270   4.133 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.835           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.944           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.332           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.466           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.714           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.327           ms/op
