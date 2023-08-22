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
# Warmup Iteration   1: 3.024 ops/ms
# Warmup Iteration   2: 6.654 ops/ms
# Warmup Iteration   3: 7.797 ops/ms
Iteration   1: 8.207 ops/ms
Iteration   2: 8.212 ops/ms
Iteration   3: 8.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.247 ±(99.9%) 1.159 ops/ms [Average]
  (min, avg, max) = (8.207, 8.247, 8.320), stdev = 0.064
  CI (99.9%): [7.087, 9.406] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.524 ops/ms
# Warmup Iteration   2: 8.295 ops/ms
# Warmup Iteration   3: 8.378 ops/ms
Iteration   1: 8.801 ops/ms
Iteration   2: 8.937 ops/ms
Iteration   3: 9.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.970 ±(99.9%) 3.425 ops/ms [Average]
  (min, avg, max) = (8.801, 8.970, 9.172), stdev = 0.188
  CI (99.9%): [5.545, 12.394] (assumes normal distribution)


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
# Warmup Iteration   1: 4.765 ops/ms
# Warmup Iteration   2: 7.563 ops/ms
# Warmup Iteration   3: 7.733 ops/ms
Iteration   1: 7.922 ops/ms
Iteration   2: 8.489 ops/ms
Iteration   3: 8.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.300 ±(99.9%) 5.972 ops/ms [Average]
  (min, avg, max) = (7.922, 8.300, 8.490), stdev = 0.327
  CI (99.9%): [2.329, 14.272] (assumes normal distribution)


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
# Warmup Iteration   1: 3.927 ops/ms
# Warmup Iteration   2: 5.844 ops/ms
# Warmup Iteration   3: 6.220 ops/ms
Iteration   1: 6.371 ops/ms
Iteration   2: 6.322 ops/ms
Iteration   3: 6.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.318 ±(99.9%) 1.006 ops/ms [Average]
  (min, avg, max) = (6.261, 6.318, 6.371), stdev = 0.055
  CI (99.9%): [5.312, 7.324] (assumes normal distribution)


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
# Warmup Iteration   1: 5.537 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.026 ms/op
Iteration   1: 3.891 ±(99.9%) 0.005 ms/op
Iteration   2: 3.836 ±(99.9%) 0.004 ms/op
Iteration   3: 3.863 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.863 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (3.836, 3.863, 3.891), stdev = 0.027
  CI (99.9%): [3.363, 4.364] (assumes normal distribution)


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.702 ±(99.9%) 0.007 ms/op
Iteration   1: 3.751 ±(99.9%) 0.005 ms/op
Iteration   2: 3.645 ±(99.9%) 0.003 ms/op
Iteration   3: 3.674 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.690 ±(99.9%) 1.002 ms/op [Average]
  (min, avg, max) = (3.645, 3.690, 3.751), stdev = 0.055
  CI (99.9%): [2.688, 4.692] (assumes normal distribution)


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
# Warmup Iteration   1: 5.170 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.005 ms/op
Iteration   1: 3.795 ±(99.9%) 0.004 ms/op
Iteration   2: 4.202 ±(99.9%) 0.004 ms/op
Iteration   3: 4.028 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.008 ±(99.9%) 3.730 ms/op [Average]
  (min, avg, max) = (3.795, 4.008, 4.202), stdev = 0.204
  CI (99.9%): [0.279, 7.738] (assumes normal distribution)


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
# Warmup Iteration   1: 7.652 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.734 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.491 ±(99.9%) 0.014 ms/op
Iteration   1: 5.288 ±(99.9%) 0.018 ms/op
Iteration   2: 5.345 ±(99.9%) 0.014 ms/op
Iteration   3: 5.257 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.297 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (5.257, 5.297, 5.345), stdev = 0.044
  CI (99.9%): [4.486, 6.108] (assumes normal distribution)


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
# Warmup Iteration   1: 5.994 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.013 ms/op
Iteration   1: 4.066 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   8.520 ms/op
                 createUser·p0.999:  15.603 ms/op
                 createUser·p0.9999: 20.199 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.937 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.346 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   7.600 ms/op
                 createUser·p0.999:  19.486 ms/op
                 createUser·p0.9999: 34.594 ms/op
                 createUser·p1.00:   35.062 ms/op

Iteration   3: 3.986 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.369 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   5.123 ms/op
                 createUser·p0.95:   5.882 ms/op
                 createUser·p0.99:   8.976 ms/op
                 createUser·p0.999:  12.799 ms/op
                 createUser·p0.9999: 23.395 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 240395
  mean =      3.996 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11599 
    [ 2.500,  5.000) = 204396 
    [ 5.000,  7.500) = 20427 
    [ 7.500, 10.000) = 2944 
    [10.000, 12.500) = 594 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     14.641 ms/op
     p(99.9900) =     33.094 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 5.303 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.012 ms/op
Iteration   1: 3.712 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   8.487 ms/op
                 existUser·p0.999:  11.600 ms/op
                 existUser·p0.9999: 17.680 ms/op
                 existUser·p1.00:   18.252 ms/op

Iteration   2: 3.684 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   7.340 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 17.869 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 3.659 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   7.635 ms/op
                 existUser·p0.999:  12.715 ms/op
                 existUser·p0.9999: 32.187 ms/op
                 existUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 260420
  mean =      3.685 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16730 
    [ 2.500,  5.000) = 227110 
    [ 5.000,  7.500) = 13515 
    [ 7.500, 10.000) = 2314 
    [10.000, 12.500) = 560 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     31.816 ms/op
     p(99.9990) =     32.401 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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
# Warmup Iteration   1: 5.557 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.014 ms/op
Iteration   1: 3.993 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   5.136 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   9.126 ms/op
                 getUser·p0.999:  13.031 ms/op
                 getUser·p0.9999: 31.063 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   2: 3.839 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  13.310 ms/op
                 getUser·p0.9999: 30.496 ms/op
                 getUser·p1.00:   32.539 ms/op

Iteration   3: 3.836 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  10.079 ms/op
                 getUser·p0.9999: 21.386 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 246928
  mean =      3.888 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12637 
    [ 2.500,  5.000) = 212860 
    [ 5.000,  7.500) = 18359 
    [ 7.500, 10.000) = 2285 
    [10.000, 12.500) = 483 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     30.353 ms/op
     p(99.9990) =     31.666 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 7.484 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.394 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.281 ±(99.9%) 0.021 ms/op
Iteration   1: 5.268 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   8.200 ms/op
                 listUser·p0.99:   11.207 ms/op
                 listUser·p0.999:  18.842 ms/op
                 listUser·p0.9999: 25.788 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 5.032 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.725 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  19.643 ms/op
                 listUser·p0.9999: 23.536 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   3: 4.984 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.644 ms/op
                 listUser·p0.95:   7.545 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  26.214 ms/op
                 listUser·p0.9999: 33.527 ms/op
                 listUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188527
  mean =      5.092 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 854 
    [ 2.500,  5.000) = 115601 
    [ 5.000,  7.500) = 59846 
    [ 7.500, 10.000) = 10041 
    [10.000, 12.500) = 1417 
    [12.500, 15.000) = 381 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      7.840 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     21.149 ms/op
     p(99.9900) =     32.155 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.247 ± 1.159  ops/ms
ClientGrpc.existUser                       thrpt       3   8.970 ± 3.425  ops/ms
ClientGrpc.getUser                         thrpt       3   8.300 ± 5.972  ops/ms
ClientGrpc.listUser                        thrpt       3   6.318 ± 1.006  ops/ms
ClientGrpc.createUser                       avgt       3   3.863 ± 0.500   ms/op
ClientGrpc.existUser                        avgt       3   3.690 ± 1.002   ms/op
ClientGrpc.getUser                          avgt       3   4.008 ± 3.730   ms/op
ClientGrpc.listUser                         avgt       3   5.297 ± 0.811   ms/op
ClientGrpc.createUser                     sample  240395   3.996 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.346           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.389           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.641           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.094           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.062           ms/op
ClientGrpc.existUser                      sample  260420   3.685 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.511           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.259           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.799           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.764           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.816           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.604           ms/op
ClientGrpc.getUser                        sample  246928   3.888 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.818           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.554           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.963           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.943           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.353           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.539           ms/op
ClientGrpc.listUser                       sample  188527   5.092 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.990           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.840           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.289           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.149           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.155           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.948           ms/op
