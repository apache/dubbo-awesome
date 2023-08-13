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
# Warmup Iteration   1: 3.811 ops/ms
# Warmup Iteration   2: 8.375 ops/ms
# Warmup Iteration   3: 9.847 ops/ms
Iteration   1: 10.235 ops/ms
Iteration   2: 10.459 ops/ms
Iteration   3: 10.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.367 ±(99.9%) 2.138 ops/ms [Average]
  (min, avg, max) = (10.235, 10.367, 10.459), stdev = 0.117
  CI (99.9%): [8.229, 12.506] (assumes normal distribution)


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
# Warmup Iteration   1: 7.061 ops/ms
# Warmup Iteration   2: 10.444 ops/ms
# Warmup Iteration   3: 10.850 ops/ms
Iteration   1: 10.810 ops/ms
Iteration   2: 10.815 ops/ms
Iteration   3: 10.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.831 ±(99.9%) 0.570 ops/ms [Average]
  (min, avg, max) = (10.810, 10.831, 10.867), stdev = 0.031
  CI (99.9%): [10.261, 11.400] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.989 ops/ms
# Warmup Iteration   2: 9.825 ops/ms
# Warmup Iteration   3: 10.263 ops/ms
Iteration   1: 10.342 ops/ms
Iteration   2: 10.242 ops/ms
Iteration   3: 10.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.348 ±(99.9%) 1.982 ops/ms [Average]
  (min, avg, max) = (10.242, 10.348, 10.459), stdev = 0.109
  CI (99.9%): [8.366, 12.329] (assumes normal distribution)


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
# Warmup Iteration   1: 5.326 ops/ms
# Warmup Iteration   2: 7.491 ops/ms
# Warmup Iteration   3: 7.729 ops/ms
Iteration   1: 7.799 ops/ms
Iteration   2: 7.763 ops/ms
Iteration   3: 7.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.826 ±(99.9%) 1.455 ops/ms [Average]
  (min, avg, max) = (7.763, 7.826, 7.916), stdev = 0.080
  CI (99.9%): [6.371, 9.281] (assumes normal distribution)


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.300 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.003 ms/op
Iteration   1: 3.125 ±(99.9%) 0.004 ms/op
Iteration   2: 3.130 ±(99.9%) 0.004 ms/op
Iteration   3: 3.124 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.126 ±(99.9%) 0.064 ms/op [Average]
  (min, avg, max) = (3.124, 3.126, 3.130), stdev = 0.003
  CI (99.9%): [3.063, 3.190] (assumes normal distribution)


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.003 ms/op
Iteration   1: 2.933 ±(99.9%) 0.002 ms/op
Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
Iteration   3: 2.967 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.951 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (2.933, 2.951, 2.967), stdev = 0.017
  CI (99.9%): [2.639, 3.263] (assumes normal distribution)


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
# Warmup Iteration   1: 4.520 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.002 ms/op
Iteration   1: 3.108 ±(99.9%) 0.003 ms/op
Iteration   2: 3.093 ±(99.9%) 0.003 ms/op
Iteration   3: 3.090 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.097 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.090, 3.097, 3.108), stdev = 0.010
  CI (99.9%): [2.920, 3.274] (assumes normal distribution)


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
# Warmup Iteration   1: 5.077 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.026 ms/op
Iteration   1: 4.094 ±(99.9%) 0.017 ms/op
Iteration   2: 4.052 ±(99.9%) 0.012 ms/op
Iteration   3: 4.071 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.072 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (4.052, 4.072, 4.094), stdev = 0.021
  CI (99.9%): [3.688, 4.457] (assumes normal distribution)


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
Iteration   1: 3.175 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  9.054 ms/op
                 createUser·p0.9999: 17.069 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.866 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 16.590 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  10.565 ms/op
                 createUser·p0.9999: 21.137 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306720
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15823 
    [ 2.500,  5.000) = 288069 
    [ 5.000,  7.500) = 1904 
    [ 7.500, 10.000) = 659 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     18.841 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.007 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.907 ms/op
                 existUser·p0.999:  8.946 ms/op
                 existUser·p0.9999: 21.135 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   2: 2.941 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.510 ms/op
                 existUser·p0.9999: 14.930 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   3: 3.031 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  9.354 ms/op
                 existUser·p0.9999: 19.180 ms/op
                 existUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321600
  mean =      2.984 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28356 
    [ 2.500,  5.000) = 290689 
    [ 5.000,  7.500) = 1985 
    [ 7.500, 10.000) = 366 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =      8.510 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     21.416 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 4.408 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
Iteration   1: 3.107 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 21.103 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   2: 3.093 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  9.683 ms/op
                 getUser·p0.9999: 23.287 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.440 ms/op
                 getUser·p0.9999: 24.674 ms/op
                 getUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310107
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16874 
    [ 2.500,  5.000) = 290411 
    [ 5.000,  7.500) = 2071 
    [ 7.500, 10.000) = 476 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 5.236 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.012 ms/op
Iteration   1: 4.153 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.250 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 4.105 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  20.060 ms/op
                 listUser·p0.9999: 24.689 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   3: 4.082 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  17.472 ms/op
                 listUser·p0.9999: 25.035 ms/op
                 listUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233237
  mean =      4.113 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2631 
    [ 2.500,  5.000) = 201004 
    [ 5.000,  7.500) = 27380 
    [ 7.500, 10.000) = 1718 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     17.319 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     25.352 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.367 ± 2.138  ops/ms
ClientGrpc.existUser                       thrpt       3  10.831 ± 0.570  ops/ms
ClientGrpc.getUser                         thrpt       3  10.348 ± 1.982  ops/ms
ClientGrpc.listUser                        thrpt       3   7.826 ± 1.455  ops/ms
ClientGrpc.createUser                       avgt       3   3.126 ± 0.064   ms/op
ClientGrpc.existUser                        avgt       3   2.951 ± 0.312   ms/op
ClientGrpc.getUser                          avgt       3   3.097 ± 0.177   ms/op
ClientGrpc.listUser                         avgt       3   4.072 ± 0.385   ms/op
ClientGrpc.createUser                     sample  306720   3.132 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.644           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.940           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.568           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.841           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.791           ms/op
ClientGrpc.existUser                      sample  321600   2.984 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.701           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.784           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.510           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.874           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.496           ms/op
ClientGrpc.getUser                        sample  310107   3.094 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.597           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.907           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.437           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.248           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.904           ms/op
ClientGrpc.listUser                       sample  233237   4.113 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.900           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.119           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.447           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.319           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.805           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.395           ms/op
