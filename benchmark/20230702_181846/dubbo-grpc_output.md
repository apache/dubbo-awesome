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
# Warmup Iteration   1: 3.360 ops/ms
# Warmup Iteration   2: 6.980 ops/ms
# Warmup Iteration   3: 7.943 ops/ms
Iteration   1: 8.746 ops/ms
Iteration   2: 8.738 ops/ms
Iteration   3: 8.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.760 ±(99.9%) 0.555 ops/ms [Average]
  (min, avg, max) = (8.738, 8.760, 8.795), stdev = 0.030
  CI (99.9%): [8.205, 9.314] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.048 ops/ms
# Warmup Iteration   2: 8.592 ops/ms
# Warmup Iteration   3: 9.111 ops/ms
Iteration   1: 9.050 ops/ms
Iteration   2: 9.602 ops/ms
Iteration   3: 9.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.286 ±(99.9%) 5.196 ops/ms [Average]
  (min, avg, max) = (9.050, 9.286, 9.602), stdev = 0.285
  CI (99.9%): [4.089, 14.482] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.796 ops/ms
# Warmup Iteration   2: 8.398 ops/ms
# Warmup Iteration   3: 8.644 ops/ms
Iteration   1: 8.830 ops/ms
Iteration   2: 8.759 ops/ms
Iteration   3: 8.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.795 ±(99.9%) 0.652 ops/ms [Average]
  (min, avg, max) = (8.759, 8.795, 8.830), stdev = 0.036
  CI (99.9%): [8.144, 9.447] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.850 ops/ms
# Warmup Iteration   2: 6.075 ops/ms
# Warmup Iteration   3: 6.484 ops/ms
Iteration   1: 6.752 ops/ms
Iteration   2: 6.699 ops/ms
Iteration   3: 6.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.740 ±(99.9%) 0.675 ops/ms [Average]
  (min, avg, max) = (6.699, 6.740, 6.770), stdev = 0.037
  CI (99.9%): [6.065, 7.415] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.342 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.006 ms/op
Iteration   1: 3.652 ±(99.9%) 0.003 ms/op
Iteration   2: 3.583 ±(99.9%) 0.004 ms/op
Iteration   3: 3.674 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.637 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (3.583, 3.637, 3.674), stdev = 0.047
  CI (99.9%): [2.771, 4.502] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.785 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.002 ms/op
Iteration   1: 3.438 ±(99.9%) 0.004 ms/op
Iteration   2: 3.491 ±(99.9%) 0.004 ms/op
Iteration   3: 3.316 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.415 ±(99.9%) 1.640 ms/op [Average]
  (min, avg, max) = (3.316, 3.415, 3.491), stdev = 0.090
  CI (99.9%): [1.775, 5.055] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.307 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.003 ms/op
Iteration   1: 3.646 ±(99.9%) 0.004 ms/op
Iteration   2: 3.714 ±(99.9%) 0.004 ms/op
Iteration   3: 3.850 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.737 ±(99.9%) 1.895 ms/op [Average]
  (min, avg, max) = (3.646, 3.737, 3.850), stdev = 0.104
  CI (99.9%): [1.842, 5.631] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.785 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.020 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.770 ±(99.9%) 0.013 ms/op
Iteration   1: 4.858 ±(99.9%) 0.014 ms/op
Iteration   2: 4.895 ±(99.9%) 0.025 ms/op
Iteration   3: 4.767 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.840 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (4.767, 4.840, 4.895), stdev = 0.066
  CI (99.9%): [3.644, 6.036] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.631 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.010 ms/op
Iteration   1: 3.648 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  12.425 ms/op
                 createUser·p0.9999: 16.158 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   2: 3.668 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  11.016 ms/op
                 createUser·p0.9999: 16.204 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   3: 3.603 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  16.457 ms/op
                 createUser·p0.9999: 22.821 ms/op
                 createUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263769
  mean =      3.639 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12898 
    [ 2.500,  5.000) = 242562 
    [ 5.000,  7.500) = 7241 
    [ 7.500, 10.000) = 763 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     11.382 ms/op
     p(99.9900) =     21.385 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.283 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.009 ms/op
Iteration   1: 3.481 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  9.917 ms/op
                 existUser·p0.9999: 14.235 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   2: 3.474 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  11.368 ms/op
                 existUser·p0.9999: 15.184 ms/op
                 existUser·p1.00:   15.548 ms/op

Iteration   3: 3.568 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  8.530 ms/op
                 existUser·p0.9999: 19.174 ms/op
                 existUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273654
  mean =      3.507 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 519 
    [ 1.250,  2.500) = 10700 
    [ 2.500,  3.750) = 193422 
    [ 3.750,  5.000) = 62044 
    [ 5.000,  6.250) = 4916 
    [ 6.250,  7.500) = 1165 
    [ 7.500,  8.750) = 504 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =      9.912 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     19.645 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.363 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.721 ±(99.9%) 0.010 ms/op
Iteration   1: 3.605 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  13.537 ms/op
                 getUser·p0.9999: 22.647 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   2: 3.683 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  10.617 ms/op
                 getUser·p0.9999: 18.000 ms/op
                 getUser·p1.00:   20.316 ms/op

Iteration   3: 3.727 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.886 ms/op
                 getUser·p0.999:  12.534 ms/op
                 getUser·p0.9999: 27.243 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261662
  mean =      3.671 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11649 
    [ 2.500,  5.000) = 239860 
    [ 5.000,  7.500) = 8775 
    [ 7.500, 10.000) = 975 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     11.753 ms/op
     p(99.9900) =     26.733 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 6.602 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.864 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.872 ±(99.9%) 0.015 ms/op
Iteration   1: 4.711 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 18.920 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 4.911 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  16.317 ms/op
                 listUser·p0.9999: 20.037 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 4.946 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.554 ms/op
                 listUser·p0.95:   7.365 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  20.164 ms/op
                 listUser·p0.9999: 27.346 ms/op
                 listUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197747
  mean =      4.854 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 435 
    [ 2.500,  5.000) = 137114 
    [ 5.000,  7.500) = 53732 
    [ 7.500, 10.000) = 5404 
    [10.000, 12.500) = 616 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.070 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     17.375 ms/op
     p(99.9900) =     26.146 ms/op
     p(99.9990) =     27.755 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.760 ± 0.555  ops/ms
ClientGrpc.existUser                       thrpt       3   9.286 ± 5.196  ops/ms
ClientGrpc.getUser                         thrpt       3   8.795 ± 0.652  ops/ms
ClientGrpc.listUser                        thrpt       3   6.740 ± 0.675  ops/ms
ClientGrpc.createUser                       avgt       3   3.637 ± 0.865   ms/op
ClientGrpc.existUser                        avgt       3   3.415 ± 1.640   ms/op
ClientGrpc.getUser                          avgt       3   3.737 ± 1.895   ms/op
ClientGrpc.listUser                         avgt       3   4.840 ± 1.196   ms/op
ClientGrpc.createUser                     sample  263769   3.639 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.838           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.906           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.382           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.385           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.117           ms/op
ClientGrpc.existUser                      sample  273654   3.507 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.885           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.865           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.912           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.105           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.759           ms/op
ClientGrpc.getUser                        sample  261662   3.671 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.770           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.825           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.390           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.753           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.733           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.623           ms/op
ClientGrpc.listUser                       sample  197747   4.854 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.186           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.234           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.978           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.375           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.146           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.787           ms/op
