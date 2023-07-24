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
# Warmup Iteration   1: 3.225 ops/ms
# Warmup Iteration   2: 6.320 ops/ms
# Warmup Iteration   3: 7.953 ops/ms
Iteration   1: 8.670 ops/ms
Iteration   2: 8.415 ops/ms
Iteration   3: 8.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.537 ±(99.9%) 2.331 ops/ms [Average]
  (min, avg, max) = (8.415, 8.537, 8.670), stdev = 0.128
  CI (99.9%): [6.206, 10.867] (assumes normal distribution)


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
# Warmup Iteration   1: 6.074 ops/ms
# Warmup Iteration   2: 8.660 ops/ms
# Warmup Iteration   3: 8.979 ops/ms
Iteration   1: 9.207 ops/ms
Iteration   2: 9.145 ops/ms
Iteration   3: 9.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.152 ±(99.9%) 0.952 ops/ms [Average]
  (min, avg, max) = (9.104, 9.152, 9.207), stdev = 0.052
  CI (99.9%): [8.200, 10.104] (assumes normal distribution)


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
# Warmup Iteration   1: 5.734 ops/ms
# Warmup Iteration   2: 8.130 ops/ms
# Warmup Iteration   3: 8.685 ops/ms
Iteration   1: 8.498 ops/ms
Iteration   2: 8.663 ops/ms
Iteration   3: 8.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.584 ±(99.9%) 1.507 ops/ms [Average]
  (min, avg, max) = (8.498, 8.584, 8.663), stdev = 0.083
  CI (99.9%): [7.077, 10.091] (assumes normal distribution)


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
# Warmup Iteration   1: 4.300 ops/ms
# Warmup Iteration   2: 6.195 ops/ms
# Warmup Iteration   3: 6.698 ops/ms
Iteration   1: 6.726 ops/ms
Iteration   2: 6.900 ops/ms
Iteration   3: 6.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.768 ±(99.9%) 2.113 ops/ms [Average]
  (min, avg, max) = (6.680, 6.768, 6.900), stdev = 0.116
  CI (99.9%): [4.656, 8.881] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.449 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.041 ms/op
Iteration   1: 3.655 ±(99.9%) 0.005 ms/op
Iteration   2: 3.603 ±(99.9%) 0.006 ms/op
Iteration   3: 3.645 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.634 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (3.603, 3.634, 3.655), stdev = 0.027
  CI (99.9%): [3.137, 4.132] (assumes normal distribution)


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
# Warmup Iteration   1: 6.386 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.576 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.002 ms/op
Iteration   1: 3.732 ±(99.9%) 0.009 ms/op
Iteration   2: 3.633 ±(99.9%) 0.004 ms/op
Iteration   3: 3.658 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.675 ±(99.9%) 0.942 ms/op [Average]
  (min, avg, max) = (3.633, 3.675, 3.732), stdev = 0.052
  CI (99.9%): [2.733, 4.616] (assumes normal distribution)


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
# Warmup Iteration   1: 4.945 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.011 ms/op
Iteration   1: 3.763 ±(99.9%) 0.003 ms/op
Iteration   2: 3.699 ±(99.9%) 0.005 ms/op
Iteration   3: 3.638 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.700 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.638, 3.700, 3.763), stdev = 0.062
  CI (99.9%): [2.565, 4.835] (assumes normal distribution)


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
# Warmup Iteration   1: 6.702 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.171 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.828 ±(99.9%) 0.014 ms/op
Iteration   1: 4.837 ±(99.9%) 0.011 ms/op
Iteration   2: 4.749 ±(99.9%) 0.013 ms/op
Iteration   3: 4.575 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.720 ±(99.9%) 2.437 ms/op [Average]
  (min, avg, max) = (4.575, 4.720, 4.837), stdev = 0.134
  CI (99.9%): [2.283, 7.158] (assumes normal distribution)


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
# Warmup Iteration   1: 5.548 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.009 ms/op
Iteration   1: 3.732 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  10.556 ms/op
                 createUser·p0.9999: 30.321 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   2: 3.704 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  8.760 ms/op
                 createUser·p0.9999: 23.751 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   3: 3.710 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 26.870 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258513
  mean =      3.715 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4464 
    [ 2.500,  5.000) = 247863 
    [ 5.000,  7.500) = 5422 
    [ 7.500, 10.000) = 508 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     28.148 ms/op
     p(99.9990) =     31.752 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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
# Warmup Iteration   1: 4.911 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.008 ms/op
Iteration   1: 3.499 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  9.174 ms/op
                 existUser·p0.9999: 14.252 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 3.471 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  7.422 ms/op
                 existUser·p0.9999: 15.672 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   3: 3.478 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  12.107 ms/op
                 existUser·p0.9999: 17.138 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275584
  mean =      3.483 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8797 
    [ 2.500,  5.000) = 262444 
    [ 5.000,  7.500) = 3824 
    [ 7.500, 10.000) = 244 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.982 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     18.006 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 5.337 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.778 ±(99.9%) 0.015 ms/op
Iteration   1: 3.894 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   7.463 ms/op
                 getUser·p0.999:  12.812 ms/op
                 getUser·p0.9999: 16.089 ms/op
                 getUser·p1.00:   16.663 ms/op

Iteration   2: 3.714 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.749 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  9.601 ms/op
                 getUser·p0.9999: 17.937 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   3: 3.711 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  8.143 ms/op
                 getUser·p0.9999: 20.767 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254437
  mean =      3.771 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9400 
    [ 2.500,  5.000) = 233126 
    [ 5.000,  7.500) = 10593 
    [ 7.500, 10.000) = 979 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     11.183 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     22.101 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 6.798 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.982 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.673 ±(99.9%) 0.012 ms/op
Iteration   1: 4.817 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   8.259 ms/op
                 listUser·p0.999:  14.377 ms/op
                 listUser·p0.9999: 18.951 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 4.731 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  15.955 ms/op
                 listUser·p0.9999: 18.530 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   3: 4.735 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   6.472 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  20.329 ms/op
                 listUser·p0.9999: 23.518 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201665
  mean =      4.761 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 276 
    [ 2.500,  5.000) = 153564 
    [ 5.000,  7.500) = 43493 
    [ 7.500, 10.000) = 3719 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.592 ms/op
     p(99.0000) =      8.244 ms/op
     p(99.9000) =     16.204 ms/op
     p(99.9900) =     22.501 ms/op
     p(99.9990) =     23.723 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.537 ± 2.331  ops/ms
ClientGrpc.existUser                       thrpt       3   9.152 ± 0.952  ops/ms
ClientGrpc.getUser                         thrpt       3   8.584 ± 1.507  ops/ms
ClientGrpc.listUser                        thrpt       3   6.768 ± 2.113  ops/ms
ClientGrpc.createUser                       avgt       3   3.634 ± 0.497   ms/op
ClientGrpc.existUser                        avgt       3   3.675 ± 0.942   ms/op
ClientGrpc.getUser                          avgt       3   3.700 ± 1.135   ms/op
ClientGrpc.listUser                         avgt       3   4.720 ± 2.437   ms/op
ClientGrpc.createUser                     sample  258513   3.715 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.762           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.732           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.148           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.785           ms/op
ClientGrpc.existUser                      sample  275584   3.483 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.820           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.022           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.464           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.982           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.777           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.447           ms/op
ClientGrpc.getUser                        sample  254437   3.771 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.749           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.956           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.463           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.183           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.218           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.151           ms/op
ClientGrpc.listUser                       sample  201665   4.761 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.192           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.592           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.244           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.204           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.501           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.888           ms/op
