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
# Warmup Iteration   1: 4.264 ops/ms
# Warmup Iteration   2: 8.682 ops/ms
# Warmup Iteration   3: 9.997 ops/ms
Iteration   1: 10.524 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.520 ±(99.9%) 1.096 ops/ms [Average]
  (min, avg, max) = (10.458, 10.520, 10.578), stdev = 0.060
  CI (99.9%): [9.424, 11.616] (assumes normal distribution)


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
# Warmup Iteration   1: 7.216 ops/ms
# Warmup Iteration   2: 10.539 ops/ms
# Warmup Iteration   3: 10.883 ops/ms
Iteration   1: 11.031 ops/ms
Iteration   2: 10.982 ops/ms
Iteration   3: 11.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.133 ±(99.9%) 4.009 ops/ms [Average]
  (min, avg, max) = (10.982, 11.133, 11.385), stdev = 0.220
  CI (99.9%): [7.124, 15.142] (assumes normal distribution)


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
# Warmup Iteration   1: 6.894 ops/ms
# Warmup Iteration   2: 10.058 ops/ms
# Warmup Iteration   3: 10.289 ops/ms
Iteration   1: 10.484 ops/ms
Iteration   2: 10.289 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.440 ±(99.9%) 2.469 ops/ms [Average]
  (min, avg, max) = (10.289, 10.440, 10.549), stdev = 0.135
  CI (99.9%): [7.971, 12.910] (assumes normal distribution)


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
# Warmup Iteration   1: 6.288 ops/ms
# Warmup Iteration   2: 7.351 ops/ms
# Warmup Iteration   3: 7.843 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 7.774 ops/ms
Iteration   3: 8.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.916 ±(99.9%) 2.294 ops/ms [Average]
  (min, avg, max) = (7.774, 7.916, 8.012), stdev = 0.126
  CI (99.9%): [5.623, 10.210] (assumes normal distribution)


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.002 ms/op
Iteration   1: 3.028 ±(99.9%) 0.001 ms/op
Iteration   2: 3.043 ±(99.9%) 0.004 ms/op
Iteration   3: 3.081 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.051 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.028, 3.051, 3.081), stdev = 0.028
  CI (99.9%): [2.548, 3.553] (assumes normal distribution)


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.002 ms/op
Iteration   1: 2.914 ±(99.9%) 0.003 ms/op
Iteration   2: 2.959 ±(99.9%) 0.003 ms/op
Iteration   3: 2.971 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.948 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (2.914, 2.948, 2.971), stdev = 0.030
  CI (99.9%): [2.402, 3.494] (assumes normal distribution)


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.001 ms/op
Iteration   1: 3.068 ±(99.9%) 0.003 ms/op
Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
Iteration   3: 3.079 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.063 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (3.042, 3.063, 3.079), stdev = 0.019
  CI (99.9%): [2.718, 3.408] (assumes normal distribution)


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
# Warmup Iteration   1: 5.432 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.016 ms/op
Iteration   1: 4.083 ±(99.9%) 0.018 ms/op
Iteration   2: 4.041 ±(99.9%) 0.027 ms/op
Iteration   3: 4.112 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.079 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (4.041, 4.079, 4.112), stdev = 0.036
  CI (99.9%): [3.421, 4.737] (assumes normal distribution)


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
# Warmup Iteration   1: 4.864 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  9.382 ms/op
                 createUser·p0.9999: 11.829 ms/op
                 createUser·p1.00:   12.059 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.681 ms/op
                 createUser·p0.9999: 15.860 ms/op
                 createUser·p1.00:   16.204 ms/op

Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  7.070 ms/op
                 createUser·p0.9999: 23.215 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315195
  mean =      3.046 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23012 
    [ 2.500,  5.000) = 291117 
    [ 5.000,  7.500) = 698 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     22.527 ms/op
     p(99.9990) =     24.444 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.858 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.523 ms/op
                 existUser·p0.9999: 13.339 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   2: 2.840 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  5.835 ms/op
                 existUser·p0.9999: 16.117 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  9.239 ms/op
                 existUser·p0.9999: 19.657 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332551
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46594 
    [ 2.500,  5.000) = 284918 
    [ 5.000,  7.500) = 782 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.512 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     20.633 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.691 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 13.451 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   2: 3.071 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.232 ms/op
                 getUser·p0.9999: 15.385 ms/op
                 getUser·p1.00:   15.876 ms/op

Iteration   3: 3.065 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  5.796 ms/op
                 getUser·p0.9999: 17.105 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312352
  mean =      3.073 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 401 
    [ 1.250,  2.500) = 15975 
    [ 2.500,  3.750) = 277097 
    [ 3.750,  5.000) = 17610 
    [ 5.000,  6.250) = 821 
    [ 6.250,  7.500) = 184 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      6.846 ms/op
     p(99.9900) =     15.471 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.114 ±(99.9%) 0.011 ms/op
Iteration   1: 4.097 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  13.523 ms/op
                 listUser·p0.9999: 17.963 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   2: 4.124 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.341 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  15.774 ms/op
                 listUser·p0.9999: 19.691 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 4.114 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 24.171 ms/op
                 listUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233655
  mean =      4.112 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2181 
    [ 2.500,  5.000) = 204471 
    [ 5.000,  7.500) = 25153 
    [ 7.500, 10.000) = 1279 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.341 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     15.210 ms/op
     p(99.9900) =     23.581 ms/op
     p(99.9990) =     24.477 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.520 ± 1.096  ops/ms
ClientGrpc.existUser                       thrpt       3  11.133 ± 4.009  ops/ms
ClientGrpc.getUser                         thrpt       3  10.440 ± 2.469  ops/ms
ClientGrpc.listUser                        thrpt       3   7.916 ± 2.294  ops/ms
ClientGrpc.createUser                       avgt       3   3.051 ± 0.503   ms/op
ClientGrpc.existUser                        avgt       3   2.948 ± 0.546   ms/op
ClientGrpc.getUser                          avgt       3   3.063 ± 0.345   ms/op
ClientGrpc.listUser                         avgt       3   4.079 ± 0.658   ms/op
ClientGrpc.createUser                     sample  315195   3.046 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.696           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.978           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.527           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.740           ms/op
ClientGrpc.existUser                      sample  332551   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.663           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.512           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.317           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.677           ms/op
ClientGrpc.getUser                        sample  312352   3.073 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.858           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.846           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.471           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.170           ms/op
ClientGrpc.listUser                       sample  233655   4.112 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.341           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.944           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.210           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.581           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.609           ms/op
