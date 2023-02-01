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
# Warmup Iteration   1: 4.922 ops/ms
# Warmup Iteration   2: 9.387 ops/ms
# Warmup Iteration   3: 10.251 ops/ms
Iteration   1: 10.403 ops/ms
Iteration   2: 10.177 ops/ms
Iteration   3: 10.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.394 ±(99.9%) 3.879 ops/ms [Average]
  (min, avg, max) = (10.177, 10.394, 10.602), stdev = 0.213
  CI (99.9%): [6.515, 14.273] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.952 ops/ms
# Warmup Iteration   2: 10.290 ops/ms
# Warmup Iteration   3: 10.879 ops/ms
Iteration   1: 10.679 ops/ms
Iteration   2: 10.986 ops/ms
Iteration   3: 10.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.782 ±(99.9%) 3.227 ops/ms [Average]
  (min, avg, max) = (10.679, 10.782, 10.986), stdev = 0.177
  CI (99.9%): [7.555, 14.009] (assumes normal distribution)


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
# Warmup Iteration   1: 8.283 ops/ms
# Warmup Iteration   2: 10.065 ops/ms
# Warmup Iteration   3: 10.546 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.248 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.460 ±(99.9%) 3.936 ops/ms [Average]
  (min, avg, max) = (10.248, 10.460, 10.680), stdev = 0.216
  CI (99.9%): [6.524, 14.396] (assumes normal distribution)


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
# Warmup Iteration   1: 6.198 ops/ms
# Warmup Iteration   2: 7.923 ops/ms
# Warmup Iteration   3: 8.208 ops/ms
Iteration   1: 8.174 ops/ms
Iteration   2: 8.234 ops/ms
Iteration   3: 8.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.176 ±(99.9%) 1.025 ops/ms [Average]
  (min, avg, max) = (8.122, 8.176, 8.234), stdev = 0.056
  CI (99.9%): [7.152, 9.201] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 3.128 ±(99.9%) 0.004 ms/op
Iteration   2: 3.107 ±(99.9%) 0.001 ms/op
Iteration   3: 3.015 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.084 ±(99.9%) 1.096 ms/op [Average]
  (min, avg, max) = (3.015, 3.084, 3.128), stdev = 0.060
  CI (99.9%): [1.987, 4.180] (assumes normal distribution)


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
# Warmup Iteration   1: 3.503 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.002 ms/op
Iteration   1: 2.919 ±(99.9%) 0.003 ms/op
Iteration   2: 2.804 ±(99.9%) 0.003 ms/op
Iteration   3: 2.886 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.870 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (2.804, 2.870, 2.919), stdev = 0.059
  CI (99.9%): [1.790, 3.950] (assumes normal distribution)


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.002 ms/op
Iteration   1: 3.022 ±(99.9%) 0.002 ms/op
Iteration   2: 3.114 ±(99.9%) 0.001 ms/op
Iteration   3: 3.005 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.047 ±(99.9%) 1.069 ms/op [Average]
  (min, avg, max) = (3.005, 3.047, 3.114), stdev = 0.059
  CI (99.9%): [1.978, 4.115] (assumes normal distribution)


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
# Warmup Iteration   1: 5.291 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.045 ms/op
Iteration   1: 3.906 ±(99.9%) 0.024 ms/op
Iteration   2: 3.991 ±(99.9%) 0.011 ms/op
Iteration   3: 3.929 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.942 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.906, 3.942, 3.991), stdev = 0.044
  CI (99.9%): [3.141, 4.743] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.068 ms/op
                 createUser·p0.9999: 18.008 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.335 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.297 ms/op
                 createUser·p0.999:  9.499 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   3: 3.177 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.438 ms/op
                 createUser·p0.9999: 18.317 ms/op
                 createUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309962
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1030 
    [ 1.250,  2.500) = 27712 
    [ 2.500,  3.750) = 249607 
    [ 3.750,  5.000) = 30598 
    [ 5.000,  6.250) = 453 
    [ 6.250,  7.500) = 159 
    [ 7.500,  8.750) = 111 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 81 

  Percentiles, ms/op:
      p(0.0000) =      0.335 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     18.999 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.006 ms/op
Iteration   1: 2.909 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  5.300 ms/op
                 existUser·p0.9999: 11.026 ms/op
                 existUser·p1.00:   11.190 ms/op

Iteration   2: 2.928 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  6.222 ms/op
                 existUser·p0.9999: 12.943 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   3: 2.863 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.455 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  9.341 ms/op
                 existUser·p0.9999: 23.554 ms/op
                 existUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331070
  mean =      2.899 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50354 
    [ 2.500,  5.000) = 279934 
    [ 5.000,  7.500) = 536 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.496 ms/op
     p(99.9900) =     21.722 ms/op
     p(99.9990) =     23.747 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.605 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.559 ms/op
                 getUser·p0.9999: 12.677 ms/op
                 getUser·p1.00:   12.894 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  8.081 ms/op
                 getUser·p0.9999: 13.623 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.009 ms/op
                 getUser·p0.9999: 15.381 ms/op
                 getUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314233
  mean =      3.054 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1538 
    [ 1.250,  2.500) = 29155 
    [ 2.500,  3.750) = 257101 
    [ 3.750,  5.000) = 25495 
    [ 5.000,  6.250) = 447 
    [ 6.250,  7.500) = 200 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.312 ms/op
     p(99.9900) =     13.885 ms/op
     p(99.9990) =     15.701 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.010 ms/op
Iteration   1: 3.993 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  11.715 ms/op
                 listUser·p0.9999: 14.778 ms/op
                 listUser·p1.00:   15.221 ms/op

Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.742 ms/op
                 listUser·p0.9999: 23.099 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   3: 3.812 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.589 ms/op
                 listUser·p0.999:  14.401 ms/op
                 listUser·p0.9999: 22.695 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244404
  mean =      3.930 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5979 
    [ 2.500,  5.000) = 209737 
    [ 5.000,  7.500) = 27595 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     22.403 ms/op
     p(99.9990) =     24.926 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.394 ± 3.879  ops/ms
ClientGrpc.existUser                       thrpt       3  10.782 ± 3.227  ops/ms
ClientGrpc.getUser                         thrpt       3  10.460 ± 3.936  ops/ms
ClientGrpc.listUser                        thrpt       3   8.176 ± 1.025  ops/ms
ClientGrpc.createUser                       avgt       3   3.084 ± 1.096   ms/op
ClientGrpc.existUser                        avgt       3   2.870 ± 1.080   ms/op
ClientGrpc.getUser                          avgt       3   3.047 ± 1.069   ms/op
ClientGrpc.listUser                         avgt       3   3.942 ± 0.801   ms/op
ClientGrpc.createUser                     sample  309962   3.097 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.335           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.940           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.438           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.350           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.104           ms/op
ClientGrpc.existUser                      sample  331070   2.899 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.455           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.496           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.722           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.019           ms/op
ClientGrpc.getUser                        sample  314233   3.054 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.628           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.312           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.885           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.827           ms/op
ClientGrpc.listUser                       sample  244404   3.930 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.876           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.206           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.403           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.199           ms/op
