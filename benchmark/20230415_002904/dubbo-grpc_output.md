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
# Warmup Iteration   1: 2.546 ops/ms
# Warmup Iteration   2: 6.113 ops/ms
# Warmup Iteration   3: 7.298 ops/ms
Iteration   1: 7.457 ops/ms
Iteration   2: 7.857 ops/ms
Iteration   3: 7.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.666 ±(99.9%) 3.656 ops/ms [Average]
  (min, avg, max) = (7.457, 7.666, 7.857), stdev = 0.200
  CI (99.9%): [4.010, 11.321] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.099 ops/ms
# Warmup Iteration   2: 7.870 ops/ms
# Warmup Iteration   3: 8.020 ops/ms
Iteration   1: 8.463 ops/ms
Iteration   2: 8.223 ops/ms
Iteration   3: 7.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.199 ±(99.9%) 5.046 ops/ms [Average]
  (min, avg, max) = (7.911, 8.199, 8.463), stdev = 0.277
  CI (99.9%): [3.153, 13.245] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.921 ops/ms
# Warmup Iteration   2: 7.250 ops/ms
# Warmup Iteration   3: 7.512 ops/ms
Iteration   1: 7.715 ops/ms
Iteration   2: 7.663 ops/ms
Iteration   3: 7.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.599 ±(99.9%) 2.890 ops/ms [Average]
  (min, avg, max) = (7.419, 7.599, 7.715), stdev = 0.158
  CI (99.9%): [4.709, 10.489] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.446 ops/ms
# Warmup Iteration   2: 5.120 ops/ms
# Warmup Iteration   3: 5.460 ops/ms
Iteration   1: 5.786 ops/ms
Iteration   2: 5.884 ops/ms
Iteration   3: 5.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.838 ±(99.9%) 0.905 ops/ms [Average]
  (min, avg, max) = (5.786, 5.838, 5.884), stdev = 0.050
  CI (99.9%): [4.934, 6.743] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.456 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.348 ±(99.9%) 0.008 ms/op
Iteration   1: 4.335 ±(99.9%) 0.003 ms/op
Iteration   2: 4.186 ±(99.9%) 0.002 ms/op
Iteration   3: 4.165 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.228 ±(99.9%) 1.689 ms/op [Average]
  (min, avg, max) = (4.165, 4.228, 4.335), stdev = 0.093
  CI (99.9%): [2.539, 5.918] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.034 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.003 ms/op
Iteration   1: 3.886 ±(99.9%) 0.005 ms/op
Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
Iteration   3: 3.876 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.843 ±(99.9%) 1.188 ms/op [Average]
  (min, avg, max) = (3.768, 3.843, 3.886), stdev = 0.065
  CI (99.9%): [2.655, 5.031] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.134 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.287 ±(99.9%) 0.011 ms/op
Iteration   1: 4.277 ±(99.9%) 0.002 ms/op
Iteration   2: 4.161 ±(99.9%) 0.004 ms/op
Iteration   3: 4.104 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.181 ±(99.9%) 1.607 ms/op [Average]
  (min, avg, max) = (4.104, 4.181, 4.277), stdev = 0.088
  CI (99.9%): [2.574, 5.787] (assumes normal distribution)


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
# Warmup Iteration   1: 7.367 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.926 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.506 ±(99.9%) 0.021 ms/op
Iteration   1: 5.484 ±(99.9%) 0.020 ms/op
Iteration   2: 5.352 ±(99.9%) 0.012 ms/op
Iteration   3: 5.536 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.458 ±(99.9%) 1.731 ms/op [Average]
  (min, avg, max) = (5.352, 5.458, 5.536), stdev = 0.095
  CI (99.9%): [3.726, 7.189] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.359 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.011 ms/op
Iteration   1: 4.112 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   4.039 ms/op
                 createUser·p0.90:   5.005 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 13.937 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 4.021 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  10.442 ms/op
                 createUser·p0.9999: 27.527 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   3: 4.171 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   7.268 ms/op
                 createUser·p0.999:  11.086 ms/op
                 createUser·p0.9999: 23.713 ms/op
                 createUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 234068
  mean =      4.100 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6948 
    [ 2.500,  5.000) = 202420 
    [ 5.000,  7.500) = 23128 
    [ 7.500, 10.000) = 1131 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     26.450 ms/op
     p(99.9990) =     28.027 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 5.617 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.011 ms/op
Iteration   1: 4.123 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  9.847 ms/op
                 existUser·p0.9999: 16.241 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 3.734 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  13.029 ms/op
                 existUser·p0.9999: 17.217 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   3: 3.806 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  11.010 ms/op
                 existUser·p0.9999: 33.580 ms/op
                 existUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 247337
  mean =      3.881 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7346 
    [ 2.500,  5.000) = 223285 
    [ 5.000,  7.500) = 15466 
    [ 7.500, 10.000) = 873 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     11.545 ms/op
     p(99.9900) =     32.654 ms/op
     p(99.9990) =     34.048 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 6.599 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.012 ms/op
Iteration   1: 4.163 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   4.084 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   6.613 ms/op
                 getUser·p0.999:  10.652 ms/op
                 getUser·p0.9999: 25.111 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   2: 4.252 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   4.166 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  14.283 ms/op
                 getUser·p0.9999: 19.773 ms/op
                 getUser·p1.00:   20.316 ms/op

Iteration   3: 4.088 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  9.900 ms/op
                 getUser·p0.9999: 19.005 ms/op
                 getUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 230369
  mean =      4.166 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2314 
    [ 2.500,  5.000) = 201699 
    [ 5.000,  7.500) = 25125 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     10.703 ms/op
     p(99.9900) =     24.213 ms/op
     p(99.9990) =     25.801 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 8.094 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 5.729 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.550 ±(99.9%) 0.017 ms/op
Iteration   1: 5.322 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   6.729 ms/op
                 listUser·p0.95:   7.700 ms/op
                 listUser·p0.99:   9.602 ms/op
                 listUser·p0.999:  15.662 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   2: 5.405 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   5.153 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   7.733 ms/op
                 listUser·p0.99:   10.109 ms/op
                 listUser·p0.999:  16.735 ms/op
                 listUser·p0.9999: 23.251 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   3: 5.354 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   6.799 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  18.195 ms/op
                 listUser·p0.9999: 33.264 ms/op
                 listUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179006
  mean =      5.360 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 144 
    [ 2.500,  5.000) = 77087 
    [ 5.000,  7.500) = 91250 
    [ 7.500, 10.000) = 8946 
    [10.000, 12.500) = 1033 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.709 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     32.673 ms/op
     p(99.9990) =     33.699 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.666 ± 3.656  ops/ms
ClientGrpc.existUser                       thrpt       3   8.199 ± 5.046  ops/ms
ClientGrpc.getUser                         thrpt       3   7.599 ± 2.890  ops/ms
ClientGrpc.listUser                        thrpt       3   5.838 ± 0.905  ops/ms
ClientGrpc.createUser                       avgt       3   4.228 ± 1.689   ms/op
ClientGrpc.existUser                        avgt       3   3.843 ± 1.188   ms/op
ClientGrpc.getUser                          avgt       3   4.181 ± 1.607   ms/op
ClientGrpc.listUser                         avgt       3   5.458 ± 1.731   ms/op
ClientGrpc.createUser                     sample  234068   4.100 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.916           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.022           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.030           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.423           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.922           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.190           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.450           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.180           ms/op
ClientGrpc.existUser                      sample  247337   3.881 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.821           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.760           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.186           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.513           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.545           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.654           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.210           ms/op
ClientGrpc.getUser                        sample  230369   4.166 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.096           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.079           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.448           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.619           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.703           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.213           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.919           ms/op
ClientGrpc.listUser                       sample  179006   5.360 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.460           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.709           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.798           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.564           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.673           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.751           ms/op
