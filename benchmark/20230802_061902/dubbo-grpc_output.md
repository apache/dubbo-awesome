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
# Warmup Iteration   1: 3.142 ops/ms
# Warmup Iteration   2: 6.945 ops/ms
# Warmup Iteration   3: 7.941 ops/ms
Iteration   1: 8.723 ops/ms
Iteration   2: 8.909 ops/ms
Iteration   3: 8.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.766 ±(99.9%) 2.328 ops/ms [Average]
  (min, avg, max) = (8.665, 8.766, 8.909), stdev = 0.128
  CI (99.9%): [6.438, 11.094] (assumes normal distribution)


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
# Warmup Iteration   1: 6.180 ops/ms
# Warmup Iteration   2: 8.706 ops/ms
# Warmup Iteration   3: 9.295 ops/ms
Iteration   1: 9.392 ops/ms
Iteration   2: 9.213 ops/ms
Iteration   3: 9.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.266 ±(99.9%) 1.998 ops/ms [Average]
  (min, avg, max) = (9.193, 9.266, 9.392), stdev = 0.110
  CI (99.9%): [7.268, 11.264] (assumes normal distribution)


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
# Warmup Iteration   1: 5.711 ops/ms
# Warmup Iteration   2: 8.495 ops/ms
# Warmup Iteration   3: 8.560 ops/ms
Iteration   1: 8.646 ops/ms
Iteration   2: 8.763 ops/ms
Iteration   3: 9.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.805 ±(99.9%) 3.335 ops/ms [Average]
  (min, avg, max) = (8.646, 8.805, 9.005), stdev = 0.183
  CI (99.9%): [5.469, 12.140] (assumes normal distribution)


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
# Warmup Iteration   1: 4.490 ops/ms
# Warmup Iteration   2: 6.188 ops/ms
# Warmup Iteration   3: 6.619 ops/ms
Iteration   1: 6.515 ops/ms
Iteration   2: 6.576 ops/ms
Iteration   3: 6.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.605 ±(99.9%) 1.979 ops/ms [Average]
  (min, avg, max) = (6.515, 6.605, 6.726), stdev = 0.108
  CI (99.9%): [4.626, 8.585] (assumes normal distribution)


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
# Warmup Iteration   1: 5.206 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.003 ms/op
Iteration   1: 3.729 ±(99.9%) 0.003 ms/op
Iteration   2: 3.667 ±(99.9%) 0.004 ms/op
Iteration   3: 3.774 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.723 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (3.667, 3.723, 3.774), stdev = 0.054
  CI (99.9%): [2.744, 4.702] (assumes normal distribution)


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
# Warmup Iteration   1: 4.968 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.002 ms/op
Iteration   1: 3.442 ±(99.9%) 0.003 ms/op
Iteration   2: 3.436 ±(99.9%) 0.004 ms/op
Iteration   3: 3.561 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.480 ±(99.9%) 1.279 ms/op [Average]
  (min, avg, max) = (3.436, 3.480, 3.561), stdev = 0.070
  CI (99.9%): [2.200, 4.759] (assumes normal distribution)


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
# Warmup Iteration   1: 5.466 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.003 ms/op
Iteration   1: 3.815 ±(99.9%) 0.004 ms/op
Iteration   2: 3.626 ±(99.9%) 0.004 ms/op
Iteration   3: 3.664 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.702 ±(99.9%) 1.826 ms/op [Average]
  (min, avg, max) = (3.626, 3.702, 3.815), stdev = 0.100
  CI (99.9%): [1.876, 5.527] (assumes normal distribution)


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
# Warmup Iteration   1: 6.671 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.075 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.930 ±(99.9%) 0.014 ms/op
Iteration   1: 4.794 ±(99.9%) 0.010 ms/op
Iteration   2: 4.891 ±(99.9%) 0.018 ms/op
Iteration   3: 4.987 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.891 ±(99.9%) 1.753 ms/op [Average]
  (min, avg, max) = (4.794, 4.891, 4.987), stdev = 0.096
  CI (99.9%): [3.138, 6.643] (assumes normal distribution)


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
# Warmup Iteration   1: 5.434 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
Iteration   1: 3.616 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  11.190 ms/op
                 createUser·p0.9999: 16.605 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 3.690 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.649 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  11.180 ms/op
                 createUser·p0.9999: 18.896 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   3: 3.836 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  13.582 ms/op
                 createUser·p0.9999: 23.320 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258476
  mean =      3.712 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7185 
    [ 2.500,  5.000) = 241421 
    [ 5.000,  7.500) = 8081 
    [ 7.500, 10.000) = 1219 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     12.641 ms/op
     p(99.9900) =     22.817 ms/op
     p(99.9990) =     25.015 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 5.242 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.008 ms/op
Iteration   1: 3.573 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 22.159 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.484 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  9.719 ms/op
                 existUser·p0.9999: 16.673 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   3: 3.462 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  13.101 ms/op
                 existUser·p0.9999: 23.225 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273651
  mean =      3.506 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11840 
    [ 2.500,  5.000) = 254128 
    [ 5.000,  7.500) = 6468 
    [ 7.500, 10.000) = 817 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     10.940 ms/op
     p(99.9900) =     22.082 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 5.193 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.010 ms/op
Iteration   1: 3.559 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.465 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  10.324 ms/op
                 getUser·p0.9999: 16.057 ms/op
                 getUser·p1.00:   16.548 ms/op

Iteration   2: 3.614 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  10.357 ms/op
                 getUser·p0.9999: 18.944 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   3: 3.623 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.417 ms/op
                 getUser·p0.999:  10.430 ms/op
                 getUser·p0.9999: 19.044 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 266861
  mean =      3.599 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16626 
    [ 2.500,  5.000) = 239659 
    [ 5.000,  7.500) = 9183 
    [ 7.500, 10.000) = 1042 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     10.387 ms/op
     p(99.9900) =     18.819 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 6.366 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.220 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.813 ±(99.9%) 0.017 ms/op
Iteration   1: 4.669 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  16.166 ms/op
                 listUser·p0.9999: 24.488 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   2: 4.780 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   6.693 ms/op
                 listUser·p0.95:   7.537 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  18.727 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 4.797 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.259 ms/op
                 listUser·p0.95:   7.250 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  21.785 ms/op
                 listUser·p0.9999: 33.903 ms/op
                 listUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202161
  mean =      4.748 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 756 
    [ 2.500,  5.000) = 147929 
    [ 5.000,  7.500) = 44848 
    [ 7.500, 10.000) = 7133 
    [10.000, 12.500) = 906 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =      9.460 ms/op
     p(99.9000) =     18.886 ms/op
     p(99.9900) =     31.916 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.766 ± 2.328  ops/ms
ClientGrpc.existUser                       thrpt       3   9.266 ± 1.998  ops/ms
ClientGrpc.getUser                         thrpt       3   8.805 ± 3.335  ops/ms
ClientGrpc.listUser                        thrpt       3   6.605 ± 1.979  ops/ms
ClientGrpc.createUser                       avgt       3   3.723 ± 0.979   ms/op
ClientGrpc.existUser                        avgt       3   3.480 ± 1.279   ms/op
ClientGrpc.getUser                          avgt       3   3.702 ± 1.826   ms/op
ClientGrpc.listUser                         avgt       3   4.891 ± 1.753   ms/op
ClientGrpc.createUser                     sample  258476   3.712 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.669           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.636           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.641           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.817           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.378           ms/op
ClientGrpc.existUser                      sample  273651   3.506 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.565           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.193           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.940           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.082           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.691           ms/op
ClientGrpc.getUser                        sample  266861   3.599 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.465           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.275           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.387           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.819           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.070           ms/op
ClientGrpc.listUser                       sample  202161   4.748 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.414           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.340           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.460           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.886           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.916           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.537           ms/op
