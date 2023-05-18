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
# Warmup Iteration   1: 2.580 ops/ms
# Warmup Iteration   2: 5.864 ops/ms
# Warmup Iteration   3: 7.091 ops/ms
Iteration   1: 7.418 ops/ms
Iteration   2: 7.619 ops/ms
Iteration   3: 7.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.644 ±(99.9%) 4.364 ops/ms [Average]
  (min, avg, max) = (7.418, 7.644, 7.894), stdev = 0.239
  CI (99.9%): [3.280, 12.007] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.339 ops/ms
# Warmup Iteration   2: 7.895 ops/ms
# Warmup Iteration   3: 8.486 ops/ms
Iteration   1: 8.159 ops/ms
Iteration   2: 8.550 ops/ms
Iteration   3: 8.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.356 ±(99.9%) 3.571 ops/ms [Average]
  (min, avg, max) = (8.159, 8.356, 8.550), stdev = 0.196
  CI (99.9%): [4.785, 11.927] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.125 ops/ms
# Warmup Iteration   2: 7.538 ops/ms
# Warmup Iteration   3: 7.484 ops/ms
Iteration   1: 7.787 ops/ms
Iteration   2: 7.628 ops/ms
Iteration   3: 7.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.778 ±(99.9%) 2.659 ops/ms [Average]
  (min, avg, max) = (7.628, 7.778, 7.919), stdev = 0.146
  CI (99.9%): [5.119, 10.437] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.103 ops/ms
# Warmup Iteration   2: 5.691 ops/ms
# Warmup Iteration   3: 6.170 ops/ms
Iteration   1: 6.138 ops/ms
Iteration   2: 6.139 ops/ms
Iteration   3: 5.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.087 ±(99.9%) 1.624 ops/ms [Average]
  (min, avg, max) = (5.984, 6.087, 6.139), stdev = 0.089
  CI (99.9%): [4.463, 7.711] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.678 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.003 ms/op
Iteration   1: 3.921 ±(99.9%) 0.003 ms/op
Iteration   2: 4.631 ±(99.9%) 0.005 ms/op
Iteration   3: 4.048 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.200 ±(99.9%) 6.901 ms/op [Average]
  (min, avg, max) = (3.921, 4.200, 4.631), stdev = 0.378
  CI (99.9%): [≈ 0, 11.101] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.227 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.005 ms/op
Iteration   1: 3.999 ±(99.9%) 0.004 ms/op
Iteration   2: 4.367 ±(99.9%) 0.004 ms/op
Iteration   3: 4.077 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.148 ±(99.9%) 3.541 ms/op [Average]
  (min, avg, max) = (3.999, 4.148, 4.367), stdev = 0.194
  CI (99.9%): [0.606, 7.689] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.200 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.465 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.002 ms/op
Iteration   1: 4.534 ±(99.9%) 0.004 ms/op
Iteration   2: 4.453 ±(99.9%) 0.005 ms/op
Iteration   3: 4.342 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.443 ±(99.9%) 1.751 ms/op [Average]
  (min, avg, max) = (4.342, 4.443, 4.534), stdev = 0.096
  CI (99.9%): [2.692, 6.194] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 6.584 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.895 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.503 ±(99.9%) 0.017 ms/op
Iteration   1: 5.749 ±(99.9%) 0.027 ms/op
Iteration   2: 5.299 ±(99.9%) 0.015 ms/op
Iteration   3: 5.290 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.446 ±(99.9%) 4.791 ms/op [Average]
  (min, avg, max) = (5.290, 5.446, 5.749), stdev = 0.263
  CI (99.9%): [0.655, 10.236] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.026 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.567 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.803 ±(99.9%) 0.020 ms/op
Iteration   1: 4.705 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   7.512 ms/op
                 createUser·p0.99:   9.978 ms/op
                 createUser·p0.999:  16.846 ms/op
                 createUser·p0.9999: 22.748 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   2: 4.282 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   5.702 ms/op
                 createUser·p0.95:   6.488 ms/op
                 createUser·p0.99:   9.334 ms/op
                 createUser·p0.999:  13.734 ms/op
                 createUser·p0.9999: 26.821 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 4.226 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   5.521 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   8.864 ms/op
                 createUser·p0.999:  15.352 ms/op
                 createUser·p0.9999: 29.249 ms/op
                 createUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 218386
  mean =      4.394 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7866 
    [ 2.500,  5.000) = 162104 
    [ 5.000,  7.500) = 41223 
    [ 7.500, 10.000) = 5689 
    [10.000, 12.500) = 1088 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.832 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     28.087 ms/op
     p(99.9990) =     30.069 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.590 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.014 ms/op
Iteration   1: 4.265 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   3.953 ms/op
                 existUser·p0.90:   5.677 ms/op
                 existUser·p0.95:   6.676 ms/op
                 existUser·p0.99:   9.044 ms/op
                 existUser·p0.999:  12.731 ms/op
                 existUser·p0.9999: 26.165 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   2: 4.126 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   5.513 ms/op
                 existUser·p0.95:   6.365 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  15.024 ms/op
                 existUser·p0.9999: 21.509 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 3.951 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   5.104 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   7.799 ms/op
                 existUser·p0.999:  9.931 ms/op
                 existUser·p0.9999: 24.406 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 233503
  mean =      4.110 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9212 
    [ 2.500,  5.000) = 189166 
    [ 5.000,  7.500) = 29919 
    [ 7.500, 10.000) = 4358 
    [10.000, 12.500) = 599 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      6.283 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     12.738 ms/op
     p(99.9900) =     24.520 ms/op
     p(99.9990) =     26.466 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 6.023 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.537 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.016 ms/op
Iteration   1: 4.371 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   4.080 ms/op
                 getUser·p0.90:   5.743 ms/op
                 getUser·p0.95:   6.693 ms/op
                 getUser·p0.99:   9.568 ms/op
                 getUser·p0.999:  15.949 ms/op
                 getUser·p0.9999: 40.436 ms/op
                 getUser·p1.00:   42.140 ms/op

Iteration   2: 4.309 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   5.595 ms/op
                 getUser·p0.95:   6.463 ms/op
                 getUser·p0.99:   9.077 ms/op
                 getUser·p0.999:  12.563 ms/op
                 getUser·p0.9999: 35.427 ms/op
                 getUser·p1.00:   35.783 ms/op

Iteration   3: 4.546 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   6.088 ms/op
                 getUser·p0.95:   7.127 ms/op
                 getUser·p0.99:   9.519 ms/op
                 getUser·p0.999:  12.878 ms/op
                 getUser·p0.9999: 25.894 ms/op
                 getUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217744
  mean =      4.407 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 172469 
    [ 5.000, 10.000) = 43918 
    [10.000, 15.000) = 1195 
    [15.000, 20.000) = 30 
    [20.000, 25.000) = 57 
    [25.000, 30.000) = 19 
    [30.000, 35.000) = 26 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     14.389 ms/op
     p(99.9900) =     35.732 ms/op
     p(99.9990) =     40.867 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.476 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.789 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.510 ±(99.9%) 0.025 ms/op
Iteration   1: 5.519 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   7.545 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  16.435 ms/op
                 listUser·p0.9999: 18.291 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   2: 5.344 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.372 ms/op
                 listUser·p0.99:   11.289 ms/op
                 listUser·p0.999:  24.024 ms/op
                 listUser·p0.9999: 30.050 ms/op
                 listUser·p1.00:   30.441 ms/op

Iteration   3: 5.305 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   7.397 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  21.158 ms/op
                 listUser·p0.9999: 28.474 ms/op
                 listUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178070
  mean =      5.388 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 310 
    [ 2.500,  5.000) = 92959 
    [ 5.000,  7.500) = 67940 
    [ 7.500, 10.000) = 13286 
    [10.000, 12.500) = 2688 
    [12.500, 15.000) = 495 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      7.422 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.125 ms/op
     p(99.9000) =     19.888 ms/op
     p(99.9900) =     28.724 ms/op
     p(99.9990) =     30.365 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.644 ± 4.364  ops/ms
ClientGrpc.existUser                       thrpt       3   8.356 ± 3.571  ops/ms
ClientGrpc.getUser                         thrpt       3   7.778 ± 2.659  ops/ms
ClientGrpc.listUser                        thrpt       3   6.087 ± 1.624  ops/ms
ClientGrpc.createUser                       avgt       3   4.200 ± 6.901   ms/op
ClientGrpc.existUser                        avgt       3   4.148 ± 3.541   ms/op
ClientGrpc.getUser                          avgt       3   4.443 ± 1.751   ms/op
ClientGrpc.listUser                         avgt       3   5.446 ± 4.791   ms/op
ClientGrpc.createUser                     sample  218386   4.394 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.032           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.116           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.832           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.437           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.155           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.087           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.081           ms/op
ClientGrpc.existUser                      sample  233503   4.110 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.699           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.439           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.283           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.585           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.738           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.520           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.542           ms/op
ClientGrpc.getUser                        sample  217744   4.407 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.689           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.808           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.783           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.421           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.389           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.732           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          42.140           ms/op
ClientGrpc.listUser                       sample  178070   5.388 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.280           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.422           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.471           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.125           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.888           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.724           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.441           ms/op
