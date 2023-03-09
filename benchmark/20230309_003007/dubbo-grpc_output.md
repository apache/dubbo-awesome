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
# Warmup Iteration   1: 3.309 ops/ms
# Warmup Iteration   2: 7.256 ops/ms
# Warmup Iteration   3: 8.518 ops/ms
Iteration   1: 8.599 ops/ms
Iteration   2: 8.704 ops/ms
Iteration   3: 8.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.661 ±(99.9%) 1.011 ops/ms [Average]
  (min, avg, max) = (8.599, 8.661, 8.704), stdev = 0.055
  CI (99.9%): [7.650, 9.672] (assumes normal distribution)


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
# Warmup Iteration   1: 5.992 ops/ms
# Warmup Iteration   2: 8.578 ops/ms
# Warmup Iteration   3: 8.747 ops/ms
Iteration   1: 9.058 ops/ms
Iteration   2: 9.016 ops/ms
Iteration   3: 9.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.042 ±(99.9%) 0.410 ops/ms [Average]
  (min, avg, max) = (9.016, 9.042, 9.058), stdev = 0.022
  CI (99.9%): [8.632, 9.452] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.726 ops/ms
# Warmup Iteration   2: 8.133 ops/ms
# Warmup Iteration   3: 8.629 ops/ms
Iteration   1: 8.779 ops/ms
Iteration   2: 9.113 ops/ms
Iteration   3: 9.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.977 ±(99.9%) 3.196 ops/ms [Average]
  (min, avg, max) = (8.779, 8.977, 9.113), stdev = 0.175
  CI (99.9%): [5.781, 12.173] (assumes normal distribution)


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
# Warmup Iteration   1: 4.389 ops/ms
# Warmup Iteration   2: 6.352 ops/ms
# Warmup Iteration   3: 6.724 ops/ms
Iteration   1: 6.695 ops/ms
Iteration   2: 6.827 ops/ms
Iteration   3: 7.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.880 ±(99.9%) 3.949 ops/ms [Average]
  (min, avg, max) = (6.695, 6.880, 7.118), stdev = 0.216
  CI (99.9%): [2.931, 10.829] (assumes normal distribution)


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
# Warmup Iteration   1: 5.185 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.003 ms/op
Iteration   1: 3.632 ±(99.9%) 0.004 ms/op
Iteration   2: 3.599 ±(99.9%) 0.003 ms/op
Iteration   3: 3.594 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.609 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (3.594, 3.609, 3.632), stdev = 0.021
  CI (99.9%): [3.229, 3.988] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.640 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.004 ms/op
Iteration   1: 3.466 ±(99.9%) 0.002 ms/op
Iteration   2: 3.493 ±(99.9%) 0.003 ms/op
Iteration   3: 3.608 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.522 ±(99.9%) 1.371 ms/op [Average]
  (min, avg, max) = (3.466, 3.522, 3.608), stdev = 0.075
  CI (99.9%): [2.151, 4.893] (assumes normal distribution)


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
# Warmup Iteration   1: 5.381 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.004 ms/op
Iteration   1: 3.566 ±(99.9%) 0.005 ms/op
Iteration   2: 3.541 ±(99.9%) 0.003 ms/op
Iteration   3: 3.504 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.537 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (3.504, 3.537, 3.566), stdev = 0.031
  CI (99.9%): [2.969, 4.105] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.893 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.998 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.791 ±(99.9%) 0.023 ms/op
Iteration   1: 4.701 ±(99.9%) 0.010 ms/op
Iteration   2: 4.664 ±(99.9%) 0.011 ms/op
Iteration   3: 4.643 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.669 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (4.643, 4.669, 4.701), stdev = 0.029
  CI (99.9%): [4.137, 5.202] (assumes normal distribution)


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
# Warmup Iteration   1: 5.129 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.008 ms/op
Iteration   1: 3.685 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  14.041 ms/op
                 createUser·p0.9999: 16.548 ms/op
                 createUser·p1.00:   16.564 ms/op

Iteration   2: 3.673 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  11.615 ms/op
                 createUser·p0.9999: 15.240 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   3: 3.722 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  12.125 ms/op
                 createUser·p0.9999: 18.625 ms/op
                 createUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259859
  mean =      3.693 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3453 
    [ 2.500,  5.000) = 249131 
    [ 5.000,  7.500) = 6329 
    [ 7.500, 10.000) = 539 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     18.220 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.286 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.009 ms/op
Iteration   1: 3.509 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.651 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 21.721 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.503 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  10.785 ms/op
                 existUser·p0.9999: 16.705 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   3: 3.407 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.225 ms/op
                 existUser·p0.99:   5.334 ms/op
                 existUser·p0.999:  9.701 ms/op
                 existUser·p0.9999: 20.063 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276457
  mean =      3.472 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7852 
    [ 2.500,  5.000) = 263549 
    [ 5.000,  7.500) = 4262 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     10.478 ms/op
     p(99.9900) =     21.016 ms/op
     p(99.9990) =     21.937 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 4.985 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.008 ms/op
Iteration   1: 3.655 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  12.982 ms/op
                 getUser·p0.9999: 19.399 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   2: 3.633 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   3.568 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  8.028 ms/op
                 getUser·p0.9999: 20.355 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   3: 3.565 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.666 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  10.392 ms/op
                 getUser·p0.9999: 29.036 ms/op
                 getUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265320
  mean =      3.618 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7474 
    [ 2.500,  5.000) = 251466 
    [ 5.000,  7.500) = 5682 
    [ 7.500, 10.000) = 462 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     28.419 ms/op
     p(99.9990) =     29.285 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 7.562 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.993 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.839 ±(99.9%) 0.016 ms/op
Iteration   1: 4.756 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.029 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   9.129 ms/op
                 listUser·p0.999:  15.871 ms/op
                 listUser·p0.9999: 17.713 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   2: 4.861 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.955 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  16.945 ms/op
                 listUser·p0.9999: 19.314 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 4.912 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.218 ms/op
                 listUser·p0.95:   7.168 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  20.906 ms/op
                 listUser·p0.9999: 29.983 ms/op
                 listUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198268
  mean =      4.842 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 428 
    [ 2.500,  5.000) = 142423 
    [ 5.000,  7.500) = 48861 
    [ 7.500, 10.000) = 5478 
    [10.000, 12.500) = 616 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     30.281 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.661 ± 1.011  ops/ms
ClientGrpc.existUser                       thrpt       3   9.042 ± 0.410  ops/ms
ClientGrpc.getUser                         thrpt       3   8.977 ± 3.196  ops/ms
ClientGrpc.listUser                        thrpt       3   6.880 ± 3.949  ops/ms
ClientGrpc.createUser                       avgt       3   3.609 ± 0.379   ms/op
ClientGrpc.existUser                        avgt       3   3.522 ± 1.371   ms/op
ClientGrpc.getUser                          avgt       3   3.537 ± 0.568   ms/op
ClientGrpc.listUser                         avgt       3   4.669 ± 0.532   ms/op
ClientGrpc.createUser                     sample  259859   3.693 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.810           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.857           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.452           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.220           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.578           ms/op
ClientGrpc.existUser                      sample  276457   3.472 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.861           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.076           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.587           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.478           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.016           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.987           ms/op
ClientGrpc.getUser                        sample  265320   3.618 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.666           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.792           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.126           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.419           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.327           ms/op
ClientGrpc.listUser                       sample  198268   4.842 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.966           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.103           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.978           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.974           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.229           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.309           ms/op
