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
# Warmup Iteration   1: 3.095 ops/ms
# Warmup Iteration   2: 7.119 ops/ms
# Warmup Iteration   3: 8.369 ops/ms
Iteration   1: 8.825 ops/ms
Iteration   2: 8.873 ops/ms
Iteration   3: 8.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.845 ±(99.9%) 0.456 ops/ms [Average]
  (min, avg, max) = (8.825, 8.845, 8.873), stdev = 0.025
  CI (99.9%): [8.389, 9.301] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.893 ops/ms
# Warmup Iteration   2: 8.561 ops/ms
# Warmup Iteration   3: 9.031 ops/ms
Iteration   1: 9.318 ops/ms
Iteration   2: 9.524 ops/ms
Iteration   3: 9.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.371 ±(99.9%) 2.463 ops/ms [Average]
  (min, avg, max) = (9.271, 9.371, 9.524), stdev = 0.135
  CI (99.9%): [6.908, 11.834] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.449 ops/ms
# Warmup Iteration   2: 8.085 ops/ms
# Warmup Iteration   3: 8.672 ops/ms
Iteration   1: 8.727 ops/ms
Iteration   2: 8.785 ops/ms
Iteration   3: 8.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.725 ±(99.9%) 1.106 ops/ms [Average]
  (min, avg, max) = (8.664, 8.725, 8.785), stdev = 0.061
  CI (99.9%): [7.619, 9.831] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.210 ops/ms
# Warmup Iteration   2: 6.328 ops/ms
# Warmup Iteration   3: 6.638 ops/ms
Iteration   1: 6.679 ops/ms
Iteration   2: 6.814 ops/ms
Iteration   3: 6.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.778 ±(99.9%) 1.577 ops/ms [Average]
  (min, avg, max) = (6.679, 6.778, 6.841), stdev = 0.086
  CI (99.9%): [5.201, 8.356] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.363 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.028 ms/op
Iteration   1: 3.710 ±(99.9%) 0.002 ms/op
Iteration   2: 3.731 ±(99.9%) 0.003 ms/op
Iteration   3: 3.650 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.697 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (3.650, 3.697, 3.731), stdev = 0.042
  CI (99.9%): [2.934, 4.460] (assumes normal distribution)


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
# Warmup Iteration   1: 5.026 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.002 ms/op
Iteration   1: 3.547 ±(99.9%) 0.003 ms/op
Iteration   2: 3.490 ±(99.9%) 0.002 ms/op
Iteration   3: 3.497 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.511 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (3.490, 3.511, 3.547), stdev = 0.031
  CI (99.9%): [2.940, 4.083] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.356 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.741 ±(99.9%) 0.010 ms/op
Iteration   1: 3.630 ±(99.9%) 0.005 ms/op
Iteration   2: 3.684 ±(99.9%) 0.002 ms/op
Iteration   3: 3.577 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.630 ±(99.9%) 0.969 ms/op [Average]
  (min, avg, max) = (3.577, 3.630, 3.684), stdev = 0.053
  CI (99.9%): [2.662, 4.599] (assumes normal distribution)


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
# Warmup Iteration   1: 6.427 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.062 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.796 ±(99.9%) 0.017 ms/op
Iteration   1: 4.768 ±(99.9%) 0.013 ms/op
Iteration   2: 4.631 ±(99.9%) 0.009 ms/op
Iteration   3: 4.648 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.682 ±(99.9%) 1.359 ms/op [Average]
  (min, avg, max) = (4.631, 4.682, 4.768), stdev = 0.075
  CI (99.9%): [3.323, 6.041] (assumes normal distribution)


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
# Warmup Iteration   1: 5.503 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.009 ms/op
Iteration   1: 3.667 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  9.884 ms/op
                 createUser·p0.9999: 13.198 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   2: 3.679 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   3: 3.679 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  16.171 ms/op
                 createUser·p0.9999: 21.299 ms/op
                 createUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261303
  mean =      3.675 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4305 
    [ 2.500,  5.000) = 251160 
    [ 5.000,  7.500) = 5074 
    [ 7.500, 10.000) = 456 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     10.771 ms/op
     p(99.9900) =     20.705 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 5.493 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.008 ms/op
Iteration   1: 3.537 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  9.608 ms/op
                 existUser·p0.9999: 14.877 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   2: 3.488 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  9.835 ms/op
                 existUser·p0.9999: 15.215 ms/op
                 existUser·p1.00:   15.401 ms/op

Iteration   3: 3.572 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.436 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271774
  mean =      3.532 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 283 
    [ 1.250,  2.500) = 8823 
    [ 2.500,  3.750) = 185891 
    [ 3.750,  5.000) = 72250 
    [ 5.000,  6.250) = 3156 
    [ 6.250,  7.500) = 668 
    [ 7.500,  8.750) = 366 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.883 ms/op
     p(99.9900) =     16.688 ms/op
     p(99.9990) =     17.606 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 5.227 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.009 ms/op
Iteration   1: 3.716 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  12.074 ms/op
                 getUser·p0.9999: 15.581 ms/op
                 getUser·p1.00:   15.892 ms/op

Iteration   2: 3.720 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  11.291 ms/op
                 getUser·p0.9999: 16.302 ms/op
                 getUser·p1.00:   16.695 ms/op

Iteration   3: 3.731 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  8.527 ms/op
                 getUser·p0.9999: 19.154 ms/op
                 getUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257797
  mean =      3.722 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4914 
    [ 2.500,  5.000) = 246070 
    [ 5.000,  7.500) = 6059 
    [ 7.500, 10.000) = 403 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     11.059 ms/op
     p(99.9900) =     18.463 ms/op
     p(99.9990) =     20.114 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 5.952 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.224 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.828 ±(99.9%) 0.014 ms/op
Iteration   1: 4.716 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  16.531 ms/op
                 listUser·p0.9999: 22.311 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   2: 4.795 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.857 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 20.523 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 4.746 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.509 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  20.120 ms/op
                 listUser·p0.9999: 36.996 ms/op
                 listUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201975
  mean =      4.752 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180 
    [ 2.500,  5.000) = 155869 
    [ 5.000,  7.500) = 40770 
    [ 7.500, 10.000) = 4408 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     35.639 ms/op
     p(99.9990) =     37.353 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.845 ± 0.456  ops/ms
ClientGrpc.existUser                       thrpt       3   9.371 ± 2.463  ops/ms
ClientGrpc.getUser                         thrpt       3   8.725 ± 1.106  ops/ms
ClientGrpc.listUser                        thrpt       3   6.778 ± 1.577  ops/ms
ClientGrpc.createUser                       avgt       3   3.697 ± 0.763   ms/op
ClientGrpc.existUser                        avgt       3   3.511 ± 0.572   ms/op
ClientGrpc.getUser                          avgt       3   3.630 ± 0.969   ms/op
ClientGrpc.listUser                         avgt       3   4.682 ± 1.359   ms/op
ClientGrpc.createUser                     sample  261303   3.675 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.932           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.771           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.705           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.299           ms/op
ClientGrpc.existUser                      sample  271774   3.532 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.936           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.505           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.883           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.688           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.793           ms/op
ClientGrpc.getUser                        sample  257797   3.722 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.910           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.059           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.463           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.218           ms/op
ClientGrpc.listUser                       sample  201975   4.752 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.339           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.438           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.448           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.639           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.421           ms/op
