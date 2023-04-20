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
# Warmup Iteration   1: 4.145 ops/ms
# Warmup Iteration   2: 9.232 ops/ms
# Warmup Iteration   3: 10.223 ops/ms
Iteration   1: 10.392 ops/ms
Iteration   2: 10.384 ops/ms
Iteration   3: 10.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.462 ±(99.9%) 2.346 ops/ms [Average]
  (min, avg, max) = (10.384, 10.462, 10.611), stdev = 0.129
  CI (99.9%): [8.116, 12.809] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.730 ops/ms
# Warmup Iteration   2: 10.351 ops/ms
# Warmup Iteration   3: 10.871 ops/ms
Iteration   1: 10.897 ops/ms
Iteration   2: 11.216 ops/ms
Iteration   3: 10.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.031 ±(99.9%) 3.020 ops/ms [Average]
  (min, avg, max) = (10.897, 11.031, 11.216), stdev = 0.166
  CI (99.9%): [8.010, 14.051] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.546 ops/ms
# Warmup Iteration   2: 10.081 ops/ms
# Warmup Iteration   3: 10.612 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.602 ops/ms
Iteration   3: 10.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.532 ±(99.9%) 2.744 ops/ms [Average]
  (min, avg, max) = (10.359, 10.532, 10.634), stdev = 0.150
  CI (99.9%): [7.788, 13.275] (assumes normal distribution)


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
# Warmup Iteration   1: 5.381 ops/ms
# Warmup Iteration   2: 7.681 ops/ms
# Warmup Iteration   3: 7.986 ops/ms
Iteration   1: 7.972 ops/ms
Iteration   2: 7.971 ops/ms
Iteration   3: 8.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.067 ±(99.9%) 3.005 ops/ms [Average]
  (min, avg, max) = (7.971, 8.067, 8.257), stdev = 0.165
  CI (99.9%): [5.062, 11.072] (assumes normal distribution)


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.002 ms/op
Iteration   1: 3.143 ±(99.9%) 0.008 ms/op
Iteration   2: 3.107 ±(99.9%) 0.003 ms/op
Iteration   3: 3.061 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.104 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (3.061, 3.104, 3.143), stdev = 0.041
  CI (99.9%): [2.351, 3.856] (assumes normal distribution)


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.002 ms/op
Iteration   1: 2.919 ±(99.9%) 0.002 ms/op
Iteration   2: 2.886 ±(99.9%) 0.002 ms/op
Iteration   3: 2.913 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.906 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (2.886, 2.906, 2.919), stdev = 0.018
  CI (99.9%): [2.585, 3.227] (assumes normal distribution)


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
# Warmup Iteration   1: 4.334 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.004 ms/op
Iteration   1: 3.036 ±(99.9%) 0.004 ms/op
Iteration   2: 3.052 ±(99.9%) 0.001 ms/op
Iteration   3: 3.111 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.036, 3.066, 3.111), stdev = 0.040
  CI (99.9%): [2.343, 3.789] (assumes normal distribution)


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
# Warmup Iteration   1: 5.695 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.015 ms/op
Iteration   1: 3.977 ±(99.9%) 0.017 ms/op
Iteration   2: 4.018 ±(99.9%) 0.034 ms/op
Iteration   3: 3.991 ±(99.9%) 0.057 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.996 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (3.977, 3.996, 4.018), stdev = 0.021
  CI (99.9%): [3.615, 4.377] (assumes normal distribution)


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
# Warmup Iteration   1: 4.253 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.050 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.586 ms/op
                 createUser·p0.9999: 13.214 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   2: 3.050 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  7.523 ms/op
                 createUser·p0.9999: 14.353 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  12.947 ms/op
                 createUser·p0.9999: 20.336 ms/op
                 createUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313507
  mean =      3.062 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15820 
    [ 2.500,  5.000) = 295754 
    [ 5.000,  7.500) = 1582 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      7.754 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     20.733 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.042 ms/op
Iteration   1: 3.211 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   7.845 ms/op
                 existUser·p0.999:  57.237 ms/op
                 existUser·p0.9999: 86.054 ms/op
                 existUser·p1.00:   101.974 ms/op

Iteration   2: 3.306 ±(99.9%) 0.047 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   22.249 ms/op
                 existUser·p0.999:  68.944 ms/op
                 existUser·p0.9999: 85.894 ms/op
                 existUser·p1.00:   88.343 ms/op

Iteration   3: 3.312 ±(99.9%) 0.042 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   20.130 ms/op
                 existUser·p0.999:  57.431 ms/op
                 existUser·p0.9999: 71.740 ms/op
                 existUser·p1.00:   76.415 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 293139
  mean =      3.276 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 289840 
    [ 12.500,  25.000) = 894 
    [ 25.000,  37.500) = 978 
    [ 37.500,  50.000) = 724 
    [ 50.000,  62.500) = 452 
    [ 62.500,  75.000) = 161 
    [ 75.000,  87.500) = 77 
    [ 87.500, 100.000) = 12 
    [100.000, 112.500) = 1 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =     17.223 ms/op
     p(99.9000) =     60.359 ms/op
     p(99.9900) =     83.976 ms/op
     p(99.9990) =     96.708 ms/op
     p(99.9999) =    101.974 ms/op
    p(100.0000) =    101.974 ms/op


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
# Warmup Iteration   1: 5.247 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.047 ms/op
Iteration   1: 3.473 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   8.120 ms/op
                 getUser·p0.999:  64.001 ms/op
                 getUser·p0.9999: 88.781 ms/op
                 getUser·p1.00:   110.100 ms/op

Iteration   2: 3.320 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   15.455 ms/op
                 getUser·p0.999:  56.638 ms/op
                 getUser·p0.9999: 71.477 ms/op
                 getUser·p1.00:   81.658 ms/op

Iteration   3: 3.467 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   22.590 ms/op
                 getUser·p0.999:  62.601 ms/op
                 getUser·p0.9999: 80.982 ms/op
                 getUser·p1.00:   103.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 281228
  mean =      3.419 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 278205 
    [ 12.500,  25.000) = 635 
    [ 25.000,  37.500) = 886 
    [ 37.500,  50.000) = 660 
    [ 50.000,  62.500) = 607 
    [ 62.500,  75.000) = 175 
    [ 75.000,  87.500) = 48 
    [ 87.500, 100.000) = 8 
    [100.000, 112.500) = 4 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =     17.025 ms/op
     p(99.9000) =     61.014 ms/op
     p(99.9900) =     81.642 ms/op
     p(99.9990) =    104.228 ms/op
     p(99.9999) =    110.100 ms/op
    p(100.0000) =    110.100 ms/op


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
# Warmup Iteration   1: 6.461 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.362 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.018 ms/op
Iteration   1: 4.065 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  15.275 ms/op
                 listUser·p0.9999: 21.177 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 4.023 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.069 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  17.254 ms/op
                 listUser·p0.9999: 19.240 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   3: 4.028 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.660 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 21.729 ms/op
                 listUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237572
  mean =      4.039 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4050 
    [ 2.500,  5.000) = 201500 
    [ 5.000,  7.500) = 30143 
    [ 7.500, 10.000) = 1226 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     22.016 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt    Score   Error   Units
ClientGrpc.createUser                      thrpt       3   10.462 ± 2.346  ops/ms
ClientGrpc.existUser                       thrpt       3   11.031 ± 3.020  ops/ms
ClientGrpc.getUser                         thrpt       3   10.532 ± 2.744  ops/ms
ClientGrpc.listUser                        thrpt       3    8.067 ± 3.005  ops/ms
ClientGrpc.createUser                       avgt       3    3.104 ± 0.752   ms/op
ClientGrpc.existUser                        avgt       3    2.906 ± 0.321   ms/op
ClientGrpc.getUser                          avgt       3    3.066 ± 0.723   ms/op
ClientGrpc.listUser                         avgt       3    3.996 ± 0.381   ms/op
ClientGrpc.createUser                     sample  313507    3.062 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample            0.764           ms/op
ClientGrpc.createUser:createUser·p0.50    sample            3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample            3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample            3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample            4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample            7.754           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample           19.661           ms/op
ClientGrpc.createUser:createUser·p1.00    sample           20.939           ms/op
ClientGrpc.existUser                      sample  293139    3.276 ± 0.025   ms/op
ClientGrpc.existUser:existUser·p0.00      sample            0.581           ms/op
ClientGrpc.existUser:existUser·p0.50      sample            2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample            3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample            3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           17.223           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           60.359           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample           83.976           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          101.974           ms/op
ClientGrpc.getUser                        sample  281228    3.419 ± 0.026   ms/op
ClientGrpc.getUser:getUser·p0.00          sample            0.641           ms/op
ClientGrpc.getUser:getUser·p0.50          sample            3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample            3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample            4.014           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           17.025           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           61.014           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample           81.642           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          110.100           ms/op
ClientGrpc.listUser                       sample  237572    4.039 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample            0.660           ms/op
ClientGrpc.listUser:listUser·p0.50        sample            3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample            5.308           ms/op
ClientGrpc.listUser:listUser·p0.95        sample            6.038           ms/op
ClientGrpc.listUser:listUser·p0.99        sample            7.274           ms/op
ClientGrpc.listUser:listUser·p0.999       sample           17.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample           21.168           ms/op
ClientGrpc.listUser:listUser·p1.00        sample           24.084           ms/op
