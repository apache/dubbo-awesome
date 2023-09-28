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
# Warmup Iteration   1: 4.563 ops/ms
# Warmup Iteration   2: 8.845 ops/ms
# Warmup Iteration   3: 9.842 ops/ms
Iteration   1: 10.340 ops/ms
Iteration   2: 10.268 ops/ms
Iteration   3: 10.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.300 ±(99.9%) 0.668 ops/ms [Average]
  (min, avg, max) = (10.268, 10.300, 10.340), stdev = 0.037
  CI (99.9%): [9.632, 10.968] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.689 ops/ms
# Warmup Iteration   2: 10.398 ops/ms
# Warmup Iteration   3: 10.732 ops/ms
Iteration   1: 10.767 ops/ms
Iteration   2: 10.720 ops/ms
Iteration   3: 10.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.765 ±(99.9%) 0.805 ops/ms [Average]
  (min, avg, max) = (10.720, 10.765, 10.808), stdev = 0.044
  CI (99.9%): [9.960, 11.570] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.280 ops/ms
# Warmup Iteration   2: 9.959 ops/ms
# Warmup Iteration   3: 10.431 ops/ms
Iteration   1: 10.330 ops/ms
Iteration   2: 10.442 ops/ms
Iteration   3: 10.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.472 ±(99.9%) 2.899 ops/ms [Average]
  (min, avg, max) = (10.330, 10.472, 10.644), stdev = 0.159
  CI (99.9%): [7.573, 13.372] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.590 ops/ms
# Warmup Iteration   2: 7.937 ops/ms
# Warmup Iteration   3: 8.088 ops/ms
Iteration   1: 8.369 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.336 ±(99.9%) 0.982 ops/ms [Average]
  (min, avg, max) = (8.274, 8.336, 8.369), stdev = 0.054
  CI (99.9%): [7.354, 9.318] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.839 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.002 ms/op
Iteration   1: 3.069 ±(99.9%) 0.002 ms/op
Iteration   2: 3.050 ±(99.9%) 0.004 ms/op
Iteration   3: 3.135 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.085 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (3.050, 3.085, 3.135), stdev = 0.044
  CI (99.9%): [2.276, 3.894] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.508 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.003 ms/op
Iteration   1: 2.927 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.976 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (2.927, 2.976, 3.005), stdev = 0.043
  CI (99.9%): [2.199, 3.754] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.003 ms/op
Iteration   2: 3.093 ±(99.9%) 0.001 ms/op
Iteration   3: 3.092 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.090 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (3.085, 3.090, 3.093), stdev = 0.004
  CI (99.9%): [3.013, 3.168] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.052 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.019 ms/op
Iteration   1: 3.862 ±(99.9%) 0.018 ms/op
Iteration   2: 3.798 ±(99.9%) 0.022 ms/op
Iteration   3: 3.793 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.818 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (3.793, 3.818, 3.862), stdev = 0.038
  CI (99.9%): [3.115, 4.520] (assumes normal distribution)


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
# Warmup Iteration   1: 4.322 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
Iteration   1: 3.135 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  8.290 ms/op
                 createUser·p0.9999: 14.441 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  8.723 ms/op
                 createUser·p0.9999: 16.075 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   3: 3.156 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.620 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.845 ms/op
                 createUser·p0.9999: 17.166 ms/op
                 createUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306227
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 588 
    [ 1.250,  2.500) = 9036 
    [ 2.500,  3.750) = 272116 
    [ 3.750,  5.000) = 22279 
    [ 5.000,  6.250) = 1173 
    [ 6.250,  7.500) = 567 
    [ 7.500,  8.750) = 185 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 66 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      8.354 ms/op
     p(99.9900) =     16.128 ms/op
     p(99.9990) =     17.496 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.130 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 11.583 ms/op
                 existUser·p1.00:   11.928 ms/op

Iteration   2: 3.057 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.558 ms/op
                 existUser·p0.9999: 12.255 ms/op
                 existUser·p1.00:   12.567 ms/op

Iteration   3: 3.031 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  8.632 ms/op
                 existUser·p0.9999: 14.580 ms/op
                 existUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315982
  mean =      3.038 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 884 
    [ 1.250,  2.500) = 19031 
    [ 2.500,  3.750) = 280311 
    [ 3.750,  5.000) = 13976 
    [ 5.000,  6.250) = 985 
    [ 6.250,  7.500) = 397 
    [ 7.500,  8.750) = 158 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.955 ms/op
     p(99.9900) =     14.189 ms/op
     p(99.9990) =     14.952 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.868 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.008 ms/op
Iteration   1: 3.145 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  9.597 ms/op
                 getUser·p0.9999: 11.611 ms/op
                 getUser·p1.00:   11.764 ms/op

Iteration   2: 3.114 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.787 ms/op
                 getUser·p0.9999: 12.492 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.317 ms/op
                 getUser·p0.9999: 18.416 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306197
  mean =      3.136 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 251 
    [ 1.250,  2.500) = 6279 
    [ 2.500,  3.750) = 278213 
    [ 3.750,  5.000) = 19625 
    [ 5.000,  6.250) = 1039 
    [ 6.250,  7.500) = 395 
    [ 7.500,  8.750) = 167 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.936 ms/op
     p(99.9900) =     17.412 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 4.945 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.010 ms/op
Iteration   1: 3.940 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.305 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.640 ms/op
                 listUser·p0.9999: 16.720 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   2: 3.931 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 15.581 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   3: 3.864 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.799 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  13.930 ms/op
                 listUser·p0.9999: 20.986 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245375
  mean =      3.911 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3767 
    [ 2.500,  5.000) = 220566 
    [ 5.000,  7.500) = 19681 
    [ 7.500, 10.000) = 795 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.305 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     21.350 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.300 ± 0.668  ops/ms
ClientGrpc.existUser                       thrpt       3  10.765 ± 0.805  ops/ms
ClientGrpc.getUser                         thrpt       3  10.472 ± 2.899  ops/ms
ClientGrpc.listUser                        thrpt       3   8.336 ± 0.982  ops/ms
ClientGrpc.createUser                       avgt       3   3.085 ± 0.809   ms/op
ClientGrpc.existUser                        avgt       3   2.976 ± 0.777   ms/op
ClientGrpc.getUser                          avgt       3   3.090 ± 0.077   ms/op
ClientGrpc.listUser                         avgt       3   3.818 ± 0.702   ms/op
ClientGrpc.createUser                     sample  306227   3.134 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.620           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.354           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.128           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.564           ms/op
ClientGrpc.existUser                      sample  315982   3.038 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.648           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.955           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.189           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.318           ms/op
ClientGrpc.getUser                        sample  306197   3.136 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.851           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.936           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.412           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.268           ms/op
ClientGrpc.listUser                       sample  245375   3.911 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.305           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.484           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.366           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.398           ms/op
