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
# Warmup Iteration   1: 2.766 ops/ms
# Warmup Iteration   2: 6.566 ops/ms
# Warmup Iteration   3: 8.082 ops/ms
Iteration   1: 8.586 ops/ms
Iteration   2: 8.516 ops/ms
Iteration   3: 8.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.570 ±(99.9%) 0.872 ops/ms [Average]
  (min, avg, max) = (8.516, 8.570, 8.607), stdev = 0.048
  CI (99.9%): [7.698, 9.441] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.754 ops/ms
# Warmup Iteration   2: 8.472 ops/ms
# Warmup Iteration   3: 9.021 ops/ms
Iteration   1: 8.895 ops/ms
Iteration   2: 8.885 ops/ms
Iteration   3: 8.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.909 ±(99.9%) 0.604 ops/ms [Average]
  (min, avg, max) = (8.885, 8.909, 8.947), stdev = 0.033
  CI (99.9%): [8.305, 9.513] (assumes normal distribution)


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
# Warmup Iteration   1: 5.087 ops/ms
# Warmup Iteration   2: 7.872 ops/ms
# Warmup Iteration   3: 8.419 ops/ms
Iteration   1: 8.755 ops/ms
Iteration   2: 8.650 ops/ms
Iteration   3: 8.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.651 ±(99.9%) 1.892 ops/ms [Average]
  (min, avg, max) = (8.548, 8.651, 8.755), stdev = 0.104
  CI (99.9%): [6.759, 10.543] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.300 ops/ms
# Warmup Iteration   2: 6.376 ops/ms
# Warmup Iteration   3: 6.776 ops/ms
Iteration   1: 6.820 ops/ms
Iteration   2: 6.853 ops/ms
Iteration   3: 6.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.846 ±(99.9%) 0.420 ops/ms [Average]
  (min, avg, max) = (6.820, 6.846, 6.865), stdev = 0.023
  CI (99.9%): [6.426, 7.266] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.470 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.036 ms/op
Iteration   1: 3.675 ±(99.9%) 0.003 ms/op
Iteration   2: 3.739 ±(99.9%) 0.010 ms/op
Iteration   3: 3.730 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.715 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.675, 3.715, 3.739), stdev = 0.035
  CI (99.9%): [3.084, 4.345] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.105 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.002 ms/op
Iteration   1: 3.561 ±(99.9%) 0.003 ms/op
Iteration   2: 3.506 ±(99.9%) 0.003 ms/op
Iteration   3: 3.637 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.568 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (3.506, 3.568, 3.637), stdev = 0.066
  CI (99.9%): [2.372, 4.764] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.471 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.009 ms/op
Iteration   1: 3.609 ±(99.9%) 0.007 ms/op
Iteration   2: 3.703 ±(99.9%) 0.007 ms/op
Iteration   3: 3.600 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.637 ±(99.9%) 1.047 ms/op [Average]
  (min, avg, max) = (3.600, 3.637, 3.703), stdev = 0.057
  CI (99.9%): [2.590, 4.684] (assumes normal distribution)


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
# Warmup Iteration   1: 7.130 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.049 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.831 ±(99.9%) 0.013 ms/op
Iteration   1: 4.831 ±(99.9%) 0.032 ms/op
Iteration   2: 4.750 ±(99.9%) 0.016 ms/op
Iteration   3: 4.696 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.759 ±(99.9%) 1.245 ms/op [Average]
  (min, avg, max) = (4.696, 4.759, 4.831), stdev = 0.068
  CI (99.9%): [3.514, 6.004] (assumes normal distribution)


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
# Warmup Iteration   1: 5.622 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.009 ms/op
Iteration   1: 3.692 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   6.222 ms/op
                 createUser·p0.999:  13.156 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   2: 3.674 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  9.796 ms/op
                 createUser·p0.9999: 16.553 ms/op
                 createUser·p1.00:   16.728 ms/op

Iteration   3: 3.629 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  18.018 ms/op
                 createUser·p0.9999: 33.541 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261749
  mean =      3.665 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6971 
    [ 2.500,  5.000) = 248850 
    [ 5.000,  7.500) = 5052 
    [ 7.500, 10.000) = 471 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     13.275 ms/op
     p(99.9900) =     32.795 ms/op
     p(99.9990) =     33.973 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.007 ms/op
Iteration   1: 3.585 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.420 ms/op
                 existUser·p0.999:  12.659 ms/op
                 existUser·p0.9999: 24.052 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   2: 3.565 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  8.046 ms/op
                 existUser·p0.9999: 15.811 ms/op
                 existUser·p1.00:   16.204 ms/op

Iteration   3: 3.568 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  12.185 ms/op
                 existUser·p0.9999: 20.416 ms/op
                 existUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268924
  mean =      3.573 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4616 
    [ 2.500,  5.000) = 260668 
    [ 5.000,  7.500) = 2876 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     19.874 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 5.554 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.010 ms/op
Iteration   1: 3.675 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  12.648 ms/op
                 getUser·p0.9999: 19.408 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   2: 3.690 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  11.155 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   3: 3.663 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.469 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  9.940 ms/op
                 getUser·p0.9999: 28.320 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261108
  mean =      3.676 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6917 
    [ 2.500,  5.000) = 248537 
    [ 5.000,  7.500) = 4752 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     10.611 ms/op
     p(99.9900) =     23.644 ms/op
     p(99.9990) =     28.377 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 6.698 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.888 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.732 ±(99.9%) 0.013 ms/op
Iteration   1: 4.733 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.644 ms/op
                 listUser·p0.95:   6.644 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  16.213 ms/op
                 listUser·p0.9999: 20.906 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 4.787 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.947 ms/op
                 listUser·p0.95:   7.062 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  16.630 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 4.609 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.661 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 21.532 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203807
  mean =      4.709 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 629 
    [ 2.500,  5.000) = 158503 
    [ 5.000,  7.500) = 39405 
    [ 7.500, 10.000) = 4369 
    [10.000, 12.500) = 353 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.734 ms/op
     p(95.0000) =      6.767 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     16.764 ms/op
     p(99.9900) =     20.894 ms/op
     p(99.9990) =     21.914 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.570 ± 0.872  ops/ms
ClientGrpc.existUser                       thrpt       3   8.909 ± 0.604  ops/ms
ClientGrpc.getUser                         thrpt       3   8.651 ± 1.892  ops/ms
ClientGrpc.listUser                        thrpt       3   6.846 ± 0.420  ops/ms
ClientGrpc.createUser                       avgt       3   3.715 ± 0.630   ms/op
ClientGrpc.existUser                        avgt       3   3.568 ± 1.196   ms/op
ClientGrpc.getUser                          avgt       3   3.637 ± 1.047   ms/op
ClientGrpc.listUser                         avgt       3   4.759 ± 1.245   ms/op
ClientGrpc.createUser                     sample  261749   3.665 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.746           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.275           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.795           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.079           ms/op
ClientGrpc.existUser                      sample  268924   3.573 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.863           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.354           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.874           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.314           ms/op
ClientGrpc.getUser                        sample  261108   3.676 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.469           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.759           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.611           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.644           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.377           ms/op
ClientGrpc.listUser                       sample  203807   4.709 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.057           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.380           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.764           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.894           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.922           ms/op
