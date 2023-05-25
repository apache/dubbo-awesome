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
# Warmup Iteration   1: 4.029 ops/ms
# Warmup Iteration   2: 8.756 ops/ms
# Warmup Iteration   3: 10.022 ops/ms
Iteration   1: 10.361 ops/ms
Iteration   2: 10.481 ops/ms
Iteration   3: 10.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.472 ±(99.9%) 1.953 ops/ms [Average]
  (min, avg, max) = (10.361, 10.472, 10.574), stdev = 0.107
  CI (99.9%): [8.519, 12.425] (assumes normal distribution)


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
# Warmup Iteration   1: 7.722 ops/ms
# Warmup Iteration   2: 10.756 ops/ms
# Warmup Iteration   3: 10.861 ops/ms
Iteration   1: 10.927 ops/ms
Iteration   2: 10.876 ops/ms
Iteration   3: 11.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.935 ±(99.9%) 1.172 ops/ms [Average]
  (min, avg, max) = (10.876, 10.935, 11.003), stdev = 0.064
  CI (99.9%): [9.764, 12.107] (assumes normal distribution)


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
# Warmup Iteration   1: 6.975 ops/ms
# Warmup Iteration   2: 9.938 ops/ms
# Warmup Iteration   3: 10.431 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.436 ops/ms
Iteration   3: 10.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.511 ±(99.9%) 1.238 ops/ms [Average]
  (min, avg, max) = (10.436, 10.511, 10.567), stdev = 0.068
  CI (99.9%): [9.273, 11.749] (assumes normal distribution)


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
# Warmup Iteration   1: 5.600 ops/ms
# Warmup Iteration   2: 7.635 ops/ms
# Warmup Iteration   3: 8.057 ops/ms
Iteration   1: 8.019 ops/ms
Iteration   2: 8.008 ops/ms
Iteration   3: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.020 ±(99.9%) 0.228 ops/ms [Average]
  (min, avg, max) = (8.008, 8.020, 8.033), stdev = 0.012
  CI (99.9%): [7.792, 8.247] (assumes normal distribution)


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.002 ms/op
Iteration   2: 3.134 ±(99.9%) 0.003 ms/op
Iteration   3: 3.095 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.104 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.085, 3.104, 3.134), stdev = 0.026
  CI (99.9%): [2.632, 3.577] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
Iteration   1: 2.929 ±(99.9%) 0.003 ms/op
Iteration   2: 2.934 ±(99.9%) 0.004 ms/op
Iteration   3: 2.973 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.945 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (2.929, 2.945, 2.973), stdev = 0.024
  CI (99.9%): [2.510, 3.381] (assumes normal distribution)


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.004 ms/op
Iteration   1: 3.011 ±(99.9%) 0.002 ms/op
Iteration   2: 3.024 ±(99.9%) 0.002 ms/op
Iteration   3: 3.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.014 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (3.005, 3.014, 3.024), stdev = 0.010
  CI (99.9%): [2.833, 3.194] (assumes normal distribution)


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
# Warmup Iteration   1: 5.048 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.357 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.011 ms/op
Iteration   1: 3.938 ±(99.9%) 0.013 ms/op
Iteration   2: 3.985 ±(99.9%) 0.011 ms/op
Iteration   3: 3.892 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.938 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (3.892, 3.938, 3.985), stdev = 0.047
  CI (99.9%): [3.087, 4.790] (assumes normal distribution)


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
# Warmup Iteration   1: 4.357 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  9.158 ms/op
                 createUser·p0.9999: 15.255 ms/op
                 createUser·p1.00:   15.827 ms/op

Iteration   2: 3.111 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.773 ms/op
                 createUser·p0.999:  13.489 ms/op
                 createUser·p0.9999: 25.826 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 18.162 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310235
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14101 
    [ 2.500,  5.000) = 293521 
    [ 5.000,  7.500) = 2038 
    [ 7.500, 10.000) = 224 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =     10.351 ms/op
     p(99.9900) =     23.788 ms/op
     p(99.9990) =     26.240 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  8.171 ms/op
                 existUser·p0.9999: 12.701 ms/op
                 existUser·p1.00:   12.861 ms/op

Iteration   2: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.442 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  7.700 ms/op
                 existUser·p0.9999: 14.239 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.389 ms/op
                 existUser·p0.9999: 18.055 ms/op
                 existUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327963
  mean =      2.927 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 792 
    [ 1.250,  2.500) = 36509 
    [ 2.500,  3.750) = 276425 
    [ 3.750,  5.000) = 12687 
    [ 5.000,  6.250) = 827 
    [ 6.250,  7.500) = 363 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.660 ms/op
     p(99.9900) =     17.499 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.549 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.776 ms/op
                 getUser·p0.999:  8.684 ms/op
                 getUser·p0.9999: 16.630 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.739 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.717 ms/op
                 getUser·p0.9999: 23.220 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318156
  mean =      3.017 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19503 
    [ 2.500,  5.000) = 296818 
    [ 5.000,  7.500) = 1413 
    [ 7.500, 10.000) = 220 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.847 ms/op
     p(99.9900) =     22.613 ms/op
     p(99.9990) =     24.093 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.012 ms/op
Iteration   1: 4.061 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.520 ms/op
                 listUser·p0.9999: 15.817 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 3.970 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  16.024 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 3.957 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  20.450 ms/op
                 listUser·p0.9999: 26.509 ms/op
                 listUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240369
  mean =      3.995 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2421 
    [ 2.500,  5.000) = 215576 
    [ 5.000,  7.500) = 20867 
    [ 7.500, 10.000) = 1046 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.792 ms/op
     p(99.9900) =     25.491 ms/op
     p(99.9990) =     26.666 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.472 ± 1.953  ops/ms
ClientGrpc.existUser                       thrpt       3  10.935 ± 1.172  ops/ms
ClientGrpc.getUser                         thrpt       3  10.511 ± 1.238  ops/ms
ClientGrpc.listUser                        thrpt       3   8.020 ± 0.228  ops/ms
ClientGrpc.createUser                       avgt       3   3.104 ± 0.472   ms/op
ClientGrpc.existUser                        avgt       3   2.945 ± 0.436   ms/op
ClientGrpc.getUser                          avgt       3   3.014 ± 0.180   ms/op
ClientGrpc.listUser                         avgt       3   3.938 ± 0.851   ms/op
ClientGrpc.createUser                     sample  310235   3.093 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.637           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.866           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.351           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.788           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.477           ms/op
ClientGrpc.existUser                      sample  327963   2.927 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.442           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.660           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.499           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.153           ms/op
ClientGrpc.getUser                        sample  318156   3.017 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.549           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.847           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.613           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.281           ms/op
ClientGrpc.listUser                       sample  240369   3.995 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.732           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.792           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.491           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.213           ms/op
