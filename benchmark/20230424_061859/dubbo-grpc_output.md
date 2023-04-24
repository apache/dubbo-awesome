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
# Warmup Iteration   1: 3.755 ops/ms
# Warmup Iteration   2: 8.125 ops/ms
# Warmup Iteration   3: 9.611 ops/ms
Iteration   1: 10.067 ops/ms
Iteration   2: 10.311 ops/ms
Iteration   3: 10.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.285 ±(99.9%) 3.752 ops/ms [Average]
  (min, avg, max) = (10.067, 10.285, 10.476), stdev = 0.206
  CI (99.9%): [6.533, 14.037] (assumes normal distribution)


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
# Warmup Iteration   1: 6.892 ops/ms
# Warmup Iteration   2: 10.345 ops/ms
# Warmup Iteration   3: 10.958 ops/ms
Iteration   1: 10.928 ops/ms
Iteration   2: 11.003 ops/ms
Iteration   3: 10.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.898 ±(99.9%) 2.258 ops/ms [Average]
  (min, avg, max) = (10.762, 10.898, 11.003), stdev = 0.124
  CI (99.9%): [8.640, 13.155] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.602 ops/ms
# Warmup Iteration   2: 9.940 ops/ms
# Warmup Iteration   3: 10.270 ops/ms
Iteration   1: 10.359 ops/ms
Iteration   2: 10.211 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.356 ±(99.9%) 2.621 ops/ms [Average]
  (min, avg, max) = (10.211, 10.356, 10.498), stdev = 0.144
  CI (99.9%): [7.736, 12.977] (assumes normal distribution)


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
# Warmup Iteration   1: 5.236 ops/ms
# Warmup Iteration   2: 7.523 ops/ms
# Warmup Iteration   3: 7.889 ops/ms
Iteration   1: 7.812 ops/ms
Iteration   2: 7.927 ops/ms
Iteration   3: 7.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.850 ±(99.9%) 1.225 ops/ms [Average]
  (min, avg, max) = (7.810, 7.850, 7.927), stdev = 0.067
  CI (99.9%): [6.625, 9.074] (assumes normal distribution)


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.001 ms/op
Iteration   1: 3.100 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.003 ms/op
Iteration   3: 3.129 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.091 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (3.044, 3.091, 3.129), stdev = 0.043
  CI (99.9%): [2.302, 3.880] (assumes normal distribution)


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
# Warmup Iteration   1: 4.173 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.003 ms/op
Iteration   2: 2.933 ±(99.9%) 0.002 ms/op
Iteration   3: 2.924 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.933 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (2.924, 2.933, 2.943), stdev = 0.010
  CI (99.9%): [2.757, 3.110] (assumes normal distribution)


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.004 ms/op
Iteration   3: 3.117 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.088 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.070, 3.088, 3.117), stdev = 0.026
  CI (99.9%): [2.620, 3.556] (assumes normal distribution)


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
# Warmup Iteration   1: 5.466 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.013 ms/op
Iteration   1: 3.971 ±(99.9%) 0.015 ms/op
Iteration   2: 4.020 ±(99.9%) 0.011 ms/op
Iteration   3: 4.003 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.998 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (3.971, 3.998, 4.020), stdev = 0.025
  CI (99.9%): [3.539, 4.457] (assumes normal distribution)


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
Iteration   1: 3.110 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.965 ms/op
                 createUser·p0.999:  12.868 ms/op
                 createUser·p0.9999: 14.245 ms/op
                 createUser·p1.00:   15.843 ms/op

Iteration   2: 3.058 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  7.893 ms/op
                 createUser·p0.9999: 21.819 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  8.887 ms/op
                 createUser·p0.9999: 17.574 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310908
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19648 
    [ 2.500,  5.000) = 288510 
    [ 5.000,  7.500) = 2123 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =     10.472 ms/op
     p(99.9900) =     20.075 ms/op
     p(99.9990) =     22.799 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  8.072 ms/op
                 existUser·p0.9999: 13.307 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  10.650 ms/op
                 existUser·p0.9999: 15.557 ms/op
                 existUser·p1.00:   15.942 ms/op

Iteration   3: 2.936 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  10.160 ms/op
                 existUser·p0.9999: 17.990 ms/op
                 existUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325154
  mean =      2.950 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1945 
    [ 1.250,  2.500) = 33542 
    [ 2.500,  3.750) = 276580 
    [ 3.750,  5.000) = 11375 
    [ 5.000,  6.250) = 908 
    [ 6.250,  7.500) = 347 
    [ 7.500,  8.750) = 122 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      9.530 ms/op
     p(99.9900) =     15.859 ms/op
     p(99.9990) =     18.047 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
Iteration   1: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  8.841 ms/op
                 getUser·p0.9999: 14.001 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  10.767 ms/op
                 getUser·p0.9999: 14.836 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  8.156 ms/op
                 getUser·p0.9999: 20.429 ms/op
                 getUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311524
  mean =      3.081 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24170 
    [ 2.500,  5.000) = 284804 
    [ 5.000,  7.500) = 1995 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      9.691 ms/op
     p(99.9900) =     19.017 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 5.755 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.261 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.011 ms/op
Iteration   1: 4.080 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  14.798 ms/op
                 listUser·p0.9999: 17.547 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   2: 3.963 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  16.110 ms/op
                 listUser·p0.9999: 19.654 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 3.950 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  18.449 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240089
  mean =      3.997 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2846 
    [ 2.500,  5.000) = 210252 
    [ 5.000,  7.500) = 24913 
    [ 7.500, 10.000) = 1570 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     20.119 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.285 ± 3.752  ops/ms
ClientGrpc.existUser                       thrpt       3  10.898 ± 2.258  ops/ms
ClientGrpc.getUser                         thrpt       3  10.356 ± 2.621  ops/ms
ClientGrpc.listUser                        thrpt       3   7.850 ± 1.225  ops/ms
ClientGrpc.createUser                       avgt       3   3.091 ± 0.789   ms/op
ClientGrpc.existUser                        avgt       3   2.933 ± 0.176   ms/op
ClientGrpc.getUser                          avgt       3   3.088 ± 0.468   ms/op
ClientGrpc.listUser                         avgt       3   3.998 ± 0.459   ms/op
ClientGrpc.createUser                     sample  310908   3.087 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.611           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.907           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.472           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.075           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.938           ms/op
ClientGrpc.existUser                      sample  325154   2.950 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.628           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.530           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.859           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.088           ms/op
ClientGrpc.getUser                        sample  311524   3.081 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.571           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.691           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.017           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.546           ms/op
ClientGrpc.listUser                       sample  240089   3.997 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.911           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.365           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.119           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.906           ms/op
