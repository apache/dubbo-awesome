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
# Warmup Iteration   1: 4.240 ops/ms
# Warmup Iteration   2: 8.853 ops/ms
# Warmup Iteration   3: 9.928 ops/ms
Iteration   1: 10.405 ops/ms
Iteration   2: 10.497 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.453 ±(99.9%) 0.846 ops/ms [Average]
  (min, avg, max) = (10.405, 10.453, 10.497), stdev = 0.046
  CI (99.9%): [9.607, 11.299] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.181 ops/ms
# Warmup Iteration   2: 10.256 ops/ms
# Warmup Iteration   3: 10.773 ops/ms
Iteration   1: 10.860 ops/ms
Iteration   2: 10.745 ops/ms
Iteration   3: 10.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.809 ±(99.9%) 1.073 ops/ms [Average]
  (min, avg, max) = (10.745, 10.809, 10.860), stdev = 0.059
  CI (99.9%): [9.736, 11.883] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.043 ops/ms
# Warmup Iteration   2: 10.116 ops/ms
# Warmup Iteration   3: 10.510 ops/ms
Iteration   1: 10.344 ops/ms
Iteration   2: 10.535 ops/ms
Iteration   3: 10.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.433 ±(99.9%) 1.760 ops/ms [Average]
  (min, avg, max) = (10.344, 10.433, 10.535), stdev = 0.096
  CI (99.9%): [8.673, 12.193] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.746 ops/ms
# Warmup Iteration   2: 7.527 ops/ms
# Warmup Iteration   3: 8.068 ops/ms
Iteration   1: 7.938 ops/ms
Iteration   2: 8.353 ops/ms
Iteration   3: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.193 ±(99.9%) 4.070 ops/ms [Average]
  (min, avg, max) = (7.938, 8.193, 8.353), stdev = 0.223
  CI (99.9%): [4.123, 12.263] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.183 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.003 ms/op
Iteration   1: 3.118 ±(99.9%) 0.002 ms/op
Iteration   2: 3.071 ±(99.9%) 0.002 ms/op
Iteration   3: 3.022 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.070 ±(99.9%) 0.881 ms/op [Average]
  (min, avg, max) = (3.022, 3.070, 3.118), stdev = 0.048
  CI (99.9%): [2.189, 3.951] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.661 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.003 ms/op
Iteration   1: 2.912 ±(99.9%) 0.004 ms/op
Iteration   2: 2.970 ±(99.9%) 0.003 ms/op
Iteration   3: 3.017 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.966 ±(99.9%) 0.965 ms/op [Average]
  (min, avg, max) = (2.912, 2.966, 3.017), stdev = 0.053
  CI (99.9%): [2.001, 3.931] (assumes normal distribution)


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
# Warmup Iteration   1: 4.296 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.003 ms/op
Iteration   1: 3.120 ±(99.9%) 0.003 ms/op
Iteration   2: 3.074 ±(99.9%) 0.002 ms/op
Iteration   3: 3.081 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.092 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (3.074, 3.092, 3.120), stdev = 0.025
  CI (99.9%): [2.637, 3.547] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.316 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.009 ms/op
Iteration   1: 3.938 ±(99.9%) 0.020 ms/op
Iteration   2: 3.848 ±(99.9%) 0.018 ms/op
Iteration   3: 3.998 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.928 ±(99.9%) 1.375 ms/op [Average]
  (min, avg, max) = (3.848, 3.928, 3.998), stdev = 0.075
  CI (99.9%): [2.554, 5.303] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
Iteration   1: 3.095 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.607 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.973 ms/op
                 createUser·p0.999:  7.976 ms/op
                 createUser·p0.9999: 17.880 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.247 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  9.789 ms/op
                 createUser·p0.9999: 13.398 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  11.088 ms/op
                 createUser·p0.9999: 18.389 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309979
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1427 
    [ 1.250,  2.500) = 25838 
    [ 2.500,  3.750) = 253091 
    [ 3.750,  5.000) = 26583 
    [ 5.000,  6.250) = 1608 
    [ 6.250,  7.500) = 705 
    [ 7.500,  8.750) = 344 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.247 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.981 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     18.606 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
Iteration   1: 2.943 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  8.028 ms/op
                 existUser·p0.9999: 17.765 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 2.994 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.923 ms/op
                 existUser·p0.999:  8.280 ms/op
                 existUser·p0.9999: 23.997 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.359 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  8.126 ms/op
                 existUser·p0.9999: 16.403 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323823
  mean =      2.963 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35416 
    [ 2.500,  5.000) = 285811 
    [ 5.000,  7.500) = 2079 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =      8.126 ms/op
     p(99.9900) =     22.884 ms/op
     p(99.9990) =     24.364 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 3.877 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
Iteration   1: 3.087 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.218 ms/op
                 getUser·p0.999:  8.585 ms/op
                 getUser·p0.9999: 13.063 ms/op
                 getUser·p1.00:   13.320 ms/op

Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  9.177 ms/op
                 getUser·p0.9999: 20.036 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  8.329 ms/op
                 getUser·p0.9999: 16.796 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310709
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23245 
    [ 2.500,  5.000) = 284556 
    [ 5.000,  7.500) = 2321 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =      8.705 ms/op
     p(99.9900) =     18.708 ms/op
     p(99.9990) =     21.030 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 5.439 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.011 ms/op
Iteration   1: 3.947 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  11.910 ms/op
                 listUser·p0.9999: 17.003 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   2: 3.914 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  18.448 ms/op
                 listUser·p0.9999: 21.577 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   3: 3.963 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 20.101 ms/op
                 listUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243604
  mean =      3.941 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2986 
    [ 2.500,  5.000) = 218506 
    [ 5.000,  7.500) = 20521 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.867 ms/op
     p(99.9900) =     21.058 ms/op
     p(99.9990) =     22.033 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.453 ± 0.846  ops/ms
ClientGrpc.existUser                       thrpt       3  10.809 ± 1.073  ops/ms
ClientGrpc.getUser                         thrpt       3  10.433 ± 1.760  ops/ms
ClientGrpc.listUser                        thrpt       3   8.193 ± 4.070  ops/ms
ClientGrpc.createUser                       avgt       3   3.070 ± 0.881   ms/op
ClientGrpc.existUser                        avgt       3   2.966 ± 0.965   ms/op
ClientGrpc.getUser                          avgt       3   3.092 ± 0.455   ms/op
ClientGrpc.listUser                         avgt       3   3.928 ± 1.375   ms/op
ClientGrpc.createUser                     sample  309979   3.096 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.247           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.990           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.981           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.781           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.957           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.743           ms/op
ClientGrpc.existUser                      sample  323823   2.963 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.359           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.776           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.126           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.884           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.478           ms/op
ClientGrpc.getUser                        sample  310709   3.089 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.642           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.985           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.932           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.705           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.708           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.135           ms/op
ClientGrpc.listUser                       sample  243604   3.941 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.804           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.867           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.058           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.151           ms/op
