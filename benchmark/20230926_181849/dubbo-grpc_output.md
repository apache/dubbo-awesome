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
# Warmup Iteration   1: 2.285 ops/ms
# Warmup Iteration   2: 5.500 ops/ms
# Warmup Iteration   3: 7.679 ops/ms
Iteration   1: 7.682 ops/ms
Iteration   2: 7.898 ops/ms
Iteration   3: 7.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.772 ±(99.9%) 2.042 ops/ms [Average]
  (min, avg, max) = (7.682, 7.772, 7.898), stdev = 0.112
  CI (99.9%): [5.730, 9.815] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.562 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 8.335 ops/ms
Iteration   1: 8.645 ops/ms
Iteration   2: 8.883 ops/ms
Iteration   3: 8.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.655 ±(99.9%) 4.067 ops/ms [Average]
  (min, avg, max) = (8.438, 8.655, 8.883), stdev = 0.223
  CI (99.9%): [4.588, 12.722] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.194 ops/ms
# Warmup Iteration   2: 7.362 ops/ms
# Warmup Iteration   3: 7.777 ops/ms
Iteration   1: 7.771 ops/ms
Iteration   2: 7.899 ops/ms
Iteration   3: 7.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.868 ±(99.9%) 1.574 ops/ms [Average]
  (min, avg, max) = (7.771, 7.868, 7.935), stdev = 0.086
  CI (99.9%): [6.294, 9.443] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.608 ops/ms
# Warmup Iteration   2: 5.737 ops/ms
# Warmup Iteration   3: 6.006 ops/ms
Iteration   1: 6.164 ops/ms
Iteration   2: 6.085 ops/ms
Iteration   3: 5.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.075 ±(99.9%) 1.718 ops/ms [Average]
  (min, avg, max) = (5.976, 6.075, 6.164), stdev = 0.094
  CI (99.9%): [4.356, 7.793] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.023 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.018 ms/op
Iteration   1: 4.226 ±(99.9%) 0.004 ms/op
Iteration   2: 4.073 ±(99.9%) 0.008 ms/op
Iteration   3: 4.165 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.155 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (4.073, 4.155, 4.226), stdev = 0.077
  CI (99.9%): [2.752, 5.558] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.035 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.003 ms/op
Iteration   1: 3.676 ±(99.9%) 0.006 ms/op
Iteration   2: 3.756 ±(99.9%) 0.005 ms/op
Iteration   3: 3.721 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.718 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (3.676, 3.718, 3.756), stdev = 0.040
  CI (99.9%): [2.985, 4.451] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.884 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.175 ±(99.9%) 0.010 ms/op
Iteration   1: 4.114 ±(99.9%) 0.004 ms/op
Iteration   2: 4.018 ±(99.9%) 0.005 ms/op
Iteration   3: 4.050 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.060 ±(99.9%) 0.893 ms/op [Average]
  (min, avg, max) = (4.018, 4.060, 4.114), stdev = 0.049
  CI (99.9%): [3.168, 4.953] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.919 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.894 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.269 ±(99.9%) 0.034 ms/op
Iteration   1: 5.303 ±(99.9%) 0.012 ms/op
Iteration   2: 5.251 ±(99.9%) 0.023 ms/op
Iteration   3: 5.162 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.239 ±(99.9%) 1.301 ms/op [Average]
  (min, avg, max) = (5.162, 5.239, 5.303), stdev = 0.071
  CI (99.9%): [3.938, 6.540] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.524 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.541 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.016 ms/op
Iteration   1: 4.076 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   5.210 ms/op
                 createUser·p0.95:   5.685 ms/op
                 createUser·p0.99:   8.217 ms/op
                 createUser·p0.999:  15.074 ms/op
                 createUser·p0.9999: 19.933 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   2: 4.063 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  14.082 ms/op
                 createUser·p0.9999: 21.172 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   3: 4.071 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   3.965 ms/op
                 createUser·p0.90:   5.071 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   7.741 ms/op
                 createUser·p0.999:  23.527 ms/op
                 createUser·p0.9999: 26.051 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 235841
  mean =      4.070 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11475 
    [ 2.500,  5.000) = 196315 
    [ 5.000,  7.500) = 25488 
    [ 7.500, 10.000) = 1630 
    [10.000, 12.500) = 501 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     14.828 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     26.224 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.950 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.013 ms/op
Iteration   1: 3.741 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   7.848 ms/op
                 existUser·p0.999:  14.066 ms/op
                 existUser·p0.9999: 18.055 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   2: 3.753 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  17.394 ms/op
                 existUser·p0.9999: 20.234 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   3: 3.886 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.300 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  10.181 ms/op
                 existUser·p0.9999: 28.362 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 252943
  mean =      3.792 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18317 
    [ 2.500,  5.000) = 216415 
    [ 5.000,  7.500) = 15897 
    [ 7.500, 10.000) = 1521 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     15.009 ms/op
     p(99.9900) =     27.645 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.552 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.489 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.176 ±(99.9%) 0.012 ms/op
Iteration   1: 4.037 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   6.707 ms/op
                 getUser·p0.999:  12.201 ms/op
                 getUser·p0.9999: 16.810 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   7.649 ms/op
                 getUser·p0.999:  15.815 ms/op
                 getUser·p0.9999: 19.440 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   3: 4.151 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   7.733 ms/op
                 getUser·p0.999:  16.187 ms/op
                 getUser·p0.9999: 21.388 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235124
  mean =      4.084 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6553 
    [ 2.500,  5.000) = 202784 
    [ 5.000,  7.500) = 23641 
    [ 7.500, 10.000) = 1439 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.313 ms/op
     p(99.9000) =     15.004 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     22.598 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 8.568 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 5.573 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.213 ±(99.9%) 0.022 ms/op
Iteration   1: 5.247 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   4.932 ms/op
                 listUser·p0.90:   7.021 ms/op
                 listUser·p0.95:   7.979 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  16.909 ms/op
                 listUser·p0.9999: 28.112 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   2: 5.168 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   8.069 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  18.547 ms/op
                 listUser·p0.9999: 21.092 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   3: 5.276 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  21.803 ms/op
                 listUser·p0.9999: 35.914 ms/op
                 listUser·p1.00:   38.928 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 183533
  mean =      5.230 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 724 
    [ 2.500,  5.000) = 99901 
    [ 5.000,  7.500) = 69235 
    [ 7.500, 10.000) = 11004 
    [10.000, 12.500) = 1643 
    [12.500, 15.000) = 491 
    [15.000, 17.500) = 259 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     10.808 ms/op
     p(99.9000) =     18.986 ms/op
     p(99.9900) =     28.286 ms/op
     p(99.9990) =     38.217 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.772 ± 2.042  ops/ms
ClientGrpc.existUser                       thrpt       3   8.655 ± 4.067  ops/ms
ClientGrpc.getUser                         thrpt       3   7.868 ± 1.574  ops/ms
ClientGrpc.listUser                        thrpt       3   6.075 ± 1.718  ops/ms
ClientGrpc.createUser                       avgt       3   4.155 ± 1.403   ms/op
ClientGrpc.existUser                        avgt       3   3.718 ± 0.733   ms/op
ClientGrpc.getUser                          avgt       3   4.060 ± 0.893   ms/op
ClientGrpc.listUser                         avgt       3   5.239 ± 1.301   ms/op
ClientGrpc.createUser                     sample  235841   4.070 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.883           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.981           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.120           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.684           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.828           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.805           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.313           ms/op
ClientGrpc.existUser                      sample  252943   3.792 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.744           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.776           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.243           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.307           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.009           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.645           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.606           ms/op
ClientGrpc.getUser                        sample  235124   4.084 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.810           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.063           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.472           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.313           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.004           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.497           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.101           ms/op
ClientGrpc.listUser                       sample  183533   5.230 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.016           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.036           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.986           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.286           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.928           ms/op
