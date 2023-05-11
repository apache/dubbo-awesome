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
# Warmup Iteration   1: 4.742 ops/ms
# Warmup Iteration   2: 9.312 ops/ms
# Warmup Iteration   3: 10.324 ops/ms
Iteration   1: 10.699 ops/ms
Iteration   2: 10.508 ops/ms
Iteration   3: 10.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.666 ±(99.9%) 2.636 ops/ms [Average]
  (min, avg, max) = (10.508, 10.666, 10.791), stdev = 0.144
  CI (99.9%): [8.030, 13.301] (assumes normal distribution)


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
# Warmup Iteration   1: 8.547 ops/ms
# Warmup Iteration   2: 10.881 ops/ms
# Warmup Iteration   3: 11.376 ops/ms
Iteration   1: 11.105 ops/ms
Iteration   2: 11.295 ops/ms
Iteration   3: 11.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.268 ±(99.9%) 2.749 ops/ms [Average]
  (min, avg, max) = (11.105, 11.268, 11.403), stdev = 0.151
  CI (99.9%): [8.518, 14.017] (assumes normal distribution)


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
# Warmup Iteration   1: 7.168 ops/ms
# Warmup Iteration   2: 10.344 ops/ms
# Warmup Iteration   3: 10.628 ops/ms
Iteration   1: 10.735 ops/ms
Iteration   2: 10.777 ops/ms
Iteration   3: 10.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.706 ±(99.9%) 1.623 ops/ms [Average]
  (min, avg, max) = (10.606, 10.706, 10.777), stdev = 0.089
  CI (99.9%): [9.082, 12.329] (assumes normal distribution)


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
# Warmup Iteration   1: 6.358 ops/ms
# Warmup Iteration   2: 8.105 ops/ms
# Warmup Iteration   3: 8.150 ops/ms
Iteration   1: 8.145 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 8.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.142 ±(99.9%) 1.079 ops/ms [Average]
  (min, avg, max) = (8.081, 8.142, 8.199), stdev = 0.059
  CI (99.9%): [7.063, 9.220] (assumes normal distribution)


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.003 ms/op
Iteration   1: 3.073 ±(99.9%) 0.003 ms/op
Iteration   2: 3.013 ±(99.9%) 0.004 ms/op
Iteration   3: 3.059 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.049 ±(99.9%) 0.575 ms/op [Average]
  (min, avg, max) = (3.013, 3.049, 3.073), stdev = 0.032
  CI (99.9%): [2.474, 3.623] (assumes normal distribution)


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
# Warmup Iteration   1: 3.704 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 2.813 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.003 ms/op
Iteration   1: 2.861 ±(99.9%) 0.004 ms/op
Iteration   2: 2.824 ±(99.9%) 0.004 ms/op
Iteration   3: 2.798 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.828 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (2.798, 2.828, 2.861), stdev = 0.031
  CI (99.9%): [2.254, 3.402] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.757 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.003 ms/op
Iteration   1: 3.015 ±(99.9%) 0.003 ms/op
Iteration   2: 2.965 ±(99.9%) 0.004 ms/op
Iteration   3: 2.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.986 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (2.965, 2.986, 3.015), stdev = 0.026
  CI (99.9%): [2.509, 3.464] (assumes normal distribution)


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.036 ms/op
Iteration   1: 3.881 ±(99.9%) 0.030 ms/op
Iteration   2: 3.870 ±(99.9%) 0.023 ms/op
Iteration   3: 3.814 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.855 ±(99.9%) 0.656 ms/op [Average]
  (min, avg, max) = (3.814, 3.855, 3.881), stdev = 0.036
  CI (99.9%): [3.199, 4.510] (assumes normal distribution)


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
# Warmup Iteration   1: 4.147 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.618 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.280 ms/op
                 createUser·p0.9999: 11.616 ms/op
                 createUser·p1.00:   12.157 ms/op

Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  6.349 ms/op
                 createUser·p0.9999: 14.679 ms/op
                 createUser·p1.00:   15.073 ms/op

Iteration   3: 2.982 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  10.535 ms/op
                 createUser·p0.9999: 23.471 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319431
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26072 
    [ 2.500,  5.000) = 292062 
    [ 5.000,  7.500) = 986 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.410 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     23.750 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.917 ±(99.9%) 0.005 ms/op
Iteration   1: 2.885 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.572 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  6.526 ms/op
                 existUser·p0.9999: 19.265 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   2: 2.916 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.438 ms/op
                 existUser·p0.999:  7.949 ms/op
                 existUser·p0.9999: 12.832 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   3: 2.874 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  6.354 ms/op
                 existUser·p0.9999: 14.217 ms/op
                 existUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331909
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2756 
    [ 1.250,  2.500) = 41599 
    [ 2.500,  3.750) = 275977 
    [ 3.750,  5.000) = 10301 
    [ 5.000,  6.250) = 874 
    [ 6.250,  7.500) = 139 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      6.603 ms/op
     p(99.9900) =     14.395 ms/op
     p(99.9990) =     19.771 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.119 ms/op
                 getUser·p0.9999: 11.795 ms/op
                 getUser·p1.00:   16.171 ms/op

Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.061 ms/op
                 getUser·p0.9999: 21.725 ms/op
                 getUser·p1.00:   21.922 ms/op

Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.542 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  9.108 ms/op
                 getUser·p0.9999: 21.640 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320153
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28496 
    [ 2.500,  5.000) = 290509 
    [ 5.000,  7.500) = 808 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.700 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     21.915 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.010 ms/op
Iteration   1: 3.983 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  13.152 ms/op
                 listUser·p0.9999: 20.937 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.937 ms/op
                 listUser·p0.9999: 17.185 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.878 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.991 ms/op
                 listUser·p0.999:  15.159 ms/op
                 listUser·p0.9999: 26.034 ms/op
                 listUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244097
  mean =      3.930 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5774 
    [ 2.500,  5.000) = 212100 
    [ 5.000,  7.500) = 24803 
    [ 7.500, 10.000) = 1008 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.169 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     26.686 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.666 ± 2.636  ops/ms
ClientGrpc.existUser                       thrpt       3  11.268 ± 2.749  ops/ms
ClientGrpc.getUser                         thrpt       3  10.706 ± 1.623  ops/ms
ClientGrpc.listUser                        thrpt       3   8.142 ± 1.079  ops/ms
ClientGrpc.createUser                       avgt       3   3.049 ± 0.575   ms/op
ClientGrpc.existUser                        avgt       3   2.828 ± 0.574   ms/op
ClientGrpc.getUser                          avgt       3   2.986 ± 0.477   ms/op
ClientGrpc.listUser                         avgt       3   3.855 ± 0.656   ms/op
ClientGrpc.createUser                     sample  319431   3.006 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.604           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.410           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.807           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.904           ms/op
ClientGrpc.existUser                      sample  331909   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.572           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.603           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.395           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.923           ms/op
ClientGrpc.getUser                        sample  320153   2.997 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.542           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.700           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.594           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.922           ms/op
ClientGrpc.listUser                       sample  244097   3.930 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.049           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.169           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.297           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.903           ms/op
