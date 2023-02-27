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
# Warmup Iteration   1: 2.912 ops/ms
# Warmup Iteration   2: 6.665 ops/ms
# Warmup Iteration   3: 7.702 ops/ms
Iteration   1: 7.937 ops/ms
Iteration   2: 7.978 ops/ms
Iteration   3: 8.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.985 ±(99.9%) 0.952 ops/ms [Average]
  (min, avg, max) = (7.937, 7.985, 8.041), stdev = 0.052
  CI (99.9%): [7.033, 8.938] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.759 ops/ms
# Warmup Iteration   2: 7.966 ops/ms
# Warmup Iteration   3: 8.167 ops/ms
Iteration   1: 8.333 ops/ms
Iteration   2: 8.394 ops/ms
Iteration   3: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.369 ±(99.9%) 0.582 ops/ms [Average]
  (min, avg, max) = (8.333, 8.369, 8.394), stdev = 0.032
  CI (99.9%): [7.787, 8.951] (assumes normal distribution)


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
# Warmup Iteration   1: 5.203 ops/ms
# Warmup Iteration   2: 7.800 ops/ms
# Warmup Iteration   3: 7.871 ops/ms
Iteration   1: 8.250 ops/ms
Iteration   2: 8.260 ops/ms
Iteration   3: 8.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.208 ±(99.9%) 1.485 ops/ms [Average]
  (min, avg, max) = (8.114, 8.208, 8.260), stdev = 0.081
  CI (99.9%): [6.723, 9.693] (assumes normal distribution)


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
# Warmup Iteration   1: 3.969 ops/ms
# Warmup Iteration   2: 5.821 ops/ms
# Warmup Iteration   3: 6.008 ops/ms
Iteration   1: 6.263 ops/ms
Iteration   2: 6.359 ops/ms
Iteration   3: 6.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.258 ±(99.9%) 1.877 ops/ms [Average]
  (min, avg, max) = (6.153, 6.258, 6.359), stdev = 0.103
  CI (99.9%): [4.381, 8.136] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.810 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.007 ms/op
Iteration   1: 3.721 ±(99.9%) 0.004 ms/op
Iteration   2: 3.709 ±(99.9%) 0.003 ms/op
Iteration   3: 3.698 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.709 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (3.698, 3.709, 3.721), stdev = 0.012
  CI (99.9%): [3.497, 3.922] (assumes normal distribution)


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
# Warmup Iteration   1: 5.143 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.004 ms/op
Iteration   1: 3.800 ±(99.9%) 0.003 ms/op
Iteration   2: 3.590 ±(99.9%) 0.004 ms/op
Iteration   3: 3.712 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.701 ±(99.9%) 1.923 ms/op [Average]
  (min, avg, max) = (3.590, 3.701, 3.800), stdev = 0.105
  CI (99.9%): [1.778, 5.624] (assumes normal distribution)


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
# Warmup Iteration   1: 5.519 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.004 ms/op
Iteration   1: 3.841 ±(99.9%) 0.003 ms/op
Iteration   2: 3.740 ±(99.9%) 0.004 ms/op
Iteration   3: 3.952 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.845 ±(99.9%) 1.936 ms/op [Average]
  (min, avg, max) = (3.740, 3.845, 3.952), stdev = 0.106
  CI (99.9%): [1.908, 5.781] (assumes normal distribution)


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
# Warmup Iteration   1: 7.026 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.181 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.004 ±(99.9%) 0.019 ms/op
Iteration   1: 4.781 ±(99.9%) 0.008 ms/op
Iteration   2: 4.991 ±(99.9%) 0.007 ms/op
Iteration   3: 4.885 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.886 ±(99.9%) 1.914 ms/op [Average]
  (min, avg, max) = (4.781, 4.886, 4.991), stdev = 0.105
  CI (99.9%): [2.972, 6.799] (assumes normal distribution)


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
# Warmup Iteration   1: 5.426 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.011 ms/op
Iteration   1: 3.817 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.592 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  14.241 ms/op
                 createUser·p0.9999: 16.562 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 3.849 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.251 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  10.420 ms/op
                 createUser·p0.9999: 22.895 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.845 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.345 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.159 ms/op
                 createUser·p0.999:  20.080 ms/op
                 createUser·p0.9999: 23.627 ms/op
                 createUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250066
  mean =      3.837 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6630 
    [ 2.500,  5.000) = 229554 
    [ 5.000,  7.500) = 12616 
    [ 7.500, 10.000) = 765 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     24.673 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 5.092 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.008 ms/op
Iteration   1: 3.742 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  12.059 ms/op
                 existUser·p0.9999: 14.956 ms/op
                 existUser·p1.00:   15.237 ms/op

Iteration   2: 3.712 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  9.821 ms/op
                 existUser·p0.9999: 19.870 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   3: 3.846 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   6.685 ms/op
                 existUser·p0.999:  10.809 ms/op
                 existUser·p0.9999: 20.229 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 254900
  mean =      3.766 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10120 
    [ 2.500,  5.000) = 231353 
    [ 5.000,  7.500) = 12299 
    [ 7.500, 10.000) = 813 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     11.077 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     20.590 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 5.661 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.010 ms/op
Iteration   1: 4.112 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  11.865 ms/op
                 getUser·p0.9999: 17.079 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   2: 4.036 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.480 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  10.350 ms/op
                 getUser·p0.9999: 17.175 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   3: 3.944 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.964 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  9.599 ms/op
                 getUser·p0.9999: 18.998 ms/op
                 getUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 238245
  mean =      4.030 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 6582 
    [ 2.500,  3.750) = 89132 
    [ 3.750,  5.000) = 115786 
    [ 5.000,  6.250) = 22867 
    [ 6.250,  7.500) = 2461 
    [ 7.500,  8.750) = 710 
    [ 8.750, 10.000) = 324 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     10.527 ms/op
     p(99.9900) =     18.389 ms/op
     p(99.9990) =     19.406 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 7.426 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.328 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.059 ±(99.9%) 0.017 ms/op
Iteration   1: 4.920 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.349 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  14.531 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   2: 4.923 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.447 ms/op
                 listUser·p0.95:   7.245 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 4.759 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.972 ms/op
                 listUser·p0.95:   6.840 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  22.371 ms/op
                 listUser·p0.9999: 26.232 ms/op
                 listUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197347
  mean =      4.866 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 447 
    [ 2.500,  5.000) = 137277 
    [ 5.000,  7.500) = 52584 
    [ 7.500, 10.000) = 5915 
    [10.000, 12.500) = 612 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.111 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     17.683 ms/op
     p(99.9900) =     25.308 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.985 ± 0.952  ops/ms
ClientGrpc.existUser                       thrpt       3   8.369 ± 0.582  ops/ms
ClientGrpc.getUser                         thrpt       3   8.208 ± 1.485  ops/ms
ClientGrpc.listUser                        thrpt       3   6.258 ± 1.877  ops/ms
ClientGrpc.createUser                       avgt       3   3.709 ± 0.212   ms/op
ClientGrpc.existUser                        avgt       3   3.701 ± 1.923   ms/op
ClientGrpc.getUser                          avgt       3   3.845 ± 1.936   ms/op
ClientGrpc.listUser                         avgt       3   4.886 ± 1.914   ms/op
ClientGrpc.createUser                     sample  250066   3.837 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.345           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.071           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.349           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.926           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.839           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.280           ms/op
ClientGrpc.existUser                      sample  254900   3.766 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.854           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.275           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.077           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.759           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.742           ms/op
ClientGrpc.getUser                        sample  238245   4.030 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.945           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.940           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.063           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.456           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.742           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.527           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.389           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.530           ms/op
ClientGrpc.listUser                       sample  197347   4.866 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.143           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.267           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.683           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.308           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.017           ms/op
