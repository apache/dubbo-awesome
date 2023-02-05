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
# Warmup Iteration   1: 2.035 ops/ms
# Warmup Iteration   2: 4.999 ops/ms
# Warmup Iteration   3: 6.427 ops/ms
Iteration   1: 6.618 ops/ms
Iteration   2: 6.534 ops/ms
Iteration   3: 6.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.622 ±(99.9%) 1.646 ops/ms [Average]
  (min, avg, max) = (6.534, 6.622, 6.714), stdev = 0.090
  CI (99.9%): [4.976, 8.268] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.553 ops/ms
# Warmup Iteration   2: 6.673 ops/ms
# Warmup Iteration   3: 7.056 ops/ms
Iteration   1: 7.143 ops/ms
Iteration   2: 7.483 ops/ms
Iteration   3: 7.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.353 ±(99.9%) 3.341 ops/ms [Average]
  (min, avg, max) = (7.143, 7.353, 7.483), stdev = 0.183
  CI (99.9%): [4.012, 10.694] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.222 ops/ms
# Warmup Iteration   2: 6.529 ops/ms
# Warmup Iteration   3: 6.357 ops/ms
Iteration   1: 6.825 ops/ms
Iteration   2: 7.025 ops/ms
Iteration   3: 6.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.853 ±(99.9%) 2.910 ops/ms [Average]
  (min, avg, max) = (6.710, 6.853, 7.025), stdev = 0.160
  CI (99.9%): [3.943, 9.763] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ops/ms
# Warmup Iteration   2: 5.190 ops/ms
# Warmup Iteration   3: 5.257 ops/ms
Iteration   1: 5.404 ops/ms
Iteration   2: 5.364 ops/ms
Iteration   3: 5.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.373 ±(99.9%) 0.504 ops/ms [Average]
  (min, avg, max) = (5.351, 5.373, 5.404), stdev = 0.028
  CI (99.9%): [4.869, 5.877] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.750 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.956 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.700 ±(99.9%) 0.006 ms/op
Iteration   1: 4.554 ±(99.9%) 0.004 ms/op
Iteration   2: 4.726 ±(99.9%) 0.004 ms/op
Iteration   3: 4.728 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.669 ±(99.9%) 1.821 ms/op [Average]
  (min, avg, max) = (4.554, 4.669, 4.728), stdev = 0.100
  CI (99.9%): [2.848, 6.491] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.528 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.691 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.481 ±(99.9%) 0.004 ms/op
Iteration   1: 4.424 ±(99.9%) 0.004 ms/op
Iteration   2: 4.542 ±(99.9%) 0.003 ms/op
Iteration   3: 4.539 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.502 ±(99.9%) 1.230 ms/op [Average]
  (min, avg, max) = (4.424, 4.502, 4.542), stdev = 0.067
  CI (99.9%): [3.271, 5.732] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.033 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.947 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.697 ±(99.9%) 0.004 ms/op
Iteration   1: 4.560 ±(99.9%) 0.004 ms/op
Iteration   2: 4.648 ±(99.9%) 0.003 ms/op
Iteration   3: 4.428 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.545 ±(99.9%) 2.015 ms/op [Average]
  (min, avg, max) = (4.428, 4.545, 4.648), stdev = 0.110
  CI (99.9%): [2.530, 6.561] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.606 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 6.980 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 6.359 ±(99.9%) 0.036 ms/op
Iteration   1: 6.089 ±(99.9%) 0.019 ms/op
Iteration   2: 6.016 ±(99.9%) 0.019 ms/op
Iteration   3: 6.177 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.094 ±(99.9%) 1.475 ms/op [Average]
  (min, avg, max) = (6.016, 6.094, 6.177), stdev = 0.081
  CI (99.9%): [4.619, 7.569] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.954 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.167 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.639 ±(99.9%) 0.015 ms/op
Iteration   1: 4.708 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   4.555 ms/op
                 createUser·p0.90:   6.054 ms/op
                 createUser·p0.95:   6.595 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  14.952 ms/op
                 createUser·p0.9999: 22.315 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   2: 4.626 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   4.489 ms/op
                 createUser·p0.90:   5.915 ms/op
                 createUser·p0.95:   6.537 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  15.344 ms/op
                 createUser·p0.9999: 29.991 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   3: 4.852 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   4.661 ms/op
                 createUser·p0.90:   6.193 ms/op
                 createUser·p0.95:   6.865 ms/op
                 createUser·p0.99:   9.650 ms/op
                 createUser·p0.999:  17.723 ms/op
                 createUser·p0.9999: 26.097 ms/op
                 createUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 202970
  mean =      4.727 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3700 
    [ 2.500,  5.000) = 131747 
    [ 5.000,  7.500) = 62376 
    [ 7.500, 10.000) = 3931 
    [10.000, 12.500) = 672 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.062 ms/op
     p(95.0000) =      6.660 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     29.200 ms/op
     p(99.9990) =     30.343 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.728 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.619 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.472 ±(99.9%) 0.015 ms/op
Iteration   1: 4.492 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   4.383 ms/op
                 existUser·p0.90:   5.620 ms/op
                 existUser·p0.95:   6.160 ms/op
                 existUser·p0.99:   8.407 ms/op
                 existUser·p0.999:  13.262 ms/op
                 existUser·p0.9999: 27.620 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   2: 4.721 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   4.555 ms/op
                 existUser·p0.90:   5.980 ms/op
                 existUser·p0.95:   6.840 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  15.508 ms/op
                 existUser·p0.9999: 37.487 ms/op
                 existUser·p1.00:   37.749 ms/op

Iteration   3: 4.435 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   4.325 ms/op
                 existUser·p0.90:   5.685 ms/op
                 existUser·p0.95:   6.250 ms/op
                 existUser·p0.99:   9.080 ms/op
                 existUser·p0.999:  13.858 ms/op
                 existUser·p0.9999: 31.490 ms/op
                 existUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 211089
  mean =      4.546 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6882 
    [ 2.500,  5.000) = 146882 
    [ 5.000,  7.500) = 52454 
    [ 7.500, 10.000) = 3489 
    [10.000, 12.500) = 909 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      6.390 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     14.564 ms/op
     p(99.9900) =     37.159 ms/op
     p(99.9990) =     37.618 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.571 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.267 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.880 ±(99.9%) 0.019 ms/op
Iteration   1: 4.824 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   4.653 ms/op
                 getUser·p0.90:   6.152 ms/op
                 getUser·p0.95:   6.939 ms/op
                 getUser·p0.99:   9.667 ms/op
                 getUser·p0.999:  15.625 ms/op
                 getUser·p0.9999: 18.100 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   2: 4.766 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   5.972 ms/op
                 getUser·p0.95:   6.619 ms/op
                 getUser·p0.99:   9.191 ms/op
                 getUser·p0.999:  13.435 ms/op
                 getUser·p0.9999: 18.117 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   3: 4.798 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   4.653 ms/op
                 getUser·p0.90:   6.054 ms/op
                 getUser·p0.95:   6.578 ms/op
                 getUser·p0.99:   9.028 ms/op
                 getUser·p0.999:  14.085 ms/op
                 getUser·p0.9999: 22.206 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 200071
  mean =      4.796 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2851 
    [ 2.500,  5.000) = 126114 
    [ 5.000,  7.500) = 65540 
    [ 7.500, 10.000) = 4270 
    [10.000, 12.500) = 928 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.062 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     14.548 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.162 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 6.520 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.806 ±(99.9%) 0.023 ms/op
Iteration   1: 5.988 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   8.028 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  18.771 ms/op
                 listUser·p0.9999: 22.784 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   2: 5.683 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   7.447 ms/op
                 listUser·p0.95:   8.372 ms/op
                 listUser·p0.99:   10.699 ms/op
                 listUser·p0.999:  20.742 ms/op
                 listUser·p0.9999: 30.597 ms/op
                 listUser·p1.00:   30.900 ms/op

Iteration   3: 5.783 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   10.945 ms/op
                 listUser·p0.999:  22.919 ms/op
                 listUser·p0.9999: 29.730 ms/op
                 listUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165049
  mean =      5.815 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 104 
    [ 2.500,  5.000) = 49861 
    [ 5.000,  7.500) = 96511 
    [ 7.500, 10.000) = 15001 
    [10.000, 12.500) = 2660 
    [12.500, 15.000) = 463 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      7.668 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     21.561 ms/op
     p(99.9900) =     30.113 ms/op
     p(99.9990) =     31.633 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.622 ± 1.646  ops/ms
ClientGrpc.existUser                       thrpt       3   7.353 ± 3.341  ops/ms
ClientGrpc.getUser                         thrpt       3   6.853 ± 2.910  ops/ms
ClientGrpc.listUser                        thrpt       3   5.373 ± 0.504  ops/ms
ClientGrpc.createUser                       avgt       3   4.669 ± 1.821   ms/op
ClientGrpc.existUser                        avgt       3   4.502 ± 1.230   ms/op
ClientGrpc.getUser                          avgt       3   4.545 ± 2.015   ms/op
ClientGrpc.listUser                         avgt       3   6.094 ± 1.475   ms/op
ClientGrpc.createUser                     sample  202970   4.727 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.836           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.062           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.660           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.946           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.007           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.200           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.376           ms/op
ClientGrpc.existUser                      sample  211089   4.546 ± 0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.811           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.767           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.390           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.159           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.564           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          37.159           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          37.749           ms/op
ClientGrpc.getUser                        sample  200071   4.796 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.237           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.062           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.693           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.290           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.548           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.611           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.643           ms/op
ClientGrpc.listUser                       sample  165049   5.815 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.969           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.668           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.667           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.289           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.561           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.113           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.654           ms/op
