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
# Warmup Iteration   1: 2.830 ops/ms
# Warmup Iteration   2: 6.431 ops/ms
# Warmup Iteration   3: 8.121 ops/ms
Iteration   1: 8.451 ops/ms
Iteration   2: 8.632 ops/ms
Iteration   3: 8.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.596 ±(99.9%) 2.374 ops/ms [Average]
  (min, avg, max) = (8.451, 8.596, 8.704), stdev = 0.130
  CI (99.9%): [6.222, 10.970] (assumes normal distribution)


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
# Warmup Iteration   1: 5.166 ops/ms
# Warmup Iteration   2: 8.232 ops/ms
# Warmup Iteration   3: 8.663 ops/ms
Iteration   1: 8.968 ops/ms
Iteration   2: 9.131 ops/ms
Iteration   3: 9.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.085 ±(99.9%) 1.867 ops/ms [Average]
  (min, avg, max) = (8.968, 9.085, 9.157), stdev = 0.102
  CI (99.9%): [7.219, 10.952] (assumes normal distribution)


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
# Warmup Iteration   1: 4.910 ops/ms
# Warmup Iteration   2: 7.599 ops/ms
# Warmup Iteration   3: 8.136 ops/ms
Iteration   1: 8.551 ops/ms
Iteration   2: 8.646 ops/ms
Iteration   3: 8.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.554 ±(99.9%) 1.643 ops/ms [Average]
  (min, avg, max) = (8.466, 8.554, 8.646), stdev = 0.090
  CI (99.9%): [6.911, 10.198] (assumes normal distribution)


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
# Warmup Iteration   1: 4.629 ops/ms
# Warmup Iteration   2: 5.863 ops/ms
# Warmup Iteration   3: 6.270 ops/ms
Iteration   1: 6.420 ops/ms
Iteration   2: 6.650 ops/ms
Iteration   3: 6.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.584 ±(99.9%) 2.609 ops/ms [Average]
  (min, avg, max) = (6.420, 6.584, 6.682), stdev = 0.143
  CI (99.9%): [3.975, 9.193] (assumes normal distribution)


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
# Warmup Iteration   1: 5.604 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.013 ms/op
Iteration   1: 3.752 ±(99.9%) 0.004 ms/op
Iteration   2: 3.687 ±(99.9%) 0.004 ms/op
Iteration   3: 3.767 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.735 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (3.687, 3.735, 3.767), stdev = 0.043
  CI (99.9%): [2.958, 4.513] (assumes normal distribution)


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
# Warmup Iteration   1: 5.512 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.006 ms/op
Iteration   1: 3.497 ±(99.9%) 0.002 ms/op
Iteration   2: 3.489 ±(99.9%) 0.004 ms/op
Iteration   3: 3.464 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.484 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.464, 3.484, 3.497), stdev = 0.017
  CI (99.9%): [3.167, 3.800] (assumes normal distribution)


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
# Warmup Iteration   1: 4.913 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.004 ms/op
Iteration   1: 3.664 ±(99.9%) 0.003 ms/op
Iteration   2: 3.728 ±(99.9%) 0.001 ms/op
Iteration   3: 3.741 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.711 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.664, 3.711, 3.741), stdev = 0.042
  CI (99.9%): [2.952, 4.470] (assumes normal distribution)


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
# Warmup Iteration   1: 6.198 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 5.251 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.916 ±(99.9%) 0.040 ms/op
Iteration   1: 4.709 ±(99.9%) 0.013 ms/op
Iteration   2: 4.724 ±(99.9%) 0.018 ms/op
Iteration   3: 4.816 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.750 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (4.709, 4.750, 4.816), stdev = 0.058
  CI (99.9%): [3.696, 5.804] (assumes normal distribution)


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
# Warmup Iteration   1: 5.523 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.009 ms/op
Iteration   1: 3.769 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  10.084 ms/op
                 createUser·p0.9999: 20.219 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   2: 3.732 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  11.665 ms/op
                 createUser·p0.9999: 42.926 ms/op
                 createUser·p1.00:   42.992 ms/op

Iteration   3: 3.756 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  16.335 ms/op
                 createUser·p0.9999: 35.225 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255673
  mean =      3.752 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 247805 
    [ 5.000, 10.000) = 7572 
    [10.000, 15.000) = 128 
    [15.000, 20.000) = 60 
    [20.000, 25.000) = 12 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 45 
    [35.000, 40.000) = 34 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     11.632 ms/op
     p(99.9900) =     37.580 ms/op
     p(99.9990) =     42.992 ms/op
     p(99.9999) =     42.992 ms/op
    p(100.0000) =     42.992 ms/op


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
# Warmup Iteration   1: 5.027 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.618 ±(99.9%) 0.008 ms/op
Iteration   1: 3.646 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.525 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  10.774 ms/op
                 existUser·p0.9999: 19.792 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.560 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  11.977 ms/op
                 existUser·p0.9999: 16.368 ms/op
                 existUser·p1.00:   16.663 ms/op

Iteration   3: 3.608 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  15.095 ms/op
                 existUser·p0.9999: 22.188 ms/op
                 existUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266201
  mean =      3.604 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5563 
    [ 2.500,  5.000) = 254827 
    [ 5.000,  7.500) = 4661 
    [ 7.500, 10.000) = 742 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 5.499 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.672 ±(99.9%) 0.009 ms/op
Iteration   1: 3.732 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.109 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 18.308 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.628 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  13.709 ms/op
                 getUser·p0.9999: 29.923 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   3: 3.679 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  8.913 ms/op
                 getUser·p0.9999: 23.746 ms/op
                 getUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261023
  mean =      3.679 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7442 
    [ 2.500,  5.000) = 246043 
    [ 5.000,  7.500) = 6687 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     28.508 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 6.143 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.431 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.868 ±(99.9%) 0.015 ms/op
Iteration   1: 4.755 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.821 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.767 ms/op
                 listUser·p0.95:   6.774 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  15.770 ms/op
                 listUser·p0.9999: 27.594 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   2: 4.776 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.783 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  16.319 ms/op
                 listUser·p0.9999: 20.172 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   3: 4.773 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.751 ms/op
                 listUser·p0.95:   6.685 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  19.984 ms/op
                 listUser·p0.9999: 29.229 ms/op
                 listUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201331
  mean =      4.768 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 365 
    [ 2.500,  5.000) = 156331 
    [ 5.000,  7.500) = 39237 
    [ 7.500, 10.000) = 4415 
    [10.000, 12.500) = 624 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      6.750 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     16.504 ms/op
     p(99.9900) =     28.397 ms/op
     p(99.9990) =     29.717 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.596 ± 2.374  ops/ms
ClientGrpc.existUser                       thrpt       3   9.085 ± 1.867  ops/ms
ClientGrpc.getUser                         thrpt       3   8.554 ± 1.643  ops/ms
ClientGrpc.listUser                        thrpt       3   6.584 ± 2.609  ops/ms
ClientGrpc.createUser                       avgt       3   3.735 ± 0.777   ms/op
ClientGrpc.existUser                        avgt       3   3.484 ± 0.316   ms/op
ClientGrpc.getUser                          avgt       3   3.711 ± 0.759   ms/op
ClientGrpc.listUser                         avgt       3   4.750 ± 1.054   ms/op
ClientGrpc.createUser                     sample  255673   3.752 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.647           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.988           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.632           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          37.580           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          42.992           ms/op
ClientGrpc.existUser                      sample  266201   3.604 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.525           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.825           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.419           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.792           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.723           ms/op
ClientGrpc.getUser                        sample  261023   3.679 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.710           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.013           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.470           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.508           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.212           ms/op
ClientGrpc.listUser                       sample  201331   4.768 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.009           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.733           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.504           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.397           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.753           ms/op
