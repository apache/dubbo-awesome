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
# Warmup Iteration   1: 4.136 ops/ms
# Warmup Iteration   2: 8.826 ops/ms
# Warmup Iteration   3: 9.692 ops/ms
Iteration   1: 9.991 ops/ms
Iteration   2: 10.162 ops/ms
Iteration   3: 10.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.083 ±(99.9%) 1.572 ops/ms [Average]
  (min, avg, max) = (9.991, 10.083, 10.162), stdev = 0.086
  CI (99.9%): [8.511, 11.655] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.501 ops/ms
# Warmup Iteration   2: 10.289 ops/ms
# Warmup Iteration   3: 10.705 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.692 ops/ms
Iteration   3: 10.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.647 ±(99.9%) 1.140 ops/ms [Average]
  (min, avg, max) = (10.575, 10.647, 10.692), stdev = 0.063
  CI (99.9%): [9.506, 11.787] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.397 ops/ms
# Warmup Iteration   2: 9.944 ops/ms
# Warmup Iteration   3: 10.081 ops/ms
Iteration   1: 10.120 ops/ms
Iteration   2: 10.320 ops/ms
Iteration   3: 10.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.289 ±(99.9%) 2.828 ops/ms [Average]
  (min, avg, max) = (10.120, 10.289, 10.426), stdev = 0.155
  CI (99.9%): [7.460, 13.117] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.748 ops/ms
# Warmup Iteration   2: 8.051 ops/ms
# Warmup Iteration   3: 8.073 ops/ms
Iteration   1: 8.020 ops/ms
Iteration   2: 8.181 ops/ms
Iteration   3: 8.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.117 ±(99.9%) 1.558 ops/ms [Average]
  (min, avg, max) = (8.020, 8.117, 8.181), stdev = 0.085
  CI (99.9%): [6.559, 9.676] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.003 ms/op
Iteration   1: 3.087 ±(99.9%) 0.001 ms/op
Iteration   2: 3.126 ±(99.9%) 0.002 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.103 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (3.087, 3.103, 3.126), stdev = 0.020
  CI (99.9%): [2.735, 3.471] (assumes normal distribution)


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.002 ms/op
Iteration   1: 2.980 ±(99.9%) 0.002 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 3.001 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.000 ±(99.9%) 0.363 ms/op [Average]
  (min, avg, max) = (2.980, 3.000, 3.020), stdev = 0.020
  CI (99.9%): [2.637, 3.364] (assumes normal distribution)


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
# Warmup Iteration   1: 4.126 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.002 ms/op
Iteration   1: 3.093 ±(99.9%) 0.003 ms/op
Iteration   2: 3.121 ±(99.9%) 0.002 ms/op
Iteration   3: 3.189 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.134 ±(99.9%) 0.907 ms/op [Average]
  (min, avg, max) = (3.093, 3.134, 3.189), stdev = 0.050
  CI (99.9%): [2.227, 4.042] (assumes normal distribution)


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.018 ms/op
Iteration   1: 3.925 ±(99.9%) 0.024 ms/op
Iteration   2: 3.904 ±(99.9%) 0.009 ms/op
Iteration   3: 3.847 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.847, 3.892, 3.925), stdev = 0.040
  CI (99.9%): [3.163, 4.620] (assumes normal distribution)


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
Iteration   1: 3.166 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.454 ms/op
                 createUser·p0.9999: 11.876 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   2: 3.111 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  6.975 ms/op
                 createUser·p0.9999: 14.409 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 21.383 ms/op
                 createUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308421
  mean =      3.114 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6390 
    [ 2.500,  5.000) = 300385 
    [ 5.000,  7.500) = 1176 
    [ 7.500, 10.000) = 220 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.974 ms/op
     p(99.9900) =     20.828 ms/op
     p(99.9990) =     22.962 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  8.241 ms/op
                 existUser·p0.9999: 9.726 ms/op
                 existUser·p1.00:   11.010 ms/op

Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.249 ms/op
                 existUser·p0.999:  11.254 ms/op
                 existUser·p0.9999: 12.403 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  9.224 ms/op
                 existUser·p0.9999: 14.330 ms/op
                 existUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314001
  mean =      3.057 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 727 
    [ 1.250,  2.500) = 16151 
    [ 2.500,  3.750) = 278676 
    [ 3.750,  5.000) = 16684 
    [ 5.000,  6.250) = 763 
    [ 6.250,  7.500) = 326 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 208 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     14.849 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.146 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  12.014 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   2: 3.170 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  9.434 ms/op
                 getUser·p0.9999: 19.425 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   3: 3.132 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.508 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.693 ms/op
                 getUser·p0.9999: 20.303 ms/op
                 getUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304738
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5187 
    [ 2.500,  5.000) = 297861 
    [ 5.000,  7.500) = 1186 
    [ 7.500, 10.000) = 239 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.069 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 5.189 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.008 ms/op
Iteration   1: 4.017 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  11.989 ms/op
                 listUser·p0.9999: 13.878 ms/op
                 listUser·p1.00:   14.385 ms/op

Iteration   2: 3.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.076 ms/op
                 listUser·p0.9999: 14.729 ms/op
                 listUser·p1.00:   15.974 ms/op

Iteration   3: 3.869 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  14.505 ms/op
                 listUser·p0.9999: 18.964 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242234
  mean =      3.961 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 2170 
    [ 2.500,  3.750) = 85321 
    [ 3.750,  5.000) = 141407 
    [ 5.000,  6.250) = 8174 
    [ 6.250,  7.500) = 4123 
    [ 7.500,  8.750) = 458 
    [ 8.750, 10.000) = 156 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 151 
    [13.750, 15.000) = 92 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     16.919 ms/op
     p(99.9990) =     19.386 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.083 ± 1.572  ops/ms
ClientGrpc.existUser                       thrpt       3  10.647 ± 1.140  ops/ms
ClientGrpc.getUser                         thrpt       3  10.289 ± 2.828  ops/ms
ClientGrpc.listUser                        thrpt       3   8.117 ± 1.558  ops/ms
ClientGrpc.createUser                       avgt       3   3.103 ± 0.368   ms/op
ClientGrpc.existUser                        avgt       3   3.000 ± 0.363   ms/op
ClientGrpc.getUser                          avgt       3   3.134 ± 0.907   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 0.729   ms/op
ClientGrpc.createUser                     sample  308421   3.114 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.741           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.974           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.828           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.495           ms/op
ClientGrpc.existUser                      sample  314001   3.057 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.563           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.257           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.008           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.139           ms/op
ClientGrpc.getUser                        sample  304738   3.149 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.508           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.069           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.661           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.873           ms/op
ClientGrpc.listUser                       sample  242234   3.961 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.231           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.399           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.074           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.919           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.497           ms/op
