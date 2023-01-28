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
# Warmup Iteration   1: 2.088 ops/ms
# Warmup Iteration   2: 5.382 ops/ms
# Warmup Iteration   3: 6.721 ops/ms
Iteration   1: 7.326 ops/ms
Iteration   2: 6.764 ops/ms
Iteration   3: 7.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.061 ±(99.9%) 5.148 ops/ms [Average]
  (min, avg, max) = (6.764, 7.061, 7.326), stdev = 0.282
  CI (99.9%): [1.912, 12.209] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.376 ops/ms
# Warmup Iteration   2: 6.916 ops/ms
# Warmup Iteration   3: 7.350 ops/ms
Iteration   1: 7.727 ops/ms
Iteration   2: 7.695 ops/ms
Iteration   3: 7.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.635 ±(99.9%) 2.425 ops/ms [Average]
  (min, avg, max) = (7.482, 7.635, 7.727), stdev = 0.133
  CI (99.9%): [5.209, 10.060] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ops/ms
# Warmup Iteration   2: 6.479 ops/ms
# Warmup Iteration   3: 7.260 ops/ms
Iteration   1: 7.227 ops/ms
Iteration   2: 7.042 ops/ms
Iteration   3: 6.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.051 ±(99.9%) 3.137 ops/ms [Average]
  (min, avg, max) = (6.883, 7.051, 7.227), stdev = 0.172
  CI (99.9%): [3.914, 10.188] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.817 ops/ms
# Warmup Iteration   2: 5.201 ops/ms
# Warmup Iteration   3: 5.565 ops/ms
Iteration   1: 5.712 ops/ms
Iteration   2: 5.691 ops/ms
Iteration   3: 5.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.712 ±(99.9%) 0.373 ops/ms [Average]
  (min, avg, max) = (5.691, 5.712, 5.732), stdev = 0.020
  CI (99.9%): [5.338, 6.085] (assumes normal distribution)


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
# Warmup Iteration   1: 6.744 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.649 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.640 ±(99.9%) 0.004 ms/op
Iteration   1: 4.563 ±(99.9%) 0.006 ms/op
Iteration   2: 4.513 ±(99.9%) 0.003 ms/op
Iteration   3: 4.542 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.539 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (4.513, 4.539, 4.563), stdev = 0.025
  CI (99.9%): [4.084, 4.995] (assumes normal distribution)


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
# Warmup Iteration   1: 6.340 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.004 ms/op
Iteration   1: 4.201 ±(99.9%) 0.004 ms/op
Iteration   2: 4.025 ±(99.9%) 0.004 ms/op
Iteration   3: 4.179 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.135 ±(99.9%) 1.750 ms/op [Average]
  (min, avg, max) = (4.025, 4.135, 4.201), stdev = 0.096
  CI (99.9%): [2.386, 5.885] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.940 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.798 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.528 ±(99.9%) 0.004 ms/op
Iteration   1: 4.557 ±(99.9%) 0.003 ms/op
Iteration   2: 4.373 ±(99.9%) 0.004 ms/op
Iteration   3: 4.442 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.458 ±(99.9%) 1.693 ms/op [Average]
  (min, avg, max) = (4.373, 4.458, 4.557), stdev = 0.093
  CI (99.9%): [2.764, 6.151] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.774 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 6.157 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.747 ±(99.9%) 0.023 ms/op
Iteration   1: 5.577 ±(99.9%) 0.019 ms/op
Iteration   2: 5.746 ±(99.9%) 0.019 ms/op
Iteration   3: 5.565 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.630 ±(99.9%) 1.846 ms/op [Average]
  (min, avg, max) = (5.565, 5.630, 5.746), stdev = 0.101
  CI (99.9%): [3.784, 7.475] (assumes normal distribution)


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
# Warmup Iteration   1: 7.369 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.812 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.619 ±(99.9%) 0.017 ms/op
Iteration   1: 4.453 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.300 ms/op
                 createUser·p0.99:   8.651 ms/op
                 createUser·p0.999:  13.395 ms/op
                 createUser·p0.9999: 18.338 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   2: 4.291 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.366 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   8.798 ms/op
                 createUser·p0.999:  15.343 ms/op
                 createUser·p0.9999: 19.828 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   3: 4.322 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.609 ms/op
                 createUser·p0.50:   4.133 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.128 ms/op
                 createUser·p0.99:   8.552 ms/op
                 createUser·p0.999:  15.590 ms/op
                 createUser·p0.9999: 27.656 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 220301
  mean =      4.354 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4198 
    [ 2.500,  5.000) = 174145 
    [ 5.000,  7.500) = 37757 
    [ 7.500, 10.000) = 3229 
    [10.000, 12.500) = 606 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      4.166 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     13.938 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 6.224 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.500 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.015 ms/op
Iteration   1: 4.040 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.898 ms/op
                 existUser·p0.99:   8.167 ms/op
                 existUser·p0.999:  13.154 ms/op
                 existUser·p0.9999: 16.714 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   2: 3.984 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.865 ms/op
                 existUser·p0.99:   8.520 ms/op
                 existUser·p0.999:  15.083 ms/op
                 existUser·p0.9999: 21.462 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   3: 3.982 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.603 ms/op
                 existUser·p0.99:   8.159 ms/op
                 existUser·p0.999:  12.298 ms/op
                 existUser·p0.9999: 23.067 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 239758
  mean =      4.002 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12661 
    [ 2.500,  5.000) = 200627 
    [ 5.000,  7.500) = 22546 
    [ 7.500, 10.000) = 2862 
    [10.000, 12.500) = 663 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      8.290 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     21.562 ms/op
     p(99.9990) =     27.723 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 6.933 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.738 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.605 ±(99.9%) 0.016 ms/op
Iteration   1: 4.430 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.710 ms/op
                 getUser·p0.95:   6.332 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  12.571 ms/op
                 getUser·p0.9999: 18.761 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 4.370 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   6.111 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  13.200 ms/op
                 getUser·p0.9999: 24.423 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   3: 4.401 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.693 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  14.325 ms/op
                 getUser·p0.9999: 27.516 ms/op
                 getUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218200
  mean =      4.400 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6422 
    [ 2.500,  5.000) = 163022 
    [ 5.000,  7.500) = 44158 
    [ 7.500, 10.000) = 3429 
    [10.000, 12.500) = 844 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.275 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     27.039 ms/op
     p(99.9990) =     27.763 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 8.604 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.940 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.583 ±(99.9%) 0.022 ms/op
Iteration   1: 5.637 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   5.226 ms/op
                 listUser·p0.90:   7.864 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   11.551 ms/op
                 listUser·p0.999:  18.906 ms/op
                 listUser·p0.9999: 25.785 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   2: 5.412 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   7.487 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.813 ms/op
                 listUser·p0.999:  19.787 ms/op
                 listUser·p0.9999: 25.008 ms/op
                 listUser·p1.00:   29.131 ms/op

Iteration   3: 5.567 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   5.145 ms/op
                 listUser·p0.90:   7.709 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   12.468 ms/op
                 listUser·p0.999:  21.299 ms/op
                 listUser·p0.9999: 28.885 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173445
  mean =      5.537 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 269 
    [ 2.500,  5.000) = 77970 
    [ 5.000,  7.500) = 75666 
    [ 7.500, 10.000) = 15170 
    [10.000, 12.500) = 2987 
    [12.500, 15.000) = 893 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      7.692 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     11.944 ms/op
     p(99.9000) =     20.039 ms/op
     p(99.9900) =     28.219 ms/op
     p(99.9990) =     29.414 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.061 ± 5.148  ops/ms
ClientGrpc.existUser                       thrpt       3   7.635 ± 2.425  ops/ms
ClientGrpc.getUser                         thrpt       3   7.051 ± 3.137  ops/ms
ClientGrpc.listUser                        thrpt       3   5.712 ± 0.373  ops/ms
ClientGrpc.createUser                       avgt       3   4.539 ± 0.455   ms/op
ClientGrpc.existUser                        avgt       3   4.135 ± 1.750   ms/op
ClientGrpc.getUser                          avgt       3   4.458 ± 1.693   ms/op
ClientGrpc.listUser                         avgt       3   5.630 ± 1.846   ms/op
ClientGrpc.createUser                     sample  220301   4.354 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.609           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.166           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.546           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.152           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.667           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.938           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.361           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.853           ms/op
ClientGrpc.existUser                      sample  239758   4.002 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.780           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.854           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.095           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.784           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.290           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.484           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.562           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.574           ms/op
ClientGrpc.getUser                        sample  218200   4.400 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.865           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.275           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.798           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.550           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.039           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.820           ms/op
ClientGrpc.listUser                       sample  173445   5.537 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.489           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.692           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.765           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.944           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.039           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.219           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.655           ms/op
