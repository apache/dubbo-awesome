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
# Warmup Iteration   1: 3.152 ops/ms
# Warmup Iteration   2: 6.856 ops/ms
# Warmup Iteration   3: 8.134 ops/ms
Iteration   1: 8.487 ops/ms
Iteration   2: 8.547 ops/ms
Iteration   3: 8.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.575 ±(99.9%) 1.908 ops/ms [Average]
  (min, avg, max) = (8.487, 8.575, 8.690), stdev = 0.105
  CI (99.9%): [6.667, 10.482] (assumes normal distribution)


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
# Warmup Iteration   1: 6.154 ops/ms
# Warmup Iteration   2: 8.616 ops/ms
# Warmup Iteration   3: 8.944 ops/ms
Iteration   1: 8.979 ops/ms
Iteration   2: 9.000 ops/ms
Iteration   3: 9.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.062 ±(99.9%) 2.284 ops/ms [Average]
  (min, avg, max) = (8.979, 9.062, 9.206), stdev = 0.125
  CI (99.9%): [6.778, 11.345] (assumes normal distribution)


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
# Warmup Iteration   1: 5.449 ops/ms
# Warmup Iteration   2: 8.287 ops/ms
# Warmup Iteration   3: 8.680 ops/ms
Iteration   1: 8.728 ops/ms
Iteration   2: 8.970 ops/ms
Iteration   3: 8.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.858 ±(99.9%) 2.224 ops/ms [Average]
  (min, avg, max) = (8.728, 8.858, 8.970), stdev = 0.122
  CI (99.9%): [6.635, 11.082] (assumes normal distribution)


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
# Warmup Iteration   1: 4.171 ops/ms
# Warmup Iteration   2: 6.117 ops/ms
# Warmup Iteration   3: 6.670 ops/ms
Iteration   1: 6.617 ops/ms
Iteration   2: 6.702 ops/ms
Iteration   3: 6.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.680 ±(99.9%) 1.008 ops/ms [Average]
  (min, avg, max) = (6.617, 6.680, 6.721), stdev = 0.055
  CI (99.9%): [5.672, 7.688] (assumes normal distribution)


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
# Warmup Iteration   1: 5.456 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.005 ms/op
Iteration   1: 3.628 ±(99.9%) 0.002 ms/op
Iteration   2: 3.613 ±(99.9%) 0.002 ms/op
Iteration   3: 3.797 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.679 ±(99.9%) 1.869 ms/op [Average]
  (min, avg, max) = (3.613, 3.679, 3.797), stdev = 0.102
  CI (99.9%): [1.810, 5.548] (assumes normal distribution)


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
# Warmup Iteration   1: 4.881 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.004 ms/op
Iteration   1: 3.614 ±(99.9%) 0.006 ms/op
Iteration   2: 3.505 ±(99.9%) 0.003 ms/op
Iteration   3: 3.557 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.559 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (3.505, 3.559, 3.614), stdev = 0.054
  CI (99.9%): [2.565, 4.553] (assumes normal distribution)


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
# Warmup Iteration   1: 5.176 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.652 ±(99.9%) 0.003 ms/op
Iteration   1: 3.720 ±(99.9%) 0.004 ms/op
Iteration   2: 3.755 ±(99.9%) 0.003 ms/op
Iteration   3: 3.616 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.697 ±(99.9%) 1.322 ms/op [Average]
  (min, avg, max) = (3.616, 3.697, 3.755), stdev = 0.072
  CI (99.9%): [2.375, 5.018] (assumes normal distribution)


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
# Warmup Iteration   1: 5.413 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.775 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.626 ±(99.9%) 0.031 ms/op
Iteration   1: 4.554 ±(99.9%) 0.018 ms/op
Iteration   2: 4.514 ±(99.9%) 0.020 ms/op
Iteration   3: 4.630 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.566 ±(99.9%) 1.076 ms/op [Average]
  (min, avg, max) = (4.514, 4.566, 4.630), stdev = 0.059
  CI (99.9%): [3.490, 5.642] (assumes normal distribution)


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
# Warmup Iteration   1: 5.580 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.011 ms/op
Iteration   1: 3.936 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  13.753 ms/op
                 createUser·p0.9999: 14.924 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   2: 3.751 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  11.642 ms/op
                 createUser·p0.9999: 18.151 ms/op
                 createUser·p1.00:   19.562 ms/op

Iteration   3: 3.753 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  16.068 ms/op
                 createUser·p0.9999: 21.789 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251982
  mean =      3.811 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4019 
    [ 2.500,  5.000) = 236138 
    [ 5.000,  7.500) = 10432 
    [ 7.500, 10.000) = 843 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     12.681 ms/op
     p(99.9900) =     20.664 ms/op
     p(99.9990) =     22.150 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 4.606 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.008 ms/op
Iteration   1: 3.599 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  9.456 ms/op
                 existUser·p0.9999: 14.533 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 3.532 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 20.477 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   3: 3.488 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  9.382 ms/op
                 existUser·p0.9999: 21.141 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271009
  mean =      3.539 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6247 
    [ 2.500,  5.000) = 259453 
    [ 5.000,  7.500) = 4469 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     10.010 ms/op
     p(99.9900) =     20.706 ms/op
     p(99.9990) =     21.341 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 5.492 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.008 ms/op
Iteration   1: 3.764 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  10.098 ms/op
                 getUser·p0.9999: 14.934 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   2: 3.739 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   5.995 ms/op
                 getUser·p0.999:  9.199 ms/op
                 getUser·p0.9999: 16.908 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 3.679 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  8.454 ms/op
                 getUser·p0.9999: 19.376 ms/op
                 getUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257417
  mean =      3.727 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 2498 
    [ 2.500,  3.750) = 144654 
    [ 3.750,  5.000) = 103875 
    [ 5.000,  6.250) = 4412 
    [ 6.250,  7.500) = 1043 
    [ 7.500,  8.750) = 568 
    [ 8.750, 10.000) = 123 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 77 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     17.113 ms/op
     p(99.9990) =     19.590 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 6.251 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.080 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.650 ±(99.9%) 0.014 ms/op
Iteration   1: 4.544 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 17.530 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   2: 4.614 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.689 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 19.007 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 4.571 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.603 ms/op
                 listUser·p0.95:   6.504 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  20.972 ms/op
                 listUser·p0.9999: 28.803 ms/op
                 listUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 209751
  mean =      4.576 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 433 
    [ 2.500,  5.000) = 174448 
    [ 5.000,  7.500) = 31160 
    [ 7.500, 10.000) = 3091 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      6.414 ms/op
     p(99.0000) =      8.061 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     28.116 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.575 ± 1.908  ops/ms
ClientGrpc.existUser                       thrpt       3   9.062 ± 2.284  ops/ms
ClientGrpc.getUser                         thrpt       3   8.858 ± 2.224  ops/ms
ClientGrpc.listUser                        thrpt       3   6.680 ± 1.008  ops/ms
ClientGrpc.createUser                       avgt       3   3.679 ± 1.869   ms/op
ClientGrpc.existUser                        avgt       3   3.559 ± 0.994   ms/op
ClientGrpc.getUser                          avgt       3   3.697 ± 1.322   ms/op
ClientGrpc.listUser                         avgt       3   4.566 ± 1.076   ms/op
ClientGrpc.createUser                     sample  251982   3.811 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.608           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.956           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.562           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.681           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.664           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.249           ms/op
ClientGrpc.existUser                      sample  271009   3.539 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.756           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.751           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.010           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.706           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.430           ms/op
ClientGrpc.getUser                        sample  257417   3.727 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.754           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.849           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.191           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.113           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.694           ms/op
ClientGrpc.listUser                       sample  209751   4.576 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.689           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.424           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.414           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.061           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.072           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.116           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.376           ms/op
