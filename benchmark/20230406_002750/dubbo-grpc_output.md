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
# Warmup Iteration   1: 4.237 ops/ms
# Warmup Iteration   2: 9.162 ops/ms
# Warmup Iteration   3: 10.069 ops/ms
Iteration   1: 10.351 ops/ms
Iteration   2: 10.709 ops/ms
Iteration   3: 10.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.543 ±(99.9%) 3.288 ops/ms [Average]
  (min, avg, max) = (10.351, 10.543, 10.709), stdev = 0.180
  CI (99.9%): [7.255, 13.830] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.437 ops/ms
# Warmup Iteration   2: 10.765 ops/ms
# Warmup Iteration   3: 10.935 ops/ms
Iteration   1: 11.132 ops/ms
Iteration   2: 10.941 ops/ms
Iteration   3: 10.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.014 ±(99.9%) 1.884 ops/ms [Average]
  (min, avg, max) = (10.941, 11.014, 11.132), stdev = 0.103
  CI (99.9%): [9.130, 12.898] (assumes normal distribution)


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
# Warmup Iteration   1: 7.273 ops/ms
# Warmup Iteration   2: 9.745 ops/ms
# Warmup Iteration   3: 10.245 ops/ms
Iteration   1: 10.412 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.491 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (10.412, 10.491, 10.557), stdev = 0.073
  CI (99.9%): [9.158, 11.823] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.035 ops/ms
# Warmup Iteration   2: 7.655 ops/ms
# Warmup Iteration   3: 7.981 ops/ms
Iteration   1: 7.982 ops/ms
Iteration   2: 8.048 ops/ms
Iteration   3: 8.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.029 ±(99.9%) 0.749 ops/ms [Average]
  (min, avg, max) = (7.982, 8.029, 8.057), stdev = 0.041
  CI (99.9%): [7.280, 8.778] (assumes normal distribution)


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.067 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (3.047, 3.067, 3.093), stdev = 0.023
  CI (99.9%): [2.640, 3.494] (assumes normal distribution)


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.004 ms/op
Iteration   1: 2.956 ±(99.9%) 0.002 ms/op
Iteration   2: 2.970 ±(99.9%) 0.001 ms/op
Iteration   3: 2.974 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.967 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.956, 2.967, 2.974), stdev = 0.009
  CI (99.9%): [2.801, 3.132] (assumes normal distribution)


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.003 ms/op
Iteration   1: 3.040 ±(99.9%) 0.004 ms/op
Iteration   2: 3.052 ±(99.9%) 0.002 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.047 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (3.040, 3.047, 3.052), stdev = 0.006
  CI (99.9%): [2.933, 3.161] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.531 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.023 ms/op
Iteration   1: 3.947 ±(99.9%) 0.009 ms/op
Iteration   2: 4.001 ±(99.9%) 0.012 ms/op
Iteration   3: 3.949 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.966 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.947, 3.966, 4.001), stdev = 0.031
  CI (99.9%): [3.405, 4.527] (assumes normal distribution)


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
# Warmup Iteration   1: 4.249 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  10.304 ms/op
                 createUser·p0.9999: 15.900 ms/op
                 createUser·p1.00:   16.155 ms/op

Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  7.217 ms/op
                 createUser·p0.9999: 25.071 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.919 ms/op
                 createUser·p0.9999: 28.000 ms/op
                 createUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314668
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19533 
    [ 2.500,  5.000) = 293746 
    [ 5.000,  7.500) = 1023 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.410 ms/op
     p(99.9000) =      7.957 ms/op
     p(99.9900) =     26.612 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.005 ms/op
Iteration   1: 2.930 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.841 ms/op
                 existUser·p0.9999: 13.388 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.925 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.018 ms/op
                 existUser·p0.999:  6.234 ms/op
                 existUser·p0.9999: 22.940 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   3: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.113 ms/op
                 existUser·p0.999:  6.885 ms/op
                 existUser·p0.9999: 17.999 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327093
  mean =      2.934 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32720 
    [ 2.500,  5.000) = 293471 
    [ 5.000,  7.500) = 690 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      6.554 ms/op
     p(99.9900) =     19.511 ms/op
     p(99.9990) =     23.656 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 4.119 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
Iteration   1: 3.120 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  9.191 ms/op
                 getUser·p0.9999: 19.358 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  6.600 ms/op
                 getUser·p0.9999: 18.579 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.382 ms/op
                 getUser·p0.9999: 17.320 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311257
  mean =      3.083 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 694 
    [ 1.250,  2.500) = 15336 
    [ 2.500,  3.750) = 275069 
    [ 3.750,  5.000) = 18571 
    [ 5.000,  6.250) = 1019 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.373 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     19.723 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 4.826 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.011 ms/op
Iteration   1: 3.976 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.961 ms/op
                 listUser·p0.999:  13.510 ms/op
                 listUser·p0.9999: 23.593 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 3.917 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  15.128 ms/op
                 listUser·p0.9999: 17.192 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.927 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 23.626 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243613
  mean =      3.940 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3211 
    [ 2.500,  5.000) = 219090 
    [ 5.000,  7.500) = 19946 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     23.483 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.543 ± 3.288  ops/ms
ClientGrpc.existUser                       thrpt       3  11.014 ± 1.884  ops/ms
ClientGrpc.getUser                         thrpt       3  10.491 ± 1.333  ops/ms
ClientGrpc.listUser                        thrpt       3   8.029 ± 0.749  ops/ms
ClientGrpc.createUser                       avgt       3   3.067 ± 0.427   ms/op
ClientGrpc.existUser                        avgt       3   2.967 ± 0.166   ms/op
ClientGrpc.getUser                          avgt       3   3.047 ± 0.114   ms/op
ClientGrpc.listUser                         avgt       3   3.966 ± 0.561   ms/op
ClientGrpc.createUser                     sample  314668   3.051 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.644           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.410           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.957           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.612           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.049           ms/op
ClientGrpc.existUser                      sample  327093   2.934 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.573           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.554           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.511           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.347           ms/op
ClientGrpc.getUser                        sample  311257   3.083 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.658           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.373           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.743           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.825           ms/op
ClientGrpc.listUser                       sample  243613   3.940 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.865           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.204           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.483           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.919           ms/op
