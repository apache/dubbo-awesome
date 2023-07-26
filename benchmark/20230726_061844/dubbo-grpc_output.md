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
# Warmup Iteration   1: 2.183 ops/ms
# Warmup Iteration   2: 5.497 ops/ms
# Warmup Iteration   3: 6.671 ops/ms
Iteration   1: 6.756 ops/ms
Iteration   2: 7.180 ops/ms
Iteration   3: 7.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.034 ±(99.9%) 4.394 ops/ms [Average]
  (min, avg, max) = (6.756, 7.034, 7.180), stdev = 0.241
  CI (99.9%): [2.640, 11.427] (assumes normal distribution)


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
# Warmup Iteration   1: 4.591 ops/ms
# Warmup Iteration   2: 7.069 ops/ms
# Warmup Iteration   3: 7.479 ops/ms
Iteration   1: 7.830 ops/ms
Iteration   2: 7.802 ops/ms
Iteration   3: 7.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.750 ±(99.9%) 2.105 ops/ms [Average]
  (min, avg, max) = (7.617, 7.750, 7.830), stdev = 0.115
  CI (99.9%): [5.645, 9.855] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.357 ops/ms
# Warmup Iteration   2: 6.609 ops/ms
# Warmup Iteration   3: 6.765 ops/ms
Iteration   1: 7.329 ops/ms
Iteration   2: 7.105 ops/ms
Iteration   3: 6.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.940 ±(99.9%) 8.986 ops/ms [Average]
  (min, avg, max) = (6.386, 6.940, 7.329), stdev = 0.493
  CI (99.9%): [≈ 0, 15.926] (assumes normal distribution)


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
# Warmup Iteration   1: 3.688 ops/ms
# Warmup Iteration   2: 4.938 ops/ms
# Warmup Iteration   3: 5.365 ops/ms
Iteration   1: 5.616 ops/ms
Iteration   2: 5.479 ops/ms
Iteration   3: 5.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.569 ±(99.9%) 1.410 ops/ms [Average]
  (min, avg, max) = (5.479, 5.569, 5.616), stdev = 0.077
  CI (99.9%): [4.159, 6.978] (assumes normal distribution)


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
# Warmup Iteration   1: 6.690 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.935 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.563 ±(99.9%) 0.017 ms/op
Iteration   1: 4.458 ±(99.9%) 0.005 ms/op
Iteration   2: 4.878 ±(99.9%) 0.005 ms/op
Iteration   3: 4.393 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.576 ±(99.9%) 4.803 ms/op [Average]
  (min, avg, max) = (4.393, 4.576, 4.878), stdev = 0.263
  CI (99.9%): [≈ 0, 9.380] (assumes normal distribution)


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
# Warmup Iteration   1: 6.346 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.552 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.003 ms/op
Iteration   1: 4.139 ±(99.9%) 0.003 ms/op
Iteration   2: 4.108 ±(99.9%) 0.003 ms/op
Iteration   3: 4.132 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.126 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (4.108, 4.126, 4.139), stdev = 0.016
  CI (99.9%): [3.835, 4.418] (assumes normal distribution)


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
# Warmup Iteration   1: 6.840 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.910 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.579 ±(99.9%) 0.004 ms/op
Iteration   1: 4.425 ±(99.9%) 0.003 ms/op
Iteration   2: 4.399 ±(99.9%) 0.004 ms/op
Iteration   3: 4.528 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.451 ±(99.9%) 1.243 ms/op [Average]
  (min, avg, max) = (4.399, 4.451, 4.528), stdev = 0.068
  CI (99.9%): [3.207, 5.694] (assumes normal distribution)


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
# Warmup Iteration   1: 7.864 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.937 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.038 ±(99.9%) 0.018 ms/op
Iteration   1: 5.754 ±(99.9%) 0.017 ms/op
Iteration   2: 5.700 ±(99.9%) 0.030 ms/op
Iteration   3: 5.976 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.810 ±(99.9%) 2.673 ms/op [Average]
  (min, avg, max) = (5.700, 5.810, 5.976), stdev = 0.147
  CI (99.9%): [3.137, 8.483] (assumes normal distribution)


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
# Warmup Iteration   1: 6.867 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.846 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.569 ±(99.9%) 0.016 ms/op
Iteration   1: 4.432 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.545 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 16.999 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   2: 4.433 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   7.995 ms/op
                 createUser·p0.999:  11.928 ms/op
                 createUser·p0.9999: 18.573 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   3: 4.575 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.726 ms/op
                 createUser·p0.95:   6.250 ms/op
                 createUser·p0.99:   8.176 ms/op
                 createUser·p0.999:  17.039 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214287
  mean =      4.479 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3358 
    [ 2.500,  5.000) = 161241 
    [ 5.000,  7.500) = 46832 
    [ 7.500, 10.000) = 2316 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     13.507 ms/op
     p(99.9900) =     20.251 ms/op
     p(99.9990) =     21.402 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 6.045 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.012 ms/op
Iteration   1: 4.239 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   4.080 ms/op
                 existUser·p0.90:   5.333 ms/op
                 existUser·p0.95:   5.874 ms/op
                 existUser·p0.99:   7.774 ms/op
                 existUser·p0.999:  11.577 ms/op
                 existUser·p0.9999: 15.315 ms/op
                 existUser·p1.00:   16.400 ms/op

Iteration   2: 4.270 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   4.129 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  11.813 ms/op
                 existUser·p0.9999: 20.742 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   3: 4.231 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.276 ms/op
                 existUser·p0.95:   5.757 ms/op
                 existUser·p0.99:   7.520 ms/op
                 existUser·p0.999:  14.078 ms/op
                 existUser·p0.9999: 21.539 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 226005
  mean =      4.247 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3416 
    [ 2.500,  5.000) = 188997 
    [ 5.000,  7.500) = 31345 
    [ 7.500, 10.000) = 1770 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     22.248 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 6.868 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.708 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.661 ±(99.9%) 0.014 ms/op
Iteration   1: 4.480 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.669 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   7.946 ms/op
                 getUser·p0.999:  15.450 ms/op
                 getUser·p0.9999: 22.147 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   2: 4.889 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.468 ms/op
                 getUser·p0.50:   4.645 ms/op
                 getUser·p0.90:   6.365 ms/op
                 getUser·p0.95:   7.315 ms/op
                 getUser·p0.99:   9.683 ms/op
                 getUser·p0.999:  13.739 ms/op
                 getUser·p0.9999: 22.789 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   3: 4.554 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.685 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   7.963 ms/op
                 getUser·p0.999:  16.155 ms/op
                 getUser·p0.9999: 26.688 ms/op
                 getUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 206995
  mean =      4.634 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3633 
    [ 2.500,  5.000) = 144827 
    [ 5.000,  7.500) = 53581 
    [ 7.500, 10.000) = 4065 
    [10.000, 12.500) = 543 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.563 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     15.336 ms/op
     p(99.9900) =     25.218 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 8.770 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.077 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.701 ±(99.9%) 0.022 ms/op
Iteration   1: 5.742 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.700 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.370 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 19.081 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 5.552 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   10.797 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 21.974 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 5.737 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.856 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  21.561 ms/op
                 listUser·p0.9999: 31.752 ms/op
                 listUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169105
  mean =      5.675 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 174 
    [ 2.500,  5.000) = 62792 
    [ 5.000,  7.500) = 87116 
    [ 7.500, 10.000) = 15446 
    [10.000, 12.500) = 2820 
    [12.500, 15.000) = 361 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      7.676 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     31.427 ms/op
     p(99.9990) =     32.925 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.034 ± 4.394  ops/ms
ClientGrpc.existUser                       thrpt       3   7.750 ± 2.105  ops/ms
ClientGrpc.getUser                         thrpt       3   6.940 ± 8.986  ops/ms
ClientGrpc.listUser                        thrpt       3   5.569 ± 1.410  ops/ms
ClientGrpc.createUser                       avgt       3   4.576 ± 4.803   ms/op
ClientGrpc.existUser                        avgt       3   4.126 ± 0.291   ms/op
ClientGrpc.getUser                          avgt       3   4.451 ± 1.243   ms/op
ClientGrpc.listUser                         avgt       3   5.810 ± 2.673   ms/op
ClientGrpc.createUser                     sample  214287   4.479 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.835           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.603           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.111           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.905           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.507           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.251           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.627           ms/op
ClientGrpc.existUser                      sample  226005   4.247 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.625           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.096           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.825           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.496           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.108           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.546           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.282           ms/op
ClientGrpc.getUser                        sample  206995   4.634 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.468           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.882           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.563           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.782           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.336           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.218           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.804           ms/op
ClientGrpc.listUser                       sample  169105   5.675 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.225           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.676           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.076           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.153           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.427           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.423           ms/op
