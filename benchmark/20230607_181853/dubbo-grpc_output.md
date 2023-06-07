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
# Warmup Iteration   1: 3.199 ops/ms
# Warmup Iteration   2: 6.935 ops/ms
# Warmup Iteration   3: 8.012 ops/ms
Iteration   1: 8.467 ops/ms
Iteration   2: 8.735 ops/ms
Iteration   3: 8.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.629 ±(99.9%) 2.607 ops/ms [Average]
  (min, avg, max) = (8.467, 8.629, 8.735), stdev = 0.143
  CI (99.9%): [6.022, 11.236] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.072 ops/ms
# Warmup Iteration   2: 8.534 ops/ms
# Warmup Iteration   3: 8.951 ops/ms
Iteration   1: 9.458 ops/ms
Iteration   2: 9.272 ops/ms
Iteration   3: 9.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.296 ±(99.9%) 2.773 ops/ms [Average]
  (min, avg, max) = (9.157, 9.296, 9.458), stdev = 0.152
  CI (99.9%): [6.522, 12.069] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.969 ops/ms
# Warmup Iteration   2: 8.118 ops/ms
# Warmup Iteration   3: 8.533 ops/ms
Iteration   1: 8.673 ops/ms
Iteration   2: 8.599 ops/ms
Iteration   3: 8.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.598 ±(99.9%) 1.389 ops/ms [Average]
  (min, avg, max) = (8.521, 8.598, 8.673), stdev = 0.076
  CI (99.9%): [7.208, 9.987] (assumes normal distribution)


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
# Warmup Iteration   1: 4.277 ops/ms
# Warmup Iteration   2: 6.474 ops/ms
# Warmup Iteration   3: 6.741 ops/ms
Iteration   1: 6.742 ops/ms
Iteration   2: 6.793 ops/ms
Iteration   3: 6.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.703 ±(99.9%) 2.098 ops/ms [Average]
  (min, avg, max) = (6.573, 6.703, 6.793), stdev = 0.115
  CI (99.9%): [4.604, 8.801] (assumes normal distribution)


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
# Warmup Iteration   1: 5.486 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.013 ms/op
Iteration   1: 3.676 ±(99.9%) 0.004 ms/op
Iteration   2: 3.594 ±(99.9%) 0.004 ms/op
Iteration   3: 3.631 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.634 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (3.594, 3.634, 3.676), stdev = 0.041
  CI (99.9%): [2.887, 4.380] (assumes normal distribution)


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
# Warmup Iteration   1: 4.734 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.003 ms/op
Iteration   1: 3.456 ±(99.9%) 0.006 ms/op
Iteration   2: 3.548 ±(99.9%) 0.004 ms/op
Iteration   3: 3.489 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.497 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (3.456, 3.497, 3.548), stdev = 0.046
  CI (99.9%): [2.649, 4.346] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.189 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.003 ms/op
Iteration   1: 3.613 ±(99.9%) 0.004 ms/op
Iteration   2: 3.626 ±(99.9%) 0.003 ms/op
Iteration   3: 3.685 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.641 ±(99.9%) 0.700 ms/op [Average]
  (min, avg, max) = (3.613, 3.641, 3.685), stdev = 0.038
  CI (99.9%): [2.941, 4.341] (assumes normal distribution)


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
# Warmup Iteration   1: 6.729 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.114 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.761 ±(99.9%) 0.011 ms/op
Iteration   1: 4.698 ±(99.9%) 0.015 ms/op
Iteration   2: 4.777 ±(99.9%) 0.020 ms/op
Iteration   3: 4.538 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.671 ±(99.9%) 2.220 ms/op [Average]
  (min, avg, max) = (4.538, 4.671, 4.777), stdev = 0.122
  CI (99.9%): [2.451, 6.891] (assumes normal distribution)


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
# Warmup Iteration   1: 5.283 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.010 ms/op
Iteration   1: 3.763 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  11.796 ms/op
                 createUser·p0.9999: 15.384 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   2: 3.764 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  12.585 ms/op
                 createUser·p0.9999: 17.385 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   3: 3.746 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  11.158 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255443
  mean =      3.758 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8591 
    [ 2.500,  5.000) = 234146 
    [ 5.000,  7.500) = 11187 
    [ 7.500, 10.000) = 1150 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     11.747 ms/op
     p(99.9900) =     19.560 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 4.866 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.010 ms/op
Iteration   1: 3.483 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.357 ms/op
                 existUser·p0.999:  14.139 ms/op
                 existUser·p0.9999: 25.187 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   2: 3.490 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  9.241 ms/op
                 existUser·p0.9999: 17.007 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   3: 3.461 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  9.389 ms/op
                 existUser·p0.9999: 20.300 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275939
  mean =      3.478 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13729 
    [ 2.500,  5.000) = 254561 
    [ 5.000,  7.500) = 6420 
    [ 7.500, 10.000) = 908 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.157 ms/op
     p(99.9000) =     10.437 ms/op
     p(99.9900) =     24.655 ms/op
     p(99.9990) =     25.542 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 5.080 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.776 ±(99.9%) 0.010 ms/op
Iteration   1: 3.737 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.915 ms/op
                 getUser·p0.999:  12.216 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   20.152 ms/op

Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.426 ms/op
                 getUser·p0.999:  9.577 ms/op
                 getUser·p0.9999: 22.428 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   3: 3.674 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  10.156 ms/op
                 getUser·p0.9999: 26.791 ms/op
                 getUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258111
  mean =      3.718 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8124 
    [ 2.500,  5.000) = 239244 
    [ 5.000,  7.500) = 9299 
    [ 7.500, 10.000) = 1183 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     10.011 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     27.061 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 6.312 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.148 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.782 ±(99.9%) 0.018 ms/op
Iteration   1: 4.756 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   7.176 ms/op
                 listUser·p0.99:   9.830 ms/op
                 listUser·p0.999:  15.608 ms/op
                 listUser·p0.9999: 19.833 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 4.735 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 18.825 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 4.807 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   6.428 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   9.683 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 21.987 ms/op
                 listUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201417
  mean =      4.766 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 690 
    [ 2.500,  5.000) = 150497 
    [ 5.000,  7.500) = 42853 
    [ 7.500, 10.000) = 5758 
    [10.000, 12.500) = 970 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 163 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      6.218 ms/op
     p(95.0000) =      7.160 ms/op
     p(99.0000) =      9.535 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.629 ± 2.607  ops/ms
ClientGrpc.existUser                       thrpt       3   9.296 ± 2.773  ops/ms
ClientGrpc.getUser                         thrpt       3   8.598 ± 1.389  ops/ms
ClientGrpc.listUser                        thrpt       3   6.703 ± 2.098  ops/ms
ClientGrpc.createUser                       avgt       3   3.634 ± 0.746   ms/op
ClientGrpc.existUser                        avgt       3   3.497 ± 0.848   ms/op
ClientGrpc.getUser                          avgt       3   3.641 ± 0.700   ms/op
ClientGrpc.listUser                         avgt       3   4.671 ± 2.220   ms/op
ClientGrpc.createUser                     sample  255443   3.758 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.646           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.997           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.734           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.747           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.560           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217           ms/op
ClientGrpc.existUser                      sample  275939   3.478 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.718           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.437           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.655           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.625           ms/op
ClientGrpc.getUser                        sample  258111   3.718 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.699           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.455           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.011           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.919           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.230           ms/op
ClientGrpc.listUser                       sample  201417   4.766 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.130           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.218           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.160           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.535           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.465           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.185           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.757           ms/op
