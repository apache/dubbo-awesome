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
# Warmup Iteration   1: 3.884 ops/ms
# Warmup Iteration   2: 9.129 ops/ms
# Warmup Iteration   3: 10.164 ops/ms
Iteration   1: 10.389 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.524 ±(99.9%) 2.177 ops/ms [Average]
  (min, avg, max) = (10.389, 10.524, 10.616), stdev = 0.119
  CI (99.9%): [8.347, 12.700] (assumes normal distribution)


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
# Warmup Iteration   1: 7.292 ops/ms
# Warmup Iteration   2: 10.742 ops/ms
# Warmup Iteration   3: 10.992 ops/ms
Iteration   1: 11.156 ops/ms
Iteration   2: 11.188 ops/ms
Iteration   3: 11.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.303 ±(99.9%) 4.150 ops/ms [Average]
  (min, avg, max) = (11.156, 11.303, 11.565), stdev = 0.227
  CI (99.9%): [7.153, 15.453] (assumes normal distribution)


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
# Warmup Iteration   1: 6.974 ops/ms
# Warmup Iteration   2: 10.442 ops/ms
# Warmup Iteration   3: 10.607 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.629 ops/ms
Iteration   3: 10.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.596 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (10.512, 10.596, 10.647), stdev = 0.073
  CI (99.9%): [9.263, 11.929] (assumes normal distribution)


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
# Warmup Iteration   1: 5.559 ops/ms
# Warmup Iteration   2: 8.040 ops/ms
# Warmup Iteration   3: 8.332 ops/ms
Iteration   1: 8.331 ops/ms
Iteration   2: 8.205 ops/ms
Iteration   3: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.254 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (8.205, 8.254, 8.331), stdev = 0.068
  CI (99.9%): [7.017, 9.490] (assumes normal distribution)


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
# Warmup Iteration   1: 4.412 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.004 ms/op
Iteration   1: 2.953 ±(99.9%) 0.003 ms/op
Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
Iteration   3: 3.001 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.999 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (2.953, 2.999, 3.042), stdev = 0.044
  CI (99.9%): [2.189, 3.808] (assumes normal distribution)


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
# Warmup Iteration   1: 3.561 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.004 ms/op
Iteration   1: 2.951 ±(99.9%) 0.002 ms/op
Iteration   2: 2.960 ±(99.9%) 0.003 ms/op
Iteration   3: 2.883 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.931 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (2.883, 2.931, 2.960), stdev = 0.042
  CI (99.9%): [2.163, 3.700] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.735 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 3.017 ±(99.9%) 0.003 ms/op
Iteration   3: 3.004 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.015 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (3.004, 3.015, 3.023), stdev = 0.010
  CI (99.9%): [2.837, 3.193] (assumes normal distribution)


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
# Warmup Iteration   1: 4.574 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.046 ms/op
Iteration   1: 3.870 ±(99.9%) 0.016 ms/op
Iteration   2: 3.892 ±(99.9%) 0.023 ms/op
Iteration   3: 3.908 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.890 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (3.870, 3.890, 3.908), stdev = 0.019
  CI (99.9%): [3.547, 4.233] (assumes normal distribution)


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
Iteration   1: 2.965 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.473 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.325 ms/op
                 createUser·p0.9999: 18.259 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  6.687 ms/op
                 createUser·p0.9999: 14.311 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  10.895 ms/op
                 createUser·p0.9999: 16.017 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321346
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 546 
    [ 1.250,  2.500) = 27769 
    [ 2.500,  3.750) = 279276 
    [ 3.750,  5.000) = 12446 
    [ 5.000,  6.250) = 860 
    [ 6.250,  7.500) = 141 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 72 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.234 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     18.795 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.007 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.122 ms/op
                 existUser·p0.9999: 13.557 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.149 ms/op
                 existUser·p0.9999: 20.621 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   3: 2.988 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  10.109 ms/op
                 existUser·p0.9999: 22.151 ms/op
                 existUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321690
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26437 
    [ 2.500,  5.000) = 293964 
    [ 5.000,  7.500) = 930 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.883 ms/op
     p(99.9900) =     21.092 ms/op
     p(99.9990) =     22.465 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.935 ms/op
                 getUser·p0.9999: 15.269 ms/op
                 getUser·p1.00:   16.663 ms/op

Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.428 ms/op
                 getUser·p0.9999: 23.855 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.290 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 20.217 ms/op
                 getUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312273
  mean =      3.075 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12037 
    [ 2.500,  5.000) = 298921 
    [ 5.000,  7.500) = 1003 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.502 ms/op
     p(99.9900) =     22.701 ms/op
     p(99.9990) =     24.441 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 6.065 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.011 ms/op
Iteration   1: 4.008 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.304 ms/op
                 listUser·p0.9999: 20.907 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 3.866 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  15.295 ms/op
                 listUser·p0.9999: 17.284 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 3.924 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.499 ms/op
                 listUser·p0.9999: 17.024 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244169
  mean =      3.932 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2476 
    [ 2.500,  5.000) = 218078 
    [ 5.000,  7.500) = 22404 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     14.828 ms/op
     p(99.9900) =     20.335 ms/op
     p(99.9990) =     21.256 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.524 ± 2.177  ops/ms
ClientGrpc.existUser                       thrpt       3  11.303 ± 4.150  ops/ms
ClientGrpc.getUser                         thrpt       3  10.596 ± 1.333  ops/ms
ClientGrpc.listUser                        thrpt       3   8.254 ± 1.236  ops/ms
ClientGrpc.createUser                       avgt       3   2.999 ± 0.809   ms/op
ClientGrpc.existUser                        avgt       3   2.931 ± 0.769   ms/op
ClientGrpc.getUser                          avgt       3   3.015 ± 0.178   ms/op
ClientGrpc.listUser                         avgt       3   3.890 ± 0.343   ms/op
ClientGrpc.createUser                     sample  321346   2.985 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.799           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.234           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.908           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.940           ms/op
ClientGrpc.existUser                      sample  321690   2.983 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.595           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.883           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.092           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.396           ms/op
ClientGrpc.getUser                        sample  312273   3.075 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.644           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.502           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.701           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.969           ms/op
ClientGrpc.listUser                       sample  244169   3.932 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.081           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.828           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.335           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.398           ms/op
