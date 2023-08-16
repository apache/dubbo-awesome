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
# Warmup Iteration   1: 3.879 ops/ms
# Warmup Iteration   2: 7.439 ops/ms
# Warmup Iteration   3: 8.732 ops/ms
Iteration   1: 9.115 ops/ms
Iteration   2: 9.348 ops/ms
Iteration   3: 9.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.303 ±(99.9%) 3.102 ops/ms [Average]
  (min, avg, max) = (9.115, 9.303, 9.445), stdev = 0.170
  CI (99.9%): [6.201, 12.404] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.553 ops/ms
# Warmup Iteration   2: 9.246 ops/ms
# Warmup Iteration   3: 9.708 ops/ms
Iteration   1: 9.760 ops/ms
Iteration   2: 9.820 ops/ms
Iteration   3: 9.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.721 ±(99.9%) 2.248 ops/ms [Average]
  (min, avg, max) = (9.583, 9.721, 9.820), stdev = 0.123
  CI (99.9%): [7.473, 11.969] (assumes normal distribution)


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
# Warmup Iteration   1: 6.237 ops/ms
# Warmup Iteration   2: 8.803 ops/ms
# Warmup Iteration   3: 9.112 ops/ms
Iteration   1: 9.207 ops/ms
Iteration   2: 9.345 ops/ms
Iteration   3: 9.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.250 ±(99.9%) 1.512 ops/ms [Average]
  (min, avg, max) = (9.197, 9.250, 9.345), stdev = 0.083
  CI (99.9%): [7.738, 10.762] (assumes normal distribution)


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
# Warmup Iteration   1: 4.866 ops/ms
# Warmup Iteration   2: 6.807 ops/ms
# Warmup Iteration   3: 7.059 ops/ms
Iteration   1: 7.138 ops/ms
Iteration   2: 7.194 ops/ms
Iteration   3: 7.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.181 ±(99.9%) 0.695 ops/ms [Average]
  (min, avg, max) = (7.138, 7.181, 7.211), stdev = 0.038
  CI (99.9%): [6.486, 7.876] (assumes normal distribution)


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
# Warmup Iteration   1: 5.048 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.002 ms/op
Iteration   1: 3.530 ±(99.9%) 0.005 ms/op
Iteration   2: 3.465 ±(99.9%) 0.005 ms/op
Iteration   3: 3.451 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.482 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (3.451, 3.482, 3.530), stdev = 0.042
  CI (99.9%): [2.712, 4.252] (assumes normal distribution)


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.005 ms/op
Iteration   1: 3.282 ±(99.9%) 0.004 ms/op
Iteration   2: 3.333 ±(99.9%) 0.002 ms/op
Iteration   3: 3.242 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.286 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (3.242, 3.286, 3.333), stdev = 0.045
  CI (99.9%): [2.458, 4.114] (assumes normal distribution)


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
# Warmup Iteration   1: 4.828 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.005 ms/op
Iteration   1: 3.374 ±(99.9%) 0.004 ms/op
Iteration   2: 3.446 ±(99.9%) 0.006 ms/op
Iteration   3: 3.419 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.413 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (3.374, 3.413, 3.446), stdev = 0.036
  CI (99.9%): [2.752, 4.074] (assumes normal distribution)


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
# Warmup Iteration   1: 5.727 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.617 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.438 ±(99.9%) 0.007 ms/op
Iteration   1: 4.487 ±(99.9%) 0.031 ms/op
Iteration   2: 4.529 ±(99.9%) 0.014 ms/op
Iteration   3: 4.404 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.474 ±(99.9%) 1.161 ms/op [Average]
  (min, avg, max) = (4.404, 4.474, 4.529), stdev = 0.064
  CI (99.9%): [3.313, 5.634] (assumes normal distribution)


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
# Warmup Iteration   1: 4.889 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.007 ms/op
Iteration   1: 3.374 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  8.847 ms/op
                 createUser·p0.9999: 13.861 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   2: 3.359 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.404 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.593 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.400 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  9.041 ms/op
                 createUser·p0.9999: 22.556 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 284188
  mean =      3.378 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16767 
    [ 2.500,  5.000) = 263275 
    [ 5.000,  7.500) = 3543 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      8.959 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     23.112 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.007 ms/op
Iteration   1: 3.288 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  8.867 ms/op
                 existUser·p0.9999: 16.130 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   2: 3.284 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.958 ms/op
                 existUser·p0.99:   5.024 ms/op
                 existUser·p0.999:  8.606 ms/op
                 existUser·p0.9999: 14.963 ms/op
                 existUser·p1.00:   18.285 ms/op

Iteration   3: 3.329 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   4.702 ms/op
                 existUser·p0.999:  11.621 ms/op
                 existUser·p0.9999: 18.769 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 290842
  mean =      3.300 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 563 
    [ 1.250,  2.500) = 10948 
    [ 2.500,  3.750) = 244453 
    [ 3.750,  5.000) = 32234 
    [ 5.000,  6.250) = 1704 
    [ 6.250,  7.500) = 374 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =      8.915 ms/op
     p(99.9900) =     16.759 ms/op
     p(99.9990) =     19.050 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 4.493 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.008 ms/op
Iteration   1: 3.439 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.048 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  9.732 ms/op
                 getUser·p0.9999: 15.019 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   2: 3.426 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.384 ms/op
                 getUser·p0.999:  8.923 ms/op
                 getUser·p0.9999: 18.163 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  9.746 ms/op
                 getUser·p0.9999: 21.103 ms/op
                 getUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 282581
  mean =      3.396 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14481 
    [ 2.500,  5.000) = 263797 
    [ 5.000,  7.500) = 3549 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     22.452 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 6.634 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.750 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.493 ±(99.9%) 0.013 ms/op
Iteration   1: 4.478 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.365 ms/op
                 listUser·p0.99:   7.942 ms/op
                 listUser·p0.999:  16.995 ms/op
                 listUser·p0.9999: 24.440 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 4.445 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.645 ms/op
                 listUser·p0.999:  15.676 ms/op
                 listUser·p0.9999: 29.531 ms/op
                 listUser·p1.00:   29.819 ms/op

Iteration   3: 4.397 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   8.028 ms/op
                 listUser·p0.999:  18.793 ms/op
                 listUser·p0.9999: 21.454 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 216167
  mean =      4.440 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 743 
    [ 2.500,  5.000) = 185261 
    [ 5.000,  7.500) = 27010 
    [ 7.500, 10.000) = 2434 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     26.764 ms/op
     p(99.9990) =     29.798 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.303 ± 3.102  ops/ms
ClientGrpc.existUser                       thrpt       3   9.721 ± 2.248  ops/ms
ClientGrpc.getUser                         thrpt       3   9.250 ± 1.512  ops/ms
ClientGrpc.listUser                        thrpt       3   7.181 ± 0.695  ops/ms
ClientGrpc.createUser                       avgt       3   3.482 ± 0.770   ms/op
ClientGrpc.existUser                        avgt       3   3.286 ± 0.828   ms/op
ClientGrpc.getUser                          avgt       3   3.413 ± 0.661   ms/op
ClientGrpc.listUser                         avgt       3   4.474 ± 1.161   ms/op
ClientGrpc.createUser                     sample  284188   3.378 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.404           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.383           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.959           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.823           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.200           ms/op
ClientGrpc.existUser                      sample  290842   3.300 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.804           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.915           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.759           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.235           ms/op
ClientGrpc.getUser                        sample  282581   3.396 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.707           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.383           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.503           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.775           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.200           ms/op
ClientGrpc.listUser                       sample  216167   4.440 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.022           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.268           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.399           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.218           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.864           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.695           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.764           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.819           ms/op
