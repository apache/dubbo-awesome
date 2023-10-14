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
# Warmup Iteration   1: 3.185 ops/ms
# Warmup Iteration   2: 6.914 ops/ms
# Warmup Iteration   3: 8.512 ops/ms
Iteration   1: 8.586 ops/ms
Iteration   2: 8.744 ops/ms
Iteration   3: 8.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.585 ±(99.9%) 2.892 ops/ms [Average]
  (min, avg, max) = (8.427, 8.585, 8.744), stdev = 0.159
  CI (99.9%): [5.694, 11.477] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.828 ops/ms
# Warmup Iteration   2: 8.589 ops/ms
# Warmup Iteration   3: 9.183 ops/ms
Iteration   1: 8.992 ops/ms
Iteration   2: 8.708 ops/ms
Iteration   3: 9.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.008 ±(99.9%) 5.606 ops/ms [Average]
  (min, avg, max) = (8.708, 9.008, 9.322), stdev = 0.307
  CI (99.9%): [3.402, 14.614] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.579 ops/ms
# Warmup Iteration   2: 8.112 ops/ms
# Warmup Iteration   3: 8.416 ops/ms
Iteration   1: 8.484 ops/ms
Iteration   2: 8.432 ops/ms
Iteration   3: 8.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.485 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (8.432, 8.485, 8.539), stdev = 0.053
  CI (99.9%): [7.515, 9.455] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.808 ops/ms
# Warmup Iteration   2: 5.931 ops/ms
# Warmup Iteration   3: 6.345 ops/ms
Iteration   1: 6.602 ops/ms
Iteration   2: 6.362 ops/ms
Iteration   3: 6.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.510 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (6.362, 6.510, 6.602), stdev = 0.130
  CI (99.9%): [4.147, 8.873] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.482 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.070 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.003 ms/op
Iteration   1: 3.672 ±(99.9%) 0.003 ms/op
Iteration   2: 3.671 ±(99.9%) 0.004 ms/op
Iteration   3: 3.623 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.655 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.623, 3.655, 3.672), stdev = 0.028
  CI (99.9%): [3.145, 4.165] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.175 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.004 ms/op
Iteration   1: 3.704 ±(99.9%) 0.005 ms/op
Iteration   2: 3.504 ±(99.9%) 0.003 ms/op
Iteration   3: 3.523 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.577 ±(99.9%) 2.014 ms/op [Average]
  (min, avg, max) = (3.504, 3.577, 3.704), stdev = 0.110
  CI (99.9%): [1.563, 5.591] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.562 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.007 ms/op
Iteration   1: 3.940 ±(99.9%) 0.002 ms/op
Iteration   2: 3.977 ±(99.9%) 0.002 ms/op
Iteration   3: 3.929 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.949 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (3.929, 3.949, 3.977), stdev = 0.025
  CI (99.9%): [3.496, 4.402] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.394 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.900 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.003 ±(99.9%) 0.013 ms/op
Iteration   1: 4.882 ±(99.9%) 0.018 ms/op
Iteration   2: 5.085 ±(99.9%) 0.016 ms/op
Iteration   3: 4.936 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.968 ±(99.9%) 1.921 ms/op [Average]
  (min, avg, max) = (4.882, 4.968, 5.085), stdev = 0.105
  CI (99.9%): [3.046, 6.889] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.296 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.011 ms/op
Iteration   1: 3.731 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  11.387 ms/op
                 createUser·p0.9999: 15.357 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   2: 3.643 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  11.313 ms/op
                 createUser·p0.9999: 16.694 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 3.665 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  11.810 ms/op
                 createUser·p0.9999: 17.760 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260668
  mean =      3.679 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2896 
    [ 2.500,  5.000) = 252044 
    [ 5.000,  7.500) = 4769 
    [ 7.500, 10.000) = 565 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 4.827 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.008 ms/op
Iteration   1: 3.636 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 14.696 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   2: 3.626 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  9.142 ms/op
                 existUser·p0.9999: 16.220 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   3: 3.600 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  10.704 ms/op
                 existUser·p0.9999: 18.092 ms/op
                 existUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265013
  mean =      3.621 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 297 
    [ 1.250,  2.500) = 7930 
    [ 2.500,  3.750) = 168809 
    [ 3.750,  5.000) = 80233 
    [ 5.000,  6.250) = 5382 
    [ 6.250,  7.500) = 1304 
    [ 7.500,  8.750) = 645 
    [ 8.750, 10.000) = 189 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 70 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     16.695 ms/op
     p(99.9990) =     19.028 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 5.267 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
Iteration   1: 3.705 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.868 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  9.432 ms/op
                 getUser·p0.9999: 14.604 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 3.798 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  10.530 ms/op
                 getUser·p0.9999: 18.238 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   3: 4.107 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   5.980 ms/op
                 getUser·p0.99:   8.864 ms/op
                 getUser·p0.999:  14.622 ms/op
                 getUser·p0.9999: 21.044 ms/op
                 getUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 248438
  mean =      3.863 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6218 
    [ 2.500,  5.000) = 225340 
    [ 5.000,  7.500) = 14436 
    [ 7.500, 10.000) = 1813 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     12.685 ms/op
     p(99.9900) =     20.551 ms/op
     p(99.9990) =     21.333 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 6.275 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.211 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.005 ±(99.9%) 0.019 ms/op
Iteration   1: 4.976 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.837 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   6.455 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  14.966 ms/op
                 listUser·p0.9999: 21.014 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 4.871 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.373 ms/op
                 listUser·p0.95:   7.365 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  17.096 ms/op
                 listUser·p0.9999: 26.803 ms/op
                 listUser·p1.00:   28.901 ms/op

Iteration   3: 5.221 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   7.143 ms/op
                 listUser·p0.95:   8.069 ms/op
                 listUser·p0.99:   11.108 ms/op
                 listUser·p0.999:  22.894 ms/op
                 listUser·p0.9999: 26.341 ms/op
                 listUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 191233
  mean =      5.018 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 417 
    [ 2.500,  5.000) = 124051 
    [ 5.000,  7.500) = 56406 
    [ 7.500, 10.000) = 8335 
    [10.000, 12.500) = 1290 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.594 ms/op
     p(99.0000) =     10.120 ms/op
     p(99.9000) =     18.473 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.585 ± 2.892  ops/ms
ClientGrpc.existUser                       thrpt       3   9.008 ± 5.606  ops/ms
ClientGrpc.getUser                         thrpt       3   8.485 ± 0.970  ops/ms
ClientGrpc.listUser                        thrpt       3   6.510 ± 2.363  ops/ms
ClientGrpc.createUser                       avgt       3   3.655 ± 0.510   ms/op
ClientGrpc.existUser                        avgt       3   3.577 ± 2.014   ms/op
ClientGrpc.getUser                          avgt       3   3.949 ± 0.453   ms/op
ClientGrpc.listUser                         avgt       3   4.968 ± 1.921   ms/op
ClientGrpc.createUser                     sample  260668   3.679 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.732           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.420           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.007           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.004           ms/op
ClientGrpc.existUser                      sample  265013   3.621 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.813           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.095           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.241           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.695           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.104           ms/op
ClientGrpc.getUser                        sample  248438   3.863 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.736           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.463           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.685           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.551           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.463           ms/op
ClientGrpc.listUser                       sample  191233   5.018 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.296           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.694           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.594           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.120           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.473           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.182           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.671           ms/op
