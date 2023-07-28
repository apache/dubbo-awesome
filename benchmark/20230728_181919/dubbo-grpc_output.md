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
# Warmup Iteration   1: 2.195 ops/ms
# Warmup Iteration   2: 5.541 ops/ms
# Warmup Iteration   3: 7.049 ops/ms
Iteration   1: 7.430 ops/ms
Iteration   2: 7.310 ops/ms
Iteration   3: 7.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.348 ±(99.9%) 1.298 ops/ms [Average]
  (min, avg, max) = (7.304, 7.348, 7.430), stdev = 0.071
  CI (99.9%): [6.051, 8.646] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.818 ops/ms
# Warmup Iteration   2: 7.241 ops/ms
# Warmup Iteration   3: 7.862 ops/ms
Iteration   1: 7.983 ops/ms
Iteration   2: 7.914 ops/ms
Iteration   3: 7.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.959 ±(99.9%) 0.711 ops/ms [Average]
  (min, avg, max) = (7.914, 7.959, 7.983), stdev = 0.039
  CI (99.9%): [7.248, 8.670] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.661 ops/ms
# Warmup Iteration   2: 6.822 ops/ms
# Warmup Iteration   3: 7.348 ops/ms
Iteration   1: 7.638 ops/ms
Iteration   2: 7.404 ops/ms
Iteration   3: 7.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.546 ±(99.9%) 2.282 ops/ms [Average]
  (min, avg, max) = (7.404, 7.546, 7.638), stdev = 0.125
  CI (99.9%): [5.264, 9.828] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ops/ms
# Warmup Iteration   2: 5.114 ops/ms
# Warmup Iteration   3: 5.634 ops/ms
Iteration   1: 5.600 ops/ms
Iteration   2: 5.839 ops/ms
Iteration   3: 5.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.739 ±(99.9%) 2.260 ops/ms [Average]
  (min, avg, max) = (5.600, 5.739, 5.839), stdev = 0.124
  CI (99.9%): [3.478, 7.999] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.752 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.622 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.402 ±(99.9%) 0.006 ms/op
Iteration   1: 4.351 ±(99.9%) 0.002 ms/op
Iteration   2: 4.352 ±(99.9%) 0.003 ms/op
Iteration   3: 4.270 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.325 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (4.270, 4.325, 4.352), stdev = 0.047
  CI (99.9%): [3.467, 5.182] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.367 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.012 ms/op
Iteration   1: 4.018 ±(99.9%) 0.003 ms/op
Iteration   2: 3.993 ±(99.9%) 0.003 ms/op
Iteration   3: 4.162 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.058 ±(99.9%) 1.664 ms/op [Average]
  (min, avg, max) = (3.993, 4.058, 4.162), stdev = 0.091
  CI (99.9%): [2.394, 5.721] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.317 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.701 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.411 ±(99.9%) 0.005 ms/op
Iteration   1: 4.388 ±(99.9%) 0.005 ms/op
Iteration   2: 4.250 ±(99.9%) 0.004 ms/op
Iteration   3: 4.225 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.287 ±(99.9%) 1.599 ms/op [Average]
  (min, avg, max) = (4.225, 4.287, 4.388), stdev = 0.088
  CI (99.9%): [2.688, 5.887] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.905 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 6.210 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.682 ±(99.9%) 0.021 ms/op
Iteration   1: 5.557 ±(99.9%) 0.017 ms/op
Iteration   2: 5.627 ±(99.9%) 0.016 ms/op
Iteration   3: 5.508 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.564 ±(99.9%) 1.097 ms/op [Average]
  (min, avg, max) = (5.508, 5.564, 5.627), stdev = 0.060
  CI (99.9%): [4.467, 6.661] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.749 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.750 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.013 ms/op
Iteration   1: 4.127 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   4.076 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.513 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  11.100 ms/op
                 createUser·p0.9999: 17.023 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 4.232 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   4.125 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  10.306 ms/op
                 createUser·p0.9999: 22.573 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   3: 4.323 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  15.352 ms/op
                 createUser·p0.9999: 24.052 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227158
  mean =      4.226 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4758 
    [ 2.500,  5.000) = 193362 
    [ 5.000,  7.500) = 26939 
    [ 7.500, 10.000) = 1613 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     13.247 ms/op
     p(99.9900) =     23.588 ms/op
     p(99.9990) =     24.245 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.733 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.011 ms/op
Iteration   1: 3.956 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  10.933 ms/op
                 existUser·p0.9999: 16.251 ms/op
                 existUser·p1.00:   16.695 ms/op

Iteration   2: 4.136 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   5.112 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   7.717 ms/op
                 existUser·p0.999:  14.025 ms/op
                 existUser·p0.9999: 18.719 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   3: 4.009 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   7.283 ms/op
                 existUser·p0.999:  12.423 ms/op
                 existUser·p0.9999: 21.103 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 237979
  mean =      4.032 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7190 
    [ 2.500,  5.000) = 209200 
    [ 5.000,  7.500) = 19535 
    [ 7.500, 10.000) = 1473 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     20.369 ms/op
     p(99.9990) =     21.909 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.598 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.305 ±(99.9%) 0.013 ms/op
Iteration   1: 4.207 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   4.121 ms/op
                 getUser·p0.90:   5.112 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  9.781 ms/op
                 getUser·p0.9999: 15.437 ms/op
                 getUser·p1.00:   15.942 ms/op

Iteration   2: 4.391 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   5.767 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  11.634 ms/op
                 getUser·p0.9999: 20.480 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   3: 4.320 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  9.713 ms/op
                 getUser·p0.9999: 19.615 ms/op
                 getUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 223037
  mean =      4.305 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2805 
    [ 2.500,  5.000) = 184954 
    [ 5.000,  7.500) = 33674 
    [ 7.500, 10.000) = 1329 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.643 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.411 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.831 ±(99.9%) 0.020 ms/op
Iteration   1: 5.861 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.786 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   7.676 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   11.600 ms/op
                 listUser·p0.999:  17.511 ms/op
                 listUser·p0.9999: 20.405 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 5.868 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   5.628 ms/op
                 listUser·p0.90:   7.374 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.637 ms/op
                 listUser·p0.999:  15.175 ms/op
                 listUser·p0.9999: 25.340 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   3: 5.629 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   5.390 ms/op
                 listUser·p0.90:   7.152 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   11.125 ms/op
                 listUser·p0.999:  21.830 ms/op
                 listUser·p0.9999: 25.428 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165866
  mean =      5.784 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 44660 
    [ 5.000,  7.500) = 105357 
    [ 7.500, 10.000) = 12682 
    [10.000, 12.500) = 2154 
    [12.500, 15.000) = 464 
    [15.000, 17.500) = 223 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      7.414 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     18.883 ms/op
     p(99.9900) =     25.258 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.348 ± 1.298  ops/ms
ClientGrpc.existUser                       thrpt       3   7.959 ± 0.711  ops/ms
ClientGrpc.getUser                         thrpt       3   7.546 ± 2.282  ops/ms
ClientGrpc.listUser                        thrpt       3   5.739 ± 2.260  ops/ms
ClientGrpc.createUser                       avgt       3   4.325 ± 0.858   ms/op
ClientGrpc.existUser                        avgt       3   4.058 ± 1.664   ms/op
ClientGrpc.getUser                          avgt       3   4.287 ± 1.599   ms/op
ClientGrpc.listUser                         avgt       3   5.564 ± 1.097   ms/op
ClientGrpc.createUser                     sample  227158   4.226 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.812           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.153           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.587           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.356           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.247           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.588           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.330           ms/op
ClientGrpc.existUser                      sample  237979   4.032 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.752           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.928           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.242           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.337           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.369           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.955           ms/op
ClientGrpc.getUser                        sample  223037   4.305 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.007           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.004           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.551           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.218           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  165866   5.784 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.565           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.471           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.141           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.883           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.258           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
