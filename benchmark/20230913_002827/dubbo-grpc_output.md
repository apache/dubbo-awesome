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
# Warmup Iteration   1: 3.123 ops/ms
# Warmup Iteration   2: 6.987 ops/ms
# Warmup Iteration   3: 8.226 ops/ms
Iteration   1: 8.464 ops/ms
Iteration   2: 8.631 ops/ms
Iteration   3: 8.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.512 ±(99.9%) 1.878 ops/ms [Average]
  (min, avg, max) = (8.443, 8.512, 8.631), stdev = 0.103
  CI (99.9%): [6.635, 10.390] (assumes normal distribution)


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
# Warmup Iteration   1: 6.260 ops/ms
# Warmup Iteration   2: 8.503 ops/ms
# Warmup Iteration   3: 9.305 ops/ms
Iteration   1: 9.204 ops/ms
Iteration   2: 9.284 ops/ms
Iteration   3: 9.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.270 ±(99.9%) 1.106 ops/ms [Average]
  (min, avg, max) = (9.204, 9.270, 9.323), stdev = 0.061
  CI (99.9%): [8.164, 10.377] (assumes normal distribution)


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
# Warmup Iteration   1: 5.302 ops/ms
# Warmup Iteration   2: 8.321 ops/ms
# Warmup Iteration   3: 8.370 ops/ms
Iteration   1: 8.640 ops/ms
Iteration   2: 8.701 ops/ms
Iteration   3: 8.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.654 ±(99.9%) 0.774 ops/ms [Average]
  (min, avg, max) = (8.619, 8.654, 8.701), stdev = 0.042
  CI (99.9%): [7.880, 9.427] (assumes normal distribution)


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
# Warmup Iteration   1: 4.528 ops/ms
# Warmup Iteration   2: 6.172 ops/ms
# Warmup Iteration   3: 6.505 ops/ms
Iteration   1: 6.463 ops/ms
Iteration   2: 6.450 ops/ms
Iteration   3: 6.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.466 ±(99.9%) 0.311 ops/ms [Average]
  (min, avg, max) = (6.450, 6.466, 6.484), stdev = 0.017
  CI (99.9%): [6.155, 6.777] (assumes normal distribution)


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
# Warmup Iteration   1: 5.411 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.019 ms/op
Iteration   1: 3.794 ±(99.9%) 0.003 ms/op
Iteration   2: 3.684 ±(99.9%) 0.004 ms/op
Iteration   3: 3.711 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.730 ±(99.9%) 1.048 ms/op [Average]
  (min, avg, max) = (3.684, 3.730, 3.794), stdev = 0.057
  CI (99.9%): [2.682, 4.777] (assumes normal distribution)


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
# Warmup Iteration   1: 5.100 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.003 ms/op
Iteration   1: 3.594 ±(99.9%) 0.004 ms/op
Iteration   2: 3.430 ±(99.9%) 0.004 ms/op
Iteration   3: 3.570 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.531 ±(99.9%) 1.618 ms/op [Average]
  (min, avg, max) = (3.430, 3.531, 3.594), stdev = 0.089
  CI (99.9%): [1.913, 5.150] (assumes normal distribution)


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
# Warmup Iteration   1: 5.308 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.745 ±(99.9%) 0.004 ms/op
Iteration   1: 3.681 ±(99.9%) 0.005 ms/op
Iteration   2: 3.685 ±(99.9%) 0.005 ms/op
Iteration   3: 3.629 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.665 ±(99.9%) 0.573 ms/op [Average]
  (min, avg, max) = (3.629, 3.665, 3.685), stdev = 0.031
  CI (99.9%): [3.092, 4.238] (assumes normal distribution)


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
# Warmup Iteration   1: 6.194 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.284 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.872 ±(99.9%) 0.030 ms/op
Iteration   1: 4.848 ±(99.9%) 0.011 ms/op
Iteration   2: 4.811 ±(99.9%) 0.015 ms/op
Iteration   3: 4.743 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.800 ±(99.9%) 0.969 ms/op [Average]
  (min, avg, max) = (4.743, 4.800, 4.848), stdev = 0.053
  CI (99.9%): [3.832, 5.769] (assumes normal distribution)


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
# Warmup Iteration   1: 5.456 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.010 ms/op
Iteration   1: 3.699 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  10.136 ms/op
                 createUser·p0.9999: 16.046 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   2: 3.708 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.349 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  11.157 ms/op
                 createUser·p0.9999: 17.239 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   3: 3.692 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  11.701 ms/op
                 createUser·p0.9999: 19.737 ms/op
                 createUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259638
  mean =      3.700 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9790 
    [ 2.500,  5.000) = 239617 
    [ 5.000,  7.500) = 8960 
    [ 7.500, 10.000) = 808 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     19.170 ms/op
     p(99.9990) =     20.192 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 5.007 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.009 ms/op
Iteration   1: 3.476 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.422 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  9.339 ms/op
                 existUser·p0.9999: 14.018 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   2: 3.481 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.820 ms/op
                 existUser·p0.999:  11.464 ms/op
                 existUser·p0.9999: 17.754 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   3: 3.472 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.955 ms/op
                 existUser·p0.999:  10.418 ms/op
                 existUser·p0.9999: 19.850 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275951
  mean =      3.476 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11221 
    [ 2.500,  5.000) = 257934 
    [ 5.000,  7.500) = 5907 
    [ 7.500, 10.000) = 603 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     10.142 ms/op
     p(99.9900) =     17.708 ms/op
     p(99.9990) =     20.259 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 5.340 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.011 ms/op
Iteration   1: 3.751 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.123 ms/op
                 getUser·p0.999:  9.433 ms/op
                 getUser·p0.9999: 16.089 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   2: 3.758 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  11.534 ms/op
                 getUser·p0.9999: 20.938 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   3: 3.686 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  9.731 ms/op
                 getUser·p0.9999: 18.623 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257034
  mean =      3.731 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6944 
    [ 2.500,  5.000) = 240662 
    [ 5.000,  7.500) = 8471 
    [ 7.500, 10.000) = 660 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     10.338 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     21.295 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 5.851 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.454 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.936 ±(99.9%) 0.015 ms/op
Iteration   1: 4.779 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.980 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  15.189 ms/op
                 listUser·p0.9999: 18.360 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 4.754 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.751 ms/op
                 listUser·p0.95:   6.775 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 23.709 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   3: 4.880 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   7.152 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  19.104 ms/op
                 listUser·p0.9999: 33.260 ms/op
                 listUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199697
  mean =      4.804 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 357 
    [ 2.500,  5.000) = 149140 
    [ 5.000,  7.500) = 43833 
    [ 7.500, 10.000) = 5480 
    [10.000, 12.500) = 486 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     17.148 ms/op
     p(99.9900) =     32.997 ms/op
     p(99.9990) =     33.523 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.512 ± 1.878  ops/ms
ClientGrpc.existUser                       thrpt       3   9.270 ± 1.106  ops/ms
ClientGrpc.getUser                         thrpt       3   8.654 ± 0.774  ops/ms
ClientGrpc.listUser                        thrpt       3   6.466 ± 0.311  ops/ms
ClientGrpc.createUser                       avgt       3   3.730 ± 1.048   ms/op
ClientGrpc.existUser                        avgt       3   3.531 ± 1.618   ms/op
ClientGrpc.getUser                          avgt       3   3.665 ± 0.573   ms/op
ClientGrpc.listUser                         avgt       3   4.800 ± 0.969   ms/op
ClientGrpc.createUser                     sample  259638   3.700 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.349           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.332           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.272           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.170           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.349           ms/op
ClientGrpc.existUser                      sample  275951   3.476 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.650           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.833           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.142           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.708           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  257034   3.731 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.931           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.021           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.338           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.038           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.398           ms/op
ClientGrpc.listUser                       sample  199697   4.804 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.333           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.684           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.148           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.997           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.817           ms/op
