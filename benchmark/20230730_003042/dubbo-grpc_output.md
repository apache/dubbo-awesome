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
# Warmup Iteration   1: 3.654 ops/ms
# Warmup Iteration   2: 8.068 ops/ms
# Warmup Iteration   3: 9.628 ops/ms
Iteration   1: 9.967 ops/ms
Iteration   2: 10.079 ops/ms
Iteration   3: 10.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.090 ±(99.9%) 2.356 ops/ms [Average]
  (min, avg, max) = (9.967, 10.090, 10.224), stdev = 0.129
  CI (99.9%): [7.734, 12.446] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.523 ops/ms
# Warmup Iteration   2: 9.893 ops/ms
# Warmup Iteration   3: 10.521 ops/ms
Iteration   1: 10.521 ops/ms
Iteration   2: 10.628 ops/ms
Iteration   3: 10.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.631 ±(99.9%) 2.033 ops/ms [Average]
  (min, avg, max) = (10.521, 10.631, 10.744), stdev = 0.111
  CI (99.9%): [8.598, 12.664] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.136 ops/ms
# Warmup Iteration   2: 9.929 ops/ms
# Warmup Iteration   3: 10.116 ops/ms
Iteration   1: 10.321 ops/ms
Iteration   2: 10.407 ops/ms
Iteration   3: 10.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.420 ±(99.9%) 1.939 ops/ms [Average]
  (min, avg, max) = (10.321, 10.420, 10.532), stdev = 0.106
  CI (99.9%): [8.481, 12.359] (assumes normal distribution)


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
# Warmup Iteration   1: 5.118 ops/ms
# Warmup Iteration   2: 7.095 ops/ms
# Warmup Iteration   3: 7.514 ops/ms
Iteration   1: 7.705 ops/ms
Iteration   2: 7.605 ops/ms
Iteration   3: 7.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.668 ±(99.9%) 0.998 ops/ms [Average]
  (min, avg, max) = (7.605, 7.668, 7.705), stdev = 0.055
  CI (99.9%): [6.670, 8.667] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.745 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.003 ms/op
Iteration   1: 3.096 ±(99.9%) 0.003 ms/op
Iteration   2: 3.067 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.082 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (3.067, 3.082, 3.096), stdev = 0.015
  CI (99.9%): [2.817, 3.347] (assumes normal distribution)


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
# Warmup Iteration   1: 4.006 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.003 ms/op
Iteration   1: 2.912 ±(99.9%) 0.002 ms/op
Iteration   2: 2.896 ±(99.9%) 0.002 ms/op
Iteration   3: 2.907 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.905 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.896, 2.905, 2.912), stdev = 0.008
  CI (99.9%): [2.757, 3.053] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.005 ms/op
Iteration   1: 3.072 ±(99.9%) 0.003 ms/op
Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
Iteration   3: 3.040 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.053 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.040, 3.053, 3.072), stdev = 0.017
  CI (99.9%): [2.737, 3.368] (assumes normal distribution)


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
# Warmup Iteration   1: 5.802 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.009 ms/op
Iteration   1: 4.132 ±(99.9%) 0.008 ms/op
Iteration   2: 4.137 ±(99.9%) 0.018 ms/op
Iteration   3: 4.198 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.155 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (4.132, 4.155, 4.198), stdev = 0.037
  CI (99.9%): [3.488, 4.823] (assumes normal distribution)


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
# Warmup Iteration   1: 4.819 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  9.880 ms/op
                 createUser·p0.9999: 13.287 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 14.549 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.849 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.765 ms/op
                 createUser·p0.9999: 18.000 ms/op
                 createUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311238
  mean =      3.086 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 17775 
    [ 2.500,  3.750) = 272529 
    [ 3.750,  5.000) = 18412 
    [ 5.000,  6.250) = 878 
    [ 6.250,  7.500) = 528 
    [ 7.500,  8.750) = 202 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      9.040 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     18.244 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.007 ms/op
Iteration   1: 2.933 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.458 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   2: 2.915 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.536 ms/op
                 existUser·p0.999:  11.076 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   3: 2.977 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  10.622 ms/op
                 existUser·p0.9999: 20.553 ms/op
                 existUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326495
  mean =      2.941 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40627 
    [ 2.500,  5.000) = 283837 
    [ 5.000,  7.500) = 1276 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =     10.191 ms/op
     p(99.9900) =     22.210 ms/op
     p(99.9990) =     25.550 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 4.563 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
Iteration   1: 3.118 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.647 ms/op
                 getUser·p0.9999: 13.140 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  9.491 ms/op
                 getUser·p0.9999: 25.135 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   3: 3.110 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  9.522 ms/op
                 getUser·p0.9999: 33.030 ms/op
                 getUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310156
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17399 
    [ 2.500,  5.000) = 290303 
    [ 5.000,  7.500) = 1801 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      9.156 ms/op
     p(99.9900) =     32.342 ms/op
     p(99.9990) =     33.256 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 5.530 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.012 ms/op
Iteration   1: 4.096 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  13.628 ms/op
                 listUser·p0.9999: 17.931 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   2: 4.082 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  20.010 ms/op
                 listUser·p0.9999: 24.450 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   3: 4.176 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.193 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 24.718 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233156
  mean =      4.117 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2036 
    [ 2.500,  5.000) = 204713 
    [ 5.000,  7.500) = 24183 
    [ 7.500, 10.000) = 1555 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     16.253 ms/op
     p(99.9900) =     24.260 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.090 ± 2.356  ops/ms
ClientGrpc.existUser                       thrpt       3  10.631 ± 2.033  ops/ms
ClientGrpc.getUser                         thrpt       3  10.420 ± 1.939  ops/ms
ClientGrpc.listUser                        thrpt       3   7.668 ± 0.998  ops/ms
ClientGrpc.createUser                       avgt       3   3.082 ± 0.265   ms/op
ClientGrpc.existUser                        avgt       3   2.905 ± 0.148   ms/op
ClientGrpc.getUser                          avgt       3   3.053 ± 0.315   ms/op
ClientGrpc.listUser                         avgt       3   4.155 ± 0.668   ms/op
ClientGrpc.createUser                     sample  311238   3.086 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.567           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.040           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.629           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.285           ms/op
ClientGrpc.existUser                      sample  326495   2.941 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.458           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.191           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.210           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.690           ms/op
ClientGrpc.getUser                        sample  310156   3.094 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.638           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.156           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.342           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.391           ms/op
ClientGrpc.listUser                       sample  233156   4.117 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.011           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.936           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.447           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.253           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.260           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.133           ms/op
