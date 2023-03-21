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
# Warmup Iteration   1: 2.756 ops/ms
# Warmup Iteration   2: 6.576 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 8.465 ops/ms
Iteration   2: 8.563 ops/ms
Iteration   3: 8.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.413 ±(99.9%) 3.324 ops/ms [Average]
  (min, avg, max) = (8.210, 8.413, 8.563), stdev = 0.182
  CI (99.9%): [5.089, 11.737] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.675 ops/ms
# Warmup Iteration   2: 8.394 ops/ms
# Warmup Iteration   3: 9.045 ops/ms
Iteration   1: 8.931 ops/ms
Iteration   2: 9.011 ops/ms
Iteration   3: 9.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.987 ±(99.9%) 0.883 ops/ms [Average]
  (min, avg, max) = (8.931, 8.987, 9.018), stdev = 0.048
  CI (99.9%): [8.104, 9.869] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.883 ops/ms
# Warmup Iteration   2: 7.639 ops/ms
# Warmup Iteration   3: 8.361 ops/ms
Iteration   1: 8.529 ops/ms
Iteration   2: 8.560 ops/ms
Iteration   3: 8.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.529 ±(99.9%) 0.558 ops/ms [Average]
  (min, avg, max) = (8.499, 8.529, 8.560), stdev = 0.031
  CI (99.9%): [7.971, 9.088] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.222 ops/ms
# Warmup Iteration   2: 5.857 ops/ms
# Warmup Iteration   3: 6.499 ops/ms
Iteration   1: 6.478 ops/ms
Iteration   2: 6.742 ops/ms
Iteration   3: 6.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.541 ±(99.9%) 3.255 ops/ms [Average]
  (min, avg, max) = (6.402, 6.541, 6.742), stdev = 0.178
  CI (99.9%): [3.286, 9.796] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.562 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.004 ms/op
Iteration   1: 3.838 ±(99.9%) 0.003 ms/op
Iteration   2: 3.901 ±(99.9%) 0.002 ms/op
Iteration   3: 3.922 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.887 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.838, 3.887, 3.922), stdev = 0.044
  CI (99.9%): [3.086, 4.688] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.264 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.003 ms/op
Iteration   1: 3.573 ±(99.9%) 0.002 ms/op
Iteration   2: 3.467 ±(99.9%) 0.002 ms/op
Iteration   3: 3.651 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.564 ±(99.9%) 1.681 ms/op [Average]
  (min, avg, max) = (3.467, 3.564, 3.651), stdev = 0.092
  CI (99.9%): [1.882, 5.245] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.739 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.958 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.009 ms/op
Iteration   1: 3.755 ±(99.9%) 0.002 ms/op
Iteration   2: 3.893 ±(99.9%) 0.003 ms/op
Iteration   3: 3.783 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.810 ±(99.9%) 1.333 ms/op [Average]
  (min, avg, max) = (3.755, 3.810, 3.893), stdev = 0.073
  CI (99.9%): [2.477, 5.143] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.447 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.114 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.812 ±(99.9%) 0.013 ms/op
Iteration   1: 4.858 ±(99.9%) 0.029 ms/op
Iteration   2: 4.831 ±(99.9%) 0.014 ms/op
Iteration   3: 4.891 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.860 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (4.831, 4.860, 4.891), stdev = 0.030
  CI (99.9%): [4.307, 5.413] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.162 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.348 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.011 ms/op
Iteration   1: 3.882 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   5.030 ms/op
                 createUser·p0.95:   5.554 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 19.809 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   2: 3.910 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  14.108 ms/op
                 createUser·p0.9999: 21.168 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   3: 3.931 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  11.134 ms/op
                 createUser·p0.9999: 24.432 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 245627
  mean =      3.908 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9466 
    [ 2.500,  5.000) = 215883 
    [ 5.000,  7.500) = 18577 
    [ 7.500, 10.000) = 1232 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     12.349 ms/op
     p(99.9900) =     24.015 ms/op
     p(99.9990) =     27.364 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.344 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.009 ms/op
Iteration   1: 3.593 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 21.696 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   2: 3.441 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 15.747 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   3: 3.505 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  9.847 ms/op
                 existUser·p0.9999: 21.185 ms/op
                 existUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273206
  mean =      3.512 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11886 
    [ 2.500,  5.000) = 251507 
    [ 5.000,  7.500) = 8965 
    [ 7.500, 10.000) = 562 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     10.345 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     22.029 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.727 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.011 ms/op
Iteration   1: 3.746 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  8.733 ms/op
                 getUser·p0.9999: 19.184 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   2: 3.791 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  14.915 ms/op
                 getUser·p0.9999: 20.194 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   3: 3.657 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  8.791 ms/op
                 getUser·p0.9999: 22.291 ms/op
                 getUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257151
  mean =      3.730 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8114 
    [ 2.500,  5.000) = 235557 
    [ 5.000,  7.500) = 12402 
    [ 7.500, 10.000) = 762 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     10.420 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     22.572 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 6.788 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.150 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.999 ±(99.9%) 0.018 ms/op
Iteration   1: 4.818 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.262 ms/op
                 listUser·p0.999:  15.778 ms/op
                 listUser·p0.9999: 18.294 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   2: 4.902 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.242 ms/op
                 listUser·p0.95:   7.111 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 24.802 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   3: 4.931 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.599 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.315 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  19.678 ms/op
                 listUser·p0.9999: 28.919 ms/op
                 listUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196556
  mean =      4.883 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 324 
    [ 2.500,  5.000) = 130206 
    [ 5.000,  7.500) = 58379 
    [ 7.500, 10.000) = 6328 
    [10.000, 12.500) = 741 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.209 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     17.840 ms/op
     p(99.9900) =     27.831 ms/op
     p(99.9990) =     29.430 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.413 ± 3.324  ops/ms
ClientGrpc.existUser                       thrpt       3   8.987 ± 0.883  ops/ms
ClientGrpc.getUser                         thrpt       3   8.529 ± 0.558  ops/ms
ClientGrpc.listUser                        thrpt       3   6.541 ± 3.255  ops/ms
ClientGrpc.createUser                       avgt       3   3.887 ± 0.801   ms/op
ClientGrpc.existUser                        avgt       3   3.564 ± 1.681   ms/op
ClientGrpc.getUser                          avgt       3   3.810 ± 1.333   ms/op
ClientGrpc.listUser                         avgt       3   4.860 ± 0.553   ms/op
ClientGrpc.createUser                     sample  245627   3.908 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.847           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.922           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.349           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.015           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.460           ms/op
ClientGrpc.existUser                      sample  273206   3.512 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.779           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.021           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.345           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.430           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.053           ms/op
ClientGrpc.getUser                        sample  257151   3.730 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.774           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.030           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.259           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.420           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.103           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.741           ms/op
ClientGrpc.listUser                       sample  196556   4.883 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.040           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.653           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.332           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.322           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.840           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.831           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.557           ms/op
