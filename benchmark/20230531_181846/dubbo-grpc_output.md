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
# Warmup Iteration   1: 4.176 ops/ms
# Warmup Iteration   2: 9.105 ops/ms
# Warmup Iteration   3: 10.596 ops/ms
Iteration   1: 10.554 ops/ms
Iteration   2: 10.672 ops/ms
Iteration   3: 10.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.578 ±(99.9%) 1.551 ops/ms [Average]
  (min, avg, max) = (10.507, 10.578, 10.672), stdev = 0.085
  CI (99.9%): [9.027, 12.128] (assumes normal distribution)


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
# Warmup Iteration   1: 7.631 ops/ms
# Warmup Iteration   2: 10.564 ops/ms
# Warmup Iteration   3: 11.097 ops/ms
Iteration   1: 10.990 ops/ms
Iteration   2: 11.153 ops/ms
Iteration   3: 11.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.150 ±(99.9%) 2.877 ops/ms [Average]
  (min, avg, max) = (10.990, 11.150, 11.306), stdev = 0.158
  CI (99.9%): [8.273, 14.026] (assumes normal distribution)


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
# Warmup Iteration   1: 6.712 ops/ms
# Warmup Iteration   2: 10.225 ops/ms
# Warmup Iteration   3: 10.432 ops/ms
Iteration   1: 10.625 ops/ms
Iteration   2: 10.699 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.627 ±(99.9%) 1.291 ops/ms [Average]
  (min, avg, max) = (10.558, 10.627, 10.699), stdev = 0.071
  CI (99.9%): [9.336, 11.918] (assumes normal distribution)


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
# Warmup Iteration   1: 6.227 ops/ms
# Warmup Iteration   2: 8.100 ops/ms
# Warmup Iteration   3: 8.035 ops/ms
Iteration   1: 8.324 ops/ms
Iteration   2: 8.220 ops/ms
Iteration   3: 8.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.248 ±(99.9%) 1.211 ops/ms [Average]
  (min, avg, max) = (8.201, 8.248, 8.324), stdev = 0.066
  CI (99.9%): [7.037, 9.460] (assumes normal distribution)


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.003 ms/op
Iteration   2: 3.033 ±(99.9%) 0.002 ms/op
Iteration   3: 3.042 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.030 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (3.016, 3.030, 3.042), stdev = 0.013
  CI (99.9%): [2.796, 3.264] (assumes normal distribution)


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.003 ms/op
Iteration   1: 2.886 ±(99.9%) 0.002 ms/op
Iteration   2: 2.929 ±(99.9%) 0.003 ms/op
Iteration   3: 2.927 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (2.886, 2.914, 2.929), stdev = 0.024
  CI (99.9%): [2.474, 3.354] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.004 ms/op
Iteration   1: 3.094 ±(99.9%) 0.002 ms/op
Iteration   2: 2.991 ±(99.9%) 0.003 ms/op
Iteration   3: 3.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.034 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (2.991, 3.034, 3.094), stdev = 0.053
  CI (99.9%): [2.060, 4.009] (assumes normal distribution)


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
# Warmup Iteration   1: 5.297 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.011 ms/op
Iteration   1: 3.940 ±(99.9%) 0.012 ms/op
Iteration   2: 3.865 ±(99.9%) 0.012 ms/op
Iteration   3: 3.927 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.911 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.865, 3.911, 3.940), stdev = 0.040
  CI (99.9%): [3.181, 4.640] (assumes normal distribution)


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.009 ms/op
                 createUser·p0.9999: 12.115 ms/op
                 createUser·p1.00:   12.517 ms/op

Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.406 ms/op
                 createUser·p0.9999: 19.234 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  13.137 ms/op
                 createUser·p0.9999: 15.410 ms/op
                 createUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316163
  mean =      3.037 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1132 
    [ 1.250,  2.500) = 20270 
    [ 2.500,  3.750) = 280292 
    [ 3.750,  5.000) = 12732 
    [ 5.000,  6.250) = 902 
    [ 6.250,  7.500) = 455 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      9.497 ms/op
     p(99.9900) =     18.274 ms/op
     p(99.9990) =     19.524 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.006 ms/op
Iteration   1: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  5.988 ms/op
                 existUser·p0.9999: 11.469 ms/op
                 existUser·p1.00:   12.059 ms/op

Iteration   2: 2.906 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  7.299 ms/op
                 existUser·p0.9999: 14.319 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  7.065 ms/op
                 existUser·p0.9999: 23.434 ms/op
                 existUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329783
  mean =      2.912 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43443 
    [ 2.500,  5.000) = 284939 
    [ 5.000,  7.500) = 1179 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      6.793 ms/op
     p(99.9900) =     14.968 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.119 ms/op
                 getUser·p0.9999: 17.283 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   2: 2.973 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  6.971 ms/op
                 getUser·p0.9999: 12.882 ms/op
                 getUser·p1.00:   13.009 ms/op

Iteration   3: 3.108 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.431 ms/op
                 getUser·p0.9999: 15.031 ms/op
                 getUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316179
  mean =      3.035 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1703 
    [ 1.250,  2.500) = 21403 
    [ 2.500,  3.750) = 275570 
    [ 3.750,  5.000) = 16061 
    [ 5.000,  6.250) = 915 
    [ 6.250,  7.500) = 296 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      6.791 ms/op
     p(99.9900) =     16.802 ms/op
     p(99.9990) =     17.460 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 5.520 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.010 ms/op
Iteration   1: 3.878 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  12.376 ms/op
                 listUser·p0.9999: 15.043 ms/op
                 listUser·p1.00:   15.385 ms/op

Iteration   2: 3.902 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 19.425 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 3.840 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.222 ms/op
                 listUser·p0.9999: 16.857 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247849
  mean =      3.873 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3394 
    [ 2.500,  5.000) = 226678 
    [ 5.000,  7.500) = 16792 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.765 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     21.137 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.578 ± 1.551  ops/ms
ClientGrpc.existUser                       thrpt       3  11.150 ± 2.877  ops/ms
ClientGrpc.getUser                         thrpt       3  10.627 ± 1.291  ops/ms
ClientGrpc.listUser                        thrpt       3   8.248 ± 1.211  ops/ms
ClientGrpc.createUser                       avgt       3   3.030 ± 0.234   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ± 0.440   ms/op
ClientGrpc.getUser                          avgt       3   3.034 ± 0.974   ms/op
ClientGrpc.listUser                         avgt       3   3.911 ± 0.729   ms/op
ClientGrpc.createUser                     sample  316163   3.037 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.696           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.497           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.274           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.628           ms/op
ClientGrpc.existUser                      sample  329783   2.912 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.634           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.793           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.968           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.822           ms/op
ClientGrpc.getUser                        sample  316179   3.035 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.642           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.791           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.802           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.498           ms/op
ClientGrpc.listUser                       sample  247849   3.873 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.978           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.765           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.907           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.201           ms/op
