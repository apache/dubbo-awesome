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
# Warmup Iteration   1: 4.827 ops/ms
# Warmup Iteration   2: 9.186 ops/ms
# Warmup Iteration   3: 9.971 ops/ms
Iteration   1: 10.252 ops/ms
Iteration   2: 10.344 ops/ms
Iteration   3: 10.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.300 ±(99.9%) 0.840 ops/ms [Average]
  (min, avg, max) = (10.252, 10.300, 10.344), stdev = 0.046
  CI (99.9%): [9.460, 11.141] (assumes normal distribution)


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
# Warmup Iteration   1: 8.088 ops/ms
# Warmup Iteration   2: 10.488 ops/ms
# Warmup Iteration   3: 10.922 ops/ms
Iteration   1: 10.734 ops/ms
Iteration   2: 10.811 ops/ms
Iteration   3: 11.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.922 ±(99.9%) 4.761 ops/ms [Average]
  (min, avg, max) = (10.734, 10.922, 11.220), stdev = 0.261
  CI (99.9%): [6.160, 15.683] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.576 ops/ms
# Warmup Iteration   2: 9.732 ops/ms
# Warmup Iteration   3: 10.087 ops/ms
Iteration   1: 10.273 ops/ms
Iteration   2: 10.234 ops/ms
Iteration   3: 10.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.307 ±(99.9%) 1.749 ops/ms [Average]
  (min, avg, max) = (10.234, 10.307, 10.416), stdev = 0.096
  CI (99.9%): [8.558, 12.057] (assumes normal distribution)


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
# Warmup Iteration   1: 7.889 ops/ms
# Warmup Iteration   2: 8.078 ops/ms
# Warmup Iteration   3: 8.477 ops/ms
Iteration   1: 8.318 ops/ms
Iteration   2: 8.391 ops/ms
Iteration   3: 8.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.350 ±(99.9%) 0.675 ops/ms [Average]
  (min, avg, max) = (8.318, 8.350, 8.391), stdev = 0.037
  CI (99.9%): [7.676, 9.025] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.005 ms/op
Iteration   1: 3.112 ±(99.9%) 0.002 ms/op
Iteration   2: 3.065 ±(99.9%) 0.002 ms/op
Iteration   3: 3.088 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.088 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (3.065, 3.088, 3.112), stdev = 0.024
  CI (99.9%): [2.655, 3.521] (assumes normal distribution)


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
# Warmup Iteration   1: 3.564 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.003 ms/op
Iteration   1: 2.968 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.003 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.996 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (2.968, 2.996, 3.028), stdev = 0.030
  CI (99.9%): [2.445, 3.547] (assumes normal distribution)


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.001 ms/op
Iteration   1: 3.118 ±(99.9%) 0.002 ms/op
Iteration   2: 3.093 ±(99.9%) 0.002 ms/op
Iteration   3: 3.060 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.090 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (3.060, 3.090, 3.118), stdev = 0.029
  CI (99.9%): [2.556, 3.625] (assumes normal distribution)


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
# Warmup Iteration   1: 5.033 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.018 ms/op
Iteration   1: 3.785 ±(99.9%) 0.042 ms/op
Iteration   2: 3.759 ±(99.9%) 0.013 ms/op
Iteration   3: 3.812 ±(99.9%) 0.056 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.785 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (3.759, 3.785, 3.812), stdev = 0.026
  CI (99.9%): [3.302, 4.268] (assumes normal distribution)


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.005 ms/op
Iteration   1: 3.061 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  8.971 ms/op
                 createUser·p0.9999: 11.594 ms/op
                 createUser·p1.00:   11.977 ms/op

Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.279 ms/op
                 createUser·p0.999:  9.870 ms/op
                 createUser·p0.9999: 14.027 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   3: 3.114 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  10.578 ms/op
                 createUser·p0.9999: 16.387 ms/op
                 createUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311658
  mean =      3.081 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 385 
    [ 1.250,  2.500) = 10197 
    [ 2.500,  3.750) = 284406 
    [ 3.750,  5.000) = 14926 
    [ 5.000,  6.250) = 770 
    [ 6.250,  7.500) = 344 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =     10.338 ms/op
     p(99.9900) =     14.445 ms/op
     p(99.9990) =     16.639 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 3.704 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
Iteration   1: 3.046 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  8.980 ms/op
                 existUser·p0.9999: 12.313 ms/op
                 existUser·p1.00:   12.616 ms/op

Iteration   2: 2.823 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.435 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.352 ms/op
                 existUser·p0.999:  7.119 ms/op
                 existUser·p0.9999: 11.813 ms/op
                 existUser·p1.00:   12.157 ms/op

Iteration   3: 2.998 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.463 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.006 ms/op
                 existUser·p0.9999: 14.854 ms/op
                 existUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325181
  mean =      2.953 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2062 
    [ 1.250,  2.500) = 34681 
    [ 2.500,  3.750) = 276959 
    [ 3.750,  5.000) = 10239 
    [ 5.000,  6.250) = 602 
    [ 6.250,  7.500) = 328 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.396 ms/op
     p(99.9900) =     14.606 ms/op
     p(99.9990) =     15.208 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.005 ms/op
Iteration   1: 3.179 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 13.498 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.648 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 16.805 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   3: 3.150 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.634 ms/op
                 getUser·p0.9999: 15.904 ms/op
                 getUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303755
  mean =      3.161 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 561 
    [ 1.250,  2.500) = 8211 
    [ 2.500,  3.750) = 265816 
    [ 3.750,  5.000) = 27332 
    [ 5.000,  6.250) = 765 
    [ 6.250,  7.500) = 438 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 148 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     16.404 ms/op
     p(99.9990) =     17.004 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.008 ms/op
Iteration   1: 3.816 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  11.404 ms/op
                 listUser·p0.9999: 12.963 ms/op
                 listUser·p1.00:   13.287 ms/op

Iteration   2: 3.836 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  13.189 ms/op
                 listUser·p0.9999: 14.576 ms/op
                 listUser·p1.00:   15.073 ms/op

Iteration   3: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  13.042 ms/op
                 listUser·p0.9999: 15.876 ms/op
                 listUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250358
  mean =      3.836 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 4677 
    [ 2.500,  3.750) = 122890 
    [ 3.750,  5.000) = 107018 
    [ 5.000,  6.250) = 11351 
    [ 6.250,  7.500) = 3650 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 126 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     12.173 ms/op
     p(99.9900) =     15.447 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.300 ± 0.840  ops/ms
ClientGrpc.existUser                       thrpt       3  10.922 ± 4.761  ops/ms
ClientGrpc.getUser                         thrpt       3  10.307 ± 1.749  ops/ms
ClientGrpc.listUser                        thrpt       3   8.350 ± 0.675  ops/ms
ClientGrpc.createUser                       avgt       3   3.088 ± 0.433   ms/op
ClientGrpc.existUser                        avgt       3   2.996 ± 0.551   ms/op
ClientGrpc.getUser                          avgt       3   3.090 ± 0.535   ms/op
ClientGrpc.listUser                         avgt       3   3.785 ± 0.483   ms/op
ClientGrpc.createUser                     sample  311658   3.081 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.338           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.445           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.761           ms/op
ClientGrpc.existUser                      sample  325181   2.953 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.435           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.396           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.606           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.303           ms/op
ClientGrpc.getUser                        sample  303755   3.161 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.712           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.634           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.404           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.105           ms/op
ClientGrpc.listUser                       sample  250358   3.836 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.939           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.480           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.173           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.447           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          16.450           ms/op
