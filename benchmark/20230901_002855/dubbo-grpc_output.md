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
# Warmup Iteration   1: 2.169 ops/ms
# Warmup Iteration   2: 5.288 ops/ms
# Warmup Iteration   3: 7.116 ops/ms
Iteration   1: 7.519 ops/ms
Iteration   2: 7.892 ops/ms
Iteration   3: 8.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.839 ±(99.9%) 5.411 ops/ms [Average]
  (min, avg, max) = (7.519, 7.839, 8.105), stdev = 0.297
  CI (99.9%): [2.427, 13.250] (assumes normal distribution)


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
# Warmup Iteration   1: 5.283 ops/ms
# Warmup Iteration   2: 7.782 ops/ms
# Warmup Iteration   3: 7.829 ops/ms
Iteration   1: 8.381 ops/ms
Iteration   2: 7.753 ops/ms
Iteration   3: 8.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.133 ±(99.9%) 6.097 ops/ms [Average]
  (min, avg, max) = (7.753, 8.133, 8.381), stdev = 0.334
  CI (99.9%): [2.035, 14.230] (assumes normal distribution)


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
# Warmup Iteration   1: 4.570 ops/ms
# Warmup Iteration   2: 6.977 ops/ms
# Warmup Iteration   3: 7.275 ops/ms
Iteration   1: 7.487 ops/ms
Iteration   2: 7.600 ops/ms
Iteration   3: 7.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.534 ±(99.9%) 1.068 ops/ms [Average]
  (min, avg, max) = (7.487, 7.534, 7.600), stdev = 0.059
  CI (99.9%): [6.466, 8.602] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.866 ops/ms
# Warmup Iteration   2: 5.091 ops/ms
# Warmup Iteration   3: 5.571 ops/ms
Iteration   1: 5.686 ops/ms
Iteration   2: 6.046 ops/ms
Iteration   3: 5.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.834 ±(99.9%) 3.442 ops/ms [Average]
  (min, avg, max) = (5.686, 5.834, 6.046), stdev = 0.189
  CI (99.9%): [2.392, 9.277] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.301 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.441 ±(99.9%) 0.009 ms/op
Iteration   1: 4.513 ±(99.9%) 0.002 ms/op
Iteration   2: 4.385 ±(99.9%) 0.002 ms/op
Iteration   3: 4.453 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.450 ±(99.9%) 1.171 ms/op [Average]
  (min, avg, max) = (4.385, 4.450, 4.513), stdev = 0.064
  CI (99.9%): [3.279, 5.621] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.391 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.347 ±(99.9%) 0.002 ms/op
Iteration   1: 4.012 ±(99.9%) 0.003 ms/op
Iteration   2: 4.004 ±(99.9%) 0.003 ms/op
Iteration   3: 3.830 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.949 ±(99.9%) 1.885 ms/op [Average]
  (min, avg, max) = (3.830, 3.949, 4.012), stdev = 0.103
  CI (99.9%): [2.063, 5.834] (assumes normal distribution)


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
# Warmup Iteration   1: 6.179 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.473 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.007 ms/op
Iteration   1: 4.309 ±(99.9%) 0.007 ms/op
Iteration   2: 4.265 ±(99.9%) 0.003 ms/op
Iteration   3: 4.190 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.255 ±(99.9%) 1.093 ms/op [Average]
  (min, avg, max) = (4.190, 4.255, 4.309), stdev = 0.060
  CI (99.9%): [3.161, 5.348] (assumes normal distribution)


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
# Warmup Iteration   1: 7.917 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 6.350 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.573 ±(99.9%) 0.013 ms/op
Iteration   1: 5.464 ±(99.9%) 0.020 ms/op
Iteration   2: 5.748 ±(99.9%) 0.031 ms/op
Iteration   3: 5.833 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.682 ±(99.9%) 3.525 ms/op [Average]
  (min, avg, max) = (5.464, 5.682, 5.833), stdev = 0.193
  CI (99.9%): [2.157, 9.207] (assumes normal distribution)


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
# Warmup Iteration   1: 7.692 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.328 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.022 ±(99.9%) 0.023 ms/op
Iteration   1: 4.654 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   6.111 ms/op
                 createUser·p0.95:   7.414 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  14.762 ms/op
                 createUser·p0.9999: 22.328 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   2: 4.499 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.857 ms/op
                 createUser·p0.95:   6.636 ms/op
                 createUser·p0.99:   9.781 ms/op
                 createUser·p0.999:  15.799 ms/op
                 createUser·p0.9999: 26.965 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   3: 4.533 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.424 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.759 ms/op
                 createUser·p0.95:   6.586 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  17.560 ms/op
                 createUser·p0.9999: 28.996 ms/op
                 createUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 210336
  mean =      4.561 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8182 
    [ 2.500,  5.000) = 150814 
    [ 5.000,  7.500) = 43345 
    [ 7.500, 10.000) = 5836 
    [10.000, 12.500) = 1531 
    [12.500, 15.000) = 365 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.898 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     29.164 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 6.506 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.715 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.405 ±(99.9%) 0.017 ms/op
Iteration   1: 4.463 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   5.816 ms/op
                 existUser·p0.95:   6.767 ms/op
                 existUser·p0.99:   9.659 ms/op
                 existUser·p0.999:  14.189 ms/op
                 existUser·p0.9999: 20.993 ms/op
                 existUser·p1.00:   21.660 ms/op

Iteration   2: 4.529 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   4.252 ms/op
                 existUser·p0.90:   6.021 ms/op
                 existUser·p0.95:   7.627 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  15.619 ms/op
                 existUser·p0.9999: 22.767 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   3: 4.474 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   6.013 ms/op
                 existUser·p0.95:   7.234 ms/op
                 existUser·p0.99:   9.732 ms/op
                 existUser·p0.999:  13.590 ms/op
                 existUser·p0.9999: 24.107 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 213932
  mean =      4.489 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9585 
    [ 2.500,  5.000) = 154782 
    [ 5.000,  7.500) = 40287 
    [ 7.500, 10.000) = 7355 
    [10.000, 12.500) = 1426 
    [12.500, 15.000) = 317 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      7.176 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     14.258 ms/op
     p(99.9900) =     23.502 ms/op
     p(99.9990) =     26.533 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 6.753 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.659 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.568 ±(99.9%) 0.015 ms/op
Iteration   1: 4.436 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.562 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.791 ms/op
                 getUser·p0.999:  11.333 ms/op
                 getUser·p0.9999: 20.473 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   2: 4.382 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   5.775 ms/op
                 getUser·p0.99:   7.407 ms/op
                 getUser·p0.999:  15.287 ms/op
                 getUser·p0.9999: 18.340 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   3: 4.516 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.579 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   8.036 ms/op
                 getUser·p0.999:  12.455 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215928
  mean =      4.444 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4626 
    [ 2.500,  5.000) = 164144 
    [ 5.000,  7.500) = 44636 
    [ 7.500, 10.000) = 1861 
    [10.000, 12.500) = 416 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     20.343 ms/op
     p(99.9990) =     21.800 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 8.483 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 6.392 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.868 ±(99.9%) 0.022 ms/op
Iteration   1: 5.764 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  18.790 ms/op
                 listUser·p0.9999: 23.309 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   2: 5.837 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   7.668 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  26.150 ms/op
                 listUser·p0.9999: 33.720 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   3: 5.818 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.521 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.241 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  24.485 ms/op
                 listUser·p0.9999: 33.784 ms/op
                 listUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165313
  mean =      5.806 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 132 
    [ 2.500,  5.000) = 43164 
    [ 5.000,  7.500) = 104913 
    [ 7.500, 10.000) = 14501 
    [10.000, 12.500) = 1959 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 58 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      7.545 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     34.682 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.839 ± 5.411  ops/ms
ClientGrpc.existUser                       thrpt       3   8.133 ± 6.097  ops/ms
ClientGrpc.getUser                         thrpt       3   7.534 ± 1.068  ops/ms
ClientGrpc.listUser                        thrpt       3   5.834 ± 3.442  ops/ms
ClientGrpc.createUser                       avgt       3   4.450 ± 1.171   ms/op
ClientGrpc.existUser                        avgt       3   3.949 ± 1.885   ms/op
ClientGrpc.getUser                          avgt       3   4.255 ± 1.093   ms/op
ClientGrpc.listUser                         avgt       3   5.682 ± 3.525   ms/op
ClientGrpc.createUser                     sample  210336   4.561 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.424           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.898           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.873           ms/op
ClientGrpc.createUser:createUser·p0.99    sample          10.043           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.302           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.705           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.229           ms/op
ClientGrpc.existUser                      sample  213932   4.489 ± 0.011   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.690           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.947           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           7.176           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.847           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.258           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.502           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.673           ms/op
ClientGrpc.getUser                        sample  215928   4.444 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.096           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.939           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.766           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.780           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.343           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  165313   5.806 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.521           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.438           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.715           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.184           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.620           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.324           ms/op
