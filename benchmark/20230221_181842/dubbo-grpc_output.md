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
# Warmup Iteration   1: 5.018 ops/ms
# Warmup Iteration   2: 9.536 ops/ms
# Warmup Iteration   3: 10.517 ops/ms
Iteration   1: 10.438 ops/ms
Iteration   2: 10.624 ops/ms
Iteration   3: 10.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.491 ±(99.9%) 2.107 ops/ms [Average]
  (min, avg, max) = (10.412, 10.491, 10.624), stdev = 0.115
  CI (99.9%): [8.384, 12.599] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.726 ops/ms
# Warmup Iteration   2: 10.503 ops/ms
# Warmup Iteration   3: 10.710 ops/ms
Iteration   1: 11.199 ops/ms
Iteration   2: 11.006 ops/ms
Iteration   3: 10.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.017 ±(99.9%) 3.226 ops/ms [Average]
  (min, avg, max) = (10.846, 11.017, 11.199), stdev = 0.177
  CI (99.9%): [7.791, 14.243] (assumes normal distribution)


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
# Warmup Iteration   1: 8.356 ops/ms
# Warmup Iteration   2: 10.476 ops/ms
# Warmup Iteration   3: 10.450 ops/ms
Iteration   1: 10.477 ops/ms
Iteration   2: 10.381 ops/ms
Iteration   3: 10.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.353 ±(99.9%) 2.575 ops/ms [Average]
  (min, avg, max) = (10.199, 10.353, 10.477), stdev = 0.141
  CI (99.9%): [7.777, 12.928] (assumes normal distribution)


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
# Warmup Iteration   1: 6.178 ops/ms
# Warmup Iteration   2: 7.968 ops/ms
# Warmup Iteration   3: 8.009 ops/ms
Iteration   1: 8.056 ops/ms
Iteration   2: 8.181 ops/ms
Iteration   3: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.204 ±(99.9%) 2.927 ops/ms [Average]
  (min, avg, max) = (8.056, 8.204, 8.374), stdev = 0.160
  CI (99.9%): [5.276, 11.131] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.893 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.002 ms/op
Iteration   1: 3.064 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
Iteration   3: 3.088 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.053 ±(99.9%) 0.776 ms/op [Average]
  (min, avg, max) = (3.005, 3.053, 3.088), stdev = 0.043
  CI (99.9%): [2.277, 3.829] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.653 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.004 ms/op
Iteration   1: 2.961 ±(99.9%) 0.002 ms/op
Iteration   2: 2.852 ±(99.9%) 0.003 ms/op
Iteration   3: 2.876 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.896 ±(99.9%) 1.047 ms/op [Average]
  (min, avg, max) = (2.852, 2.896, 2.961), stdev = 0.057
  CI (99.9%): [1.849, 3.943] (assumes normal distribution)


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.003 ms/op
Iteration   1: 3.018 ±(99.9%) 0.002 ms/op
Iteration   2: 3.074 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.059 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (3.018, 3.059, 3.084), stdev = 0.035
  CI (99.9%): [2.412, 3.706] (assumes normal distribution)


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
# Warmup Iteration   1: 4.943 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.028 ms/op
Iteration   1: 3.934 ±(99.9%) 0.028 ms/op
Iteration   2: 3.973 ±(99.9%) 0.008 ms/op
Iteration   3: 3.881 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.930 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (3.881, 3.930, 3.973), stdev = 0.046
  CI (99.9%): [3.087, 4.772] (assumes normal distribution)


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.005 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.523 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.984 ms/op
                 createUser·p0.9999: 11.629 ms/op
                 createUser·p1.00:   11.878 ms/op

Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.333 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  10.788 ms/op
                 createUser·p0.9999: 18.692 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  8.816 ms/op
                 createUser·p0.9999: 23.691 ms/op
                 createUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313697
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27838 
    [ 2.500,  5.000) = 284855 
    [ 5.000,  7.500) = 620 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      9.152 ms/op
     p(99.9900) =     23.057 ms/op
     p(99.9990) =     23.949 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.006 ms/op
Iteration   1: 2.864 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.865 ms/op
                 existUser·p0.9999: 16.327 ms/op
                 existUser·p1.00:   16.597 ms/op

Iteration   2: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.365 ms/op
                 existUser·p0.9999: 12.748 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   3: 2.948 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  7.844 ms/op
                 existUser·p0.9999: 27.432 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329779
  mean =      2.911 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49002 
    [ 2.500,  5.000) = 279805 
    [ 5.000,  7.500) = 675 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.309 ms/op
     p(99.9900) =     16.825 ms/op
     p(99.9990) =     27.712 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.165 ms/op
                 getUser·p0.9999: 17.513 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.144 ms/op
                 getUser·p0.999:  6.368 ms/op
                 getUser·p0.9999: 16.030 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   3: 2.960 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.593 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.095 ms/op
                 getUser·p0.9999: 13.995 ms/op
                 getUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319818
  mean =      3.001 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1727 
    [ 1.250,  2.500) = 25066 
    [ 2.500,  3.750) = 277773 
    [ 3.750,  5.000) = 14459 
    [ 5.000,  6.250) = 418 
    [ 6.250,  7.500) = 144 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.621 ms/op
     p(99.9900) =     16.680 ms/op
     p(99.9990) =     17.688 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.012 ms/op
Iteration   1: 3.986 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.567 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  12.169 ms/op
                 listUser·p0.9999: 15.252 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   2: 3.851 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  17.562 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.922 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  14.032 ms/op
                 listUser·p0.9999: 19.941 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244815
  mean =      3.919 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4514 
    [ 2.500,  5.000) = 214780 
    [ 5.000,  7.500) = 24483 
    [ 7.500, 10.000) = 567 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     20.088 ms/op
     p(99.9990) =     20.687 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.491 ± 2.107  ops/ms
ClientGrpc.existUser                       thrpt       3  11.017 ± 3.226  ops/ms
ClientGrpc.getUser                         thrpt       3  10.353 ± 2.575  ops/ms
ClientGrpc.listUser                        thrpt       3   8.204 ± 2.927  ops/ms
ClientGrpc.createUser                       avgt       3   3.053 ± 0.776   ms/op
ClientGrpc.existUser                        avgt       3   2.896 ± 1.047   ms/op
ClientGrpc.getUser                          avgt       3   3.059 ± 0.647   ms/op
ClientGrpc.listUser                         avgt       3   3.930 ± 0.842   ms/op
ClientGrpc.createUser                     sample  313697   3.062 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.333           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.152           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.057           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.117           ms/op
ClientGrpc.existUser                      sample  329779   2.911 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.545           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.309           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.825           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.787           ms/op
ClientGrpc.getUser                        sample  319818   3.001 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.554           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.621           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.680           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.859           ms/op
ClientGrpc.listUser                       sample  244815   3.919 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.567           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.992           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.088           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.775           ms/op
