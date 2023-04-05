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
# Warmup Iteration   1: 4.730 ops/ms
# Warmup Iteration   2: 9.510 ops/ms
# Warmup Iteration   3: 10.452 ops/ms
Iteration   1: 10.439 ops/ms
Iteration   2: 10.663 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.601 ±(99.9%) 2.589 ops/ms [Average]
  (min, avg, max) = (10.439, 10.601, 10.702), stdev = 0.142
  CI (99.9%): [8.013, 13.190] (assumes normal distribution)


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
# Warmup Iteration   1: 8.127 ops/ms
# Warmup Iteration   2: 10.711 ops/ms
# Warmup Iteration   3: 11.087 ops/ms
Iteration   1: 11.227 ops/ms
Iteration   2: 11.372 ops/ms
Iteration   3: 11.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.333 ±(99.9%) 1.698 ops/ms [Average]
  (min, avg, max) = (11.227, 11.333, 11.400), stdev = 0.093
  CI (99.9%): [9.635, 13.031] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.028 ops/ms
# Warmup Iteration   2: 10.373 ops/ms
# Warmup Iteration   3: 10.680 ops/ms
Iteration   1: 10.771 ops/ms
Iteration   2: 10.726 ops/ms
Iteration   3: 10.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.759 ±(99.9%) 0.535 ops/ms [Average]
  (min, avg, max) = (10.726, 10.759, 10.781), stdev = 0.029
  CI (99.9%): [10.224, 11.294] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.994 ops/ms
# Warmup Iteration   2: 8.103 ops/ms
# Warmup Iteration   3: 8.425 ops/ms
Iteration   1: 8.438 ops/ms
Iteration   2: 8.236 ops/ms
Iteration   3: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.343 ±(99.9%) 1.851 ops/ms [Average]
  (min, avg, max) = (8.236, 8.343, 8.438), stdev = 0.101
  CI (99.9%): [6.492, 10.194] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.706 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.003 ms/op
Iteration   1: 2.992 ±(99.9%) 0.003 ms/op
Iteration   2: 2.975 ±(99.9%) 0.002 ms/op
Iteration   3: 2.997 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.988 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.975, 2.988, 2.997), stdev = 0.012
  CI (99.9%): [2.773, 3.202] (assumes normal distribution)


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.902 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.004 ms/op
Iteration   1: 2.813 ±(99.9%) 0.003 ms/op
Iteration   2: 2.870 ±(99.9%) 0.003 ms/op
Iteration   3: 2.886 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.856 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (2.813, 2.856, 2.886), stdev = 0.038
  CI (99.9%): [2.155, 3.558] (assumes normal distribution)


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.003 ms/op
Iteration   1: 2.930 ±(99.9%) 0.003 ms/op
Iteration   2: 2.953 ±(99.9%) 0.003 ms/op
Iteration   3: 2.944 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.943 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.930, 2.943, 2.953), stdev = 0.012
  CI (99.9%): [2.732, 3.153] (assumes normal distribution)


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
# Warmup Iteration   1: 5.200 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.010 ms/op
Iteration   1: 3.814 ±(99.9%) 0.021 ms/op
Iteration   2: 3.787 ±(99.9%) 0.009 ms/op
Iteration   3: 3.797 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.799 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (3.787, 3.799, 3.814), stdev = 0.014
  CI (99.9%): [3.545, 4.054] (assumes normal distribution)


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 2.951 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.495 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   3.420 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.650 ms/op
                 createUser·p0.9999: 11.783 ms/op
                 createUser·p1.00:   12.009 ms/op

Iteration   2: 2.960 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  6.283 ms/op
                 createUser·p0.9999: 17.269 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  8.683 ms/op
                 createUser·p0.9999: 17.836 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323558
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24193 
    [ 2.500,  5.000) = 297954 
    [ 5.000,  7.500) = 998 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.895 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     20.628 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.883 ±(99.9%) 0.006 ms/op
Iteration   1: 2.941 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  7.236 ms/op
                 existUser·p0.9999: 11.407 ms/op
                 existUser·p1.00:   11.796 ms/op

Iteration   2: 2.830 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.244 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  6.455 ms/op
                 existUser·p0.9999: 13.692 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.872 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.028 ms/op
                 existUser·p0.9999: 24.665 ms/op
                 existUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333096
  mean =      2.880 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32365 
    [ 2.500,  5.000) = 299460 
    [ 5.000,  7.500) = 995 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      4.195 ms/op
     p(99.9000) =      6.996 ms/op
     p(99.9900) =     22.133 ms/op
     p(99.9990) =     25.013 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 3.759 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.376 ms/op
                 getUser·p0.9999: 11.518 ms/op
                 getUser·p1.00:   11.665 ms/op

Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  10.072 ms/op
                 getUser·p0.9999: 13.099 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.203 ms/op
                 getUser·p0.999:  6.803 ms/op
                 getUser·p0.9999: 20.616 ms/op
                 getUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319564
  mean =      3.002 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28777 
    [ 2.500,  5.000) = 289681 
    [ 5.000,  7.500) = 759 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.856 ms/op
     p(99.9900) =     19.960 ms/op
     p(99.9990) =     21.963 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 4.804 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
Iteration   1: 3.828 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 19.743 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 3.833 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  16.738 ms/op
                 listUser·p0.9999: 22.894 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 3.841 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  15.095 ms/op
                 listUser·p0.9999: 21.801 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250525
  mean =      3.834 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7721 
    [ 2.500,  5.000) = 221119 
    [ 5.000,  7.500) = 20567 
    [ 7.500, 10.000) = 656 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     15.818 ms/op
     p(99.9900) =     21.917 ms/op
     p(99.9990) =     22.987 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.601 ± 2.589  ops/ms
ClientGrpc.existUser                       thrpt       3  11.333 ± 1.698  ops/ms
ClientGrpc.getUser                         thrpt       3  10.759 ± 0.535  ops/ms
ClientGrpc.listUser                        thrpt       3   8.343 ± 1.851  ops/ms
ClientGrpc.createUser                       avgt       3   2.988 ± 0.215   ms/op
ClientGrpc.existUser                        avgt       3   2.856 ± 0.702   ms/op
ClientGrpc.getUser                          avgt       3   2.943 ± 0.210   ms/op
ClientGrpc.listUser                         avgt       3   3.799 ± 0.255   ms/op
ClientGrpc.createUser                     sample  323558   2.967 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.495           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.383           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.895           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.302           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.775           ms/op
ClientGrpc.existUser                      sample  333096   2.880 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.597           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.195           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.996           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.133           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.100           ms/op
ClientGrpc.getUser                        sample  319564   3.002 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.582           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.856           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.960           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.708           ms/op
ClientGrpc.listUser                       sample  250525   3.834 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.779           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.818           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.917           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.036           ms/op
