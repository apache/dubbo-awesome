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
# Warmup Iteration   1: 2.993 ops/ms
# Warmup Iteration   2: 6.397 ops/ms
# Warmup Iteration   3: 7.947 ops/ms
Iteration   1: 8.056 ops/ms
Iteration   2: 8.347 ops/ms
Iteration   3: 8.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.337 ±(99.9%) 5.041 ops/ms [Average]
  (min, avg, max) = (8.056, 8.337, 8.608), stdev = 0.276
  CI (99.9%): [3.296, 13.378] (assumes normal distribution)


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
# Warmup Iteration   1: 5.754 ops/ms
# Warmup Iteration   2: 8.619 ops/ms
# Warmup Iteration   3: 9.158 ops/ms
Iteration   1: 9.108 ops/ms
Iteration   2: 9.615 ops/ms
Iteration   3: 9.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.337 ±(99.9%) 4.684 ops/ms [Average]
  (min, avg, max) = (9.108, 9.337, 9.615), stdev = 0.257
  CI (99.9%): [4.653, 14.022] (assumes normal distribution)


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
# Warmup Iteration   1: 5.393 ops/ms
# Warmup Iteration   2: 8.155 ops/ms
# Warmup Iteration   3: 8.528 ops/ms
Iteration   1: 8.956 ops/ms
Iteration   2: 8.880 ops/ms
Iteration   3: 8.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.834 ±(99.9%) 2.754 ops/ms [Average]
  (min, avg, max) = (8.665, 8.834, 8.956), stdev = 0.151
  CI (99.9%): [6.079, 11.588] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.978 ops/ms
# Warmup Iteration   2: 6.135 ops/ms
# Warmup Iteration   3: 6.604 ops/ms
Iteration   1: 6.759 ops/ms
Iteration   2: 6.686 ops/ms
Iteration   3: 6.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.704 ±(99.9%) 0.892 ops/ms [Average]
  (min, avg, max) = (6.667, 6.704, 6.759), stdev = 0.049
  CI (99.9%): [5.812, 7.596] (assumes normal distribution)


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
# Warmup Iteration   1: 5.512 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.830 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.011 ms/op
Iteration   1: 3.759 ±(99.9%) 0.002 ms/op
Iteration   2: 3.692 ±(99.9%) 0.003 ms/op
Iteration   3: 3.666 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.705 ±(99.9%) 0.873 ms/op [Average]
  (min, avg, max) = (3.666, 3.705, 3.759), stdev = 0.048
  CI (99.9%): [2.832, 4.578] (assumes normal distribution)


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
# Warmup Iteration   1: 5.025 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.002 ms/op
Iteration   1: 3.577 ±(99.9%) 0.003 ms/op
Iteration   2: 3.502 ±(99.9%) 0.004 ms/op
Iteration   3: 3.436 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.505 ±(99.9%) 1.281 ms/op [Average]
  (min, avg, max) = (3.436, 3.505, 3.577), stdev = 0.070
  CI (99.9%): [2.224, 4.787] (assumes normal distribution)


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
# Warmup Iteration   1: 5.302 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.005 ms/op
Iteration   1: 3.667 ±(99.9%) 0.005 ms/op
Iteration   2: 3.571 ±(99.9%) 0.004 ms/op
Iteration   3: 3.571 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.603 ±(99.9%) 1.012 ms/op [Average]
  (min, avg, max) = (3.571, 3.603, 3.667), stdev = 0.055
  CI (99.9%): [2.591, 4.615] (assumes normal distribution)


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
# Warmup Iteration   1: 7.175 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.144 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.923 ±(99.9%) 0.011 ms/op
Iteration   1: 4.873 ±(99.9%) 0.020 ms/op
Iteration   2: 4.830 ±(99.9%) 0.015 ms/op
Iteration   3: 4.653 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.785 ±(99.9%) 2.125 ms/op [Average]
  (min, avg, max) = (4.653, 4.785, 4.873), stdev = 0.116
  CI (99.9%): [2.660, 6.911] (assumes normal distribution)


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
# Warmup Iteration   1: 5.363 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.010 ms/op
Iteration   1: 3.570 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  9.279 ms/op
                 createUser·p0.9999: 15.255 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   2: 3.601 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  10.462 ms/op
                 createUser·p0.9999: 24.158 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.591 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  17.859 ms/op
                 createUser·p0.9999: 28.738 ms/op
                 createUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 267575
  mean =      3.587 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15288 
    [ 2.500,  5.000) = 244044 
    [ 5.000,  7.500) = 7204 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.966 ms/op
     p(99.9000) =     11.099 ms/op
     p(99.9900) =     28.073 ms/op
     p(99.9990) =     28.933 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.008 ms/op
Iteration   1: 3.341 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  7.820 ms/op
                 existUser·p0.9999: 28.752 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   2: 3.377 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  9.464 ms/op
                 existUser·p0.9999: 21.531 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 3.551 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  10.974 ms/op
                 existUser·p0.9999: 23.232 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280496
  mean =      3.420 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8341 
    [ 2.500,  5.000) = 266514 
    [ 5.000,  7.500) = 4850 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.921 ms/op
     p(99.9900) =     28.375 ms/op
     p(99.9990) =     28.908 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 5.256 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.009 ms/op
Iteration   1: 3.609 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  12.242 ms/op
                 getUser·p0.9999: 20.451 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   2: 3.624 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  9.007 ms/op
                 getUser·p0.9999: 20.491 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   3: 3.751 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  10.917 ms/op
                 getUser·p0.9999: 24.559 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262244
  mean =      3.660 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10880 
    [ 2.500,  5.000) = 240765 
    [ 5.000,  7.500) = 9328 
    [ 7.500, 10.000) = 932 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     10.502 ms/op
     p(99.9900) =     23.749 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 6.615 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.473 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.889 ±(99.9%) 0.015 ms/op
Iteration   1: 4.965 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.357 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  16.880 ms/op
                 listUser·p0.9999: 26.018 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 4.688 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.759 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  18.252 ms/op
                 listUser·p0.9999: 25.204 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 4.784 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   7.094 ms/op
                 listUser·p0.99:   9.830 ms/op
                 listUser·p0.999:  19.895 ms/op
                 listUser·p0.9999: 23.777 ms/op
                 listUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199508
  mean =      4.810 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 279 
    [ 2.500,  5.000) = 146099 
    [ 5.000,  7.500) = 46572 
    [ 7.500, 10.000) = 5240 
    [10.000, 12.500) = 835 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.971 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     25.692 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.337 ± 5.041  ops/ms
ClientGrpc.existUser                       thrpt       3   9.337 ± 4.684  ops/ms
ClientGrpc.getUser                         thrpt       3   8.834 ± 2.754  ops/ms
ClientGrpc.listUser                        thrpt       3   6.704 ± 0.892  ops/ms
ClientGrpc.createUser                       avgt       3   3.705 ± 0.873   ms/op
ClientGrpc.existUser                        avgt       3   3.505 ± 1.281   ms/op
ClientGrpc.getUser                          avgt       3   3.603 ± 1.012   ms/op
ClientGrpc.listUser                         avgt       3   4.785 ± 2.125   ms/op
ClientGrpc.createUser                     sample  267575   3.587 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.689           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.966           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.099           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.073           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.065           ms/op
ClientGrpc.existUser                      sample  280496   3.420 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.627           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.965           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.636           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.921           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.375           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.934           ms/op
ClientGrpc.getUser                        sample  262244   3.660 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.805           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.373           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.502           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.749           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.805           ms/op
ClientGrpc.listUser                       sample  199508   4.810 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.204           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.743           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.692           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.149           ms/op
