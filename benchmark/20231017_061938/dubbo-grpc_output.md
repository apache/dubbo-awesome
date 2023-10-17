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
# Warmup Iteration   1: 3.079 ops/ms
# Warmup Iteration   2: 6.934 ops/ms
# Warmup Iteration   3: 7.826 ops/ms
Iteration   1: 8.086 ops/ms
Iteration   2: 8.338 ops/ms
Iteration   3: 8.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.299 ±(99.9%) 3.584 ops/ms [Average]
  (min, avg, max) = (8.086, 8.299, 8.473), stdev = 0.196
  CI (99.9%): [4.715, 11.883] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.789 ops/ms
# Warmup Iteration   2: 8.335 ops/ms
# Warmup Iteration   3: 8.925 ops/ms
Iteration   1: 8.946 ops/ms
Iteration   2: 8.972 ops/ms
Iteration   3: 9.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.995 ±(99.9%) 1.160 ops/ms [Average]
  (min, avg, max) = (8.946, 8.995, 9.067), stdev = 0.064
  CI (99.9%): [7.835, 10.155] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.240 ops/ms
# Warmup Iteration   2: 8.167 ops/ms
# Warmup Iteration   3: 8.177 ops/ms
Iteration   1: 8.472 ops/ms
Iteration   2: 8.698 ops/ms
Iteration   3: 8.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.549 ±(99.9%) 2.359 ops/ms [Average]
  (min, avg, max) = (8.472, 8.549, 8.698), stdev = 0.129
  CI (99.9%): [6.189, 10.908] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.103 ops/ms
# Warmup Iteration   2: 6.276 ops/ms
# Warmup Iteration   3: 6.685 ops/ms
Iteration   1: 6.639 ops/ms
Iteration   2: 6.655 ops/ms
Iteration   3: 6.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.685 ±(99.9%) 1.215 ops/ms [Average]
  (min, avg, max) = (6.639, 6.685, 6.761), stdev = 0.067
  CI (99.9%): [5.470, 7.900] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.547 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.010 ms/op
Iteration   1: 3.808 ±(99.9%) 0.003 ms/op
Iteration   2: 3.789 ±(99.9%) 0.003 ms/op
Iteration   3: 3.629 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.742 ±(99.9%) 1.797 ms/op [Average]
  (min, avg, max) = (3.629, 3.742, 3.808), stdev = 0.098
  CI (99.9%): [1.945, 5.539] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.132 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.005 ms/op
Iteration   1: 3.579 ±(99.9%) 0.004 ms/op
Iteration   2: 3.570 ±(99.9%) 0.002 ms/op
Iteration   3: 3.514 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.554 ±(99.9%) 0.645 ms/op [Average]
  (min, avg, max) = (3.514, 3.554, 3.579), stdev = 0.035
  CI (99.9%): [2.909, 4.199] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.460 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.003 ms/op
Iteration   1: 3.813 ±(99.9%) 0.003 ms/op
Iteration   2: 3.677 ±(99.9%) 0.007 ms/op
Iteration   3: 3.775 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.755 ±(99.9%) 1.280 ms/op [Average]
  (min, avg, max) = (3.677, 3.755, 3.813), stdev = 0.070
  CI (99.9%): [2.475, 5.035] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.352 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.951 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.964 ±(99.9%) 0.019 ms/op
Iteration   1: 4.830 ±(99.9%) 0.023 ms/op
Iteration   2: 4.833 ±(99.9%) 0.015 ms/op
Iteration   3: 4.749 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.804 ±(99.9%) 0.867 ms/op [Average]
  (min, avg, max) = (4.749, 4.804, 4.833), stdev = 0.048
  CI (99.9%): [3.937, 5.672] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.380 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.011 ms/op
Iteration   1: 3.820 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  11.859 ms/op
                 createUser·p0.9999: 54.698 ms/op
                 createUser·p1.00:   55.116 ms/op

Iteration   2: 3.765 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.971 ms/op
                 createUser·p0.999:  12.192 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   3: 3.841 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   8.094 ms/op
                 createUser·p0.999:  14.282 ms/op
                 createUser·p0.9999: 21.944 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251972
  mean =      3.808 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 240037 
    [ 5.000, 10.000) = 11295 
    [10.000, 15.000) = 454 
    [15.000, 20.000) = 116 
    [20.000, 25.000) = 38 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.383 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     52.101 ms/op
     p(99.9990) =     55.016 ms/op
     p(99.9999) =     55.116 ms/op
    p(100.0000) =     55.116 ms/op


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
# Warmup Iteration   1: 5.152 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.891 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.008 ms/op
Iteration   1: 3.613 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  10.390 ms/op
                 existUser·p0.9999: 22.619 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 3.571 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  9.100 ms/op
                 existUser·p0.9999: 17.433 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   3: 3.545 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 18.972 ms/op
                 existUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268422
  mean =      3.576 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9923 
    [ 2.500,  5.000) = 250736 
    [ 5.000,  7.500) = 6702 
    [ 7.500, 10.000) = 863 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =      9.397 ms/op
     p(99.9900) =     21.273 ms/op
     p(99.9990) =     22.882 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 5.564 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.010 ms/op
Iteration   1: 3.817 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   7.184 ms/op
                 getUser·p0.999:  11.129 ms/op
                 getUser·p0.9999: 14.789 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   2: 3.788 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   7.469 ms/op
                 getUser·p0.999:  11.366 ms/op
                 getUser·p0.9999: 16.755 ms/op
                 getUser·p1.00:   17.400 ms/op

Iteration   3: 3.691 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  10.229 ms/op
                 getUser·p0.9999: 23.691 ms/op
                 getUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254836
  mean =      3.765 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9570 
    [ 2.500,  5.000) = 233750 
    [ 5.000,  7.500) = 9511 
    [ 7.500, 10.000) = 1563 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     10.928 ms/op
     p(99.9900) =     21.414 ms/op
     p(99.9990) =     23.870 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 6.641 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.999 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.782 ±(99.9%) 0.015 ms/op
Iteration   1: 4.739 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  14.326 ms/op
                 listUser·p0.9999: 15.946 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 4.792 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.242 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  15.686 ms/op
                 listUser·p0.9999: 21.321 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 4.857 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.259 ms/op
                 listUser·p0.95:   7.176 ms/op
                 listUser·p0.99:   9.197 ms/op
                 listUser·p0.999:  22.184 ms/op
                 listUser·p0.9999: 31.831 ms/op
                 listUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200168
  mean =      4.796 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 255 
    [ 2.500,  5.000) = 148050 
    [ 5.000,  7.500) = 44932 
    [ 7.500, 10.000) = 5703 
    [10.000, 12.500) = 826 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      7.062 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     15.393 ms/op
     p(99.9900) =     31.187 ms/op
     p(99.9990) =     32.145 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.299 ± 3.584  ops/ms
ClientGrpc.existUser                       thrpt       3   8.995 ± 1.160  ops/ms
ClientGrpc.getUser                         thrpt       3   8.549 ± 2.359  ops/ms
ClientGrpc.listUser                        thrpt       3   6.685 ± 1.215  ops/ms
ClientGrpc.createUser                       avgt       3   3.742 ± 1.797   ms/op
ClientGrpc.existUser                        avgt       3   3.554 ± 0.645   ms/op
ClientGrpc.getUser                          avgt       3   3.755 ± 1.280   ms/op
ClientGrpc.listUser                         avgt       3   4.804 ± 0.867   ms/op
ClientGrpc.createUser                     sample  251972   3.808 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.860           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.964           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.566           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          52.101           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          55.116           ms/op
ClientGrpc.existUser                      sample  268422   3.576 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.776           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.169           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.397           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.273           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.970           ms/op
ClientGrpc.getUser                        sample  254836   3.765 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.591           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.923           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.070           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.928           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.414           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.888           ms/op
ClientGrpc.listUser                       sample  200168   4.796 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.024           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.103           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.110           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.393           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.187           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.244           ms/op
