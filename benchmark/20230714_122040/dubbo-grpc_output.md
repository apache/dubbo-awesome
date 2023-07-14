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
# Warmup Iteration   1: 4.265 ops/ms
# Warmup Iteration   2: 9.597 ops/ms
# Warmup Iteration   3: 10.261 ops/ms
Iteration   1: 10.605 ops/ms
Iteration   2: 10.614 ops/ms
Iteration   3: 10.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.586 ±(99.9%) 0.749 ops/ms [Average]
  (min, avg, max) = (10.539, 10.586, 10.614), stdev = 0.041
  CI (99.9%): [9.837, 11.335] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.152 ops/ms
# Warmup Iteration   2: 10.767 ops/ms
# Warmup Iteration   3: 11.048 ops/ms
Iteration   1: 11.140 ops/ms
Iteration   2: 11.291 ops/ms
Iteration   3: 11.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.197 ±(99.9%) 1.505 ops/ms [Average]
  (min, avg, max) = (11.140, 11.197, 11.291), stdev = 0.082
  CI (99.9%): [9.692, 12.702] (assumes normal distribution)


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
# Warmup Iteration   1: 7.322 ops/ms
# Warmup Iteration   2: 10.324 ops/ms
# Warmup Iteration   3: 10.577 ops/ms
Iteration   1: 10.724 ops/ms
Iteration   2: 10.769 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.738 ±(99.9%) 0.498 ops/ms [Average]
  (min, avg, max) = (10.720, 10.738, 10.769), stdev = 0.027
  CI (99.9%): [10.239, 11.236] (assumes normal distribution)


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
# Warmup Iteration   1: 6.049 ops/ms
# Warmup Iteration   2: 7.931 ops/ms
# Warmup Iteration   3: 8.140 ops/ms
Iteration   1: 8.191 ops/ms
Iteration   2: 8.292 ops/ms
Iteration   3: 8.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.336 ±(99.9%) 3.129 ops/ms [Average]
  (min, avg, max) = (8.191, 8.336, 8.525), stdev = 0.171
  CI (99.9%): [5.208, 11.465] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.004 ms/op
Iteration   1: 3.001 ±(99.9%) 0.003 ms/op
Iteration   2: 2.958 ±(99.9%) 0.004 ms/op
Iteration   3: 2.929 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.963 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (2.929, 2.963, 3.001), stdev = 0.036
  CI (99.9%): [2.301, 3.624] (assumes normal distribution)


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.857 ±(99.9%) 0.005 ms/op
Iteration   1: 2.832 ±(99.9%) 0.002 ms/op
Iteration   2: 2.865 ±(99.9%) 0.003 ms/op
Iteration   3: 2.837 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.845 ±(99.9%) 0.330 ms/op [Average]
  (min, avg, max) = (2.832, 2.845, 2.865), stdev = 0.018
  CI (99.9%): [2.515, 3.174] (assumes normal distribution)


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.002 ms/op
Iteration   1: 3.005 ±(99.9%) 0.002 ms/op
Iteration   2: 3.021 ±(99.9%) 0.004 ms/op
Iteration   3: 3.015 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.013 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (3.005, 3.013, 3.021), stdev = 0.008
  CI (99.9%): [2.867, 3.160] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.797 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.012 ms/op
Iteration   1: 3.920 ±(99.9%) 0.016 ms/op
Iteration   2: 3.863 ±(99.9%) 0.024 ms/op
Iteration   3: 3.834 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.872 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (3.834, 3.872, 3.920), stdev = 0.044
  CI (99.9%): [3.068, 4.677] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 3.046 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.815 ms/op
                 createUser·p0.9999: 14.885 ms/op
                 createUser·p1.00:   15.909 ms/op

Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.589 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  13.742 ms/op
                 createUser·p0.9999: 17.129 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  10.123 ms/op
                 createUser·p0.9999: 18.758 ms/op
                 createUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316853
  mean =      3.028 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 859 
    [ 1.250,  2.500) = 22645 
    [ 2.500,  3.750) = 276831 
    [ 3.750,  5.000) = 14750 
    [ 5.000,  6.250) = 970 
    [ 6.250,  7.500) = 348 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 61 
    [17.500, 18.750) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      9.866 ms/op
     p(99.9900) =     18.131 ms/op
     p(99.9990) =     19.245 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.856 ±(99.9%) 0.007 ms/op
Iteration   1: 2.884 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.402 ms/op
                 existUser·p0.9999: 14.221 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   2: 2.856 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.119 ms/op
                 existUser·p0.9999: 18.743 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   3: 2.879 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  10.807 ms/op
                 existUser·p0.9999: 27.263 ms/op
                 existUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334251
  mean =      2.873 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44834 
    [ 2.500,  5.000) = 287818 
    [ 5.000,  7.500) = 1229 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.977 ms/op
     p(99.9900) =     19.741 ms/op
     p(99.9990) =     27.514 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.779 ms/op
                 getUser·p0.999:  8.356 ms/op
                 getUser·p0.9999: 11.873 ms/op
                 getUser·p1.00:   12.222 ms/op

Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.254 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.683 ms/op
                 getUser·p0.9999: 14.727 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.759 ms/op
                 getUser·p0.9999: 16.187 ms/op
                 getUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321639
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1520 
    [ 1.250,  2.500) = 28505 
    [ 2.500,  3.750) = 277074 
    [ 3.750,  5.000) = 12432 
    [ 5.000,  6.250) = 1231 
    [ 6.250,  7.500) = 417 
    [ 7.500,  8.750) = 228 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.254 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.069 ms/op
     p(99.9900) =     15.401 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 5.208 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.010 ms/op
Iteration   1: 3.876 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.634 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 18.145 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   2: 3.903 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  14.156 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 3.951 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.849 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245417
  mean =      3.910 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3342 
    [ 2.500,  5.000) = 223041 
    [ 5.000,  7.500) = 17698 
    [ 7.500, 10.000) = 834 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.568 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     21.270 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.586 ± 0.749  ops/ms
ClientGrpc.existUser                       thrpt       3  11.197 ± 1.505  ops/ms
ClientGrpc.getUser                         thrpt       3  10.738 ± 0.498  ops/ms
ClientGrpc.listUser                        thrpt       3   8.336 ± 3.129  ops/ms
ClientGrpc.createUser                       avgt       3   2.963 ± 0.661   ms/op
ClientGrpc.existUser                        avgt       3   2.845 ± 0.330   ms/op
ClientGrpc.getUser                          avgt       3   3.013 ± 0.147   ms/op
ClientGrpc.listUser                         avgt       3   3.872 ± 0.805   ms/op
ClientGrpc.createUser                     sample  316853   3.028 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.589           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.866           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.131           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.857           ms/op
ClientGrpc.existUser                      sample  334251   2.873 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.592           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.314           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.977           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.741           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.558           ms/op
ClientGrpc.getUser                        sample  321639   2.985 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.254           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.069           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.401           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.367           ms/op
ClientGrpc.listUser                       sample  245417   3.910 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.786           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.568           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.283           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.791           ms/op
