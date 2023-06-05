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
# Warmup Iteration   1: 3.775 ops/ms
# Warmup Iteration   2: 7.886 ops/ms
# Warmup Iteration   3: 9.405 ops/ms
Iteration   1: 9.837 ops/ms
Iteration   2: 10.083 ops/ms
Iteration   3: 10.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.978 ±(99.9%) 2.315 ops/ms [Average]
  (min, avg, max) = (9.837, 9.978, 10.083), stdev = 0.127
  CI (99.9%): [7.663, 12.293] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 6.388 ops/ms
# Warmup Iteration   2: 10.209 ops/ms
# Warmup Iteration   3: 10.581 ops/ms
Iteration   1: 10.692 ops/ms
Iteration   2: 10.863 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.756 ±(99.9%) 1.700 ops/ms [Average]
  (min, avg, max) = (10.692, 10.756, 10.863), stdev = 0.093
  CI (99.9%): [9.056, 12.456] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.267 ops/ms
# Warmup Iteration   2: 9.782 ops/ms
# Warmup Iteration   3: 10.094 ops/ms
Iteration   1: 10.136 ops/ms
Iteration   2: 9.952 ops/ms
Iteration   3: 10.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.130 ±(99.9%) 3.212 ops/ms [Average]
  (min, avg, max) = (9.952, 10.130, 10.304), stdev = 0.176
  CI (99.9%): [6.918, 13.343] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.012 ops/ms
# Warmup Iteration   2: 7.122 ops/ms
# Warmup Iteration   3: 7.799 ops/ms
Iteration   1: 7.923 ops/ms
Iteration   2: 7.532 ops/ms
Iteration   3: 7.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.781 ±(99.9%) 3.940 ops/ms [Average]
  (min, avg, max) = (7.532, 7.781, 7.923), stdev = 0.216
  CI (99.9%): [3.841, 11.721] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.654 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.011 ms/op
Iteration   1: 3.124 ±(99.9%) 0.002 ms/op
Iteration   2: 3.224 ±(99.9%) 0.001 ms/op
Iteration   3: 3.127 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.158 ±(99.9%) 1.046 ms/op [Average]
  (min, avg, max) = (3.124, 3.158, 3.224), stdev = 0.057
  CI (99.9%): [2.113, 4.204] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.173 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.002 ms/op
Iteration   1: 2.984 ±(99.9%) 0.002 ms/op
Iteration   2: 3.048 ±(99.9%) 0.002 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.015 ±(99.9%) 0.585 ms/op [Average]
  (min, avg, max) = (2.984, 3.015, 3.048), stdev = 0.032
  CI (99.9%): [2.430, 3.600] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.480 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.002 ms/op
Iteration   1: 3.176 ±(99.9%) 0.002 ms/op
Iteration   2: 3.189 ±(99.9%) 0.002 ms/op
Iteration   3: 3.124 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.163 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (3.124, 3.163, 3.189), stdev = 0.034
  CI (99.9%): [2.538, 3.788] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.832 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.386 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.010 ms/op
Iteration   1: 4.146 ±(99.9%) 0.016 ms/op
Iteration   2: 4.199 ±(99.9%) 0.010 ms/op
Iteration   3: 4.055 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.134 ±(99.9%) 1.332 ms/op [Average]
  (min, avg, max) = (4.055, 4.134, 4.199), stdev = 0.073
  CI (99.9%): [2.802, 5.465] (assumes normal distribution)


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.945 ms/op
                 createUser·p0.9999: 13.304 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   2: 3.112 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.367 ms/op
                 createUser·p0.9999: 22.310 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 3.145 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  11.428 ms/op
                 createUser·p0.9999: 33.057 ms/op
                 createUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306856
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13664 
    [ 2.500,  5.000) = 291788 
    [ 5.000,  7.500) = 871 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     32.614 ms/op
     p(99.9990) =     33.290 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.146 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.005 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.980 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  8.339 ms/op
                 existUser·p0.9999: 21.366 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  5.932 ms/op
                 existUser·p0.9999: 27.298 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324098
  mean =      2.962 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22332 
    [ 2.500,  5.000) = 300886 
    [ 5.000,  7.500) = 650 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =      6.774 ms/op
     p(99.9900) =     24.548 ms/op
     p(99.9990) =     27.640 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.384 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  9.002 ms/op
                 getUser·p0.9999: 13.603 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.269 ms/op
                 getUser·p0.9999: 21.856 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.567 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  8.280 ms/op
                 getUser·p0.9999: 17.876 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313066
  mean =      3.065 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17823 
    [ 2.500,  5.000) = 293727 
    [ 5.000,  7.500) = 1218 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     21.224 ms/op
     p(99.9990) =     22.049 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 5.957 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.284 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.011 ms/op
Iteration   1: 4.003 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  14.207 ms/op
                 listUser·p0.9999: 15.647 ms/op
                 listUser·p1.00:   15.909 ms/op

Iteration   2: 3.969 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 22.081 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 3.973 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  15.737 ms/op
                 listUser·p0.9999: 18.611 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241163
  mean =      3.982 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2320 
    [ 2.500,  5.000) = 215690 
    [ 5.000,  7.500) = 21696 
    [ 7.500, 10.000) = 992 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     20.902 ms/op
     p(99.9990) =     22.471 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.978 ± 2.315  ops/ms
ClientGrpc.existUser                       thrpt       3  10.756 ± 1.700  ops/ms
ClientGrpc.getUser                         thrpt       3  10.130 ± 3.212  ops/ms
ClientGrpc.listUser                        thrpt       3   7.781 ± 3.940  ops/ms
ClientGrpc.createUser                       avgt       3   3.158 ± 1.046   ms/op
ClientGrpc.existUser                        avgt       3   3.015 ± 0.585   ms/op
ClientGrpc.getUser                          avgt       3   3.163 ± 0.625   ms/op
ClientGrpc.listUser                         avgt       3   4.134 ± 1.332   ms/op
ClientGrpc.createUser                     sample  306856   3.129 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.614           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.077           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.614           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.423           ms/op
ClientGrpc.existUser                      sample  324098   2.962 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.822           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.043           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.774           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.548           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.787           ms/op
ClientGrpc.getUser                        sample  313066   3.065 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.567           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.406           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.224           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.118           ms/op
ClientGrpc.listUser                       sample  241163   3.982 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.077           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.713           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.902           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.577           ms/op
