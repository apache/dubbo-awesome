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
# Warmup Iteration   1: 4.488 ops/ms
# Warmup Iteration   2: 9.366 ops/ms
# Warmup Iteration   3: 9.994 ops/ms
Iteration   1: 10.155 ops/ms
Iteration   2: 10.075 ops/ms
Iteration   3: 10.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.191 ±(99.9%) 2.490 ops/ms [Average]
  (min, avg, max) = (10.075, 10.191, 10.341), stdev = 0.136
  CI (99.9%): [7.701, 12.681] (assumes normal distribution)


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
# Warmup Iteration   1: 8.006 ops/ms
# Warmup Iteration   2: 10.365 ops/ms
# Warmup Iteration   3: 10.792 ops/ms
Iteration   1: 10.545 ops/ms
Iteration   2: 10.710 ops/ms
Iteration   3: 10.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.671 ±(99.9%) 2.034 ops/ms [Average]
  (min, avg, max) = (10.545, 10.671, 10.757), stdev = 0.112
  CI (99.9%): [8.636, 12.705] (assumes normal distribution)


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
# Warmup Iteration   1: 7.898 ops/ms
# Warmup Iteration   2: 10.277 ops/ms
# Warmup Iteration   3: 10.456 ops/ms
Iteration   1: 10.582 ops/ms
Iteration   2: 10.246 ops/ms
Iteration   3: 10.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.486 ±(99.9%) 3.814 ops/ms [Average]
  (min, avg, max) = (10.246, 10.486, 10.630), stdev = 0.209
  CI (99.9%): [6.672, 14.300] (assumes normal distribution)


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
# Warmup Iteration   1: 6.090 ops/ms
# Warmup Iteration   2: 8.349 ops/ms
# Warmup Iteration   3: 8.274 ops/ms
Iteration   1: 8.553 ops/ms
Iteration   2: 8.473 ops/ms
Iteration   3: 8.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.520 ±(99.9%) 0.757 ops/ms [Average]
  (min, avg, max) = (8.473, 8.520, 8.553), stdev = 0.041
  CI (99.9%): [7.763, 9.277] (assumes normal distribution)


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.003 ms/op
Iteration   1: 3.147 ±(99.9%) 0.002 ms/op
Iteration   2: 3.076 ±(99.9%) 0.001 ms/op
Iteration   3: 3.084 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.102 ±(99.9%) 0.709 ms/op [Average]
  (min, avg, max) = (3.076, 3.102, 3.147), stdev = 0.039
  CI (99.9%): [2.393, 3.812] (assumes normal distribution)


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.001 ms/op
Iteration   1: 2.955 ±(99.9%) 0.002 ms/op
Iteration   2: 2.950 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.972 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (2.950, 2.972, 3.012), stdev = 0.034
  CI (99.9%): [2.344, 3.601] (assumes normal distribution)


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.002 ms/op
Iteration   1: 3.109 ±(99.9%) 0.002 ms/op
Iteration   2: 3.039 ±(99.9%) 0.002 ms/op
Iteration   3: 3.057 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.068 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.039, 3.068, 3.109), stdev = 0.037
  CI (99.9%): [2.402, 3.734] (assumes normal distribution)


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
# Warmup Iteration   1: 5.120 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.028 ms/op
Iteration   1: 3.811 ±(99.9%) 0.047 ms/op
Iteration   2: 3.730 ±(99.9%) 0.025 ms/op
Iteration   3: 3.768 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.770 ±(99.9%) 0.739 ms/op [Average]
  (min, avg, max) = (3.730, 3.770, 3.811), stdev = 0.041
  CI (99.9%): [3.031, 4.509] (assumes normal distribution)


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.006 ms/op
Iteration   1: 3.116 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  9.933 ms/op
                 createUser·p0.9999: 17.695 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   2: 3.085 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.031 ms/op
                 createUser·p0.999:  8.249 ms/op
                 createUser·p0.9999: 13.161 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 3.009 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.720 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.682 ms/op
                 createUser·p0.9999: 13.719 ms/op
                 createUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312704
  mean =      3.069 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 505 
    [ 1.250,  2.500) = 12518 
    [ 2.500,  3.750) = 282560 
    [ 3.750,  5.000) = 15829 
    [ 5.000,  6.250) = 686 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.946 ms/op
     p(99.9900) =     16.914 ms/op
     p(99.9990) =     17.887 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  6.431 ms/op
                 existUser·p0.9999: 13.025 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   2: 2.971 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.456 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  6.841 ms/op
                 existUser·p0.9999: 16.064 ms/op
                 existUser·p1.00:   16.400 ms/op

Iteration   3: 2.958 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.493 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.568 ms/op
                 existUser·p0.9999: 31.097 ms/op
                 existUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323474
  mean =      2.968 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26434 
    [ 2.500,  5.000) = 295652 
    [ 5.000,  7.500) = 1170 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.591 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     31.253 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.068 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.765 ms/op
                 getUser·p0.9999: 11.436 ms/op
                 getUser·p1.00:   11.567 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  11.630 ms/op
                 getUser·p0.9999: 17.929 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.978 ms/op
                 getUser·p0.9999: 14.434 ms/op
                 getUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311574
  mean =      3.079 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 737 
    [ 1.250,  2.500) = 14445 
    [ 2.500,  3.750) = 278356 
    [ 3.750,  5.000) = 16645 
    [ 5.000,  6.250) = 799 
    [ 6.250,  7.500) = 231 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.146 ms/op
     p(99.9900) =     17.291 ms/op
     p(99.9990) =     18.379 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 5.007 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.008 ms/op
Iteration   1: 3.808 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   6.411 ms/op
                 listUser·p0.999:  12.494 ms/op
                 listUser·p0.9999: 16.947 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 3.815 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.341 ms/op
                 listUser·p0.999:  13.371 ms/op
                 listUser·p0.9999: 16.243 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 3.822 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  16.704 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251845
  mean =      3.815 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3959 
    [ 2.500,  5.000) = 234103 
    [ 5.000,  7.500) = 12898 
    [ 7.500, 10.000) = 408 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     13.503 ms/op
     p(99.9900) =     19.688 ms/op
     p(99.9990) =     21.200 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.191 ± 2.490  ops/ms
ClientGrpc.existUser                       thrpt       3  10.671 ± 2.034  ops/ms
ClientGrpc.getUser                         thrpt       3  10.486 ± 3.814  ops/ms
ClientGrpc.listUser                        thrpt       3   8.520 ± 0.757  ops/ms
ClientGrpc.createUser                       avgt       3   3.102 ± 0.709   ms/op
ClientGrpc.existUser                        avgt       3   2.972 ± 0.629   ms/op
ClientGrpc.getUser                          avgt       3   3.068 ± 0.666   ms/op
ClientGrpc.listUser                         avgt       3   3.770 ± 0.739   ms/op
ClientGrpc.createUser                     sample  312704   3.069 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.720           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.946           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.914           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.924           ms/op
ClientGrpc.existUser                      sample  323474   2.968 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.456           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.591           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.366           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.654           ms/op
ClientGrpc.getUser                        sample  311574   3.079 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.606           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.146           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.291           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.514           ms/op
ClientGrpc.listUser                       sample  251845   3.815 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.762           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.252           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.431           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.503           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.688           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.266           ms/op
