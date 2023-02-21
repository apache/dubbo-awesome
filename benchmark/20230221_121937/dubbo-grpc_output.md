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
# Warmup Iteration   1: 4.878 ops/ms
# Warmup Iteration   2: 9.303 ops/ms
# Warmup Iteration   3: 10.824 ops/ms
Iteration   1: 10.703 ops/ms
Iteration   2: 10.320 ops/ms
Iteration   3: 10.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.474 ±(99.9%) 3.691 ops/ms [Average]
  (min, avg, max) = (10.320, 10.474, 10.703), stdev = 0.202
  CI (99.9%): [6.783, 14.165] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.979 ops/ms
# Warmup Iteration   2: 11.073 ops/ms
# Warmup Iteration   3: 10.741 ops/ms
Iteration   1: 10.927 ops/ms
Iteration   2: 11.125 ops/ms
Iteration   3: 10.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.904 ±(99.9%) 4.247 ops/ms [Average]
  (min, avg, max) = (10.661, 10.904, 11.125), stdev = 0.233
  CI (99.9%): [6.657, 15.151] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.295 ops/ms
# Warmup Iteration   2: 10.151 ops/ms
# Warmup Iteration   3: 10.418 ops/ms
Iteration   1: 10.307 ops/ms
Iteration   2: 9.930 ops/ms
Iteration   3: 10.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.265 ±(99.9%) 5.777 ops/ms [Average]
  (min, avg, max) = (9.930, 10.265, 10.559), stdev = 0.317
  CI (99.9%): [4.488, 16.042] (assumes normal distribution)


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
# Warmup Iteration   1: 5.676 ops/ms
# Warmup Iteration   2: 7.835 ops/ms
# Warmup Iteration   3: 7.983 ops/ms
Iteration   1: 8.068 ops/ms
Iteration   2: 7.943 ops/ms
Iteration   3: 7.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.979 ±(99.9%) 1.421 ops/ms [Average]
  (min, avg, max) = (7.926, 7.979, 8.068), stdev = 0.078
  CI (99.9%): [6.558, 9.400] (assumes normal distribution)


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
# Warmup Iteration   1: 3.977 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.002 ms/op
Iteration   1: 3.170 ±(99.9%) 0.002 ms/op
Iteration   2: 3.212 ±(99.9%) 0.003 ms/op
Iteration   3: 3.107 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.163 ±(99.9%) 0.960 ms/op [Average]
  (min, avg, max) = (3.107, 3.163, 3.212), stdev = 0.053
  CI (99.9%): [2.203, 4.123] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.540 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.003 ms/op
Iteration   1: 2.956 ±(99.9%) 0.003 ms/op
Iteration   2: 2.920 ±(99.9%) 0.003 ms/op
Iteration   3: 3.034 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.970 ±(99.9%) 1.055 ms/op [Average]
  (min, avg, max) = (2.920, 2.970, 3.034), stdev = 0.058
  CI (99.9%): [1.914, 4.025] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.002 ms/op
Iteration   1: 3.033 ±(99.9%) 0.002 ms/op
Iteration   2: 3.052 ±(99.9%) 0.002 ms/op
Iteration   3: 3.059 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.048 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (3.033, 3.048, 3.059), stdev = 0.014
  CI (99.9%): [2.798, 3.298] (assumes normal distribution)


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
# Warmup Iteration   1: 4.560 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.029 ms/op
Iteration   1: 3.998 ±(99.9%) 0.010 ms/op
Iteration   2: 3.914 ±(99.9%) 0.012 ms/op
Iteration   3: 4.149 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.020 ±(99.9%) 2.172 ms/op [Average]
  (min, avg, max) = (3.914, 4.020, 4.149), stdev = 0.119
  CI (99.9%): [1.848, 6.193] (assumes normal distribution)


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
# Warmup Iteration   1: 4.217 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.005 ms/op
Iteration   1: 3.101 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  6.816 ms/op
                 createUser·p0.9999: 11.087 ms/op
                 createUser·p1.00:   11.338 ms/op

Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.769 ms/op
                 createUser·p0.9999: 12.875 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.466 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.791 ms/op
                 createUser·p0.9999: 23.986 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309846
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25098 
    [ 2.500,  5.000) = 283697 
    [ 5.000,  7.500) = 737 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.643 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     24.606 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.803 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  5.144 ms/op
                 existUser·p0.9999: 14.877 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  9.417 ms/op
                 existUser·p0.9999: 18.102 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   3: 2.941 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.048 ms/op
                 existUser·p0.9999: 24.453 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321716
  mean =      2.985 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43091 
    [ 2.500,  5.000) = 277623 
    [ 5.000,  7.500) = 771 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     22.721 ms/op
     p(99.9990) =     24.765 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 3.786 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.007 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.350 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  6.568 ms/op
                 getUser·p0.9999: 23.364 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.963 ms/op
                 getUser·p0.9999: 21.103 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   3: 3.097 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.522 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.761 ms/op
                 getUser·p0.9999: 27.027 ms/op
                 getUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313676
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23877 
    [ 2.500,  5.000) = 289037 
    [ 5.000,  7.500) = 485 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.350 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.176 ms/op
     p(99.9900) =     25.687 ms/op
     p(99.9990) =     27.737 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 5.343 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.012 ms/op
Iteration   1: 3.963 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  17.246 ms/op
                 listUser·p0.9999: 20.248 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   2: 3.944 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.565 ms/op
                 listUser·p0.9999: 18.179 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 3.932 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  14.658 ms/op
                 listUser·p0.9999: 25.284 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243117
  mean =      3.946 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3473 
    [ 2.500,  5.000) = 217958 
    [ 5.000,  7.500) = 20675 
    [ 7.500, 10.000) = 583 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     24.041 ms/op
     p(99.9990) =     25.746 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.474 ± 3.691  ops/ms
ClientGrpc.existUser                       thrpt       3  10.904 ± 4.247  ops/ms
ClientGrpc.getUser                         thrpt       3  10.265 ± 5.777  ops/ms
ClientGrpc.listUser                        thrpt       3   7.979 ± 1.421  ops/ms
ClientGrpc.createUser                       avgt       3   3.163 ± 0.960   ms/op
ClientGrpc.existUser                        avgt       3   2.970 ± 1.055   ms/op
ClientGrpc.getUser                          avgt       3   3.048 ± 0.250   ms/op
ClientGrpc.listUser                         avgt       3   4.020 ± 2.172   ms/op
ClientGrpc.createUser                     sample  309846   3.099 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.466           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.643           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.233           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.199           ms/op
ClientGrpc.existUser                      sample  321716   2.985 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.644           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.881           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.721           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.904           ms/op
ClientGrpc.getUser                        sample  313676   3.058 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.350           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.176           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.687           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.000           ms/op
ClientGrpc.listUser                       sample  243117   3.946 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.930           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.942           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.041           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
