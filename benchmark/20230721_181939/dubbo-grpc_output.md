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
# Warmup Iteration   1: 4.378 ops/ms
# Warmup Iteration   2: 9.276 ops/ms
# Warmup Iteration   3: 10.131 ops/ms
Iteration   1: 10.523 ops/ms
Iteration   2: 10.746 ops/ms
Iteration   3: 10.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.633 ±(99.9%) 2.041 ops/ms [Average]
  (min, avg, max) = (10.523, 10.633, 10.746), stdev = 0.112
  CI (99.9%): [8.592, 12.674] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.810 ops/ms
# Warmup Iteration   2: 10.554 ops/ms
# Warmup Iteration   3: 11.015 ops/ms
Iteration   1: 10.930 ops/ms
Iteration   2: 11.210 ops/ms
Iteration   3: 11.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.073 ±(99.9%) 2.564 ops/ms [Average]
  (min, avg, max) = (10.930, 11.073, 11.210), stdev = 0.141
  CI (99.9%): [8.510, 13.637] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.060 ops/ms
# Warmup Iteration   2: 10.261 ops/ms
# Warmup Iteration   3: 10.885 ops/ms
Iteration   1: 10.775 ops/ms
Iteration   2: 10.884 ops/ms
Iteration   3: 10.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.792 ±(99.9%) 1.548 ops/ms [Average]
  (min, avg, max) = (10.717, 10.792, 10.884), stdev = 0.085
  CI (99.9%): [9.244, 12.340] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.602 ops/ms
# Warmup Iteration   2: 7.991 ops/ms
# Warmup Iteration   3: 8.162 ops/ms
Iteration   1: 8.414 ops/ms
Iteration   2: 8.246 ops/ms
Iteration   3: 8.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.369 ±(99.9%) 1.970 ops/ms [Average]
  (min, avg, max) = (8.246, 8.369, 8.448), stdev = 0.108
  CI (99.9%): [6.399, 10.339] (assumes normal distribution)


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.003 ms/op
Iteration   1: 2.887 ±(99.9%) 0.004 ms/op
Iteration   2: 2.971 ±(99.9%) 0.003 ms/op
Iteration   3: 2.919 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.925 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (2.887, 2.925, 2.971), stdev = 0.043
  CI (99.9%): [2.144, 3.707] (assumes normal distribution)


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.895 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.785 ±(99.9%) 0.003 ms/op
Iteration   1: 2.823 ±(99.9%) 0.003 ms/op
Iteration   2: 2.885 ±(99.9%) 0.004 ms/op
Iteration   3: 2.850 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.853 ±(99.9%) 0.565 ms/op [Average]
  (min, avg, max) = (2.823, 2.853, 2.885), stdev = 0.031
  CI (99.9%): [2.287, 3.418] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.860 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.003 ms/op
Iteration   1: 2.992 ±(99.9%) 0.003 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.987 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (2.976, 2.987, 2.994), stdev = 0.010
  CI (99.9%): [2.808, 3.166] (assumes normal distribution)


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
# Warmup Iteration   1: 4.972 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.013 ms/op
Iteration   1: 3.800 ±(99.9%) 0.015 ms/op
Iteration   2: 3.858 ±(99.9%) 0.058 ms/op
Iteration   3: 3.842 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.833 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (3.800, 3.833, 3.858), stdev = 0.030
  CI (99.9%): [3.283, 4.383] (assumes normal distribution)


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.221 ms/op
                 createUser·p0.9999: 12.518 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.468 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  10.001 ms/op
                 createUser·p0.9999: 20.238 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   3: 3.003 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.500 ms/op
                 createUser·p0.9999: 26.706 ms/op
                 createUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320758
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22851 
    [ 2.500,  5.000) = 296421 
    [ 5.000,  7.500) = 1052 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.982 ms/op
     p(99.9900) =     25.882 ms/op
     p(99.9990) =     26.797 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.824 ±(99.9%) 0.006 ms/op
Iteration   1: 2.850 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.173 ms/op
                 existUser·p0.9999: 12.063 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   2: 2.911 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.620 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.581 ms/op
                 existUser·p0.9999: 21.791 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   3: 2.846 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.224 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.653 ms/op
                 existUser·p0.9999: 14.643 ms/op
                 existUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334671
  mean =      2.868 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51065 
    [ 2.500,  5.000) = 282420 
    [ 5.000,  7.500) = 885 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.224 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      6.971 ms/op
     p(99.9900) =     16.427 ms/op
     p(99.9990) =     21.910 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.573 ms/op
                 getUser·p0.9999: 12.145 ms/op
                 getUser·p1.00:   12.321 ms/op

Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.031 ms/op
                 getUser·p0.9999: 14.151 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.518 ms/op
                 getUser·p0.9999: 13.517 ms/op
                 getUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322292
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2018 
    [ 1.250,  2.500) = 25333 
    [ 2.500,  3.750) = 280412 
    [ 3.750,  5.000) = 13488 
    [ 5.000,  6.250) = 659 
    [ 6.250,  7.500) = 154 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.631 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     15.190 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


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
# Warmup Iteration   1: 4.867 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.010 ms/op
Iteration   1: 3.918 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  14.109 ms/op
                 listUser·p0.9999: 18.405 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   2: 3.809 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 15.627 ms/op
                 listUser·p1.00:   16.663 ms/op

Iteration   3: 3.855 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.787 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  16.166 ms/op
                 listUser·p0.9999: 23.714 ms/op
                 listUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248503
  mean =      3.860 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3427 
    [ 2.500,  5.000) = 226262 
    [ 5.000,  7.500) = 17726 
    [ 7.500, 10.000) = 654 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     14.229 ms/op
     p(99.9900) =     22.231 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.633 ± 2.041  ops/ms
ClientGrpc.existUser                       thrpt       3  11.073 ± 2.564  ops/ms
ClientGrpc.getUser                         thrpt       3  10.792 ± 1.548  ops/ms
ClientGrpc.listUser                        thrpt       3   8.369 ± 1.970  ops/ms
ClientGrpc.createUser                       avgt       3   2.925 ± 0.782   ms/op
ClientGrpc.existUser                        avgt       3   2.853 ± 0.565   ms/op
ClientGrpc.getUser                          avgt       3   2.987 ± 0.179   ms/op
ClientGrpc.listUser                         avgt       3   3.833 ± 0.550   ms/op
ClientGrpc.createUser                     sample  320758   2.992 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.468           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.432           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.982           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.882           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.837           ms/op
ClientGrpc.existUser                      sample  334671   2.868 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.224           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.971           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.427           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.987           ms/op
ClientGrpc.getUser                        sample  322292   2.979 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.618           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.631           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.418           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.319           ms/op
ClientGrpc.listUser                       sample  248503   3.860 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.787           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.229           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.231           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.609           ms/op
