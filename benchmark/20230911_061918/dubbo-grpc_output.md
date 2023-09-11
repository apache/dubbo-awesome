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
# Warmup Iteration   1: 2.006 ops/ms
# Warmup Iteration   2: 4.814 ops/ms
# Warmup Iteration   3: 6.156 ops/ms
Iteration   1: 6.610 ops/ms
Iteration   2: 6.493 ops/ms
Iteration   3: 6.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.661 ±(99.9%) 3.621 ops/ms [Average]
  (min, avg, max) = (6.493, 6.661, 6.880), stdev = 0.198
  CI (99.9%): [3.040, 10.282] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.915 ops/ms
# Warmup Iteration   2: 6.478 ops/ms
# Warmup Iteration   3: 6.999 ops/ms
Iteration   1: 6.992 ops/ms
Iteration   2: 7.084 ops/ms
Iteration   3: 7.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.077 ±(99.9%) 1.480 ops/ms [Average]
  (min, avg, max) = (6.992, 7.077, 7.154), stdev = 0.081
  CI (99.9%): [5.597, 8.556] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ops/ms
# Warmup Iteration   2: 6.066 ops/ms
# Warmup Iteration   3: 6.611 ops/ms
Iteration   1: 6.904 ops/ms
Iteration   2: 6.850 ops/ms
Iteration   3: 7.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.932 ±(99.9%) 1.793 ops/ms [Average]
  (min, avg, max) = (6.850, 6.932, 7.041), stdev = 0.098
  CI (99.9%): [5.139, 8.725] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.200 ops/ms
# Warmup Iteration   2: 5.061 ops/ms
# Warmup Iteration   3: 5.189 ops/ms
Iteration   1: 5.407 ops/ms
Iteration   2: 5.441 ops/ms
Iteration   3: 5.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.468 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (5.407, 5.468, 5.555), stdev = 0.077
  CI (99.9%): [4.055, 6.881] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.318 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.876 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.775 ±(99.9%) 0.024 ms/op
Iteration   1: 4.636 ±(99.9%) 0.004 ms/op
Iteration   2: 4.529 ±(99.9%) 0.005 ms/op
Iteration   3: 4.542 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.569 ±(99.9%) 1.064 ms/op [Average]
  (min, avg, max) = (4.529, 4.569, 4.636), stdev = 0.058
  CI (99.9%): [3.505, 5.633] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.537 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.680 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.438 ±(99.9%) 0.005 ms/op
Iteration   1: 4.326 ±(99.9%) 0.004 ms/op
Iteration   2: 4.370 ±(99.9%) 0.003 ms/op
Iteration   3: 4.364 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.353 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (4.326, 4.353, 4.370), stdev = 0.024
  CI (99.9%): [3.915, 4.792] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.164 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.086 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.682 ±(99.9%) 0.008 ms/op
Iteration   1: 4.642 ±(99.9%) 0.004 ms/op
Iteration   2: 4.488 ±(99.9%) 0.005 ms/op
Iteration   3: 4.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.552 ±(99.9%) 1.460 ms/op [Average]
  (min, avg, max) = (4.488, 4.552, 4.642), stdev = 0.080
  CI (99.9%): [3.092, 6.012] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.172 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 6.795 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.116 ±(99.9%) 0.027 ms/op
Iteration   1: 6.223 ±(99.9%) 0.021 ms/op
Iteration   2: 6.103 ±(99.9%) 0.047 ms/op
Iteration   3: 5.967 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.098 ±(99.9%) 2.338 ms/op [Average]
  (min, avg, max) = (5.967, 6.098, 6.223), stdev = 0.128
  CI (99.9%): [3.760, 8.436] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.584 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 4.875 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.620 ±(99.9%) 0.014 ms/op
Iteration   1: 4.571 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.726 ms/op
                 createUser·p0.95:   6.308 ms/op
                 createUser·p0.99:   8.413 ms/op
                 createUser·p0.999:  16.005 ms/op
                 createUser·p0.9999: 21.758 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 4.592 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   5.743 ms/op
                 createUser·p0.95:   6.406 ms/op
                 createUser·p0.99:   9.086 ms/op
                 createUser·p0.999:  14.385 ms/op
                 createUser·p0.9999: 24.217 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   3: 4.643 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.841 ms/op
                 createUser·p0.95:   6.365 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  25.853 ms/op
                 createUser·p0.9999: 29.510 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 208718
  mean =      4.602 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3594 
    [ 2.500,  5.000) = 152597 
    [ 5.000,  7.500) = 48690 
    [ 7.500, 10.000) = 2686 
    [10.000, 12.500) = 455 
    [12.500, 15.000) = 437 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     16.077 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     32.241 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.000 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.887 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.612 ±(99.9%) 0.016 ms/op
Iteration   1: 4.519 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.751 ms/op
                 existUser·p0.95:   6.308 ms/op
                 existUser·p0.99:   8.176 ms/op
                 existUser·p0.999:  12.803 ms/op
                 existUser·p0.9999: 19.263 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   2: 4.472 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   4.325 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   6.160 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  14.893 ms/op
                 existUser·p0.9999: 18.678 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   3: 4.560 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   4.325 ms/op
                 existUser·p0.90:   5.939 ms/op
                 existUser·p0.95:   6.758 ms/op
                 existUser·p0.99:   9.929 ms/op
                 existUser·p0.999:  16.087 ms/op
                 existUser·p0.9999: 23.330 ms/op
                 existUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 212381
  mean =      4.517 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6016 
    [ 2.500,  5.000) = 155602 
    [ 5.000,  7.500) = 46041 
    [ 7.500, 10.000) = 3307 
    [10.000, 12.500) = 837 
    [12.500, 15.000) = 372 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.405 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     22.201 ms/op
     p(99.9990) =     23.687 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 7.924 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 5.100 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.815 ±(99.9%) 0.016 ms/op
Iteration   1: 4.632 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   5.857 ms/op
                 getUser·p0.95:   6.545 ms/op
                 getUser·p0.99:   9.060 ms/op
                 getUser·p0.999:  14.513 ms/op
                 getUser·p0.9999: 17.882 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   2: 4.531 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  13.959 ms/op
                 getUser·p0.9999: 18.847 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   3: 4.482 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   8.315 ms/op
                 getUser·p0.999:  13.994 ms/op
                 getUser·p0.9999: 23.841 ms/op
                 getUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 211147
  mean =      4.548 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5245 
    [ 2.500,  5.000) = 156764 
    [ 5.000,  7.500) = 44655 
    [ 7.500, 10.000) = 3526 
    [10.000, 12.500) = 556 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     24.277 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 7.855 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.544 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 6.192 ±(99.9%) 0.027 ms/op
Iteration   1: 6.273 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   8.667 ms/op
                 listUser·p0.95:   9.945 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  22.839 ms/op
                 listUser·p0.9999: 29.160 ms/op
                 listUser·p1.00:   29.852 ms/op

Iteration   2: 6.124 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.729 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   8.364 ms/op
                 listUser·p0.95:   9.552 ms/op
                 listUser·p0.99:   12.435 ms/op
                 listUser·p0.999:  17.819 ms/op
                 listUser·p0.9999: 21.336 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 6.140 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   8.208 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   12.517 ms/op
                 listUser·p0.999:  22.794 ms/op
                 listUser·p0.9999: 33.147 ms/op
                 listUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 155276
  mean =      6.178 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 35352 
    [ 5.000,  7.500) = 93335 
    [ 7.500, 10.000) = 20036 
    [10.000, 12.500) = 4706 
    [12.500, 15.000) = 1187 
    [15.000, 17.500) = 277 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.505 ms/op
     p(50.0000) =      5.743 ms/op
     p(90.0000) =      8.405 ms/op
     p(95.0000) =      9.683 ms/op
     p(99.0000) =     12.698 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     31.982 ms/op
     p(99.9990) =     34.241 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.661 ± 3.621  ops/ms
ClientGrpc.existUser                       thrpt       3   7.077 ± 1.480  ops/ms
ClientGrpc.getUser                         thrpt       3   6.932 ± 1.793  ops/ms
ClientGrpc.listUser                        thrpt       3   5.468 ± 1.413  ops/ms
ClientGrpc.createUser                       avgt       3   4.569 ± 1.064   ms/op
ClientGrpc.existUser                        avgt       3   4.353 ± 0.439   ms/op
ClientGrpc.getUser                          avgt       3   4.552 ± 1.460   ms/op
ClientGrpc.listUser                         avgt       3   6.098 ± 2.338   ms/op
ClientGrpc.createUser                     sample  208718   4.602 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.081           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.775           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.357           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.602           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.077           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.787           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.375           ms/op
ClientGrpc.existUser                      sample  212381   4.517 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.905           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.743           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.405           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.847           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.877           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.201           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.790           ms/op
ClientGrpc.getUser                        sample  211147   4.548 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.645           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.702           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.332           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.651           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.025           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.004           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.412           ms/op
ClientGrpc.listUser                       sample  155276   6.178 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.505           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.405           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.683           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.698           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.398           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.982           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.603           ms/op
