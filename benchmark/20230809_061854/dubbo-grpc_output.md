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
# Warmup Iteration   1: 2.971 ops/ms
# Warmup Iteration   2: 6.783 ops/ms
# Warmup Iteration   3: 8.181 ops/ms
Iteration   1: 8.610 ops/ms
Iteration   2: 8.621 ops/ms
Iteration   3: 8.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.620 ±(99.9%) 0.175 ops/ms [Average]
  (min, avg, max) = (8.610, 8.620, 8.629), stdev = 0.010
  CI (99.9%): [8.445, 8.795] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.381 ops/ms
# Warmup Iteration   2: 8.813 ops/ms
# Warmup Iteration   3: 8.992 ops/ms
Iteration   1: 9.194 ops/ms
Iteration   2: 9.249 ops/ms
Iteration   3: 9.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.277 ±(99.9%) 1.827 ops/ms [Average]
  (min, avg, max) = (9.194, 9.277, 9.388), stdev = 0.100
  CI (99.9%): [7.450, 11.103] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.397 ops/ms
# Warmup Iteration   2: 7.757 ops/ms
# Warmup Iteration   3: 8.172 ops/ms
Iteration   1: 8.468 ops/ms
Iteration   2: 8.636 ops/ms
Iteration   3: 8.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.649 ±(99.9%) 3.421 ops/ms [Average]
  (min, avg, max) = (8.468, 8.649, 8.842), stdev = 0.187
  CI (99.9%): [5.228, 12.069] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.454 ops/ms
# Warmup Iteration   2: 6.127 ops/ms
# Warmup Iteration   3: 6.612 ops/ms
Iteration   1: 6.823 ops/ms
Iteration   2: 6.517 ops/ms
Iteration   3: 6.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.650 ±(99.9%) 2.872 ops/ms [Average]
  (min, avg, max) = (6.517, 6.650, 6.823), stdev = 0.157
  CI (99.9%): [3.778, 9.522] (assumes normal distribution)


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
# Warmup Iteration   1: 5.743 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.004 ms/op
Iteration   1: 3.730 ±(99.9%) 0.002 ms/op
Iteration   2: 3.674 ±(99.9%) 0.003 ms/op
Iteration   3: 3.620 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.675 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.620, 3.675, 3.730), stdev = 0.055
  CI (99.9%): [2.665, 4.684] (assumes normal distribution)


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
# Warmup Iteration   1: 5.347 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.005 ms/op
Iteration   1: 3.537 ±(99.9%) 0.003 ms/op
Iteration   2: 3.553 ±(99.9%) 0.003 ms/op
Iteration   3: 3.498 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.529 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.498, 3.529, 3.553), stdev = 0.028
  CI (99.9%): [3.019, 4.039] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.888 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.005 ms/op
Iteration   1: 3.754 ±(99.9%) 0.003 ms/op
Iteration   2: 3.750 ±(99.9%) 0.003 ms/op
Iteration   3: 3.577 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.694 ±(99.9%) 1.845 ms/op [Average]
  (min, avg, max) = (3.577, 3.694, 3.754), stdev = 0.101
  CI (99.9%): [1.849, 5.539] (assumes normal distribution)


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
# Warmup Iteration   1: 6.875 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.948 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.801 ±(99.9%) 0.014 ms/op
Iteration   1: 4.640 ±(99.9%) 0.013 ms/op
Iteration   2: 4.774 ±(99.9%) 0.021 ms/op
Iteration   3: 4.669 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.694 ±(99.9%) 1.279 ms/op [Average]
  (min, avg, max) = (4.640, 4.694, 4.774), stdev = 0.070
  CI (99.9%): [3.415, 5.973] (assumes normal distribution)


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
# Warmup Iteration   1: 5.478 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.670 ±(99.9%) 0.009 ms/op
Iteration   1: 3.662 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  12.520 ms/op
                 createUser·p0.9999: 14.992 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   2: 3.636 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.213 ms/op
                 createUser·p0.999:  9.830 ms/op
                 createUser·p0.9999: 26.745 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 3.767 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.373 ms/op
                 createUser·p0.999:  11.879 ms/op
                 createUser·p0.9999: 19.661 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260336
  mean =      3.687 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10940 
    [ 2.500,  5.000) = 239944 
    [ 5.000,  7.500) = 8244 
    [ 7.500, 10.000) = 869 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     11.485 ms/op
     p(99.9900) =     25.459 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 4.857 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.009 ms/op
Iteration   1: 3.495 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  10.088 ms/op
                 existUser·p0.9999: 15.934 ms/op
                 existUser·p1.00:   16.384 ms/op

Iteration   2: 3.589 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  10.283 ms/op
                 existUser·p0.9999: 16.762 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   3: 3.524 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  9.082 ms/op
                 existUser·p0.9999: 20.215 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271612
  mean =      3.536 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11387 
    [ 2.500,  5.000) = 253186 
    [ 5.000,  7.500) = 5904 
    [ 7.500, 10.000) = 885 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     18.252 ms/op
     p(99.9990) =     20.555 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 5.288 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.009 ms/op
Iteration   1: 3.764 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  9.880 ms/op
                 getUser·p0.9999: 16.482 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   2: 3.700 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.098 ms/op
                 getUser·p0.999:  9.353 ms/op
                 getUser·p0.9999: 15.745 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 3.802 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  12.260 ms/op
                 getUser·p0.9999: 22.367 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255670
  mean =      3.755 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6228 
    [ 2.500,  5.000) = 239302 
    [ 5.000,  7.500) = 8703 
    [ 7.500, 10.000) = 1194 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =      9.896 ms/op
     p(99.9900) =     20.396 ms/op
     p(99.9990) =     22.493 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 7.013 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.848 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.828 ±(99.9%) 0.015 ms/op
Iteration   1: 4.798 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.060 ms/op
                 listUser·p0.95:   6.914 ms/op
                 listUser·p0.99:   8.929 ms/op
                 listUser·p0.999:  19.430 ms/op
                 listUser·p0.9999: 25.330 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 4.867 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.357 ms/op
                 listUser·p0.95:   7.217 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 20.887 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 4.942 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.275 ms/op
                 listUser·p0.95:   7.152 ms/op
                 listUser·p0.99:   9.353 ms/op
                 listUser·p0.999:  18.715 ms/op
                 listUser·p0.9999: 25.987 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197132
  mean =      4.868 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 397 
    [ 2.500,  5.000) = 139461 
    [ 5.000,  7.500) = 50269 
    [ 7.500, 10.000) = 5773 
    [10.000, 12.500) = 758 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      7.102 ms/op
     p(99.0000) =      9.142 ms/op
     p(99.9000) =     17.592 ms/op
     p(99.9900) =     25.274 ms/op
     p(99.9990) =     26.120 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.620 ± 0.175  ops/ms
ClientGrpc.existUser                       thrpt       3   9.277 ± 1.827  ops/ms
ClientGrpc.getUser                         thrpt       3   8.649 ± 3.421  ops/ms
ClientGrpc.listUser                        thrpt       3   6.650 ± 2.872  ops/ms
ClientGrpc.createUser                       avgt       3   3.675 ± 1.010   ms/op
ClientGrpc.existUser                        avgt       3   3.529 ± 0.510   ms/op
ClientGrpc.getUser                          avgt       3   3.694 ± 1.845   ms/op
ClientGrpc.listUser                         avgt       3   4.694 ± 1.279   ms/op
ClientGrpc.createUser                     sample  260336   3.687 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.831           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.308           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.485           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.459           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.034           ms/op
ClientGrpc.existUser                      sample  271612   3.536 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.853           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.947           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.880           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.252           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.611           ms/op
ClientGrpc.getUser                        sample  255670   3.755 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.766           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.365           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.896           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.396           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.577           ms/op
ClientGrpc.listUser                       sample  197132   4.868 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.114           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.142           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.592           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.274           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
