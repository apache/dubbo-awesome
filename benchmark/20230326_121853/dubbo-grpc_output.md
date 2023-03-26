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
# Warmup Iteration   1: 4.332 ops/ms
# Warmup Iteration   2: 9.170 ops/ms
# Warmup Iteration   3: 10.113 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.478 ops/ms
Iteration   3: 10.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.558 ±(99.9%) 1.962 ops/ms [Average]
  (min, avg, max) = (10.478, 10.558, 10.680), stdev = 0.108
  CI (99.9%): [8.596, 12.520] (assumes normal distribution)


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
# Warmup Iteration   1: 6.972 ops/ms
# Warmup Iteration   2: 10.507 ops/ms
# Warmup Iteration   3: 10.987 ops/ms
Iteration   1: 11.054 ops/ms
Iteration   2: 11.169 ops/ms
Iteration   3: 10.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.028 ±(99.9%) 2.840 ops/ms [Average]
  (min, avg, max) = (10.861, 11.028, 11.169), stdev = 0.156
  CI (99.9%): [8.188, 13.868] (assumes normal distribution)


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
# Warmup Iteration   1: 6.832 ops/ms
# Warmup Iteration   2: 10.133 ops/ms
# Warmup Iteration   3: 10.374 ops/ms
Iteration   1: 10.418 ops/ms
Iteration   2: 10.519 ops/ms
Iteration   3: 10.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.424 ±(99.9%) 1.685 ops/ms [Average]
  (min, avg, max) = (10.335, 10.424, 10.519), stdev = 0.092
  CI (99.9%): [8.739, 12.109] (assumes normal distribution)


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
# Warmup Iteration   1: 5.742 ops/ms
# Warmup Iteration   2: 7.509 ops/ms
# Warmup Iteration   3: 7.882 ops/ms
Iteration   1: 7.817 ops/ms
Iteration   2: 7.830 ops/ms
Iteration   3: 7.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.833 ±(99.9%) 0.327 ops/ms [Average]
  (min, avg, max) = (7.817, 7.833, 7.852), stdev = 0.018
  CI (99.9%): [7.506, 8.160] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.605 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.003 ms/op
Iteration   1: 3.087 ±(99.9%) 0.002 ms/op
Iteration   2: 3.112 ±(99.9%) 0.002 ms/op
Iteration   3: 3.083 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.094 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (3.083, 3.094, 3.112), stdev = 0.016
  CI (99.9%): [2.800, 3.388] (assumes normal distribution)


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.002 ms/op
Iteration   1: 2.868 ±(99.9%) 0.003 ms/op
Iteration   2: 2.912 ±(99.9%) 0.002 ms/op
Iteration   3: 2.923 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.901 ±(99.9%) 0.528 ms/op [Average]
  (min, avg, max) = (2.868, 2.901, 2.923), stdev = 0.029
  CI (99.9%): [2.373, 3.429] (assumes normal distribution)


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.003 ms/op
Iteration   1: 3.071 ±(99.9%) 0.003 ms/op
Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
Iteration   3: 3.013 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.044 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (3.013, 3.044, 3.071), stdev = 0.029
  CI (99.9%): [2.509, 3.579] (assumes normal distribution)


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
# Warmup Iteration   1: 6.026 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.014 ms/op
Iteration   1: 4.024 ±(99.9%) 0.021 ms/op
Iteration   2: 3.998 ±(99.9%) 0.008 ms/op
Iteration   3: 3.954 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.992 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.954, 3.992, 4.024), stdev = 0.035
  CI (99.9%): [3.346, 4.639] (assumes normal distribution)


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
Iteration   1: 3.074 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  9.484 ms/op
                 createUser·p0.9999: 21.037 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.452 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 22.466 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.270 ms/op
                 createUser·p0.9999: 24.773 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312332
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21135 
    [ 2.500,  5.000) = 289497 
    [ 5.000,  7.500) = 1146 
    [ 7.500, 10.000) = 255 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      9.858 ms/op
     p(99.9900) =     24.379 ms/op
     p(99.9990) =     24.900 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  6.554 ms/op
                 existUser·p0.9999: 17.237 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 2.959 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.914 ms/op
                 existUser·p0.9999: 14.700 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  7.596 ms/op
                 existUser·p0.9999: 17.671 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326339
  mean =      2.941 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 851 
    [ 1.250,  2.500) = 32703 
    [ 2.500,  3.750) = 284272 
    [ 3.750,  5.000) = 7504 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 249 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 70 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 52 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      7.070 ms/op
     p(99.9900) =     17.182 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  7.807 ms/op
                 getUser·p0.9999: 13.207 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  10.617 ms/op
                 getUser·p0.9999: 14.769 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.516 ms/op
                 getUser·p0.9999: 19.598 ms/op
                 getUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314729
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22430 
    [ 2.500,  5.000) = 290425 
    [ 5.000,  7.500) = 1473 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      8.102 ms/op
     p(99.9900) =     18.069 ms/op
     p(99.9990) =     19.979 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 5.468 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.010 ms/op
Iteration   1: 4.081 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 16.499 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   2: 4.171 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   7.980 ms/op
                 listUser·p0.999:  16.088 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   3: 4.054 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.693 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  17.534 ms/op
                 listUser·p0.9999: 21.667 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234024
  mean =      4.102 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2402 
    [ 2.500,  5.000) = 202845 
    [ 5.000,  7.500) = 26482 
    [ 7.500, 10.000) = 1724 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     19.943 ms/op
     p(99.9990) =     21.845 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.558 ± 1.962  ops/ms
ClientGrpc.existUser                       thrpt       3  11.028 ± 2.840  ops/ms
ClientGrpc.getUser                         thrpt       3  10.424 ± 1.685  ops/ms
ClientGrpc.listUser                        thrpt       3   7.833 ± 0.327  ops/ms
ClientGrpc.createUser                       avgt       3   3.094 ± 0.294   ms/op
ClientGrpc.existUser                        avgt       3   2.901 ± 0.528   ms/op
ClientGrpc.getUser                          avgt       3   3.044 ± 0.535   ms/op
ClientGrpc.listUser                         avgt       3   3.992 ± 0.646   ms/op
ClientGrpc.createUser                     sample  312332   3.073 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.636           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.858           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.379           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.969           ms/op
ClientGrpc.existUser                      sample  326339   2.941 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.735           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.116           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.070           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.182           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.907           ms/op
ClientGrpc.getUser                        sample  314729   3.050 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.643           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.102           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.069           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.152           ms/op
ClientGrpc.listUser                       sample  234024   4.102 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.693           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.972           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.471           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.581           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.943           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.922           ms/op
