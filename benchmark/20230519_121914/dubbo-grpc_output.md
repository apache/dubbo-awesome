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
# Warmup Iteration   1: 4.271 ops/ms
# Warmup Iteration   2: 9.210 ops/ms
# Warmup Iteration   3: 10.162 ops/ms
Iteration   1: 10.654 ops/ms
Iteration   2: 10.494 ops/ms
Iteration   3: 10.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.568 ±(99.9%) 1.472 ops/ms [Average]
  (min, avg, max) = (10.494, 10.568, 10.654), stdev = 0.081
  CI (99.9%): [9.096, 12.040] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.171 ops/ms
# Warmup Iteration   2: 10.737 ops/ms
# Warmup Iteration   3: 11.224 ops/ms
Iteration   1: 10.947 ops/ms
Iteration   2: 11.209 ops/ms
Iteration   3: 11.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.087 ±(99.9%) 2.411 ops/ms [Average]
  (min, avg, max) = (10.947, 11.087, 11.209), stdev = 0.132
  CI (99.9%): [8.676, 13.498] (assumes normal distribution)


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
# Warmup Iteration   1: 7.091 ops/ms
# Warmup Iteration   2: 10.209 ops/ms
# Warmup Iteration   3: 10.506 ops/ms
Iteration   1: 10.690 ops/ms
Iteration   2: 10.904 ops/ms
Iteration   3: 10.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.764 ±(99.9%) 2.209 ops/ms [Average]
  (min, avg, max) = (10.690, 10.764, 10.904), stdev = 0.121
  CI (99.9%): [8.555, 12.974] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.200 ops/ms
# Warmup Iteration   2: 7.997 ops/ms
# Warmup Iteration   3: 8.072 ops/ms
Iteration   1: 8.106 ops/ms
Iteration   2: 8.106 ops/ms
Iteration   3: 8.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.120 ±(99.9%) 0.431 ops/ms [Average]
  (min, avg, max) = (8.106, 8.120, 8.147), stdev = 0.024
  CI (99.9%): [7.689, 8.551] (assumes normal distribution)


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
# Warmup Iteration   1: 4.243 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.004 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.035 ±(99.9%) 0.002 ms/op
Iteration   3: 3.032 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.039 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (3.032, 3.039, 3.049), stdev = 0.009
  CI (99.9%): [2.873, 3.205] (assumes normal distribution)


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.002 ms/op
Iteration   1: 2.870 ±(99.9%) 0.003 ms/op
Iteration   2: 2.814 ±(99.9%) 0.003 ms/op
Iteration   3: 2.857 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.847 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (2.814, 2.847, 2.870), stdev = 0.029
  CI (99.9%): [2.312, 3.382] (assumes normal distribution)


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
# Warmup Iteration   1: 4.333 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.003 ms/op
Iteration   1: 3.010 ±(99.9%) 0.002 ms/op
Iteration   2: 2.942 ±(99.9%) 0.002 ms/op
Iteration   3: 3.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.985 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (2.942, 2.985, 3.010), stdev = 0.037
  CI (99.9%): [2.307, 3.663] (assumes normal distribution)


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
# Warmup Iteration   1: 5.462 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.015 ms/op
Iteration   1: 3.846 ±(99.9%) 0.014 ms/op
Iteration   2: 3.706 ±(99.9%) 0.010 ms/op
Iteration   3: 3.818 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.790 ±(99.9%) 1.349 ms/op [Average]
  (min, avg, max) = (3.706, 3.790, 3.846), stdev = 0.074
  CI (99.9%): [2.442, 5.139] (assumes normal distribution)


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.481 ms/op
                 createUser·p0.9999: 12.180 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  6.841 ms/op
                 createUser·p0.9999: 14.277 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   3: 3.077 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  11.452 ms/op
                 createUser·p0.9999: 36.158 ms/op
                 createUser·p1.00:   46.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315613
  mean =      3.039 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 313535 
    [ 5.000, 10.000) = 1808 
    [10.000, 15.000) = 221 
    [15.000, 20.000) = 17 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      9.525 ms/op
     p(99.9900) =     34.267 ms/op
     p(99.9990) =     46.596 ms/op
     p(99.9999) =     46.727 ms/op
    p(100.0000) =     46.727 ms/op


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.005 ms/op
Iteration   1: 2.867 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.150 ms/op
                 existUser·p0.95:   3.240 ms/op
                 existUser·p0.99:   3.908 ms/op
                 existUser·p0.999:  6.565 ms/op
                 existUser·p0.9999: 18.897 ms/op
                 existUser·p1.00:   19.300 ms/op

Iteration   2: 2.941 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  9.162 ms/op
                 existUser·p0.9999: 13.701 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   3: 2.885 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.397 ms/op
                 existUser·p0.9999: 16.132 ms/op
                 existUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331416
  mean =      2.897 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 847 
    [ 1.250,  2.500) = 33032 
    [ 2.500,  3.750) = 291618 
    [ 3.750,  5.000) = 4863 
    [ 5.000,  6.250) = 579 
    [ 6.250,  7.500) = 221 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      4.026 ms/op
     p(99.9000) =      6.603 ms/op
     p(99.9900) =     16.475 ms/op
     p(99.9990) =     19.225 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.619 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.534 ms/op
                 getUser·p0.9999: 14.932 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   2: 3.042 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.543 ms/op
                 getUser·p0.9999: 15.220 ms/op
                 getUser·p1.00:   15.630 ms/op

Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.307 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  7.663 ms/op
                 getUser·p0.9999: 20.106 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315883
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22443 
    [ 2.500,  5.000) = 291484 
    [ 5.000,  7.500) = 1520 
    [ 7.500, 10.000) = 203 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      8.079 ms/op
     p(99.9900) =     18.186 ms/op
     p(99.9990) =     20.628 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 5.539 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
Iteration   1: 3.861 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.962 ms/op
                 listUser·p0.9999: 18.800 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 3.901 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   3: 3.894 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  20.693 ms/op
                 listUser·p0.9999: 23.822 ms/op
                 listUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246971
  mean =      3.885 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2609 
    [ 2.500,  5.000) = 224164 
    [ 5.000,  7.500) = 18900 
    [ 7.500, 10.000) = 849 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.802 ms/op
     p(99.9000) =     15.124 ms/op
     p(99.9900) =     23.197 ms/op
     p(99.9990) =     25.399 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.568 ± 1.472  ops/ms
ClientGrpc.existUser                       thrpt       3  11.087 ± 2.411  ops/ms
ClientGrpc.getUser                         thrpt       3  10.764 ± 2.209  ops/ms
ClientGrpc.listUser                        thrpt       3   8.120 ± 0.431  ops/ms
ClientGrpc.createUser                       avgt       3   3.039 ± 0.166   ms/op
ClientGrpc.existUser                        avgt       3   2.847 ± 0.535   ms/op
ClientGrpc.getUser                          avgt       3   2.985 ± 0.678   ms/op
ClientGrpc.listUser                         avgt       3   3.790 ± 1.349   ms/op
ClientGrpc.createUser                     sample  315613   3.039 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.725           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.525           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.267           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          46.727           ms/op
ClientGrpc.existUser                      sample  331416   2.897 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.561           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.603           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.475           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.300           ms/op
ClientGrpc.getUser                        sample  315883   3.038 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.307           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.079           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.186           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.677           ms/op
ClientGrpc.listUser                       sample  246971   3.885 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.963           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.802           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.124           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.197           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.592           ms/op
