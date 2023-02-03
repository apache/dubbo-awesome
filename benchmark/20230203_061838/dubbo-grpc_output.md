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
# Warmup Iteration   1: 4.546 ops/ms
# Warmup Iteration   2: 9.102 ops/ms
# Warmup Iteration   3: 10.029 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 10.125 ops/ms
Iteration   3: 10.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.213 ±(99.9%) 4.838 ops/ms [Average]
  (min, avg, max) = (10.003, 10.213, 10.511), stdev = 0.265
  CI (99.9%): [5.375, 15.052] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.791 ops/ms
# Warmup Iteration   2: 10.665 ops/ms
# Warmup Iteration   3: 10.365 ops/ms
Iteration   1: 10.507 ops/ms
Iteration   2: 10.995 ops/ms
Iteration   3: 11.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.850 ±(99.9%) 5.436 ops/ms [Average]
  (min, avg, max) = (10.507, 10.850, 11.048), stdev = 0.298
  CI (99.9%): [5.414, 16.286] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.196 ops/ms
# Warmup Iteration   2: 10.171 ops/ms
# Warmup Iteration   3: 10.307 ops/ms
Iteration   1: 10.390 ops/ms
Iteration   2: 10.239 ops/ms
Iteration   3: 10.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.435 ±(99.9%) 4.062 ops/ms [Average]
  (min, avg, max) = (10.239, 10.435, 10.677), stdev = 0.223
  CI (99.9%): [6.374, 14.497] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.968 ops/ms
# Warmup Iteration   2: 7.544 ops/ms
# Warmup Iteration   3: 7.986 ops/ms
Iteration   1: 7.960 ops/ms
Iteration   2: 7.967 ops/ms
Iteration   3: 7.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.939 ±(99.9%) 0.759 ops/ms [Average]
  (min, avg, max) = (7.892, 7.939, 7.967), stdev = 0.042
  CI (99.9%): [7.180, 8.698] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.001 ms/op
Iteration   2: 3.185 ±(99.9%) 0.002 ms/op
Iteration   3: 3.083 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.118 ±(99.9%) 1.058 ms/op [Average]
  (min, avg, max) = (3.083, 3.118, 3.185), stdev = 0.058
  CI (99.9%): [2.060, 4.177] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.864 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.002 ms/op
Iteration   2: 2.961 ±(99.9%) 0.002 ms/op
Iteration   3: 2.945 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.972 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (2.945, 2.972, 3.011), stdev = 0.034
  CI (99.9%): [2.344, 3.601] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.826 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.003 ms/op
Iteration   1: 3.052 ±(99.9%) 0.003 ms/op
Iteration   2: 3.123 ±(99.9%) 0.002 ms/op
Iteration   3: 3.068 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.081 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (3.052, 3.081, 3.123), stdev = 0.037
  CI (99.9%): [2.400, 3.762] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.218 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.138 ±(99.9%) 0.013 ms/op
Iteration   1: 3.992 ±(99.9%) 0.008 ms/op
Iteration   2: 3.954 ±(99.9%) 0.055 ms/op
Iteration   3: 3.939 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.962 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.939, 3.962, 3.992), stdev = 0.027
  CI (99.9%): [3.460, 4.463] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
Iteration   1: 2.971 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.566 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  6.423 ms/op
                 createUser·p0.9999: 22.486 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  9.052 ms/op
                 createUser·p0.9999: 19.227 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 21.500 ms/op
                 createUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314703
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29573 
    [ 2.500,  5.000) = 284104 
    [ 5.000,  7.500) = 673 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.349 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     22.703 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.806 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.511 ms/op
                 existUser·p0.9999: 10.934 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   2: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.408 ms/op
                 existUser·p0.9999: 21.139 ms/op
                 existUser·p1.00:   21.660 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  10.715 ms/op
                 existUser·p0.9999: 17.520 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321983
  mean =      2.982 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42656 
    [ 2.500,  5.000) = 278398 
    [ 5.000,  7.500) = 625 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.356 ms/op
     p(99.9900) =     19.421 ms/op
     p(99.9990) =     21.580 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.877 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
Iteration   1: 3.086 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  9.198 ms/op
                 getUser·p0.9999: 20.283 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.471 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.696 ms/op
                 getUser·p0.9999: 16.576 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.623 ms/op
                 getUser·p0.9999: 18.266 ms/op
                 getUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313824
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26517 
    [ 2.500,  5.000) = 286011 
    [ 5.000,  7.500) = 922 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.333 ms/op
     p(99.9900) =     19.283 ms/op
     p(99.9990) =     20.748 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 5.317 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.010 ms/op
Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.529 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.632 ms/op
                 listUser·p0.999:  11.226 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 4.123 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 15.143 ms/op
                 listUser·p1.00:   16.122 ms/op

Iteration   3: 3.883 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.842 ms/op
                 listUser·p0.999:  16.359 ms/op
                 listUser·p0.9999: 32.727 ms/op
                 listUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240797
  mean =      3.985 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3866 
    [ 2.500,  5.000) = 205244 
    [ 5.000,  7.500) = 30452 
    [ 7.500, 10.000) = 764 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     31.097 ms/op
     p(99.9990) =     33.062 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.213 ± 4.838  ops/ms
ClientGrpc.existUser                       thrpt       3  10.850 ± 5.436  ops/ms
ClientGrpc.getUser                         thrpt       3  10.435 ± 4.062  ops/ms
ClientGrpc.listUser                        thrpt       3   7.939 ± 0.759  ops/ms
ClientGrpc.createUser                       avgt       3   3.118 ± 1.058   ms/op
ClientGrpc.existUser                        avgt       3   2.972 ± 0.629   ms/op
ClientGrpc.getUser                          avgt       3   3.081 ± 0.681   ms/op
ClientGrpc.listUser                         avgt       3   3.962 ± 0.502   ms/op
ClientGrpc.createUser                     sample  314703   3.050 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.566           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.349           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.660           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.839           ms/op
ClientGrpc.existUser                      sample  321983   2.982 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.478           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.356           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.421           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.660           ms/op
ClientGrpc.getUser                        sample  313824   3.059 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.471           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.333           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.283           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  240797   3.985 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.529           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.844           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.097           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.161           ms/op
