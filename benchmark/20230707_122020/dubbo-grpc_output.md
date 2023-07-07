# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.176 ops/ms
# Warmup Iteration   2: 7.409 ops/ms
# Warmup Iteration   3: 8.859 ops/ms
Iteration   1: 9.314 ops/ms
Iteration   2: 9.730 ops/ms
Iteration   3: 9.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.503 ±(99.9%) 3.847 ops/ms [Average]
  (min, avg, max) = (9.314, 9.503, 9.730), stdev = 0.211
  CI (99.9%): [5.656, 13.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.048 ops/ms
# Warmup Iteration   2: 9.723 ops/ms
# Warmup Iteration   3: 10.304 ops/ms
Iteration   1: 10.364 ops/ms
Iteration   2: 10.171 ops/ms
Iteration   3: 10.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.281 ±(99.9%) 1.815 ops/ms [Average]
  (min, avg, max) = (10.171, 10.281, 10.364), stdev = 0.099
  CI (99.9%): [8.466, 12.096] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.198 ops/ms
# Warmup Iteration   2: 8.804 ops/ms
# Warmup Iteration   3: 9.485 ops/ms
Iteration   1: 10.093 ops/ms
Iteration   2: 9.975 ops/ms
Iteration   3: 9.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.934 ±(99.9%) 3.347 ops/ms [Average]
  (min, avg, max) = (9.733, 9.934, 10.093), stdev = 0.183
  CI (99.9%): [6.587, 13.281] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.214 ops/ms
# Warmup Iteration   2: 6.676 ops/ms
# Warmup Iteration   3: 7.321 ops/ms
Iteration   1: 7.290 ops/ms
Iteration   2: 7.207 ops/ms
Iteration   3: 7.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.310 ±(99.9%) 2.074 ops/ms [Average]
  (min, avg, max) = (7.207, 7.310, 7.432), stdev = 0.114
  CI (99.9%): [5.236, 9.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.082 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.002 ms/op
Iteration   1: 3.310 ±(99.9%) 0.003 ms/op
Iteration   2: 3.218 ±(99.9%) 0.002 ms/op
Iteration   3: 3.366 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.298 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.218, 3.298, 3.366), stdev = 0.075
  CI (99.9%): [1.935, 4.660] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.673 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.002 ms/op
Iteration   1: 3.060 ±(99.9%) 0.002 ms/op
Iteration   2: 3.200 ±(99.9%) 0.003 ms/op
Iteration   3: 3.043 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.101 ±(99.9%) 1.571 ms/op [Average]
  (min, avg, max) = (3.043, 3.101, 3.200), stdev = 0.086
  CI (99.9%): [1.530, 4.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.649 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.383 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.003 ms/op
Iteration   1: 3.152 ±(99.9%) 0.001 ms/op
Iteration   2: 3.155 ±(99.9%) 0.002 ms/op
Iteration   3: 3.124 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.144 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.124, 3.144, 3.155), stdev = 0.017
  CI (99.9%): [2.828, 3.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.697 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.197 ±(99.9%) 0.024 ms/op
Iteration   1: 4.124 ±(99.9%) 0.015 ms/op
Iteration   2: 4.204 ±(99.9%) 0.019 ms/op
Iteration   3: 4.133 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.154 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (4.124, 4.154, 4.204), stdev = 0.044
  CI (99.9%): [3.353, 4.955] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.316 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
Iteration   1: 3.196 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  9.118 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  9.022 ms/op
                 createUser·p0.9999: 25.887 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 3.176 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  10.956 ms/op
                 createUser·p0.9999: 29.060 ms/op
                 createUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301012
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11878 
    [ 2.500,  5.000) = 286675 
    [ 5.000,  7.500) = 1850 
    [ 7.500, 10.000) = 319 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     28.472 ms/op
     p(99.9990) =     29.521 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.552 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.006 ms/op
Iteration   1: 3.180 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  8.226 ms/op
                 existUser·p0.9999: 15.545 ms/op
                 existUser·p1.00:   15.794 ms/op

Iteration   2: 3.176 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  8.644 ms/op
                 existUser·p0.9999: 15.024 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   3: 3.116 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.371 ms/op
                 existUser·p0.999:  10.813 ms/op
                 existUser·p0.9999: 27.001 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 304050
  mean =      3.157 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12228 
    [ 2.500,  5.000) = 288611 
    [ 5.000,  7.500) = 2456 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.063 ms/op
     p(99.9000) =      8.928 ms/op
     p(99.9900) =     26.221 ms/op
     p(99.9990) =     27.293 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.007 ms/op
Iteration   1: 3.350 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  8.462 ms/op
                 getUser·p0.9999: 14.261 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 3.251 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  7.803 ms/op
                 getUser·p0.9999: 19.895 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   3: 3.282 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  9.325 ms/op
                 getUser·p0.9999: 18.235 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 291550
  mean =      3.294 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8312 
    [ 2.500,  5.000) = 280298 
    [ 5.000,  7.500) = 2461 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =      8.462 ms/op
     p(99.9900) =     19.351 ms/op
     p(99.9990) =     20.527 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.259 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.013 ms/op
Iteration   1: 4.135 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  15.035 ms/op
                 listUser·p0.9999: 18.195 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   2: 4.189 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.605 ms/op
                 listUser·p0.999:  17.593 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   3: 4.307 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 27.351 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228079
  mean =      4.209 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2080 
    [ 2.500,  5.000) = 191120 
    [ 5.000,  7.500) = 32191 
    [ 7.500, 10.000) = 2064 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      7.678 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     25.434 ms/op
     p(99.9990) =     27.971 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.503 ± 3.847  ops/ms
ClientGrpc.existUser                       thrpt       3  10.281 ± 1.815  ops/ms
ClientGrpc.getUser                         thrpt       3   9.934 ± 3.347  ops/ms
ClientGrpc.listUser                        thrpt       3   7.310 ± 2.074  ops/ms
ClientGrpc.createUser                       avgt       3   3.298 ± 1.363   ms/op
ClientGrpc.existUser                        avgt       3   3.101 ± 1.571   ms/op
ClientGrpc.getUser                          avgt       3   3.144 ± 0.316   ms/op
ClientGrpc.listUser                         avgt       3   4.154 ± 0.801   ms/op
ClientGrpc.createUser                     sample  301012   3.190 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.708           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.404           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.472           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.753           ms/op
ClientGrpc.existUser                      sample  304050   3.157 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.756           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.101           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.063           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.928           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.221           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.361           ms/op
ClientGrpc.getUser                        sample  291550   3.294 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.772           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.236           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.190           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.462           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.351           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  228079   4.209 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.137           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.981           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.185           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.678           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.236           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.434           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.082           ms/op
