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
# Warmup Iteration   1: 3.344 ops/ms
# Warmup Iteration   2: 6.810 ops/ms
# Warmup Iteration   3: 8.274 ops/ms
Iteration   1: 8.369 ops/ms
Iteration   2: 8.961 ops/ms
Iteration   3: 8.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.742 ±(99.9%) 5.920 ops/ms [Average]
  (min, avg, max) = (8.369, 8.742, 8.961), stdev = 0.325
  CI (99.9%): [2.822, 14.662] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.855 ops/ms
# Warmup Iteration   2: 8.914 ops/ms
# Warmup Iteration   3: 9.300 ops/ms
Iteration   1: 9.394 ops/ms
Iteration   2: 9.299 ops/ms
Iteration   3: 9.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.338 ±(99.9%) 0.904 ops/ms [Average]
  (min, avg, max) = (9.299, 9.338, 9.394), stdev = 0.050
  CI (99.9%): [8.434, 10.242] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.493 ops/ms
# Warmup Iteration   2: 7.820 ops/ms
# Warmup Iteration   3: 8.118 ops/ms
Iteration   1: 8.291 ops/ms
Iteration   2: 8.306 ops/ms
Iteration   3: 8.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.221 ±(99.9%) 2.438 ops/ms [Average]
  (min, avg, max) = (8.067, 8.221, 8.306), stdev = 0.134
  CI (99.9%): [5.784, 10.659] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.015 ops/ms
# Warmup Iteration   2: 5.900 ops/ms
# Warmup Iteration   3: 6.380 ops/ms
Iteration   1: 6.595 ops/ms
Iteration   2: 6.395 ops/ms
Iteration   3: 6.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.485 ±(99.9%) 1.858 ops/ms [Average]
  (min, avg, max) = (6.395, 6.485, 6.595), stdev = 0.102
  CI (99.9%): [4.626, 8.343] (assumes normal distribution)


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
# Warmup Iteration   1: 5.702 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.011 ms/op
Iteration   1: 3.648 ±(99.9%) 0.004 ms/op
Iteration   2: 3.635 ±(99.9%) 0.003 ms/op
Iteration   3: 3.573 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.619 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (3.573, 3.619, 3.648), stdev = 0.040
  CI (99.9%): [2.881, 4.357] (assumes normal distribution)


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
# Warmup Iteration   1: 5.007 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.002 ms/op
Iteration   1: 3.437 ±(99.9%) 0.004 ms/op
Iteration   2: 3.383 ±(99.9%) 0.003 ms/op
Iteration   3: 3.364 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.395 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (3.364, 3.395, 3.437), stdev = 0.038
  CI (99.9%): [2.701, 4.088] (assumes normal distribution)


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
# Warmup Iteration   1: 5.136 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.003 ms/op
Iteration   1: 3.690 ±(99.9%) 0.004 ms/op
Iteration   2: 3.548 ±(99.9%) 0.003 ms/op
Iteration   3: 3.613 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.617 ±(99.9%) 1.301 ms/op [Average]
  (min, avg, max) = (3.548, 3.617, 3.690), stdev = 0.071
  CI (99.9%): [2.316, 4.918] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.174 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.246 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.783 ±(99.9%) 0.025 ms/op
Iteration   1: 4.742 ±(99.9%) 0.015 ms/op
Iteration   2: 4.665 ±(99.9%) 0.026 ms/op
Iteration   3: 4.738 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.715 ±(99.9%) 0.788 ms/op [Average]
  (min, avg, max) = (4.665, 4.715, 4.742), stdev = 0.043
  CI (99.9%): [3.927, 5.503] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.765 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.007 ms/op
Iteration   1: 3.654 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  13.443 ms/op
                 createUser·p0.9999: 19.422 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   2: 3.669 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.352 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  9.716 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   3: 3.776 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  11.319 ms/op
                 createUser·p0.9999: 23.251 ms/op
                 createUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259720
  mean =      3.699 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5095 
    [ 2.500,  5.000) = 245740 
    [ 5.000,  7.500) = 7665 
    [ 7.500, 10.000) = 850 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.352 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.224 ms/op
     p(99.9000) =     11.178 ms/op
     p(99.9900) =     22.449 ms/op
     p(99.9990) =     23.685 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 5.261 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.008 ms/op
Iteration   1: 3.511 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  10.204 ms/op
                 existUser·p0.9999: 22.475 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.504 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  12.487 ms/op
                 existUser·p0.9999: 19.633 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   3: 3.439 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  8.864 ms/op
                 existUser·p0.9999: 21.312 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275647
  mean =      3.484 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8768 
    [ 2.500,  5.000) = 261936 
    [ 5.000,  7.500) = 4201 
    [ 7.500, 10.000) = 408 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     11.033 ms/op
     p(99.9900) =     21.473 ms/op
     p(99.9990) =     22.618 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 5.147 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.008 ms/op
Iteration   1: 3.721 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  12.436 ms/op
                 getUser·p0.9999: 15.211 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   2: 3.658 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  8.331 ms/op
                 getUser·p0.9999: 18.391 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   3: 3.756 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  15.396 ms/op
                 getUser·p0.9999: 21.938 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258488
  mean =      3.711 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3998 
    [ 2.500,  5.000) = 247988 
    [ 5.000,  7.500) = 5763 
    [ 7.500, 10.000) = 458 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     11.977 ms/op
     p(99.9900) =     19.277 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.842 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.190 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.717 ±(99.9%) 0.015 ms/op
Iteration   1: 4.694 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.816 ms/op
                 listUser·p0.99:   8.164 ms/op
                 listUser·p0.999:  15.020 ms/op
                 listUser·p0.9999: 17.602 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 4.685 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  16.358 ms/op
                 listUser·p0.9999: 19.514 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 4.732 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.629 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.709 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  20.720 ms/op
                 listUser·p0.9999: 35.274 ms/op
                 listUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204227
  mean =      4.703 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 235 
    [ 2.500,  5.000) = 160272 
    [ 5.000,  7.500) = 39032 
    [ 7.500, 10.000) = 4076 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.660 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     34.089 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.742 ± 5.920  ops/ms
ClientGrpc.existUser                       thrpt       3   9.338 ± 0.904  ops/ms
ClientGrpc.getUser                         thrpt       3   8.221 ± 2.438  ops/ms
ClientGrpc.listUser                        thrpt       3   6.485 ± 1.858  ops/ms
ClientGrpc.createUser                       avgt       3   3.619 ± 0.738   ms/op
ClientGrpc.existUser                        avgt       3   3.395 ± 0.694   ms/op
ClientGrpc.getUser                          avgt       3   3.617 ± 1.301   ms/op
ClientGrpc.listUser                         avgt       3   4.715 ± 0.788   ms/op
ClientGrpc.createUser                     sample  259720   3.699 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.352           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.224           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.178           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.449           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.790           ms/op
ClientGrpc.existUser                      sample  275647   3.484 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.787           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.076           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.521           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.033           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.473           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.643           ms/op
ClientGrpc.getUser                        sample  258488   3.711 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.864           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.677           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.977           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.277           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.118           ms/op
ClientGrpc.listUser                       sample  204227   4.703 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.629           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.506           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.348           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.286           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.089           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.045           ms/op
