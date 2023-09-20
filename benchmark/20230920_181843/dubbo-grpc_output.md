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
# Warmup Iteration   1: 2.881 ops/ms
# Warmup Iteration   2: 7.501 ops/ms
# Warmup Iteration   3: 8.429 ops/ms
Iteration   1: 8.825 ops/ms
Iteration   2: 9.046 ops/ms
Iteration   3: 8.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.823 ±(99.9%) 4.088 ops/ms [Average]
  (min, avg, max) = (8.598, 8.823, 9.046), stdev = 0.224
  CI (99.9%): [4.735, 12.911] (assumes normal distribution)


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
# Warmup Iteration   1: 6.072 ops/ms
# Warmup Iteration   2: 8.568 ops/ms
# Warmup Iteration   3: 9.000 ops/ms
Iteration   1: 9.117 ops/ms
Iteration   2: 8.919 ops/ms
Iteration   3: 9.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.053 ±(99.9%) 2.114 ops/ms [Average]
  (min, avg, max) = (8.919, 9.053, 9.123), stdev = 0.116
  CI (99.9%): [6.939, 11.167] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.896 ops/ms
# Warmup Iteration   2: 8.441 ops/ms
# Warmup Iteration   3: 8.540 ops/ms
Iteration   1: 8.931 ops/ms
Iteration   2: 8.910 ops/ms
Iteration   3: 8.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.915 ±(99.9%) 0.259 ops/ms [Average]
  (min, avg, max) = (8.905, 8.915, 8.931), stdev = 0.014
  CI (99.9%): [8.656, 9.174] (assumes normal distribution)


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
# Warmup Iteration   1: 4.326 ops/ms
# Warmup Iteration   2: 6.674 ops/ms
# Warmup Iteration   3: 6.861 ops/ms
Iteration   1: 6.994 ops/ms
Iteration   2: 6.941 ops/ms
Iteration   3: 6.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.860 ±(99.9%) 3.431 ops/ms [Average]
  (min, avg, max) = (6.645, 6.860, 6.994), stdev = 0.188
  CI (99.9%): [3.429, 10.290] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.638 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.007 ms/op
Iteration   1: 3.754 ±(99.9%) 0.002 ms/op
Iteration   2: 3.635 ±(99.9%) 0.003 ms/op
Iteration   3: 3.675 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.688 ±(99.9%) 1.100 ms/op [Average]
  (min, avg, max) = (3.635, 3.688, 3.754), stdev = 0.060
  CI (99.9%): [2.588, 4.788] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.770 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.004 ms/op
Iteration   1: 3.458 ±(99.9%) 0.003 ms/op
Iteration   2: 3.433 ±(99.9%) 0.004 ms/op
Iteration   3: 3.480 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.457 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (3.433, 3.457, 3.480), stdev = 0.023
  CI (99.9%): [3.031, 3.884] (assumes normal distribution)


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
# Warmup Iteration   1: 5.263 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.004 ms/op
Iteration   1: 3.666 ±(99.9%) 0.003 ms/op
Iteration   2: 3.579 ±(99.9%) 0.003 ms/op
Iteration   3: 3.648 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.631 ±(99.9%) 0.838 ms/op [Average]
  (min, avg, max) = (3.579, 3.631, 3.666), stdev = 0.046
  CI (99.9%): [2.793, 4.469] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.348 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.958 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.608 ±(99.9%) 0.011 ms/op
Iteration   1: 4.591 ±(99.9%) 0.013 ms/op
Iteration   2: 4.542 ±(99.9%) 0.015 ms/op
Iteration   3: 4.457 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.530 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (4.457, 4.530, 4.591), stdev = 0.068
  CI (99.9%): [3.291, 5.769] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.849 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.009 ms/op
Iteration   1: 3.744 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  9.574 ms/op
                 createUser·p0.9999: 20.265 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   2: 3.835 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   7.190 ms/op
                 createUser·p0.999:  11.085 ms/op
                 createUser·p0.9999: 19.661 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   3: 3.681 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.559 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  11.585 ms/op
                 createUser·p0.9999: 23.144 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255888
  mean =      3.752 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5962 
    [ 2.500,  5.000) = 233219 
    [ 5.000,  7.500) = 15153 
    [ 7.500, 10.000) = 1154 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.728 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     11.321 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     27.059 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.609 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.008 ms/op
Iteration   1: 3.518 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  12.113 ms/op
                 existUser·p0.9999: 13.614 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 3.383 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  10.185 ms/op
                 existUser·p0.9999: 19.482 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   3: 3.374 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  8.987 ms/op
                 existUser·p0.9999: 17.269 ms/op
                 existUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280205
  mean =      3.424 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11126 
    [ 2.500,  5.000) = 261786 
    [ 5.000,  7.500) = 6462 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =      9.991 ms/op
     p(99.9900) =     18.513 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 5.880 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.010 ms/op
Iteration   1: 3.850 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  12.826 ms/op
                 getUser·p0.9999: 19.716 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 3.663 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   6.279 ms/op
                 getUser·p0.999:  9.384 ms/op
                 getUser·p0.9999: 19.956 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   3: 3.561 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  10.158 ms/op
                 getUser·p0.9999: 23.071 ms/op
                 getUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260100
  mean =      3.688 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7186 
    [ 2.500,  5.000) = 240125 
    [ 5.000,  7.500) = 11353 
    [ 7.500, 10.000) = 1100 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     10.730 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     24.012 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 6.186 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.800 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.784 ±(99.9%) 0.017 ms/op
Iteration   1: 4.575 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.972 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 16.744 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   2: 4.519 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.242 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  16.042 ms/op
                 listUser·p0.9999: 17.982 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 4.738 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   6.095 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  19.710 ms/op
                 listUser·p0.9999: 22.741 ms/op
                 listUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208278
  mean =      4.609 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 635 
    [ 2.500,  5.000) = 159297 
    [ 5.000,  7.500) = 43155 
    [ 7.500, 10.000) = 4365 
    [10.000, 12.500) = 365 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      5.849 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     16.466 ms/op
     p(99.9900) =     21.016 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.823 ± 4.088  ops/ms
ClientGrpc.existUser                       thrpt       3   9.053 ± 2.114  ops/ms
ClientGrpc.getUser                         thrpt       3   8.915 ± 0.259  ops/ms
ClientGrpc.listUser                        thrpt       3   6.860 ± 3.431  ops/ms
ClientGrpc.createUser                       avgt       3   3.688 ± 1.100   ms/op
ClientGrpc.existUser                        avgt       3   3.457 ± 0.427   ms/op
ClientGrpc.getUser                          avgt       3   3.631 ± 0.838   ms/op
ClientGrpc.listUser                         avgt       3   4.530 ± 1.239   ms/op
ClientGrpc.createUser                     sample  255888   3.752 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.892           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.728           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.169           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.701           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.321           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.069           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.132           ms/op
ClientGrpc.existUser                      sample  280205   3.424 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.676           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.882           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.991           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.513           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.152           ms/op
ClientGrpc.getUser                        sample  260100   3.688 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.707           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.989           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.644           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.730           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.692           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.379           ms/op
ClientGrpc.listUser                       sample  208278   4.609 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.274           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.415           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.466           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.016           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.134           ms/op
