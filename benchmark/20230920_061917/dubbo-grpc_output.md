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
# Warmup Iteration   1: 4.266 ops/ms
# Warmup Iteration   2: 8.929 ops/ms
# Warmup Iteration   3: 9.759 ops/ms
Iteration   1: 10.045 ops/ms
Iteration   2: 10.364 ops/ms
Iteration   3: 10.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.245 ±(99.9%) 3.176 ops/ms [Average]
  (min, avg, max) = (10.045, 10.245, 10.364), stdev = 0.174
  CI (99.9%): [7.069, 13.421] (assumes normal distribution)


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
# Warmup Iteration   1: 8.031 ops/ms
# Warmup Iteration   2: 10.227 ops/ms
# Warmup Iteration   3: 10.355 ops/ms
Iteration   1: 10.742 ops/ms
Iteration   2: 10.606 ops/ms
Iteration   3: 10.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.587 ±(99.9%) 3.008 ops/ms [Average]
  (min, avg, max) = (10.413, 10.587, 10.742), stdev = 0.165
  CI (99.9%): [7.579, 13.595] (assumes normal distribution)


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
# Warmup Iteration   1: 7.762 ops/ms
# Warmup Iteration   2: 9.701 ops/ms
# Warmup Iteration   3: 10.327 ops/ms
Iteration   1: 10.058 ops/ms
Iteration   2: 10.036 ops/ms
Iteration   3: 10.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.141 ±(99.9%) 2.980 ops/ms [Average]
  (min, avg, max) = (10.036, 10.141, 10.329), stdev = 0.163
  CI (99.9%): [7.161, 13.121] (assumes normal distribution)


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
# Warmup Iteration   1: 5.628 ops/ms
# Warmup Iteration   2: 7.910 ops/ms
# Warmup Iteration   3: 7.835 ops/ms
Iteration   1: 8.052 ops/ms
Iteration   2: 8.128 ops/ms
Iteration   3: 8.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.098 ±(99.9%) 0.738 ops/ms [Average]
  (min, avg, max) = (8.052, 8.098, 8.128), stdev = 0.040
  CI (99.9%): [7.360, 8.836] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.002 ms/op
Iteration   1: 3.125 ±(99.9%) 0.003 ms/op
Iteration   2: 3.158 ±(99.9%) 0.001 ms/op
Iteration   3: 3.124 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.136 ±(99.9%) 0.357 ms/op [Average]
  (min, avg, max) = (3.124, 3.136, 3.158), stdev = 0.020
  CI (99.9%): [2.779, 3.493] (assumes normal distribution)


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.002 ms/op
Iteration   1: 2.998 ±(99.9%) 0.004 ms/op
Iteration   2: 2.990 ±(99.9%) 0.001 ms/op
Iteration   3: 3.069 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.019 ±(99.9%) 0.791 ms/op [Average]
  (min, avg, max) = (2.990, 3.019, 3.069), stdev = 0.043
  CI (99.9%): [2.229, 3.810] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.002 ms/op
Iteration   1: 3.068 ±(99.9%) 0.002 ms/op
Iteration   2: 3.147 ±(99.9%) 0.002 ms/op
Iteration   3: 3.115 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.110 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.068, 3.110, 3.147), stdev = 0.040
  CI (99.9%): [2.387, 3.833] (assumes normal distribution)


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.019 ms/op
Iteration   1: 3.967 ±(99.9%) 0.022 ms/op
Iteration   2: 3.929 ±(99.9%) 0.012 ms/op
Iteration   3: 3.854 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.917 ±(99.9%) 1.046 ms/op [Average]
  (min, avg, max) = (3.854, 3.917, 3.967), stdev = 0.057
  CI (99.9%): [2.871, 4.962] (assumes normal distribution)


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
# Warmup Iteration   1: 4.139 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.006 ms/op
Iteration   1: 3.213 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.435 ms/op
                 createUser·p0.999:  10.673 ms/op
                 createUser·p0.9999: 12.933 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   2: 3.129 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 12.654 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.052 ms/op
                 createUser·p0.9999: 16.734 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305828
  mean =      3.138 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 243 
    [ 1.250,  2.500) = 7125 
    [ 2.500,  3.750) = 276840 
    [ 3.750,  5.000) = 19691 
    [ 5.000,  6.250) = 1023 
    [ 6.250,  7.500) = 445 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.063 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 3.769 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.005 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.150 ms/op
                 existUser·p0.9999: 11.473 ms/op
                 existUser·p1.00:   11.813 ms/op

Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  9.128 ms/op
                 existUser·p0.9999: 14.018 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  9.795 ms/op
                 existUser·p0.9999: 15.519 ms/op
                 existUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323324
  mean =      2.971 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1345 
    [ 1.250,  2.500) = 23097 
    [ 2.500,  3.750) = 287910 
    [ 3.750,  5.000) = 9504 
    [ 5.000,  6.250) = 787 
    [ 6.250,  7.500) = 282 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     14.598 ms/op
     p(99.9990) =     15.730 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 4.290 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
Iteration   1: 3.176 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 14.726 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   2: 3.121 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.237 ms/op
                 getUser·p0.9999: 20.283 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   3: 3.106 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.573 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.030 ms/op
                 getUser·p0.999:  6.715 ms/op
                 getUser·p0.9999: 17.170 ms/op
                 getUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306434
  mean =      3.134 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6806 
    [ 2.500,  5.000) = 298097 
    [ 5.000,  7.500) = 979 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      9.727 ms/op
     p(99.9900) =     20.098 ms/op
     p(99.9990) =     20.410 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 4.629 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.010 ms/op
Iteration   1: 3.925 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  11.764 ms/op
                 listUser·p0.9999: 13.053 ms/op
                 listUser·p1.00:   14.991 ms/op

Iteration   2: 3.883 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 14.505 ms/op
                 listUser·p1.00:   14.877 ms/op

Iteration   3: 3.928 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.549 ms/op
                 listUser·p0.9999: 18.996 ms/op
                 listUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245248
  mean =      3.912 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2647 
    [ 2.500,  3.750) = 94797 
    [ 3.750,  5.000) = 135999 
    [ 5.000,  6.250) = 7123 
    [ 6.250,  7.500) = 3799 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 203 
    [12.500, 13.750) = 139 
    [13.750, 15.000) = 101 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     17.705 ms/op
     p(99.9990) =     19.864 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.245 ± 3.176  ops/ms
ClientGrpc.existUser                       thrpt       3  10.587 ± 3.008  ops/ms
ClientGrpc.getUser                         thrpt       3  10.141 ± 2.980  ops/ms
ClientGrpc.listUser                        thrpt       3   8.098 ± 0.738  ops/ms
ClientGrpc.createUser                       avgt       3   3.136 ± 0.357   ms/op
ClientGrpc.existUser                        avgt       3   3.019 ± 0.791   ms/op
ClientGrpc.getUser                          avgt       3   3.110 ± 0.723   ms/op
ClientGrpc.listUser                         avgt       3   3.917 ± 1.046   ms/op
ClientGrpc.createUser                     sample  305828   3.138 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.839           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.063           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.729           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.007           ms/op
ClientGrpc.existUser                      sample  323324   2.971 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.727           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.011           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.598           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.827           ms/op
ClientGrpc.getUser                        sample  306434   3.134 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.573           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.727           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.098           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.018           ms/op
ClientGrpc.listUser                       sample  245248   3.912 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.317           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.960           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.705           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.988           ms/op
