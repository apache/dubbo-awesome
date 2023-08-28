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
# Warmup Iteration   1: 3.162 ops/ms
# Warmup Iteration   2: 7.250 ops/ms
# Warmup Iteration   3: 8.652 ops/ms
Iteration   1: 9.200 ops/ms
Iteration   2: 9.463 ops/ms
Iteration   3: 9.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.310 ±(99.9%) 2.499 ops/ms [Average]
  (min, avg, max) = (9.200, 9.310, 9.463), stdev = 0.137
  CI (99.9%): [6.811, 11.809] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.245 ops/ms
# Warmup Iteration   2: 8.932 ops/ms
# Warmup Iteration   3: 9.737 ops/ms
Iteration   1: 9.579 ops/ms
Iteration   2: 10.128 ops/ms
Iteration   3: 9.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.825 ±(99.9%) 5.090 ops/ms [Average]
  (min, avg, max) = (9.579, 9.825, 10.128), stdev = 0.279
  CI (99.9%): [4.735, 14.916] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.840 ops/ms
# Warmup Iteration   2: 8.783 ops/ms
# Warmup Iteration   3: 9.122 ops/ms
Iteration   1: 9.230 ops/ms
Iteration   2: 9.367 ops/ms
Iteration   3: 9.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.281 ±(99.9%) 1.362 ops/ms [Average]
  (min, avg, max) = (9.230, 9.281, 9.367), stdev = 0.075
  CI (99.9%): [7.920, 10.643] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.849 ops/ms
# Warmup Iteration   2: 6.960 ops/ms
# Warmup Iteration   3: 7.016 ops/ms
Iteration   1: 7.064 ops/ms
Iteration   2: 6.850 ops/ms
Iteration   3: 6.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.917 ±(99.9%) 2.337 ops/ms [Average]
  (min, avg, max) = (6.835, 6.917, 7.064), stdev = 0.128
  CI (99.9%): [4.580, 9.253] (assumes normal distribution)


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
# Warmup Iteration   1: 5.095 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.003 ms/op
Iteration   1: 3.606 ±(99.9%) 0.005 ms/op
Iteration   2: 3.552 ±(99.9%) 0.003 ms/op
Iteration   3: 3.543 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.567 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.543, 3.567, 3.606), stdev = 0.034
  CI (99.9%): [2.946, 4.187] (assumes normal distribution)


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
# Warmup Iteration   1: 4.979 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.003 ms/op
Iteration   1: 3.300 ±(99.9%) 0.003 ms/op
Iteration   2: 3.360 ±(99.9%) 0.002 ms/op
Iteration   3: 3.281 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.314 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (3.281, 3.314, 3.360), stdev = 0.041
  CI (99.9%): [2.558, 4.069] (assumes normal distribution)


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
# Warmup Iteration   1: 4.752 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.004 ms/op
Iteration   1: 3.445 ±(99.9%) 0.004 ms/op
Iteration   2: 3.482 ±(99.9%) 0.005 ms/op
Iteration   3: 3.481 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.470 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (3.445, 3.470, 3.482), stdev = 0.021
  CI (99.9%): [3.081, 3.858] (assumes normal distribution)


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
# Warmup Iteration   1: 6.325 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.668 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.521 ±(99.9%) 0.014 ms/op
Iteration   1: 4.554 ±(99.9%) 0.031 ms/op
Iteration   2: 4.467 ±(99.9%) 0.016 ms/op
Iteration   3: 4.528 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.516 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (4.467, 4.516, 4.554), stdev = 0.044
  CI (99.9%): [3.705, 5.328] (assumes normal distribution)


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
# Warmup Iteration   1: 5.040 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.009 ms/op
Iteration   1: 3.455 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.590 ms/op
                 createUser·p0.999:  14.505 ms/op
                 createUser·p0.9999: 23.814 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 3.453 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  8.081 ms/op
                 createUser·p0.9999: 36.404 ms/op
                 createUser·p1.00:   37.814 ms/op

Iteration   3: 3.448 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  17.829 ms/op
                 createUser·p0.9999: 27.329 ms/op
                 createUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 278030
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12404 
    [ 2.500,  5.000) = 261205 
    [ 5.000,  7.500) = 3697 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     11.485 ms/op
     p(99.9900) =     34.800 ms/op
     p(99.9990) =     37.581 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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
# Warmup Iteration   1: 4.625 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.007 ms/op
Iteration   1: 3.355 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.318 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   4.989 ms/op
                 existUser·p0.999:  7.349 ms/op
                 existUser·p0.9999: 12.458 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   2: 3.350 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.008 ms/op
                 existUser·p0.999:  7.738 ms/op
                 existUser·p0.9999: 19.545 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   3: 3.355 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 20.658 ms/op
                 existUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 286487
  mean =      3.353 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12837 
    [ 2.500,  5.000) = 270216 
    [ 5.000,  7.500) = 2871 
    [ 7.500, 10.000) = 269 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.318 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     10.125 ms/op
     p(99.9900) =     19.979 ms/op
     p(99.9990) =     20.747 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 5.320 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.009 ms/op
Iteration   1: 3.571 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  11.436 ms/op
                 getUser·p0.9999: 14.353 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 3.609 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  9.503 ms/op
                 getUser·p0.9999: 15.911 ms/op
                 getUser·p1.00:   16.335 ms/op

Iteration   3: 3.505 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  8.708 ms/op
                 getUser·p0.9999: 19.358 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 269693
  mean =      3.561 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 5615 
    [ 2.500,  3.750) = 181337 
    [ 3.750,  5.000) = 78377 
    [ 5.000,  6.250) = 2893 
    [ 6.250,  7.500) = 609 
    [ 7.500,  8.750) = 372 
    [ 8.750, 10.000) = 160 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     16.614 ms/op
     p(99.9990) =     19.746 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 6.069 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.755 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.621 ±(99.9%) 0.014 ms/op
Iteration   1: 4.654 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.898 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 22.946 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   2: 4.478 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  15.753 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   3: 4.548 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.424 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  19.027 ms/op
                 listUser·p0.9999: 34.077 ms/op
                 listUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 210456
  mean =      4.559 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 590 
    [ 2.500,  5.000) = 176247 
    [ 5.000,  7.500) = 29525 
    [ 7.500, 10.000) = 3308 
    [10.000, 12.500) = 425 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.578 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     33.222 ms/op
     p(99.9990) =     34.465 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.310 ± 2.499  ops/ms
ClientGrpc.existUser                       thrpt       3   9.825 ± 5.090  ops/ms
ClientGrpc.getUser                         thrpt       3   9.281 ± 1.362  ops/ms
ClientGrpc.listUser                        thrpt       3   6.917 ± 2.337  ops/ms
ClientGrpc.createUser                       avgt       3   3.567 ± 0.620   ms/op
ClientGrpc.existUser                        avgt       3   3.314 ± 0.756   ms/op
ClientGrpc.getUser                          avgt       3   3.470 ± 0.389   ms/op
ClientGrpc.listUser                         avgt       3   4.516 ± 0.811   ms/op
ClientGrpc.createUser                     sample  278030   3.452 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.792           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.424           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.485           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.800           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          37.814           ms/op
ClientGrpc.existUser                      sample  286487   3.353 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.318           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.928           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.125           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.979           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.906           ms/op
ClientGrpc.getUser                        sample  269693   3.561 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.767           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.585           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.614           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.857           ms/op
ClientGrpc.listUser                       sample  210456   4.559 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.130           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.383           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.192           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.629           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.222           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.603           ms/op
