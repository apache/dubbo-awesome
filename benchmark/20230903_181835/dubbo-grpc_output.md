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
# Warmup Iteration   1: 3.226 ops/ms
# Warmup Iteration   2: 6.759 ops/ms
# Warmup Iteration   3: 7.771 ops/ms
Iteration   1: 8.669 ops/ms
Iteration   2: 8.587 ops/ms
Iteration   3: 8.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.692 ±(99.9%) 2.135 ops/ms [Average]
  (min, avg, max) = (8.587, 8.692, 8.818), stdev = 0.117
  CI (99.9%): [6.556, 10.827] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.221 ops/ms
# Warmup Iteration   2: 8.550 ops/ms
# Warmup Iteration   3: 9.348 ops/ms
Iteration   1: 9.384 ops/ms
Iteration   2: 9.198 ops/ms
Iteration   3: 9.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.227 ±(99.9%) 2.634 ops/ms [Average]
  (min, avg, max) = (9.100, 9.227, 9.384), stdev = 0.144
  CI (99.9%): [6.593, 11.862] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.497 ops/ms
# Warmup Iteration   2: 8.570 ops/ms
# Warmup Iteration   3: 9.091 ops/ms
Iteration   1: 8.707 ops/ms
Iteration   2: 8.786 ops/ms
Iteration   3: 8.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.735 ±(99.9%) 0.818 ops/ms [Average]
  (min, avg, max) = (8.707, 8.735, 8.786), stdev = 0.045
  CI (99.9%): [7.916, 9.553] (assumes normal distribution)


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
# Warmup Iteration   1: 4.716 ops/ms
# Warmup Iteration   2: 6.372 ops/ms
# Warmup Iteration   3: 6.752 ops/ms
Iteration   1: 6.741 ops/ms
Iteration   2: 6.521 ops/ms
Iteration   3: 6.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.661 ±(99.9%) 2.214 ops/ms [Average]
  (min, avg, max) = (6.521, 6.661, 6.741), stdev = 0.121
  CI (99.9%): [4.446, 8.875] (assumes normal distribution)


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
# Warmup Iteration   1: 5.227 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.006 ms/op
Iteration   1: 3.708 ±(99.9%) 0.004 ms/op
Iteration   2: 3.694 ±(99.9%) 0.002 ms/op
Iteration   3: 3.736 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.712 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (3.694, 3.712, 3.736), stdev = 0.021
  CI (99.9%): [3.322, 4.103] (assumes normal distribution)


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
# Warmup Iteration   1: 4.977 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.004 ms/op
Iteration   1: 3.496 ±(99.9%) 0.002 ms/op
Iteration   2: 3.406 ±(99.9%) 0.004 ms/op
Iteration   3: 3.417 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.440 ±(99.9%) 0.895 ms/op [Average]
  (min, avg, max) = (3.406, 3.440, 3.496), stdev = 0.049
  CI (99.9%): [2.544, 4.335] (assumes normal distribution)


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
# Warmup Iteration   1: 4.840 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.003 ms/op
Iteration   1: 3.708 ±(99.9%) 0.003 ms/op
Iteration   2: 3.606 ±(99.9%) 0.004 ms/op
Iteration   3: 3.668 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.660 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (3.606, 3.660, 3.708), stdev = 0.051
  CI (99.9%): [2.724, 4.596] (assumes normal distribution)


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
# Warmup Iteration   1: 7.145 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.052 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.776 ±(99.9%) 0.025 ms/op
Iteration   1: 4.739 ±(99.9%) 0.015 ms/op
Iteration   2: 4.769 ±(99.9%) 0.012 ms/op
Iteration   3: 4.585 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.698 ±(99.9%) 1.798 ms/op [Average]
  (min, avg, max) = (4.585, 4.698, 4.769), stdev = 0.099
  CI (99.9%): [2.900, 6.495] (assumes normal distribution)


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
# Warmup Iteration   1: 5.210 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.010 ms/op
Iteration   1: 3.617 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  11.485 ms/op
                 createUser·p0.9999: 23.182 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.606 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  13.129 ms/op
                 createUser·p0.9999: 17.334 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   3: 3.629 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  13.968 ms/op
                 createUser·p0.9999: 19.235 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265290
  mean =      3.617 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12439 
    [ 2.500,  5.000) = 245121 
    [ 5.000,  7.500) = 6469 
    [ 7.500, 10.000) = 725 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     12.241 ms/op
     p(99.9900) =     21.527 ms/op
     p(99.9990) =     23.671 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 5.038 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.008 ms/op
Iteration   1: 3.533 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.003 ms/op
                 existUser·p0.999:  9.837 ms/op
                 existUser·p0.9999: 21.918 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   2: 3.451 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.641 ms/op
                 existUser·p0.999:  12.895 ms/op
                 existUser·p0.9999: 30.474 ms/op
                 existUser·p1.00:   33.620 ms/op

Iteration   3: 3.475 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  8.829 ms/op
                 existUser·p0.9999: 19.333 ms/op
                 existUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275381
  mean =      3.486 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7653 
    [ 2.500,  5.000) = 262784 
    [ 5.000,  7.500) = 4105 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.546 ms/op
     p(99.9900) =     30.129 ms/op
     p(99.9990) =     31.341 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 5.206 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.010 ms/op
Iteration   1: 3.730 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  10.940 ms/op
                 getUser·p0.9999: 23.391 ms/op
                 getUser·p1.00:   23.658 ms/op

Iteration   2: 3.679 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.333 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  8.716 ms/op
                 getUser·p0.9999: 17.191 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   3: 3.577 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.187 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 19.040 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262129
  mean =      3.661 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7292 
    [ 2.500,  5.000) = 247541 
    [ 5.000,  7.500) = 6398 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     22.767 ms/op
     p(99.9990) =     23.605 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 7.074 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.875 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.936 ±(99.9%) 0.016 ms/op
Iteration   1: 4.710 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   6.980 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  20.352 ms/op
                 listUser·p0.9999: 23.974 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   2: 4.679 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   8.615 ms/op
                 listUser·p0.999:  15.329 ms/op
                 listUser·p0.9999: 32.014 ms/op
                 listUser·p1.00:   32.473 ms/op

Iteration   3: 4.861 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.332 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  19.071 ms/op
                 listUser·p0.9999: 22.722 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202113
  mean =      4.748 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 693 
    [ 2.500,  5.000) = 148091 
    [ 5.000,  7.500) = 46317 
    [ 7.500, 10.000) = 6060 
    [10.000, 12.500) = 516 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      6.201 ms/op
     p(95.0000) =      7.070 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     19.067 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     32.404 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.692 ± 2.135  ops/ms
ClientGrpc.existUser                       thrpt       3   9.227 ± 2.634  ops/ms
ClientGrpc.getUser                         thrpt       3   8.735 ± 0.818  ops/ms
ClientGrpc.listUser                        thrpt       3   6.661 ± 2.214  ops/ms
ClientGrpc.createUser                       avgt       3   3.712 ± 0.390   ms/op
ClientGrpc.existUser                        avgt       3   3.440 ± 0.895   ms/op
ClientGrpc.getUser                          avgt       3   3.660 ± 0.936   ms/op
ClientGrpc.listUser                         avgt       3   4.698 ± 1.798   ms/op
ClientGrpc.createUser                     sample  265290   3.617 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.813           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.029           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.241           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.527           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.757           ms/op
ClientGrpc.existUser                      sample  275381   3.486 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.742           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.595           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.546           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.129           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.620           ms/op
ClientGrpc.getUser                        sample  262129   3.661 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.931           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.882           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.634           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.767           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.658           ms/op
ClientGrpc.listUser                       sample  202113   4.748 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.859           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.201           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.880           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.067           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.130           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.473           ms/op
