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
# Warmup Iteration   1: 3.597 ops/ms
# Warmup Iteration   2: 8.678 ops/ms
# Warmup Iteration   3: 9.971 ops/ms
Iteration   1: 10.291 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.457 ±(99.9%) 3.377 ops/ms [Average]
  (min, avg, max) = (10.291, 10.457, 10.657), stdev = 0.185
  CI (99.9%): [7.079, 13.834] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.107 ops/ms
# Warmup Iteration   2: 10.211 ops/ms
# Warmup Iteration   3: 10.771 ops/ms
Iteration   1: 11.002 ops/ms
Iteration   2: 10.883 ops/ms
Iteration   3: 10.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.891 ±(99.9%) 1.951 ops/ms [Average]
  (min, avg, max) = (10.789, 10.891, 11.002), stdev = 0.107
  CI (99.9%): [8.941, 12.842] (assumes normal distribution)


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
# Warmup Iteration   1: 6.724 ops/ms
# Warmup Iteration   2: 9.938 ops/ms
# Warmup Iteration   3: 9.941 ops/ms
Iteration   1: 10.189 ops/ms
Iteration   2: 10.294 ops/ms
Iteration   3: 10.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.232 ±(99.9%) 0.996 ops/ms [Average]
  (min, avg, max) = (10.189, 10.232, 10.294), stdev = 0.055
  CI (99.9%): [9.237, 11.228] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.051 ops/ms
# Warmup Iteration   2: 7.490 ops/ms
# Warmup Iteration   3: 7.731 ops/ms
Iteration   1: 7.906 ops/ms
Iteration   2: 7.920 ops/ms
Iteration   3: 7.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.895 ±(99.9%) 0.593 ops/ms [Average]
  (min, avg, max) = (7.858, 7.895, 7.920), stdev = 0.033
  CI (99.9%): [7.302, 8.488] (assumes normal distribution)


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
# Warmup Iteration   1: 4.417 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.003 ms/op
Iteration   1: 3.152 ±(99.9%) 0.002 ms/op
Iteration   2: 3.080 ±(99.9%) 0.002 ms/op
Iteration   3: 3.106 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.113 ±(99.9%) 0.669 ms/op [Average]
  (min, avg, max) = (3.080, 3.113, 3.152), stdev = 0.037
  CI (99.9%): [2.444, 3.782] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.002 ms/op
Iteration   1: 2.999 ±(99.9%) 0.001 ms/op
Iteration   2: 2.892 ±(99.9%) 0.001 ms/op
Iteration   3: 2.958 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.950 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (2.892, 2.950, 2.999), stdev = 0.054
  CI (99.9%): [1.961, 3.938] (assumes normal distribution)


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
# Warmup Iteration   1: 4.516 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.004 ms/op
Iteration   1: 3.143 ±(99.9%) 0.003 ms/op
Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
Iteration   3: 3.093 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.108 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (3.088, 3.108, 3.143), stdev = 0.030
  CI (99.9%): [2.556, 3.660] (assumes normal distribution)


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
# Warmup Iteration   1: 5.927 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.015 ms/op
Iteration   1: 4.077 ±(99.9%) 0.041 ms/op
Iteration   2: 4.027 ±(99.9%) 0.030 ms/op
Iteration   3: 4.096 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.066 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (4.027, 4.066, 4.096), stdev = 0.036
  CI (99.9%): [3.413, 4.720] (assumes normal distribution)


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.006 ms/op
Iteration   1: 3.180 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  7.093 ms/op
                 createUser·p0.9999: 12.008 ms/op
                 createUser·p1.00:   12.173 ms/op

Iteration   2: 3.125 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.356 ms/op
                 createUser·p0.999:  7.791 ms/op
                 createUser·p0.9999: 14.693 ms/op
                 createUser·p1.00:   15.172 ms/op

Iteration   3: 3.174 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.553 ms/op
                 createUser·p0.9999: 16.810 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303635
  mean =      3.160 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 291 
    [ 1.250,  2.500) = 7681 
    [ 2.500,  3.750) = 270462 
    [ 3.750,  5.000) = 23819 
    [ 5.000,  6.250) = 809 
    [ 6.250,  7.500) = 283 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.365 ms/op
     p(99.9900) =     16.499 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.005 ms/op
Iteration   1: 2.995 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  6.162 ms/op
                 existUser·p0.9999: 11.829 ms/op
                 existUser·p1.00:   12.206 ms/op

Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.373 ms/op
                 existUser·p0.9999: 14.483 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   3: 2.916 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.363 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  7.808 ms/op
                 existUser·p0.9999: 16.515 ms/op
                 existUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322605
  mean =      2.976 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 623 
    [ 1.250,  2.500) = 18261 
    [ 2.500,  3.750) = 295210 
    [ 3.750,  5.000) = 7668 
    [ 5.000,  6.250) = 436 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =      6.775 ms/op
     p(99.9900) =     16.167 ms/op
     p(99.9990) =     16.599 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 4.243 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.006 ms/op
Iteration   1: 3.125 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.146 ms/op
                 getUser·p0.9999: 11.868 ms/op
                 getUser·p1.00:   15.630 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.827 ms/op
                 getUser·p0.9999: 14.570 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  7.233 ms/op
                 getUser·p0.9999: 23.137 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308922
  mean =      3.107 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12821 
    [ 2.500,  5.000) = 294309 
    [ 5.000,  7.500) = 1527 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.258 ms/op
     p(99.9900) =     21.372 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 5.875 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.011 ms/op
Iteration   1: 4.065 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.340 ms/op
                 listUser·p0.9999: 22.197 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 4.054 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.730 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 17.544 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 4.080 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.860 ms/op
                 listUser·p0.9999: 28.312 ms/op
                 listUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236185
  mean =      4.066 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2204 
    [ 2.500,  5.000) = 209537 
    [ 5.000,  7.500) = 23116 
    [ 7.500, 10.000) = 864 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.447 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.457 ± 3.377  ops/ms
ClientGrpc.existUser                       thrpt       3  10.891 ± 1.951  ops/ms
ClientGrpc.getUser                         thrpt       3  10.232 ± 0.996  ops/ms
ClientGrpc.listUser                        thrpt       3   7.895 ± 0.593  ops/ms
ClientGrpc.createUser                       avgt       3   3.113 ± 0.669   ms/op
ClientGrpc.existUser                        avgt       3   2.950 ± 0.988   ms/op
ClientGrpc.getUser                          avgt       3   3.108 ± 0.552   ms/op
ClientGrpc.listUser                         avgt       3   4.066 ± 0.653   ms/op
ClientGrpc.createUser                     sample  303635   3.160 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.790           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.365           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.499           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.974           ms/op
ClientGrpc.existUser                      sample  322605   2.976 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.735           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.775           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.167           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.712           ms/op
ClientGrpc.getUser                        sample  308922   3.107 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.575           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.258           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.372           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.429           ms/op
ClientGrpc.listUser                       sample  236185   4.066 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.730           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.447           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.263           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.769           ms/op
