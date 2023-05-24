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
# Warmup Iteration   1: 4.548 ops/ms
# Warmup Iteration   2: 9.270 ops/ms
# Warmup Iteration   3: 10.331 ops/ms
Iteration   1: 10.315 ops/ms
Iteration   2: 11.082 ops/ms
Iteration   3: 10.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.722 ±(99.9%) 7.029 ops/ms [Average]
  (min, avg, max) = (10.315, 10.722, 11.082), stdev = 0.385
  CI (99.9%): [3.693, 17.750] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.037 ops/ms
# Warmup Iteration   2: 10.358 ops/ms
# Warmup Iteration   3: 11.106 ops/ms
Iteration   1: 11.083 ops/ms
Iteration   2: 11.264 ops/ms
Iteration   3: 11.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.152 ±(99.9%) 1.793 ops/ms [Average]
  (min, avg, max) = (11.083, 11.152, 11.264), stdev = 0.098
  CI (99.9%): [9.358, 12.945] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.057 ops/ms
# Warmup Iteration   2: 10.265 ops/ms
# Warmup Iteration   3: 10.635 ops/ms
Iteration   1: 10.758 ops/ms
Iteration   2: 10.818 ops/ms
Iteration   3: 10.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.722 ±(99.9%) 2.152 ops/ms [Average]
  (min, avg, max) = (10.591, 10.722, 10.818), stdev = 0.118
  CI (99.9%): [8.570, 12.875] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.448 ops/ms
# Warmup Iteration   2: 7.749 ops/ms
# Warmup Iteration   3: 8.031 ops/ms
Iteration   1: 8.058 ops/ms
Iteration   2: 8.357 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.131 ±(99.9%) 3.658 ops/ms [Average]
  (min, avg, max) = (7.977, 8.131, 8.357), stdev = 0.201
  CI (99.9%): [4.472, 11.789] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.002 ms/op
Iteration   1: 2.996 ±(99.9%) 0.004 ms/op
Iteration   2: 2.970 ±(99.9%) 0.002 ms/op
Iteration   3: 2.935 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.967 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (2.935, 2.967, 2.996), stdev = 0.031
  CI (99.9%): [2.409, 3.524] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.629 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.002 ms/op
Iteration   1: 2.887 ±(99.9%) 0.002 ms/op
Iteration   2: 2.842 ±(99.9%) 0.002 ms/op
Iteration   3: 2.833 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.854 ±(99.9%) 0.526 ms/op [Average]
  (min, avg, max) = (2.833, 2.854, 2.887), stdev = 0.029
  CI (99.9%): [2.328, 3.380] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.204 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.003 ms/op
Iteration   1: 3.014 ±(99.9%) 0.002 ms/op
Iteration   2: 3.045 ±(99.9%) 0.002 ms/op
Iteration   3: 3.021 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.027 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (3.014, 3.027, 3.045), stdev = 0.016
  CI (99.9%): [2.735, 3.319] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.478 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.016 ms/op
Iteration   1: 3.892 ±(99.9%) 0.010 ms/op
Iteration   2: 3.918 ±(99.9%) 0.017 ms/op
Iteration   3: 3.885 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.898 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (3.885, 3.898, 3.918), stdev = 0.017
  CI (99.9%): [3.586, 4.211] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.007 ms/op
Iteration   1: 2.962 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.479 ms/op
                 createUser·p0.9999: 16.407 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  8.186 ms/op
                 createUser·p0.9999: 21.266 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.303 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.677 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318937
  mean =      3.009 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32800 
    [ 2.500,  5.000) = 284567 
    [ 5.000,  7.500) = 1130 
    [ 7.500, 10.000) = 198 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.303 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.619 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.191 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.005 ms/op
Iteration   1: 2.882 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.774 ms/op
                 existUser·p0.9999: 12.073 ms/op
                 existUser·p1.00:   12.403 ms/op

Iteration   2: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.882 ms/op
                 existUser·p0.9999: 13.648 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.854 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.805 ms/op
                 existUser·p0.9999: 16.869 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332956
  mean =      2.882 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1615 
    [ 1.250,  2.500) = 40928 
    [ 2.500,  3.750) = 279795 
    [ 3.750,  5.000) = 9223 
    [ 5.000,  6.250) = 840 
    [ 6.250,  7.500) = 265 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.242 ms/op
     p(99.9900) =     15.729 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.336 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.005 ms/op
Iteration   1: 3.025 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  7.660 ms/op
                 getUser·p0.9999: 25.887 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 2.975 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.570 ms/op
                 getUser·p0.9999: 21.537 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.914 ms/op
                 getUser·p0.9999: 31.570 ms/op
                 getUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319106
  mean =      3.008 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26302 
    [ 2.500,  5.000) = 291118 
    [ 5.000,  7.500) = 1396 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      7.306 ms/op
     p(99.9900) =     29.601 ms/op
     p(99.9990) =     31.746 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 4.797 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.010 ms/op
Iteration   1: 3.944 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.465 ms/op
                 listUser·p0.9999: 19.519 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 3.993 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  16.869 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   3: 3.861 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  16.354 ms/op
                 listUser·p0.9999: 18.767 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244052
  mean =      3.932 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3451 
    [ 2.500,  5.000) = 218809 
    [ 5.000,  7.500) = 20583 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      6.885 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     22.040 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.722 ± 7.029  ops/ms
ClientGrpc.existUser                       thrpt       3  11.152 ± 1.793  ops/ms
ClientGrpc.getUser                         thrpt       3  10.722 ± 2.152  ops/ms
ClientGrpc.listUser                        thrpt       3   8.131 ± 3.658  ops/ms
ClientGrpc.createUser                       avgt       3   2.967 ± 0.557   ms/op
ClientGrpc.existUser                        avgt       3   2.854 ± 0.526   ms/op
ClientGrpc.getUser                          avgt       3   3.027 ± 0.292   ms/op
ClientGrpc.listUser                         avgt       3   3.898 ± 0.312   ms/op
ClientGrpc.createUser                     sample  318937   3.009 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.303           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.619           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.398           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  332956   2.882 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.729           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.242           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.729           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.400           ms/op
ClientGrpc.getUser                        sample  319106   3.008 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.740           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.306           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.601           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.850           ms/op
ClientGrpc.listUser                       sample  244052   3.932 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.083           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.885           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.663           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.040           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.855           ms/op
