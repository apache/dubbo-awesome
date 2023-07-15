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
# Warmup Iteration   1: 2.836 ops/ms
# Warmup Iteration   2: 6.930 ops/ms
# Warmup Iteration   3: 8.174 ops/ms
Iteration   1: 8.391 ops/ms
Iteration   2: 8.530 ops/ms
Iteration   3: 8.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.482 ±(99.9%) 1.439 ops/ms [Average]
  (min, avg, max) = (8.391, 8.482, 8.530), stdev = 0.079
  CI (99.9%): [7.042, 9.921] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.952 ops/ms
# Warmup Iteration   2: 8.689 ops/ms
# Warmup Iteration   3: 8.891 ops/ms
Iteration   1: 9.090 ops/ms
Iteration   2: 9.257 ops/ms
Iteration   3: 9.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.197 ±(99.9%) 1.703 ops/ms [Average]
  (min, avg, max) = (9.090, 9.197, 9.257), stdev = 0.093
  CI (99.9%): [7.495, 10.900] (assumes normal distribution)


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
# Warmup Iteration   1: 5.633 ops/ms
# Warmup Iteration   2: 8.048 ops/ms
# Warmup Iteration   3: 8.568 ops/ms
Iteration   1: 8.375 ops/ms
Iteration   2: 8.450 ops/ms
Iteration   3: 8.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.403 ±(99.9%) 0.748 ops/ms [Average]
  (min, avg, max) = (8.375, 8.403, 8.450), stdev = 0.041
  CI (99.9%): [7.655, 9.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.219 ops/ms
# Warmup Iteration   2: 5.901 ops/ms
# Warmup Iteration   3: 6.605 ops/ms
Iteration   1: 6.377 ops/ms
Iteration   2: 6.518 ops/ms
Iteration   3: 6.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.374 ±(99.9%) 2.669 ops/ms [Average]
  (min, avg, max) = (6.226, 6.374, 6.518), stdev = 0.146
  CI (99.9%): [3.705, 9.043] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.667 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.004 ms/op
Iteration   1: 4.135 ±(99.9%) 0.002 ms/op
Iteration   2: 3.738 ±(99.9%) 0.002 ms/op
Iteration   3: 3.687 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.853 ±(99.9%) 4.469 ms/op [Average]
  (min, avg, max) = (3.687, 3.853, 4.135), stdev = 0.245
  CI (99.9%): [≈ 0, 8.322] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.095 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.003 ms/op
Iteration   1: 3.548 ±(99.9%) 0.002 ms/op
Iteration   2: 3.424 ±(99.9%) 0.002 ms/op
Iteration   3: 3.389 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.454 ±(99.9%) 1.525 ms/op [Average]
  (min, avg, max) = (3.389, 3.454, 3.548), stdev = 0.084
  CI (99.9%): [1.929, 4.979] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.642 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.002 ms/op
Iteration   1: 4.109 ±(99.9%) 0.004 ms/op
Iteration   2: 3.790 ±(99.9%) 0.003 ms/op
Iteration   3: 3.736 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.878 ±(99.9%) 3.672 ms/op [Average]
  (min, avg, max) = (3.736, 3.878, 4.109), stdev = 0.201
  CI (99.9%): [0.206, 7.551] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.866 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.917 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.989 ±(99.9%) 0.011 ms/op
Iteration   1: 4.820 ±(99.9%) 0.015 ms/op
Iteration   2: 4.748 ±(99.9%) 0.018 ms/op
Iteration   3: 4.932 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.834 ±(99.9%) 1.687 ms/op [Average]
  (min, avg, max) = (4.748, 4.834, 4.932), stdev = 0.092
  CI (99.9%): [3.146, 6.521] (assumes normal distribution)


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
# Warmup Iteration   1: 5.430 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.889 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.012 ms/op
Iteration   1: 3.720 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.762 ms/op
                 createUser·p0.999:  10.797 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   2: 3.685 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  13.189 ms/op
                 createUser·p0.9999: 23.339 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   3: 3.699 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  19.857 ms/op
                 createUser·p0.9999: 25.156 ms/op
                 createUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259354
  mean =      3.701 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6111 
    [ 2.500,  5.000) = 241280 
    [ 5.000,  7.500) = 10405 
    [ 7.500, 10.000) = 1039 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     12.014 ms/op
     p(99.9900) =     24.414 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.001 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.009 ms/op
Iteration   1: 3.435 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  10.303 ms/op
                 existUser·p0.9999: 20.197 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.484 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  10.338 ms/op
                 existUser·p0.9999: 16.902 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   3: 3.384 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  13.130 ms/op
                 existUser·p0.9999: 19.104 ms/op
                 existUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279562
  mean =      3.434 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10094 
    [ 2.500,  5.000) = 262656 
    [ 5.000,  7.500) = 5609 
    [ 7.500, 10.000) = 802 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     11.212 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     20.787 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 5.976 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.010 ms/op
Iteration   1: 3.765 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   6.557 ms/op
                 getUser·p0.999:  12.417 ms/op
                 getUser·p0.9999: 23.675 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   2: 3.729 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  9.699 ms/op
                 getUser·p0.9999: 19.539 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   3: 3.712 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.527 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  10.289 ms/op
                 getUser·p0.9999: 16.691 ms/op
                 getUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257077
  mean =      3.735 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7245 
    [ 2.500,  5.000) = 236106 
    [ 5.000,  7.500) = 12388 
    [ 7.500, 10.000) = 968 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     10.926 ms/op
     p(99.9900) =     22.924 ms/op
     p(99.9990) =     23.967 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 6.170 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.336 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.903 ±(99.9%) 0.018 ms/op
Iteration   1: 4.862 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.078 ms/op
                 listUser·p0.95:   7.070 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  21.135 ms/op
                 listUser·p0.9999: 25.864 ms/op
                 listUser·p1.00:   26.870 ms/op

Iteration   2: 4.842 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   7.004 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  18.739 ms/op
                 listUser·p0.9999: 25.597 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   3: 4.935 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.406 ms/op
                 listUser·p0.95:   7.266 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  21.990 ms/op
                 listUser·p0.9999: 38.765 ms/op
                 listUser·p1.00:   46.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196856
  mean =      4.879 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 132563 
    [ 5.000, 10.000) = 63110 
    [10.000, 15.000) = 768 
    [15.000, 20.000) = 156 
    [20.000, 25.000) = 195 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 10 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.201 ms/op
     p(95.0000) =      7.119 ms/op
     p(99.0000) =      9.142 ms/op
     p(99.9000) =     21.173 ms/op
     p(99.9900) =     37.090 ms/op
     p(99.9990) =     45.627 ms/op
     p(99.9999) =     46.072 ms/op
    p(100.0000) =     46.072 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.482 ± 1.439  ops/ms
ClientGrpc.existUser                       thrpt       3   9.197 ± 1.703  ops/ms
ClientGrpc.getUser                         thrpt       3   8.403 ± 0.748  ops/ms
ClientGrpc.listUser                        thrpt       3   6.374 ± 2.669  ops/ms
ClientGrpc.createUser                       avgt       3   3.853 ± 4.469   ms/op
ClientGrpc.existUser                        avgt       3   3.454 ± 1.525   ms/op
ClientGrpc.getUser                          avgt       3   3.878 ± 3.672   ms/op
ClientGrpc.listUser                         avgt       3   4.834 ± 1.687   ms/op
ClientGrpc.createUser                     sample  259354   3.701 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.793           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.948           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.627           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.014           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.414           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.526           ms/op
ClientGrpc.existUser                      sample  279562   3.434 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.748           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.906           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.212           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.366           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.987           ms/op
ClientGrpc.getUser                        sample  257077   3.735 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.697           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.038           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.332           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.926           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.924           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.052           ms/op
ClientGrpc.listUser                       sample  196856   4.879 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.145           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.201           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.142           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.173           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.090           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          46.072           ms/op
