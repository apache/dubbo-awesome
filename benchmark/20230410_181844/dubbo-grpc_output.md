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
# Warmup Iteration   1: 4.746 ops/ms
# Warmup Iteration   2: 9.626 ops/ms
# Warmup Iteration   3: 10.423 ops/ms
Iteration   1: 10.686 ops/ms
Iteration   2: 10.753 ops/ms
Iteration   3: 10.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.742 ±(99.9%) 0.935 ops/ms [Average]
  (min, avg, max) = (10.686, 10.742, 10.786), stdev = 0.051
  CI (99.9%): [9.807, 11.677] (assumes normal distribution)


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
# Warmup Iteration   1: 8.093 ops/ms
# Warmup Iteration   2: 11.310 ops/ms
# Warmup Iteration   3: 11.329 ops/ms
Iteration   1: 11.324 ops/ms
Iteration   2: 11.338 ops/ms
Iteration   3: 11.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.318 ±(99.9%) 0.416 ops/ms [Average]
  (min, avg, max) = (11.293, 11.318, 11.338), stdev = 0.023
  CI (99.9%): [10.903, 11.734] (assumes normal distribution)


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
# Warmup Iteration   1: 8.168 ops/ms
# Warmup Iteration   2: 10.348 ops/ms
# Warmup Iteration   3: 10.754 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.916 ops/ms
Iteration   3: 10.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.788 ±(99.9%) 2.458 ops/ms [Average]
  (min, avg, max) = (10.647, 10.788, 10.916), stdev = 0.135
  CI (99.9%): [8.330, 13.246] (assumes normal distribution)


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
# Warmup Iteration   1: 6.172 ops/ms
# Warmup Iteration   2: 7.988 ops/ms
# Warmup Iteration   3: 8.248 ops/ms
Iteration   1: 8.387 ops/ms
Iteration   2: 8.315 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.353 ±(99.9%) 0.655 ops/ms [Average]
  (min, avg, max) = (8.315, 8.353, 8.387), stdev = 0.036
  CI (99.9%): [7.698, 9.009] (assumes normal distribution)


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.003 ms/op
Iteration   1: 2.925 ±(99.9%) 0.003 ms/op
Iteration   2: 2.923 ±(99.9%) 0.004 ms/op
Iteration   3: 2.953 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.933 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.923, 2.933, 2.953), stdev = 0.017
  CI (99.9%): [2.628, 3.238] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.661 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.867 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.835 ±(99.9%) 0.003 ms/op
Iteration   1: 2.782 ±(99.9%) 0.004 ms/op
Iteration   2: 2.842 ±(99.9%) 0.002 ms/op
Iteration   3: 2.820 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.815 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (2.782, 2.815, 2.842), stdev = 0.030
  CI (99.9%): [2.265, 3.364] (assumes normal distribution)


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.002 ms/op
Iteration   1: 2.950 ±(99.9%) 0.003 ms/op
Iteration   2: 2.943 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.953 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (2.943, 2.953, 2.965), stdev = 0.011
  CI (99.9%): [2.749, 3.156] (assumes normal distribution)


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
# Warmup Iteration   1: 5.240 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.013 ms/op
Iteration   1: 3.801 ±(99.9%) 0.020 ms/op
Iteration   2: 3.752 ±(99.9%) 0.008 ms/op
Iteration   3: 3.855 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.803 ±(99.9%) 0.940 ms/op [Average]
  (min, avg, max) = (3.752, 3.803, 3.855), stdev = 0.052
  CI (99.9%): [2.862, 4.743] (assumes normal distribution)


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
Iteration   1: 2.942 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.240 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.393 ms/op
                 createUser·p0.9999: 17.957 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   2: 2.927 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.182 ms/op
                 createUser·p0.999:  7.311 ms/op
                 createUser·p0.9999: 17.173 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 2.933 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.445 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  8.108 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 327237
  mean =      2.934 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2404 
    [ 1.250,  2.500) = 32813 
    [ 2.500,  3.750) = 278278 
    [ 3.750,  5.000) = 12677 
    [ 5.000,  6.250) = 528 
    [ 6.250,  7.500) = 193 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 54 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.240 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.707 ms/op
     p(99.9900) =     17.474 ms/op
     p(99.9990) =     18.210 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 3.664 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.900 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.795 ±(99.9%) 0.006 ms/op
Iteration   1: 2.824 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   2.789 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.607 ms/op
                 existUser·p0.9999: 18.503 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   2: 2.844 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   4.154 ms/op
                 existUser·p0.999:  7.004 ms/op
                 existUser·p0.9999: 14.024 ms/op
                 existUser·p1.00:   15.565 ms/op

Iteration   3: 2.821 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  8.055 ms/op
                 existUser·p0.9999: 13.844 ms/op
                 existUser·p1.00:   14.565 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 339200
  mean =      2.830 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58328 
    [ 2.500,  5.000) = 279550 
    [ 5.000,  7.500) = 1001 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.402 ms/op
     p(99.9900) =     14.947 ms/op
     p(99.9990) =     20.603 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.932 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.704 ms/op
                 getUser·p0.9999: 14.976 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   2: 3.006 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.232 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.092 ms/op
                 getUser·p0.999:  6.623 ms/op
                 getUser·p0.9999: 12.889 ms/op
                 getUser·p1.00:   13.025 ms/op

Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.211 ms/op
                 getUser·p0.9999: 15.112 ms/op
                 getUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324431
  mean =      2.961 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1567 
    [ 1.250,  2.500) = 27177 
    [ 2.500,  3.750) = 284263 
    [ 3.750,  5.000) = 10355 
    [ 5.000,  6.250) = 615 
    [ 6.250,  7.500) = 239 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.232 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      6.861 ms/op
     p(99.9900) =     14.886 ms/op
     p(99.9990) =     15.381 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 3.893 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.922 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.010 ms/op
Iteration   1: 3.829 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  12.738 ms/op
                 listUser·p0.9999: 19.485 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 3.870 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.292 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  15.294 ms/op
                 listUser·p0.9999: 18.452 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 3.824 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.796 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  21.398 ms/op
                 listUser·p0.9999: 23.614 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249974
  mean =      3.841 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4993 
    [ 2.500,  5.000) = 226562 
    [ 5.000,  7.500) = 17210 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.292 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     16.270 ms/op
     p(99.9900) =     21.989 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.742 ± 0.935  ops/ms
ClientGrpc.existUser                       thrpt       3  11.318 ± 0.416  ops/ms
ClientGrpc.getUser                         thrpt       3  10.788 ± 2.458  ops/ms
ClientGrpc.listUser                        thrpt       3   8.353 ± 0.655  ops/ms
ClientGrpc.createUser                       avgt       3   2.933 ± 0.305   ms/op
ClientGrpc.existUser                        avgt       3   2.815 ± 0.549   ms/op
ClientGrpc.getUser                          avgt       3   2.953 ± 0.204   ms/op
ClientGrpc.listUser                         avgt       3   3.803 ± 0.940   ms/op
ClientGrpc.createUser                     sample  327237   2.934 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.240           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.929           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.707           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.474           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.285           ms/op
ClientGrpc.existUser                      sample  339200   2.830 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.440           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.814           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.402           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.947           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.939           ms/op
ClientGrpc.getUser                        sample  324431   2.961 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.232           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.957           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.190           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.861           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.886           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.483           ms/op
ClientGrpc.listUser                       sample  249974   3.841 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.292           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.627           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.270           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.989           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.773           ms/op
