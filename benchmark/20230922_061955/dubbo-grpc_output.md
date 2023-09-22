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
# Warmup Iteration   1: 3.312 ops/ms
# Warmup Iteration   2: 6.679 ops/ms
# Warmup Iteration   3: 8.041 ops/ms
Iteration   1: 8.452 ops/ms
Iteration   2: 8.466 ops/ms
Iteration   3: 8.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.495 ±(99.9%) 1.169 ops/ms [Average]
  (min, avg, max) = (8.452, 8.495, 8.569), stdev = 0.064
  CI (99.9%): [7.327, 9.664] (assumes normal distribution)


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
# Warmup Iteration   1: 5.916 ops/ms
# Warmup Iteration   2: 8.567 ops/ms
# Warmup Iteration   3: 8.799 ops/ms
Iteration   1: 9.002 ops/ms
Iteration   2: 9.014 ops/ms
Iteration   3: 9.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.056 ±(99.9%) 1.513 ops/ms [Average]
  (min, avg, max) = (9.002, 9.056, 9.151), stdev = 0.083
  CI (99.9%): [7.542, 10.569] (assumes normal distribution)


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
# Warmup Iteration   1: 5.313 ops/ms
# Warmup Iteration   2: 8.233 ops/ms
# Warmup Iteration   3: 8.434 ops/ms
Iteration   1: 8.335 ops/ms
Iteration   2: 8.460 ops/ms
Iteration   3: 8.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.414 ±(99.9%) 1.263 ops/ms [Average]
  (min, avg, max) = (8.335, 8.414, 8.460), stdev = 0.069
  CI (99.9%): [7.151, 9.677] (assumes normal distribution)


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
# Warmup Iteration   1: 4.532 ops/ms
# Warmup Iteration   2: 6.401 ops/ms
# Warmup Iteration   3: 6.828 ops/ms
Iteration   1: 6.904 ops/ms
Iteration   2: 6.826 ops/ms
Iteration   3: 6.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.804 ±(99.9%) 2.039 ops/ms [Average]
  (min, avg, max) = (6.683, 6.804, 6.904), stdev = 0.112
  CI (99.9%): [4.766, 8.843] (assumes normal distribution)


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
# Warmup Iteration   1: 5.615 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.006 ms/op
Iteration   1: 3.622 ±(99.9%) 0.004 ms/op
Iteration   2: 3.644 ±(99.9%) 0.002 ms/op
Iteration   3: 3.779 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.682 ±(99.9%) 1.548 ms/op [Average]
  (min, avg, max) = (3.622, 3.682, 3.779), stdev = 0.085
  CI (99.9%): [2.134, 5.230] (assumes normal distribution)


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.002 ms/op
Iteration   1: 3.549 ±(99.9%) 0.003 ms/op
Iteration   2: 3.579 ±(99.9%) 0.003 ms/op
Iteration   3: 3.572 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.567 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (3.549, 3.567, 3.579), stdev = 0.016
  CI (99.9%): [3.282, 3.852] (assumes normal distribution)


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
# Warmup Iteration   1: 5.248 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.003 ms/op
Iteration   1: 3.719 ±(99.9%) 0.004 ms/op
Iteration   2: 3.709 ±(99.9%) 0.003 ms/op
Iteration   3: 3.727 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.718 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (3.709, 3.718, 3.727), stdev = 0.009
  CI (99.9%): [3.553, 3.883] (assumes normal distribution)


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
# Warmup Iteration   1: 6.764 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.828 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.707 ±(99.9%) 0.018 ms/op
Iteration   1: 4.713 ±(99.9%) 0.010 ms/op
Iteration   2: 4.572 ±(99.9%) 0.011 ms/op
Iteration   3: 4.641 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.642 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (4.572, 4.642, 4.713), stdev = 0.070
  CI (99.9%): [3.356, 5.927] (assumes normal distribution)


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
# Warmup Iteration   1: 5.114 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.009 ms/op
Iteration   1: 3.851 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 20.034 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 3.689 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 19.606 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   3: 3.801 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.209 ms/op
                 createUser·p0.999:  13.346 ms/op
                 createUser·p0.9999: 23.200 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253988
  mean =      3.779 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2272 
    [ 2.500,  5.000) = 244750 
    [ 5.000,  7.500) = 5821 
    [ 7.500, 10.000) = 873 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     10.273 ms/op
     p(99.9900) =     22.158 ms/op
     p(99.9990) =     23.295 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 5.107 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.009 ms/op
Iteration   1: 3.609 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  9.306 ms/op
                 existUser·p0.9999: 14.975 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   2: 3.545 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  11.580 ms/op
                 existUser·p0.9999: 16.038 ms/op
                 existUser·p1.00:   16.400 ms/op

Iteration   3: 3.564 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  9.131 ms/op
                 existUser·p0.9999: 20.054 ms/op
                 existUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268469
  mean =      3.572 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6236 
    [ 2.500,  5.000) = 256207 
    [ 5.000,  7.500) = 4736 
    [ 7.500, 10.000) = 1075 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =      9.446 ms/op
     p(99.9900) =     18.229 ms/op
     p(99.9990) =     20.261 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 5.731 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.009 ms/op
Iteration   1: 3.835 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  13.313 ms/op
                 getUser·p0.9999: 19.366 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   2: 3.747 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  10.808 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   3: 3.804 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  9.060 ms/op
                 getUser·p0.9999: 25.526 ms/op
                 getUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252973
  mean =      3.795 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5592 
    [ 2.500,  5.000) = 239478 
    [ 5.000,  7.500) = 6831 
    [ 7.500, 10.000) = 733 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     10.879 ms/op
     p(99.9900) =     23.941 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 6.305 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.044 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.776 ±(99.9%) 0.014 ms/op
Iteration   1: 4.750 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.504 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  14.806 ms/op
                 listUser·p0.9999: 18.089 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   2: 4.764 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  15.672 ms/op
                 listUser·p0.9999: 19.615 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 4.795 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  19.442 ms/op
                 listUser·p0.9999: 21.911 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201325
  mean =      4.770 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 203 
    [ 2.500,  5.000) = 153033 
    [ 5.000,  7.500) = 41285 
    [ 7.500, 10.000) = 5881 
    [10.000, 12.500) = 511 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     15.625 ms/op
     p(99.9900) =     21.323 ms/op
     p(99.9990) =     22.183 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.495 ± 1.169  ops/ms
ClientGrpc.existUser                       thrpt       3   9.056 ± 1.513  ops/ms
ClientGrpc.getUser                         thrpt       3   8.414 ± 1.263  ops/ms
ClientGrpc.listUser                        thrpt       3   6.804 ± 2.039  ops/ms
ClientGrpc.createUser                       avgt       3   3.682 ± 1.548   ms/op
ClientGrpc.existUser                        avgt       3   3.567 ± 0.285   ms/op
ClientGrpc.getUser                          avgt       3   3.718 ± 0.165   ms/op
ClientGrpc.listUser                         avgt       3   4.642 ± 1.285   ms/op
ClientGrpc.createUser                     sample  253988   3.779 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.681           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.177           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.273           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.158           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.364           ms/op
ClientGrpc.existUser                      sample  268469   3.572 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.794           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.365           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.446           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.229           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.382           ms/op
ClientGrpc.getUser                        sample  252973   3.795 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.541           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.046           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.879           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.941           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.559           ms/op
ClientGrpc.listUser                       sample  201325   4.770 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.968           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.667           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.625           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.323           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.315           ms/op
