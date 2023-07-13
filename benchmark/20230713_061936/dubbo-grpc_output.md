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
# Warmup Iteration   1: 4.741 ops/ms
# Warmup Iteration   2: 9.245 ops/ms
# Warmup Iteration   3: 10.242 ops/ms
Iteration   1: 10.798 ops/ms
Iteration   2: 10.675 ops/ms
Iteration   3: 10.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.691 ±(99.9%) 1.823 ops/ms [Average]
  (min, avg, max) = (10.600, 10.691, 10.798), stdev = 0.100
  CI (99.9%): [8.868, 12.514] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 8.107 ops/ms
# Warmup Iteration   2: 10.860 ops/ms
# Warmup Iteration   3: 11.122 ops/ms
Iteration   1: 11.313 ops/ms
Iteration   2: 11.319 ops/ms
Iteration   3: 11.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.267 ±(99.9%) 1.553 ops/ms [Average]
  (min, avg, max) = (11.169, 11.267, 11.319), stdev = 0.085
  CI (99.9%): [9.714, 12.820] (assumes normal distribution)


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
# Warmup Iteration   1: 7.567 ops/ms
# Warmup Iteration   2: 10.609 ops/ms
# Warmup Iteration   3: 10.852 ops/ms
Iteration   1: 10.844 ops/ms
Iteration   2: 10.909 ops/ms
Iteration   3: 10.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.868 ±(99.9%) 0.645 ops/ms [Average]
  (min, avg, max) = (10.844, 10.868, 10.909), stdev = 0.035
  CI (99.9%): [10.223, 11.513] (assumes normal distribution)


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
# Warmup Iteration   1: 5.964 ops/ms
# Warmup Iteration   2: 8.040 ops/ms
# Warmup Iteration   3: 8.220 ops/ms
Iteration   1: 8.361 ops/ms
Iteration   2: 8.340 ops/ms
Iteration   3: 8.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.361 ±(99.9%) 0.377 ops/ms [Average]
  (min, avg, max) = (8.340, 8.361, 8.381), stdev = 0.021
  CI (99.9%): [7.984, 8.737] (assumes normal distribution)


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.004 ms/op
Iteration   1: 2.973 ±(99.9%) 0.003 ms/op
Iteration   2: 2.997 ±(99.9%) 0.003 ms/op
Iteration   3: 2.967 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.979 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.967, 2.979, 2.997), stdev = 0.016
  CI (99.9%): [2.693, 3.265] (assumes normal distribution)


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.876 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.003 ms/op
Iteration   1: 2.814 ±(99.9%) 0.004 ms/op
Iteration   2: 2.803 ±(99.9%) 0.003 ms/op
Iteration   3: 2.855 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.824 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (2.803, 2.824, 2.855), stdev = 0.028
  CI (99.9%): [2.321, 3.327] (assumes normal distribution)


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.002 ms/op
Iteration   2: 3.014 ±(99.9%) 0.003 ms/op
Iteration   3: 3.001 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.010 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (3.001, 3.010, 3.016), stdev = 0.008
  CI (99.9%): [2.865, 3.155] (assumes normal distribution)


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.023 ms/op
Iteration   1: 3.881 ±(99.9%) 0.026 ms/op
Iteration   2: 3.783 ±(99.9%) 0.004 ms/op
Iteration   3: 3.889 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.851 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (3.783, 3.851, 3.889), stdev = 0.059
  CI (99.9%): [2.775, 4.926] (assumes normal distribution)


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.466 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.394 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   5.054 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  11.698 ms/op
                 createUser·p0.9999: 42.583 ms/op
                 createUser·p1.00:   43.188 ms/op

Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  12.554 ms/op
                 createUser·p0.9999: 20.197 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  10.623 ms/op
                 createUser·p0.9999: 25.440 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303380
  mean =      3.164 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 292841 
    [ 5.000, 10.000) = 10050 
    [10.000, 15.000) = 368 
    [15.000, 20.000) = 41 
    [20.000, 25.000) = 37 
    [25.000, 30.000) = 11 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.394 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     11.528 ms/op
     p(99.9900) =     40.763 ms/op
     p(99.9990) =     43.051 ms/op
     p(99.9999) =     43.188 ms/op
    p(100.0000) =     43.188 ms/op


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.911 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.887 ±(99.9%) 0.005 ms/op
Iteration   1: 2.857 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  5.621 ms/op
                 existUser·p0.9999: 11.299 ms/op
                 existUser·p1.00:   11.551 ms/op

Iteration   2: 2.844 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  10.273 ms/op
                 existUser·p0.9999: 14.594 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   3: 2.850 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.676 ms/op
                 existUser·p0.9999: 13.207 ms/op
                 existUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336615
  mean =      2.850 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2968 
    [ 1.250,  2.500) = 52874 
    [ 2.500,  3.750) = 270475 
    [ 3.750,  5.000) = 9264 
    [ 5.000,  6.250) = 675 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      6.439 ms/op
     p(99.9900) =     13.639 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.376 ms/op
                 getUser·p0.9999: 12.524 ms/op
                 getUser·p1.00:   12.534 ms/op

Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.573 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.290 ms/op
                 getUser·p0.9999: 12.934 ms/op
                 getUser·p1.00:   13.091 ms/op

Iteration   3: 3.012 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.670 ms/op
                 getUser·p0.9999: 18.014 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317639
  mean =      3.022 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1266 
    [ 1.250,  2.500) = 17335 
    [ 2.500,  3.750) = 286690 
    [ 3.750,  5.000) = 11558 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 185 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.561 ms/op
     p(99.9900) =     15.486 ms/op
     p(99.9990) =     18.601 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.789 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.011 ms/op
Iteration   1: 3.873 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  12.194 ms/op
                 listUser·p0.9999: 17.129 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   2: 3.920 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.671 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 19.125 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.557 ms/op
                 listUser·p0.999:  13.577 ms/op
                 listUser·p0.9999: 27.115 ms/op
                 listUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246870
  mean =      3.889 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5893 
    [ 2.500,  5.000) = 217644 
    [ 5.000,  7.500) = 22251 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     13.896 ms/op
     p(99.9900) =     26.356 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.691 ± 1.823  ops/ms
ClientGrpc.existUser                       thrpt       3  11.267 ± 1.553  ops/ms
ClientGrpc.getUser                         thrpt       3  10.868 ± 0.645  ops/ms
ClientGrpc.listUser                        thrpt       3   8.361 ± 0.377  ops/ms
ClientGrpc.createUser                       avgt       3   2.979 ± 0.286   ms/op
ClientGrpc.existUser                        avgt       3   2.824 ± 0.503   ms/op
ClientGrpc.getUser                          avgt       3   3.010 ± 0.145   ms/op
ClientGrpc.listUser                         avgt       3   3.851 ± 1.075   ms/op
ClientGrpc.createUser                     sample  303380   3.164 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.394           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.103           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.528           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          40.763           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          43.188           ms/op
ClientGrpc.existUser                      sample  336615   2.850 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.519           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.439           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.639           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.991           ms/op
ClientGrpc.getUser                        sample  317639   3.022 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.573           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.561           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.486           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.678           ms/op
ClientGrpc.listUser                       sample  246870   3.889 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.671           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.896           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.356           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.427           ms/op
