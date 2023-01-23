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
# Warmup Iteration   1: 4.642 ops/ms
# Warmup Iteration   2: 9.107 ops/ms
# Warmup Iteration   3: 10.083 ops/ms
Iteration   1: 10.066 ops/ms
Iteration   2: 10.036 ops/ms
Iteration   3: 9.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.026 ±(99.9%) 0.845 ops/ms [Average]
  (min, avg, max) = (9.975, 10.026, 10.066), stdev = 0.046
  CI (99.9%): [9.180, 10.871] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.519 ops/ms
# Warmup Iteration   2: 10.366 ops/ms
# Warmup Iteration   3: 10.460 ops/ms
Iteration   1: 10.472 ops/ms
Iteration   2: 11.020 ops/ms
Iteration   3: 10.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.648 ±(99.9%) 5.869 ops/ms [Average]
  (min, avg, max) = (10.453, 10.648, 11.020), stdev = 0.322
  CI (99.9%): [4.780, 16.517] (assumes normal distribution)


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
# Warmup Iteration   1: 7.013 ops/ms
# Warmup Iteration   2: 10.022 ops/ms
# Warmup Iteration   3: 9.899 ops/ms
Iteration   1: 10.076 ops/ms
Iteration   2: 10.179 ops/ms
Iteration   3: 10.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.186 ±(99.9%) 2.075 ops/ms [Average]
  (min, avg, max) = (10.076, 10.186, 10.304), stdev = 0.114
  CI (99.9%): [8.111, 12.261] (assumes normal distribution)


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
# Warmup Iteration   1: 6.552 ops/ms
# Warmup Iteration   2: 7.529 ops/ms
# Warmup Iteration   3: 7.891 ops/ms
Iteration   1: 7.690 ops/ms
Iteration   2: 7.864 ops/ms
Iteration   3: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.905 ±(99.9%) 4.340 ops/ms [Average]
  (min, avg, max) = (7.690, 7.905, 8.161), stdev = 0.238
  CI (99.9%): [3.566, 12.245] (assumes normal distribution)


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.006 ms/op
Iteration   1: 3.181 ±(99.9%) 0.002 ms/op
Iteration   2: 3.236 ±(99.9%) 0.002 ms/op
Iteration   3: 3.164 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.194 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (3.164, 3.194, 3.236), stdev = 0.038
  CI (99.9%): [2.506, 3.882] (assumes normal distribution)


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.002 ms/op
Iteration   1: 2.997 ±(99.9%) 0.002 ms/op
Iteration   2: 3.019 ±(99.9%) 0.001 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.004 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (2.995, 3.004, 3.019), stdev = 0.013
  CI (99.9%): [2.761, 3.247] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.178 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.002 ms/op
Iteration   1: 3.184 ±(99.9%) 0.002 ms/op
Iteration   2: 3.146 ±(99.9%) 0.002 ms/op
Iteration   3: 3.204 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.178 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (3.146, 3.178, 3.204), stdev = 0.030
  CI (99.9%): [2.632, 3.724] (assumes normal distribution)


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
# Warmup Iteration   1: 5.659 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.008 ms/op
Iteration   1: 3.992 ±(99.9%) 0.012 ms/op
Iteration   2: 3.944 ±(99.9%) 0.011 ms/op
Iteration   3: 3.931 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.956 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (3.931, 3.956, 3.992), stdev = 0.032
  CI (99.9%): [3.363, 4.548] (assumes normal distribution)


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.007 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  7.148 ms/op
                 createUser·p0.9999: 12.849 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 3.140 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.497 ms/op
                 createUser·p0.9999: 14.225 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   3: 3.113 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.027 ms/op
                 createUser·p0.9999: 16.857 ms/op
                 createUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307130
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 334 
    [ 1.250,  2.500) = 26382 
    [ 2.500,  3.750) = 247981 
    [ 3.750,  5.000) = 30785 
    [ 5.000,  6.250) = 1003 
    [ 6.250,  7.500) = 318 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.609 ms/op
     p(99.9900) =     16.059 ms/op
     p(99.9990) =     17.037 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  6.504 ms/op
                 existUser·p0.9999: 11.862 ms/op
                 existUser·p1.00:   12.141 ms/op

Iteration   2: 2.989 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  9.159 ms/op
                 existUser·p0.9999: 14.964 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  10.020 ms/op
                 existUser·p0.9999: 27.270 ms/op
                 existUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321343
  mean =      2.987 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49340 
    [ 2.500,  5.000) = 270716 
    [ 5.000,  7.500) = 901 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.388 ms/op
     p(99.9900) =     25.326 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 4.563 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.006 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.245 ms/op
                 getUser·p0.9999: 13.181 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.433 ms/op
                 getUser·p0.9999: 19.820 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.389 ms/op
                 getUser·p0.9999: 16.442 ms/op
                 getUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308991
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24879 
    [ 2.500,  5.000) = 282713 
    [ 5.000,  7.500) = 1116 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.348 ms/op
     p(99.9900) =     18.367 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 5.971 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.011 ms/op
Iteration   1: 4.020 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  14.613 ms/op
                 listUser·p0.9999: 20.056 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 3.990 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  14.186 ms/op
                 listUser·p0.9999: 18.152 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 4.007 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  18.729 ms/op
                 listUser·p0.9999: 24.415 ms/op
                 listUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239526
  mean =      4.006 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3312 
    [ 2.500,  5.000) = 209555 
    [ 5.000,  7.500) = 25220 
    [ 7.500, 10.000) = 935 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.590 ms/op
     p(99.9900) =     23.891 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.026 ± 0.845  ops/ms
ClientGrpc.existUser                       thrpt       3  10.648 ± 5.869  ops/ms
ClientGrpc.getUser                         thrpt       3  10.186 ± 2.075  ops/ms
ClientGrpc.listUser                        thrpt       3   7.905 ± 4.340  ops/ms
ClientGrpc.createUser                       avgt       3   3.194 ± 0.688   ms/op
ClientGrpc.existUser                        avgt       3   3.004 ± 0.243   ms/op
ClientGrpc.getUser                          avgt       3   3.178 ± 0.546   ms/op
ClientGrpc.listUser                         avgt       3   3.956 ± 0.593   ms/op
ClientGrpc.createUser                     sample  307130   3.125 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.641           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.609           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.059           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.105           ms/op
ClientGrpc.existUser                      sample  321343   2.987 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.712           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.388           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.326           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.213           ms/op
ClientGrpc.getUser                        sample  308991   3.105 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.741           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.348           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.367           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  239526   4.006 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.956           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.590           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.891           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.264           ms/op
