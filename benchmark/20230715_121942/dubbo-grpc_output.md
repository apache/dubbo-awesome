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
# Warmup Iteration   1: 4.157 ops/ms
# Warmup Iteration   2: 9.031 ops/ms
# Warmup Iteration   3: 10.024 ops/ms
Iteration   1: 10.557 ops/ms
Iteration   2: 10.367 ops/ms
Iteration   3: 10.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.443 ±(99.9%) 1.829 ops/ms [Average]
  (min, avg, max) = (10.367, 10.443, 10.557), stdev = 0.100
  CI (99.9%): [8.615, 12.272] (assumes normal distribution)


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
# Warmup Iteration   1: 7.913 ops/ms
# Warmup Iteration   2: 10.616 ops/ms
# Warmup Iteration   3: 11.004 ops/ms
Iteration   1: 11.450 ops/ms
Iteration   2: 11.122 ops/ms
Iteration   3: 11.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.246 ±(99.9%) 3.240 ops/ms [Average]
  (min, avg, max) = (11.122, 11.246, 11.450), stdev = 0.178
  CI (99.9%): [8.006, 14.487] (assumes normal distribution)


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
# Warmup Iteration   1: 6.706 ops/ms
# Warmup Iteration   2: 10.220 ops/ms
# Warmup Iteration   3: 10.350 ops/ms
Iteration   1: 10.665 ops/ms
Iteration   2: 10.526 ops/ms
Iteration   3: 10.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.557 ±(99.9%) 1.763 ops/ms [Average]
  (min, avg, max) = (10.479, 10.557, 10.665), stdev = 0.097
  CI (99.9%): [8.794, 12.320] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.628 ops/ms
# Warmup Iteration   2: 7.786 ops/ms
# Warmup Iteration   3: 7.960 ops/ms
Iteration   1: 7.972 ops/ms
Iteration   2: 8.082 ops/ms
Iteration   3: 7.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.993 ±(99.9%) 1.467 ops/ms [Average]
  (min, avg, max) = (7.925, 7.993, 8.082), stdev = 0.080
  CI (99.9%): [6.526, 9.460] (assumes normal distribution)


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.003 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.065 ±(99.9%) 0.003 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.043 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (3.016, 3.043, 3.065), stdev = 0.025
  CI (99.9%): [2.582, 3.505] (assumes normal distribution)


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
# Warmup Iteration   1: 3.821 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.004 ms/op
Iteration   1: 2.863 ±(99.9%) 0.002 ms/op
Iteration   2: 2.887 ±(99.9%) 0.003 ms/op
Iteration   3: 2.905 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.885 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (2.863, 2.885, 2.905), stdev = 0.021
  CI (99.9%): [2.501, 3.269] (assumes normal distribution)


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.005 ms/op
Iteration   1: 3.018 ±(99.9%) 0.005 ms/op
Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
Iteration   3: 2.988 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.011 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (2.988, 3.011, 3.027), stdev = 0.021
  CI (99.9%): [2.636, 3.386] (assumes normal distribution)


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
# Warmup Iteration   1: 4.926 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.027 ms/op
Iteration   1: 4.040 ±(99.9%) 0.025 ms/op
Iteration   2: 3.999 ±(99.9%) 0.013 ms/op
Iteration   3: 3.984 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.008 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (3.984, 4.008, 4.040), stdev = 0.029
  CI (99.9%): [3.477, 4.538] (assumes normal distribution)


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  8.066 ms/op
                 createUser·p0.9999: 12.272 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.438 ms/op
                 createUser·p0.9999: 20.594 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.436 ms/op
                 createUser·p0.9999: 18.678 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317400
  mean =      3.023 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20858 
    [ 2.500,  5.000) = 295138 
    [ 5.000,  7.500) = 1072 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.682 ms/op
     p(99.9900) =     19.752 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  8.815 ms/op
                 existUser·p0.9999: 13.059 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.905 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.472 ms/op
                 existUser·p0.9999: 19.365 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   3: 2.917 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  6.605 ms/op
                 existUser·p0.9999: 17.565 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329493
  mean =      2.915 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1062 
    [ 1.250,  2.500) = 38884 
    [ 2.500,  3.750) = 281215 
    [ 3.750,  5.000) = 7386 
    [ 5.000,  6.250) = 507 
    [ 6.250,  7.500) = 129 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =      7.070 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     19.553 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.441 ms/op
                 getUser·p0.99:   4.063 ms/op
                 getUser·p0.999:  10.122 ms/op
                 getUser·p0.9999: 17.470 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  6.610 ms/op
                 getUser·p0.9999: 17.067 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  6.401 ms/op
                 getUser·p0.9999: 17.953 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316278
  mean =      3.037 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 15974 
    [ 2.500,  3.750) = 288369 
    [ 3.750,  5.000) = 10627 
    [ 5.000,  6.250) = 613 
    [ 6.250,  7.500) = 190 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      6.633 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     18.924 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 5.423 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.011 ms/op
Iteration   1: 4.031 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.231 ms/op
                 listUser·p0.9999: 19.962 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   2: 3.973 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.973 ms/op
                 listUser·p0.9999: 16.744 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   3: 3.858 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.079 ms/op
                 listUser·p0.9999: 20.910 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242805
  mean =      3.953 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1596 
    [ 2.500,  5.000) = 220220 
    [ 5.000,  7.500) = 19572 
    [ 7.500, 10.000) = 987 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     19.937 ms/op
     p(99.9990) =     21.402 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.443 ± 1.829  ops/ms
ClientGrpc.existUser                       thrpt       3  11.246 ± 3.240  ops/ms
ClientGrpc.getUser                         thrpt       3  10.557 ± 1.763  ops/ms
ClientGrpc.listUser                        thrpt       3   7.993 ± 1.467  ops/ms
ClientGrpc.createUser                       avgt       3   3.043 ± 0.461   ms/op
ClientGrpc.existUser                        avgt       3   2.885 ± 0.384   ms/op
ClientGrpc.getUser                          avgt       3   3.011 ± 0.375   ms/op
ClientGrpc.listUser                         avgt       3   4.008 ± 0.531   ms/op
ClientGrpc.createUser                     sample  317400   3.023 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.744           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.682           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.752           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.037           ms/op
ClientGrpc.existUser                      sample  329493   2.915 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.603           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.070           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.760           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.661           ms/op
ClientGrpc.getUser                        sample  316278   3.037 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.753           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.190           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.633           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.334           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.104           ms/op
ClientGrpc.listUser                       sample  242805   3.953 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.967           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.909           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.937           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.529           ms/op
