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
# Warmup Iteration   1: 3.627 ops/ms
# Warmup Iteration   2: 8.793 ops/ms
# Warmup Iteration   3: 9.794 ops/ms
Iteration   1: 10.261 ops/ms
Iteration   2: 10.319 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.371 ±(99.9%) 2.608 ops/ms [Average]
  (min, avg, max) = (10.261, 10.371, 10.533), stdev = 0.143
  CI (99.9%): [7.763, 12.979] (assumes normal distribution)


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
# Warmup Iteration   1: 7.368 ops/ms
# Warmup Iteration   2: 10.441 ops/ms
# Warmup Iteration   3: 10.654 ops/ms
Iteration   1: 11.237 ops/ms
Iteration   2: 10.895 ops/ms
Iteration   3: 10.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.985 ±(99.9%) 4.039 ops/ms [Average]
  (min, avg, max) = (10.822, 10.985, 11.237), stdev = 0.221
  CI (99.9%): [6.946, 15.024] (assumes normal distribution)


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
# Warmup Iteration   1: 6.587 ops/ms
# Warmup Iteration   2: 9.780 ops/ms
# Warmup Iteration   3: 10.330 ops/ms
Iteration   1: 10.420 ops/ms
Iteration   2: 10.527 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.518 ±(99.9%) 1.725 ops/ms [Average]
  (min, avg, max) = (10.420, 10.518, 10.608), stdev = 0.095
  CI (99.9%): [8.793, 12.244] (assumes normal distribution)


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
# Warmup Iteration   1: 5.393 ops/ms
# Warmup Iteration   2: 7.685 ops/ms
# Warmup Iteration   3: 7.812 ops/ms
Iteration   1: 8.240 ops/ms
Iteration   2: 7.892 ops/ms
Iteration   3: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.047 ±(99.9%) 3.236 ops/ms [Average]
  (min, avg, max) = (7.892, 8.047, 8.240), stdev = 0.177
  CI (99.9%): [4.810, 11.283] (assumes normal distribution)


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
# Warmup Iteration   1: 4.560 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.003 ms/op
Iteration   1: 3.152 ±(99.9%) 0.004 ms/op
Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
Iteration   3: 3.117 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.110 ±(99.9%) 0.841 ms/op [Average]
  (min, avg, max) = (3.060, 3.110, 3.152), stdev = 0.046
  CI (99.9%): [2.268, 3.951] (assumes normal distribution)


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.003 ms/op
Iteration   1: 3.012 ±(99.9%) 0.003 ms/op
Iteration   2: 2.893 ±(99.9%) 0.003 ms/op
Iteration   3: 2.816 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 1.795 ms/op [Average]
  (min, avg, max) = (2.816, 2.907, 3.012), stdev = 0.098
  CI (99.9%): [1.112, 4.703] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.535 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.003 ms/op
Iteration   1: 3.064 ±(99.9%) 0.003 ms/op
Iteration   2: 3.040 ±(99.9%) 0.004 ms/op
Iteration   3: 3.048 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.051 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (3.040, 3.051, 3.064), stdev = 0.012
  CI (99.9%): [2.826, 3.276] (assumes normal distribution)


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
# Warmup Iteration   1: 5.796 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.013 ms/op
Iteration   1: 4.097 ±(99.9%) 0.017 ms/op
Iteration   2: 4.128 ±(99.9%) 0.014 ms/op
Iteration   3: 4.097 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.107 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (4.097, 4.107, 4.128), stdev = 0.018
  CI (99.9%): [3.784, 4.431] (assumes normal distribution)


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  11.338 ms/op
                 createUser·p0.9999: 13.095 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  10.640 ms/op
                 createUser·p0.9999: 14.844 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.291 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.487 ms/op
                 createUser·p0.9999: 15.994 ms/op
                 createUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313550
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 881 
    [ 1.250,  2.500) = 19220 
    [ 2.500,  3.750) = 277121 
    [ 3.750,  5.000) = 13957 
    [ 5.000,  6.250) = 1013 
    [ 6.250,  7.500) = 663 
    [ 7.500,  8.750) = 295 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 84 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.291 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =     10.632 ms/op
     p(99.9900) =     15.647 ms/op
     p(99.9990) =     16.330 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


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
# Warmup Iteration   1: 4.135 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.007 ms/op
Iteration   1: 2.960 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  8.158 ms/op
                 existUser·p0.9999: 13.758 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.951 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.289 ms/op
                 existUser·p0.999:  7.763 ms/op
                 existUser·p0.9999: 14.732 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   3: 2.949 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.296 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  8.020 ms/op
                 existUser·p0.9999: 15.073 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324947
  mean =      2.954 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 805 
    [ 1.250,  2.500) = 30529 
    [ 2.500,  3.750) = 282159 
    [ 3.750,  5.000) = 9780 
    [ 5.000,  6.250) = 716 
    [ 6.250,  7.500) = 532 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.296 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.004 ms/op
     p(99.9900) =     14.787 ms/op
     p(99.9990) =     16.458 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  8.249 ms/op
                 getUser·p0.9999: 21.702 ms/op
                 getUser·p1.00:   22.151 ms/op

Iteration   2: 3.058 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  10.289 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  7.684 ms/op
                 getUser·p0.9999: 24.936 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312434
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22159 
    [ 2.500,  5.000) = 287074 
    [ 5.000,  7.500) = 2798 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =      8.480 ms/op
     p(99.9900) =     23.053 ms/op
     p(99.9990) =     25.260 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 5.742 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.012 ms/op
Iteration   1: 3.994 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  14.118 ms/op
                 listUser·p0.9999: 16.662 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   2: 4.124 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  16.812 ms/op
                 listUser·p0.9999: 26.958 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   3: 4.043 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.541 ms/op
                 listUser·p0.9999: 24.412 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236951
  mean =      4.053 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2448 
    [ 2.500,  5.000) = 207942 
    [ 5.000,  7.500) = 24352 
    [ 7.500, 10.000) = 1682 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.844 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     26.038 ms/op
     p(99.9990) =     27.351 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.371 ± 2.608  ops/ms
ClientGrpc.existUser                       thrpt       3  10.985 ± 4.039  ops/ms
ClientGrpc.getUser                         thrpt       3  10.518 ± 1.725  ops/ms
ClientGrpc.listUser                        thrpt       3   8.047 ± 3.236  ops/ms
ClientGrpc.createUser                       avgt       3   3.110 ± 0.841   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 1.795   ms/op
ClientGrpc.getUser                          avgt       3   3.051 ± 0.225   ms/op
ClientGrpc.listUser                         avgt       3   4.107 ± 0.324   ms/op
ClientGrpc.createUser                     sample  313550   3.059 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.291           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.632           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.647           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.400           ms/op
ClientGrpc.existUser                      sample  324947   2.954 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.296           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.004           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.787           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.974           ms/op
ClientGrpc.getUser                        sample  312434   3.074 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.605           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.022           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.480           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.053           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.362           ms/op
ClientGrpc.listUser                       sample  236951   4.053 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.063           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.844           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.430           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.038           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.623           ms/op
