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
# Warmup Iteration   1: 4.532 ops/ms
# Warmup Iteration   2: 9.094 ops/ms
# Warmup Iteration   3: 10.612 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.948 ops/ms
Iteration   3: 11.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.904 ±(99.9%) 5.354 ops/ms [Average]
  (min, avg, max) = (10.591, 10.904, 11.173), stdev = 0.293
  CI (99.9%): [5.549, 16.258] (assumes normal distribution)


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
# Warmup Iteration   1: 9.628 ops/ms
# Warmup Iteration   2: 10.868 ops/ms
# Warmup Iteration   3: 11.549 ops/ms
Iteration   1: 11.081 ops/ms
Iteration   2: 11.322 ops/ms
Iteration   3: 11.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.234 ±(99.9%) 2.429 ops/ms [Average]
  (min, avg, max) = (11.081, 11.234, 11.322), stdev = 0.133
  CI (99.9%): [8.805, 13.663] (assumes normal distribution)


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
# Warmup Iteration   1: 7.600 ops/ms
# Warmup Iteration   2: 10.313 ops/ms
# Warmup Iteration   3: 10.699 ops/ms
Iteration   1: 10.767 ops/ms
Iteration   2: 11.009 ops/ms
Iteration   3: 10.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.894 ±(99.9%) 2.210 ops/ms [Average]
  (min, avg, max) = (10.767, 10.894, 11.009), stdev = 0.121
  CI (99.9%): [8.684, 13.104] (assumes normal distribution)


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
# Warmup Iteration   1: 6.226 ops/ms
# Warmup Iteration   2: 8.163 ops/ms
# Warmup Iteration   3: 8.413 ops/ms
Iteration   1: 8.371 ops/ms
Iteration   2: 8.445 ops/ms
Iteration   3: 8.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.435 ±(99.9%) 1.097 ops/ms [Average]
  (min, avg, max) = (8.371, 8.435, 8.490), stdev = 0.060
  CI (99.9%): [7.338, 9.533] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.002 ms/op
Iteration   1: 2.957 ±(99.9%) 0.002 ms/op
Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
Iteration   3: 2.949 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.968 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (2.949, 2.968, 2.998), stdev = 0.026
  CI (99.9%): [2.485, 3.451] (assumes normal distribution)


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.893 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.850 ±(99.9%) 0.002 ms/op
Iteration   1: 2.842 ±(99.9%) 0.003 ms/op
Iteration   2: 2.765 ±(99.9%) 0.003 ms/op
Iteration   3: 2.843 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.817 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (2.765, 2.817, 2.843), stdev = 0.045
  CI (99.9%): [1.996, 3.637] (assumes normal distribution)


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.002 ms/op
Iteration   1: 2.941 ±(99.9%) 0.003 ms/op
Iteration   2: 2.927 ±(99.9%) 0.003 ms/op
Iteration   3: 2.961 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.943 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.927, 2.943, 2.961), stdev = 0.017
  CI (99.9%): [2.628, 3.257] (assumes normal distribution)


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
# Warmup Iteration   1: 5.157 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.015 ms/op
Iteration   1: 3.790 ±(99.9%) 0.014 ms/op
Iteration   2: 3.834 ±(99.9%) 0.016 ms/op
Iteration   3: 3.781 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.802 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.781, 3.802, 3.834), stdev = 0.028
  CI (99.9%): [3.292, 4.311] (assumes normal distribution)


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.007 ms/op
Iteration   1: 2.932 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.501 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  9.648 ms/op
                 createUser·p0.9999: 18.061 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   2: 2.918 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.313 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.032 ms/op
                 createUser·p0.9999: 21.726 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   3: 2.918 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  10.040 ms/op
                 createUser·p0.9999: 16.286 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 328269
  mean =      2.922 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34863 
    [ 2.500,  5.000) = 292267 
    [ 5.000,  7.500) = 756 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.313 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     18.979 ms/op
     p(99.9990) =     22.011 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.914 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.813 ±(99.9%) 0.005 ms/op
Iteration   1: 2.846 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.505 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.390 ms/op
                 existUser·p0.9999: 13.460 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   2: 2.892 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.505 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  7.277 ms/op
                 existUser·p0.9999: 15.105 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 2.792 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   2.785 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  10.262 ms/op
                 existUser·p0.9999: 16.843 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337769
  mean =      2.843 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57220 
    [ 2.500,  5.000) = 279373 
    [ 5.000,  7.500) = 835 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.539 ms/op
     p(99.9900) =     15.195 ms/op
     p(99.9990) =     20.074 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
Iteration   1: 2.880 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.516 ms/op
                 getUser·p0.50:   2.900 ms/op
                 getUser·p0.90:   3.273 ms/op
                 getUser·p0.95:   3.494 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.954 ms/op
                 getUser·p0.9999: 15.742 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   2: 2.976 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  6.191 ms/op
                 getUser·p0.9999: 12.984 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.206 ms/op
                 getUser·p0.9999: 14.327 ms/op
                 getUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 327552
  mean =      2.930 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2471 
    [ 1.250,  2.500) = 29965 
    [ 2.500,  3.750) = 282735 
    [ 3.750,  5.000) = 11149 
    [ 5.000,  6.250) = 872 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.492 ms/op
     p(99.9900) =     15.233 ms/op
     p(99.9990) =     15.933 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 4.340 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.010 ms/op
Iteration   1: 3.823 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.047 ms/op
                 listUser·p0.9999: 19.321 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 3.778 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  14.850 ms/op
                 listUser·p0.9999: 23.252 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 3.804 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 21.554 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252420
  mean =      3.802 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5861 
    [ 2.500,  5.000) = 226999 
    [ 5.000,  7.500) = 18457 
    [ 7.500, 10.000) = 627 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     14.427 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     23.509 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.904 ± 5.354  ops/ms
ClientGrpc.existUser                       thrpt       3  11.234 ± 2.429  ops/ms
ClientGrpc.getUser                         thrpt       3  10.894 ± 2.210  ops/ms
ClientGrpc.listUser                        thrpt       3   8.435 ± 1.097  ops/ms
ClientGrpc.createUser                       avgt       3   2.968 ± 0.483   ms/op
ClientGrpc.existUser                        avgt       3   2.817 ± 0.821   ms/op
ClientGrpc.getUser                          avgt       3   2.943 ± 0.314   ms/op
ClientGrpc.listUser                         avgt       3   3.802 ± 0.509   ms/op
ClientGrpc.createUser                     sample  328269   2.922 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.313           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.912           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.387           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.979           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.118           ms/op
ClientGrpc.existUser                      sample  337769   2.843 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.505           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.539           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.195           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.758           ms/op
ClientGrpc.getUser                        sample  327552   2.930 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.516           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.929           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.416           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.492           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.233           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.007           ms/op
ClientGrpc.listUser                       sample  252420   3.802 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.048           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.658           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.427           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.708           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.593           ms/op
