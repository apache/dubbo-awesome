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
# Warmup Iteration   1: 3.739 ops/ms
# Warmup Iteration   2: 8.653 ops/ms
# Warmup Iteration   3: 9.822 ops/ms
Iteration   1: 10.239 ops/ms
Iteration   2: 10.139 ops/ms
Iteration   3: 10.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.160 ±(99.9%) 1.288 ops/ms [Average]
  (min, avg, max) = (10.103, 10.160, 10.239), stdev = 0.071
  CI (99.9%): [8.873, 11.448] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.283 ops/ms
# Warmup Iteration   2: 9.992 ops/ms
# Warmup Iteration   3: 10.775 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 10.833 ops/ms
Iteration   3: 10.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.640 ±(99.9%) 3.039 ops/ms [Average]
  (min, avg, max) = (10.537, 10.640, 10.833), stdev = 0.167
  CI (99.9%): [7.602, 13.679] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.607 ops/ms
# Warmup Iteration   2: 9.764 ops/ms
# Warmup Iteration   3: 9.836 ops/ms
Iteration   1: 10.236 ops/ms
Iteration   2: 10.167 ops/ms
Iteration   3: 10.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.180 ±(99.9%) 0.936 ops/ms [Average]
  (min, avg, max) = (10.136, 10.180, 10.236), stdev = 0.051
  CI (99.9%): [9.244, 11.116] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.488 ops/ms
# Warmup Iteration   2: 7.570 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 8.123 ops/ms
Iteration   2: 8.150 ops/ms
Iteration   3: 8.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.142 ±(99.9%) 0.310 ops/ms [Average]
  (min, avg, max) = (8.123, 8.142, 8.155), stdev = 0.017
  CI (99.9%): [7.832, 8.453] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.539 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.004 ms/op
Iteration   1: 3.141 ±(99.9%) 0.003 ms/op
Iteration   2: 3.115 ±(99.9%) 0.003 ms/op
Iteration   3: 3.226 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.161 ±(99.9%) 1.061 ms/op [Average]
  (min, avg, max) = (3.115, 3.161, 3.226), stdev = 0.058
  CI (99.9%): [2.100, 4.222] (assumes normal distribution)


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.001 ms/op
Iteration   1: 3.085 ±(99.9%) 0.002 ms/op
Iteration   2: 3.069 ±(99.9%) 0.004 ms/op
Iteration   3: 3.056 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.070 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (3.056, 3.070, 3.085), stdev = 0.015
  CI (99.9%): [2.802, 3.337] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.251 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.006 ms/op
Iteration   1: 3.164 ±(99.9%) 0.005 ms/op
Iteration   2: 3.108 ±(99.9%) 0.003 ms/op
Iteration   3: 3.149 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.140 ±(99.9%) 0.528 ms/op [Average]
  (min, avg, max) = (3.108, 3.140, 3.164), stdev = 0.029
  CI (99.9%): [2.612, 3.669] (assumes normal distribution)


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
# Warmup Iteration   1: 5.761 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.026 ms/op
Iteration   1: 3.925 ±(99.9%) 0.019 ms/op
Iteration   2: 3.960 ±(99.9%) 0.027 ms/op
Iteration   3: 3.925 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.937 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (3.925, 3.937, 3.960), stdev = 0.020
  CI (99.9%): [3.571, 4.302] (assumes normal distribution)


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.007 ms/op
Iteration   1: 3.172 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  6.922 ms/op
                 createUser·p0.9999: 16.903 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   2: 3.184 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.994 ms/op
                 createUser·p0.9999: 16.761 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   3: 3.222 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.672 ms/op
                 createUser·p0.999:  15.200 ms/op
                 createUser·p0.9999: 20.087 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300530
  mean =      3.193 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10897 
    [ 2.500,  5.000) = 287605 
    [ 5.000,  7.500) = 1587 
    [ 7.500, 10.000) = 211 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     18.742 ms/op
     p(99.9990) =     20.315 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.703 ms/op
                 existUser·p0.9999: 13.816 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.249 ms/op
                 existUser·p0.999:  13.036 ms/op
                 existUser·p0.9999: 16.286 ms/op
                 existUser·p1.00:   16.613 ms/op

Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  9.372 ms/op
                 existUser·p0.9999: 19.595 ms/op
                 existUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317610
  mean =      3.022 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18959 
    [ 2.500,  5.000) = 296859 
    [ 5.000,  7.500) = 1240 
    [ 7.500, 10.000) = 256 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.472 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     18.954 ms/op
     p(99.9990) =     19.884 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 4.570 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
Iteration   1: 3.194 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  10.789 ms/op
                 getUser·p0.9999: 15.105 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   2: 3.122 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  8.028 ms/op
                 getUser·p0.9999: 22.299 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  8.521 ms/op
                 getUser·p0.9999: 22.381 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305691
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14152 
    [ 2.500,  5.000) = 288607 
    [ 5.000,  7.500) = 2348 
    [ 7.500, 10.000) = 266 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.973 ms/op
     p(99.9000) =     10.278 ms/op
     p(99.9900) =     21.969 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 5.636 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.216 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.013 ms/op
Iteration   1: 3.962 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.643 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  21.201 ms/op
                 listUser·p0.9999: 22.771 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   2: 3.858 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.468 ms/op
                 listUser·p0.9999: 26.144 ms/op
                 listUser·p1.00:   26.935 ms/op

Iteration   3: 3.901 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 23.050 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245617
  mean =      3.907 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2411 
    [ 2.500,  5.000) = 228548 
    [ 5.000,  7.500) = 13146 
    [ 7.500, 10.000) = 1012 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 160 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     18.408 ms/op
     p(99.9900) =     22.886 ms/op
     p(99.9990) =     26.759 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.160 ± 1.288  ops/ms
ClientGrpc.existUser                       thrpt       3  10.640 ± 3.039  ops/ms
ClientGrpc.getUser                         thrpt       3  10.180 ± 0.936  ops/ms
ClientGrpc.listUser                        thrpt       3   8.142 ± 0.310  ops/ms
ClientGrpc.createUser                       avgt       3   3.161 ± 1.061   ms/op
ClientGrpc.existUser                        avgt       3   3.070 ± 0.267   ms/op
ClientGrpc.getUser                          avgt       3   3.140 ± 0.528   ms/op
ClientGrpc.listUser                         avgt       3   3.937 ± 0.366   ms/op
ClientGrpc.createUser                     sample  300530   3.193 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.713           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.150           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.018           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.897           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.742           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.626           ms/op
ClientGrpc.existUser                      sample  317610   3.022 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.507           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.982           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.472           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.667           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.954           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.021           ms/op
ClientGrpc.getUser                        sample  305691   3.140 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.663           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.973           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.278           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.969           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  245617   3.907 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.643           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.415           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.292           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.408           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.886           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.935           ms/op
