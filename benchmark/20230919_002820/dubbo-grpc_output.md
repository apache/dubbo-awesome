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
# Warmup Iteration   1: 4.503 ops/ms
# Warmup Iteration   2: 9.043 ops/ms
# Warmup Iteration   3: 9.897 ops/ms
Iteration   1: 10.288 ops/ms
Iteration   2: 10.237 ops/ms
Iteration   3: 10.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.289 ±(99.9%) 0.960 ops/ms [Average]
  (min, avg, max) = (10.237, 10.289, 10.342), stdev = 0.053
  CI (99.9%): [9.328, 11.249] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.924 ops/ms
# Warmup Iteration   2: 10.566 ops/ms
# Warmup Iteration   3: 11.004 ops/ms
Iteration   1: 10.609 ops/ms
Iteration   2: 10.943 ops/ms
Iteration   3: 10.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.768 ±(99.9%) 3.054 ops/ms [Average]
  (min, avg, max) = (10.609, 10.768, 10.943), stdev = 0.167
  CI (99.9%): [7.713, 13.822] (assumes normal distribution)


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
# Warmup Iteration   1: 7.059 ops/ms
# Warmup Iteration   2: 10.109 ops/ms
# Warmup Iteration   3: 10.436 ops/ms
Iteration   1: 10.127 ops/ms
Iteration   2: 10.442 ops/ms
Iteration   3: 10.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.270 ±(99.9%) 2.906 ops/ms [Average]
  (min, avg, max) = (10.127, 10.270, 10.442), stdev = 0.159
  CI (99.9%): [7.364, 13.176] (assumes normal distribution)


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
# Warmup Iteration   1: 7.586 ops/ms
# Warmup Iteration   2: 8.217 ops/ms
# Warmup Iteration   3: 8.274 ops/ms
Iteration   1: 8.396 ops/ms
Iteration   2: 8.295 ops/ms
Iteration   3: 8.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.334 ±(99.9%) 0.981 ops/ms [Average]
  (min, avg, max) = (8.295, 8.334, 8.396), stdev = 0.054
  CI (99.9%): [7.354, 9.315] (assumes normal distribution)


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
# Warmup Iteration   1: 3.969 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.003 ms/op
Iteration   1: 3.091 ±(99.9%) 0.002 ms/op
Iteration   2: 3.117 ±(99.9%) 0.002 ms/op
Iteration   3: 3.110 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.106 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (3.091, 3.106, 3.117), stdev = 0.013
  CI (99.9%): [2.867, 3.345] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.002 ms/op
Iteration   2: 3.019 ±(99.9%) 0.001 ms/op
Iteration   3: 2.972 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.003 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (2.972, 3.003, 3.019), stdev = 0.026
  CI (99.9%): [2.523, 3.483] (assumes normal distribution)


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.002 ms/op
Iteration   1: 3.124 ±(99.9%) 0.002 ms/op
Iteration   2: 3.127 ±(99.9%) 0.002 ms/op
Iteration   3: 3.082 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.111 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.082, 3.111, 3.127), stdev = 0.025
  CI (99.9%): [2.652, 3.571] (assumes normal distribution)


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
# Warmup Iteration   1: 4.849 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.035 ms/op
Iteration   1: 3.827 ±(99.9%) 0.023 ms/op
Iteration   2: 3.839 ±(99.9%) 0.027 ms/op
Iteration   3: 3.831 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.832 ±(99.9%) 0.112 ms/op [Average]
  (min, avg, max) = (3.827, 3.832, 3.839), stdev = 0.006
  CI (99.9%): [3.721, 3.944] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.006 ms/op
Iteration   1: 3.103 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.338 ms/op
                 createUser·p0.9999: 11.780 ms/op
                 createUser·p1.00:   11.960 ms/op

Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  7.507 ms/op
                 createUser·p0.9999: 14.313 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  9.142 ms/op
                 createUser·p0.9999: 21.332 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308536
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15678 
    [ 2.500,  5.000) = 290882 
    [ 5.000,  7.500) = 1534 
    [ 7.500, 10.000) = 186 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.249 ms/op
     p(99.9900) =     15.827 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.005 ms/op
Iteration   1: 2.942 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.709 ms/op
                 existUser·p0.9999: 11.659 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.793 ms/op
                 existUser·p0.9999: 12.659 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  10.105 ms/op
                 existUser·p0.9999: 15.024 ms/op
                 existUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321750
  mean =      2.980 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1272 
    [ 1.250,  2.500) = 25716 
    [ 2.500,  3.750) = 281211 
    [ 3.750,  5.000) = 12111 
    [ 5.000,  6.250) = 730 
    [ 6.250,  7.500) = 347 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.709 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     15.174 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 4.169 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  8.055 ms/op
                 getUser·p0.9999: 20.742 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.135 ms/op
                 getUser·p0.999:  7.717 ms/op
                 getUser·p0.9999: 18.730 ms/op
                 getUser·p1.00:   19.399 ms/op

Iteration   3: 3.154 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.090 ms/op
                 getUser·p0.9999: 20.241 ms/op
                 getUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309381
  mean =      3.102 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9641 
    [ 2.500,  5.000) = 298582 
    [ 5.000,  7.500) = 816 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      7.651 ms/op
     p(99.9900) =     20.154 ms/op
     p(99.9990) =     21.064 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.009 ms/op
Iteration   1: 3.920 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  12.571 ms/op
                 listUser·p0.9999: 15.005 ms/op
                 listUser·p1.00:   16.269 ms/op

Iteration   2: 3.849 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  12.321 ms/op
                 listUser·p0.9999: 13.381 ms/op
                 listUser·p1.00:   13.713 ms/op

Iteration   3: 3.914 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  14.018 ms/op
                 listUser·p0.9999: 17.809 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246520
  mean =      3.894 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 3145 
    [ 2.500,  3.750) = 100754 
    [ 3.750,  5.000) = 129200 
    [ 5.000,  6.250) = 9173 
    [ 6.250,  7.500) = 3523 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 142 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     17.129 ms/op
     p(99.9990) =     18.092 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.289 ± 0.960  ops/ms
ClientGrpc.existUser                       thrpt       3  10.768 ± 3.054  ops/ms
ClientGrpc.getUser                         thrpt       3  10.270 ± 2.906  ops/ms
ClientGrpc.listUser                        thrpt       3   8.334 ± 0.981  ops/ms
ClientGrpc.createUser                       avgt       3   3.106 ± 0.239   ms/op
ClientGrpc.existUser                        avgt       3   3.003 ± 0.480   ms/op
ClientGrpc.getUser                          avgt       3   3.111 ± 0.460   ms/op
ClientGrpc.listUser                         avgt       3   3.832 ± 0.112   ms/op
ClientGrpc.createUser                     sample  308536   3.111 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.752           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.249           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.827           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.365           ms/op
ClientGrpc.existUser                      sample  321750   2.980 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.603           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.709           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.729           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.497           ms/op
ClientGrpc.getUser                        sample  309381   3.102 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.590           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.186           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.651           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.154           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.135           ms/op
ClientGrpc.listUser                       sample  246520   3.894 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.116           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.480           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.763           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.129           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.940           ms/op
